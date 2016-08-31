#### Test 833712394bbb446_thali05_samsung-SM-T719 Logs


```
--------- beginning of system
,08-31 03:00:49.279  1131  3583 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
08-31 03:00:49.729  6007  6007 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-31 03:00:49.729  6007  6007 D AndroidRuntime: CheckJNI is OFF
08-31 03:00:49.729  6007  6007 D AndroidRuntime: readGMSProperty: start
08-31 03:00:49.729  6007  6007 D AndroidRuntime: readGMSProperty: already setted!!
08-31 03:00:49.729  6007  6007 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-31 03:00:49.729  6007  6007 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-31 03:00:49.729  6007  6007 D AndroidRuntime: readGMSProperty: end
08-31 03:00:49.729  6007  6007 D AndroidRuntime: addProductProperty: start
08-31 03:00:49.759  6007  6007 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-31 03:00:49.789  6007  6007 I Radio-JNI: register_android_hardware_Radio DONE
08-31 03:00:49.789  6007  6007 E AffinityControl: AffinityControl: registerfunction enter
08-31 03:00:49.809  6007  6007 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-31 03:00:49.839  1131  1718 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
08-31 03:00:49.849  1131  1718 D GameManagerService: identifyGamePackage. com.test.thalitest
08-31 03:00:49.849  1131  1718 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
08-31 03:00:49.869  1131  1718 D ActivityManager: mDVFSHelper.acquire()
08-31 03:00:49.869   444   444 I SurfaceFlinger: id=13 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-31 03:00:49.869   444   444 I SurfaceFlinger: id=14 createSurf (16x16),-1 flag=20004, EimLayer(An
08-31 03:00:49.879  1702  1702 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-31 03:00:49.879  1131  1718 D FocusedStackFrame: Set to : 0
08-31 03:00:49.879  1131  1131 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-31 03:00:49.879  1702  1702 D WallpaperService: MSG_WINDOW_RESIZED
08-31 03:00:49.879  1702  1702 D WallpaperService: updateSurface
08-31 03:00:49.879  1702  1702 V WallpaperService: Changes: creating=false format=false size=false
08-31 03:00:49.879  1702  1702 V WallpaperService: mWidth:2048 SurfaceWidth:2048 mHeight:2048 SurfaceHeigh:2048
08-31 03:00:49.879  1702  1702 D WallpaperService: relayout
08-31 03:00:49.879  1131  1718 V WindowManager: addAppToken: AppWindowToken{d06321a3e token=Token{720eaf9 ActivityRecord{17edc0 u0 com.test.thalitest/.MainActivity t18}}} to stack=2 task=18 at 0
08-31 03:00:49.879  1131  1131 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-31 03:00:49.889  1702  1702 V WallpaperService: Wallpaper size has changed: (2048, 2048)
08-31 03:00:49.889  1131  1399 D SecWifiDisplayUtil: Metadata value : SecSettings2
08-31 03:00:49.899  1131  1399 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{7f53316 V.E...... R.....ID 0,0-0,0}
08-31 03:00:49.899  6017  6017 E Zygote  : v2
08-31 03:00:49.899  6017  6017 I libpersona: KNOX_SDCARD checking this for 10136
08-31 03:00:49.899  6017  6017 I libpersona: KNOX_SDCARD not a persona
08-31 03:00:49.909   444   444 I SurfaceFlinger: id=15 createSurf (1536x2048),1 flag=404, uhalitest
08-31 03:00:49.909  1131  1718 I ActivityManager: Start proc 6017:com.test.thalitest/u0a136 for activity com.test.thalitest/.MainActivity
08-31 03:00:49.909  6017  6017 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-31 03:00:49.909  6017  6017 E Zygote  : accessInfo : 0
08-31 03:00:49.909  6017  6017 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-31 03:00:49.909  1131  1718 D InputDispatcher: Focused application set to: xxxx
08-31 03:00:49.909  1131  1399 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 48 - 0, 0) vi=Rect(0, 48 - 0, 0) or=1
08-31 03:00:49.909  6007  6007 D AndroidRuntime: Shutting down VM
08-31 03:00:49.909  1131  1619 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-31 03:00:49.929  6017  6017 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 03:00:49.929  6017  6017 D ActivityThread: Added TimaKeyStore provider
08-31 03:00:49.939  1131  1988 D ActivityManager:  Launching com.test.thalitest, updated priority
08-31 03:00:49.939  1993  1993 V ActivityThread: updateVisibility : ActivityRecord{c2b28ea token=android.os.BinderProxy@cc30f88 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
08-31 03:00:49.949  1131  1131 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
08-31 03:00:49.949  1131  1365 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-31 03:00:49.949  1131  1399 V WindowStateAnimator: Finishing drawing window Window{8154684 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-31 03:00:49.969   444  1421 I SurfaceFlinger: id=10 Removed MauncherAct (6/11)
08-31 03:00:49.969   444   474 I SurfaceFlinger: id=10 Removed MauncherAct (-2/11)
08-31 03:00:49.979  1993  1993 D Launcher: onTrimMemory. Level: 20
,08-31 03:00:50.249  1131  1988 I WindowManager: Screenshot max retries 4 of Token{720eaf9 ActivityRecord{17edc0 u0 com.test.thalitest/.MainActivity t18}} appWin=Window{8154684 u0 d0 Starting com.test.thalitest} drawState=4
,08-31 03:00:50.259  1131  1619 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-31 03:00:50.269  1131  3551 D GameManagerService: identifyGamePackage. com.test.thalitest
,08-31 03:00:50.279  1131  3551 D GameManagerService: identifyGamePackage. com.test.thalitest
,08-31 03:00:50.299  1131  2316 W ActivityManager: Permission Denial: getCurrentUser() from pid=6017, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
,08-31 03:00:50.309  6017  6017 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-31 03:00:50.309  6017  6017 D RelationGraph: garbageCollect()
,08-31 03:00:50.329  1131  1718 W ActivityManager: Permission Denial: getCurrentUser() from pid=6017, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
,08-31 03:00:50.339  6017  6017 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
,08-31 03:00:50.369  6017  6017 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-31 03:00:50.389  6017  6017 I cr_LibraryLoader: Time to load native libraries: 10 ms (timestamps 2664-2674)
08-31 03:00:50.389  6017  6017 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
,08-31 03:00:50.419  6017  6031 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-31 03:00:50.419  6017  6017 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9ac85b1}
,08-31 03:00:50.419  6017  6017 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
,08-31 03:00:50.429  6017  6017 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 03:00:50.449  6017  6017 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-31 03:00:50.509  6017  6017 I Adreno  : QUALCOMM build                   : 971aff5, Ic07f1cdce3
08-31 03:00:50.509  6017  6017 I Adreno  : Build Date                       : 03/29/16
08-31 03:00:50.509  6017  6017 I Adreno  : OpenGL ES Shader Compiler Version: XE031.06.00.02
08-31 03:00:50.509  6017  6017 I Adreno  : Local Branch                     : 
08-31 03:00:50.509  6017  6017 I Adreno  : Remote Branch                    : refs/tags/AU_LINUX_ANDROID_LA.BR.1.3.3.C2.06.00.01.205.077
08-31 03:00:50.509  6017  6017 I Adreno  : Remote Branch                    : NONE
08-31 03:00:50.509  6017  6017 I Adreno  : Reconstruct Branch               : NOTHING
,08-31 03:00:50.569  1131  2263 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10136
,08-31 03:00:50.569  1131  2263 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:851 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29617 com.android.server.am.ActivityManagerService.registerReceiver:22639 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3995 
,08-31 03:00:50.629  6017  6017 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-31 03:00:50.649  6017  6017 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-31 03:00:50.649  6017  6017 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-31 03:00:50.659  6017  6017 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-31 03:00:50.699  6017  6017 D SecWifiDisplayUtil: Metadata value : SecSettings2
,08-31 03:00:50.709  6017  6017 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{c8f8bf6 I.E...... R.....ID 0,0-0,0}
,08-31 03:00:50.709  6017  6055 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-31 03:00:50.719  1131  2013 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-31 03:00:50.719  1131  2013 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-31 03:00:50.719  1131  1131 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-31 03:00:50.719  1131  1131 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-31 03:00:50.729  6017  6031 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-31 03:00:50.739  6017  6017 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10136, CallingPid : 6017
,08-31 03:00:50.739  1131  1718 D ConnectivityService: listenForNetwork for Listen from uid/pid:10136/6017 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 03:00:50.739  1131  1628 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
08-31 03:00:50.739  1131  1628 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,fe80::4678:3eff:feeb:95ef/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -36]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-31 03:00:50.739  1131  1628 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-31 03:00:50.739  1131  1628 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-31 03:00:50.739  1131  1628 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-31 03:00:50.739  1131  1628 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-31 03:00:50.739  1131  1628 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-31 03:00:50.739  1131  1628 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
08-31 03:00:50.739  1131  1628 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 03:00:50.749  6017  6017 D SecWifiDisplayUtil: Metadata value : SecSettings2
,08-31 03:00:50.759   444   444 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=404, NainActivit
,08-31 03:00:50.769  6017  6055 I OpenGLRenderer: Initialized EGL, version 1.4
,08-31 03:00:50.789  6017  6017 V ActivityThread: updateVisibility : ActivityRecord{3c9e0c9 token=android.os.BinderProxy@a7996c {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-31 03:00:50.799  6017  6017 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 48 - 0, 0) vi=Rect(0, 48 - 0, 0) or=1
,08-31 03:00:50.829  6017  6055 E libGLESv2: HWUI Protection: wrong call from hwui context F: ES3-glCreateProgramSEC
,08-31 03:00:50.869  1131  1988 V WindowStateAnimator: Finishing drawing window Window{bbca74d u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
08-31 03:00:50.869  6017  6017 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@a7996c time:93153
08-31 03:00:50.869  1131  1399 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-31 03:00:50.869  1131  1131 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-31 03:00:50.869  1131  1399 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +620ms (total +987ms)
08-31 03:00:50.869  1131  1399 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{17edc0 u0 com.test.thalitest/.MainActivity t18} time:93159
08-31 03:00:50.869  1131  1399 D ActivityManager: mDVFSHelper.release()
08-31 03:00:50.869  1131  1399 D ViewRootImpl: #3 mView = null
08-31 03:00:50.879  1131  1131 I KnoxTimeoutHandler: SD activityfalse
08-31 03:00:50.879  1131  1131 I KnoxTimeoutHandler: Fullscreen and mCurrent is not KNOX user. Hence hide keyguard
08-31 03:00:50.879   444   474 I SurfaceFlinger: id=15 Removed uhalitest (6/11)
08-31 03:00:50.879  6017  6060 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 03:00:50.879   444   472 I SurfaceFlinger: id=15 Removed uhalitest (-2/11)
,08-31 03:00:50.929  6017  6017 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6017
,08-31 03:00:51.129  6017  6017 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 03:00:51.239  6017  6066 D jxcore_app_log: JniHelper::setJavaVM(0xf49fc000), pthread_self() = -630720208
,08-31 03:00:51.239  6017  6066 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 03:00:51.239  6017  6066 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 03:00:51.239  6017  6066 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 03:00:51.239  6017  6066 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 03:00:51.239  6017  6066 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-31 03:00:51.239  6017  6066 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10dea6 added. We now have 1 listener(s)
,08-31 03:00:51.239  6017  6066 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:EB:95:EE
,08-31 03:00:51.239  6017  6066 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:EB:95:EE"
08-31 03:00:51.239  6017  6066 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 03:00:51.239  6017  6066 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 03:00:51.239  6017  6066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 03:00:51.239  6017  6066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 03:00:51.239  6017  6066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 03:00:51.239  6017  6066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:78:3E:EB:95:EE
08-31 03:00:51.239  6017  6066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 03:00:51.239  6017  6066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 03:00:51.239  6017  6066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 03:00:51.239  6017  6066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 03:00:51.239  6017  6066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 03:00:51.239  6017  6066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 03:00:51.239  6017  6066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 03:00:51.239  6017  6066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 03:00:51.239  6017  6066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 03:00:51.239  6017  6066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-31 03:00:51.239  6017  6066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d817b3d added. We now have 1 listener(s)
08-31 03:00:51.239  6017  6066 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 03:00:51.249  6017  6066 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 03:00:51.249  6017  6066 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-31 03:00:51.249  6017  6066 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 03:00:51.249  6017  6066 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 03:00:51.249  6017  6066 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-31 03:00:51.249  6017  6066 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 03:00:51.249  6017  6066 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:EB:95:EE
,08-31 03:00:51.249  6017  6066 D BluetoothAdapter: STATE_ON
,08-31 03:00:51.249  6017  6066 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-31 03:00:51.249  6017  6066 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 03:00:51.249  6017  6066 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 03:00:51.249  6017  6066 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 03:00:51.249  6017  6066 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 03:00:51.249  6017  6066 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 03:00:51.249  6017  6066 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 03:00:51.249  6017  6066 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 03:00:51.249  6017  6066 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 03:00:51.259  6017  6066 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 03:00:51.259  6017  6066 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 03:00:51.259  6017  6066 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 03:00:51.259  6017  6017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 03:00:51.259  6017  6017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 03:00:51.289  6017  6017 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 03:00:51.469   713   713 I MSM-irqbalance: Decided to move IRQ166 from CPU2 to CPU3
,08-31 03:00:51.639  6017  6067 W jxcore-log: Initializing JXcore engine
08-31 03:00:51.639  6017  6067 W jxcore-log: JXcore engine is ready
,08-31 03:00:51.659  2565  2565 E audit   : type=1400 msg=audit(1472605251.659:273): avc:  denied  { ioctl } for  pid=6067 comm="Thread-108" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5531 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-31 03:00:51.659  2565  2565 E audit   :  SEPF_SECMOBILE_6.0.1_0013
08-31 03:00:51.659  2565  2565 E audit   : type=1300 msg=audit(1472605251.659:273): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=7 a1=5451 a2=3 a3=d87de3c8 items=0 ppid=581 pid=6067 auid=4294967295 uid=10136 gid=10136 euid=10136 suid=10136 fsuid=10136 egid=10136 sgid=10136 fsgid=10136 ses=4294967295 tty=(none) comm="Thread-108" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-31 03:00:51.659  2565  2565 E audit   : type=1327 msg=audit(1472605251.659:273): proctitle="com.test.thalitest"
08-31 03:00:51.659  2565  2565 E audit   : type=1320 msg=audit(1472605251.659:273): 
08-31 03:00:51.659  2565  2565 E audit   : type=1400 msg=audit(1472605251.659:274): avc:  denied  { ioctl } for  pid=6067 comm="Thread-108" path="socket:[44270]" dev="sockfs" ino=44270 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-31 03:00:51.659  2565  2565 E audit   :  SEPF_SECMOBILE_6.0.1_0013
08-31 03:00:51.659  2565  2565 E audit   : type=1300 msg=audit(1472605251.659:274): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3c a1=5451 a2=3 a3=d87de3c8 items=0 ppid=581 pid=6067 auid=4294967295 uid=10136 gid=10136 euid=10136 suid=10136 fsuid=10136 egid=10136 sgid=10136 fsgid=10136 ses=4294967295 tty=(none) comm="Thread-108" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-31 03:00:51.659  2565  2565 E audit   : type=1327 msg=audit(1472605251.659:274): proctitle="com.test.thalitest"
08-31 03:00:51.659  2565  2565 E audit   : type=1320 msg=audit(1472605251.659:274): 
,08-31 03:00:51.669  6017  6067 W jxcore-log: Starting JXcore engine
,08-31 03:00:51.719  6017  6067 W jxcore-log: Platform android
08-31 03:00:51.719  6017  6067 W jxcore-log: 
08-31 03:00:51.719  6017  6067 W jxcore-log: Process ARCH arm
08-31 03:00:51.719  6017  6067 W jxcore-log: 
,08-31 03:00:51.719  1791  1791 D Recents : onTaskStackChanged
,08-31 03:00:51.799  6017  6067 I jxcore-log: JXcore Cordova bridge is ready!
08-31 03:00:51.799  6017  6067 I jxcore-log: 
08-31 03:00:51.809  6017  6067 W jxcore-log: JXcore engine is started
,08-31 03:00:51.809  6017  6066 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-31 03:00:51.809  6017  6017 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 03:00:52.889  1131  1660 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/18_task.xml.bak
,08-31 03:00:53.279  1131  3551 D GameManagerService: identifyGamePackage. com.test.thalitest
,08-31 03:00:54.279  1131  3583 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 03:00:55.099  1131  3551 D SSRM:s  : SIOP:: AP = 340, PST = 361 (W:9), CP = 43, LCD = 0
,08-31 03:00:55.099  1131  3551 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-31 03:00:55.719  3628  3628 D FactoryTest: User mode
,08-31 03:00:55.719  3628  3628 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-31 03:00:55.719  3628  3628 D MTPRx   : still no open session command from host, so toast
,08-31 03:00:55.729  1131  2625 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
,08-31 03:00:55.729  1131  2625 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,08-31 03:00:55.729  1131  2625 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.samsung.android.MtpApplication)
,08-31 03:00:55.739  1131  2625 D ActivityManager: mDVFSHelper.acquire()
,08-31 03:00:55.739  1131  2625 V WindowManager: addAppToken: AppWindowToken{d08374114 token=Token{275af67 ActivityRecord{586726 u0 com.samsung.android.MtpApplication/.USBConnection t19}}} to stack=2 task=19 at 0
,08-31 03:00:55.739  1131  2625 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,08-31 03:00:55.749  1131  1365 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-31 03:00:55.749  1131  1131 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
,08-31 03:00:55.759  1131  2625 D InputDispatcher: Focused application set to: xxxx
,08-31 03:00:55.759  3628  3628 E MTPRx   : started activity for popup
,08-31 03:00:55.769  3628  3628 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-31 03:00:55.769  3628  3628 D RelationGraph: garbageCollect()
,08-31 03:00:55.769  1131  3551 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,08-31 03:00:55.779  3628  3628 D MTPUSBConnection: onCreate in USBConnection
08-31 03:00:55.779  3628  3628 V MTPUSBConnection: Registering broadcast receiver.
,08-31 03:00:55.789  3628  3628 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,08-31 03:00:55.789  1131  1827 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,08-31 03:00:55.819  3628  3628 D TAG     : dev.kiessupport is : TRUE
,08-31 03:00:55.849  3628  3628 D SecWifiDisplayUtil: Metadata value : SecSettings2
,08-31 03:00:55.849  3628  3628 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{50dfca7 V.E...... R.....I. 0,0-0,0}
,08-31 03:00:55.849  3628  6069 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-31 03:00:55.859  3628  3628 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{c70773e I.E...... R.....I. 0,0-0,0}
,08-31 03:00:55.859  1131  2000 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-31 03:00:55.859  1131  2000 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-31 03:00:55.859  1131  1131 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-31 03:00:55.869  1131  1131 I KnoxTimeoutHandler: Shared devices show user statefalse,
08-31 03:00:55.869  1131  1131 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-31 03:00:55.879   444   444 I SurfaceFlinger: id=17 createSurf (97x97),1 flag=4, VSBConnecti
,08-31 03:00:55.889  3628  6069 I Adreno  : QUALCOMM build                   : 971aff5, Ic07f1cdce3
08-31 03:00:55.889  3628  6069 I Adreno  : Build Date                       : 03/29/16
08-31 03:00:55.889  3628  6069 I Adreno  : OpenGL ES Shader Compiler Version: XE031.06.00.02
08-31 03:00:55.889  3628  6069 I Adreno  : Local Branch                     : 
08-31 03:00:55.889  3628  6069 I Adreno  : Remote Branch                    : refs/tags/AU_LINUX_ANDROID_LA.BR.1.3.3.C2.06.00.01.205.077
08-31 03:00:55.889  3628  6069 I Adreno  : Remote Branch                    : NONE
08-31 03:00:55.889  3628  6069 I Adreno  : Reconstruct Branch               : NOTHING
,08-31 03:00:55.899  3628  6069 I OpenGLRenderer: Initialized EGL, version 1.4
,08-31 03:00:55.919   444   444 I SurfaceFlinger: id=18 createSurf (129x129),1 flag=4, VSBConnecti
,08-31 03:00:55.929  3628  3628 V ActivityThread: updateVisibility : ActivityRecord{35ffeb5 token=android.os.BinderProxy@5a1010f {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-31 03:00:55.949  3628  6069 E libGLESv2: HWUI Protection: wrong call from hwui context F: ES3-glCreateProgramSEC
,08-31 03:00:55.949  3628  6069 E libGLESv2: HWUI Protection: wrong call from hwui context F: ES3-glCreateProgramSEC
,08-31 03:00:55.959  3628  6069 E libGLESv2: HWUI Protection: wrong call from hwui context F: ES3-glCreateProgramSEC
,08-31 03:00:55.959  1131  2625 V WindowStateAnimator: Finishing drawing window Window{8319eac u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-31 03:00:55.969  1131  1718 V WindowStateAnimator: Finishing drawing window Window{a81a30a u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-31 03:00:55.969  3628  3628 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-31 03:00:55.969  3628  3628 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,08-31 03:00:55.969  1131  2000 V WindowStateAnimator: Finishing drawing window Window{8319eac u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
08-31 03:00:55.969  1131  1399 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-31 03:00:55.979  1131  1131 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-31 03:00:55.979  1131  1399 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +220ms (total +233ms)
,08-31 03:00:55.979  1131  1399 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{586726 u0 com.samsung.android.MtpApplication/.USBConnection t19} time:98261
08-31 03:00:55.979  1131  1399 D ActivityManager: mDVFSHelper.release()
08-31 03:00:55.979  1131  1181 V WindowStateAnimator: Finishing drawing window Window{a81a30a u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
08-31 03:00:55.979  3628  3628 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@5a1010f time:98262
08-31 03:00:55.979  1131  1131 I KnoxTimeoutHandler: SD activityfalse
,08-31 03:00:56.869  1791  1791 D Recents : onTaskStackChanged
,08-31 03:00:56.879  1131  1988 D PackageManager: getComponentMetadataForIconTray : com.test.thalitest.MainActivity does not exist in mServices
08-31 03:00:56.879  1131  1988 D PackageManager: getComponentMetadataForIconTray : com.test.thalitest.MainActivity does not exist in mProviders
08-31 03:00:56.879  1131  1988 D PackageManager: getComponentMetadataForIconTray : com.test.thalitest.MainActivity does not exist in mReceivers
,08-31 03:00:56.879  1791  1791 I ApplicationPackageManager: load=com.test.thalitest, bg=96-96, dr=96-96
,08-31 03:00:56.879  1791  1791 I ApplicationPackageManager: scaled rate=0.98086953, size=96, alpha=2, hold=26, target=96,
,08-31 03:00:59.279  1131  3583 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 03:00:59.939  1131  1422 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-31 03:00:59.959  1131  1422 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-31 03:00:59.969  6017  6067 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 03:00:59.969  6017  6067 I jxcore-log: 
,08-31 03:00:59.979  6017  6067 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 03:00:59.979  6017  6067 I jxcore-log: 
,08-31 03:00:59.989  6017  6067 D BluetoothAdapter: STATE_ON
,08-31 03:00:59.989  6017  6067 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 03:00:59.989  6017  6067 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 03:00:59.989  6017  6067 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 03:00:59.989  6017  6067 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 03:00:59.989  6017  6067 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 03:00:59.989  6017  6067 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 03:00:59.989  6017  6067 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 03:00:59.989  6017  6067 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 03:00:59.989  6017  6067 D BluetoothAdapter: STATE_ON
,08-31 03:00:59.989  1131  1588 V AlarmManager: Expired Alarm result :8
,08-31 03:00:59.999  6017  6067 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 03:00:59.999  6017  6067 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 03:00:59.999  6017  6067 I jxcore-log: 
,08-31 03:00:59.999  6017  6067 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 03:00:59.999  6017  6067 I jxcore-log: 
,08-31 03:01:00.199  6017  6067 I jxcore-log: Running unit tests
08-31 03:01:00.199  6017  6067 I jxcore-log: 
,08-31 03:01:00.199  6017  6067 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-31 03:01:00.199  6017  6067 I jxcore-log: Failed to execute UT.
08-31 03:01:00.199  6017  6067 I jxcore-log: 
,08-31 03:01:00.199  6017  6067 I jxcore-log: Unit Test app is loaded
08-31 03:01:00.199  6017  6067 I jxcore-log: 
,08-31 03:01:00.199  6017  6067 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 03:01:00.199  6017  6067 I jxcore-log: ,
,08-31 03:01:00.209  6017  6067 I jxcore-log: My device name is: samsung-SM-T719,
08-31 03:01:00.209  6017  6067 I jxcore-log: 
08-31 03:01:00.209  6017  6067 I jxcore-log: WARN testUtils: myNameCallback not set!
08-31 03:01:00.209  6017  6067 I jxcore-log: 
,08-31 03:01:00.219  6017  6017 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68),
,08-31 03:01:01.469   713   713 I MSM-irqbalance: Decided to move IRQ200 from CPU0 to CPU3
,08-31 03:01:01.669  6017  6067 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js,
08-31 03:01:01.669  6017  6067 I jxcore-log: 
,08-31 03:01:01.919  6017  6067 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js,
08-31 03:01:01.919  6017  6067 I jxcore-log: 
,08-31 03:01:01.929  6017  6067 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js,
08-31 03:01:01.929  6017  6067 I jxcore-log: 
,08-31 03:01:02.739  6017  6067 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js,
08-31 03:01:02.739  6017  6067 I jxcore-log: 
,08-31 03:01:02.869  6017  6067 I jxcore-log: ERROR runTests: ,
08-31 03:01:02.869  6017  6067 I jxcore-log: 
,08-31 03:01:02.869  6017  6067 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-31 03:01:02.869  6017  6067 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
08-31 03:01:02.869  6017  6067 I jxcore-log: WARN testUtils: logCallback not set!
08-31 03:01:02.869  6017  6067 I jxcore-log: 
,08-31 03:01:02.879  6017  6067 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',,
08-31 03:01:02.879  6017  6067 I jxcore-log:     _functionName: 'loadFile',
08-31 03:01:02.879  6017  6067 I jxcore-log:     _lineNumber: '26',
08-31 03:01:02.879  6017  6067 I jxcore-log:     _columnNumber: '11',
08-31 03:01:02.879  6017  6067 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-31 03:01:02.879  6017  6067 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 03:01:02.879  6017  6067 I jxcore-log:     _functionName: '',
08-31 03:01:02.879  6017  6067 I jxcore-log:     _lineNumber: '38',,
,08-31 03:01:02.879  6017  6067 I jxcore-log:     _columnNumber: '7',
08-31 03:01:02.879  6017  6067 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-31 03:01:02.879  6017  6067 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 03:01:02.879  6017  6067 I jxcore-log:     _functionName: '',
08-31 03:01:02.879  6017  6067 I jxcore-log:     _lineNumber: '35',
08-31 03:01:02.879  6017  6067 I jxcore-log:     _columnNumber: '3',
08-31 03:01:02.879  6017  6067 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-31 03:01:02.879  6017  6067 I jxcore-log:   { _fileName: 'module.js',
08-31 03:01:02.879  6017  6067 I jxcore-log:     _functionName: '$w.prototype._compile',
08-31 03:01:02.879  6017  6067 I jxcore-log:     _lineNumber: '621',
08-31 03:01:02.879  6017  6067 I jxcore-log:     _columnNumber: '8',
08-31 03:01:02.879  6017  6067 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-31 03:01:02.879  6017  6067 I jxcore-log:   { _fileName: 'module.js',
08-31 03:01:02.879  6017  6067 I jxcore-log:     _functionName: '$w._extensions[".js"]',,
08-31 03:01:02.879  6017  6067 I jxcore-log:     _lineNumber: '651',
08-31 03:01:02.879  6017  6067 I jxcore-log:     _columnNumber: '1',
08-31 03:01:02.879  6017  6067 I jxcore-log:    
08-31 03:01:02.879  6017  6067 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-31 03:01:02.879  6017  6067 I jxcore-log: 
,08-31 03:01:02.879  6017  6067 E jxcore-log: Error: 
08-31 03:01:02.879  6017  6067 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-31 03:01:02.879  6017  6067 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-31 03:01:02.879  6017  6067 E jxcore-log: 
,08-31 03:01:03.359  6072  6072 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-31 03:01:03.369  6072  6072 D AndroidRuntime: CheckJNI is OFF
,08-31 03:01:03.369  6072  6072 D AndroidRuntime: readGMSProperty: start
08-31 03:01:03.369  6072  6072 D AndroidRuntime: readGMSProperty: already setted!!
08-31 03:01:03.369  6072  6072 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-31 03:01:03.369  6072  6072 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-31 03:01:03.369  6072  6072 D AndroidRuntime: readGMSProperty: end
08-31 03:01:03.369  6072  6072 D AndroidRuntime: addProductProperty: start
,08-31 03:01:03.429  6072  6072 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-31 03:01:03.479  6072  6072 I Radio-JNI: register_android_hardware_Radio DONE
,08-31 03:01:03.479  6072  6072 E AffinityControl: AffinityControl: registerfunction enter
,08-31 03:01:03.499  6072  6072 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 03:01:03.519  1131  1988 D PackageManager: START PACKAGE DELETE: observer{211527547}
08-31 03:01:03.519  1131  1988 D PackageManager: pkg{<packageName>}
08-31 03:01:03.519  1131  1988 D PackageManager: user{0}
08-31 03:01:03.519  1131  1988 D PackageManager: caller{2000}
08-31 03:01:03.519  1131  1988 D PackageManager: flags{2}
08-31 03:01:03.519  1131  1988 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-31 03:01:03.519  1131  1988 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-31 03:01:03.519  1131  1988 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-31 03:01:03.519  1131  1988 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-31 03:01:03.519  1131  1988 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-31 03:01:03.519  1131  1422 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-31 03:01:03.519  1131  1422 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-31 03:01:03.519  1131  1422 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-31 03:01:03.519  1131  1422 D ApplicationPolicy: getApplicationUninstallationEnabled
08-31 03:01:03.519  1131  1422 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
08-31 03:01:03.519  1131  1422 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-31 03:01:03.519  1131  1422 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-31 03:01:03.519  1131  1422 D PackageManager: !@killApplicatoin: 10136, uninstall pkg,
08-31 03:01:03.519  1131  1422 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-31 03:01:03.519  1131  1365 I ActivityManager: Force stopping com.test.thalitest appid=10136 user=-1: uninstall pkg
08-31 03:01:03.519  1131  1422 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-31 03:01:03.519  1131  1365 I ActivityManager: Killing 6017:com.test.thalitest/u0a136 (adj 1): stop com.test.thalitest cause uninstall pkg
08-31 03:01:03.519  1131  1365 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=6017 ,hash=178482797 ,name=com.test.thalitest
08-31 03:01:03.529  1131  1365 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-31 03:01:03.549  1131  1422 D AASAinstall: there is not AASApackages.xml file
,08-31 03:01:03.549  6081  6081 E Zygote  : v2
08-31 03:01:03.549  6081  6081 I libpersona: KNOX_SDCARD checking this for 10136
08-31 03:01:03.549  6081  6081 I libpersona: KNOX_SDCARD not a persona
,08-31 03:01:03.549  6081  6081 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-31 03:01:03.549  1131  1365 I ActivityManager: Start proc 6081:com.test.thalitest/u0a136 for activity com.test.thalitest/.MainActivity
,08-31 03:01:03.549  6081  6081 E Zygote  : accessInfo : 0
08-31 03:01:03.549  1131  1365 W VirtualScreenManagerService: moveTaskBackToDisplayIfNeeded(): top activity or app is null
08-31 03:01:03.549  1131  1365 I ActivityManager:   Force finishing activity ActivityRecord{17edc0 u0 com.test.thalitest/.MainActivity t18}
08-31 03:01:03.549  6081  6081 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
,08-31 03:01:03.559   444  6016 I SurfaceFlinger: id=16 Removed NainActivit (6/12)
,08-31 03:01:03.559   444   474 I SurfaceFlinger: id=16 Removed NainActivit (-2/12)
,08-31 03:01:03.559  1131  1718 D GraphicsStats: Buffer count: 5
08-31 03:01:03.559  1131  2625 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@449c5f1)
08-31 03:01:03.559   444  6016 E         : BitTube(): close sendFd (44)
08-31 03:01:03.559   444  6016 E         : BitTube(): close sendFd (45)
,08-31 03:01:03.559  1131  1628 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 03:01:03.569   444  6016 I SurfaceFlinger: id=16 Removed NainActivit (-2/12)
08-31 03:01:03.559  1131  1628 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 03:01:03.569  1131  1628 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 03:01:03.579  6081  6081 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 03:01:03.579  6081  6081 D ActivityThread: Added TimaKeyStore provider
,08-31 03:01:03.819  1131  1422 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-31 03:01:03.909  1131  1422 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-31 03:01:03.909   566   566 W keystore: ENTER clear_uid from uid 1000 for 10136
,08-31 03:01:03.909  1131  1422 I art     : Starting a blocking GC Explicit
,08-31 03:01:03.919  1131  2263 I ActivityManager: Killing 5506:com.sec.android.soagent/1000 (adj 15): DHA:empty #31
,08-31 03:01:03.939  6081  6081 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
08-31 03:01:03.939  6081  6081 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
,08-31 03:01:03.939  6081  6081 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
08-31 03:01:03.939  6081  6081 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
,08-31 03:01:03.949  6081  6081 D AndroidRuntime: Shutting down VM
,08-31 03:01:03.959  6081  6081 E AndroidRuntime: FATAL EXCEPTION: main
08-31 03:01:03.959  6081  6081 E AndroidRuntime: Process: com.test.thalitest, PID: 6081
08-31 03:01:03.959  6081  6081 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-31 03:01:03.959  6081  6081 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:676)
08-31 03:01:03.959  6081  6081 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6296)
08-31 03:01:03.959  6081  6081 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:223)
08-31 03:01:03.959  6081  6081 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1863)
08-31 03:01:03.959  6081  6081 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:01:03.959  6081  6081 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
08-31 03:01:03.959  6081  6081 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7231)
08-31 03:01:03.959  6081  6081 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:01:03.959  6081  6081 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-31 03:01:03.959  6081  6081 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-31 03:01:03.959  6081  6081 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-31 03:01:03.959  6081  6081 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:485)
08-31 03:01:03.959  6081  6081 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:661)
08-31 03:01:03.959  6081  6081 E AndroidRuntime: 	... 9 more
,08-31 03:01:03.959  6081  6081 I Process : Sending signal. PID: 6081 SIG: 9
,08-31 03:01:03.969  1131  1365 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{71ee5d6 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3db9e8d 5711:com.samsung.android.sm/1000}
,08-31 03:01:03.969  1131  2000 I ActivityManager: Process com.test.thalitest (pid 6081)(adj 9) has died(173,1495)
,08-31 03:01:03.969  1131  2000 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=6081 ,hash=258996632 ,name=com.test.thalitest
08-31 03:01:03.969  1131  2000 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-31 03:01:03.969  1131  2000 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.android.server.am.ActivityManagerService.updateOomAdjLocked:26615 com.android.server.am.ActivityManagerService.appDiedLocked:7605 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1888 android.os.BinderProxy.sendDeathNotice:558 
,08-31 03:01:03.979  5711  5711 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1311 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.samsung.android.sm.common.SmartManagerReceiver.b:259 com.samsung.android.sm.common.SmartManagerReceiver.onReceive:107 
,08-31 03:01:04.029  1131  1988 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5506 ,hash=157374289 ,name=com.sec.android.soagent
08-31 03:01:04.029  1131  1988 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.soagent, Auto Run ON
,08-31 03:01:04.159  1131  1422 I art     : Explicit concurrent mark sweep GC freed 229068(13MB) AllocSpace objects, 47(2MB) LOS objects, 33% free, 29MB/43MB, paused 3.016ms total 244.045ms
,08-31 03:01:04.179  1131  1422 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-31 03:01:04.179  1131  1422 D AASAuninstall: userId = 0, info.removedAppID = 10136, info.uid = 10136, packageName = com.test.thalitest
,08-31 03:01:04.179  1131  1422 D AASAinstall: there is not AASApackages.xml file
08-31 03:01:04.179  1131  1422 D PackageManager: result of delete: 1{211527547}
,08-31 03:01:04.179  1131  1422 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-31 03:01:04.179  1131  1422 D PackageManager: userId{-1}
08-31 03:01:04.179  1131  1422 D PackageManager: andCode{true}
,08-31 03:01:04.189  6072  6072 I art     : System.exit called, status: 0
08-31 03:01:04.189  6072  6072 I AndroidRuntime: VM exiting with result code 0.
,08-31 03:01:04.189  1131  1422 I ActivityManager: Force stopping com.test.thalitest appid=10136 user=0: pkg removed
,08-31 03:01:04.209  5766  6096 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-31 03:01:04.219  1702  1702 D ShortcutManager: onReceive : android.intent.action.PACKAGE_REMOVED
08-31 03:01:04.219  1702  1702 D ShortcutManager: onReceive : Intent.EXTRA_REPLACING false,com.test.thalitest
,08-31 03:01:04.219  5766  6096 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
08-31 03:01:04.219  1702  1702 D CoverUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
,08-31 03:01:04.219  5766  6096 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-31 03:01:04.229  5075  5106 I SystemBroadcastReceiver: [#CMH#] Received broadcast 
08-31 03:01:04.229  5075  5106 I ControllerEventHandler: [#CMH#] onPackageRemoved  null
08-31 03:01:04.229  5075  5106 I SystemBroadcastReceiver: [#CMH#] onReceive completed 
,08-31 03:01:04.229  1874  2389 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-31 03:01:04.239  1131  1590 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 03:01:04.239  1131  1618 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 03:01:04.239  1131  1618 V NetworkStats: removeUidsLocked() for UIDs [10136]
08-31 03:01:04.239  1131  1618 V NetworkStats: performPollLocked(flags=0x3)
,08-31 03:01:04.249  1131  1618 D NetworkStatsRecorder: entry.iface is null
08-31 03:01:04.249  1131  1618 D NetworkStatsRecorder: entry.iface is null
08-31 03:01:04.249  1131  1618 D NetworkStatsRecorder: entry.iface is null
08-31 03:01:04.249  1131  1618 D NetworkStatsRecorder: entry.iface is null
,08-31 03:01:04.249  1791  1791 I Recents_MultiWindowAppListInfo: android.intent.action.PACKAGE_REMOVE
08-31 03:01:04.249  1131  1365 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{89d0f12 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{900d021 3911:com.samsung.klmsagent/u0a16}
08-31 03:01:04.249  1131  2447 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=2486, uid=10093 that is not exported from uid 10091
,08-31 03:01:04.249  1944  1944 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-31 03:01:04.259  3911  3911 I KLMS-2.6.094: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } | timestamp: Wed Aug 31 03:01:04 GMT+02:00 2016
,08-31 03:01:04.269  3911  3911 I KLMS-2.6.094: : KLMSAbstractReciever(): onReceive().END.
,08-31 03:01:04.269  1131  2447 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{89d0f12 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9846c1 1131:system/1000}
08-31 03:01:04.269  3911  3911 I KLMS-2.6.094: : KLMSIntentService(): onCreate()
08-31 03:01:04.269  3911  3911 I KLMS-2.6.094: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-31 03:01:04.269  3911  3911 I KLMS-2.6.094: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-31 03:01:04.269  3911  6100 I KLMS-2.6.094: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
08-31 03:01:04.269  1131  1358 D EnterpriseDeviceManagerService: Package has changed for user 0
08-31 03:01:04.269  1131  1358 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-31 03:01:04.269  3911  6100 D KLMS-2.6.094: : KLMSIntentService(): PACKAGE_REMOVED
08-31 03:01:04.269  3911  6100 I KLMS-2.6.094: : Systemprocess(): listeningToPackageRemoved().START
08-31 03:01:04.269  3911  6100 I KLMS-2.6.094: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
08-31 03:01:04.269  3911  6100 I KLMS-2.6.094: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
08-31 03:01:04.269  3911  6100 I KLMS-2.6.094: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-31 03:01:04.269  3911  6100 I KLMS-2.6.094: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-31 03:01:04.279  3911  6100 I KLMS-2.6.094: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-31 03:01:04.279  3911  6100 I KLMS-2.6.094: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-31 03:01:04.279  3911  6100 D KLMS-2.6.094: : Systemprocess(): arrayLicenseInfo is null
,08-31 03:01:04.289  3911  6100 D KLMS-2.6.094: : DataSource(): Fetched Data from data base count : 0
,08-31 03:01:04.289  1131  1618 V NetworkStats: performPollLocked() took 49ms
08-31 03:01:04.289  1131  1618 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 03:01:04.289  1131  1619 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 03:01:04.289  1131  2018 D SettingsProvider: isChangeAllowed() : name = klm_eula_shown
08-31 03:01:04.289  1131  1619 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 03:01:04.289  1131  2018 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 03:01:04.289  1131  2018 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-31 03:01:04.289  1131  2018 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 03:01:04.289  1131  2018 D SettingsProvider: selectionArgs: false
08-31 03:01:04.289  1131  2018 D SettingsProvider: selectionArgs: 10016
,08-31 03:01:04.289  1131  2018 D SettingsProvider: ret = -1
,08-31 03:01:04.309  1131  1131 V AlarmManager: Remove alarm for next reason : android.intent.action.PACKAGE_REMOVED : package: com.test.thalitest
,08-31 03:01:04.309  1131  1131 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-31 03:01:04.309  1131  1131 D UniversalCredentialManagerService: inside mPkgReciever onReceive : android.intent.action.PACKAGE_REMOVED
08-31 03:01:04.309  1131  1131 D UniversalCredentialManagerService: ACTION_PACKAGE_REMOVED is called....
08-31 03:01:04.309  1131  1131 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-31 03:01:04.309  1131  1131 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-31 03:01:04.309  1131  1131 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10136 container id = 0
,08-31 03:01:04.309  1131  1131 I OTPFW   : ProvisionData::getAllEntries Enter
,08-31 03:01:04.309  1131  1131 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-31 03:01:04.309  1131  1131 E SDAgentPackageStateReceiver: Not going to handle 'com.test.thalitest'!
,08-31 03:01:04.309  1131  1131 D UcmService: onReceive android.intent.action.PACKAGE_REMOVED
,08-31 03:01:04.309  1131  1131 D UcmService: Package update in userId-0 and uid-10136
,08-31 03:01:04.319  1131  1131 D GameManager.DatabaseHelper: removeGame(), packageName: com.test.thalitest, ret: 0
,08-31 03:01:04.319  1131  1131 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-31 03:01:04.319  1131  1131 V EnterpriseBillingAsyncHandler: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,08-31 03:01:04.319  1131  1652 V EnterpriseBillingPolicyInternal: packageModification -  start - android.intent.action.PACKAGE_REMOVED
08-31 03:01:04.319  1131  1652 V EnterpriseBillingPolicyInternal: uID is 10136
08-31 03:01:04.319  1131  1652 V EnterpriseBillingPolicyInternal: Removed Packageuid is0
08-31 03:01:04.319  1131  1652 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-31 03:01:04.319  1131  1652 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-31 03:01:04.319  1131  1652 V EnterpriseBillingPolicyInternal: packageModificationReceiver - onreceive - personal application - profile null
,08-31 03:01:04.319  1131  1131 D SdpManagerService:  ActionReceiver::onReceive() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,08-31 03:01:04.319  1131  1131 D SdpManagerService: ACTION_PACKAGE_REMOVED Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } DATA= package:com.test.thalitest UID 1000 userId 0
08-31 03:01:04.319  1131  1131 D SdpManagerService: ACTION_PACKAGE_REMOVED packageName:: com.test.thalitest
08-31 03:01:04.319  1131  1131 D EnterprisePartitionManager: SND -> {secure_fs remove_enc_dir}
,08-31 03:01:04.329   382   437 D epmd    : Partition obj created
08-31 03:01:04.329   382   437 D epmd    : Partition::dump============== 0
08-31 03:01:04.329   382   437 D epmd    : Partition::mType > INTERNAL-SDCARD mSrcPath > /data/knox/secure_fs/enc_user mMntPath > /data/enc_user
08-31 03:01:04.329   382   437 D epmd    : Partition::SDP > not supported
,08-31 03:01:04.329   382   437 E epmd    : removeEncPkgDir ERROR
08-31 03:01:04.329   382   437 D epmd    : deleting Partition object.
08-31 03:01:04.329   382   437 W FrameworkListener: Handler 'secure_fs' error (No such file or directory)
08-31 03:01:04.329  1131  1424 D EnterprisePartitionManager: RCV <-
08-31 03:01:04.329  1131  1131 D EnterprisePartitionManager: RMV <-
08-31 03:01:04.329  1131  1131 D EnterprisePartitionManager: event : 281 3 remove_enc_dir failed
,08-31 03:01:04.329  1131  1131 D SdpManagerService: start document   : ,
08-31 03:01:04.329  1131  1131 D SdpManagerService: start element    : engine_list
08-31 03:01:04.329  1131  1131 D SdpManagerService: start characters : 
08-31 03:01:04.329  1131  1131 D SdpManagerService: start element    : engine,
08-31 03:01:04.329  1131  1131 D SdpManagerService:  attribte alias: android_0
08-31 03:01:04.329  1131  1131 D SdpManagerService:  attribte id: 0
08-31 03:01:04.329  1131  1131 D SdpManagerService: end element      : engine,
08-31 03:01:04.329  1131  1131 D SdpManagerService: start characters : 
08-31 03:01:04.329  1131  3551 D SSRM:bb : MSG_TYPE_APP_REMOVED::
08-31 03:01:04.329  1131  1131 D SdpManagerService: end element      : engine_list
,08-31 03:01:04.329  1131  1131 D SdpManagerService: end document     : 
08-31 03:01:04.329  1131  1131 W System.err: mkdir failed: EEXIST (File exists) : /data/system/users/0
08-31 03:01:04.329  1131  1131 E SdpManagerService: cant make directory /data/system/users/0
08-31 03:01:04.329  1131  1131 D SdpManagerService: start document   : 
,08-31 03:01:04.329  1131  3551 D SSRM:bb : MSG_TYPE_UID_REMOVED::
08-31 03:01:04.329  1131  1131 D SdpManagerService: start element    : user
08-31 03:01:04.329  1131  1131 D SdpManagerService: end element      : user
08-31 03:01:04.329  1131  1131 D SdpUtil : num:0 index-0
08-31 03:01:04.329  1131  1131 D SdpUtil : detecected userId : 0
08-31 03:01:04.329  1131  1131 D SdpManagerService: end document     : 
08-31 03:01:04.329  1131  1131 E SdpManagerService: Can't find engine info [android_0]
08-31 03:01:04.329  1131  1131 V EnterpriseBillingAsyncHandler: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-31 03:01:04.329  1131  1652 V EnterpriseBillingPolicyInternal: packageModification -  start - android.intent.action.PACKAGE_FULLY_REMOVED
08-31 03:01:04.329  1131  1652 V EnterpriseBillingPolicyInternal: uID is 10136
08-31 03:01:04.329  1131  1652 V EnterpriseBillingPolicyInternal: Removed Packageuid is0
08-31 03:01:04.329  1131  1652 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-31 03:01:04.329  1131  1652 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-31 03:01:04.329  1131  1652 V EnterpriseBillingPolicyInternal: packageModificationReceiver - onreceive - personal application - profile null
,08-31 03:01:04.329  1131  1131 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{89d0f12 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c6d4a8d 1874:com.google.android.gms.persistent/u0a10}
,08-31 03:01:04.339  1131  1131 D AccessibilityManagerService: checkUniversalSwitchState start:
,08-31 03:01:04.339  5815  5827 E SQLiteLog: (10) unixWrite() File Descriptor : 20 gets errno : 30
,08-31 03:01:04.349  5815  5827 E DatabaseUtils: Writing exception to parcel
08-31 03:01:04.349  5815  5827 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
08-31 03:01:04.349  5815  5827 E DatabaseUtils: #################################################################
08-31 03:01:04.349  5815  5827 E DatabaseUtils: Error Code : 778 (SQLITE_IOERR_WRITE)
08-31 03:01:04.349  5815  5827 E DatabaseUtils: Caused By : Disk I/O error occurred during 'write' operation.
08-31 03:01:04.349  5815  5827 E DatabaseUtils: 	(disk I/O error (code 778))
08-31 03:01:04.349  5815  5827 E DatabaseUtils: #################################################################
08-31 03:01:04.349  5815  5827 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 03:01:04.349  5815  5827 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:866)
08-31 03:01:04.349  5815  5827 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 03:01:04.349  5815  5827 E DatabaseUtils: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 03:01:04.349  5815  5827 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
08-31 03:01:04.349  5815  5827 E DatabaseUtils: 	at com.samsung.android.sm.database.SmProvider.delete(SmProvider.java:826)
08-31 03:01:04.349  5815  5827 E DatabaseUtils: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:352)
08-31 03:01:04.349  5815  5827 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:206)
08-31 03:01:04.349  5815  5827 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:453)
,08-31 03:01:04.349  1131  1718 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{89d0f12 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{98d41e3 2219:com.google.android.gms/u0a10}
,08-31 03:01:04.349  2219  6102 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-31 03:01:04.349  1131  1397 E MARsDBManager: Exception with contentResolver : disk I/O error (code 778)
08-31 03:01:04.349  1131  1397 E MARsDBManager: #################################################################
08-31 03:01:04.349  1131  1397 E MARsDBManager: Error Code : 778 (SQLITE_IOERR_WRITE)
08-31 03:01:04.349  1131  1397 E MARsDBManager: Caused By : Disk I/O error occurred during 'write' operation.
08-31 03:01:04.349  1131  1397 E MARsDBManager: 	(disk I/O error (code 778))
08-31 03:01:04.349  1131  1397 E MARsDBManager: #################################################################
08-31 03:01:04.349  1131  1397 E MARsDBManager: #################################################################
08-31 03:01:04.349  1131  1397 E MARsDBManager: Error Code : 778 (SQLITE_IOERR_WRITE)
,08-31 03:01:04.349  1131  1397 E MARsDBManager: Caused By : Disk I/O error occurred during 'write' operation.
08-31 03:01:04.349  1131  1397 E MARsDBManager: 	(disk I/O error (code 778)
08-31 03:01:04.349  1131  1397 E MARsDBManager: #################################################################
08-31 03:01:04.349  1131  1397 E MARsDBManager: Error Code : 778 (SQLITE_IOERR_WRITE)
08-31 03:01:04.349  1131  1397 E MARsDBManager: Caused By : Disk I/O error occurred during 'write' operation.
08-31 03:01:04.349  1131  1397 E MARsDBManager: 	(disk I/O error (code 778))
08-31 03:01:04.349  1131  1397 E MARsDBManager: #################################################################)
08-31 03:01:04.349  1131  1397 E MARsDBManager: #################################################################
08-31 03:01:04.349  2219  6102 D AccountUtils: Clearing selected account for com.test.thalitest
,08-31 03:01:04.349  1131  2000 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{89d0f12 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{98d41e3 2219:com.google.android.gms/u0a10}
,08-31 03:01:04.359  1131  2316 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{89d0f12 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c6d4a8d 1874:com.google.android.gms.persistent/u0a10}
,08-31 03:01:04.359  1874  1874 D GCM-PT  : Populating db of packages that use GCM
,08-31 03:01:04.359  2219  6102 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-31 03:01:04.369  2219  6102 W SQLiteLog: (28) failed to open "/data/user/0/com.google.android.gms/databases/phenotype.db" with flag (131138) and mode_t (0) due to error (30)
,08-31 03:01:04.369  1874  1874 W SQLiteLog: (28) failed to open "/data/user/0/com.google.android.gms/databases/gcm_registrar.db-journal" with flag (131138) and mode_t (1b0) due to error (30)
08-31 03:01:04.369  1874  1874 E SQLiteLog: (10) unixWrite() File Descriptor : 32 gets errno : 9
08-31 03:01:04.369  1874  1874 E SQLiteLog: (778) statement aborts at 16: [INSERT INTO packages(uid,package_name) VALUES (?,?)] 
,08-31 03:01:04.369  2219  6102 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
08-31 03:01:04.369  2219  6102 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:01:04.369  2219  6102 E SQLiteDatabase: #################################################################
08-31 03:01:04.369  2219  6102 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
08-31 03:01:04.369  2219  6102 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-31 03:01:04.369  2219  6102 E SQLiteDatabase: #################################################################
08-31 03:01:04.369  2219  6102 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:01:04.369  2219  6102 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-31 03:01:04.369  2219  6102 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-31 03:01:04.369  2219  6102 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 03:01:04.369  2219  6102 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 03:01:04.369  2219  6102 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 03:01:04.369  2219  6102 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 03:01:04.369  2219  6102 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 03:01:04.369  2219  6102 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 03:01:04.369  2219  6102 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:639)
08-31 03:01:04.369  2219  6102 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-31 03:01:04.369  2219  6102 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-31 03:01:04.369  2219  6102 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:01:04.369  2219  6102 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:01:04.369  2219  6102 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastIntentOperation.onHandleIntent(:com.google.android.gms:51)
08-31 03:01:04.369  2219  6102 E SQLiteDatabase: 	at com.google.android.chimera.IntentOperation.onHandleIntent(:com.google.android.gms:76)
08-31 03:01:04.369  2219  6102 E SQLiteDatabase: 	at com.google.android.chimera.container.l.run(:com.google.android.gms:801)
08-31 03:01:04.369  2219  6102 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 03:01:04.369  2219  6102 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 03:01:04.369  2219  6102 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-31 03:01:04.379  2219  6102 E PhenotypeInitializer: Could not unregister android package com.test.thalitest
08-31 03:01:04.379  2219  6102 E PhenotypeInitializer: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:01:04.379  2219  6102 E PhenotypeInitializer: #################################################################
08-31 03:01:04.379  2219  6102 E PhenotypeInitializer: Error Code : 0 (SQLITE_OK)
08-31 03:01:04.379  2219  6102 E PhenotypeInitializer: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-31 03:01:04.379  2219  6102 E PhenotypeInitializer: #################################################################
08-31 03:01:04.379  2219  6102 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:01:04.379  2219  6102 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-31 03:01:04.379  2219  6102 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-31 03:01:04.379  2219  6102 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 03:01:04.379  2219  6102 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 03:01:04.379  2219  6102 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 03:01:04.379  2219  6102 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 03:01:04.379  2219  6102 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 03:01:04.379  2219  6102 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 03:01:04.379  2219  6102 E PhenotypeInitializer: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:639)
08-31 03:01:04.379  2219  6102 E PhenotypeInitializer: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-31 03:01:04.379  2219  6102 E PhenotypeInitializer: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-31 03:01:04.379  2219  6102 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:01:04.379  2219  6102 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:01:04.379  2219  6102 E PhenotypeInitializer: 	at com.google.android.gms.app.service.PackageBroadcastIntentOperation.onHandleIntent(:com.google.android.gms:51)
08-31 03:01:04.379  2219  6102 E PhenotypeInitializer: 	at com.google.android.chimera.IntentOperation.onHandleIntent(:com.google.android.gms:76)
08-31 03:01:04.379  2219  6102 E PhenotypeInitializer: 	at com.google.android.chimera.container.l.run(:com.google.android.gms:801)
08-31 03:01:04.379  2219  6102 E PhenotypeInitializer: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 03:01:04.379  2219  6102 E PhenotypeInitializer: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 03:01:04.379  2219  6102 E PhenotypeInitializer: 	at java.lang.Thread.run(Thread.java:818)
08-31 03:01:04.379  1874  1874 E SQLiteDatabase: Error inserting uid=0 package_name=com.samsung.android.fmm
08-31 03:01:04.379  1874  1874 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
08-31 03:01:04.379  1874  1874 E SQLiteDatabase: #################################################################
08-31 03:01:04.379  1874  1874 E SQLiteDatabase: Error Code : 778 (SQLITE_IOERR_WRITE)
08-31 03:01:04.379  1874  1874 E SQLiteDatabase: Caused By : Disk I/O error occurred during 'write' operation.
08-31 03:01:04.379  1874  1874 E SQLiteDatabase: 	(disk I/O error (code 778))
08-31 03:01:04.379  1874  1874 E SQLiteDatabase: #################################################################
08-31 03:01:04.379  1874  1874 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-31 03:01:04.379  1874  1874 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:915)
08-31 03:01:04.379  1874  1874 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-31 03:01:04.379  1874  1874 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-31 03:01:04.379  1874  1874 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-31 03:01:04.379  1874  1874 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-31 03:01:04.379  1874  1874 E SQLiteDatabase: 	at com.google.android.gms.gcm.GcmPackageTracker.c(:com.google.android.gms:292)
08-31 03:01:04.379  1874  1874 E SQLiteDatabase: 	at com.google.android.gms.gcm.GcmPackageTracker.a(:com.google.android.gms:219)
08-31 03:01:04.379  1874  1874 E SQLiteDatabase: 	at com.google.android.gms.gcm.GcmPackageTracker.a(:com.google.android.gms:124)
08-31 03:01:04.379  1874  1874 E SQLiteDatabase: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(:com.google.android.gms:332)
08-31 03:01:04.379  1874  1874 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3637)
08-31 03:01:04.379  1874  1874 E SQLiteDatabase: 	at android.app.ActivityThread.access$2000(ActivityThread.java:223)
08-31 03:01:04.379  1874  1874 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1879)
08-31 03:01:04.379  1874  1874 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:01:04.379  1874  1874 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:158)
08-31 03:01:04.379  1874  1874 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:7231)
08-31 03:01:04.379  1874  1874 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:01:04.379  1874  1874 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-31 03:01:04.379  1874  1874 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-31 03:01:04.379  1874  1874 W GCM-PT  : Unable to add package to the database
08-31 03:01:04.379  1131  1988 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{89d0f12 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c6d4a8d 1874:com.google.android.gms.persistent/u0a10}
08-31 03:01:04.379  1131  1358 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-31 03:01:04.379  1993  1993 E Launcher.Model: onPackageRemoved :com.test.thalitest
08-31 03:01:04.389  1874  1874 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
08-31 03:01:04.389  1874  1874 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
08-31 03:01:04.389  1993  2126 E SQLiteLog: (10) unixWrite() File Descriptor : 20 gets errno : 30
08-31 03:01:04.389  1874  2230 W System.err: mkdir failed: EEXIST (File exists) : /data/user/0/com.google.android.gms/shared_prefs
08-31 03:01:04.389  1874  2230 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.gms/shared_prefs/nlp-prefs.xml
08-31 03:01:04.389  1993  2126 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-31 03:01:04.389  1993  2126 E AndroidRuntime: Process: com.sec.android.app.launcher, PID: 1993
08-31 03:01:04.389  1993  2126 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
08-31 03:01:04.389  1993  2126 E AndroidRuntime: #################################################################
08-31 03:01:04.389  1993  2126 E AndroidRuntime: Error Code : 778 (SQLITE_IOERR_WRITE)
08-31 03:01:04.389  1993  2126 E AndroidRuntime: Caused By : Disk I/O error occurred during 'write' operation.
08-31 03:01:04.389  1993  2126 E AndroidRuntime: 	(disk I/O error (code 778))
08-31 03:01:04.389  1993  2126 E AndroidRuntime: #################################################################
08-31 03:01:04.389  1993  2126 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-31 03:01:04.389  1993  2126 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:679)
08-31 03:01:04.389  1993  2126 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
08-31 03:01:04.389  1993  2126 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
08-31 03:01:04.389  1993  2126 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:527)
08-31 03:01:04.389  1993  2126 E AndroidRuntime: 	at com.android.launcher2.LauncherProvider.updateAppItems(LauncherProvider.java:539)
08-31 03:01:04.389  1993  2126 E AndroidRuntime: 	at com.android.launcher2.LauncherModel$6.run(LauncherModel.java:845)
08-31 03:01:04.389  1993  2126 E AndroidRuntime: 	at com.android.launcher2.LauncherModel.updateAppItems(LauncherModel.java:849)
08-31 03:01:04.389  1993  2126 E AndroidRuntime: 	at com.android.launcher2.MenuAppLoader.removePackage(MenuAppLoader.java:891)
08-31 03:01:04.389  1993  2126 E AndroidRuntime: 	at com.android.launcher2.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3788)
08-31 03:01:04.389  1993  2126 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 03:01:04.389  1993  2126 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 03:01:04.389  1993  2126 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
08-31 03:01:04.389  1993  2126 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:01:04.389  1131  2005 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{89d0f12 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5a8ca3b 5369:com.android.vending/u0a19}
08-31 03:01:04.399  1131  1718 V AlarmManager:  remove PendingIntent] PendingIntent{ed47400: PendingIntentRecord{cbe49bb com.google.android.gms broadcastIntent}}
08-31 03:01:04.399  5369  5369 W Finsky  : [1] com.google.android.finsky.FinskyApp.i(1379): No account configured on this device.

```
