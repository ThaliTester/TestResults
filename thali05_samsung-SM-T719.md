#### Test 85019474526c333_thali05_samsung-SM-T719 Logs


```
--------- beginning of system
09-13 12:25:24.976  1258  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,--------- beginning of main
09-13 12:25:25.486  5997  5997 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-13 12:25:25.496  5997  5997 D AndroidRuntime: CheckJNI is OFF
09-13 12:25:25.496  5997  5997 D AndroidRuntime: readGMSProperty: start
09-13 12:25:25.496  5997  5997 D AndroidRuntime: readGMSProperty: already setted!!
09-13 12:25:25.496  5997  5997 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-13 12:25:25.496  5997  5997 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-13 12:25:25.496  5997  5997 D AndroidRuntime: readGMSProperty: end
09-13 12:25:25.496  5997  5997 D AndroidRuntime: addProductProperty: start
09-13 12:25:25.516  5997  5997 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-13 12:25:25.556  5997  5997 I Radio-JNI: register_android_hardware_Radio DONE
09-13 12:25:25.556  5997  5997 E AffinityControl: AffinityControl: registerfunction enter
09-13 12:25:25.576  5997  5997 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-13 12:25:25.596  1258  1303 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
09-13 12:25:25.616  1258  1303 D GameManagerService: identifyGamePackage. com.test.thalitest
09-13 12:25:25.616  1258  1303 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-13 12:25:25.626  1258  1303 D ActivityManager: mDVFSHelper.acquire()
09-13 12:25:25.626  1258  1303 V WindowManager: addAppToken: AppWindowToken{d0bb4e3b9 token=Token{6915180 ActivityRecord{f1d4e03 u0 com.test.thalitest/.MainActivity t19}}} to stack=2 task=19 at 0
09-13 12:25:25.636  1258  1416 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{f8250f1 V.E...... R.....ID 0,0-0,0}
09-13 12:25:25.636  1258  1416 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-13 12:25:25.636  1258  1303 I ActivityManager: Start proc 6006:com.test.thalitest/u0a136 for activity com.test.thalitest/.MainActivity
09-13 12:25:25.646  1258  1303 D InputDispatcher: Focused application set to: xxxx
09-13 12:25:25.646  6006  6006 E Zygote  : v2
09-13 12:25:25.646  6006  6006 I libpersona: KNOX_SDCARD checking this for 10136
09-13 12:25:25.646  6006  6006 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:25.646  1258  1621 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-13 12:25:25.646  6006  6006 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-13 12:25:25.646  5997  5997 D AndroidRuntime: Shutting down VM
09-13 12:25:25.646  6006  6006 E Zygote  : accessInfo : 0
09-13 12:25:25.646  6006  6006 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-13 12:25:25.656   445   445 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
09-13 12:25:25.666  3604  3604 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-13 12:25:25.666  3604  3604 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-13 12:25:25.676  3604  3614 V ViewRootImpl: dispatchResized mReportNextDraw cancel... mWinFrame : Rect(256, 1016 - 1280, 1080)  frame : Rect(256, 992 - 1280, 1056) window com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
09-13 12:25:25.676  3604  3615 V ViewRootImpl: dispatchResized mReportNextDraw cancel... mWinFrame : Rect(256, 461 - 1280, 1634)  frame : Rect(256, 437 - 1280, 1610) window com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
09-13 12:25:25.676  6006  6006 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:25:25.676  6006  6006 D ActivityThread: Added TimaKeyStore provider
09-13 12:25:25.676  1258  1416 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-13 12:25:25.676  1258  1258 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-13 12:25:25.676  1258  1416 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 48 - 0, 0) vi=Rect(0, 48 - 0, 0) or=1
09-13 12:25:25.676  1258  1258 I KnoxTimeoutHandler: SD activityfalse
09-13 12:25:25.676  1258  1304 D ActivityManager:  Launching com.test.thalitest, updated priority
09-13 12:25:25.676  1997  1997 V ActivityThread: updateVisibility : ActivityRecord{55c8640 token=android.os.BinderProxy@cd43d6f {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-13 12:25:25.686  1258  1377 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-13 12:25:25.686  1258  1258 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-13 12:25:25.696  3604  3604 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-13 12:25:25.696  3604  3604 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-13 12:25:25.696  3604  3604 V ActivityThread: updateVisibility : ActivityRecord{aa671a0 token=android.os.BinderProxy@53ece02 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-13 12:25:25.706   445   466 I SurfaceFlinger: id=9 Removed MauncherAct (5/14)
09-13 12:25:25.706   445   460 I SurfaceFlinger: id=9 Removed MauncherAct (-2/14)
09-13 12:25:25.706  1997  1997 D Launcher: onTrimMemory. Level: 20
09-13 12:25:25.716   445   466 I SurfaceFlinger: id=17 Removed VSBConnecti (6/13)
09-13 12:25:25.716   445   466 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/13)
09-13 12:25:25.726   445  1957 I SurfaceFlinger: id=16 Removed VSBConnecti (6/12)
09-13 12:25:25.726   445   460 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/12)
09-13 12:25:25.726  1258  1416 V WindowStateAnimator: Finishing drawing window Window{f824357 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
,09-13 12:25:25.996  1258  1304 I WindowManager: Screenshot max retries 4 of Token{6915180 ActivityRecord{f1d4e03 u0 com.test.thalitest/.MainActivity t19}} appWin=Window{f824357 u0 d0 Starting com.test.thalitest} drawState=2
,09-13 12:25:25.996  1258  1621 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,09-13 12:25:26.006  1258  3539 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-13 12:25:26.016  1258  3539 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-13 12:25:26.046  1258  2011 W ActivityManager: Permission Denial: getCurrentUser() from pid=6006, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
,09-13 12:25:26.056  6006  6006 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-13 12:25:26.056  6006  6006 D RelationGraph: garbageCollect()
,09-13 12:25:26.076  1258  2586 W ActivityManager: Permission Denial: getCurrentUser() from pid=6006, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
,09-13 12:25:26.086  6006  6006 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
,09-13 12:25:26.116  6006  6006 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-13 12:25:26.136  6006  6006 I cr_LibraryLoader: Time to load native libraries: 10 ms (timestamps 2236-2246)
,09-13 12:25:26.136  6006  6006 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
,09-13 12:25:26.166  6006  6021 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,09-13 12:25:26.166  6006  6006 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {caf73aa}
,09-13 12:25:26.166  6006  6006 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
,09-13 12:25:26.176  6006  6006 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 12:25:26.196  6006  6006 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,09-13 12:25:26.266  6006  6006 I Adreno  : QUALCOMM build                   : 971aff5, Ic07f1cdce3
09-13 12:25:26.266  6006  6006 I Adreno  : Build Date                       : 03/29/16
09-13 12:25:26.266  6006  6006 I Adreno  : OpenGL ES Shader Compiler Version: XE031.06.00.02
09-13 12:25:26.266  6006  6006 I Adreno  : Local Branch                     : 
09-13 12:25:26.266  6006  6006 I Adreno  : Remote Branch                    : refs/tags/AU_LINUX_ANDROID_LA.BR.1.3.3.C2.06.00.01.205.077
09-13 12:25:26.266  6006  6006 I Adreno  : Remote Branch                    : NONE
09-13 12:25:26.266  6006  6006 I Adreno  : Reconstruct Branch               : NOTHING
,09-13 12:25:26.336  1258  2391 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10136
09-13 12:25:26.336  1258  2391 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:851 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29617 com.android.server.am.ActivityManagerService.registerReceiver:22639 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3995 
,09-13 12:25:26.396  6006  6006 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,09-13 12:25:26.406  6006  6006 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-13 12:25:26.406  6006  6006 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,09-13 12:25:26.426  6006  6006 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-13 12:25:26.466  6006  6006 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-13 12:25:26.466  6006  6006 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{239a37b I.E...... R.....ID 0,0-0,0}
,09-13 12:25:26.476  6006  6045 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-13 12:25:26.476  1258  1303 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-13 12:25:26.476  1258  1303 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-13 12:25:26.476  1258  1258 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-13 12:25:26.476  1258  1258 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-13 12:25:26.486  6006  6021 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,09-13 12:25:26.496  6006  6006 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10136, CallingPid : 6006
,09-13 12:25:26.506  1258  1303 D ConnectivityService: listenForNetwork for Listen from uid/pid:10136/6006 for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 12:25:26.506  1258  1630 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
09-13 12:25:26.506  1258  1630 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,fe80::4678:3eff:feeb:95ef/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-13 12:25:26.506  1258  1630 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
09-13 12:25:26.506  1258  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-13 12:25:26.506  1258  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
09-13 12:25:26.506  1258  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-13 12:25:26.506  1258  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,09-13 12:25:26.506  1258  1630 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-13 12:25:26.516  6006  6006 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-13 12:25:26.526   445   445 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
,09-13 12:25:26.536  6006  6045 I OpenGLRenderer: Initialized EGL, version 1.4
,09-13 12:25:26.556  6006  6006 V ActivityThread: updateVisibility : ActivityRecord{b457562 token=android.os.BinderProxy@86235d9 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-13 12:25:26.566  6006  6006 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 48 - 0, 0) vi=Rect(0, 48 - 0, 0) or=1
,09-13 12:25:26.596  6006  6045 E libGLESv2: HWUI Protection: wrong call from hwui context F: ES3-glCreateProgramSEC
,09-13 12:25:26.636  1258  2011 V WindowStateAnimator: Finishing drawing window Window{5b54ea4 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,09-13 12:25:26.636  6006  6006 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@86235d9 time:102745
,09-13 12:25:26.636  1258  1416 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-13 12:25:26.646  1258  1416 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +648ms (total +1s13ms)
09-13 12:25:26.646  1258  1258 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-13 12:25:26.646  1258  1416 D ActivityManager: mDVFSHelper.release()
09-13 12:25:26.646  1258  1416 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{f1d4e03 u0 com.test.thalitest/.MainActivity t19} time:102751
09-13 12:25:26.646  1258  1416 D ViewRootImpl: #3 mView = null
09-13 12:25:26.646   445  1957 I SurfaceFlinger: id=18 Removed uhalitest (6/12)
,09-13 12:25:26.646   445   460 I SurfaceFlinger: id=18 Removed uhalitest (-2/12)
09-13 12:25:26.646  1258  1258 I KnoxTimeoutHandler: SD activityfalse
09-13 12:25:26.646  1258  1258 I KnoxTimeoutHandler: Fullscreen and mCurrent is not KNOX user. Hence hide keyguard
,09-13 12:25:26.656  6006  6050 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 12:25:26.696  6006  6006 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6006
,09-13 12:25:26.876  6006  6006 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 12:25:27.006  6006  6057 D jxcore_app_log: JniHelper::setJavaVM(0xf50bc000), pthread_self() = -623904464
,09-13 12:25:27.006  6006  6057 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 12:25:27.006  6006  6057 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 12:25:27.006  6006  6057 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 12:25:27.006  6006  6057 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 12:25:27.006  6006  6057 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-13 12:25:27.006  6006  6057 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@376616b added. We now have 1 listener(s)
09-13 12:25:27.016  6006  6057 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:EB:95:EE
09-13 12:25:27.016  6006  6057 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-13 12:25:27.016  6006  6057 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 12:25:27.016  6006  6057 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 12:25:27.016  6006  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 12:25:27.016  6006  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 12:25:27.016  6006  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 12:25:27.016  6006  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:78:3E:EB:95:EE
09-13 12:25:27.016  6006  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 12:25:27.016  6006  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 12:25:27.016  6006  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 12:25:27.016  6006  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 12:25:27.016  6006  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 12:25:27.016  6006  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 12:25:27.016  6006  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 12:25:27.016  6006  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 12:25:27.016  6006  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 12:25:27.016  6006  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-13 12:25:27.016  6006  6057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a809c86 added. We now have 1 listener(s)
09-13 12:25:27.016  6006  6057 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 12:25:27.016  6006  6057 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 12:25:27.016  6006  6057 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-13 12:25:27.026  6006  6057 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 12:25:27.026  6006  6057 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 12:25:27.026  6006  6057 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-13 12:25:27.026  6006  6057 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 12:25:27.026  6006  6057 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:EB:95:EE
09-13 12:25:27.026  6006  6057 D BluetoothAdapter: STATE_ON
09-13 12:25:27.036  6006  6057 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-13 12:25:27.036  6006  6057 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:25:27.036  6006  6057 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:25:27.036  6006  6057 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:25:27.036  6006  6057 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:25:27.036  6006  6057 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:25:27.036  6006  6057 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:25:27.036  6006  6057 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:25:27.036  6006  6057 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 12:25:27.036  6006  6057 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 12:25:27.036  6006  6057 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 12:25:27.036  6006  6057 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 12:25:27.036  6006  6006 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:25:27.036  6006  6006 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:25:27.056  6006  6006 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 12:25:27.416  6006  6058 W jxcore-log: Initializing JXcore engine
09-13 12:25:27.416  6006  6058 W jxcore-log: JXcore engine is ready
,09-13 12:25:27.436  2560  2560 E audit   : type=1400 msg=audit(1473762327.436:271): avc:  denied  { ioctl } for  pid=6058 comm="Thread-112" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5369 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-13 12:25:27.436  2560  2560 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-13 12:25:27.436  2560  2560 E audit   : type=1300 msg=audit(1473762327.436:271): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=7 a1=5451 a2=3 a3=da37f3c8 items=0 ppid=587 pid=6058 auid=4294967295 uid=10136 gid=10136 euid=10136 suid=10136 fsuid=10136 egid=10136 sgid=10136 fsgid=10136 ses=4294967295 tty=(none) comm="Thread-112" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-13 12:25:27.436  2560  2560 E audit   : type=1327 msg=audit(1473762327.436:271): proctitle="com.test.thalitest"
09-13 12:25:27.436  2560  2560 E audit   : type=1320 msg=audit(1473762327.436:271): 
,09-13 12:25:27.446  2560  2560 E audit   : type=1400 msg=audit(1473762327.436:272): avc:  denied  { ioctl } for  pid=6058 comm="Thread-112" path="socket:[46936]" dev="sockfs" ino=46936 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-13 12:25:27.446  2560  2560 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-13 12:25:27.446  2560  2560 E audit   : type=1300 msg=audit(1473762327.436:272): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3c a1=5451 a2=3 a3=da37f3c8 items=0 ppid=587 pid=6058 auid=4294967295 uid=10136 gid=10136 euid=10136 suid=10136 fsuid=10136 egid=10136 sgid=10136 fsgid=10136 ses=4294967295 tty=(none) comm="Thread-112" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-13 12:25:27.446  2560  2560 E audit   : type=1327 msg=audit(1473762327.436:272): proctitle="com.test.thalitest"
09-13 12:25:27.446  2560  2560 E audit   : type=1320 msg=audit(1473762327.436:272): 
,09-13 12:25:27.446  6006  6058 W jxcore-log: Starting JXcore engine
,09-13 12:25:27.486  1794  1794 D Recents : onTaskStackChanged
,09-13 12:25:27.506  6006  6058 W jxcore-log: Platform android
09-13 12:25:27.506  6006  6058 W jxcore-log: 
09-13 12:25:27.506  6006  6058 W jxcore-log: Process ARCH arm
09-13 12:25:27.506  6006  6058 W jxcore-log: 
,09-13 12:25:27.596  6006  6058 I jxcore-log: JXcore Cordova bridge is ready!
09-13 12:25:27.596  6006  6058 I jxcore-log: 
09-13 12:25:27.596  6006  6058 W jxcore-log: JXcore engine is started
,09-13 12:25:27.596  6006  6057 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-13 12:25:27.596  6006  6006 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 12:25:28.636  1258  1663 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/19_task.xml.bak
,09-13 12:25:29.026  1258  3539 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-13 12:25:31.396  1258  3539 D SSRM:s  : SIOP:: AP = 350, PST = 359 (W:10), CP = 43, LCD = 0
,09-13 12:25:31.396  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:25:31.636  1258  1833 E Watchdog: !@Sync 3 [09-13 12:25:31.645]
,09-13 12:25:31.646  1258  1589 V AlarmManager: Expired Alarm result :4
,09-13 12:25:31.646  1258  1377 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{49718e6 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9847c17 1865:com.google.android.gms.persistent/u0a10}
,09-13 12:25:31.656  1258  1303 V AlarmManager:  remove PendingIntent] PendingIntent{5cfde27: PendingIntentRecord{e1daaab com.google.android.gms broadcastIntent}}
,09-13 12:25:31.746  1258  2011 V AlarmManager:  remove PendingIntent] PendingIntent{46faa7d: PendingIntentRecord{e1daaab com.google.android.gms broadcastIntent}}
,09-13 12:25:31.866  1865  6061 I VacuumService: Vacuum at: now=1473762331872 tag=VacuumService
,09-13 12:25:31.906  1258  1986 V AlarmManager:  remove PendingIntent] PendingIntent{a347e40: PendingIntentRecord{e1daaab com.google.android.gms broadcastIntent}}
,09-13 12:25:32.596  1258  2215 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 12:25:32.596  1258  2215 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4359, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 12:25:32.596  1258  2215 D BatteryService: online:4, current avg:10, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-132
,09-13 12:25:32.596  1258  1258 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:25:32.606  1714  1714 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:25:32.606  1714  1714 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:25:32.606  1714  1714 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-13 12:25:32.606  2552  2552 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:25:32.606  2552  3097 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:25:32.626  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-13 12:25:32.626  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:25:32.626  1714  1714 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:25:35.676  1258  1424 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-13 12:25:35.696  1258  1424 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-13 12:25:35.826  6006  6058 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 12:25:35.826  6006  6058 I jxcore-log: 
,09-13 12:25:35.826  6006  6058 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 12:25:35.826  6006  6058 I jxcore-log: 
,09-13 12:25:35.836  6006  6058 D BluetoothAdapter: STATE_ON
,09-13 12:25:35.836  6006  6058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:25:35.836  6006  6058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:25:35.836  6006  6058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:25:35.836  6006  6058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:25:35.836  6006  6058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:25:35.836  6006  6058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:25:35.836  6006  6058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:25:35.836  6006  6058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:25:35.836  6006  6058 D BluetoothAdapter: STATE_ON
,09-13 12:25:35.846  6006  6058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 12:25:35.846  6006  6058 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 12:25:35.846  6006  6058 I jxcore-log: 
,09-13 12:25:35.846  6006  6058 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 12:25:35.846  6006  6058 I jxcore-log: 
,09-13 12:25:36.056  6006  6058 I jxcore-log: Running unit tests
09-13 12:25:36.056  6006  6058 I jxcore-log: 
,09-13 12:25:36.056  6006  6058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 12:25:36.056  6006  6058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4d4b3a added. We now have 2 listener(s)
09-13 12:25:36.056  6006  6058 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-13 12:25:36.056  6006  6058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 12:25:36.056  6006  6058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 12:25:36.056  6006  6058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 12:25:36.056  6006  6058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b0e3eb added. We now have 2 listener(s)
09-13 12:25:36.056  6006  6058 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 12:25:36.056  6006  6058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 12:25:36.056  6006  6058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 12:25:36.066  6006  6058 D BluetoothAdapter: STATE_ON
,09-13 12:25:36.076  6006  6058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:25:36.076  6006  6058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:25:36.076  6006  6058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:25:36.076  6006  6058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:25:36.076  6006  6058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:25:36.076  6006  6058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:25:36.076  6006  6058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:25:36.076  6006  6058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:25:36.076  6006  6058 D BluetoothAdapter: STATE_ON
,09-13 12:25:36.076  6006  6058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 12:25:36.076  6006  6058 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 12:25:36.076  6006  6058 D executeNativeTests: Running unit tests
,09-13 12:25:36.086  6006  6006 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:25:36.086  6006  6006 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-13 12:25:36.106  6006  6058 I jxcore-log: Total number of executed tests:  1,
09-13 12:25:36.106  6006  6058 I jxcore-log: 
09-13 12:25:36.106  6006  6058 I jxcore-log: Number of passed tests:  1
09-13 12:25:36.106  6006  6058 I jxcore-log: 
09-13 12:25:36.106  6006  6058 I jxcore-log: Number of failed tests:  0
09-13 12:25:36.106  6006  6058 I jxcore-log: 
09-13 12:25:36.106  6006  6058 I jxcore-log: Number of ignored tests:  0
09-13 12:25:36.106  6006  6058 I jxcore-log: ,
09-13 12:25:36.106  6006  6058 I jxcore-log: Total duration:  2
09-13 12:25:36.106  6006  6058 I jxcore-log: 
09-13 12:25:36.106  6006  6058 I jxcore-log: Unit Test app is loaded
09-13 12:25:36.106  6006  6058 I jxcore-log: 
,09-13 12:25:36.116  6006  6058 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:25:36.116  6006  6058 I jxcore-log: 
,09-13 12:25:36.116  6006  6058 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
09-13 12:25:36.116  6006  6058 I jxcore-log: 
09-13 12:25:36.116  6006  6058 I jxcore-log: My device name is: samsung-SM-T719
09-13 12:25:36.116  6006  6058 I jxcore-log: 
09-13 12:25:36.116  6006  6058 I jxcore-log: WARN testUtils: myNameCallback not set!
09-13 12:25:36.116  6006  6058 I jxcore-log: 
09-13 12:25:36.116  6006  6058 I jxcore-log: Running for WIFI network type
09-13 12:25:36.116  6006  6058 I jxcore-log: 
,09-13 12:25:36.126  6006  6006 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-13 12:25:37.606  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-13 12:25:37.606  6006  6058 I jxcore-log: 
,09-13 12:25:37.646   715   715 I MSM-irqbalance: Decided to move IRQ215 from CPU1 to CPU3
,09-13 12:25:37.876  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-13 12:25:37.876  6006  6058 I jxcore-log: 
,09-13 12:25:37.896  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-13 12:25:37.896  6006  6058 I jxcore-log: 
,09-13 12:25:38.736  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-13 12:25:38.736  6006  6058 I jxcore-log: 
,09-13 12:25:38.876  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-13 12:25:38.876  6006  6058 I jxcore-log: 
,09-13 12:25:38.876  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-13 12:25:38.876  6006  6058 I jxcore-log: 
,09-13 12:25:38.886  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-13 12:25:38.886  6006  6058 I jxcore-log: 
,09-13 12:25:38.926  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-13 12:25:38.926  6006  6058 I jxcore-log: 
,09-13 12:25:39.056  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-13 12:25:39.056  6006  6058 I jxcore-log: 
,09-13 12:25:39.056  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-13 12:25:39.056  6006  6058 I jxcore-log: 
,09-13 12:25:39.496  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
09-13 12:25:39.496  6006  6058 I jxcore-log: 
,09-13 12:25:39.596  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-13 12:25:39.596  6006  6058 I jxcore-log: 
,09-13 12:25:39.796  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-13 12:25:39.796  6006  6058 I jxcore-log: 
,09-13 12:25:39.796  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-13 12:25:39.796  6006  6058 I jxcore-log: 
,09-13 12:25:39.806  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-13 12:25:39.806  6006  6058 I jxcore-log: 
,09-13 12:25:39.806  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-13 12:25:39.806  6006  6058 I jxcore-log: 
,09-13 12:25:39.826  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-13 12:25:39.826  6006  6058 I jxcore-log: 
,09-13 12:25:39.856  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-13 12:25:39.856  6006  6058 I jxcore-log: 
,09-13 12:25:39.856  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-13 12:25:39.856  6006  6058 I jxcore-log: 
,09-13 12:25:39.866  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-13 12:25:39.866  6006  6058 I jxcore-log: 
,09-13 12:25:39.876  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-13 12:25:39.876  6006  6058 I jxcore-log: 
,09-13 12:25:39.876  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-13 12:25:39.876  6006  6058 I jxcore-log: 
,09-13 12:25:39.886  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-13 12:25:39.886  6006  6058 I jxcore-log: 
,09-13 12:25:39.896  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-13 12:25:39.896  6006  6058 I jxcore-log: 
,09-13 12:25:39.906  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-13 12:25:39.906  6006  6058 I jxcore-log: 
,09-13 12:25:39.916  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-13 12:25:39.916  6006  6058 I jxcore-log: 
,09-13 12:25:39.926  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-13 12:25:39.926  6006  6058 I jxcore-log: 
,09-13 12:25:39.936  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-13 12:25:39.936  6006  6058 I jxcore-log: 
,09-13 12:25:39.946  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-13 12:25:39.946  6006  6058 I jxcore-log: 
,09-13 12:25:39.946  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-13 12:25:39.946  6006  6058 I jxcore-log: 
,09-13 12:25:39.956  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-13 12:25:39.956  6006  6058 I jxcore-log: 
,09-13 12:25:39.966  6006  6058 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-13 12:25:39.966  6006  6058 I jxcore-log: 
,09-13 12:25:39.976  6006  6058 D BluetoothAdapter: STATE_ON
,09-13 12:25:39.976  6006  6058 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-13 12:25:39.976  6006  6058 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-13 12:25:39.976  6006  6058 I jxcore-log: 
,09-13 12:25:39.976  6006  6058 I jxcore-log: ThaliTestRunner :: Running ThaliTape,
09-13 12:25:39.976  6006  6058 I jxcore-log: 
,09-13 12:25:39.986  6006  6058 I jxcore-log: ThaliTape :: Started ThaliTape
09-13 12:25:39.986  6006  6058 I jxcore-log: 
,09-13 12:25:39.986  6006  6058 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/,
09-13 12:25:39.986  6006  6058 I jxcore-log: 
,09-13 12:25:40.046  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error,
09-13 12:25:40.046  6006  6058 I jxcore-log: 
,09-13 12:25:40.046  6006  6058 I jxcore-log: websocket error
09-13 12:25:40.046  6006  6058 I jxcore-log: 
09-13 12:25:40.046  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:25:40.046  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
,09-13 12:25:40.046  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:25:40.046  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:25:40.046  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:25:40.046  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:25:40.046  6006  6058 I jxcore-log: 
,09-13 12:25:41.416  1258  3539 D SSRM:s  : SIOP:: AP = 370, PST = 360 (W:11), CP = 46, LCD = 0
,09-13 12:25:41.416  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:25:41.546  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:25:41.546  6006  6058 I jxcore-log: 
09-13 12:25:41.546  6006  6058 I jxcore-log: websocket error
09-13 12:25:41.546  6006  6058 I jxcore-log: 
09-13 12:25:41.546  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:25:41.546  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:25:41.546  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:25:41.546  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:25:41.546  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:25:41.546  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:25:41.546  6006  6058 I jxcore-log: 
,09-13 12:25:42.646   715   715 I MSM-irqbalance: Decided to move IRQ155 from CPU1 to CPU3
,09-13 12:25:42.666  1258  2215 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 12:25:42.666  1258  2215 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4390, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 12:25:42.666  1258  2215 D BatteryService: online:4, current avg:16, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:167
09-13 12:25:42.666  1258  1258 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:25:42.666  1714  1714 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:25:42.676  1714  1714 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:25:42.676  1714  1714 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-13 12:25:42.676  2552  2552 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:25:42.676  2552  3097 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:25:42.696  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-13 12:25:42.696  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:25:42.696  1714  1714 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:25:43.936  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:25:43.936  6006  6058 I jxcore-log: 
09-13 12:25:43.936  6006  6058 I jxcore-log: websocket error
09-13 12:25:43.936  6006  6058 I jxcore-log: 
09-13 12:25:43.936  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:25:43.936  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:25:43.936  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:25:43.936  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:25:43.936  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:25:43.936  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:25:43.936  6006  6058 I jxcore-log: 
,09-13 12:25:44.976  1258  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:25:46.716  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:25:46.716  6006  6058 I jxcore-log: 
,09-13 12:25:46.716  6006  6058 I jxcore-log: websocket error
09-13 12:25:46.716  6006  6058 I jxcore-log: 
09-13 12:25:46.716  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:25:46.716  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:25:46.716  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:25:46.716  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:25:46.716  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:25:46.716  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:25:46.716  6006  6058 I jxcore-log: 
,09-13 12:25:47.646   715   715 I MSM-irqbalance: Decided to move IRQ166 from CPU1 to CPU3
,09-13 12:25:51.446  1258  3539 D SSRM:s  : SIOP:: AP = 340, PST = 358 (W:12), CP = 40, LCD = 0
,09-13 12:25:51.446  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:25:51.746  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:25:51.746  6006  6058 I jxcore-log: 
09-13 12:25:51.746  6006  6058 I jxcore-log: websocket error
09-13 12:25:51.746  6006  6058 I jxcore-log: 
09-13 12:25:51.746  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:25:51.746  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:25:51.746  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:25:51.746  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:25:51.746  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:25:51.746  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:25:51.746  6006  6058 I jxcore-log: 
,09-13 12:25:52.646   715   715 I MSM-irqbalance: Decided to move IRQ327 from CPU1 to CPU3
,09-13 12:25:56.806  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:25:56.806  6006  6058 I jxcore-log: 
,09-13 12:25:56.806  6006  6058 I jxcore-log: websocket error
09-13 12:25:56.806  6006  6058 I jxcore-log: 
09-13 12:25:56.806  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:25:56.806  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:25:56.806  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:25:56.806  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:25:56.806  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:25:56.806  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:25:56.806  6006  6058 I jxcore-log: 
,09-13 12:25:59.996  1258  1589 V AlarmManager: Expired Alarm result :8
,09-13 12:26:01.466  1258  3539 D SSRM:s  : SIOP:: AP = 330, PST = 355 (W:12), CP = 39, LCD = 0
,09-13 12:26:01.466  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:26:01.636  1258  1833 E Watchdog: !@Sync 4 [09-13 12:26:01.646]
,09-13 12:26:01.856  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:01.856  6006  6058 I jxcore-log: 
,09-13 12:26:01.856  6006  6058 I jxcore-log: websocket error
09-13 12:26:01.856  6006  6058 I jxcore-log: 
09-13 12:26:01.856  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:01.856  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:01.856  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:01.856  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:26:01.856  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:01.856  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:26:01.856  6006  6058 I jxcore-log: 
,09-13 12:26:02.646   715   715 I MSM-irqbalance: Decided to move IRQ200 from CPU0 to CPU3
,09-13 12:26:02.866  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-13 12:26:02.866  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-13 12:26:04.976  1258  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:26:06.896  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:06.896  6006  6058 I jxcore-log: 
09-13 12:26:06.896  6006  6058 I jxcore-log: websocket error
09-13 12:26:06.896  6006  6058 I jxcore-log: 
09-13 12:26:06.896  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:06.896  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:06.896  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:06.896  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:26:06.896  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:06.896  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:26:06.896  6006  6058 I jxcore-log: 
,09-13 12:26:11.496  1258  3539 D SSRM:s  : SIOP:: AP = 320, PST = 352 (W:12), CP = 38, LCD = 0
,09-13 12:26:11.496  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:26:11.926  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:11.926  6006  6058 I jxcore-log: 
09-13 12:26:11.926  6006  6058 I jxcore-log: websocket error
09-13 12:26:11.926  6006  6058 I jxcore-log: 
09-13 12:26:11.926  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:11.926  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:11.926  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:11.926  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:26:11.926  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:11.926  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:26:11.926  6006  6058 I jxcore-log: 
,09-13 12:26:12.716  1258  1986 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 12:26:12.716  1258  1986 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4371, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 12:26:12.716  1258  1986 D BatteryService: online:4, current avg:79, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-3
09-13 12:26:12.716  1258  1258 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:26:12.726  1714  1714 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:26:12.726  1714  1714 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:26:12.726  1714  1714 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-13 12:26:12.726  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:26:12.726  2552  2552 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:26:12.726  2552  3097 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:26:12.746  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:26:12.746  1714  1714 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:26:16.956  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:16.956  6006  6058 I jxcore-log: 
09-13 12:26:16.956  6006  6058 I jxcore-log: websocket error
09-13 12:26:16.956  6006  6058 I jxcore-log: 
09-13 12:26:16.966  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:16.966  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:16.966  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:16.966  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:26:16.966  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:16.966  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:26:16.966  6006  6058 I jxcore-log: 
,09-13 12:26:21.516  1258  3539 D SSRM:s  : SIOP:: AP = 310, PST = 348 (W:12), CP = 37, LCD = 0
,09-13 12:26:21.516  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:26:22.026  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:22.026  6006  6058 I jxcore-log: 
09-13 12:26:22.026  6006  6058 I jxcore-log: websocket error
09-13 12:26:22.026  6006  6058 I jxcore-log: 
09-13 12:26:22.026  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:22.026  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:22.026  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:22.026  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:26:22.026  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:22.026  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:26:22.026  6006  6058 I jxcore-log: 
,09-13 12:26:22.646   715   715 I MSM-irqbalance: Decided to move IRQ166 from CPU3 to CPU1
,09-13 12:26:24.976  1258  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:26:27.056  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:27.056  6006  6058 I jxcore-log: 
09-13 12:26:27.056  6006  6058 I jxcore-log: websocket error
09-13 12:26:27.056  6006  6058 I jxcore-log: 
09-13 12:26:27.056  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:27.056  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:27.056  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:27.056  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:26:27.056  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:27.056  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:26:27.056  6006  6058 I jxcore-log: 
,09-13 12:26:27.646   715   715 I MSM-irqbalance: Decided to move IRQ200 from CPU3 to CPU1
,09-13 12:26:31.546  1258  3539 D SSRM:s  : SIOP:: AP = 310, PST = 341 (W:12), CP = 37, LCD = 0
,09-13 12:26:31.546  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:26:31.636  1258  1833 E Watchdog: !@Sync 5 [09-13 12:26:31.647]
,09-13 12:26:31.686  1258  1589 V AlarmManager: Expired Alarm result :4
,09-13 12:26:31.696  1258  1377 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{515a8ca u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9847c17 1865:com.google.android.gms.persistent/u0a10}
,09-13 12:26:31.696  1714  1714 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
09-13 12:26:31.696  1714  1714 D KeyguardUpdateMonitor: handleTimeUpdate
,09-13 12:26:31.706  1714  1714 D Clock   : received broadcast android.intent.action.TIME_TICK
,09-13 12:26:31.706  1258  2636 V AlarmManager:  remove PendingIntent] PendingIntent{9e29a3b: PendingIntentRecord{e1daaab com.google.android.gms broadcastIntent}}
,09-13 12:26:31.746  1714  1714 D DateView: received broadcast android.intent.action.TIME_TICK
,09-13 12:26:31.786  4777  4777 D [WeatherWidget(1210)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB74266231DDCB0F9D898ABD6AE7EAFE9924B51C1628AB73EB6B27EF850A160BD15DCFDBE96F420541C45EF3419D3AD67E2]}
09-13 12:26:31.796  4777  4777 D [WeatherWidget(1210)]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,09-13 12:26:31.796  2242  6062 D UdcContextInitService: registered all accounts: true
,09-13 12:26:31.856  1258  2227 V AlarmManager:  remove PendingIntent] PendingIntent{1ead6b1: PendingIntentRecord{e1daaab com.google.android.gms broadcastIntent}}
,09-13 12:26:32.006  1865  6066 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 7820 seconds from now (1473762392012)
,09-13 12:26:32.016  1258  1377 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{334aae9 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9847c17 1865:com.google.android.gms.persistent/u0a10}
,09-13 12:26:32.066  1865  6064 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-13 12:26:32.066  1865  6064 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-13 12:26:32.096  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:32.096  6006  6058 I jxcore-log: 
09-13 12:26:32.096  6006  6058 I jxcore-log: websocket error
09-13 12:26:32.096  6006  6058 I jxcore-log: 
09-13 12:26:32.096  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:32.096  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:32.096  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:32.096  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:26:32.096  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:32.096  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:26:32.096  6006  6058 I jxcore-log: 
,09-13 12:26:32.106  1258  2594 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 12:26:32.186  1865  6064 I System.out: (HTTPLog)-Static: Hongbao
,09-13 12:26:32.186  1865  6064 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 12:26:32.186  1865  6064 I System.out: (HTTPLog)-Static: Hongbao
09-13 12:26:32.186  1865  6064 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:26:32.186   553  1408 D EnterpriseController: netId is 0
09-13 12:26:32.186   553  1408 D Netd    : getNetworkForDns: using netid 502 for uid 10010
,09-13 12:26:32.596  1258  1986 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 12:26:32.616  1865  6064 I System.out: (HTTPLog)-Static: Hongbao
09-13 12:26:32.616  1865  6064 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:26:32.616  1865  6064 I System.out: (HTTPLog)-Static: Hongbao
09-13 12:26:32.616  1865  6064 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:26:32.646   715   715 I MSM-irqbalance: Decided to move IRQ215 from CPU3 to CPU1
,09-13 12:26:32.726  1258  2391 V AlarmManager:  remove PendingIntent] PendingIntent{1aa882b: PendingIntentRecord{e1daaab com.google.android.gms broadcastIntent}}
,09-13 12:26:37.136  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:37.136  6006  6058 I jxcore-log: 
09-13 12:26:37.136  6006  6058 I jxcore-log: websocket error
09-13 12:26:37.136  6006  6058 I jxcore-log: 
,09-13 12:26:37.136  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:37.136  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:37.136  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:37.136  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:26:37.136  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:37.136  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:26:37.136  6006  6058 I jxcore-log: 
,09-13 12:26:41.566  1258  3539 D SSRM:s  : SIOP:: AP = 310, PST = 337 (W:14), CP = 37, LCD = 0
,09-13 12:26:41.566  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:26:42.166  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:42.166  6006  6058 I jxcore-log: 
09-13 12:26:42.166  6006  6058 I jxcore-log: websocket error
09-13 12:26:42.166  6006  6058 I jxcore-log: 
09-13 12:26:42.166  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:42.166  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:42.166  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:42.166  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:26:42.166  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:42.166  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:26:42.166  6006  6058 I jxcore-log: 
,09-13 12:26:42.646   715   715 I MSM-irqbalance: Decided to move IRQ155 from CPU3 to CPU1
,09-13 12:26:42.766  1258  2215 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 12:26:42.766  1258  2215 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4371, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 12:26:42.766  1258  2215 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-3
,09-13 12:26:42.766  1258  1258 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:26:42.776  1714  1714 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:26:42.776  1714  1714 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:26:42.776  1714  1714 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-13 12:26:42.776  2552  2552 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:26:42.776  2552  3097 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:26:42.796  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:26:42.796  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:26:42.796  1714  1714 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:26:44.926  1258  3540 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,09-13 12:26:44.936  1258  1377 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b0efcd2 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{13bd42c 5801:com.samsung.android.sm.provider/1000}
,09-13 12:26:44.976  1258  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:26:44.986  1258  3540 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,09-13 12:26:44.996  1258  1377 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1fc1ca0 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{13bd42c 5801:com.samsung.android.sm.provider/1000}
,09-13 12:26:47.196  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:47.196  6006  6058 I jxcore-log: 
09-13 12:26:47.196  6006  6058 I jxcore-log: websocket error
09-13 12:26:47.196  6006  6058 I jxcore-log: 
09-13 12:26:47.196  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:47.196  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:47.196  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:47.196  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:26:47.196  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:47.196  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:26:47.196  6006  6058 I jxcore-log: 
,09-13 12:26:51.596  1258  3539 D SSRM:s  : SIOP:: AP = 300, PST = 330 (W:14), CP = 36, LCD = 0
,09-13 12:26:51.596  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:26:52.226  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:52.226  6006  6058 I jxcore-log: 
09-13 12:26:52.226  6006  6058 I jxcore-log: websocket error
09-13 12:26:52.226  6006  6058 I jxcore-log: 
09-13 12:26:52.226  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:52.226  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:52.226  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:52.226  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:26:52.226  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:52.226  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:26:52.226  6006  6058 I jxcore-log: 
,09-13 12:26:57.266  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:57.266  6006  6058 I jxcore-log: 
,09-13 12:26:57.266  6006  6058 I jxcore-log: websocket error
09-13 12:26:57.266  6006  6058 I jxcore-log: 
,09-13 12:26:57.266  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:57.266  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:57.266  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:57.266  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:26:57.266  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:57.266  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:26:57.266  6006  6058 I jxcore-log: 
,09-13 12:26:59.996  1258  1589 V AlarmManager: Expired Alarm result :8
,09-13 12:27:01.626  1258  3539 D SSRM:s  : SIOP:: AP = 300, PST = 325 (W:14), CP = 36, LCD = 0
,09-13 12:27:01.626  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:27:01.636  1258  1833 E Watchdog: !@Sync 6 [09-13 12:27:01.648],
,09-13 12:27:02.306  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:02.306  6006  6058 I jxcore-log: 
09-13 12:27:02.306  6006  6058 I jxcore-log: websocket error
09-13 12:27:02.306  6006  6058 I jxcore-log: 
09-13 12:27:02.306  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:02.306  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:02.306  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:02.306  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:27:02.306  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:02.306  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:27:02.306  6006  6058 I jxcore-log: 
,09-13 12:27:02.916  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-13 12:27:02.916  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-13 12:27:03.006  2106  2159 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 85ms lastUpdatedAfter : 122846ms
,09-13 12:27:04.976  1258  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:27:07.346  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:07.346  6006  6058 I jxcore-log: 
,09-13 12:27:07.346  6006  6058 I jxcore-log: websocket error
09-13 12:27:07.346  6006  6058 I jxcore-log: 
09-13 12:27:07.346  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:07.346  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:07.346  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:07.346  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:27:07.346  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:07.346  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:27:07.346  6006  6058 I jxcore-log: 
,09-13 12:27:11.646  1258  3539 D SSRM:s  : SIOP:: AP = 300, PST = 320 (W:14), CP = 36, LCD = 0
,09-13 12:27:11.646  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:27:12.376  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:12.376  6006  6058 I jxcore-log: 
09-13 12:27:12.376  6006  6058 I jxcore-log: websocket error
09-13 12:27:12.376  6006  6058 I jxcore-log: 
09-13 12:27:12.376  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:12.376  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:12.376  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:12.376  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:27:12.376  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:12.376  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:27:12.376  6006  6058 I jxcore-log: 
,09-13 12:27:12.816  1258  2010 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 12:27:12.816  1258  2010 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4371, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 12:27:12.816  1258  2010 D BatteryService: online:4, current avg:-2, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-3
09-13 12:27:12.816  1258  1258 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:27:12.826  1714  1714 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:27:12.826  1714  1714 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:27:12.826  1714  1714 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-13 12:27:12.826  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-13 12:27:12.836  2552  2552 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:27:12.836  2552  3097 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:27:12.856  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-13 12:27:12.856  1714  1714 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:27:17.426  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:17.426  6006  6058 I jxcore-log: 
,09-13 12:27:17.426  6006  6058 I jxcore-log: websocket error
09-13 12:27:17.426  6006  6058 I jxcore-log: 
09-13 12:27:17.426  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:17.426  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:17.426  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:17.426  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:27:17.426  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:17.426  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:27:17.426  6006  6058 I jxcore-log: 
,09-13 12:27:21.666  1258  3539 D SSRM:s  : SIOP:: AP = 300, PST = 318 (W:16), CP = 36, LCD = 0
,09-13 12:27:21.666  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:27:22.456  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:22.456  6006  6058 I jxcore-log: 
09-13 12:27:22.456  6006  6058 I jxcore-log: websocket error
09-13 12:27:22.456  6006  6058 I jxcore-log: 
09-13 12:27:22.456  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:22.456  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:22.456  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:22.456  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:27:22.456  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:22.456  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:27:22.456  6006  6058 I jxcore-log: 
,09-13 12:27:24.976  1258  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:27:27.486  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:27.486  6006  6058 I jxcore-log: 
09-13 12:27:27.486  6006  6058 I jxcore-log: websocket error
09-13 12:27:27.486  6006  6058 I jxcore-log: 
09-13 12:27:27.486  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:27.486  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:27.486  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:27.486  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:27:27.486  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:27.486  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:27:27.486  6006  6058 I jxcore-log: 
,09-13 12:27:31.646  1258  1833 E Watchdog: !@Sync 7 [09-13 12:27:31.649]
,09-13 12:27:31.696  1258  3539 D SSRM:s  : SIOP:: AP = 300, PST = 313 (W:16), CP = 36, LCD = 0
,09-13 12:27:31.696  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:27:32.526  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:32.526  6006  6058 I jxcore-log: 
,09-13 12:27:32.526  6006  6058 I jxcore-log: websocket error
09-13 12:27:32.526  6006  6058 I jxcore-log: 
09-13 12:27:32.526  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:32.526  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:32.526  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:32.526  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:27:32.526  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:32.526  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:27:32.526  6006  6058 I jxcore-log: 
,09-13 12:27:37.566  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:37.566  6006  6058 I jxcore-log: 
,09-13 12:27:37.566  6006  6058 I jxcore-log: websocket error
09-13 12:27:37.566  6006  6058 I jxcore-log: 
09-13 12:27:37.566  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:37.566  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:37.566  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:37.566  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:27:37.566  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:37.566  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:27:37.566  6006  6058 I jxcore-log: 
,09-13 12:27:41.716  1258  3539 D SSRM:s  : SIOP:: AP = 300, PST = 308 (W:16), CP = 35, LCD = 0
,09-13 12:27:41.726  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:27:42.606  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:42.606  6006  6058 I jxcore-log: 
09-13 12:27:42.606  6006  6058 I jxcore-log: websocket error
09-13 12:27:42.606  6006  6058 I jxcore-log: 
09-13 12:27:42.606  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:42.606  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:42.606  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:42.606  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:27:42.606  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:42.606  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:27:42.606  6006  6058 I jxcore-log: 
,09-13 12:27:42.866  1258  1618 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 12:27:42.866  1258  1618 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4371, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 12:27:42.866  1258  1618 D BatteryService: online:4, current avg:-2, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-3
09-13 12:27:42.866  1258  1258 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:27:42.876  1714  1714 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:27:42.876  1714  1714 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 12:27:42.876  1714  1714 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-13 12:27:42.876  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-13 12:27:42.876  2552  2552 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:27:42.876  2552  3097 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:27:42.896  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:27:42.896  1714  1714 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:27:44.976  1258  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:27:47.636  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:47.636  6006  6058 I jxcore-log: 
09-13 12:27:47.636  6006  6058 I jxcore-log: websocket error
09-13 12:27:47.636  6006  6058 I jxcore-log: 
09-13 12:27:47.636  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:47.636  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:47.636  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:47.636  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:27:47.636  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:47.636  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:27:47.636  6006  6058 I jxcore-log: 
,09-13 12:27:51.746  1258  3539 D SSRM:s  : SIOP:: AP = 290, PST = 305 (W:16), CP = 35, LCD = 0
,09-13 12:27:51.746  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:27:52.656  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:52.656  6006  6058 I jxcore-log: 
09-13 12:27:52.666  6006  6058 I jxcore-log: websocket error
09-13 12:27:52.666  6006  6058 I jxcore-log: 
,09-13 12:27:52.666  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:52.666  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:52.666  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:52.666  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:27:52.666  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:52.666  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:27:52.666  6006  6058 I jxcore-log: 
,09-13 12:27:57.686  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:57.686  6006  6058 I jxcore-log: 
09-13 12:27:57.686  6006  6058 I jxcore-log: websocket error
09-13 12:27:57.686  6006  6058 I jxcore-log: 
09-13 12:27:57.686  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:57.686  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:57.686  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:57.686  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:27:57.686  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:57.686  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:27:57.686  6006  6058 I jxcore-log: 
,09-13 12:28:01.646  1258  1833 E Watchdog: !@Sync 8 [09-13 12:28:01.650]
,09-13 12:28:01.766  1258  3539 D SSRM:s  : SIOP:: AP = 290, PST = 303 (W:18), CP = 35, LCD = 0
,09-13 12:28:01.766  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:28:02.716  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:28:02.716  6006  6058 I jxcore-log: 
09-13 12:28:02.716  6006  6058 I jxcore-log: websocket error
09-13 12:28:02.716  6006  6058 I jxcore-log: 
09-13 12:28:02.716  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:28:02.716  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:28:02.716  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:28:02.716  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:28:02.716  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:28:02.716  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:28:02.716  6006  6058 I jxcore-log: 
,09-13 12:28:03.106  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-13 12:28:03.106  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-13 12:28:04.976  1258  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:28:07.756  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:28:07.756  6006  6058 I jxcore-log: 
09-13 12:28:07.756  6006  6058 I jxcore-log: websocket error
09-13 12:28:07.756  6006  6058 I jxcore-log: 
09-13 12:28:07.756  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:28:07.756  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:28:07.756  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:28:07.756  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:28:07.756  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:28:07.756  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:28:07.756  6006  6058 I jxcore-log: 
,09-13 12:28:11.796  1258  3539 D SSRM:s  : SIOP:: AP = 290, PST = 300 (W:18), CP = 35, LCD = 0
,09-13 12:28:11.796  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:28:12.926  1258  1743 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 12:28:12.926  1258  1743 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4371, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 12:28:12.926  1258  1743 D BatteryService: online:4, current avg:-2, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-3
09-13 12:28:12.926  1258  1258 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:28:12.926  1714  1714 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:28:12.926  1714  1714 D PowerUI : priorPlugType = 2 mPlugType =  2
09-13 12:28:12.926  1714  1714 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:28:12.936  2552  2552 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:28:12.936  2552  3097 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:28:12.946  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-13 12:28:12.946  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:28:12.946  1714  1714 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:28:19.816  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:28:19.816  6006  6058 I jxcore-log: 
,09-13 12:28:19.826  6006  6058 I jxcore-log: websocket error
09-13 12:28:19.826  6006  6058 I jxcore-log: 
,09-13 12:28:19.826  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:28:19.826  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:28:19.826  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:28:19.826  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:28:19.826  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:28:19.826  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:28:19.826  6006  6058 I jxcore-log: 
,09-13 12:28:21.826  1258  3539 D SSRM:s  : SIOP:: AP = 290, PST = 298 (W:18), CP = 35, LCD = 0
09-13 12:28:21.826  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:28:24.856  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:28:24.856  6006  6058 I jxcore-log: 
09-13 12:28:24.856  6006  6058 I jxcore-log: websocket error
09-13 12:28:24.856  6006  6058 I jxcore-log: 
09-13 12:28:24.856  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:28:24.856  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:28:24.856  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:28:24.856  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:28:24.856  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:28:24.856  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:28:24.856  6006  6058 I jxcore-log: 
,09-13 12:28:24.976  1258  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:28:29.926  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:28:29.926  6006  6058 I jxcore-log: 
09-13 12:28:29.926  6006  6058 I jxcore-log: websocket error
09-13 12:28:29.926  6006  6058 I jxcore-log: 
09-13 12:28:29.926  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:28:29.926  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:28:29.926  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:28:29.926  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:28:29.926  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:28:29.926  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:28:29.926  6006  6058 I jxcore-log: 
,09-13 12:28:31.646  1258  1833 E Watchdog: !@Sync 9 [09-13 12:28:31.651]
,09-13 12:28:31.846  1258  3539 D SSRM:s  : SIOP:: AP = 290, PST = 297 (W:18), CP = 35, LCD = 0
,09-13 12:28:31.846  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:28:34.956  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:28:34.956  6006  6058 I jxcore-log: 
09-13 12:28:34.956  6006  6058 I jxcore-log: websocket error
09-13 12:28:34.956  6006  6058 I jxcore-log: 
09-13 12:28:34.956  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:28:34.956  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:28:34.956  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:28:34.956  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:28:34.956  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:28:34.956  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:28:34.956  6006  6058 I jxcore-log: 
,09-13 12:28:39.996  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:28:39.996  6006  6058 I jxcore-log: 
09-13 12:28:39.996  6006  6058 I jxcore-log: websocket error
09-13 12:28:39.996  6006  6058 I jxcore-log: 
09-13 12:28:39.996  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:28:39.996  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:28:39.996  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:28:39.996  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:28:39.996  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:28:39.996  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:28:39.996  6006  6058 I jxcore-log: 
,09-13 12:28:41.876  1258  3539 D SSRM:s  : SIOP:: AP = 290, PST = 296 (W:20), CP = 35, LCD = 0
,09-13 12:28:41.876  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:28:42.976  1258  2391 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 12:28:42.976  1258  2391 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4371, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 12:28:42.976  1258  2391 D BatteryService: online:4, current avg:-2, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-3
09-13 12:28:42.976  1258  1258 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:28:42.976  1714  1714 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:28:42.976  1714  1714 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 12:28:42.976  1714  1714 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-13 12:28:42.986  2552  2552 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:28:42.986  2552  3097 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:28:43.006  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:28:43.006  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:28:43.006  1714  1714 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:28:44.986  1258  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:28:45.026  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:28:45.026  6006  6058 I jxcore-log: 
09-13 12:28:45.026  6006  6058 I jxcore-log: websocket error
09-13 12:28:45.026  6006  6058 I jxcore-log: 
09-13 12:28:45.026  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:28:45.026  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:28:45.026  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:28:45.026  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:28:45.026  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:28:45.026  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:28:45.026  6006  6058 I jxcore-log: 
,09-13 12:28:50.056  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:28:50.056  6006  6058 I jxcore-log: 
09-13 12:28:50.056  6006  6058 I jxcore-log: websocket error
09-13 12:28:50.056  6006  6058 I jxcore-log: 
09-13 12:28:50.056  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:28:50.056  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:28:50.056  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:28:50.056  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:28:50.056  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:28:50.056  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:28:50.056  6006  6058 I jxcore-log: 
,09-13 12:28:51.896  1258  3539 D SSRM:s  : SIOP:: AP = 290, PST = 295 (W:20), CP = 35, LCD = 0
,09-13 12:28:51.896  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:28:55.086  6006  6058 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:28:55.086  6006  6058 I jxcore-log: 
,09-13 12:28:55.086  6006  6058 I jxcore-log: websocket error
09-13 12:28:55.086  6006  6058 I jxcore-log: 
09-13 12:28:55.086  6006  6058 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:28:55.086  6006  6058 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:28:55.086  6006  6058 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:28:55.086  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:28:55.086  6006  6058 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:28:55.086  6006  6058 I jxcore-log: emit@events.js:82:1
09-13 12:28:55.086  6006  6058 I jxcore-log: 
,09-13 12:28:59.336  1258  1584 D TimaService: TIMA: TimaService scheduler is intialized. 
09-13 12:28:59.336  1258  1584 I TLC_TIMA_PKM_initialize: initializing...
09-13 12:28:59.336  1258  1584 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
09-13 12:28:59.336  1258  1584 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
09-13 12:28:59.336  1258  1583 D TimaService: TimaServiceHandler.handleMessage what =1
09-13 12:28:59.336  1258  1584 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
09-13 12:28:59.336  1258  1584 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
09-13 12:28:59.336  1258  1584 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
09-13 12:28:59.336  1258  1584 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
09-13 12:28:59.336  1258  1584 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
09-13 12:28:59.336  1258  1584 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
09-13 12:28:59.336  1258  1584 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
09-13 12:28:59.336  1258  1584 D QSEECOMAPI: : App is not loaded in QSEE
,09-13 12:28:59.346  1258  1584 D QSEECOMAPI: : app_arch = 1, total_files = 5
,09-13 12:28:59.396  1258  1584 D QSEECOMAPI: : Loaded image: APP id = 47
,09-13 12:28:59.406  1258  1584 I TZ: qc_tlc_communication: TLC_COMM: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,09-13 12:28:59.406  1258  1584 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,09-13 12:29:00.186  6006  6058 I jxcore-log: ThaliTape :: Reconnected to the test server
09-13 12:29:00.186  6006  6058 I jxcore-log: 
,09-13 12:29:00.206  6006  6058 I jxcore-log: ThaliTape :: Connected to the test server
09-13 12:29:00.206  6006  6058 I jxcore-log: 
,09-13 12:29:01.646  1258  1833 E Watchdog: !@Sync 10 [09-13 12:29:01.652]
,09-13 12:29:01.836  1258  1584 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,09-13 12:29:01.836  1258  1584 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,09-13 12:29:01.846  1258  1584 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,09-13 12:29:01.846  1258  1584 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,09-13 12:29:01.926  1258  3539 D SSRM:s  : SIOP:: AP = 290, PST = 294 (W:20), CP = 36, LCD = 0
,09-13 12:29:01.926  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:29:01.996  1258  1589 V AlarmManager: Expired Alarm result :4
,09-13 12:29:02.006  1714  1714 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
09-13 12:29:02.006  1714  1714 D KeyguardUpdateMonitor: handleTimeUpdate
,09-13 12:29:02.006  2370  2370 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-13 12:29:02.016  2370  2370 I wpa_supplicant: P2P: Current p2p state = IDLE
,09-13 12:29:02.016  1714  1714 D Clock   : received broadcast android.intent.action.TIME_TICK
09-13 12:29:02.016  2370  2370 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-13 12:29:02.056  1714  1714 D DateView: received broadcast android.intent.action.TIME_TICK
,09-13 12:29:02.096  4777  4777 D [WeatherWidget(1210)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB74266231DDCB0F9D898ABD6AE7EAFE9924B51C1628AB73EB6B27EF850A160BD15DCFDBE96F420541C45EF3419D3AD67E2]}
,09-13 12:29:02.096  4777  4777 D [WeatherWidget(1210)]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,09-13 12:29:03.166  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-13 12:29:03.166  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-13 12:29:04.986  1258  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:29:06.256  2370  2370 I wpa_supplicant: nl80211: Received scan results (44 BSSes)
,09-13 12:29:06.256  2370  2370 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
,09-13 12:29:06.266  1258  1622 D WifiP2pService: InactiveState{ what=147461 }
09-13 12:29:06.266  1258  1622 D WifiP2pService: P2pEnabledState{ what=147461 }
09-13 12:29:06.266  1258  1622 D WifiP2pService: DefaultState{ what=147461 }
,09-13 12:29:06.296  1258  1377 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61662cc u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b39926f 1714:com.android.systemui/u0a46}
,09-13 12:29:07.646   715   715 I MSM-irqbalance: Decided to move IRQ215 from CPU1 to CPU0
,09-13 12:29:11.956  1258  3539 D SSRM:s  : SIOP:: AP = 290, PST = 293 (W:20), CP = 35, LCD = 0
,09-13 12:29:11.956  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:29:12.646   715   715 I MSM-irqbalance: Decided to move IRQ166 from CPU1 to CPU0
,09-13 12:29:13.026  1258  2010 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 12:29:13.026  1258  2010 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4371, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 12:29:13.026  1258  2010 D BatteryService: online:4, current avg:-2, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-3
09-13 12:29:13.026  1258  1258 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:29:13.026  1714  1714 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:29:13.026  1714  1714 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:29:13.036  1714  1714 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-13 12:29:13.036  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-13 12:29:13.036  2552  2552 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:29:13.036  2552  3097 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:29:13.056  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:29:13.056  1714  1714 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:29:21.986  1258  3539 D SSRM:s  : SIOP:: AP = 290, PST = 293 (W:22), CP = 35, LCD = 0
,09-13 12:29:21.986  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:29:24.986  1258  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:29:31.646  1258  1833 E Watchdog: !@Sync 11 [09-13 12:29:31.653]
,09-13 12:29:32.006  1258  3539 D SSRM:s  : SIOP:: AP = 290, PST = 292 (W:22), CP = 35, LCD = 0
,09-13 12:29:32.006  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:29:34.036  5651  5695 W PlayEventLogger: No account for auth token provided
,09-13 12:29:34.056  5651  5695 I System.out: (HTTPLog)-Static: Hongbao
,09-13 12:29:34.066  5651  5695 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 12:29:34.066  5651  5695 I System.out: (HTTPLog)-Static: Hongbao
,09-13 12:29:34.066  5651  5695 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:29:34.066   553  1408 D EnterpriseController: netId is 0
09-13 12:29:34.066   553  1408 D Netd    : getNetworkForDns: using netid 502 for uid 10019
,09-13 12:29:37.646   715   715 I MSM-irqbalance: Decided to move IRQ155 from CPU1 to CPU0
,09-13 12:29:42.036  1258  3539 D SSRM:s  : SIOP:: AP = 290, PST = 291 (W:22), CP = 35, LCD = 0
,09-13 12:29:42.036  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:29:43.076  1258  1618 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 12:29:43.076  1258  1618 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4371, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 12:29:43.076  1258  1618 D BatteryService: online:4, current avg:-2, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-3
09-13 12:29:43.076  1258  1258 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:29:43.076  1714  1714 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:29:43.076  1714  1714 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 12:29:43.076  1714  1714 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-13 12:29:43.086  2552  2552 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:29:43.086  2552  3097 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:29:43.096  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-13 12:29:43.096  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:29:43.096  1714  1714 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:29:44.986  1258  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:29:47.646   715   715 I MSM-irqbalance: Decided to move IRQ327 from CPU1 to CPU0
,09-13 12:29:52.056  1258  3539 D SSRM:s  : SIOP:: AP = 290, PST = 291 (W:22), CP = 35, LCD = 0
,09-13 12:29:52.066  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:29:59.996  1258  1589 V AlarmManager: Expired Alarm result :8
,09-13 12:30:01.646  1258  1833 E Watchdog: !@Sync 12 [09-13 12:30:01.654]
,09-13 12:30:02.086  1258  3539 D SSRM:s  : SIOP:: AP = 290, PST = 290 (W:24), CP = 35, LCD = 0
,09-13 12:30:02.086  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:30:02.646   715   715 I MSM-irqbalance: Decided to move IRQ166 from CPU0 to CPU2
,09-13 12:30:03.186  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-13 12:30:03.186  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-13 12:30:03.256  2106  2159 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 72ms lastUpdatedAfter : 180251ms
,09-13 12:30:04.986  1258  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:30:07.646   715   715 I MSM-irqbalance: Decided to move IRQ215 from CPU0 to CPU2
,09-13 12:30:12.106  1258  3539 D SSRM:s  : SIOP:: AP = 290, PST = 290 (W:24), CP = 35, LCD = 0
,09-13 12:30:12.116  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:30:12.646   715   715 I MSM-irqbalance: Decided to move IRQ155 from CPU0 to CPU2
,09-13 12:30:13.126  1258  1618 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 12:30:13.126  1258  1618 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4371, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 12:30:13.126  1258  1618 D BatteryService: online:4, current avg:-2, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-3
,09-13 12:30:13.126  1258  1258 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:30:13.126  1714  1714 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:30:13.126  1714  1714 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 12:30:13.126  1714  1714 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-13 12:30:13.136  2552  2552 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:30:13.136  2552  3097 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:30:13.156  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:30:13.156  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:30:13.156  1714  1714 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:30:17.646   715   715 I MSM-irqbalance: Decided to move IRQ327 from CPU1 to CPU2
,09-13 12:30:22.146  1258  3539 D SSRM:s  : SIOP:: AP = 290, PST = 290 (W:24), CP = 35, LCD = 0
09-13 12:30:22.146  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:30:22.236  1258  1273 I art     : Background sticky concurrent mark sweep GC freed 110067(9MB) AllocSpace objects, 251(5MB) LOS objects, 28% free, 37MB/51MB, paused 3.427ms total 106.531ms
,09-13 12:30:24.986  1258  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:30:27.646   715   715 I MSM-irqbalance: Decided to move IRQ166 from CPU2 to CPU1
,09-13 12:30:31.646  1258  1833 E Watchdog: !@Sync 13 [09-13 12:30:31.655]
,09-13 12:30:32.166  1258  3539 D SSRM:s  : SIOP:: AP = 290, PST = 290 (W:24), CP = 35, LCD = 0
,09-13 12:30:32.166  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:30:42.196  1258  3539 D SSRM:s  : SIOP:: AP = 290, PST = 290 (W:26), CP = 35, LCD = 0
,09-13 12:30:42.196  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:30:43.176  1258  1618 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:30:44.986  1258  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:30:52.216  1258  3539 D SSRM:s  : SIOP:: AP = 290, PST = 290 (W:26), CP = 35, LCD = 0
,09-13 12:30:52.216  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:31:01.646  1258  1833 E Watchdog: !@Sync 14 [09-13 12:31:01.656]
,09-13 12:31:02.246  1258  3539 D SSRM:s  : SIOP:: AP = 290, PST = 290 (W:26), CP = 35, LCD = 0
,09-13 12:31:02.246  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:31:03.286  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-13 12:31:03.286  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-13 12:31:04.986  1258  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:31:07.646   715   715 I MSM-irqbalance: Decided to move IRQ215 from CPU2 to CPU1
,09-13 12:31:12.266  1258  3539 D SSRM:s  : SIOP:: AP = 290, PST = 290 (W:26), CP = 35, LCD = 0
,09-13 12:31:12.266  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:31:13.226  1258  2594 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 12:31:13.226  1258  2594 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4371, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 12:31:13.226  1258  2594 D BatteryService: online:4, current avg:-2, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-3
,09-13 12:31:13.226  1258  1258 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:31:13.236  1714  1714 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:31:13.236  1714  1714 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 12:31:13.236  1714  1714 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-13 12:31:13.236  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-13 12:31:13.236  2552  2552 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:31:13.236  2552  3097 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:31:13.256  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-13 12:31:13.256  1714  1714 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:31:22.286  1258  3539 D SSRM:s  : SIOP:: AP = 290, PST = 290 (W:28), CP = 35, LCD = 0
,09-13 12:31:22.286  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:31:24.986  1258  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:31:31.646  1258  1833 E Watchdog: !@Sync 15 [09-13 12:31:31.657]
,09-13 12:31:32.316  1258  3539 D SSRM:s  : SIOP:: AP = 290, PST = 290 (W:28), CP = 35, LCD = 0
,09-13 12:31:32.316  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:31:42.336  1258  3539 D SSRM:s  : SIOP:: AP = 290, PST = 290 (W:28), CP = 35, LCD = 0
,09-13 12:31:42.336  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:31:43.276  1258  2594 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 12:31:43.276  1258  2594 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4371, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 12:31:43.276  1258  2594 D BatteryService: online:4, current avg:-2, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-3
09-13 12:31:43.276  1258  1258 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:31:43.286  1714  1714 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:31:43.286  1714  1714 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 12:31:43.286  1714  1714 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-13 12:31:43.286  2552  2552 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:31:43.286  2552  3097 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:31:43.306  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-13 12:31:43.306  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:31:43.306  1714  1714 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:31:44.986  1258  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:31:52.366  1258  3539 D SSRM:s  : SIOP:: AP = 290, PST = 290 (W:28), CP = 35, LCD = 0
,09-13 12:31:52.366  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:31:52.676   597   597 I bootchecker: bootchecker wake up!!
,09-13 12:32:01.646  1258  1833 E Watchdog: !@Sync 16 [09-13 12:32:01.658]
,09-13 12:32:02.386  1258  3539 D SSRM:s  : SIOP:: AP = 290, PST = 290 (W:30), CP = 35, LCD = 0
,09-13 12:32:02.396  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:32:03.376  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-13 12:32:03.376  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-13 12:32:04.996  1258  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:32:12.416  1258  3539 D SSRM:s  : SIOP:: AP = 290, PST = 290 (W:30), CP = 35, LCD = 0
,09-13 12:32:12.416  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:32:13.326  1258  2594 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 12:32:13.326  1258  2594 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4371, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 12:32:13.326  1258  2594 D BatteryService: online:4, current avg:-2, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-3
,09-13 12:32:13.326  1258  1258 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:32:13.336  1714  1714 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:32:13.336  1714  1714 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 12:32:13.336  1714  1714 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-13 12:32:13.336  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-13 12:32:13.336  2552  2552 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:32:13.336  2552  3097 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:32:13.356  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:32:13.356  1714  1714 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:32:22.436  1258  3539 D SSRM:s  : SIOP:: AP = 290, PST = 290 (W:30), CP = 35, LCD = 0
,09-13 12:32:22.436  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:32:24.996  1258  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:32:31.656  1258  1833 E Watchdog: !@Sync 17 [09-13 12:32:31.659]
,09-13 12:32:32.466  1258  3539 D SSRM:s  : SIOP:: AP = 290, PST = 290 (W:30), CP = 35, LCD = 0
,09-13 12:32:32.466  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:32:42.486  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 289 (W:30), CP = 35, LCD = 0
,09-13 12:32:42.486  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:32:43.386  1258  2585 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 12:32:43.386  1258  2585 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4371, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 12:32:43.386  1258  2585 D BatteryService: online:4, current avg:-2, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-3
09-13 12:32:43.386  1258  1258 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:32:43.386  1714  1714 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:32:43.386  1714  1714 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 12:32:43.386  1714  1714 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-13 12:32:43.396  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-13 12:32:43.396  2552  2552 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:32:43.396  2552  3097 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:32:43.406  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:32:43.406  1714  1714 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:32:44.996  1258  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:32:52.506  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 289 (W:30), CP = 35, LCD = 0
,09-13 12:32:52.506  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:33:01.656  1258  1833 E Watchdog: !@Sync 18 [09-13 12:33:01.660]
,09-13 12:33:02.536  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 289 (W:30), CP = 35, LCD = 0
,09-13 12:33:02.536  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:33:03.476  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-13 12:33:03.476  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-13 12:33:03.546  2106  2159 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 64ms lastUpdatedAfter : 180287ms
,09-13 12:33:04.996  1258  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:33:07.646   715   715 I MSM-irqbalance: Decided to move IRQ155 from CPU2 to CPU3
,09-13 12:33:12.556  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 288 (W:30), CP = 35, LCD = 0
,09-13 12:33:12.566  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:33:13.426  1258  2011 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:33:22.586  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 288 (W:30), CP = 35, LCD = 0
,09-13 12:33:22.586  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:33:24.996  1258  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:33:31.656  1258  1833 E Watchdog: !@Sync 19 [09-13 12:33:31.661]
,09-13 12:33:32.606  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 288 (W:30), CP = 35, LCD = 0
,09-13 12:33:32.606  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:33:42.636  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 287 (W:30), CP = 35, LCD = 0
,09-13 12:33:42.636  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:33:43.486  1258  2594 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:33:44.996  1258  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:33:52.666  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 287 (W:30), CP = 35, LCD = 0
,09-13 12:33:52.666  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:33:59.336  1258  1584 D TimaService: TIMA: TimaService scheduler is intialized. 
09-13 12:33:59.336  1258  1584 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
09-13 12:33:59.336  1258  1583 D TimaService: TimaServiceHandler.handleMessage what =1
,09-13 12:34:00.606  1258  1584 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,09-13 12:34:00.606  1258  1584 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,09-13 12:34:00.616  1258  1584 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,09-13 12:34:00.616  1258  1584 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,09-13 12:34:01.656  1258  1833 E Watchdog: !@Sync 20 [09-13 12:34:01.662]
,09-13 12:34:02.686  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 287 (W:30), CP = 35, LCD = 0
,09-13 12:34:02.686  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:34:03.646  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-13 12:34:03.646  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10002, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10005, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10009, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10010, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10016, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10017, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10020, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10022, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10023, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10025, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10026, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10027, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10028, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10029, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10030, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10031, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10037, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10038, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10039, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10042, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10057, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10061, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLock,ed: 10064, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10066, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10067, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10069, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10071, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10072, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10076, mScreenOn: false, uidstate: 14, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10078, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10079, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10080, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10081, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10082, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10083, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10084, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10086, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10089, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10090, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10091, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10093, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10094, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10097, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10100, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10102, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10104, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10106, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10108, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10109, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10115, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10116, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: ,false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10118, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10120, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10121, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10124, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10126, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10130, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:04.756  1258  1368 D NetworkPolicy: isUidForegroundLocked: 10132, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,09-13 12:34:04.916  1258  1416 I ActivityManager: setMaxStartingBackgroundTimer onfinish,
09-13 12:34:04.916  1258  1416 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,09-13 12:34:04.996  1258  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:34:12.716  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 286 (W:30), CP = 35, LCD = 0
,09-13 12:34:12.716  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:34:13.536  1258  1303 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:34:21.026  1258  1589 V AlarmManager: Expired Alarm result :8
,09-13 12:34:22.736  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 286 (W:30), CP = 35, LCD = 0
,09-13 12:34:22.736  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:34:24.996  1258  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:34:31.656  1258  1833 E Watchdog: !@Sync 21 [09-13 12:34:31.663]
,09-13 12:34:32.766  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 286 (W:30), CP = 35, LCD = 0
,09-13 12:34:32.766  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:34:42.786  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 285 (W:30), CP = 35, LCD = 0
,09-13 12:34:42.786  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:34:43.586  1258  2215 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:34:52.816  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 285 (W:30), CP = 35, LCD = 0
,09-13 12:34:52.816  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:35:01.656  1258  1833 E Watchdog: !@Sync 22 [09-13 12:35:01.664]
,09-13 12:35:02.836  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 285 (W:30), CP = 35, LCD = 0
,09-13 12:35:02.836  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:35:03.746  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-13 12:35:03.746  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-13 12:35:12.866  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 284 (W:30), CP = 35, LCD = 0
,09-13 12:35:12.866  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:35:13.636  1258  2594 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 12:35:13.636  1258  2594 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4371, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 12:35:13.636  1258  2594 D BatteryService: online:4, current avg:-2, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-3
,09-13 12:35:13.636  1258  1258 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:35:13.646  1714  1714 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:35:13.646  1714  1714 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:35:13.646  1714  1714 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-13 12:35:13.646  2552  2552 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:35:13.646  2552  3097 D HeadsetStateMachine: Disconnected process message: 10, size: 0,
09-13 12:35:13.646  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-13 12:35:13.666  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:35:13.666  1714  1714 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:35:22.886  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 284 (W:30), CP = 35, LCD = 0
,09-13 12:35:22.896  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:35:31.656  1258  1833 E Watchdog: !@Sync 23 [09-13 12:35:31.665]
,09-13 12:35:32.916  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 284 (W:30), CP = 35, LCD = 0
,09-13 12:35:32.916  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:35:42.936  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 283 (W:30), CP = 35, LCD = 0
,09-13 12:35:42.936  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:35:43.686  1258  1743 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:35:52.966  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 283 (W:30), CP = 35, LCD = 0
,09-13 12:35:52.966  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:36:01.656  1258  1833 E Watchdog: !@Sync 24 [09-13 12:36:01.666]
,09-13 12:36:02.996  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 283 (W:30), CP = 34, LCD = 0
,09-13 12:36:02.996  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:36:03.756  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-13 12:36:03.756  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-13 12:36:03.836  2106  2159 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 74ms lastUpdatedAfter : 180288ms
,09-13 12:36:13.016  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 282 (W:30), CP = 35, LCD = 0
,09-13 12:36:13.016  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:36:13.736  1258  2391 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 12:36:13.736  1258  2391 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4375, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 12:36:13.736  1258  2391 D BatteryService: online:4, current avg:-2, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-3
09-13 12:36:13.736  1258  1258 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:36:13.746  1714  1714 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:36:13.746  1714  1714 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:36:13.746  1714  1714 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-13 12:36:13.756  2552  2552 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:36:13.756  2552  3097 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:36:13.766  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-13 12:36:13.766  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:36:13.766  1714  1714 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:36:23.046  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 282 (W:30), CP = 35, LCD = 0
,09-13 12:36:23.046  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:36:31.656  1258  1833 E Watchdog: !@Sync 25 [09-13 12:36:31.667]
,09-13 12:36:33.066  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 282 (W:30), CP = 34, LCD = 0
,09-13 12:36:33.076  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:36:43.096  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 281 (W:30), CP = 34, LCD = 0
,09-13 12:36:43.096  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:36:43.786  1258  2391 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 12:36:43.786  1258  2391 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4371, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 12:36:43.786  1258  2391 D BatteryService: online:4, current avg:-2, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-3
,09-13 12:36:43.786  1258  1258 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:36:43.796  1714  1714 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:36:43.796  1714  1714 D PowerUI : priorPlugType = 2 mPlugType =  2
09-13 12:36:43.796  1714  1714 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:36:43.806  2552  2552 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:36:43.806  2552  3097 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:36:43.816  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:36:43.816  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:36:43.816  1714  1714 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:36:53.126  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 281 (W:30), CP = 34, LCD = 0
,09-13 12:36:53.126  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:37:01.656  1258  1833 E Watchdog: !@Sync 26 [09-13 12:37:01.668]
,09-13 12:37:03.146  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 281 (W:30), CP = 34, LCD = 0
,09-13 12:37:03.146  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:37:03.906  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-13 12:37:03.906  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-13 12:37:04.896  1258  2669 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
09-13 12:37:04.896  1258  2669 V MARsPolicyManager: updateSMDBValues
09-13 12:37:04.896  1258  1414 E MARsDBManager: updateDBAll : begin --size 1
,09-13 12:37:04.916  1258  1414 E MARsDBManager: updateDBAll : end
09-13 12:37:04.916  1258  1414 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,09-13 12:37:13.176  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:37:13.176  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:37:13.846  1258  2391 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:37:23.196  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 35, LCD = 0
,09-13 12:37:23.196  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:37:31.666  1258  1833 E Watchdog: !@Sync 27 [09-13 12:37:31.669]
,09-13 12:37:33.226  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:37:33.226  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:37:43.256  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:37:43.256  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:37:43.896  1258  2227 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:37:53.276  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:37:53.276  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:38:01.666  1258  1833 E Watchdog: !@Sync 28 [09-13 12:38:01.670]
,09-13 12:38:03.306  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
09-13 12:38:03.306  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:38:04.006  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-13 12:38:04.006  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-13 12:38:13.326  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:38:13.326  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:38:13.946  1258  2586 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:38:23.356  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:38:23.356  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:38:31.666  1258  1833 E Watchdog: !@Sync 29 [09-13 12:38:31.671]
,09-13 12:38:33.386  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:38:33.386  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:38:43.406  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:38:43.406  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:38:43.996  1258  1618 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:38:53.426  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:38:53.436  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:38:59.336  1258  1584 D TimaService: TIMA: TimaService scheduler is intialized. 
09-13 12:38:59.336  1258  1584 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,09-13 12:38:59.336  1258  1583 D TimaService: TimaServiceHandler.handleMessage what =1
,09-13 12:39:01.666  1258  1833 E Watchdog: !@Sync 30 [09-13 12:39:01.672],
,09-13 12:39:01.676  1258  1584 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,09-13 12:39:01.676  1258  1584 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,09-13 12:39:01.686  1258  1584 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,09-13 12:39:01.686  1258  1584 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,09-13 12:39:03.456  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:39:03.456  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:39:04.116  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-13 12:39:04.116  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-13 12:39:04.186  2106  2159 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 64ms lastUpdatedAfter : 180350ms
,09-13 12:39:06.376  1258  1589 V AlarmManager: Expired Alarm result :4
,09-13 12:39:06.386  1714  1714 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
09-13 12:39:06.386  1714  1714 D KeyguardUpdateMonitor: handleTimeUpdate
,09-13 12:39:06.386  1714  1714 D Clock   : received broadcast android.intent.action.TIME_TICK
,09-13 12:39:06.386  1258  1377 V MARsPolicyManager: executePolicy policy  applockerpolicy(3) reason App Locker -- 10Min
,09-13 12:39:06.406  2992  2997 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 12:39:06.406  2992  2997 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
,09-13 12:39:06.416  2992  2997 I WCNSS_FILTER: do_write: IBS write: fd
,09-13 12:39:06.426  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,09-13 12:39:06.436  2992  2992 I WCNSS_FILTER: do_write: IBS write: fc
,09-13 12:39:06.436  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
09-13 12:39:06.436  1714  1714 D DateView: received broadcast android.intent.action.TIME_TICK
09-13 12:39:06.436  2992  2997 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 12:39:06.436  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,09-13 12:39:06.456  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
,09-13 12:39:06.456  2992  2997 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 12:39:06.456  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,09-13 12:39:06.466  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
09-13 12:39:06.466  2992  2997 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 12:39:06.466  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,09-13 12:39:06.476  4777  4777 D [WeatherWidget(1210)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB74266231DDCB0F9D898ABD6AE7EAFE9924B51C1628AB73EB6B27EF850A160BD15DCFDBE96F420541C45EF3419D3AD67E2]}
,09-13 12:39:06.476  4777  4777 D [WeatherWidget(1210)]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,09-13 12:39:06.476  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
,09-13 12:39:06.476  2992  2997 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 12:39:06.476  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,09-13 12:39:06.496  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
09-13 12:39:06.496  2992  2997 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0,
09-13 12:39:06.496  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,09-13 12:39:06.506  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
09-13 12:39:06.506  2992  2997 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
,09-13 12:39:06.506  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,09-13 12:39:06.516  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15,
09-13 12:39:06.516  2992  2997 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 12:39:06.516  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,09-13 12:39:06.526  2552  3047 E bt_btm  : outstanding rand generation exceeded max allowed 
,09-13 12:39:06.536  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
,09-13 12:39:06.536  2992  2997 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 12:39:06.536  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
09-13 12:39:06.536  2552  3047 E bt_btm  : outstanding rand generation exceeded max allowed 
,09-13 12:39:06.546  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15,
09-13 12:39:06.546  2992  2997 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 12:39:06.546  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,09-13 12:39:06.546  2552  3047 E bt_btm  : outstanding rand generation exceeded max allowed 
,09-13 12:39:06.556  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15,
09-13 12:39:06.556  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 10 : bytes_written: 10
09-13 12:39:06.566  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-13 12:39:06.566  2992  2997 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 12:39:06.566  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
09-13 12:39:06.566  2552  3047 E bt_btm  : outstanding rand generation exceeded max allowed 
,09-13 12:39:06.576  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15,
09-13 12:39:06.576  2992  2997 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 12:39:06.576  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
09-13 12:39:06.576  2552  3047 E bt_btm  : outstanding rand generation exceeded max allowed 
,09-13 12:39:06.586  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15,
09-13 12:39:06.586  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 10 : bytes_written: 10
09-13 12:39:06.586  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-13 12:39:06.586  2992  2997 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 12:39:06.586  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,09-13 12:39:06.596  1258  1989 V AlarmManager:  remove PendingIntent] PendingIntent{f8c185: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}},
,09-13 12:39:06.596  1258  2215 V AlarmManager:  remove PendingIntent] PendingIntent{6bf1bda: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}},
,09-13 12:39:06.606  1258  2636 V AlarmManager:  remove PendingIntent] PendingIntent{e77780b: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.606  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
,09-13 12:39:06.606  2992  2997 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
,09-13 12:39:06.606  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
09-13 12:39:06.606  1258  2227 V AlarmManager:  remove PendingIntent] PendingIntent{2f3a6e8: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.616  1258  2391 V AlarmManager:  remove PendingIntent] PendingIntent{e08f101: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}},
,09-13 12:39:06.616  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15,
09-13 12:39:06.616  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-13 12:39:06.616  1258  1989 V AlarmManager:  remove PendingIntent] PendingIntent{b031ba6: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.616  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 12:39:06.616  2992  2997 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 12:39:06.616  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,09-13 12:39:06.626  1258  2215 V AlarmManager:  remove PendingIntent] PendingIntent{b2389e7: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.626  1258  2636 V AlarmManager:  remove PendingIntent] PendingIntent{1d04994: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.636  1258  2227 V AlarmManager:  remove PendingIntent] PendingIntent{8929c3d: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
09-13 12:39:06.636  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
09-13 12:39:06.636  2992  2997 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 12:39:06.636  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,09-13 12:39:06.636  1258  2391 V AlarmManager:  remove PendingIntent] PendingIntent{6354c32: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.636  1258  1989 V AlarmManager:  remove PendingIntent] PendingIntent{294dd83: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}},
,09-13 12:39:06.646  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
09-13 12:39:06.646  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
,09-13 12:39:06.646  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 12:39:06.646  2992  2997 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 12:39:06.646  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
09-13 12:39:06.646  1258  2215 V AlarmManager:  remove PendingIntent] PendingIntent{b326b00: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.656  1258  2636 V AlarmManager:  remove PendingIntent] PendingIntent{311bf39: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.656  1258  2227 V AlarmManager:  remove PendingIntent] PendingIntent{5e7f97e: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}},
,09-13 12:39:06.656  1258  2391 V AlarmManager:  remove PendingIntent] PendingIntent{73dcedf: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}},
09-13 12:39:06.666  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
09-13 12:39:06.666  2992  2997 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 12:39:06.666  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,09-13 12:39:06.666  1258  1989 V AlarmManager:  remove PendingIntent] PendingIntent{9d3372c: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.666  1258  2215 V AlarmManager:  remove PendingIntent] PendingIntent{1c615f5: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.676  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15,
09-13 12:39:06.676  1258  2636 V AlarmManager:  remove PendingIntent] PendingIntent{c862f8a: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
09-13 12:39:06.676  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-13 12:39:06.676  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 12:39:06.676  2992  2997 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 12:39:06.676  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,09-13 12:39:06.676  1258  2227 V AlarmManager:  remove PendingIntent] PendingIntent{65a79fb: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.686  1258  2391 V AlarmManager:  remove PendingIntent] PendingIntent{8d29a18: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}},
,09-13 12:39:06.686  1258  1989 V AlarmManager:  remove PendingIntent] PendingIntent{32f1c71: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}},
09-13 12:39:06.686  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
09-13 12:39:06.686  2992  2997 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 12:39:06.686  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4,
,09-13 12:39:06.696  1258  2215 V AlarmManager:  remove PendingIntent] PendingIntent{61fba56: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}},
,09-13 12:39:06.696  1258  2636 V AlarmManager:  remove PendingIntent] PendingIntent{accbad7: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.706  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15,
09-13 12:39:06.706  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-13 12:39:06.706  1258  2227 V AlarmManager:  remove PendingIntent] PendingIntent{3633fc4: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
09-13 12:39:06.706  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 12:39:06.706  2992  2997 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 12:39:06.706  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,09-13 12:39:06.706  1258  2391 V AlarmManager:  remove PendingIntent] PendingIntent{4480ead: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}},
,09-13 12:39:06.716  1258  1989 V AlarmManager:  remove PendingIntent] PendingIntent{df525e2: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.716  1258  2215 V AlarmManager:  remove PendingIntent] PendingIntent{1b82d73: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.716  2992  2997 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0,
09-13 12:39:06.716  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
09-13 12:39:06.716  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
,09-13 12:39:06.716  1258  2636 V AlarmManager:  remove PendingIntent] PendingIntent{3369430: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.726  1258  2227 V AlarmManager:  remove PendingIntent] PendingIntent{c83e8a9: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.726  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
,09-13 12:39:06.736  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-13 12:39:06.736  1258  2391 V AlarmManager:  remove PendingIntent] PendingIntent{c3be2e: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
09-13 12:39:06.736  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 12:39:06.736  2992  2997 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 12:39:06.736  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,09-13 12:39:06.736  1258  1989 V AlarmManager:  remove PendingIntent] PendingIntent{cde2dcf: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.736  1258  2215 V AlarmManager:  remove PendingIntent] PendingIntent{9a8c35c: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.746  1258  2636 V AlarmManager:  remove PendingIntent] PendingIntent{d896665: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.746  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15,
09-13 12:39:06.746  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-13 12:39:06.746  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 12:39:06.746  2992  2997 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 12:39:06.746  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,09-13 12:39:06.746  1258  2227 V AlarmManager:  remove PendingIntent] PendingIntent{7d18f3a: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}},
,09-13 12:39:06.756  1258  2391 V AlarmManager:  remove PendingIntent] PendingIntent{eb9d7eb: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.756  1258  1989 V AlarmManager:  remove PendingIntent] PendingIntent{facb948: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}},
09-13 12:39:06.756  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15,
09-13 12:39:06.756  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-13 12:39:06.766  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 12:39:06.766  2992  2997 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 12:39:06.766  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,09-13 12:39:06.766  1258  2215 V AlarmManager:  remove PendingIntent] PendingIntent{2af03e1: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}},
,09-13 12:39:06.766  1258  2636 V AlarmManager:  remove PendingIntent] PendingIntent{8b96506: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}},
,09-13 12:39:06.776  1258  2227 V AlarmManager:  remove PendingIntent] PendingIntent{c5c07c7: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}},
09-13 12:39:06.776  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
09-13 12:39:06.776  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
,09-13 12:39:06.776  2992  2997 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 12:39:06.776  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 12:39:06.776  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,09-13 12:39:06.776  1258  2391 V AlarmManager:  remove PendingIntent] PendingIntent{87821f4: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.786  1258  1989 V AlarmManager:  remove PendingIntent] PendingIntent{c36fd1d: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.786  1258  2215 V AlarmManager:  remove PendingIntent] PendingIntent{5f6cb92: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.786  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
09-13 12:39:06.786  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-13 12:39:06.786  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 12:39:06.786  2992  2997 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
,09-13 12:39:06.786  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,09-13 12:39:06.796  1258  2636 V AlarmManager:  remove PendingIntent] PendingIntent{1075963: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.796  1258  2227 V AlarmManager:  remove PendingIntent] PendingIntent{2ef6960: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}},
,09-13 12:39:06.806  1258  2391 V AlarmManager:  remove PendingIntent] PendingIntent{24b4e19: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.806  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-13 12:39:06.806  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
09-13 12:39:06.806  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-13 12:39:06.806  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-13 12:39:06.806  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 12:39:06.806  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12,
09-13 12:39:06.806  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 12:39:06.806  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-13 12:39:06.806  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8,
09-13 12:39:06.806  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-13 12:39:06.806  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 12:39:06.806  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12,
09-13 12:39:06.806  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 12:39:06.806  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-13 12:39:06.806  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 12:39:06.806  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-13 12:39:06.806  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 12:39:06.816  1258  1989 V AlarmManager:  remove PendingIntent] PendingIntent{c320ede: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
09-13 12:39:06.816  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-13 12:39:06.816  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 12:39:06.816  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-13 12:39:06.816  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 12:39:06.816  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
,09-13 12:39:06.816  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 12:39:06.816  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
,09-13 12:39:06.816  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 12:39:06.816  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-13 12:39:06.816  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 12:39:06.816  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-13 12:39:06.816  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 12:39:06.816  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-13 12:39:06.816  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 12:39:06.816  2992  2997 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-13 12:39:06.816  1258  2215 V AlarmManager:  remove PendingIntent] PendingIntent{f8c28bf: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.816  2992  2992 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-13 12:39:06.826  1258  2636 V AlarmManager:  remove PendingIntent] PendingIntent{5d1bb8c: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.826  1258  2227 V AlarmManager:  remove PendingIntent] PendingIntent{bb9b2d5: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.826  1258  2391 V AlarmManager:  remove PendingIntent] PendingIntent{84c3aea: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.836  1258  1989 V AlarmManager:  remove PendingIntent] PendingIntent{d6491db: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.836  1258  2215 V AlarmManager:  remove PendingIntent] PendingIntent{2a50478: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.846  1258  2636 V AlarmManager:  remove PendingIntent] PendingIntent{46fa751: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}},
,09-13 12:39:06.846  1258  2227 V AlarmManager:  remove PendingIntent] PendingIntent{22b1bb6: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}},
,09-13 12:39:06.846  1258  2391 V AlarmManager:  remove PendingIntent] PendingIntent{39070b7: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}},
,09-13 12:39:06.856  1258  1989 V AlarmManager:  remove PendingIntent] PendingIntent{b61f024: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}},
,09-13 12:39:06.856  1258  2215 V AlarmManager:  remove PendingIntent] PendingIntent{fb6678d: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}},
,09-13 12:39:06.866  1258  2636 V AlarmManager:  remove PendingIntent] PendingIntent{8453d42: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.866  1258  2227 V AlarmManager:  remove PendingIntent] PendingIntent{1316153: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.876  1258  2391 V AlarmManager:  remove PendingIntent] PendingIntent{6dfea90: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.876  1258  1989 V AlarmManager:  remove PendingIntent] PendingIntent{22eef89: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.876  1258  2215 V AlarmManager:  remove PendingIntent] PendingIntent{7edeb8e: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.886  1258  2636 V AlarmManager:  remove PendingIntent] PendingIntent{be6bfaf: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.886  1258  2227 V AlarmManager:  remove PendingIntent] PendingIntent{11fbc: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}},
,09-13 12:39:06.896  1258  2391 V AlarmManager:  remove PendingIntent] PendingIntent{f8dfb45: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}},
,09-13 12:39:06.896  1258  1989 V AlarmManager:  remove PendingIntent] PendingIntent{e61329a: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.896  1258  2215 V AlarmManager:  remove PendingIntent] PendingIntent{9e9a7cb: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.906  1258  2636 V AlarmManager:  remove PendingIntent] PendingIntent{b9e7ba8: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.906  1258  2227 V AlarmManager:  remove PendingIntent] PendingIntent{81806c1: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.906  1258  2391 V AlarmManager:  remove PendingIntent] PendingIntent{e8fde66: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.916  1258  1989 V AlarmManager:  remove PendingIntent] PendingIntent{1e8f5a7: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}},
,09-13 12:39:06.916  1258  2215 V AlarmManager:  remove PendingIntent] PendingIntent{133aa54: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.916  1258  2636 V AlarmManager:  remove PendingIntent] PendingIntent{1dd4dfd: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.926  1258  2227 V AlarmManager:  remove PendingIntent] PendingIntent{7ab7af2: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.926  1258  2391 V AlarmManager:  remove PendingIntent] PendingIntent{ca54543: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.936  1258  1989 V AlarmManager:  remove PendingIntent] PendingIntent{24b17c0: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.936  1258  2215 V AlarmManager:  remove PendingIntent] PendingIntent{9b5ccf9: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.936  1258  2636 V AlarmManager:  remove PendingIntent] PendingIntent{872543e: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}},
,09-13 12:39:06.946  1258  2227 V AlarmManager:  remove PendingIntent] PendingIntent{44cf29f: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.946  1258  2391 V AlarmManager:  remove PendingIntent] PendingIntent{ca9efec: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.956  1258  1989 V AlarmManager:  remove PendingIntent] PendingIntent{7fd3fb5: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:06.956  1258  2215 V AlarmManager:  remove PendingIntent] PendingIntent{b3b764a: PendingIntentRecord{75e16fc com.android.bluetooth broadcastIntent}}
,09-13 12:39:07.646   715   715 I MSM-irqbalance: Decided to move IRQ215 from CPU1 to CPU0
,09-13 12:39:07.816  2992  3051 I WCNSS_FILTER: do_write: IBS write: fe
09-13 12:39:07.816  2992  3051 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-13 12:39:12.646   715   715 I MSM-irqbalance: Decided to move IRQ166 from CPU1 to CPU0
,09-13 12:39:13.486  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 35, LCD = 0
,09-13 12:39:13.486  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:39:13.586  1258  1273 I art     : Background sticky concurrent mark sweep GC freed 44280(6MB) AllocSpace objects, 375(7MB) LOS objects, 28% free, 37MB/51MB, paused 3.122ms total 100.439ms
,09-13 12:39:14.046  1258  2010 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:39:17.646   715   715 I MSM-irqbalance: Decided to move IRQ200 from CPU1 to CPU0
,09-13 12:39:23.506  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 35, LCD = 0
,09-13 12:39:23.506  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:39:31.666  1258  1833 E Watchdog: !@Sync 31 [09-13 12:39:31.673]
,09-13 12:39:33.526  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:39:33.536  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:39:43.556  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:39:43.556  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:39:44.096  1258  1618 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:39:53.586  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:39:53.586  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:39:59.996  1258  1589 V AlarmManager: Expired Alarm result :8
,09-13 12:40:01.666  1258  1833 E Watchdog: !@Sync 32 [09-13 12:40:01.674]
,09-13 12:40:03.606  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:40:03.606  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:40:04.286  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-13 12:40:04.286  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-13 12:40:13.626  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:40:13.626  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:40:14.146  1258  1304 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:40:23.656  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:40:23.656  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:40:31.666  1258  1833 E Watchdog: !@Sync 33 [09-13 12:40:31.675]
,09-13 12:40:33.676  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:40:33.676  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:40:43.696  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:40:43.696  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:40:44.206  1258  2215 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:40:53.726  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:40:53.726  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:41:01.666  1258  1833 E Watchdog: !@Sync 34 [09-13 12:41:01.676]
,09-13 12:41:03.746  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:41:03.746  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:41:04.316  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-13 12:41:04.316  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-13 12:41:13.776  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:41:13.776  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:41:14.256  1258  2011 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 12:41:14.256  1258  2011 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4375, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 12:41:14.256  1258  2011 D BatteryService: online:4, current avg:-2, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-3
09-13 12:41:14.256  1258  1258 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:41:14.256  1714  1714 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:41:14.256  1714  1714 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:41:14.256  1714  1714 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-13 12:41:14.266  2552  2552 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:41:14.266  2552  3097 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:41:14.276  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:41:14.276  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:41:14.276  1714  1714 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:41:23.796  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:41:23.796  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:41:31.666  1258  1833 E Watchdog: !@Sync 35 [09-13 12:41:31.677]
,09-13 12:41:33.826  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:41:33.826  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:41:43.846  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:41:43.846  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:41:44.306  1258  2011 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 12:41:44.306  1258  2011 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4371, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 12:41:44.306  1258  2011 D BatteryService: online:4, current avg:-2, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-3
,09-13 12:41:44.306  1258  1258 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:41:44.306  1714  1714 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:41:44.306  1714  1714 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:41:44.316  1714  1714 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-13 12:41:44.316  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-13 12:41:44.316  2552  2552 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:41:44.316  2552  3097 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:41:44.336  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:41:44.336  1714  1714 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:41:53.866  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:41:53.876  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:42:01.666  1258  1833 E Watchdog: !@Sync 36 [09-13 12:42:01.678]
,09-13 12:42:03.896  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:42:03.896  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:42:04.426  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-13 12:42:04.426  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-13 12:42:04.486  2106  2159 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 60ms lastUpdatedAfter : 180305ms
,09-13 12:42:13.916  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:42:13.926  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:42:14.356  1258  2011 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:42:23.946  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:42:23.946  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:42:31.676  1258  1833 E Watchdog: !@Sync 37 [09-13 12:42:31.679]
,09-13 12:42:33.966  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:42:33.966  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:42:43.996  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:42:43.996  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:42:44.406  1258  1989 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:42:54.016  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:42:54.016  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:43:01.676  1258  1833 E Watchdog: !@Sync 38 [09-13 12:43:01.680]
,09-13 12:43:04.046  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
09-13 12:43:04.046  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:43:04.526  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-13 12:43:04.526  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-13 12:43:14.066  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:43:14.066  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:43:14.456  1258  2585 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 12:43:14.456  1258  2585 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4375, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 12:43:14.456  1258  2585 D BatteryService: online:4, current avg:-2, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-3
09-13 12:43:14.456  1258  1258 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:43:14.466  1714  1714 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:43:14.466  1714  1714 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:43:14.466  1714  1714 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-13 12:43:14.466  2552  2552 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:43:14.466  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:43:14.466  2552  3097 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-13 12:43:14.466  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:43:14.466  1714  1714 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:43:24.086  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:43:24.086  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:43:31.676  1258  1833 E Watchdog: !@Sync 39 [09-13 12:43:31.681]
,09-13 12:43:34.116  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:43:34.116  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:43:44.136  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:43:44.146  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:43:44.506  1258  2215 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 12:43:44.506  1258  2215 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4371, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 12:43:44.506  1258  2215 D BatteryService: online:4, current avg:-2, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-3
09-13 12:43:44.506  1258  1258 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:43:44.516  1714  1714 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:43:44.516  1714  1714 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:43:44.516  1714  1714 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-13 12:43:44.516  2552  2552 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:43:44.516  2552  3097 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:43:44.536  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-13 12:43:44.536  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:43:44.536  1714  1714 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:43:54.166  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:43:54.166  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:43:59.336  1258  1584 D TimaService: TIMA: TimaService scheduler is intialized. 
09-13 12:43:59.336  1258  1584 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
09-13 12:43:59.336  1258  1583 D TimaService: TimaServiceHandler.handleMessage what =1
,09-13 12:43:59.646  1258  1368 I UsageStatsService: User[0] Flushing usage stats to disk
,09-13 12:44:00.616  1258  1584 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,09-13 12:44:00.616  1258  1584 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,09-13 12:44:00.626  1258  1584 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,09-13 12:44:00.626  1258  1584 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,09-13 12:44:01.676  1258  1833 E Watchdog: !@Sync 40 [09-13 12:44:01.682]
,09-13 12:44:04.186  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:44:04.186  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:44:04.536  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-13 12:44:04.536  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-13 12:44:14.216  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:44:14.216  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:44:14.556  1258  2586 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:44:14.556  1258  2586 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4371, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 12:44:14.556  1258  2586 D BatteryService: online:4, current avg:-2, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-3
09-13 12:44:14.556  1258  1258 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:44:14.566  1714  1714 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:44:14.566  1714  1714 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:44:14.566  1714  1714 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-13 12:44:14.566  2552  2552 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:44:14.576  2552  3097 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:44:14.586  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-13 12:44:14.586  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:44:14.586  1714  1714 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:44:24.246  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:44:24.246  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:44:31.676  1258  1833 E Watchdog: !@Sync 41 [09-13 12:44:31.683]
,09-13 12:44:34.266  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:44:34.266  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:44:44.296  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:44:44.296  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:44:44.606  1258  2586 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:44:54.316  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:44:54.316  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:45:01.676  1258  1833 E Watchdog: !@Sync 42 [09-13 12:45:01.684]
,09-13 12:45:04.346  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
09-13 12:45:04.346  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:45:04.636  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-13 12:45:04.636  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-13 12:45:04.706  2106  2159 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 65ms lastUpdatedAfter : 180220ms
,09-13 12:45:14.366  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:45:14.366  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:45:14.666  1258  1304 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:45:24.396  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:45:24.396  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:45:31.676  1258  1833 E Watchdog: !@Sync 43 [09-13 12:45:31.685]
,09-13 12:45:34.416  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:45:34.426  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:45:44.446  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:45:44.446  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:45:44.716  1258  1618 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:45:54.466  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:45:54.466  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:46:01.676  1258  1833 E Watchdog: !@Sync 44 [09-13 12:46:01.686]
,09-13 12:46:04.496  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:46:04.496  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:46:04.816  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-13 12:46:04.816  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-13 12:46:14.526  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:46:14.526  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:46:14.766  1258  2391 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:46:24.546  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:46:24.546  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:46:31.676  1258  1833 E Watchdog: !@Sync 45 [09-13 12:46:31.687]
,09-13 12:46:34.566  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:46:34.566  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:46:44.596  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:46:44.596  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:46:44.816  1258  2227 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:46:54.626  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
09-13 12:46:54.626  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:47:01.676  1258  1833 E Watchdog: !@Sync 46 [09-13 12:47:01.688]
,09-13 12:47:04.646  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:47:04.646  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:47:04.916  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-13 12:47:04.916  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-13 12:47:14.666  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:47:14.666  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:47:14.856  1258  1303 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:47:24.696  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:47:24.696  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:47:31.686  1258  1833 E Watchdog: !@Sync 47 [09-13 12:47:31.689]
,09-13 12:47:34.726  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
09-13 12:47:34.726  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:47:44.746  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:47:44.746  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:47:44.906  1258  2215 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 12:47:44.906  1258  2215 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4371, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 12:47:44.906  1258  2215 D BatteryService: online:4, current avg:-6, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-11
09-13 12:47:44.906  1258  1258 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:47:44.916  1714  1714 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:47:44.916  1714  1714 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:47:44.916  1714  1714 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-13 12:47:44.916  2552  2552 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:47:44.916  2552  3097 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:47:44.936  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:47:44.936  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:47:44.936  1714  1714 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:47:54.766  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:47:54.776  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:48:01.686  1258  1833 E Watchdog: !@Sync 48 [09-13 12:48:01.690]
,09-13 12:48:04.796  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:48:04.796  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:48:05.006  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-13 12:48:05.006  2106  2159 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-13 12:48:05.066  2106  2159 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 60ms lastUpdatedAfter : 180359ms
,09-13 12:48:14.826  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:48:14.826  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:48:14.956  1258  2011 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 12:48:14.956  1258  2011 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4371, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 12:48:14.956  1258  2011 D BatteryService: online:4, current avg:-6, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-3
09-13 12:48:14.956  1258  1258 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:48:14.966  1714  1714 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:48:14.966  1714  1714 D PowerUI : priorPlugType = 2 mPlugType =  2
09-13 12:48:14.966  1714  1714 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:48:14.966  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:48:14.966  2552  2552 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:48:14.966  2552  3097 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:48:14.986  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:48:14.986  1714  1714 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:48:24.846  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
09-13 12:48:24.846  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:48:31.686  1258  1833 E Watchdog: !@Sync 49 [09-13 12:48:31.691]
,09-13 12:48:34.876  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:48:34.876  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:48:44.896  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:48:44.896  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:48:45.016  1258  1986 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 12:48:45.016  1258  1986 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4371, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 12:48:45.016  1258  1986 D BatteryService: online:4, current avg:-3, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-3
09-13 12:48:45.016  1258  1258 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:48:45.016  1714  1714 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:48:45.016  1714  1714 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 12:48:45.016  1714  1714 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-13 12:48:45.026  2552  2552 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:48:45.026  2552  3097 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:48:45.036  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:48:45.036  1714  1714 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 12:48:45.036  1714  1714 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:48:54.926  1258  3539 D SSRM:s  : SIOP:: AP = 280, PST = 280 (W:30), CP = 34, LCD = 0
,09-13 12:48:54.926  1258  3539 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,TIME-OUT KILL (timeout was 1400000ms),09-13 12:48:56.386  6128  6128 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-13 12:48:56.396  6128  6128 D AndroidRuntime: CheckJNI is OFF
09-13 12:48:56.396  6128  6128 D AndroidRuntime: readGMSProperty: start
09-13 12:48:56.396  6128  6128 D AndroidRuntime: readGMSProperty: already setted!!
09-13 12:48:56.396  6128  6128 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-13 12:48:56.396  6128  6128 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-13 12:48:56.396  6128  6128 D AndroidRuntime: readGMSProperty: end
09-13 12:48:56.396  6128  6128 D AndroidRuntime: addProductProperty: start
09-13 12:48:56.456  6128  6128 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-13 12:48:56.496  6128  6128 I Radio-JNI: register_android_hardware_Radio DONE
09-13 12:48:56.506  6128  6128 E AffinityControl: AffinityControl: registerfunction enter
09-13 12:48:56.516  6128  6128 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-13 12:48:56.536  1258  1304 D PackageManager: START PACKAGE DELETE: observer{111449751}
09-13 12:48:56.536  1258  1304 D PackageManager: pkg{<packageName>}
09-13 12:48:56.536  1258  1304 D PackageManager: user{0}
09-13 12:48:56.536  1258  1304 D PackageManager: caller{2000}
09-13 12:48:56.536  1258  1304 D PackageManager: flags{2}
09-13 12:48:56.536  1258  1304 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-13 12:48:56.536  1258  1304 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-13 12:48:56.536  1258  1304 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-13 12:48:56.536  1258  1304 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-13 12:48:56.536  1258  1304 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-13 12:48:56.536  1258  1424 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-13 12:48:56.536  1258  1424 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-13 12:48:56.536  1258  1424 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-13 12:48:56.536  1258  1424 D ApplicationPolicy: getApplicationUninstallationEnabled
09-13 12:48:56.536  1258  1424 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
09-13 12:48:56.536  1258  1424 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-13 12:48:56.536  1258  1424 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
09-13 12:48:56.536  1258  1424 D PackageManager: !@killApplicatoin: 10136, uninstall pkg
09-13 12:48:56.536  1258  1424 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-13 12:48:56.536  1258  1377 I ActivityManager: Force stopping com.test.thalitest appid=10136 user=-1: uninstall pkg
09-13 12:48:56.536  1258  1424 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
09-13 12:48:56.536  1258  1377 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=6006 ,hash=121986628 ,name=com.test.thalitest
09-13 12:48:56.536  1258  1377 I ActivityManager: Killing 6006:com.test.thalitest/u0a136 (adj 0): stop com.test.thalitest cause uninstall pkg
09-13 12:48:56.546  1258  1377 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
09-13 12:48:56.556  1258  1377 D ActivityManager: mDVFSHelper.acquire()
09-13 12:48:56.566  1258  1424 D AASAinstall: there is not AASApackages.xml file
09-13 12:48:56.686  1258  2215 D GraphicsStats: Buffer count: 5
09-13 12:48:56.686  1258  1986 I WindowState: WIN DEATH: Window{5b54ea4 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
09-13 12:48:56.686  1258  2585 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@9c05084)
09-13 12:48:56.686  1258  1630 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 12:48:56.686  1258  1630 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 12:48:56.686   445   460 E         : BitTube(): close sendFd (36)
09-13 12:48:56.686   445   460 E         : BitTube(): close sendFd (43)
09-13 12:48:56.686  1258  1630 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 12:48:56.686   445   460 I SurfaceFlinger: id=19 Removed NainActivit (6/11)
09-13 12:48:56.686   445  1957 I SurfaceFlinger: id=19 Removed NainActivit (-2/11)
09-13 12:48:56.686   445   466 I SurfaceFlinger: id=19 Removed NainActivit (-2/11)
09-13 12:48:56.826  1258  1424 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
09-13 12:48:56.896  1258  1424 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
09-13 12:48:56.896  1258  1377 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-13 12:48:56.896  1258  1377 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-13 12:48:56.896  1258  1377 E ActivityManager: Failure starting process com.test.thalitest
09-13 12:48:56.896  1258  1377 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-13 12:48:56.896  1258  1377 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5290)
09-13 12:48:56.896  1258  1377 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5206)
09-13 12:48:56.896  1258  1377 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5042)
09-13 12:48:56.896  1258  1377 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:2674)
09-13 12:48:56.896  1258  1377 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:3504)
09-13 12:48:56.896  1258  1377 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:2624)
09-13 12:48:56.896  1258  1377 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:5060)
09-13 12:48:56.896  1258  1377 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:5021)
09-13 12:48:56.896  1258  1377 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:7410)
09-13 12:48:56.896  1258  1377 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:9248)
09-13 12:48:56.896  1258  1377 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:8870)
09-13 12:48:56.896  1258  1377 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:9025)
09-13 12:48:56.896  1258  1377 E ActivityManager: 	at com.android.server.am.ActivityManagerService.access$900(ActivityManagerService.java:467)
09-13 12:48:56.896  1258  1377 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:2573)
09-13 12:48:56.896  1258  1377 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:48:56.896  1258  1377 E ActivityManager: 	at android.os.Looper.loop(Looper.java:158)
09-13 12:48:56.896  1258  1377 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 12:48:56.896  1258  1377 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-13 12:48:56.906  1258  1377 W VirtualScreenManagerService: moveTaskBackToDisplayIfNeeded(): top activity or app is null
09-13 12:48:56.906  1258  1377 I ActivityManager:   Force finishing activity ActivityRecord{f1d4e03 u0 com.test.thalitest/.MainActivity t19}
09-13 12:48:56.906   565   565 W keystore: ENTER clear_uid from uid 1000 for 10136
09-13 12:48:56.906  1258  1424 I art     : Starting a blocking GC Explicit
09-13 12:48:56.916  1258  1258 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
09-13 12:48:56.916  1997  1997 D Launcher: onRestart, Launcher: 63949136
09-13 12:48:56.926  1258  1377 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
09-13 12:48:56.926  1258  1377 D InputDispatcher: Focused application released
09-13 12:48:56.926  1997  1997 D Launcher: onStart, Launcher: 63949136
09-13 12:48:56.926  1997  1997 D Launcher.HomeView: onStart
09-13 12:48:56.926  1997  1997 D Launcher.MenuAppsGrid: updateGridSize:GRID_4x4 cellWidth:250  cellHeight:286
09-13 12:48:56.926  1997  6137 D WallpaperManager: 2048 / 2048 / 0
09-13 12:48:56.936  1997  1997 V ActivityThread: updateVisibility : ActivityRecord{55c8640 token=android.os.BinderProxy@cd43d6f {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : true
09-13 12:48:56.936  1258  1416 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-13 12:48:56.936  1258  1416 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:390)
09-13 12:48:56.936  1258  1416 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4721)
09-13 12:48:56.936  1258  1416 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2248)
09-13 12:48:56.936  1258  1416 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4429)
09-13 12:48:56.936  1258  1416 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13541)
09-13 12:48:56.936  1258  1416 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:48:56.936  1258  1416 W System.err: 	at android.os.Looper.loop(Looper.java:158)
09-13 12:48:56.936  1258  1416 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 12:48:56.936  1258  1416 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-13 12:48:56.936  1258  1416 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-13 12:48:56.936  1258  1416 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{2ff2c1c V.E...... R.....ID 0,0-0,0}
09-13 12:48:56.936  1258  1416 W WindowManager: Attempted to add application window with unknown token Token{6915180 ActivityRecord{f1d4e03 u0 com.test.thalitest/.MainActivity t19 f}}.  Aborting.
09-13 12:48:56.936  1258  1416 D ViewRootImpl: #3 mView = null
09-13 12:48:56.936  1258  1416 W WindowManager: Token{6915180 ActivityRecord{f1d4e03 u0 com.test.thalitest/.MainActivity t19 f}} already running, starting window not displayed. Unable to add window -- token Token{6915180 ActivityRecord{f1d4e03 u0 com.test.thalitest/.MainActivity t19 f}} is not valid; is your activity running?
09-13 12:48:56.936  1258  1416 W WindowManager: view not successfully added to wm, removing view
09-13 12:48:56.936   445   445 I SurfaceFlinger: id=20 createSurf (1120x1269),1 flag=4, VSBConnecti
09-13 12:48:56.936  1997  1997 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1480 636 span 6 2 (widgetid 2) [current Gridsize : GRID_4x4]
09-13 12:48:56.936  1258  1416 W WindowManager: Exception when adding starting window
09-13 12:48:56.936  1258  1416 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{2ff2c1c V.E...... R.....ID 0,0-0,0} not attached to window manager
09-13 12:48:56.936  1258  1416 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:454)
09-13 12:48:56.936  1258  1416 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:380)
09-13 12:48:56.936  1258  1416 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:140)
09-13 12:48:56.936  1258  1416 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4486)
09-13 12:48:56.936  1258  1416 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13541)
09-13 12:48:56.936  1258  1416 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:48:56.936  1258  1416 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-13 12:48:56.936  1258  1416 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 12:48:56.936  1258  1416 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-13 12:48:56.936  1997  1997 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Pogoda i zegar(widget id = 2) result hostview size = 1480 x 636
09-13 12:48:56.936  1997  1997 D LauncherAppWidgetHostView: setResizeScaleResult() 1480/ 636 scaleToResize = 1.0(widget id = 2)
09-13 12:48:56.946  1997  1997 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1480 308 span 6 1 (widgetid 3) [current Gridsize : GRID_4x4]
09-13 12:48:56.946  1997  1997 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Aplikacja Google(widget id = 3) result hostview size = 1480 x 308
09-13 12:48:56.946  1997  1997 D LauncherAppWidgetHostView: setResizeScaleResult() 1480/ 308 scaleToResize = 1.0(widget id = 3)
09-13 12:48:56.946  1997  1997 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1480 308 span 6 1 (widgetid 4) [current Gridsize : GRID_4x4]
09-13 12:48:56.946  1997  1997 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Galaxy Apps(widget id = 4) result hostview size = 1480 x 308
09-13 12:48:56.946  1997  1997 D LauncherAppWidgetHostView: setResizeScaleResult() 1480/ 308 scaleToResize = 1.0(widget id = 4)
09-13 12:48:56.956  1258  3539 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
09-13 12:48:56.956  1258  1303 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
09-13 12:48:56.956  1258  1303 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-13 12:48:56.956  1258  1258 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-13 12:48:56.956  1258  1258 I KnoxTimeoutHandler: Shared devices show user statefalse
09-13 12:48:56.956  1258  1258 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
09-13 12:48:56.976   445   445 I SurfaceFlinger: id=21 createSurf (1536x2048),1 flag=4, MauncherAct
09-13 12:48:56.986  1258  2594 V WindowStateAnimator: Finishing drawing window Window{815c814 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-13 12:48:56.996   445   445 I SurfaceFlinger: id=22 createSurf (1152x192),1 flag=4, VSBConnecti
09-13 12:48:56.996  1258  1416 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-13 12:48:56.996  1258  1258 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-13 12:48:56.996  1258  1416 D ActivityManager: mDVFSHelper.release()
09-13 12:48:56.996  1258  1416 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{9a9ab4e u0 com.samsung.android.MtpApplication/.USBConnection t18} time:1513105
09-13 12:48:56.996  1258  1258 I KnoxTimeoutHandler: SD activityfalse
09-13 12:48:57.006  3604  3604 V ActivityThread: updateVisibility : ActivityRecord{aa671a0 token=android.os.BinderProxy@53ece02 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
09-13 12:48:57.026  1258  1986 V WindowStateAnimator: Finishing drawing window Window{3cf2eb2 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-13 12:48:57.026  3604  3604 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@53ece02 time:1513131
09-13 12:48:57.026  1258  1416 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-13 12:48:57.026  1258  1258 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-13 12:48:57.026  1258  1258 I KnoxTimeoutHandler: SD activityfalse
09-13 12:48:57.056  1997  2257 V RenderScript: 0x7f85831000 Launching thread(s), CPUs 8
09-13 12:48:57.066  1258  2391 V WindowStateAnimator: Finishing drawing window Window{c3c1c67 u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: mDrawState=DRAW_PENDING
09-13 12:48:57.066  1997  1997 D Launcher.HomeView: onStop
09-13 12:48:57.066  1997  1997 D capture : ----destroy
09-13 12:48:57.066  1258  1416 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-13 12:48:57.066  1258  1258 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-13 12:48:57.066  1258  1416 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{b704663 u0 com.sec.android.app.launcher/.activities.LauncherActivity t15} time:1513177
09-13 12:48:57.066  1258  1258 I KnoxTimeoutHandler: SD activityfalse
09-13 12:48:57.066  1258  1258 I KnoxTimeoutHandler: Fullscreen and mCurrent is not KNOX user. Hence hide keyguard
09-13 12:48:57.126  1258  1424 I art     : Explicit concurrent mark sweep GC freed 190286(11MB) AllocSpace objects, 27(2MB) LOS objects, 33% free, 28MB/43MB, paused 2.974ms total 220.437ms
09-13 12:48:57.146  1258  1424 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-13 12:48:57.146  1258  1424 D AASAuninstall: userId = 0, info.removedAppID = 10136, info.uid = 10136, packageName = com.test.thalitest
09-13 12:48:57.146  1258  1424 D AASAinstall: there is not AASApackages.xml file
09-13 12:48:57.146  1258  1424 D PackageManager: result of delete: 1{111449751}
09-13 12:48:57.146  6128  6128 I art     : System.exit called, status: 0
09-13 12:48:57.146  6128  6128 I AndroidRuntime: VM exiting with result code 0.
09-13 12:48:57.146  1258  1424 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-13 12:48:57.146  1258  1424 D PackageManager: userId{-1}
09-13 12:48:57.146  1258  1424 D PackageManager: andCode{true}
09-13 12:48:57.156  1258  1424 I ActivityManager: Force stopping com.test.thalitest appid=10136 user=0: pkg removed
09-13 12:48:57.156  1258  1424 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=0 ,hash=175896993 ,name=com.test.thalitest
09-13 12:48:57.186  5762  6147 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
09-13 12:48:57.186  1258  1377 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-13 12:48:57.186  1258  1377 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
09-13 12:48:57.186  5762  6147 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
09-13 12:48:57.186  5762  6147 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
09-13 12:48:57.196  1714  1714 D ShortcutManager: onReceive : android.intent.action.PACKAGE_REMOVED
09-13 12:48:57.196  1714  1714 D ShortcutManager: onReceive : Intent.EXTRA_REPLACING false,com.test.thalitest
09-13 12:48:57.196  1714  1714 D CoverUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
09-13 12:48:57.206  1258  1591 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-13 12:48:57.206  1865  2388 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-13 12:48:57.216  5061  5078 I SystemBroadcastReceiver: [#CMH#] Received broadcast 
09-13 12:48:57.216  5061  5078 I ControllerEventHandler: [#CMH#] onPackageRemoved  null
09-13 12:48:57.216  5061  5078 I SystemBroadcastReceiver: [#CMH#] onReceive completed 
09-13 12:48:57.216  1258  1377 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{180c99e u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8505ca8 3939:com.samsung.klmsagent/u0a16}
09-13 12:48:57.216  3939  3939 I KLMS-2.6.094: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } | timestamp: Tue Sep 13 12:48:57 GMT+02:00 2016
09-13 12:48:57.216  1258  2391 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=2483, uid=10093 that is not exported from uid 10091
09-13 12:48:57.216  1794  1794 I Recents_MultiWindowAppListInfo: android.intent.action.PACKAGE_REMOVE
09-13 12:48:57.226  3939  3939 I KLMS-2.6.094: : KLMSAbstractReciever(): onReceive().END.
09-13 12:48:57.226  1973  1973 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-13 12:48:57.236  1258  1368 D EnterpriseDeviceManagerService: Package has changed for user 0
09-13 12:48:57.236  1258  1368 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-13 12:48:57.236  1258  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 12:48:57.236  1258  1620 V NetworkStats: removeUidsLocked() for UIDs [10136]
09-13 12:48:57.236  1258  1620 V NetworkStats: performPollLocked(flags=0x3)
09-13 12:48:57.236  1258  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 12:48:57.236  1258  1620 V NetworkStats: performPollLocked() took 5ms
09-13 12:48:57.246  3939  3939 I KLMS-2.6.094: : KLMSIntentService(): onCreate()
09-13 12:48:57.246  1258  1304 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{180c99e u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3aca49c 1258:system/1000}
09-13 12:48:57.246  3939  3939 I KLMS-2.6.094: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
09-13 12:48:57.246  3939  3939 I KLMS-2.6.094: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
09-13 12:48:57.246  3939  6151 I KLMS-2.6.094: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-13 12:48:57.246  3939  6151 D KLMS-2.6.094: : KLMSIntentService(): PACKAGE_REMOVED
09-13 12:48:57.246  3939  6151 I KLMS-2.6.094: : Systemprocess(): listeningToPackageRemoved().START
09-13 12:48:57.246  3939  6151 I KLMS-2.6.094: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
09-13 12:48:57.246  3939  6151 I KLMS-2.6.094: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
09-13 12:48:57.246  3939  6151 I KLMS-2.6.094: : MDMBridge(): getAllLicenseInfoFromSDK()
09-13 12:48:57.246  1258  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 12:48:57.246  1258  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 12:48:57.256  3939  6151 I KLMS-2.6.094: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
09-13 12:48:57.256  3939  6151 I KLMS-2.6.094: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
09-13 12:48:57.256  3939  6151 I KLMS-2.6.094: : MDMBridge(): getAllLicenseInfoFromSDK()
09-13 12:48:57.256  3939  6151 D KLMS-2.6.094: : Systemprocess(): arrayLicenseInfo is null
09-13 12:48:57.266  3939  6151 W SQLiteLog: (28) failed to open "/data/user/0/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)
09-13 12:48:57.266  3939  6151 E SQLiteDatabase: Failed to open database '/data/user/0/com.samsung.klmsagent/databases/klms.db'.
09-13 12:48:57.266  3939  6151 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 12:48:57.266  3939  6151 E SQLiteDatabase: #################################################################
09-13 12:48:57.266  3939  6151 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
09-13 12:48:57.266  3939  6151 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
09-13 12:48:57.266  3939  6151 E SQLiteDatabase: #################################################################
09-13 12:48:57.266  3939  6151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 12:48:57.266  3939  6151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
09-13 12:48:57.266  3939  6151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
09-13 12:48:57.266  3939  6151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 12:48:57.266  3939  6151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 12:48:57.266  3939  6151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 12:48:57.266  3939  6151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 12:48:57.266  3939  6151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 12:48:57.266  3939  6151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 12:48:57.266  3939  6151 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:639)
09-13 12:48:57.266  3939  6151 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
09-13 12:48:57.266  3939  6151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 12:48:57.266  3939  6151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 12:48:57.266  3939  6151 E SQLiteDatabase: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:88)
09-13 12:48:57.266  3939  6151 E SQLiteDatabase: 	at com.samsung.klmsagent.util.DataBaseUtils.checkKnoxLicenseActivationRecord(DataBaseUtils.java:323)
09-13 12:48:57.266  3939  6151 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforELM(Systemprocess.java:580)
09-13 12:48:57.266  3939  6151 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:517)
09-13 12:48:57.266  3939  6151 E SQLiteDatabase: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
09-13 12:48:57.266  3939  6151 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 12:48:57.266  3939  6151 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:48:57.266  3939  6151 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:158)
09-13 12:48:57.266  3939  6151 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 12:48:57.266  3939  6151 E SQLiteOpenHelper: Couldn't open klms.db for writing (will try read-only):
09-13 12:48:57.266  3939  6151 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 12:48:57.266  3939  6151 E SQLiteOpenHelper: #################################################################
09-13 12:48:57.266  3939  6151 E SQLiteOpenHelper: Error Code : 0 (SQLITE_OK)
09-13 12:48:57.266  3939  6151 E SQLiteOpenHelper: Caused By : not an error (code 0): Could not open the database in read/write mode.
09-13 12:48:57.266  3939  6151 E SQLiteOpenHelper: #################################################################
09-13 12:48:57.266  3939  6151 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 12:48:57.266  3939  6151 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
09-13 12:48:57.266  3939  6151 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
09-13 12:48:57.266  3939  6151 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 12:48:57.266  3939  6151 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 12:48:57.266  3939  6151 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 12:48:57.266  3939  6151 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 12:48:57.266  3939  6151 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 12:48:57.266  3939  6151 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 12:48:57.266  3939  6151 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:639)
09-13 12:48:57.266  3939  6151 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
09-13 12:48:57.266  3939  6151 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 12:48:57.266  3939  6151 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 12:48:57.266  3939  6151 E SQLiteOpenHelper: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:88)
09-13 12:48:57.266  3939  6151 E SQLiteOpenHelper: 	at com.samsung.klmsagent.util.DataBaseUtils.checkKnoxLicenseActivationRecord(DataBaseUtils.java:323)
09-13 12:48:57.266  3939  6151 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforELM(Systemprocess.java:580)
09-13 12:48:57.266  3939  6151 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:517)
09-13 12:48:57.266  3939  6151 E SQLiteOpenHelper: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
09-13 12:48:57.266  3939  6151 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 12:48:57.266  3939  6151 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:48:57.266  3939  6151 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:158)
09-13 12:48:57.266  3939  6151 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 12:48:57.266  3939  6151 W SQLiteOpenHelper: Opened klms.db in read-only mode
09-13 12:48:57.266  3939  6151 D KLMS-2.6.094: : DataSource(): Fetched Data from data base count : 0
09-13 12:48:57.276  1258  1304 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
09-13 12:48:57.276  1258  1304 D SettingsProvider: isChangeAllowed() : name = klm_eula_shown
09-13 12:48:57.276  1258  1304 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-13 12:48:57.276  1258  1304 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-13 12:48:57.276  1258  1304 D SettingsProvider: selectionArgs: false
09-13 12:48:57.276  1258  1304 D SettingsProvider: selectionArgs: 10016
09-13 12:48:57.276  1258  1304 D SettingsProvider: ret = -1
09-13 12:48:57.286  1258  1258 V AlarmManager: Remove alarm for next reason : android.intent.action.PACKAGE_REMOVED : package: com.test.thalitest
09-13 12:48:57.286  1258  1258 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
09-13 12:48:57.286  1258  1258 D UniversalCredentialManagerService: inside mPkgReciever onReceive : android.intent.action.PACKAGE_REMOVED
09-13 12:48:57.286  1258  1258 D UniversalCredentialManagerService: ACTION_PACKAGE_REMOVED is called....
09-13 12:48:57.286  1258  1258 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-13 12:48:57.286  1258  1258 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-13 12:48:57.286  1258  1258 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10136 container id = 0
09-13 12:48:57.296  1258  1258 I OTPFW   : ProvisionData::getAllEntries Enter
09-13 12:48:57.296  1258  1258 E OTPFW   : ProvisionData::getAllEntries Table is empty
09-13 12:48:57.296  1258  1258 E SDAgentPackageStateReceiver: Not going to handle 'com.test.thalitest'!
09-13 12:48:57.296  1258  1258 D UcmService: onReceive android.intent.action.PACKAGE_REMOVED
09-13 12:48:57.296  1258  1258 D UcmService: Package update in userId-0 and uid-10136
09-13 12:48:57.296  1258  1258 D GameManager.DatabaseHelper: removeGame(), packageName: com.test.thalitest, ret: 0
09-13 12:48:57.296  1258  1258 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-13 12:48:57.296  1258  1258 V EnterpriseBillingAsyncHandler: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-13 12:48:57.296  1258  1655 V EnterpriseBillingPolicyInternal: packageModification -  start - android.intent.action.PACKAGE_REMOVED
09-13 12:48:57.296  1258  1655 V EnterpriseBillingPolicyInternal: uID is 10136
09-13 12:48:57.296  1258  1655 V EnterpriseBillingPolicyInternal: Removed Packageuid is0
09-13 12:48:57.296  1258  1655 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-13 12:48:57.296  1258  1655 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-13 12:48:57.296  1258  1655 V EnterpriseBillingPolicyInternal: packageModificationReceiver - onreceive - personal application - profile null
09-13 12:48:57.296  1258  1258 D SdpManagerService:  ActionReceiver::onReceive() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-13 12:48:57.296  1258  1258 D SdpManagerService: ACTION_PACKAGE_REMOVED Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } DATA= package:com.test.thalitest UID 1000 userId 0
09-13 12:48:57.296  1258  1258 D SdpManagerService: ACTION_PACKAGE_REMOVED packageName:: com.test.thalitest
09-13 12:48:57.296  1258  1258 D EnterprisePartitionManager: SND -> {secure_fs remove_enc_dir}
09-13 12:48:57.306   382   438 D epmd    : Partition obj created
09-13 12:48:57.306   382   438 D epmd    : Partition::dump============== 0
09-13 12:48:57.306   382   438 D epmd    : Partition::mType > INTERNAL-SDCARD mSrcPath > /data/knox/secure_fs/enc_user mMntPath > /data/enc_user
09-13 12:48:57.306   382   438 D epmd    : Partition::SDP > not supported
09-13 12:48:57.306  1258  1426 D EnterprisePartitionManager: RCV <-
09-13 12:48:57.306   382   438 E epmd    : removeEncPkgDir ERROR
09-13 12:48:57.306  1258  1258 D EnterprisePartitionManager: RMV <-
09-13 12:48:57.306   382   438 D epmd    : deleting Partition object.
09-13 12:48:57.306  1258  1258 D EnterprisePartitionManager: event : 281 3 remove_enc_dir failed
09-13 12:48:57.306   382   438 W FrameworkListener: Handler 'secure_fs' error (No such file or directory)
09-13 12:48:57.306  1258  1258 D SdpManagerService: start document   : 
09-13 12:48:57.306  1258  1258 D SdpManagerService: start element    : engine_list
09-13 12:48:57.306  1258  1258 D SdpManagerService: start characters : 
09-13 12:48:57.306  1258  1258 D SdpManagerService: start element    : engine
09-13 12:48:57.306  1258  1258 D SdpManagerService:  attribte alias: android_0
09-13 12:48:57.306  1258  1258 D SdpManagerService:  attribte id: 0
09-13 12:48:57.306  1258  1258 D SdpManagerService: end element      : engine
09-13 12:48:57.306  1258  1258 D SdpManagerService: start characters : 
09-13 12:48:57.306  1258  1258 D SdpManagerService: end element      : engine_list
09-13 12:48:57.306  1258  1258 D SdpManagerService: end document     : 
09-13 12:48:57.306  1258  1258 W System.err: mkdir failed: EEXIST (File exists) : /data/system/users/0
09-13 12:48:57.306  1258  1258 E SdpManagerService: cant make directory /data/system/users/0
09-13 12:48:57.306  1258  1258 D SdpManagerService: start document   : 
09-13 12:48:57.306  1258  1258 D SdpManagerService: start element    : user
09-13 12:48:57.306  1258  1258 D SdpManagerService: end element      : user
09-13 12:48:57.306  1258  3539 D SSRM:bb : MSG_TYPE_APP_REMOVED::
09-13 12:48:57.306  1258  1258 D SdpUtil : num:0 index-0
09-13 12:48:57.306  1258  1258 D AccessibilityManagerService: checkUniversalSwitchState start:
09-13 12:48:57.306  1258  1258 D SdpUtil : detecected userId : 0
09-13 12:48:57.306  1258  1258 D SdpManagerService: end document     : 
09-13 12:48:57.306  1258  1258 E SdpManagerService: Can't find engine info [android_0]
09-13 12:48:57.306  1258  1258 V EnterpriseBillingAsyncHandler: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-13 12:48:57.306  1258  1655 V EnterpriseBillingPolicyInternal: packageModification -  start - android.intent.action.PACKAGE_FULLY_REMOVED
09-13 12:48:57.306  1258  1655 V EnterpriseBillingPolicyInternal: uID is 10136
09-13 12:48:57.306  1258  1655 V EnterpriseBillingPolicyInternal: Removed Packageuid is0
09-13 12:48:57.306  1258  1655 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-13 12:48:57.306  1258  1655 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-13 12:48:57.306  1258  1655 V EnterpriseBillingPolicyInternal: packageModificationReceiver - onreceive - personal application - profile null
09-13 12:48:57.316  5801  5815 E SQLiteLog: (10) unixWrite() File Descriptor : 20 gets errno : 30
09-13 12:48:57.316  5801  5815 E DatabaseUtils: Writing exception to parcel
09-13 12:48:57.316  5801  5815 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
09-13 12:48:57.316  5801  5815 E DatabaseUtils: #################################################################
09-13 12:48:57.316  5801  5815 E DatabaseUtils: Error Code : 778 (SQLITE_IOERR_WRITE)
09-13 12:48:57.316  5801  5815 E DatabaseUtils: Caused By : Disk I/O error occurred during 'write' operation.
09-13 12:48:57.316  5801  5815 E DatabaseUtils: 	(disk I/O error (code 778))
09-13 12:48:57.316  5801  5815 E DatabaseUtils: #################################################################
09-13 12:48:57.316  5801  5815 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 12:48:57.316  5801  5815 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:866)
09-13 12:48:57.316  5801  5815 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 12:48:57.316  5801  5815 E DatabaseUtils: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 12:48:57.316  5801  5815 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
09-13 12:48:57.316  5801  5815 E DatabaseUtils: 	at com.samsung.android.sm.database.SmProvider.delete(SmProvider.java:826)
09-13 12:48:57.316  5801  5815 E DatabaseUtils: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:352)
09-13 12:48:57.316  5801  5815 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:206)
09-13 12:48:57.316  5801  5815 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:453)
09-13 12:48:57.316  1258  1414 E MARsDBManager: Exception with contentResolver : disk I/O error (code 778)
09-13 12:48:57.316  1258  1414 E MARsDBManager: #################################################################
09-13 12:48:57.316  1258  1414 E MARsDBManager: Error Code : 778 (SQLITE_IOERR_WRITE)
09-13 12:48:57.316  1258  1414 E MARsDBManager: Caused By : Disk I/O error occurred during 'write' operation.
09-13 12:48:57.316  1258  1414 E MARsDBManager: 	(disk I/O error (code 778))
09-13 12:48:57.316  1258  1414 E MARsDBManager: #################################################################
09-13 12:48:57.316  1258  1414 E MARsDBManager: #################################################################
09-13 12:48:57.316  1258  1414 E MARsDBManager: Error Code : 778 (SQLITE_IOERR_WRITE)
09-13 12:48:57.316  1258  1414 E MARsDBManager: Caused By : Disk I/O error occurred during 'write' operation.
09-13 12:48:57.316  1258  1414 E MARsDBManager: 	(disk I/O error (code 778)
09-13 12:48:57.316  1258  1414 E MARsDBManager: #################################################################
09-13 12:48:57.316  1258  1414 E MARsDBManager: Error Code : 778 (SQLITE_IOERR_WRITE)
09-13 12:48:57.316  1258  1414 E MARsDBManager: Caused By : Disk I/O error occurred during 'write' operation.
09-13 12:48:57.316  1258  1414 E MARsDBManager: 	(disk I/O error (code 778))
09-13 12:48:57.316  1258  1414 E MARsDBManager: #################################################################)
09-13 12:48:57.316  1258  1414 E MARsDBManager: #################################################################
09-13 12:48:57.326  1258  1368 D UsbSettingsManager: clearDefaults: com.test.thalitest
09-13 12:48:57.326  1997  1997 E Launcher.Model: onPackageRemoved :com.test.thalitest

```
