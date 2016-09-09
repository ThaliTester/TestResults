#### Test 836273375fe617f_thali05_samsung-SM-T719 Logs


```
--------- beginning of system
,09-09 13:40:35.056  1259  3576 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
09-09 13:40:35.496  5946  5946 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-09 13:40:35.496  5946  5946 D AndroidRuntime: CheckJNI is OFF
09-09 13:40:35.496  5946  5946 D AndroidRuntime: readGMSProperty: start
09-09 13:40:35.496  5946  5946 D AndroidRuntime: readGMSProperty: already setted!!
09-09 13:40:35.496  5946  5946 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-09 13:40:35.496  5946  5946 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-09 13:40:35.496  5946  5946 D AndroidRuntime: readGMSProperty: end
09-09 13:40:35.496  5946  5946 D AndroidRuntime: addProductProperty: start
09-09 13:40:35.526  5946  5946 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-09 13:40:35.556  5946  5946 I Radio-JNI: register_android_hardware_Radio DONE
09-09 13:40:35.566  5946  5946 E AffinityControl: AffinityControl: registerfunction enter
09-09 13:40:35.576  5946  5946 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-09 13:40:35.606  1259  1853 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
09-09 13:40:35.616  1259  1853 D GameManagerService: identifyGamePackage. com.test.thalitest
09-09 13:40:35.626  1259  1853 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-09 13:40:35.636  1259  1853 D ActivityManager: mDVFSHelper.acquire()
09-09 13:40:35.636   443   443 I SurfaceFlinger: id=14 createSurf (16x16),-1 flag=20004, EimLayer(Di
09-09 13:40:35.636   443   443 I SurfaceFlinger: id=15 createSurf (16x16),-1 flag=20004, EimLayer(An
09-09 13:40:35.646  1259  1259 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-09 13:40:35.646  1259  1259 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-09 13:40:35.646  1694  1694 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-09 13:40:35.646  1694  1694 D WallpaperService: MSG_WINDOW_RESIZED
09-09 13:40:35.646  1259  1853 D FocusedStackFrame: Set to : 0
09-09 13:40:35.646  1694  1694 D WallpaperService: updateSurface
09-09 13:40:35.646  1694  1694 V WallpaperService: Changes: creating=false format=false size=false
09-09 13:40:35.646  1694  1694 V WallpaperService: mWidth:2048 SurfaceWidth:2048 mHeight:2048 SurfaceHeigh:2048
09-09 13:40:35.646  1694  1694 D WallpaperService: relayout
09-09 13:40:35.646  1259  1853 V WindowManager: addAppToken: AppWindowToken{d08736f5f token=Token{6e5cbfe ActivityRecord{5f14bb9 u0 com.test.thalitest/.MainActivity t18}}} to stack=2 task=18 at 0
09-09 13:40:35.646  1694  1694 V WallpaperService: Wallpaper size has changed: (2048, 2048)
09-09 13:40:35.656  1259  1417 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-09 13:40:35.656  1259  1417 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{805eb57 V.E...... R.....ID 0,0-0,0}
09-09 13:40:35.656  5955  5955 E Zygote  : v2
09-09 13:40:35.656  5955  5955 I libpersona: KNOX_SDCARD checking this for 10136
09-09 13:40:35.656  5955  5955 I libpersona: KNOX_SDCARD not a persona
09-09 13:40:35.656  1259  1853 I ActivityManager: Start proc 5955:com.test.thalitest/u0a136 for activity com.test.thalitest/.MainActivity
09-09 13:40:35.656  1259  1853 D InputDispatcher: Focused application set to: xxxx
09-09 13:40:35.656  5955  5955 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-09 13:40:35.656  1259  1621 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-09 13:40:35.656  5946  5946 D AndroidRuntime: Shutting down VM
09-09 13:40:35.666  5955  5955 E Zygote  : accessInfo : 0
09-09 13:40:35.666  5955  5955 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-09 13:40:35.666   443   443 I SurfaceFlinger: id=16 createSurf (1536x2048),1 flag=404, uhalitest
09-09 13:40:35.666  1259  1417 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 48 - 0, 0) vi=Rect(0, 48 - 0, 0) or=1
09-09 13:40:35.686  5955  5955 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:40:35.686  5955  5955 D ActivityThread: Added TimaKeyStore provider
09-09 13:40:35.696  1259  2320 D ActivityManager:  Launching com.test.thalitest, updated priority
09-09 13:40:35.696  1259  1259 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-09 13:40:35.706  1259  1417 V WindowStateAnimator: Finishing drawing window Window{8e9f32d u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-09 13:40:35.716   443   464 I SurfaceFlinger: id=10 Removed MauncherAct (6/12)
09-09 13:40:35.716   443   466 I SurfaceFlinger: id=10 Removed MauncherAct (-2/12)
09-09 13:40:35.716  1995  1995 V ActivityThread: updateVisibility : ActivityRecord{e9f3915 token=android.os.BinderProxy@d3316ba {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-09 13:40:35.716  1995  1995 D Launcher: onTrimMemory. Level: 20
,09-09 13:40:36.006  1259  2320 I WindowManager: Screenshot max retries 4 of Token{6e5cbfe ActivityRecord{5f14bb9 u0 com.test.thalitest/.MainActivity t18}} appWin=Window{8e9f32d u0 d0 Starting com.test.thalitest} drawState=4
09-09 13:40:36.006  1259  1385 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
,09-09 13:40:36.016  1259  1621 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,09-09 13:40:36.026  1259  3546 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-09 13:40:36.026  1259  3546 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-09 13:40:36.046  1259  1853 W ActivityManager: Permission Denial: getCurrentUser() from pid=5955, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
,09-09 13:40:36.056  5955  5955 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-09 13:40:36.056  5955  5955 D RelationGraph: garbageCollect()
,09-09 13:40:36.076  1259  1325 W ActivityManager: Permission Denial: getCurrentUser() from pid=5955, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
,09-09 13:40:36.086  5955  5955 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
,09-09 13:40:36.116  5955  5955 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-09 13:40:36.136  5955  5955 I cr_LibraryLoader: Time to load native libraries: 11 ms (timestamps 2456-2467)
,09-09 13:40:36.136  5955  5955 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
,09-09 13:40:36.166  5955  5969 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,09-09 13:40:36.166  5955  5955 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7b2cb7b}
,09-09 13:40:36.176  5955  5955 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
,09-09 13:40:36.176  5955  5955 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 13:40:36.196  5955  5955 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,09-09 13:40:36.266  5955  5955 I Adreno  : QUALCOMM build                   : 971aff5, Ic07f1cdce3
09-09 13:40:36.266  5955  5955 I Adreno  : Build Date                       : 03/29/16
09-09 13:40:36.266  5955  5955 I Adreno  : OpenGL ES Shader Compiler Version: XE031.06.00.02
09-09 13:40:36.266  5955  5955 I Adreno  : Local Branch                     : 
09-09 13:40:36.266  5955  5955 I Adreno  : Remote Branch                    : refs/tags/AU_LINUX_ANDROID_LA.BR.1.3.3.C2.06.00.01.205.077
09-09 13:40:36.266  5955  5955 I Adreno  : Remote Branch                    : NONE
09-09 13:40:36.266  5955  5955 I Adreno  : Reconstruct Branch               : NOTHING
,09-09 13:40:36.326  1259  2294 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10136
09-09 13:40:36.326  1259  2294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:851 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29617 com.android.server.am.ActivityManagerService.registerReceiver:22639 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3995 
,09-09 13:40:36.386  5955  5955 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,09-09 13:40:36.396  5955  5955 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-09 13:40:36.406  5955  5955 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,09-09 13:40:36.416  5955  5955 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-09 13:40:36.466  5955  5955 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-09 13:40:36.466  5955  5955 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{9f477f8 I.E...... R.....ID 0,0-0,0}
,09-09 13:40:36.466  5955  5993 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-09 13:40:36.476  1259  2629 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-09 13:40:36.476  1259  2629 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-09 13:40:36.476  1259  1259 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-09 13:40:36.476  1259  1259 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-09 13:40:36.486  5955  5969 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,09-09 13:40:36.496  5955  5955 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10136, CallingPid : 5955
,09-09 13:40:36.496  1259  2629 D ConnectivityService: listenForNetwork for Listen from uid/pid:10136/5955 for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:40:36.496  1259  1630 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
09-09 13:40:36.496  1259  1630 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,fe80::4678:3eff:feeb:95ef/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-09 13:40:36.496  1259  1630 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
09-09 13:40:36.496  1259  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-09 13:40:36.496  1259  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
09-09 13:40:36.506  1259  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-09 13:40:36.506  1259  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
09-09 13:40:36.506  1259  1630 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 13:40:36.516  5955  5955 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-09 13:40:36.526   443   443 I SurfaceFlinger: id=17 createSurf (1x1),1 flag=404, NainActivit
,09-09 13:40:36.536  5955  5993 I OpenGLRenderer: Initialized EGL, version 1.4
,09-09 13:40:36.556  5955  5955 V ActivityThread: updateVisibility : ActivityRecord{1b122d3 token=android.os.BinderProxy@22d28fe {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-09 13:40:36.596  5955  5993 E libGLESv2: HWUI Protection: wrong call from hwui context F: ES3-glCreateProgramSEC
,09-09 13:40:36.626  1259  1324 V WindowStateAnimator: Finishing drawing window Window{349c7c2 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,09-09 13:40:36.626  5955  5955 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 48 - 0, 0) vi=Rect(0, 48 - 0, 0) or=1
,09-09 13:40:36.636  1259  1417 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-09 13:40:36.636  1259  1259 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-09 13:40:36.636  1259  1417 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +626ms (total +986ms)
,09-09 13:40:36.636  1259  1259 I KnoxTimeoutHandler: SD activityfalse
09-09 13:40:36.636  1259  1259 I KnoxTimeoutHandler: Fullscreen and mCurrent is not KNOX user. Hence hide keyguard
09-09 13:40:36.636  1259  1417 D ActivityManager: mDVFSHelper.release()
09-09 13:40:36.636  1259  1417 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{5f14bb9 u0 com.test.thalitest/.MainActivity t18} time:92962
,09-09 13:40:36.636  1259  1417 D ViewRootImpl: #3 mView = null
09-09 13:40:36.636   443   464 I SurfaceFlinger: id=16 Removed uhalitest (6/12)
,09-09 13:40:36.646  5955  5998 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-09 13:40:36.646  1259  1721 V WindowStateAnimator: Finishing drawing window Window{349c7c2 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,09-09 13:40:36.656  5955  5955 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@22d28fe time:92980
,09-09 13:40:36.686  5955  5955 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5955
,09-09 13:40:36.886  5955  5955 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-09 13:40:37.006  5955  6004 D jxcore_app_log: JniHelper::setJavaVM(0xf4f7c000), pthread_self() = -627050192
,09-09 13:40:37.016  5955  6004 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 13:40:37.016  5955  6004 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 13:40:37.016  5955  6004 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 13:40:37.016  5955  6004 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 13:40:37.016  5955  6004 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-09 13:40:37.016  5955  6004 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@571cf28 added. We now have 1 listener(s)
,09-09 13:40:37.016  5955  6004 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:EB:95:EE
09-09 13:40:37.016  5955  6004 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:EB:95:EE"
,09-09 13:40:37.016  5955  6004 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:40:37.016  5955  6004 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 13:40:37.026  5955  6004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 13:40:37.026  5955  6004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 13:40:37.026  5955  6004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 13:40:37.026  5955  6004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:78:3E:EB:95:EE
09-09 13:40:37.026  5955  6004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 13:40:37.026  5955  6004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 13:40:37.026  5955  6004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 13:40:37.026  5955  6004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 13:40:37.026  5955  6004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 13:40:37.026  5955  6004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 13:40:37.026  5955  6004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 13:40:37.026  5955  6004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 13:40:37.026  5955  6004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 13:40:37.026  5955  6004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-09 13:40:37.026  5955  6004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b24ff27 added. We now have 1 listener(s)
09-09 13:40:37.026  5955  6004 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:40:37.026  5955  6004 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:40:37.026  5955  6004 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-09 13:40:37.026  5955  6004 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-09 13:40:37.026  5955  6004 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-09 13:40:37.026  5955  6004 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-09 13:40:37.026  5955  6004 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:40:37.026  5955  6004 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:EB:95:EE
,09-09 13:40:37.036  5955  6004 D BluetoothAdapter: STATE_ON
,09-09 13:40:37.036  5955  6004 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-09 13:40:37.036  5955  6004 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:40:37.036  5955  6004 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:40:37.036  5955  6004 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:40:37.036  5955  6004 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:40:37.036  5955  6004 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:40:37.036  5955  6004 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:40:37.036  5955  6004 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:40:37.036  5955  6004 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:40:37.036  5955  6004 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-09 13:40:37.036  5955  6004 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:40:37.036  5955  6004 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 13:40:37.036  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:40:37.036  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:40:37.056  5955  5955 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 13:40:37.356  5955  6005 W jxcore-log: Initializing JXcore engine
09-09 13:40:37.356  5955  6005 W jxcore-log: JXcore engine is ready
,09-09 13:40:37.386  2579  2579 E audit   : type=1400 msg=audit(1473421237.386:271): avc:  denied  { ioctl } for  pid=6005 comm="Thread-112" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5531 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-09 13:40:37.386  2579  2579 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-09 13:40:37.386  2579  2579 E audit   : type=1300 msg=audit(1473421237.386:271): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=7 a1=5451 a2=3 a3=da27f3c8 items=0 ppid=590 pid=6005 auid=4294967295 uid=10136 gid=10136 euid=10136 suid=10136 fsuid=10136 egid=10136 sgid=10136 fsgid=10136 ses=4294967295 tty=(none) comm="Thread-112" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-09 13:40:37.386  2579  2579 E audit   : type=1327 msg=audit(1473421237.386:271): proctitle="com.test.thalitest"
09-09 13:40:37.386  2579  2579 E audit   : type=1320 msg=audit(1473421237.386:271): 
09-09 13:40:37.386  2579  2579 E audit   : type=1400 msg=audit(1473421237.386:272): avc:  denied  { ioctl } for  pid=6005 comm="Thread-112" path="socket:[46386]" dev="sockfs" ino=46386 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-09 13:40:37.386  2579  2579 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-09 13:40:37.386  2579  2579 E audit   : type=1300 msg=audit(1473421237.386:272): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3c a1=5451 a2=3 a3=da27f3c8 items=0 ppid=590 pid=6005 auid=4294967295 uid=10136 gid=10136 euid=10136 suid=10136 fsuid=10136 egid=10136 sgid=10136 fsgid=10136 ses=4294967295 tty=(none) comm="Thread-112" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-09 13:40:37.386  2579  2579 E audit   : type=1327 msg=audit(1473421237.386:272): proctitle="com.test.thalitest"
09-09 13:40:37.386  2579  2579 E audit   : type=1320 msg=audit(1473421237.386:272): 
,09-09 13:40:37.396  5955  6005 W jxcore-log: Starting JXcore engine
,09-09 13:40:37.456  5955  6005 W jxcore-log: Platform android
09-09 13:40:37.456  5955  6005 W jxcore-log: 
09-09 13:40:37.456  5955  6005 W jxcore-log: Process ARCH arm
09-09 13:40:37.456  5955  6005 W jxcore-log: 
,09-09 13:40:37.476  1792  1792 D Recents : onTaskStackChanged
,09-09 13:40:37.536   720   720 I MSM-irqbalance: Decided to move IRQ166 from CPU2 to CPU3
,09-09 13:40:37.546  5955  6005 I jxcore-log: JXcore Cordova bridge is ready!
09-09 13:40:37.546  5955  6005 I jxcore-log: 
09-09 13:40:37.546  5955  6005 W jxcore-log: JXcore engine is started
,09-09 13:40:37.546  5955  6004 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-09 13:40:37.556  5955  5955 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-09 13:40:38.656  1259  1663 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/18_task.xml.bak
,09-09 13:40:39.036  1259  3546 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-09 13:40:40.056  1259  3576 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 13:40:41.576  3716  3716 D FactoryTest: User mode
,09-09 13:40:41.576  3716  3716 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,09-09 13:40:41.576  3716  3716 D MTPRx   : still no open session command from host, so toast
,09-09 13:40:41.576  1259  2320 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
,09-09 13:40:41.586  1259  2320 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
09-09 13:40:41.586  1259  2320 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.samsung.android.MtpApplication)
,09-09 13:40:41.586  1259  2320 D ActivityManager: mDVFSHelper.acquire()
,09-09 13:40:41.586  1259  2320 V WindowManager: addAppToken: AppWindowToken{d05d927d token=Token{93030d4 ActivityRecord{a818627 u0 com.samsung.android.MtpApplication/.USBConnection t19}}} to stack=2 task=19 at 0
,09-09 13:40:41.596  1259  2320 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,09-09 13:40:41.596  1259  1259 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
09-09 13:40:41.596  1259  1385 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,09-09 13:40:41.606  1259  2320 D InputDispatcher: Focused application set to: xxxx
,09-09 13:40:41.606  3716  3716 E MTPRx   : started activity for popup
,09-09 13:40:41.616  3716  3716 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-09 13:40:41.616  3716  3716 D RelationGraph: garbageCollect()
,09-09 13:40:41.626  1259  3546 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,09-09 13:40:41.626  3716  3716 D MTPUSBConnection: onCreate in USBConnection
09-09 13:40:41.626  3716  3716 V MTPUSBConnection: Registering broadcast receiver.
,09-09 13:40:41.636  3716  3716 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,09-09 13:40:41.636  1259  1853 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,09-09 13:40:41.666  3716  3716 D TAG     : dev.kiessupport is : TRUE
,09-09 13:40:41.686  3716  3716 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-09 13:40:41.686  3716  3716 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{687ea01 V.E...... R.....I. 0,0-0,0}
,09-09 13:40:41.696  3716  6007 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-09 13:40:41.706  3716  3716 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{d684800 I.E...... R.....I. 0,0-0,0}
,09-09 13:40:41.706  1259  1987 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
09-09 13:40:41.706  1259  1987 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-09 13:40:41.706  1259  1259 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-09 13:40:41.706  1259  1259 I KnoxTimeoutHandler: Shared devices show user statefalse
09-09 13:40:41.706  1259  1259 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,09-09 13:40:41.716   443   443 I SurfaceFlinger: id=18 createSurf (97x97),1 flag=4, VSBConnecti
,09-09 13:40:41.726  3716  6007 I Adreno  : QUALCOMM build                   : 971aff5, Ic07f1cdce3
09-09 13:40:41.726  3716  6007 I Adreno  : Build Date                       : 03/29/16
09-09 13:40:41.726  3716  6007 I Adreno  : OpenGL ES Shader Compiler Version: XE031.06.00.02
09-09 13:40:41.726  3716  6007 I Adreno  : Local Branch                     : 
09-09 13:40:41.726  3716  6007 I Adreno  : Remote Branch                    : refs/tags/AU_LINUX_ANDROID_LA.BR.1.3.3.C2.06.00.01.205.077
09-09 13:40:41.726  3716  6007 I Adreno  : Remote Branch                    : NONE
09-09 13:40:41.726  3716  6007 I Adreno  : Reconstruct Branch               : NOTHING
,09-09 13:40:41.736  3716  6007 I OpenGLRenderer: Initialized EGL, version 1.4
,09-09 13:40:41.746   443   443 I SurfaceFlinger: id=19 createSurf (129x129),1 flag=4, VSBConnecti
,09-09 13:40:41.766  3716  3716 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-09 13:40:41.766  3716  3716 V ActivityThread: updateVisibility : ActivityRecord{e9f0fdf token=android.os.BinderProxy@cb48629 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,09-09 13:40:41.776  3716  6007 E libGLESv2: HWUI Protection: wrong call from hwui context F: ES3-glCreateProgramSEC
,09-09 13:40:41.776  3716  6007 E libGLESv2: HWUI Protection: wrong call from hwui context F: ES3-glCreateProgramSEC
,09-09 13:40:41.786  3716  6007 E libGLESv2: HWUI Protection: wrong call from hwui context F: ES3-glCreateProgramSEC
,09-09 13:40:41.786  1259  2310 V WindowStateAnimator: Finishing drawing window Window{4b19435 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-09 13:40:41.796  1259  1987 V WindowStateAnimator: Finishing drawing window Window{763c23b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-09 13:40:41.796  3716  3716 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,09-09 13:40:41.796  1259  2304 V WindowStateAnimator: Finishing drawing window Window{763c23b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
09-09 13:40:41.796  3716  3716 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@cb48629 time:98127
,09-09 13:40:41.796  1259  1417 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-09 13:40:41.796  1259  1259 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-09 13:40:41.796  1259  1417 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +194ms (total +207ms)
,09-09 13:40:41.796  1259  1259 I KnoxTimeoutHandler: SD activityfalse
09-09 13:40:41.796  1259  1417 D ActivityManager: mDVFSHelper.release()
09-09 13:40:41.796  1259  1417 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{a818627 u0 com.samsung.android.MtpApplication/.USBConnection t19} time:98128
,09-09 13:40:42.066  1259  3546 D SSRM:s  : SIOP:: AP = 370, PST = 390 (W:9), CP = 47, LCD = 0
,09-09 13:40:42.076  1259  3546 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-09 13:40:42.296  1259  1853 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-09 13:40:42.296  1259  1853 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4359, temperature: 322, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-09 13:40:42.296  1259  1853 D BatteryService: online:4, current avg:41, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-132
09-09 13:40:42.296  1259  1259 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 13:40:42.296  1694  1694 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-09 13:40:42.296  1694  1694 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 13:40:42.296  1694  1694 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-09 13:40:42.306  2569  2569 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-09 13:40:42.306  2569  3088 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-09 13:40:42.326  1694  1694 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-09 13:40:42.326  1694  1694 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-09 13:40:42.326  1694  1694 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-09 13:40:42.706  1792  1792 D Recents : onTaskStackChanged
,09-09 13:40:42.716  1259  1989 D PackageManager: getComponentMetadataForIconTray : com.test.thalitest.MainActivity does not exist in mServices
09-09 13:40:42.716  1259  1989 D PackageManager: getComponentMetadataForIconTray : com.test.thalitest.MainActivity does not exist in mProviders
09-09 13:40:42.716  1259  1989 D PackageManager: getComponentMetadataForIconTray : com.test.thalitest.MainActivity does not exist in mReceivers
,09-09 13:40:42.726  1792  1792 I ApplicationPackageManager: load=com.test.thalitest, bg=96-96, dr=96-96
,09-09 13:40:42.726  1792  1792 I ApplicationPackageManager: scaled rate=0.98086953, size=96, alpha=2, hold=26, target=96
,09-09 13:40:43.306  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 13:40:43.306  5955  6005 I jxcore-log: 
,09-09 13:40:43.306  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-09 13:40:43.306  5955  6005 I jxcore-log: 
,09-09 13:40:43.316  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:43.316  5955  6005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:40:43.316  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:40:43.316  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:40:43.316  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:40:43.316  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:40:43.316  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:40:43.316  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:40:43.316  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:40:43.326  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:43.326  5955  6005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:40:43.326  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 13:40:43.326  5955  6005 I jxcore-log: 
,09-09 13:40:43.326  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
09-09 13:40:43.326  5955  6005 I jxcore-log: 
,09-09 13:40:43.646  5955  6005 I jxcore-log: Unit Test app is loaded
09-09 13:40:43.646  5955  6005 I jxcore-log: 
,09-09 13:40:43.646  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:40:43.646  5955  6005 I jxcore-log: 
,09-09 13:40:43.656  5955  6005 D executeNativeTests: Running unit tests,
09-09 13:40:43.656  5955  6005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 13:40:43.656  5955  6005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c66d6b added. We now have 2 listener(s)
09-09 13:40:43.656  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-09 13:40:43.656  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:40:43.656  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:40:43.656  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:40:43.656  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d9560c8 added. We now have 2 listener(s)
09-09 13:40:43.656  5955  6005 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:40:43.656  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:40:43.666  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:40:43.676  5955  6005 D BluetoothAdapter: STATE_ON,
,09-09 13:40:43.676  5955  6005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-09 13:40:43.676  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:40:43.676  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:40:43.676  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:40:43.676  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:40:43.676  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:40:43.676  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:40:43.676  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:40:43.676  5955  6005 D BluetoothAdapter: STATE_ON,
,09-09 13:40:43.686  5955  6005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
09-09 13:40:43.686  5955  6005 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:40:43.686  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:40:43.686  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-09 13:40:43.686  5955  5955 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-09 13:40:45.056  1259  3576 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 13:40:45.696  1259  1425 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-09 13:40:45.716  1259  1425 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-09 13:40:50.756  1259  1590 V AlarmManager: Expired Alarm result :4
,09-09 13:40:50.756  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f2b7704 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fadd615 1868:com.google.android.gms.persistent/u0a10}
,09-09 13:40:50.766  1259  1325 V AlarmManager:  remove PendingIntent] PendingIntent{4dd14ed: PendingIntentRecord{f644eec com.google.android.gms broadcastIntent}}
,09-09 13:40:50.866  1259  2320 V AlarmManager:  remove PendingIntent] PendingIntent{91a3db3: PendingIntentRecord{f644eec com.google.android.gms broadcastIntent}}
,09-09 13:40:51.006  1868  6012 I VacuumService: Vacuum at: now=1473421251010 tag=VacuumService
,09-09 13:40:51.056  1259  1324 V AlarmManager:  remove PendingIntent] PendingIntent{c483b6e: PendingIntentRecord{f644eec com.google.android.gms broadcastIntent}}
,09-09 13:40:51.516  1259  1833 E Watchdog: !@Sync 3 [09-09 13:40:51.529]
,09-09 13:40:52.116  1259  3546 D SSRM:s  : SIOP:: AP = 360, PST = 387 (W:10), CP = 43, LCD = 0
,09-09 13:40:52.116  1259  3546 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-09 13:40:52.346  1259  2008 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-09 13:40:52.346  1259  2008 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4390, temperature: 321, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-09 13:40:52.346  1259  2008 D BatteryService: online:4, current avg:21, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:171
09-09 13:40:52.346  1259  1259 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 13:40:52.346  1694  1694 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-09 13:40:52.346  1694  1694 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 13:40:52.356  1694  1694 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-09 13:40:52.356  2569  2569 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-09 13:40:52.356  2569  3088 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-09 13:40:52.376  1694  1694 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-09 13:40:52.376  1694  1694 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-09 13:40:52.376  1694  1694 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-09 13:40:52.566   720   720 I MSM-irqbalance: Decided to move IRQ166 from CPU3 to CPU1
,09-09 13:40:53.766  5955  6005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:40:53.766  5955  6005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56eaf36 added. We now have 3 listener(s)
,09-09 13:40:53.766  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-09 13:40:53.766  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:40:53.766  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:40:53.766  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:40:53.766  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3473e37 added. We now have 3 listener(s)
09-09 13:40:53.766  5955  6005 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:40:53.766  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:40:53.776  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-09 13:40:53.776  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:53.786  5955  6005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-09 13:40:53.786  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:40:53.786  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:40:53.786  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:40:53.786  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:40:53.786  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:40:53.786  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:40:53.786  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:40:53.786  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:53.786  5955  6005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
09-09 13:40:53.786  5955  6005 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:40:53.786  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:53.796  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:40:53.796  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-09 13:40:53.796  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:40:53.796  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:40:53.796  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 13:40:53.796  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:40:53.796  5955  6005 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-09 13:40:53.796  5955  6005 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 13:40:53.796  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:40:53.796  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:40:53.796  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:40:53.796  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:40:53.796  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:40:53.796  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:53.796  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:40:53.796  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:40:53.796  5955  6005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56eaf36 removed from the list,
09-09 13:40:53.796  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:40:53.796  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3473e37 removed from the list
09-09 13:40:53.796  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:40:53.796  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:40:53.806  5955  6005 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-09 13:40:53.806  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:40:53.806  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:40:53.806  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:53.806  5955  6005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56eaf36 not in the list
09-09 13:40:53.806  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:40:53.806  5955  6005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3473e37 not in the list
09-09 13:40:53.806  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:40:53.806  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:40:53.806  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 13:40:53.816  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:40:53.816  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:53.816  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:53.816  5955  6005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56eaf36 not in the list
09-09 13:40:53.816  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:40:53.816  5955  6005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3473e37 not in the list
09-09 13:40:53.816  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:40:53.816  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:53.816  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:53.816  5955  6005 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-09 13:40:53.816  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:40:53.826  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:53.826  5955  6005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:40:53.826  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:40:53.826  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:40:53.826  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:40:53.826  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:40:53.826  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:40:53.826  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:40:53.826  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:40:53.826  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:53.826  5955  6005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:40:53.826  5955  6005 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:40:53.826  5955  6005 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-09 13:40:53.826  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-09 13:40:53.826  5955  6005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:40:53.826  5955  6005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:40:53.826  5955  6005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-09 13:40:53.826  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:40:53.826  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 13:40:53.836  5955  6005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:40:53.836  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:40:53.836  5955  6005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:40:53.836  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:40:53.836  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:40:53.836  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:40:53.836  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:40:53.836  5955  6013 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:40:53.836  5955  6013 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:40:53.836  5955  6005 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 13:40:53.836  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:40:53.836  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:40:53.836  5955  5955 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-09 13:40:53.836  5955  6013 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-09 13:40:53.846  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:53.846  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:53.846  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:53.846  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:40:53.846  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:53.846  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:40:53.846  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 13:40:53.846  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:40:53.856  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:53.856  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-09 13:40:53.856  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:EB:95:EE"
,09-09 13:40:53.856  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 44 78 3E EB 95 EE
,09-09 13:40:53.856  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:40:53.856  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:40:53.856  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 13:40:53.856  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:53.856  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:40:53.856  5955  6005 D BluetoothLeAdvertiser: start advertising
09-09 13:40:53.856  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:53.866  2569  2589 D BtGatt.GattService: registerClient() - UUID=a96ae7a4-29d1-478b-8c48-3c3bb5344369
,09-09 13:40:53.916  2569  2739 D BtGatt.GattService: onClientRegistered() - UUID=a96ae7a4-29d1-478b-8c48-3c3bb5344369, clientIf=6
09-09 13:40:53.916  5955  5965 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-09 13:40:53.916  2569  3085 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-09 13:40:53.916  2569  3085 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-09 13:40:53.916  2569  3085 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-09 13:40:53.916  2569  2746 D BtGatt.AdvertiseManager: message : 0
09-09 13:40:53.916  2569  2761 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-09 13:40:53.916  2569  2761 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
,09-09 13:40:53.926  2569  2746 D BtGatt.AdvertiseManager: number of adv instance running = 0
09-09 13:40:53.926  2569  2746 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:40:53.926  2569  2746 D BtGatt.AdvertiseManager: starting advertising
,09-09 13:40:53.926  2569  2746 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-09 13:40:53.926  2970  2971 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
,09-09 13:40:53.926  1259  1853 V AlarmManager:  remove PendingIntent] PendingIntent{b5ca934: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:53.926  2970  2971 I WCNSS_FILTER: do_write: IBS write: fd
,09-09 13:40:53.936  2569  2761 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 10
,09-09 13:40:53.936  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 28 : bytes_written: 28
,09-09 13:40:53.936  2970  2970 I WCNSS_FILTER: do_write: IBS write: fc
09-09 13:40:53.936  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-09 13:40:53.936  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
,09-09 13:40:53.936  1259  1987 V AlarmManager:  remove PendingIntent] PendingIntent{43a135d: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:53.936  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-09 13:40:53.936  2569  2739 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-09 13:40:53.936  2569  2746 D BtGatt.AdvertiseManager: starting multi advertising
09-09 13:40:53.936  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 38 : bytes_written: 38
09-09 13:40:53.936  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-09 13:40:53.936  2569  2739 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
09-09 13:40:53.936  1259  2310 V AlarmManager:  remove PendingIntent] PendingIntent{58ec4d2: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:53.936  2569  2746 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-09 13:40:53.936  2569  2746 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-09 13:40:53.936  2569  2746 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
09-09 13:40:53.936  2569  2746 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
09-09 13:40:53.936  5955  5966 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,09-09 13:40:53.946  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-09 13:40:53.946  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:40:53.946  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-09 13:40:53.946  1259  1324 V AlarmManager:  remove PendingIntent] PendingIntent{a2df9a3: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:53.946  2569  2761 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24557020
09-09 13:40:53.946  2569  2761 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
,09-09 13:40:53.946  2569  2761 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-09 13:40:53.946  2569  2761 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-09 13:40:53.946  5955  6005 I io.jxcore.node.ConnectionHelper: start: OK
09-09 13:40:53.946  5955  5955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:40:53.946  5955  5955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-09 13:40:53.946  5955  5955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-09 13:40:53.946  5955  5955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 13:40:53.946  5955  5955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-09 13:40:53.946  5955  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-09 13:40:53.946  1259  1721 V AlarmManager:  remove PendingIntent] PendingIntent{eb524a0: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:53.946  5955  5955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-09 13:40:53.946  5955  5955 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
09-09 13:40:53.946  1259  2310 V AlarmManager:  remove PendingIntent] PendingIntent{8098859: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:40:54.446  5955  6005 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:40:54.446  5955  6005 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 13:40:54.446  5955  6005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-09 13:40:54.446  5955  6005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 13:40:54.446  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:40:54.446  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:40:54.446  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:40:54.446  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 13:40:54.446  5955  6005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:40:54.446  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-09 13:40:54.446  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:40:54.446  5955  5955 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:40:54.446  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:40:54.446  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:40:54.446  5955  6013 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:40:54.446  5955  6013 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-09 13:40:54.446  5955  6013 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:40:54.456  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:40:54.456  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:54.456  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:40:54.456  5955  6005 D BluetoothLeScanner: could not find callback wrapper
09-09 13:40:54.456  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:40:54.456  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-09 13:40:54.456  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:54.456  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:54.456  5955  6005 D BluetoothLeAdvertiser: stop advertising
,09-09 13:40:54.466  2569  2589 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-09 13:40:54.466  2569  2589 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-09 13:40:54.466  2569  2746 D BtGatt.AdvertiseManager: message : 1
09-09 13:40:54.466  2569  2761 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
09-09 13:40:54.466  2569  2761 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
,09-09 13:40:54.466  2569  2761 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-09 13:40:54.466  2569  2761 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
,09-09 13:40:54.466  2569  2746 D BtGatt.AdvertiseManager: stop advertise for client =  6
09-09 13:40:54.466  2569  2761 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
09-09 13:40:54.466  2569  2746 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
,09-09 13:40:54.466  2569  2746 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
09-09 13:40:54.466  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
09-09 13:40:54.466  1259  2629 V AlarmManager:  remove PendingIntent] PendingIntent{1705c1e: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:40:54.466  2970  2970 I WCNSS_FILTER: do_write: IBS write: fc
,09-09 13:40:54.466  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-09 13:40:54.466  2970  2971 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-09 13:40:54.466  2569  2739 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-09 13:40:54.466  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
09-09 13:40:54.466  1259  2621 V AlarmManager:  remove PendingIntent] PendingIntent{61c8cff: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:54.466  2569  2739 D BtGatt.GattService: Client app is not null!
09-09 13:40:54.466  5955  5965 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
09-09 13:40:54.476  2569  3085 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 13:40:54.476  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 13:40:54.476  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:40:54.476  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-09 13:40:54.476  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-09 13:40:54.476  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:40:54.476  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:40:54.476  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:40:54.476  1259  1637 V AlarmManager:  remove PendingIntent] PendingIntent{957eacc: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:54.476  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:40:54.476  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:40:54.476  5955  5955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:40:54.476  5955  5955 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-09 13:40:54.476  5955  5955 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-09 13:40:54.486  5955  6005 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-09 13:40:54.486  5955  6005 V io.jxcore.node.ConnectivityMonitor: start: Already started
,09-09 13:40:54.486  5955  6005 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-09 13:40:54.486  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-09 13:40:54.486  5955  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:40:54.486  5955  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:40:54.486  5955  5955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:40:54.486  5955  5955 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:40:54.486  5955  6005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:40:54.486  5955  6005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:40:54.486  5955  6005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:40:54.486  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:40:54.486  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:40:54.486  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
09-09 13:40:54.486  5955  6005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:40:54.486  5955  6005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:40:54.486  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-09 13:40:54.486  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:40:54.486  5955  5955 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:40:54.486  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:40:54.486  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:40:54.486  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-09 13:40:54.486  1259  1324 V AlarmManager:  remove PendingIntent] PendingIntent{9c15115: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:54.486  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-09 13:40:54.486  5955  6017 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:40:54.486  5955  6017 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:40:54.486  5955  6017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-09 13:40:54.496  1259  2294 V AlarmManager:  remove PendingIntent] PendingIntent{ff2e991: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:40:54.496  5955  6005 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 13:40:54.496  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 13:40:54.496  1259  1325 V AlarmManager:  remove PendingIntent] PendingIntent{4bdd0f6: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:40:54.496  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:54.496  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:54.496  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:54.496  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:40:54.496  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:54.506  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:40:54.506  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 13:40:54.506  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:40:54.506  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:54.506  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-09 13:40:54.506  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:EB:95:EE"
,09-09 13:40:54.506  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 44 78 3E EB 95 EE
09-09 13:40:54.506  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:40:54.506  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:40:54.506  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 13:40:54.506  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:54.506  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:40:54.506  5955  6005 D BluetoothLeAdvertiser: start advertising
,09-09 13:40:54.506  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:54.516  2569  3085 D BtGatt.GattService: registerClient() - UUID=bb174429-12ee-4091-a13d-8f8188c77cfc
,09-09 13:40:54.556  2569  2739 D BtGatt.GattService: onClientRegistered() - UUID=bb174429-12ee-4091-a13d-8f8188c77cfc, clientIf=6
,09-09 13:40:54.556  5955  5966 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-09 13:40:54.556  2569  2589 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-09 13:40:54.566  2569  2589 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-09 13:40:54.566  2569  2589 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-09 13:40:54.566  2569  2746 D BtGatt.AdvertiseManager: message : 0
09-09 13:40:54.566  2569  2761 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-09 13:40:54.566  2569  2761 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
,09-09 13:40:54.566  2569  2746 D BtGatt.AdvertiseManager: number of adv instance running = 0
09-09 13:40:54.566  2569  2746 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:40:54.566  2569  2746 D BtGatt.AdvertiseManager: starting advertising
09-09 13:40:54.566  2569  2746 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-09 13:40:54.566  1259  1987 V AlarmManager:  remove PendingIntent] PendingIntent{ec11cf7: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:40:54.566  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 28 : bytes_written: 28
09-09 13:40:54.566  2970  2970 I WCNSS_FILTER: do_write: IBS write: fc
09-09 13:40:54.566  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-09 13:40:54.566  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
09-09 13:40:54.576  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-09 13:40:54.576  2569  2761 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 11
09-09 13:40:54.576  2569  2761 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24557020
09-09 13:40:54.576  2569  2761 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-09 13:40:54.576  1259  2320 V AlarmManager:  remove PendingIntent] PendingIntent{d16c764: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:54.576  2569  2761 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-09 13:40:54.576  2569  2761 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-09 13:40:54.576  2569  2739 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-09 13:40:54.576  2569  2746 D BtGatt.AdvertiseManager: starting multi advertising
09-09 13:40:54.576  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 38 : bytes_written: 38
,09-09 13:40:54.576  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-09 13:40:54.576  1259  1637 V AlarmManager:  remove PendingIntent] PendingIntent{ecb8dcd: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:54.576  2569  2739 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
09-09 13:40:54.576  2569  2746 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-09 13:40:54.576  2569  2746 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-09 13:40:54.576  2569  2746 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
09-09 13:40:54.576  2569  2746 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
09-09 13:40:54.576  5955  5965 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
09-09 13:40:54.576  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-09 13:40:54.576  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 13:40:54.576  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:40:54.576  1259  2294 V AlarmManager:  remove PendingIntent] PendingIntent{b6e0682: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:54.576  5955  6005 I io.jxcore.node.ConnectionHelper: start: OK
09-09 13:40:54.576  5955  5955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:40:54.576  5955  5955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-09 13:40:54.576  5955  5955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-09 13:40:54.576  5955  5955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 13:40:54.576  5955  5955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-09 13:40:54.576  5955  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:40:54.586  1259  1721 V AlarmManager:  remove PendingIntent] PendingIntent{e609193: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:40:54.586  5955  5955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:40:54.586  5955  5955 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:40:54.586  1259  2621 V AlarmManager:  remove PendingIntent] PendingIntent{62af5d0: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:40:55.086  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:40:55.086  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-09 13:40:55.086  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:40:55.086  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:40:55.086  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 13:40:55.086  5955  6005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:40:55.086  5955  6005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56eaf36 not in the list
09-09 13:40:55.086  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:40:55.086  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:40:55.086  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:40:55.086  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:40:55.086  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:40:55.086  5955  5955 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-09 13:40:55.086  5955  6017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:40:55.086  5955  6017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:40:55.086  5955  6017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:40:55.086  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:55.086  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:40:55.086  5955  6005 D BluetoothLeScanner: could not find callback wrapper
09-09 13:40:55.086  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:40:55.086  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-09 13:40:55.086  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:55.086  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:40:55.086  5955  6005 D BluetoothLeAdvertiser: stop advertising
,09-09 13:40:55.096  2569  3085 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-09 13:40:55.096  2569  3085 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-09 13:40:55.096  2569  2746 D BtGatt.AdvertiseManager: message : 1
,09-09 13:40:55.096  2569  2761 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
09-09 13:40:55.096  2569  2761 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
09-09 13:40:55.096  2569  2761 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-09 13:40:55.096  2569  2761 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-09 13:40:55.096  2569  2761 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
09-09 13:40:55.096  2569  2746 D BtGatt.AdvertiseManager: stop advertise for client =  6
09-09 13:40:55.096  2569  2746 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
,09-09 13:40:55.096  2569  2746 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
09-09 13:40:55.096  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
,09-09 13:40:55.096  1259  1637 V AlarmManager:  remove PendingIntent] PendingIntent{61039c9: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:55.096  2970  2970 I WCNSS_FILTER: do_write: IBS write: fc
09-09 13:40:55.096  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-09 13:40:55.096  2569  2739 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-09 13:40:55.096  2569  2739 D BtGatt.GattService: Client app is not null!
09-09 13:40:55.096  2970  2971 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-09 13:40:55.096  5955  5966 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
09-09 13:40:55.096  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,09-09 13:40:55.106  2569  2589 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 13:40:55.106  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 13:40:55.106  1259  1987 V AlarmManager:  remove PendingIntent] PendingIntent{fa08ce: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:55.106  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:40:55.106  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-09 13:40:55.106  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-09 13:40:55.106  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:40:55.106  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:40:55.106  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:40:55.106  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:40:55.106  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:40:55.106  5955  6005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3473e37 not in the list
,09-09 13:40:55.106  1259  1721 V AlarmManager:  remove PendingIntent] PendingIntent{678b3ef: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:55.106  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:40:55.106  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:55.106  5955  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:40:55.106  5955  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:40:55.106  5955  5955 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-09 13:40:55.106  5955  5955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:40:55.106  5955  5955 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:40:55.106  5955  6005 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-09 13:40:55.116  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:40:55.116  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
09-09 13:40:55.116  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-09 13:40:55.116  1259  2294 V AlarmManager:  remove PendingIntent] PendingIntent{f46a00b: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:55.116  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-09 13:40:55.116  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:55.116  1259  1987 V AlarmManager:  remove PendingIntent] PendingIntent{957aee8: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:40:55.126  5955  6005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:40:55.126  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:40:55.126  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:40:55.126  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:40:55.126  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:40:55.126  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:40:55.126  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:40:55.126  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:40:55.126  1259  1721 V AlarmManager:  remove PendingIntent] PendingIntent{1105901: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:40:55.126  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:55.126  5955  6005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:40:55.126  5955  6005 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:40:55.126  5955  6005 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-09 13:40:55.126  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-09 13:40:55.126  5955  6005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:40:55.126  5955  6005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:40:55.126  5955  6005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:40:55.126  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:40:55.136  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:40:55.136  5955  6005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:40:55.136  5955  6005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:40:55.136  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:40:55.136  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:40:55.136  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:40:55.136  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:40:55.136  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:40:55.136  5955  6020 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:40:55.136  5955  6020 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:40:55.136  5955  6005 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 13:40:55.136  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:40:55.136  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:40:55.136  5955  5955 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-09 13:40:55.136  5955  6020 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-09 13:40:55.136  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:55.146  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:55.146  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:55.146  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:40:55.146  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:55.146  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:40:55.146  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 13:40:55.146  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:40:55.146  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:55.146  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-09 13:40:55.146  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-09 13:40:55.146  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 44 78 3E EB 95 EE
09-09 13:40:55.146  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:40:55.146  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:40:55.146  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 13:40:55.146  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:40:55.146  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:40:55.146  5955  6005 D BluetoothLeAdvertiser: start advertising
,09-09 13:40:55.156  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:55.156  2569  2585 D BtGatt.GattService: registerClient() - UUID=f365d958-ca32-4bd2-825d-8dd6f8817c55
,09-09 13:40:55.196  2569  2739 D BtGatt.GattService: onClientRegistered() - UUID=f365d958-ca32-4bd2-825d-8dd6f8817c55, clientIf=6
,09-09 13:40:55.196  5955  5965 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-09 13:40:55.196  2569  2589 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-09 13:40:55.206  2569  2589 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-09 13:40:55.206  2569  2589 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-09 13:40:55.206  2569  2761 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
,09-09 13:40:55.206  2569  2761 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
09-09 13:40:55.206  2569  2746 D BtGatt.AdvertiseManager: message : 0
09-09 13:40:55.206  2569  2746 D BtGatt.AdvertiseManager: number of adv instance running = 0,
09-09 13:40:55.206  2569  2746 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:40:55.206  2569  2746 D BtGatt.AdvertiseManager: starting advertising
,09-09 13:40:55.206  2569  2746 D BtGatt.AdvertiseManager: isStandardAdv = false
09-09 13:40:55.206  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 28 : bytes_written: 28
09-09 13:40:55.216  2970  2970 I WCNSS_FILTER: do_write: IBS write: fc
09-09 13:40:55.216  1259  1987 V AlarmManager:  remove PendingIntent] PendingIntent{8a8843d: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:40:55.216  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-09 13:40:55.216  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
09-09 13:40:55.216  2569  2761 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 12
09-09 13:40:55.216  2569  2761 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24557020
,09-09 13:40:55.216  2569  2761 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-09 13:40:55.216  2569  2761 D BtGatt.GattService: [GSIM LOG]: updateAdvTime,
09-09 13:40:55.216  2569  2761 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-09 13:40:55.216  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-09 13:40:55.216  2569  2739 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-09 13:40:55.216  2569  2746 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:40:55.216  1259  2304 V AlarmManager:  remove PendingIntent] PendingIntent{c391432: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:55.216  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 38 : bytes_written: 38
,09-09 13:40:55.216  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-09 13:40:55.216  2569  2739 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-09 13:40:55.216  2569  2746 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-09 13:40:55.216  2569  2746 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-09 13:40:55.216  2569  2746 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
09-09 13:40:55.216  2569  2746 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
09-09 13:40:55.216  5955  5966 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
09-09 13:40:55.216  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-09 13:40:55.216  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 13:40:55.226  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:40:55.226  5955  6005 I io.jxcore.node.ConnectionHelper: start: OK
09-09 13:40:55.226  1259  2629 V AlarmManager:  remove PendingIntent] PendingIntent{9210583: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:55.226  5955  5955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:40:55.226  5955  5955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-09 13:40:55.226  5955  5955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-09 13:40:55.226  5955  5955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 13:40:55.226  5955  5955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-09 13:40:55.226  5955  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:40:55.226  1259  1853 V AlarmManager:  remove PendingIntent] PendingIntent{90f7300: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:55.226  5955  5955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-09 13:40:55.226  5955  5955 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:40:55.226  1259  1637 V AlarmManager:  remove PendingIntent] PendingIntent{29e2739: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:40:55.236  1259  2621 V AlarmManager:  remove PendingIntent] PendingIntent{c60417e: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:40:55.726  5955  6005 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-09 13:40:55.726  5955  6005 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 13:40:55.726  5955  6005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-09 13:40:55.726  5955  6005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 13:40:55.726  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:40:55.726  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-09 13:40:55.726  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:40:55.726  5955  6020 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:40:55.726  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 13:40:55.726  5955  6020 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:40:55.726  5955  6005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-09 13:40:55.726  5955  6020 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:40:55.726  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:40:55.726  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:40:55.726  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:40:55.726  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 13:40:55.726  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:40:55.726  5955  5955 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:40:55.726  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:55.726  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:40:55.726  5955  6005 D BluetoothLeScanner: could not find callback wrapper
09-09 13:40:55.726  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
09-09 13:40:55.726  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-09 13:40:55.726  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:55.726  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:40:55.726  5955  6005 D BluetoothLeAdvertiser: stop advertising
,09-09 13:40:55.736  2569  2585 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-09 13:40:55.736  2569  2585 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-09 13:40:55.736  2569  2746 D BtGatt.AdvertiseManager: message : 1
,09-09 13:40:55.736  2569  2761 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
09-09 13:40:55.736  2569  2761 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
09-09 13:40:55.736  1259  2008 V AlarmManager:  remove PendingIntent] PendingIntent{e6476df: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:55.736  2569  2761 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-09 13:40:55.736  2569  2761 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-09 13:40:55.736  2569  2761 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
,09-09 13:40:55.736  2569  2746 D BtGatt.AdvertiseManager: stop advertise for client =  6
09-09 13:40:55.736  2569  2746 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
09-09 13:40:55.736  2569  2746 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
09-09 13:40:55.736  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
09-09 13:40:55.736  2970  2970 I WCNSS_FILTER: do_write: IBS write: fc
,09-09 13:40:55.736  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-09 13:40:55.746  2970  2971 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-09 13:40:55.746  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
09-09 13:40:55.746  2569  2739 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-09 13:40:55.746  2569  2739 D BtGatt.GattService: Client app is not null!
09-09 13:40:55.746  5955  5965 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,09-09 13:40:55.746  2569  2589 D BtGatt.GattService: unregisterClient() - clientIf=6
09-09 13:40:55.746  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 13:40:55.746  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:40:55.746  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-09 13:40:55.746  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-09 13:40:55.746  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-09 13:40:55.746  1259  2629 V AlarmManager:  remove PendingIntent] PendingIntent{c78bf2c: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:40:55.746  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:40:55.746  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:40:55.746  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:40:55.746  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:40:55.746  5955  5955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:40:55.746  5955  5955 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-09 13:40:55.746  5955  5955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:40:55.746  5955  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:40:55.746  5955  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:40:55.746  5955  5955 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-09 13:40:55.746  5955  5955 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:40:55.746  1259  2304 V AlarmManager:  remove PendingIntent] PendingIntent{1b0fdf5: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:55.746  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:40:55.746  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:55.746  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:40:55.746  5955  6005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56eaf36 not in the list
09-09 13:40:55.746  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:40:55.746  5955  6005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3473e37 not in the list
09-09 13:40:55.746  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:40:55.746  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:55.756  5955  6005 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-09 13:40:55.756  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:40:55.756  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:55.756  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:55.756  5955  6005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56eaf36 not in the list
09-09 13:40:55.756  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:40:55.756  5955  6005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3473e37 not in the list
09-09 13:40:55.756  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:40:55.756  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:55.756  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:55.756  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
09-09 13:40:55.756  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 13:40:55.756  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:40:55.756  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:55.756  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:55.756  5955  6005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56eaf36 not in the list
09-09 13:40:55.756  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:40:55.756  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-09 13:40:55.756  5955  6005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3473e37 not in the list
09-09 13:40:55.756  1259  1325 V AlarmManager:  remove PendingIntent] PendingIntent{63af78a: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:55.756  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:40:55.756  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:55.756  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:55.756  5955  6005 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-09 13:40:55.756  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:40:55.756  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:55.756  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:55.756  5955  6005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56eaf36 not in the list
09-09 13:40:55.756  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:40:55.756  5955  6005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.Discover,yManager@3473e37 not in the list
09-09 13:40:55.756  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:40:55.756  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:55.756  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:55.756  5955  6005 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-09 13:40:55.756  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:40:55.756  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:55.756  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:55.756  5955  6005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56eaf36 not in the list
09-09 13:40:55.756  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:40:55.756  5955  6005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3473e37 not in the list
09-09 13:40:55.756  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:40:55.756  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:55.756  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:55.756  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:40:55.756  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:40:55.756  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:40:55.756  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:40:55.756  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:40:55.756  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:40:55.766  1259  2294 V AlarmManager:  remove PendingIntent] PendingIntent{d43a1fb: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:55.756  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:40:55.756  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:40:55.756  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:40:55.756  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:40:55.756  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:55.756  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:55.756  5955  6005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56eaf36 not in the list
09-09 13:40:55.756  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:40:55.756  5955  6005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3473e37 not in the list
09-09 13:40:55.756  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:40:55.756  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:55.756  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:55.766  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-09 13:40:55.766  5955  6005 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:40:55.766  5955  6005 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 13:40:55.766  5955  6005 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:40:55.766  5955  6005 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-09 13:40:55.766  1259  1987 V AlarmManager:  remove PendingIntent] PendingIntent{448a218: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 13:40:55.766  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 13:40:55.766  5955  6005 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 13:40:55.766  5955  6005 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:40:55.766  5955  6005 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-09 13:40:55.766  5955  6005 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:40:55.766  5955  6005 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:40:55.766  5955  6005 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 13:40:55.766  5955  6005 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:40:55.766  5955  6005 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:40:55.766  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-09 13:40:55.776  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-09 13:40:55.776  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 13:40:55.776  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-09 13:40:55.776  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-09 13:40:55.776  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-09 13:40:55.776  5955  6005 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 13:40:55.776  5955  6005 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:40:55.776  5955  6005 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-09 13:40:55.776  5955  6024 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 212)
09-09 13:40:55.776  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:40:55.776  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:55.776  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:55.776  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-09 13:40:55.776  5955  6005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56eaf36 not in the list
09-09 13:40:55.776  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:40:55.776  5955  6025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 212
09-09 13:40:55.776  5955  6005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3473e37 not in the list
09-09 13:40:55.776  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:40:55.776  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:55.776  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:55.776  5955  6005 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 13:40:55.776  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:40:55.776  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:55.776  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:55.776  5955  6005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56eaf36 not in the list
09-09 13:40:55.776  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:40:55.776  5955  6005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3473e37 not in the list
09-09 13:40:55.776  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:40:55.776  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:55.776  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:55.786  5955  6005 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 13:40:55.786  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:40:55.786  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:55.786  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:55.786  5955  6005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56eaf36 not in the list
09-09 13:40:55.786  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:40:55.786  5955  6005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3473e37 not in the list
09-09 13:40:55.786  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:40:55.786  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:55.786  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:55.786  5955  6005 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 13:40:55.786  5955  6005 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 13:40:55.786  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:40:55.786  5955  6005 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 13:40:55.786  5955  6005 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 13:40:55.786  5955  6005 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 13:40:55.786  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:40:55.786  5955  6005 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 13:40:55.786  5955  6005 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 13:40:55.786  5955  6005 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 13:40:55.786  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:40:55.786  5955  6005 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-09 13:40:55.786  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:40:55.786  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:55.786  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:55.786  5955  6005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56eaf36 not in the list
09-09 13:40:55.786  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:40:55.786  5955  6005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3473e37 not in the list
09-09 13:40:55.786  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:40:55.786  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:55.786  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:55.786  5955  6024 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-09 13:40:55.786  5955  6005 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-09 13:40:55.786  5955  6024 D BluetoothSocket: connect(): myUserId = 0
09-09 13:40:55.786  5955  6024 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:40:55.786  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:40:55.786  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:40:55.796  5955  6005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:40:55.796  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:40:55.796  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:40:55.796  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:40:55.796  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:40:55.796  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:40:55.796  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:40:55.796  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:40:55.796  1259  2304 D SecContentProvider: insert(), uri = 2
09-09 13:40:55.796  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:40:55.796  2569  3029 W bt_btif : bta_dm_acl_change(), event : 2
09-09 13:40:55.796  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 17 : bytes_written: 17
09-09 13:40:55.796  1259  2621 V AlarmManager:  remove PendingIntent] PendingIntent{431c7c4: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:55.796  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,09-09 13:40:55.796  5955  6005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:40:55.796  5955  6005 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:40:55.796  5955  6005 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-09 13:40:55.796  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-09 13:40:55.796  5955  6005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:40:55.796  5955  6005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:40:55.796  5955  6005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:40:55.796  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:40:55.796  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:40:55.796  5955  6005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:40:55.796  5955  6005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:40:55.806  1259  1637 V AlarmManager:  remove PendingIntent] PendingIntent{6659c30: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:55.796  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:40:55.796  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:40:55.796  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:40:55.796  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:40:55.806  5955  6026 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:40:55.806  5955  6026 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:40:55.806  5955  6005 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 13:40:55.806  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 13:40:55.806  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:40:55.806  5955  6026 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-09 13:40:55.806  1259  2294 V AlarmManager:  remove PendingIntent] PendingIntent{bfa50a9: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:55.806  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:40:55.806  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:40:55.806  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:40:55.806  5955  5955 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:40:55.816  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:40:55.816  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 13:40:55.816  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:40:55.816  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:40:55.816  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 13:40:55.816  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 13:40:55.816  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:40:55.816  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-09 13:40:55.816  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-09 13:40:55.816  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 44 78 3E EB 95 EE
09-09 13:40:55.816  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:40:55.816  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:40:55.816  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-09 13:40:55.826  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:40:55.826  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:40:55.826  5955  6005 D BluetoothLeAdvertiser: start advertising
09-09 13:40:55.826  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:40:55.826  2569  3085 D BtGatt.GattService: registerClient() - UUID=e4f1dba8-0e20-4c2c-bb54-b0254585517a
,09-09 13:40:55.866  2569  2739 D BtGatt.GattService: onClientRegistered() - UUID=e4f1dba8-0e20-4c2c-bb54-b0254585517a, clientIf=6
,09-09 13:40:55.866  5955  5966 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-09 13:40:55.866  2569  2585 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-09 13:40:55.876  2569  2585 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-09 13:40:55.876  2569  2585 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-09 13:40:55.876  2569  2761 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-09 13:40:55.876  2569  2761 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
09-09 13:40:55.876  2569  2746 D BtGatt.AdvertiseManager: message : 0
,09-09 13:40:55.876  2569  2746 D BtGatt.AdvertiseManager: number of adv instance running = 0
09-09 13:40:55.876  2569  2746 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:40:55.876  2569  2746 D BtGatt.AdvertiseManager: starting advertising
,09-09 13:40:55.876  2569  2746 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-09 13:40:55.876  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 28 : bytes_written: 28
09-09 13:40:55.876  1259  1853 V AlarmManager:  remove PendingIntent] PendingIntent{9de062e: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:40:55.876  2970  2970 I WCNSS_FILTER: do_write: IBS write: fc
09-09 13:40:55.876  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-09 13:40:55.876  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
09-09 13:40:55.876  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-09 13:40:55.876  2569  2739 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
09-09 13:40:55.876  2569  2761 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 13
09-09 13:40:55.876  2569  2761 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24557020
09-09 13:40:55.886  2569  2761 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-09 13:40:55.886  2569  2761 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,09-09 13:40:55.886  2569  2761 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-09 13:40:55.886  2569  2746 D BtGatt.AdvertiseManager: starting multi advertising
09-09 13:40:55.886  1259  1721 V AlarmManager:  remove PendingIntent] PendingIntent{efed5cf: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:55.886  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 38 : bytes_written: 38
,09-09 13:40:55.886  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-09 13:40:55.886  2569  2739 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
09-09 13:40:55.886  2569  2746 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-09 13:40:55.886  2569  2746 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-09 13:40:55.886  2569  2746 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
09-09 13:40:55.886  2569  2746 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
09-09 13:40:55.886  5955  5965 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
09-09 13:40:55.886  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-09 13:40:55.886  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:40:55.886  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-09 13:40:55.886  1259  2008 V AlarmManager:  remove PendingIntent] PendingIntent{4c04b5c: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:40:55.886  5955  6005 I io.jxcore.node.ConnectionHelper: start: OK
09-09 13:40:55.886  5955  5955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:40:55.886  5955  5955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-09 13:40:55.886  5955  5955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-09 13:40:55.886  5955  5955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 13:40:55.886  5955  5955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-09 13:40:55.886  5955  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:40:55.886  5955  5955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:40:55.886  1259  2294 V AlarmManager:  remove PendingIntent] PendingIntent{1fe4e65: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:55.886  5955  5955 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:40:55.896  1259  2621 V AlarmManager:  remove PendingIntent] PendingIntent{c48573a: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:40:55.896  1259  2008 V AlarmManager:  remove PendingIntent] PendingIntent{63cffeb: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:40:56.386  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:40:56.386  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:40:56.386  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:40:56.386  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:40:56.386  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 13:40:56.386  5955  6005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:40:56.386  5955  6005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56eaf36 not in the list
09-09 13:40:56.386  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:40:56.386  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:40:56.386  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:40:56.386  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:40:56.386  5955  6026 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:40:56.386  5955  6026 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:40:56.386  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:40:56.386  5955  6026 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:40:56.386  5955  5955 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-09 13:40:56.386  5955  5955 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:40:56.386  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:56.396  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:40:56.396  5955  6005 D BluetoothLeScanner: could not find callback wrapper
09-09 13:40:56.396  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:40:56.396  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-09 13:40:56.396  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:56.396  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:40:56.396  5955  6005 D BluetoothLeAdvertiser: stop advertising
,09-09 13:40:56.396  2569  2585 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-09 13:40:56.396  2569  2585 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-09 13:40:56.396  2569  2761 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
09-09 13:40:56.396  2569  2761 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
09-09 13:40:56.396  2569  2761 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-09 13:40:56.396  2569  2761 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-09 13:40:56.396  2569  2761 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
09-09 13:40:56.396  2569  2746 D BtGatt.AdvertiseManager: message : 1
,09-09 13:40:56.396  2569  2746 D BtGatt.AdvertiseManager: stop advertise for client =  6
09-09 13:40:56.396  2569  2746 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
,09-09 13:40:56.406  2569  2746 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
09-09 13:40:56.406  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
,09-09 13:40:56.406  1259  2008 V AlarmManager:  remove PendingIntent] PendingIntent{8b4c148: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:40:56.406  2970  2970 I WCNSS_FILTER: do_write: IBS write: fc
09-09 13:40:56.406  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-09 13:40:56.406  2970  2971 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-09 13:40:56.406  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
09-09 13:40:56.406  2569  2739 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-09 13:40:56.406  2569  2739 D BtGatt.GattService: Client app is not null!
,09-09 13:40:56.406  5955  5966 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
09-09 13:40:56.406  2569  3151 D BtGatt.GattService: unregisterClient() - clientIf=6
09-09 13:40:56.406  1259  1325 V AlarmManager:  remove PendingIntent] PendingIntent{d8a6be1: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:56.406  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 13:40:56.406  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:40:56.406  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-09 13:40:56.406  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-09 13:40:56.406  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-09 13:40:56.416  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:40:56.416  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:40:56.416  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:40:56.416  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:40:56.416  1259  2008 V AlarmManager:  remove PendingIntent] PendingIntent{1d4ad06: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}},
09-09 13:40:56.416  5955  6005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3473e37 not in the list
,09-09 13:40:56.416  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:40:56.416  5955  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:40:56.416  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:56.416  5955  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:40:56.416  5955  5955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:40:56.416  5955  5955 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:40:56.416  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:40:56.416  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:56.416  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:56.416  5955  6005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56eaf36 not in the list
,09-09 13:40:56.416  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:40:56.416  5955  6005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3473e37 not in the list
09-09 13:40:56.416  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:40:56.416  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:40:56.416  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:56.416  5955  6005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:40:56.416  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:40:56.426  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
09-09 13:40:56.426  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
,09-09 13:40:56.426  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:40:56.426  1259  2294 V AlarmManager:  remove PendingIntent] PendingIntent{ce9afc7: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:56.426  5955  6005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:40:56.426  5955  6005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:40:56.426  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:40:56.426  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:40:56.426  5955  5955 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:40:56.426  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:40:56.426  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:40:56.426  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:40:56.426  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:40:56.426  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:56.426  5955  6005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:40:56.426  5955  6030 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:40:56.426  5955  6005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56eaf36 not in the list
09-09 13:40:56.426  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:40:56.426  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:40:56.426  5955  6030 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:40:56.426  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 13:40:56.426  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:40:56.426  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:56.426  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:56.426  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-09 13:40:56.426  5955  5955 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:40:56.426  5955  5955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:40:56.426  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:40:56.426  5955  6005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3473e37 not in the list
09-09 13:40:56.426  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:40:56.426  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:56.426  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:40:56.426  5955  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:40:56.426  5955  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:40:56.426  5955  5955 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:40:56.426  5955  6005 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-09 13:40:56.426  5955  6005 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 13:40:56.426  1259  1637 V AlarmManager:  remove PendingIntent] PendingIntent{df8a9f4: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:40:56.426  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:40:56.426  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:40:56.426  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 13:40:56.426  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:40:56.426  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:56.426  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:56.426  5955  6005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56eaf36 not in the list
09-09 13:40:56.426  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:40:56.426  5955  6005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3473e37 not in the list
09-09 13:40:56.426  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:40:56.426  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:56.426  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:40:56.436  1259  2629 V AlarmManager:  remove PendingIntent] PendingIntent{d60e51d: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:40:56.436  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:40:56.436  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:56.436  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:56.436  5955  6005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56eaf36 not in the list
09-09 13:40:56.436  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:40:56.436  5955  6005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3473e37 not in the list
09-09 13:40:56.436  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:40:56.436  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:56.436  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:56.436  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:40:56.436  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:56.436  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:40:56.436  5955  6005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56eaf36 not in the list
09-09 13:40:56.436  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:40:56.436  5955  6005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3473e37 not in the list
09-09 13:40:56.436  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:40:56.436  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:56.436  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:40:56.436  5955  6005 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-09 13:40:56.436  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:40:56.436  5955  6005 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-09 13:40:56.436  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:40:56.436  5955  6005 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-09 13:40:56.436  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:40:56.436  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 13:40:56.436  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-09 13:40:56.436  5955  6005 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-09 13:40:56.436  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-09 13:40:56.436  5955  6005 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-09 13:40:56.446  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 13:40:56.446  5955  6005 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-09 13:40:56.446  5955  6005 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-09 13:40:56.446  5955  6005 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-09 13:40:56.446  5955  6005 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-09 13:40:56.446  5955  6005 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 13:40:56.446  5955  6005 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-09 13:40:56.446  5955  6005 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-09 13:40:56.446  5955  6005 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-09 13:40:56.446  5955  6005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:40:56.446  5955  6005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0509d4 added. We now have 3 listener(s)
,09-09 13:40:56.446  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-09 13:40:56.446  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 13:40:56.446  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:40:56.446  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:40:56.446  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21bf77d added. We now have 3 listener(s)
09-09 13:40:56.446  5955  6005 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:40:56.446  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:40:56.456  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:40:56.456  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:56.456  5955  6005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:40:56.456  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:40:56.456  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:40:56.456  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:40:56.456  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:40:56.456  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:40:56.456  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:40:56.456  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:40:56.466  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:56.466  5955  6005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:40:56.466  5955  6005 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:40:56.466  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:56.466  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:40:56.466  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:40:56.466  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:56.466  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:40:56.466  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:40:56.466  5955  6005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0509d4 removed from the list
09-09 13:40:56.466  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:40:56.466  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21bf77d removed from the list
,09-09 13:40:56.466  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:40:56.466  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:40:56.466  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:40:56.476  5955  6005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:40:56.476  5955  6005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b4fcac3 added. We now have 3 listener(s)
,09-09 13:40:56.476  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-09 13:40:56.476  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 13:40:56.476  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:40:56.476  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:40:56.476  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@692ef40 added. We now have 3 listener(s)
09-09 13:40:56.476  5955  6005 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:40:56.476  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:40:56.476  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:40:56.486  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:56.486  5955  6005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:40:56.486  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:40:56.486  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:40:56.486  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:40:56.486  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:40:56.486  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:40:56.486  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:40:56.486  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:40:56.486  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:56.486  5955  6005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:40:56.486  5955  6005 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:40:56.496  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:40:56.496  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:40:56.496  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:40:56.496  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:40:56.496  5955  6005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b4fcac3 removed from the list
09-09 13:40:56.496  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:40:56.496  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@692ef40 removed from the list
,09-09 13:40:56.496  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:40:56.496  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:40:56.496  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:40:56.496  5955  6005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:40:56.496  5955  6005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8cb7be added. We now have 3 listener(s)
,09-09 13:40:56.496  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:EB:95:EE"
,09-09 13:40:56.496  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:40:56.496  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:40:56.496  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:40:56.496  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6da501f added. We now have 3 listener(s)
09-09 13:40:56.496  5955  6005 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:40:56.496  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:40:56.496  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:40:56.506  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:40:56.506  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:56.506  5955  6005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:40:56.506  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:40:56.506  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:40:56.506  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:40:56.506  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:40:56.506  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:40:56.506  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:40:56.506  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:40:56.516  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:40:56.516  5955  6005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:40:56.516  5955  6005 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:40:56.516  1259  1989 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
09-09 13:40:56.516  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:40:56.516  1259  1989 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,09-09 13:40:56.526  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:40:56.526  1259  1989 D WifiService: setWifiEnabled: false pid=5955, uid=10136
09-09 13:40:56.526  1259  1989 D SettingsProvider: isChangeAllowed() : name = wifi_on
,09-09 13:40:56.526  1259  1624 D WifiController: [FCC]setFccChannel() is called !!!
,09-09 13:40:56.526  1259  1624 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
09-09 13:40:56.526  1259  1624 D WifiStateMachine: setFccChannel: channel = 0
,09-09 13:40:56.526  1259  1623 D WifiBigDataLog: getJsonFormat() - feature : ONOF
09-09 13:40:56.526  1259  1624 D WifiController: MHS off and WIFI tunred off and move to mApStaDisabledState
,09-09 13:40:56.526  1259  1623 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.android.server.wifi.WifiStateMachine.insertLog:18843 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8707 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,09-09 13:40:56.526  1259  1624 D SecContentProvider: insert(), uri = 2
09-09 13:40:56.526  1259  2124 E OsAgent :  Wifi Scan Always Available: 0
09-09 13:40:56.526  1259  2124 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-09 13:40:56.526  1259  2124 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: IS_WIFI_HARDWARE_ON: false
09-09 13:40:56.526  1259  1623 D WifiBigDataLog: init : 
09-09 13:40:56.526  1259  2124 E OsAgent :  Wifi Scan Always Available: 0
09-09 13:40:56.526  1259  2124 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-09 13:40:56.526  1259  2124 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: IS_WIFI_HARDWARE_ON: false
,09-09 13:40:56.526  1259  2124 E OsAgent :  Wifi Scan Always Available: 0
09-09 13:40:56.526  1259  2124 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-09 13:40:56.526  1259  2124 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: IS_WIFI_HARDWARE_ON: false
09-09 13:40:56.526  1259  2149 E LocSvc_libulp: I/int ulp_msg_process_phone_setting_update(const UlpPhoneContextSettings*), context type: 0x4
09-09 13:40:56.526  1259  2149 E LocSvc_libulp:   gps enabled: 0
09-09 13:40:56.526  1259  2149 E LocSvc_libulp:  network position available 0
09-09 13:40:56.526  1259  2149 E LocSvc_libulp:  wifi setting enabled 0
09-09 13:40:56.526  1259  2149 E LocSvc_libulp:  battery charging 0, agps enabled 0, enh_location_services_enabled 0is_pip_user_setting_enabled 0
09-09 13:40:56.526  1259  2149 E LocSvc_libulp: I/int ulp_msg_process_system_update(UlpSystemEvent): systemEvent:4 
09-09 13:40:56.526  1259  2149 E LocSvc_libulp: I/int ulp_msg_process_start_req(), at ulp state = 1
,09-09 13:40:56.536  1259  2129 E LocSvc_LBSApiV02: E/virtual int lbs_core::LBSApiV02::wifiEnabledStatusInject(int):677]: Error : st = 2, ind.status = 1588437952
09-09 13:40:56.536  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1b9db u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1f7ee83 2608:com.samsung.android.providers.context/u0a5}
,09-09 13:40:56.536  1259  1623 D WifiStateMachine: setFccChannelNative: channel = 0
09-09 13:40:56.536  1259  1623 D WifiNative-wlan0: callSECApiInt - ID [230]
,09-09 13:40:56.546  1259  1623 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-09 13:40:56.546  1259  1623 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:40:56.546  1259  1623 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:40:56.546  1259  1623 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,09-09 13:40:56.546  1259  1623 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:40:56.546  1259  1623 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:40:56.546  1259  1623 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:40:56.546  1259  1623 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:40:56.546  1259  1623 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,09-09 13:40:56.546  1694  2072 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-09 13:40:56.546  1259  1623 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:40:56.546  1259  1623 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:40:56.546  1259  1623 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 13:40:56.546  1259  1623 E WifiNative-wlan0: do suspend true
09-09 13:40:56.546  1694  2072 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,09-09 13:40:56.546  1694  2072 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-09 13:40:56.546  1694  2072 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,09-09 13:40:56.546  1259  1622 D WifiP2pService: InactiveState{ what=143375 }
,09-09 13:40:56.556   552  1413 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:40:56.556  1259  1622 D WifiP2pService: P2pEnabledState{ what=143375 }
09-09 13:40:56.556  1259  3167 V AlarmManager:  remove PendingIntent] PendingIntent{ca863b6: PendingIntentRecord{bab6ac2 android broadcastIntent}}
09-09 13:40:56.556   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 80
09-09 13:40:56.556   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
,09-09 13:40:56.556   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:40:56.556   746  1442 I QC-NETMGR-LIB: Processing RTM_DELADDR
09-09 13:40:56.556   746  1442 I QC-NETMGR-LIB: Metainfo:  Family=2 PrefixLen=24 Scope=0x0 Index=13 Flags=[0x80]PERMANENT 
09-09 13:40:56.556   746  1442 I QC-NETMGR-LIB: Attribute: PrefixIPv4 addr [192.168.1.106]
09-09 13:40:56.556   746  1442 I QC-NETMGR-LIB: Attribute: LocalIPv4 addr [192.168.1.106]
09-09 13:40:56.556   746  1442 I QC-NETMGR-LIB: Attribute: BroadcastIPv4 addr [192.168.1.255]
09-09 13:40:56.556   746  1442 I QC-NETMGR-LIB: Attribute: Label name wlan0
09-09 13:40:56.556   746  1442 I QC-NETMGR-LIB: Attribute: Address Cache Info - prefered=-1 valid=-1 cstamp=0x968 tstamp=0x968
09-09 13:40:56.556   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [21]
09-09 13:40:56.556   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 13
,09-09 13:40:56.556  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-09 13:40:56.556  1868  4476 V NativeCrypto: Read error: ssl=0x7f83193d00: I/O error during system call, Connection timed out
,09-09 13:40:56.556  1868  4476 V NativeCrypto: SSL shutdown failed: ssl=0x7f83193d00: I/O error during system call, Broken pipe
09-09 13:40:56.566  1259  1324 V AlarmManager:  remove PendingIntent] PendingIntent{6d818b7: PendingIntentRecord{1a062e8 com.google.android.gms broadcastIntent}}
,09-09 13:40:56.566  1868  4476 E GCM     : Wifi connection closed with errorCode 20
09-09 13:40:56.566   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 64
09-09 13:40:56.566   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:40:56.566   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:40:56.566   746  1442 I QC-NETMGR-LIB: Processing RTM_DELADDR
09-09 13:40:56.566   746  1442 I QC-NETMGR-LIB: Metainfo:  Family=10 PrefixLen=64 Scope=0xfd Index=13 Flags=[0x80]PERMANENT 
09-09 13:40:56.566   746  1442 I QC-NETMGR-LIB: Attribute: PrefixIPv6 addr [fe80:0000:0000:0000:4678:3eff:feeb:95ef]
09-09 13:40:56.566   746  1442 I QC-NETMGR-LIB: Attribute: Address Cache Info - prefered=-1 valid=-1 cstamp=0x935 tstamp=0x935
09-09 13:40:56.566   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [21]
09-09 13:40:56.566   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 13
,09-09 13:40:56.566  1259  3166 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: ValidatedState{ when=0 what=532488 arg1=10010 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:40:56.566  1259  2304 D ConnectivityService: reportNetworkConnectivity(502, false) by 10010
09-09 13:40:56.566  1259  3166 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: DefaultState{ when=0 what=532488 arg1=10010 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:40:56.566  1259  1630 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-09 13:40:56.566  1259  3166 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: Forcing reevaluation for UID 10010
09-09 13:40:56.566  1259  1630 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] validation  passed
09-09 13:40:56.566  1259  3166 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:40:56.566  1259  3166 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: Validated
09-09 13:40:56.566  1259  1630 D ConnectivityService: EVENT_PROVISIONING_NOTIFICATION is sent for TYPE_MOBILE.
,09-09 13:40:56.576  1259  1630 E ConnectivityService: updateNetworkInfo()
09-09 13:40:56.576  1259  1630 E ConnectivityService: updateNetworkInfo()
09-09 13:40:56.576  1259  1630 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]
09-09 13:40:56.576  1259  1630 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
09-09 13:40:56.576  1259  1630 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 4
09-09 13:40:56.576  1259  1630 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:40:56.576  1259  1630 V NetworkStats: updateIfacesLocked()
09-09 13:40:56.576  1259  1630 V NetworkStats: performPollLocked(flags=0x1)
,09-09 13:40:56.576  1259  1259 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-09 13:40:56.576  1259  1259 I Wifi-SensorMonitor: enable sensor monitoring : false
09-09 13:40:56.576  1259  1259 D SensorHAL: GRIP_WIFI  set_enable 
,09-09 13:40:56.576  1259  1259 D SensorHAL: sx9310_grip_wifi: power-off.
09-09 13:40:56.576  1259  1259 E Sensors : ~SensorEventQueue 0
09-09 13:40:56.576  1259  1259 E         : BitTube(): close sendFd (361)
09-09 13:40:56.576  1259  1259 E         : BitTube(): close receivedFd (331)
09-09 13:40:56.576  1259  1259 D SensorManager: unregisterListener ::   
09-09 13:40:56.576  1259  1259 D WifiNative-wlan0: callSECApiInt - ID [70]
09-09 13:40:56.586  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:40:56.586  1259  1259 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
09-09 13:40:56.586  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:40:56.586  1259  1259 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.586  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:40:56.586  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:40:56.586  1259  1630 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:40:56.586  1259  1630 V NetworkStats: performPollLocked() took 9ms
09-09 13:40:56.586  1259  1259 D HS20StateMachine: checkifOSUAP  null disconnectedFromSsid"NG700"
09-09 13:40:56.586  1259  1259 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
09-09 13:40:56.586  1259  1628 I WifiHs20Service: Message received 5007
,09-09 13:40:56.586  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-09 13:40:56.586  1974  1974 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,09-09 13:40:56.586  1259  1622 D WifiP2pService: InactiveState{ what=131204 }
09-09 13:40:56.586  1259  1622 D WifiP2pService: P2pEnabledState{ what=131204 }
09-09 13:40:56.586  2389  2389 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
09-09 13:40:56.586  2389  2389 I wpa_supplicant: P2P: Clear a pre-passphrase (State NONE)
09-09 13:40:56.586  1259  1623 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(VALID)
09-09 13:40:56.586  1259  1623 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(1)
09-09 13:40:56.586  1259  1623 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:40:56.586  1259  1623 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:40:56.586  1259  1623 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
09-09 13:40:56.586  1259  1622 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-09 13:40:56.586  1259  1630 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:40:56.586  1259  1259 D RttService: SCAN_AVAILABLE : 1
09-09 13:40:56.586  1259  1630 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]
09-09 13:40:56.586  1259  1650 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:40:56.596  1259  1630 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
09-09 13:40:56.596  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:40:56.596  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:40:56.596  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:40:56.596  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 13:40:56.596  1259  1259 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
09-09 13:40:56.596  1259  1259 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
09-09 13:40:56.596  1259  1630 D ConnectivityService: sending notification LOST for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 13:40:56.596  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
,09-09 13:40:56.596  1259  1630 D ConnectivityService: sending notification LOST for NetworkRequest [ id=5, legacyType=-1, [] ]
,09-09 13:40:56.596  1259  1416 D EntConnectivity: Not allowed due to - mEnabled false
09-09 13:40:56.596  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 13:40:56.596  1259  2294 D ConnectivityService: getVpnConfig > userId : 0
09-09 13:40:56.596  1259  1630 D ConnectivityService: sending notification LOST for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 13:40:56.596  1259  3166 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:40:56.596  1259  1630 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:40:56.596  1259  1651 D Ethernet: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:40:56.596  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6147824 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8c16b67 5671:com.enhance.gameservice/u0a79}
09-09 13:40:56.596  1259  1651 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
09-09 13:40:56.596  1259  1651 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 13:40:56.596  1259  1651 D Ethernet: evalRequest
09-09 13:40:56.596  1259  1651 D Ethernet:   done
09-09 13:40:56.596  1694  2108 D QSTile.WifiTile: handleUpdateState  cb.changed 14 wifiEnabled : ON 
,09-09 13:40:56.606  1259  1623 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:40:56.606  1259  1622 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-09 13:40:56.606  1259  1623 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:40:56.606  1259  1622 D WifiP2pService: P2pDisablingState
09-09 13:40:56.606  1259  1623 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 13:40:56.606  1259  1637 V AlarmManager:  remove PendingIntent] PendingIntent{32a4f8d: PendingIntentRecord{f644eec com.google.android.gms broadcastIntent}}
09-09 13:40:56.606  1259  1622 D SecContentProvider: insert(), uri = 2,
09-09 13:40:56.606  1259  1622 D WifiP2pService: P2pDisablingState{ what=147458 }
09-09 13:40:56.606  1259  1623 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:40:56.606  1259  1622 D WifiP2pService: p2p socket connection lost
09-09 13:40:56.606  1259  1623 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:40:56.606  1259  1417 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-09 13:40:56.606  1259  1623 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 13:40:56.606  1259  1417 I WifiDisplayAdapter: onP2pDisconnected
09-09 13:40:56.606  1259  1623 D WIFI    : evalRequest
09-09 13:40:56.606  1259  1417 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 13:40:56.606  1259  1623 D WIFI    :   done
09-09 13:40:56.606  1259  1417 D IpRemoteDisplayController: WfdBridgeServer is already null
09-09 13:40:56.606  1259  1623 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:40:56.606  1694  1694 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 148
09-09 13:40:56.606  1259  1622 D WIFI_P2P: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:40:56.606  1259  1622 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:40:56.606  1259  1622 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 13:40:56.616  1259  1622 D WifiP2pService: P2pDisabledState
09-09 13:40:56.606  1259  1622 D WIFI_P2P: evalRequest
09-09 13:40:56.606  1259  1622 D WIFI_P2P:   done
09-09 13:40:56.606  1259  1622 D SecContentProvider: insert(), uri = 2
09-09 13:40:56.606  1259  1623 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:40:56.606  1259  1623 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 13:40:56.606  1259  1623 D WIFI    : evalRequest
09-09 13:40:56.606  1259  1623 D WIFI    :   done
09-09 13:40:56.606  1259  1623 D WIFI_UT : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:40:56.606  1259  1623 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:40:56.606  1259  1623 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 13:40:56.606  1259  1623 D WIFI_UT : evalRequest
09-09 13:40:56.606  1259  1623 D WIFI_UT :   done
09-09 13:40:56.616  1259  1259 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-09 13:40:56.616  1259  1623 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 13:40:56.616  1259  1623 E WifiNative-wlan0: do suspend true
09-09 13:40:56.616  1259  1417 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-09 13:40:56.616  1259  1417 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
09-09 13:40:56.616  1259  1417 D WifiDisplayController: disconnect
09-09 13:40:56.616  1259  1417 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 13:40:56.616  1694  2072 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-09 13:40:56.616  1259  1622 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-09 13:40:56.616  1259  1622 D WifiP2pService: DefaultState{ what=143375 }
,09-09 13:40:56.616  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{14f0542 u0 com.google.android.gcm.DISCONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9ff3cb0 5496:com.google.android.talk/u0a84}
,09-09 13:40:56.616  1694  2072 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,09-09 13:40:56.626  1259  1385 I ActivityManager: Start proc 6035:com.sec.android.diagmonagent/1000 for broadcast-5 com.sec.android.diagmonagent/.DiagMonConnectivityChangeReciever
,09-09 13:40:56.626  1694  1694 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-09 13:40:56.636  6035  6035 E Zygote  : v2
09-09 13:40:56.636  6035  6035 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:40:56.636  6035  6035 I libpersona: KNOX_SDCARD not a persona
,09-09 13:40:56.636  6035  6035 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-09 13:40:56.636  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-09 13:40:56.636  6035  6035 E Zygote  : accessInfo : 0
,09-09 13:40:56.636  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e32f290 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dcd9326 5659:com.samsung.android.app.FileShareServer/5005}
,09-09 13:40:56.636  5659  5659 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
09-09 13:40:56.646  5659  5659 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,09-09 13:40:56.646  5659  5659 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,09-09 13:40:56.646   445   445 I rmt_storage: rmt_storage_connect_cb: clnt_h=0xa conn_h=0x7f7bb7a000
09-09 13:40:56.646   445   445 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x7: req_h=0xa msg_id=3: R/W request received
09-09 13:40:56.646   445   445 I rmt_storage: wakelock acquired: 1, error no: 42
09-09 13:40:56.646   445   902 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x7 Unblock worker thread (th_id: 547531260992)
,09-09 13:40:56.646   552  1413 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 13:40:56.646  1694  1694 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-09 13:40:56.646  1694  1694 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-09 13:40:56.646  1694  1694 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-09 13:40:56.646  1694  1694 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-09 13:40:56.646  1259  2629 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 13:40:56.676   552  1413 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-09 13:40:56.676  1259  1630 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,fe80::4678:3eff:feeb:95ef/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } wasDefault=true
09-09 13:40:56.676   552  1413 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:40:56.676  1259  1630 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
09-09 13:40:56.676  1259  1630 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:40:56.686  1259  1416 D EntConnectivity: Not allowed due to - mEnabled false
09-09 13:40:56.686  1259  1259 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.686  6035  6035 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:40:56.686  6035  6035 D ActivityThread: Added TimaKeyStore provider
09-09 13:40:56.686  1259  1874 V AlarmManager:  remove PendingIntent] PendingIntent{39adc39: PendingIntentRecord{51f527e android broadcastIntent}}
09-09 13:40:56.686  1259  1416 D Tethering: MasterInitialState.processMessage what=3
09-09 13:40:56.686  1259  1631 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
09-09 13:40:56.686  1974  2707 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
09-09 13:40:56.686  1974  2707 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-09 13:40:56.686  1259  1631 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,09-09 13:40:56.686  1259  6050 I ApplicationPolicy: updateDataUsageMap
09-09 13:40:56.686  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-09 13:40:56.686  1259  1378 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:40:56.686  1259  1378 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.686  1259  1378 D GpsLocationProvider: handleMessage msg = 4
09-09 13:40:56.686  1259  1259 D LocSvc_java: onReceive
09-09 13:40:56.686  1259  1259 D LocSvc_java: got connectivity action
09-09 13:40:56.686  1259  1259 D LocSvc_java: broadcast - no network connections
09-09 13:40:56.686  1259  1259 D LocSvc_java: Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
09-09 13:40:56.686  1259  1259 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 13:40:56.686  1259  1259 D LocSvc_java: handleMessage msg = 4
09-09 13:40:56.686  1259  1259 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 13:40:56.686  1259  1259 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true] info.getType():1
,09-09 13:40:56.696   445   902 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x7: req_h=0xa msg_id=3: Bytes written = 1572864
09-09 13:40:56.696   445   902 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x7: req_h=0xa msg_id=3: Send response: res=0 err=0
09-09 13:40:56.696   445   902 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x7 About to block rmt_storage client thread (th_id: 547531260992) wakelock released: 1, error no: 0
09-09 13:40:56.696   445   902 I rmt_storage: 
09-09 13:40:56.696  1259  1259 V MARsPolicyManager: DataConnection: false
,09-09 13:40:56.696   445   445 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0xa conn_h=0x7f7bb7a000
09-09 13:40:56.696  1259  1621 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:40:56.696  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:40:56.696  1259  1621 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-09 13:40:56.696  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:40:56.696  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:40:56.696  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:40:56.696  3109  3109 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@3390fb1 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-09 13:40:56.696  1974  5601 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,09-09 13:40:56.696  5030  5048 I SystemBroadcastReceiver: [#CMH#] Received broadcast 
09-09 13:40:56.696  5030  5048 I SystemBroadcastReceiver: [#CMH#] No one is registered with Event Id EVENT_NETWORK_CHANGED
09-09 13:40:56.696  5030  5048 I SystemBroadcastReceiver: [#CMH#] onReceive completed 
09-09 13:40:56.706  1259  2008 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.706  1259  2008 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.706  1259  2008 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.706  1259  2008 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.706  1259  2008 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.706  1259  2008 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.706  1259  2008 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.706  1259  2008 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.706  1259  2008 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.706  1259  2008 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.706  1259  2008 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.706  1259  2008 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.706  1259  2008 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.706  1259  2008 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.706  1259  2008 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none,), roaming: false, failover: false, isAvailable: true]
,09-09 13:40:56.706  5955  5955 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-09 13:40:56.706  1259  1623 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-09 13:40:56.706  5955  5955 D BluetoothAdapter: STATE_ON
09-09 13:40:56.716  1974  5601 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,09-09 13:40:56.716  1259  1378 D TelephonyManager: getDataEnabled: retVal=true
,09-09 13:40:56.716  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:40:56.716  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:40:56.716  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:40:56.716  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:40:56.716  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:40:56.716  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:40:56.716  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:40:56.716  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:40:56.716  1259  1853 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{6147824 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{54b8953 6035:com.sec.android.diagmonagent/1000}
09-09 13:40:56.716  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-09 13:40:56.726  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.726  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.726  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.726  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.726  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.726  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.726  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.726  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.726  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.726  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.726  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.726  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.726  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.726  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-09 13:40:56.726  5955  5955 D BluetoothAdapter: STATE_ON
,09-09 13:40:56.726  1259  1259 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-09 13:40:56.726  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:40:56.726  1259  1259 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
09-09 13:40:56.726  1259  1259 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false]
,09-09 13:40:56.726  1259  1259 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
09-09 13:40:56.726  1259  1628 I WifiHs20Service: Message received 5007
,09-09 13:40:56.736  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-09 13:40:56.736  1974  1974 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,09-09 13:40:56.736  1974  1988 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@e9f0fdf, selection=nullselectionArgs=null, sort=name ASC
09-09 13:40:56.736  5955  5955 D BluetoothAdapter: STATE_ON
,09-09 13:40:56.736  1259  1259 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:40:56.736  1259  1259 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
09-09 13:40:56.736  1259  1628 I WifiHs20Service: Message received 5011
,09-09 13:40:56.746  1259  1631 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
09-09 13:40:56.746  1694  1694 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:40:56.746  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:40:56.746  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:40:56.746  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:40:56.746  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:40:56.746  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:40:56.746  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:40:56.746  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:40:56.746  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:40:56.746  1694  1694 D HotspotTile: onReceive : 0, 0
09-09 13:40:56.746  1974  1985 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,09-09 13:40:56.746  5955  5955 D BluetoothAdapter: STATE_ON
,09-09 13:40:56.746  1974  1985 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-09 13:40:56.746  1259  1631 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,09-09 13:40:56.746  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:40:56.746  1259  1259 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
09-09 13:40:56.746  1259  1259 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
09-09 13:40:56.746  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-09 13:40:56.756  1694  2108 D QSTile.WifiTile: handleUpdateState  cb.changed 5 wifiEnabled : OFF 
,09-09 13:40:56.756  6035  6035 W System  : ClassLoader referenced unknown path: /system/priv-app/DiagMonAgent/lib/arm64
09-09 13:40:56.756  1694  1694 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 148
,09-09 13:40:56.756  5955  5955 D BluetoothAdapter: STATE_ON
,09-09 13:40:56.756  1974  1988 D TelephonyProvider: query: match = 5
,09-09 13:40:56.756  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:40:56.756  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:40:56.756  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:40:56.756  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:40:56.756  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:40:56.756  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:40:56.756  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:40:56.756  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:40:56.756  1974  1988 D TelephonyProvider: getPreferredApnId(subId = 2147483643),return -1
,09-09 13:40:56.756   552  1413 E Netd    : netlink response contains error (No such file or directory)
09-09 13:40:56.756  1259  1623 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
09-09 13:40:56.756  1259  1630 D ConnectivityService: setProvNotificationVisibleIntent SIGN_IN visible=false networkType=WIFI extraInfo=null highPriority=false
09-09 13:40:56.756  1259  1630 D ConnectivityService: nai.networkMonitor.doQuit()
09-09 13:40:56.756  1259  1630 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: doQuit - quitNow()
09-09 13:40:56.766  1259  1630 E ConnectivityService: updateNetworkInfo()
09-09 13:40:56.766  1259  1630 E ConnectivityService: updateNetworkInfo()
09-09 13:40:56.766  1259  1630 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:40:56.766  1259  1630 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
09-09 13:40:56.766  1974  1988 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
,09-09 13:40:56.766  5955  5955 D BluetoothAdapter: STATE_ON
,09-09 13:40:56.776  1259  1378 E GpsLocationProvider: No APN found to select.
09-09 13:40:56.776  1259  2124 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-09 13:40:56.776  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:40:56.776  2236  6055 D MdnsClient: Multicast lock held. Releasing
09-09 13:40:56.776  1259  2124 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 0, Mac address valid: false, AP MAC address: [00:00:00:00:00:00], Wifi-Ap SSID Valid: false, SSID: 
,09-09 13:40:56.776  1259  2136 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 131 QMI_LOC_NOTIFY_WIFI_ATTACHMENT_STATUS_REQ_V02
,09-09 13:40:56.776  5955  5955 D BluetoothAdapter: STATE_ON
,09-09 13:40:56.776  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:40:56.776  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:40:56.776  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:40:56.776  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:40:56.776  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:40:56.776  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:40:56.776  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:40:56.776  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:40:56.786  5955  5955 D BluetoothAdapter: STATE_ON
,09-09 13:40:56.786  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:40:56.786  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:40:56.786  6035  6035 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-09 13:40:56.786  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:40:56.806  2236  6054 D UdcContextInitService: registered all accounts: true
,09-09 13:40:56.806  1259  1987 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d7ca7bc u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a8d25ef 1259:system/1000}
,09-09 13:40:56.816  1259  1259 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d7ca7bc u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3be25b9 2236:com.google.android.gms/u0a10}
,09-09 13:40:56.816  2236  2236 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 13:40:56.816  2236  3189 I iu.UploadsManager: num queued entries: 0
,09-09 13:40:56.826  2236  3189 I iu.UploadsManager: num updated entries: 0
,09-09 13:40:56.826  2236  3189 I iu.SyncManager: NEXT; no task
,09-09 13:40:56.826  1259  2629 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d7ca7bc u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3be25b9 2236:com.google.android.gms/u0a10}
,09-09 13:40:56.826  1259  1721 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d7ca7bc u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fadd615 1868:com.google.android.gms.persistent/u0a10}
,09-09 13:40:56.836  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d7ca7bc u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5827062 5955:com.test.thalitest/u0a136}
09-09 13:40:56.846  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.846  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.846  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.846  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.846  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.846  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.846  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.846  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.846  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.846  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.846  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.846  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-09 13:40:56.846  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.846  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.846  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: fals,e, isAvailable: true]
,09-09 13:40:56.846  1259  1324 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d7ca7bc u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1ce268a 5214:com.wssyncmldm/1000}
,09-09 13:40:56.866  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{220cfcb u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{54b8953 6035:com.sec.android.diagmonagent/1000}
,09-09 13:40:56.866  6035  6035 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-09 13:40:56.866  6035  6035 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(72/onCreate)] DiagMon DM Application Start !
,09-09 13:40:56.866  6035  6035 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
09-09 13:40:56.866  6035  6035 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
09-09 13:40:56.866  6035  6035 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
09-09 13:40:56.866  6035  6035 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
09-09 13:40:56.866  6035  6035 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,09-09 13:40:56.866  6035  6035 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
09-09 13:40:56.866  6035  6035 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-09 13:40:56.886  2389  2389 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 13:40:56.886  2389  2389 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,09-09 13:40:56.886  6058  6058 E Zygote  : v2
09-09 13:40:56.886  6058  6058 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:40:56.886  6058  6058 I libpersona: KNOX_SDCARD not a persona
,09-09 13:40:56.886  6058  6058 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-09 13:40:56.886  1259  2310 I ActivityManager: Start proc 6058:com.sec.app.RilErrorNotifier/1000 for broadcast-5 com.sec.app.RilErrorNotifier/.PhoneErrorReceiver
09-09 13:40:56.886  6058  6058 E Zygote  : accessInfo : 0
,09-09 13:40:56.896  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{220cfcb u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8c16b67 5671:com.enhance.gameservice/u0a79}
,09-09 13:40:56.896  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1983254 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5827062 5955:com.test.thalitest/u0a136}
,09-09 13:40:56.906  1259  2320 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.906  1259  2320 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.906  1259  2320 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.906  1259  2320 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.906  1259  2320 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.906  1259  2320 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.906  1259  2320 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.906  1259  2320 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.906  1259  2320 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.906  1259  2320 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.906  1259  2320 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.906  1259  2320 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-09 13:40:56.906  1259  2320 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.906  1259  2320 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:56.906  1259  2320 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-09 13:40:56.916  6058  6058 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:40:56.916  6058  6058 D ActivityThread: Added TimaKeyStore provider
,09-09 13:40:56.916  1259  2310 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{6147824 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a6a9da7 6058:com.sec.app.RilErrorNotifier/1000}
,09-09 13:40:56.926  1868  6071 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 7067 seconds from now (1473421256935)
,09-09 13:40:56.926  5955  5955 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:40:56.936  6058  6058 W System  : ClassLoader referenced unknown path: /system/priv-app/PhoneErrService/lib/arm64
09-09 13:40:56.936   552  1406 D Netd    : Iface p2p0 link down
09-09 13:40:56.936  2389  2389 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-09 13:40:56.936   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-09 13:40:56.936   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:40:56.936   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:40:56.936   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:40:56.936   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=14 Family=0 Type=0x1 Change=[0x1]UP  Flags=[0x1002]BROADCAST MULTICAST 
09-09 13:40:56.936   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:40:56.936   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:40:56.936   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 14, disable link
,09-09 13:40:56.936  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ab742f2 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fadd615 1868:com.google.android.gms.persistent/u0a10}
,09-09 13:40:56.936  6058  6058 I PhoneErrorReceiver: onReceive
09-09 13:40:56.936  6058  6058 I MIPErrReceiver: isWiFiConnected
,09-09 13:40:56.946  1259  2629 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-09 13:40:56.956  6074  6074 E Zygote  : v2
09-09 13:40:56.956  6074  6074 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:40:56.956  6074  6074 I libpersona: KNOX_SDCARD not a persona
,09-09 13:40:56.956  6074  6074 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-09 13:40:56.956  1259  2320 I ActivityManager: Start proc 6074:com.sec.knox.switcher/1000 for broadcast-5 com.sec.knox.switcher/.knoxusage.KnoxUsageReceiver
,09-09 13:40:56.956  6074  6074 E Zygote  : accessInfo : 0
,09-09 13:40:56.956  1259  2320 I ActivityManager: Killing 5316:com.sec.android.soagent/1000 (adj 15): DHA:empty #31
,09-09 13:40:56.986  6074  6074 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:40:56.986  6074  6074 D ActivityThread: Added TimaKeyStore provider
,09-09 13:40:56.996  1259  1989 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{6147824 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f996d43 6074:com.sec.knox.switcher/1000}
,09-09 13:40:56.996  1868  6057 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-09 13:40:57.006  1868  6057 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-09 13:40:57.006  6074  6074 W System  : ClassLoader referenced unknown path: /system/app/KnoxSwitcher/lib/arm64
,09-09 13:40:57.016  6074  6074 D KnoxUsageDB: getInstance - KnoxUsageDBHelper
09-09 13:40:57.016  6074  6074 D KnoxUsageDB: null == mDbHelperInstance - KnoxUsageDBHelper
,09-09 13:40:57.026  6074  6074 I usagelog: received in receiver
,09-09 13:40:57.026  6074  6074 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
09-09 13:40:57.026  1259  2304 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.soagent, Auto Run ON
09-09 13:40:57.026  1259  2304 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5316 ,hash=242870721 ,name=com.sec.android.soagent
,09-09 13:40:57.026  6074  6074 I KnoxUsageLogPro: premStatus:2
,09-09 13:40:57.026  6074  6074 I KnoxUsageLogPro: isEulaShown : false
09-09 13:40:57.026  6074  6074 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,09-09 13:40:57.026  5955  6005 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,09-09 13:40:57.026  1259  2294 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
09-09 13:40:57.036  1259  2294 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,09-09 13:40:57.036  1259  2294 D WifiService: System do NOT have com.sec.feature.sensorhub feature
09-09 13:40:57.036  1259  2294 D WifiService: Wi-Fi on and Screen on , checkSensorStatus !!
09-09 13:40:57.036  1259  2294 D WifiService: setWifiEnabled: true pid=5955, uid=10136
,09-09 13:40:57.036   552  1406 D Netd    : Iface wlan0 link down
,09-09 13:40:57.036   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-09 13:40:57.036   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:40:57.036   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:40:57.036   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:40:57.036   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=13 Family=0 Type=0x1 Change=[0x0] Flags=[0x1003]UP BROADCAST MULTICAST 
09-09 13:40:57.036   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:40:57.036   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:40:57.036   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 13, disable link
09-09 13:40:57.036   552  1406 D Netd    : Iface wlan0 link down
09-09 13:40:57.036   552  1406 D Netd    : Iface wlan0 link down
09-09 13:40:57.036  2389  2389 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 13:40:57.036  2389  2389 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-09 13:40:57.036   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 76
09-09 13:40:57.036   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:40:57.036  1259  1416 D Tethering: InitialState.processMessage what=4
09-09 13:40:57.036   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 72
09-09 13:40:57.036   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:40:57.036  1259  1416 D Tethering: NAP Supported and not Wifi Model
09-09 13:40:57.036   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:40:57.036   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:40:57.036   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=13 Family=0 Type=0x1 Change=[0x0] Flags=[0x1043]UP BROADCAST RUNNING MULTICAST 
09-09 13:40:57.036   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:40:57.036   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:40:57.036   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 13, disable link
09-09 13:40:57.036   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:40:57.036   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:40:57.036   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=13 Family=0 Type=0x1 Change=[0x0] Flags=[0x1043]UP BROADCAST RUNNING MULTICAST 
09-09 13:40:57.036   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:40:57.036   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:40:57.036   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 13, disable link
,09-09 13:40:57.036  1259  1416 E Tethering: No numeric data
,09-09 13:40:57.046  6088  6088 E Zygote  : v2
09-09 13:40:57.046  6088  6088 I libpersona: KNOX_SDCARD checking this for 5005
09-09 13:40:57.046  6088  6088 I libpersona: KNOX_SDCARD not a persona
09-09 13:40:57.046  1259  2310 I ActivityManager: Start proc 6088:com.samsung.android.app.FileShareClient/5005 for broadcast-5 com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver
09-09 13:40:57.046  6088  6088 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-09 13:40:57.046  6088  6088 E Zygote  : accessInfo : 0
09-09 13:40:57.046  1259  2310 I ActivityManager: Killing 5054:com.samsung.dcmservice/5004 (adj 15): DHA:empty #31
09-09 13:40:57.046  6088  6088 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareClient 
,09-09 13:40:57.046  1259  2294 W ActivityManager: Permission Denial: getCurrentUser() from pid=5955, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
09-09 13:40:57.046  1259  1416 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-09 13:40:57.046  1259  1623 D WifiBigDataLog: getJsonFormat() - feature : ONOF
09-09 13:40:57.046  1259  1623 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.android.server.wifi.WifiStateMachine.insertLog:18843 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8707 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,09-09 13:40:57.046  1259  2294 W WifiService: Failed getting userId using ActivityManagerNative
09-09 13:40:57.046  1259  2294 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5955, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
09-09 13:40:57.046  1259  2294 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28130)
09-09 13:40:57.046  1259  2294 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2542)
09-09 13:40:57.046  1259  2294 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2530)
09-09 13:40:57.046  1259  2294 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
09-09 13:40:57.046  1259  2294 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
09-09 13:40:57.046  1259  1620 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:40:57.046  1259  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:40:57.046  1259  2294 D SettingsProvider: isChangeAllowed() : name = wifi_on
09-09 13:40:57.056  1694  1694 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 13:40:57.056  1259  1624 D WifiController: [FCC]setFccChannel() is called !!!
09-09 13:40:57.056  1694  1694 D HotspotTile: updateTetherState():false, false
09-09 13:40:57.056  1259  1624 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
09-09 13:40:57.056  1259  2124 E OsAgent :  Wifi Scan Always Available: 0
09-09 13:40:57.056  1259  2124 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-09 13:40:57.056  1259  2124 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: IS_WIFI_HARDWARE_ON: true
09-09 13:40:57.056  1259  1624 D WifiStateMachine: setFccChannel: channel = 0
09-09 13:40:57.056  1259  2124 E OsAgent :  Wifi Scan Always Available: 0
09-09 13:40:57.056  1259  2124 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-09 13:40:57.056  1259  2124 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: IS_WIFI_HARDWARE_ON: true
09-09 13:40:57.056  1259  2149 E LocSvc_libulp: I/int ulp_msg_process_phone_setting_update(const UlpPhoneContextSettings*), context type: 0x4
09-09 13:40:57.056  1259  2149 E LocSvc_libulp:   gps enabled: 0
09-09 13:40:57.056  1259  2149 E LocSvc_libulp:  network position available 0
09-09 13:40:57.056  1259  2149 E LocSvc_libulp:  wifi setting enabled 1
09-09 13:40:57.056  1259  2149 E LocSvc_libulp:  battery charging 0, agps enabled 0, enh_location_services_enabled 0is_pip_user_setting_enabled 0
09-09 13:40:57.056  1259  1624 D SecContentProvider: insert(), uri = 2
09-09 13:40:57.056  1259  2149 E LocSvc_libulp: I/int ulp_msg_process_system_update(UlpSystemEvent): systemEvent:4 
09-09 13:40:57.056  1259  2124 E OsAgent :  Wifi Scan Always Available: 0
09-09 13:40:57.056  1259  2124 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-09 13:40:57.056  1259  2124 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: IS_WIFI_HARDWARE_ON: true
09-09 13:40:57.056  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:40:57.056  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:40:57.056  1259  2129 E LocSvc_LBSApiV02: E/virtual int lbs_core::LBSApiV02::wifiEnabledStatusInject(int):677]: Error : st = 2, ind.status = 1588437952
09-09 13:40:57.056  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:40:57.056  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:40:57.056  1259  1620 V NetworkStats: performPollLocked() took 5ms
09-09 13:40:57.056  1259  1620 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:40:57.056  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4729c3e u-1 android.net.conn.TETHER_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a8d25ef 1259:system/1000}
,09-09 13:40:57.056  5030  5030 I ServiceManager: [#CMH#] Disconnected to Service  com.samsung.dcmservice.DCMService
,09-09 13:40:57.056  1259  2304 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcmservice, Auto Run ON
09-09 13:40:57.056  1259  2304 W ActivityManager: Scheduling restart of crashed service com.samsung.dcmservice/.DCMService in 1000ms
09-09 13:40:57.056  1259  2304 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5054 ,hash=214901848 ,name=com.samsung.dcmservice
,09-09 13:40:57.066  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:40:57.066  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:40:57.066  1259  1623 D WifiBigDataLog: init : 
,09-09 13:40:57.066  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{65b9a9f u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1f7ee83 2608:com.samsung.android.providers.context/u0a5}
,09-09 13:40:57.076  6088  6088 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:40:57.076  6088  6088 D ActivityThread: Added TimaKeyStore provider
,09-09 13:40:57.076  1259  1989 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e32f290 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fea34f9 6088:com.samsung.android.app.FileShareClient/5005}
,09-09 13:40:57.086  1259  2294 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-09 13:40:57.096  6088  6088 W System  : ClassLoader referenced unknown path: /system/app/AllshareFileShareClient/lib/arm64
,09-09 13:40:57.096  6088  6088 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:40:57.106  6088  6088 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-09 13:40:57.126  6088  6088 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 13:40:57.136  6102  6102 E Zygote  : v2
09-09 13:40:57.136  6102  6102 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:40:57.136  6102  6102 I libpersona: KNOX_SDCARD not a persona
,09-09 13:40:57.136  6102  6102 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-09 13:40:57.136  1259  1853 I ActivityManager: Start proc 6102:com.policydm/1000 for broadcast-5 com.policydm/.XDMBroadcastReceiver
09-09 13:40:57.136  1868  1880 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@90fefe)
09-09 13:40:57.136  6102  6102 E Zygote  : accessInfo : 0
,09-09 13:40:57.146  1259  2008 I ActivityManager: Killing 5479:com.samsung.faceservice/5004 (adj 15): DHA:empty #31
,09-09 13:40:57.166  5030  5030 I ServiceManager: [#CMH#] Disconnected to Service  com.samsung.faceservice.FaceService
,09-09 13:40:57.166  1259  1324 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5479 ,hash=97229941 ,name=com.samsung.faceservice
09-09 13:40:57.166  1259  1324 D ActivityManager: isAutoRunBlockedApp:: com.samsung.faceservice, Auto Run ON
09-09 13:40:57.166  1259  1324 W ActivityManager: Scheduling restart of crashed service com.samsung.faceservice/.FaceService in 10894ms
,09-09 13:40:57.176  6102  6102 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:40:57.176  6102  6102 D ActivityThread: Added TimaKeyStore provider
,09-09 13:40:57.176  1259  2304 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d7ca7bc u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{41777ec 6102:com.policydm/1000}
,09-09 13:40:57.196  1868  6057 I System.out: (HTTPLog)-Static: Hongbao
,09-09 13:40:57.196  1868  6057 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-09 13:40:57.196  1868  6057 I System.out: (HTTPLog)-Static: Hongbao
09-09 13:40:57.196  1868  6057 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:40:57.196  6102  6102 W System  : ClassLoader referenced unknown path: /system/priv-app/SPDClient/lib/arm64
,09-09 13:40:57.196   552  1409 D EnterpriseController: netId is 0
09-09 13:40:57.196   552  1409 D Netd    : getNetworkForDns: using netid 0 for uid 10010
,09-09 13:40:57.206  1868  6057 D Uploader: Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,09-09 13:40:57.216  6102  6102 I FOTA    : [lIlIIlIIlIlllIIIIlll(108/llIIIIlllllIIllIIllI)] oms: /customer.xml
,09-09 13:40:57.216  6102  6102 I FOTA    : [lIlIIlIIlIlllIIIIlll(199/lllIlIlIIIllIIlIllIl)] read default : /system/csc/customer.xml
,09-09 13:40:57.236  6102  6102 I FOTA    : [com.sec.android.policyagent.PolicyApplication(36/onCreate)] PolicyApplication onCreated!
,09-09 13:40:57.236  1259  2629 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-09 13:40:57.246  6102  6102 I DBG_POLICYDM: [com.policydm.db.XDB(1501/IllIlIIIIlIIlIIIllIl)] xdbDMffs_Init
,09-09 13:40:57.256  6102  6102 I DBG_POLICYDM: [com.policydm.db.llIIIIlllllIIllIIllI(142/llIIIIlllllIIllIIllI)] try read dbString
,09-09 13:40:57.256  1868  6057 I System.out: (HTTPLog)-Static: Hongbao
09-09 13:40:57.256  1868  6057 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-09 13:40:57.256  1868  6057 I System.out: (HTTPLog)-Static: Hongbao
09-09 13:40:57.256  1868  6057 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:40:57.256  1868  6057 D Uploader: Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,09-09 13:40:57.266  2389  2389 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 13:40:57.266  2389  2389 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-09 13:40:57.286  1259  1853 V AlarmManager:  remove PendingIntent] PendingIntent{7fa26d8: PendingIntentRecord{f644eec com.google.android.gms broadcastIntent}}
,09-09 13:40:57.306  6102  6102 I DBG_POLICYDM: [IlIIIllIlIIIlIIlIIlI(51/<init>)] 
,09-09 13:40:57.306  6102  6102 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1403 android.content.ContextWrapper.bindService:632 IlIIIllIlIIIlIIlIIlI.<init>:55 IIIlIIlllIlIlIIIIIII.llIIIIlllllIIllIIllI:17 IIIlIIlllIlIlIIIIIII.llllIIIllIlIIIIllllI:23 
,09-09 13:40:57.326  6116  6116 E Zygote  : v2
09-09 13:40:57.326  6116  6116 I libpersona: KNOX_SDCARD checking this for 10054
09-09 13:40:57.326  6116  6116 I libpersona: KNOX_SDCARD not a persona
,09-09 13:40:57.326  1259  1325 I ActivityManager: Start proc 6116:com.samsung.aasaservice/u0a54 for service com.samsung.aasaservice/.AASAService
09-09 13:40:57.326  6116  6116 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-09 13:40:57.326  6102  6102 I DBG_POLICYDM: [IIIlIIlllIlIlIIIIIII(26/llllIIIllIlIIIIllllI)] AASAUpdater Init Success
09-09 13:40:57.326  6116  6116 E Zygote  : accessInfo : 0
,09-09 13:40:57.326  6116  6116 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
,09-09 13:40:57.336  6102  6102 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,09-09 13:40:57.336  6102  6102 I DBG_POLICYDM: [com.policydm.XDMService(574/llIlIllllllllllllllI)] get NotibarState : 0
,09-09 13:40:57.346  6102  6102 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,09-09 13:40:57.346  6102  6102 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,09-09 13:40:57.356  6102  6102 I DBG_POLICYDM: [com.policydm.XDMService(574/llIlIllllllllllllllI)] get NotibarState : 0
,09-09 13:40:57.356  1259  1325 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d7ca7bc u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{41777ec 6102:com.policydm/1000}
,09-09 13:40:57.356  6102  6102 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:40:57.366  6116  6116 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:40:57.366  6116  6116 D ActivityThread: Added TimaKeyStore provider
,09-09 13:40:57.376  6129  6129 E Zygote  : v2
09-09 13:40:57.376  6129  6129 I libpersona: KNOX_SDCARD checking this for 10027
09-09 13:40:57.376  6129  6129 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-09 13:40:57.376  6129  6129 I libpersona: KNOX_SDCARD not a persona
09-09 13:40:57.376  6129  6129 E Zygote  : accessInfo : 0
09-09 13:40:57.376  1259  1853 I ActivityManager: Start proc 6129:com.osp.app.signin/u0a27 for broadcast-5 com.osp.app.signin/.OspReceiver
09-09 13:40:57.376  6129  6129 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.osp.app.signin 
09-09 13:40:57.376  1259  1853 I ActivityManager: Killing 5469:com.samsung.ipservice/5004 (adj 15): DHA:empty #31
,09-09 13:40:57.386   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-09 13:40:57.386   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:40:57.386   552  1406 D Netd    : Iface wlan0 link down
09-09 13:40:57.386  2389  2389 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-09 13:40:57.386   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:40:57.386   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:40:57.386   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=13 Family=0 Type=0x1 Change=[0x1]UP  Flags=[0x1002]BROADCAST MULTICAST 
09-09 13:40:57.386   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:40:57.386   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:40:57.386   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 13, disable link
09-09 13:40:57.386   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 64
09-09 13:40:57.386   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:40:57.386   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:40:57.386   746  1442 I QC-NETMGR-LIB: Processing RTM_DELADDR
09-09 13:40:57.386   746  1442 I QC-NETMGR-LIB: Metainfo:  Family=10 PrefixLen=64 Scope=0xfd Index=13 Flags=[0xc4]OPTIMISTIC TENTATIVE PERMANENT 
09-09 13:40:57.386   746  1442 I QC-NETMGR-LIB: Attribute: PrefixIPv6 addr [fe80:0000:0000:0000:4678:3eff:feeb:95ef]
09-09 13:40:57.396   746  1442 I QC-NETMGR-LIB: Attribute: Address Cache Info - prefered=-1 valid=-1 cstamp=0x2c2d tstamp=0x2c2d
09-09 13:40:57.396   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [21]
09-09 13:40:57.396   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 13
,09-09 13:40:57.406  6116  6116 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm64
,09-09 13:40:57.406  1259  2320 W ActivityManager: Permission Denial: getCurrentUser() from pid=6116, uid=10054 requires android.permission.INTERACT_ACROSS_USERS
,09-09 13:40:57.416  6116  6116 D AASAservice: onCreate()
09-09 13:40:57.416  6102  6102 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(37/onServiceConnected)] AASA: onServiceConnected
09-09 13:40:57.416  1259  2294 I ActivityManager: Killing 5030:com.samsung.cmh:CMH/5004 (adj 15): DHA:empty #31
,09-09 13:40:57.416  6129  6129 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:40:57.416  6129  6129 D ActivityThread: Added TimaKeyStore provider
,09-09 13:40:57.416  1259  2310 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d7ca7bc u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{56d884 6129:com.osp.app.signin/u0a27}
,09-09 13:40:57.426  2970  3035 I WCNSS_FILTER: do_write: IBS write: fe
09-09 13:40:57.426  2970  3035 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-09 13:40:57.446  6129  6129 W System  : ClassLoader referenced unknown path: /system/priv-app/SamsungAccount_Hero/lib/arm64
,09-09 13:40:57.446  6129  6129 I SA      : [SSP] onCreated
,09-09 13:40:57.466  1259  1853 W ActivityManager: Unable to start service Intent { cmp=com.samsung.android.server.iris/.IrisService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} } U=0: not found
,09-09 13:40:57.486  1259  1623 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-09 13:40:57.486  1259  1259 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : -1
,09-09 13:40:57.486  1259  1259 D WifiNotificationController: SHOW_NOTI_MESSAGE : 13, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : 0
09-09 13:40:57.486  1259  1259 D WifiNotificationController: showCaptivePortalDisabledStatus with ssid/visible/title:null/false/0
,09-09 13:40:57.496  1259  1259 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:40:57.496  1259  1259 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
09-09 13:40:57.496  1259  1625 D HS20StateMachine: WIFI_STATE_DISABLED
09-09 13:40:57.496  1259  1625 D HS20StateMachine: CMD_HOTSPOT20_DISABLE
09-09 13:40:57.496  1259  1625 D HS20StateMachine: enter : DisablingState
09-09 13:40:57.496  1259  1628 I WifiHs20Service: Message received 5011
,09-09 13:40:57.496  1259  1627 D HS20SubscriptionManager: Received CMD_RELEASE_TLS, flag=1
09-09 13:40:57.496  1259  1625 D HS20StateMachine: enter : DisabledState
,09-09 13:40:57.496  1259  1631 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
09-09 13:40:57.496  1694  1694 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:40:57.496  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-09 13:40:57.496  1974  1985 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
09-09 13:40:57.496  1694  1694 D HotspotTile: onReceive : 1, 0
09-09 13:40:57.496  1974  1985 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-09 13:40:57.496  1259  1631 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
09-09 13:40:57.496  1868  2348 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:40:57.496  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:40:57.496  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1424ca2 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5827062 5955:com.test.thalitest/u0a136}
,09-09 13:40:57.506  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:40:57.506  1259  1721 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5469 ,hash=198833662 ,name=com.samsung.ipservice
09-09 13:40:57.506  1259  1721 D ActivityManager: isAutoRunBlockedApp:: com.samsung.ipservice, Auto Run ON
09-09 13:40:57.506  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:40:57.506  1259  1721 W ActivityManager: Scheduling restart of crashed service com.samsung.ipservice/.IPService in 20555ms
,09-09 13:40:57.506  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:57.506  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:57.506  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:57.506  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:57.506  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:57.506  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:57.506  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:57.506  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:57.506  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:57.506  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:57.506  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:57.506  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-09 13:40:57.506  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:57.506  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:40:57.506  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-09 13:40:57.506  1259  1325 D ActivityManager: isAutoRunBlockedApp:: com.samsung.cmh, Auto Run ON
09-09 13:40:57.506  1259  1325 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5030 ,hash=89226817 ,name=com.samsung.cmh:CMH
,09-09 13:40:57.506  5125  5125 I StoryService: [StoryService] On destroy() 
09-09 13:40:57.506  5125  5125 I ServiceController: [StoryService] shutdown() 
,09-09 13:40:57.776  6129  6129 E SIrisManager: Wait for 300ms...
,09-09 13:40:58.076  6129  6129 E SIrisManager: Wait for 600ms...
,09-09 13:40:58.376  6129  6129 E SIrisManager: Wait for 900ms...
09-09 13:40:58.376   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 476
09-09 13:40:58.376   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:40:58.376   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:40:58.376   746  1442 I QC-NETMGR-LIB: Processing RTM_DELLINK
09-09 13:40:58.376   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=13 Family=0 Type=0x1 Change=[0xffffffff]UP BROADCAST DEBUG LOOPBACK POINTOPOINT NOTRAILERS RUNNING NOARP PROMISC ALLMULTI MASTER SLAVE MULTICAST PORTSEL AUTOMEDIA DYNAMIC LOWER_UP DORMANT  Flags=[0x1002]BROADCAST MULTICAST 
09-09 13:40:58.376   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [17]
09-09 13:40:58.376   746  1442 I QC-NETMGR-LIB: Received RTM_DELLINK
09-09 13:40:58.376   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 13, disable link
,09-09 13:40:58.376  1259  1392 E EthernetNetworkFactory: stopTrackingInterface : not matched eth0/usb0 iface is wlan0
,09-09 13:40:58.386  6129  6129 I SA      : [TPM] There is no property file
,09-09 13:40:58.386  6129  6129 I SA      : [SCU] isHaveSA() - false
,09-09 13:40:58.396  6129  6129 I SA      : [TPM] getModelProperty : null
09-09 13:40:58.396  6129  6129 I SA      : [TPM] getCSCProperty : null
,09-09 13:40:58.406  6129  6129 I SA      : [DM] FLOATING AMOLED FEATURE: true
09-09 13:40:58.406  6129  6129 I SA      : [DM] PRODUCT AMOLED FEATURE: false
09-09 13:40:58.406  6129  6129 I SA      : [DM] TFT FEATURE: false
,09-09 13:40:58.406  6129  6129 I SA      : [SCU] isHaveSA() - false
,09-09 13:40:58.406  6129  6129 I SA      : [SCU] == networkStateCheck == false
09-09 13:40:58.406  6129  6129 I SA      : [SS] network off, couldn't connect to DIR
,09-09 13:40:58.406  6129  6129 I SA      : [DM] init START
,09-09 13:40:58.406  6129  6129 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-09 13:40:58.416  6129  6129 I SA      : [DM] This device is not a Vodafone,
,09-09 13:40:58.416  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:40:58.416  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:40:58.426  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:40:58.426  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:40:58.426  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:40:58.426  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:40:58.426  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:40:58.426  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:40:58.426  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:40:58.426  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:40:58.426  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:40:58.426  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:40:58.426  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:40:58.426  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:40:58.426  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:40:58.426  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:40:58.426  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:40:58.426  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:40:58.426  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:40:58.426  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:40:58.426  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:40:58.426  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:40:58.436  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:40:58.436  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:40:58.436  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:40:58.436  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:40:58.436  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:40:58.436  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:40:58.436  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000,
09-09 13:40:58.436  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000,
09-09 13:40:58.436  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:40:58.436  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:40:58.436  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000,
09-09 13:40:58.436  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:40:58.436  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:40:58.436  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:40:58.436  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:40:58.436  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:40:58.436  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:40:58.436  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:40:58.436  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:40:58.436  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:40:58.436  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:40:58.446  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:40:58.446  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:40:58.446  6129  6129 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:40:58.446  6129  6129 I SA      : support phone number id : true
09-09 13:40:58.446  6129  6129 I SA      : [DM] Supports Ref Jpn : true
09-09 13:40:58.446  6129  6129 I SA      : [DM] init END
,09-09 13:40:58.446  6129  6129 I SA      : [OR] onReceive log=[SA = 2.2.01-51 V = 23 HWD = 2048X1536 2.0 dpi = 320  SIZE = 4 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = gts28velte P = gts28veltexx I = MMB29M M = SM-T719 OKLEFT false DIS MMB29M.T719XXU1APF6 PSS = 8.00525302084415  ]
,09-09 13:40:58.446  6129  6129 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-09 13:40:58.456  6129  6129 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-09 13:40:58.456  6129  6129 I SA      : [SLFUCHKMGR] constructor called
,09-09 13:40:58.466  6129  6129 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-09 13:40:58.466  6129  6129 I SA      : [OR] == isSIMCardReady false ==
,09-09 13:40:58.466  6129  6129 I SA      : [SCU] == networkStateCheck == false
09-09 13:40:58.466  6129  6129 I SA      : [OR] onReceive END
,09-09 13:40:58.466  1259  2294 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d7ca7bc u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a6a9da7 6058:com.sec.app.RilErrorNotifier/1000}
,09-09 13:40:58.466  6058  6058 I PhoneErrorReceiver: onReceive
,09-09 13:40:58.466  6058  6058 V PhoneErrorReceiver: beginStartingService
,09-09 13:40:58.476  6058  6058 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1311 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.sec.app.RilErrorNotifier.PhoneErrorReceiver.beginStartingService:194 com.sec.app.RilErrorNotifier.PhoneErrorReceiver.onReceiveWithPrivilege:171 
,09-09 13:40:58.476  6058  6058 V PhoneErrService: Creating SmsReceiverService
09-09 13:40:58.476  1259  1721 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d7ca7bc u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ace8b17 4424:com.sec.spp.push/u0a26}
,09-09 13:40:58.486  6058  6058 V MIP_PhoneErrService: mTelephonyManager is not null
09-09 13:40:58.486  4424  4424 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:40:58.486  4424  4424 E SPPClientService: [SystemStateMoniter] Current Time : 114811
,09-09 13:40:58.486  4424  4424 E SPPClientService: [SystemStateMoniter] No Connect : true
,09-09 13:40:58.486  1259  1324 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d7ca7bc u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ce11b0e 2481:android.process.media/u0a33}
09-09 13:40:58.496  2481  2481 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:40:58.496  4424  6145 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-09 13:40:58.496  6058  6058 V PhoneErrService: Starting #1: Bundle[mParcelledData.dataSize=448]
09-09 13:40:58.506  6058  6058 I PhoneErrService: mResultCode: 0
,09-09 13:40:58.506  6058  6058 V MIP_PhoneErrService: onDataConnectionState : -1
,09-09 13:40:58.506  6058  6146 V PhoneErrService: Handling incoming message: { when=0 what=0 arg1=1 obj=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.sec.app.RilErrorNotifier/.PhoneErrService bqHint=3 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } target=com.sec.app.RilErrorNotifier.PhoneErrService$ServiceHandler }
,09-09 13:40:58.506  6058  6146 V PhoneErrorReceiver: finishStartingService
,09-09 13:40:58.506  6147  6147 E Zygote  : v2
09-09 13:40:58.506  6147  6147 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:40:58.506  6147  6147 I libpersona: KNOX_SDCARD not a persona
,09-09 13:40:58.506  6147  6147 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-09 13:40:58.506  1259  2304 I ActivityManager: Start proc 6147:com.samsung.android.SettingsReceiver/1000 for broadcast-5 com.samsung.android.SettingsReceiver/.SettingsIntentReceiver
,09-09 13:40:58.506  6147  6147 E Zygote  : accessInfo : 0
,09-09 13:40:58.516  6058  6058 V PhoneErrService: Destroying PhoneErrorReceiverService
,09-09 13:40:58.516  1259  1853 I ActivityManager: Killing 5269:com.google.android.apps.photos/u0a97 (adj 15): DHA:empty #31
,09-09 13:40:58.536   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 476
09-09 13:40:58.536   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:40:58.536   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:40:58.536   746  1442 I QC-NETMGR-LIB: Processing RTM_DELLINK
09-09 13:40:58.536   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=14 Family=0 Type=0x1 Change=[0xffffffff]UP BROADCAST DEBUG LOOPBACK POINTOPOINT NOTRAILERS RUNNING NOARP PROMISC ALLMULTI MASTER SLAVE MULTICAST PORTSEL AUTOMEDIA DYNAMIC LOWER_UP DORMANT  Flags=[0x1002]BROADCAST MULTICAST 
09-09 13:40:58.536   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [17]
09-09 13:40:58.536   746  1442 I QC-NETMGR-LIB: Received RTM_DELLINK
09-09 13:40:58.536   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 14, disable link
,09-09 13:40:58.536  1259  1392 E EthernetNetworkFactory: stopTrackingInterface : not matched eth0/usb0 iface is p2p0
,09-09 13:40:58.546  6147  6147 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:40:58.546  6147  6147 D ActivityThread: Added TimaKeyStore provider
,09-09 13:40:58.546  1259  1637 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d7ca7bc u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6454e69 6147:com.samsung.android.SettingsReceiver/1000}
,09-09 13:40:58.566  6147  6147 W System  : ClassLoader referenced unknown path: /system/priv-app/SettingsReceiver/lib/arm64
,09-09 13:40:58.576   589  6151 I art     : Starting a blocking GC HeapTrim
,09-09 13:40:58.596  6159  6159 E Zygote  : v2
09-09 13:40:58.596  6159  6159 I libpersona: KNOX_SDCARD checking this for 10022
09-09 13:40:58.596  6159  6159 I libpersona: KNOX_SDCARD not a persona
,09-09 13:40:58.596  6159  6159 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-09 13:40:58.596  1259  2320 I ActivityManager: Start proc 6159:com.myscript.atk.rmc.service.sample/u0a22 for content provider com.myscript.atk.rmc.service.sample/com.myscript.atk.rmc.DataStorageProvider
,09-09 13:40:58.596  1259  1621 D NetworkPolicy: isUidForegroundLocked: 10022, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-09 13:40:58.596  6159  6159 E Zygote  : accessInfo : 0
09-09 13:40:58.596  6159  6159 W SELinux : SELinux: seapp_context_lookup: seinfo=filtered_untrusted, level=s0:c512,c768, pkgname=com.myscript.atk.rmc.service.sample 
,09-09 13:40:58.616  6159  6159 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:40:58.616  6159  6159 D ActivityThread: Added TimaKeyStore provider
,09-09 13:40:58.626  1259  1325 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.photos, Auto Run ON
09-09 13:40:58.626  1259  1325 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5269 ,hash=209068276 ,name=com.google.android.apps.photos
,09-09 13:40:58.626  1259  1621 D NetworkPolicy: isUidForegroundLocked: 10022, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,09-09 13:40:58.646  6159  6159 W System  : ClassLoader referenced unknown path: /system/priv-app/ResourceManager/lib/arm64
,09-09 13:40:58.666  1259  1325 W ActivityManager: Permission Denial: getCurrentUser() from pid=6159, uid=10022 requires android.permission.INTERACT_ACROSS_USERS
,09-09 13:40:58.666  1259  1989 I ActivityManager: Killing 5125:com.samsung.storyservice/5004 (adj 15): DHA:empty #31
09-09 13:40:58.666  1259  1989 I ActivityManager: Killing 5247:com.google.android.gm/u0a80 (adj 15): DHA:empty #31
,09-09 13:40:58.666  1259  1989 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d7ca7bc u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bb1cd0d 2464:com.microsoft.skydrive/u0a93}
,09-09 13:40:58.666  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-09 13:40:58.676  1259  1987 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
,09-09 13:40:58.676  1259  2621 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5247 ,hash=124058850 ,name=com.google.android.gm
09-09 13:40:58.676  1259  2621 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
09-09 13:40:58.676  1259  1987 D PackageManager: findPreferredActivity: No PreferredActivities set
09-09 13:40:58.676  1259  1987 I PackageManager: No preferred activity: intent should not be shown
,09-09 13:40:58.686  1259  1721 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5125 ,hash=139340102 ,name=com.samsung.storyservice
09-09 13:40:58.686  1259  1721 D ActivityManager: isAutoRunBlockedApp:: com.samsung.storyservice, Auto Run ON
,09-09 13:40:58.696  6172  6172 E Zygote  : v2
09-09 13:40:58.696  6172  6172 I libpersona: KNOX_SDCARD checking this for 10097
09-09 13:40:58.696  6172  6172 I libpersona: KNOX_SDCARD not a persona
,09-09 13:40:58.696  6172  6172 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-09 13:40:58.696  1259  1637 I ActivityManager: Start proc 6172:com.google.android.apps.photos/u0a97 for broadcast-5 com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-09 13:40:58.696  6172  6172 E Zygote  : accessInfo : 0
09-09 13:40:58.696  6172  6172 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.photos 
,09-09 13:40:58.726  6172  6172 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:40:58.726  6172  6172 D ActivityThread: Added TimaKeyStore provider
,09-09 13:40:58.726  1259  2304 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d7ca7bc u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e6698f 6172:com.google.android.apps.photos/u0a97}
,09-09 13:40:58.796  6172  6172 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-09 13:40:59.066  6172  6172 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-09 13:40:59.116  1259  2008 W ActivityManager: Permission Denial: getCurrentUser() from pid=6172, uid=10097 requires android.permission.INTERACT_ACROSS_USERS
,09-09 13:40:59.156  6172  6172 W Primes  : Memory instrumentations are turned off.
,09-09 13:40:59.166  6172  6172 W Primes  : Timer instrumentations are turned off.
,09-09 13:40:59.176  6172  6172 W Primes  : Crash monitoring is turned off.
,09-09 13:40:59.176  6172  6172 W Primes  : Network monitoring is turned off.
09-09 13:40:59.176  6172  6172 W Primes  : Package metrics are turned off by default
,09-09 13:40:59.216  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ec923 u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e6698f 6172:com.google.android.apps.photos/u0a97}
,09-09 13:40:59.226  1259  2320 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d7ca7bc u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e6698f 6172:com.google.android.apps.photos/u0a97}
,09-09 13:40:59.236  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ba67e20 u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e6698f 6172:com.google.android.apps.photos/u0a97}
,09-09 13:40:59.246  1259  1989 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d7ca7bc u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ba36c24 4746:com.sec.android.daemonapp/u0a127}
,09-09 13:40:59.246  4746  4746 D [WeatherWidget(1210)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
,09-09 13:40:59.246  4746  4746 D [WeatherWidget(1210)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78F9CD3967C07B6DE6AAB9923C4C53919020112019F4465EB3AA6FD266958B212E]}
,09-09 13:40:59.256  1259  2294 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d7ca7bc u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bd6dd8 5344:com.sec.android.app.samsungapps/u0a9}
,09-09 13:40:59.266  1259  2294 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{220cfcb u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a6a9da7 6058:com.sec.app.RilErrorNotifier/1000}
,09-09 13:40:59.266  6058  6058 I PhoneErrorReceiver: onReceive
09-09 13:40:59.266  6058  6058 I MIPErrReceiver: isWiFiConnected
,09-09 13:40:59.266  1259  1987 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-09 13:40:59.276  1259  2294 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{220cfcb u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f996d43 6074:com.sec.knox.switcher/1000}
,09-09 13:40:59.276  6074  6074 I usagelog: received in receiver
09-09 13:40:59.276  6074  6074 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
09-09 13:40:59.276  6074  6074 I KnoxUsageLogPro: premStatus:2
,09-09 13:40:59.276  6074  6074 I KnoxUsageLogPro: isEulaShown : false
09-09 13:40:59.276  6074  6074 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,09-09 13:40:59.306  6197  6197 E Zygote  : v2
09-09 13:40:59.306  6197  6197 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:40:59.306  6197  6197 I libpersona: KNOX_SDCARD not a persona
09-09 13:40:59.306  1259  2294 I ActivityManager: Start proc 6197:com.samsung.android.securitylogagent/1000 for broadcast-5 com.samsung.android.securitylogagent/.receivers.NetworkReceiver
,09-09 13:40:59.306  6197  6197 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-09 13:40:59.306  6197  6197 E Zygote  : accessInfo : 0
09-09 13:40:59.306  1259  2294 I ActivityManager: Killing 5529:com.android.calendar/u0a106 (adj 15): DHA:empty #31
,09-09 13:40:59.326  1259  1623 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-09 13:40:59.326  1259  1623 E WifiStateMachine: Error! unhandled message{ when=-1m55s656ms what=131156 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:40:59.326  1259  1623 E WifiHW  : ##################### set firmware type 0 #####################
,09-09 13:40:59.326  6197  6197 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:40:59.326  6197  6197 D ActivityThread: Added TimaKeyStore provider
,09-09 13:40:59.336  1259  1325 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1424ca2 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{345119e 6197:com.samsung.android.securitylogagent/1000}
,09-09 13:40:59.356  6197  6197 W System  : ClassLoader referenced unknown path: /system/app/SecurityLogAgent/lib/arm64
,09-09 13:40:59.366  1259  2304 I ActivityManager: Killing 5545:com.android.providers.calendar/u0a32 (adj 15): DHA:empty #31
,09-09 13:40:59.426  1259  2294 D ActivityManager: isAutoRunBlockedApp:: com.android.calendar, Auto Run ON
,09-09 13:40:59.426  1259  2294 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5529 ,hash=147029517 ,name=com.android.calendar
,09-09 13:40:59.456  1259  2320 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5545 ,hash=68721619 ,name=com.android.providers.calendar
09-09 13:40:59.456  1259  2320 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
,09-09 13:40:59.986  1259  1590 V AlarmManager: Expired Alarm result :8
,09-09 13:41:00.616  1259  1392 E EthernetNetworkFactory: maybeTrackInterface : not matched eth0/usb0 iface is wlan0
,09-09 13:41:00.616  1259  1416 D Tethering: enter TetherInterfaceSM  and send tetherstatechangebroadcast
09-09 13:41:00.616  1259  1416 D Tethering: NAP Supported and not Wifi Model
,09-09 13:41:00.616   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1088
09-09 13:41:00.616   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:00.616   552  1406 D Netd    : Iface wlan0 link down
,09-09 13:41:00.616   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:00.616   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:41:00.616   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=15 Family=0 Type=0x1 Change=[0xffffffff]UP BROADCAST DEBUG LOOPBACK POINTOPOINT NOTRAILERS RUNNING NOARP PROMISC ALLMULTI MASTER SLAVE MULTICAST PORTSEL AUTOMEDIA DYNAMIC LOWER_UP DORMANT  Flags=[0x1002]BROADCAST MULTICAST 
09-09 13:41:00.616   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:41:00.616   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:41:00.616   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 15, disable link
,09-09 13:41:00.626  1259  1416 E Tethering: No numeric data
,09-09 13:41:00.626   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1088
09-09 13:41:00.626   552  1406 D Netd    : Iface p2p0 link down
09-09 13:41:00.626   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:00.626   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:00.626   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:41:00.626   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=16 Family=0 Type=0x1 Change=[0xffffffff]UP BROADCAST DEBUG LOOPBACK POINTOPOINT NOTRAILERS RUNNING NOARP PROMISC ALLMULTI MASTER SLAVE MULTICAST PORTSEL AUTOMEDIA DYNAMIC LOWER_UP DORMANT  Flags=[0x1002]BROADCAST MULTICAST 
09-09 13:41:00.626   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:41:00.626   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:41:00.626   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 16, disable link
,09-09 13:41:00.626  1259  1392 E EthernetNetworkFactory: maybeTrackInterface : not matched eth0/usb0 iface is p2p0,
,09-09 13:41:00.636  1259  1416 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 13:41:00.636  1259  1416 D Tethering: InitialState.processMessage what=4
09-09 13:41:00.636  1259  1416 D Tethering: NAP Supported and not Wifi Model
09-09 13:41:00.636   552  1413 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-09 13:41:00.636   552  1413 D SoftapController: Softap fwReload - Ok
09-09 13:41:00.636  1259  1620 V NetworkStats: performPollLocked(flags=0x1)
,09-09 13:41:00.636  1259  1620 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:00.636  1694  1694 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 13:41:00.636  1694  1694 D HotspotTile: updateTetherState():false, false
09-09 13:41:00.646  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{372f511 u-1 android.net.conn.TETHER_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a8d25ef 1259:system/1000}
09-09 13:41:00.646   552  1413 D CommandListener: Setting iface cfg
09-09 13:41:00.646   552  1413 D CommandListener: Trying to bring down wlan0
09-09 13:41:00.646  1259  1416 E Tethering: No numeric data
09-09 13:41:00.646   552  1413 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:41:00.646  1259  1416 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-09 13:41:00.646  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:00.646  1259  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:00.646  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:00.646  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:00.646  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:00.646  1259  1620 V NetworkStats: performPollLocked() took 10ms,
09-09 13:41:00.646  1694  1694 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 13:41:00.646  1694  1694 D HotspotTile: updateTetherState():false, false
,09-09 13:41:00.646  1259  1623 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-09 13:41:00.646  1259  1623 D wifi    : Can not initialize the vendor function pointer table
09-09 13:41:00.646  1259  1623 E WifiNative-HAL: Could not start hal
09-09 13:41:00.646  1259  1623 E WifiStateMachine: Failed to start HAL
09-09 13:41:00.656  1259  1623 E WifiHW  : supplicant_name : p2p_supplicant
,09-09 13:41:00.656  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ac3b676 u-1 android.net.conn.TETHER_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a8d25ef 1259:system/1000}
,09-09 13:41:00.656  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:00.656  1259  1620 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:41:00.656  1259  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:00.656  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:00.656  1259  1620 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:00.656  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:00.656  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:00.656  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:00.656  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:00.656  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:00.656  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:00.656  1259  1620 V NetworkStats: performPollLocked() took 3ms
,09-09 13:41:00.716  6221  6221 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-09 13:41:00.716  6221  6221 I wpa_supplicant: Successfully initialized wpa_supplicant
09-09 13:41:00.716  6221  6221 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x20000), vendorssid_list()
09-09 13:41:00.716  6221  6221 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-09 13:41:00.746  6221  6221 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-09 13:41:00.746   462   462 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6221
09-09 13:41:00.746   462   462 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
09-09 13:41:00.746  6221  6221 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-09 13:41:00.746  6221  6221 I wpa_supplicant: ssSupport state is = 1
09-09 13:41:00.746  6221  6221 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-09 13:41:00.746  6221  6221 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,09-09 13:41:00.746   462   462 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6221
09-09 13:41:00.746   462   462 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,09-09 13:41:00.756  1259  1623 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-09 13:41:00.756  1259  1259 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:00.756  1259  1259 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:00.756  1259  1628 I WifiHs20Service: Message received 5011
,09-09 13:41:00.756  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-09 13:41:00.756  1694  1694 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:00.756  1259  1631 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
09-09 13:41:00.756  1694  1694 D HotspotTile: onReceive : 2, 0
09-09 13:41:00.756  6221  6221 I SecureStorage: [INFO]: SPID(0x00000005)ss_id will be loaded by secure_storage_daemon: /system/bin/wpa_supplicant
,09-09 13:41:00.756  1974  2242 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
09-09 13:41:00.756  1974  2242 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-09 13:41:00.756  1259  1631 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,09-09 13:41:00.756  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:00.756  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c30d477 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{345119e 6197:com.samsung.android.securitylogagent/1000}
,09-09 13:41:00.766  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:00.766  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:00.776  1259  2008 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c30d477 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5827062 5955:com.test.thalitest/u0a136}
,09-09 13:41:00.776  1259  2294 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:00.776  1259  2294 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:00.776  1259  2294 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:00.776  1259  2294 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:00.776  1259  2294 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:00.776  1259  2294 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:00.776  1259  2294 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:00.776  1259  2294 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:00.776  1259  2294 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:00.776  1259  2294 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:00.776  1259  2294 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:00.776  1259  2294 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-09 13:41:00.776  1259  2294 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:00.776  1259  2294 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:00.776  1259  2294 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-09 13:41:00.966   462   462 I SecureStorage: [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
09-09 13:41:00.966  6221  6221 I SecureStorage: [INFO]: SPID(0x00000005)Processing data has been completed
,09-09 13:41:01.006  6221  6221 I wpa_supplicant: Loading default cred
09-09 13:41:01.006  6221  6221 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,09-09 13:41:01.036  6221  6221 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,09-09 13:41:01.036   462   462 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 6221
09-09 13:41:01.036   462   462 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
09-09 13:41:01.036  6221  6221 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
09-09 13:41:01.036  6221  6221 I wpa_supplicant: ssSupport state is = 1
09-09 13:41:01.036  6221  6221 W wpa_supplicant: Loading system cred
09-09 13:41:01.036  6221  6221 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,09-09 13:41:01.066  6221  6221 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,09-09 13:41:01.066   462   462 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 6221
09-09 13:41:01.066   462   462 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,09-09 13:41:01.066  6221  6221 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
09-09 13:41:01.066  6221  6221 I wpa_supplicant: ssSupport state is = 1
09-09 13:41:01.066  6221  6221 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 13:41:01.066  6221  6221 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 13:41:01.066  6221  6221 I wpa_supplicant: [getIMSI]: sim_num 0
,09-09 13:41:01.066  6221  6221 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 13:41:01.066   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-09 13:41:01.066   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:01.066   552  1406 D Netd    : Iface wlan0 link down
09-09 13:41:01.066   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:01.066   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:41:01.066   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=15 Family=0 Type=0x1 Change=[0x1]UP  Flags=[0x1003]UP BROADCAST MULTICAST 
09-09 13:41:01.066   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:41:01.066   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:41:01.066   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 15, disable link
,09-09 13:41:01.386  6221  6221 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
,09-09 13:41:01.386  6221  6221 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,09-09 13:41:01.426  6221  6221 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,09-09 13:41:01.426   462   462 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 6221
09-09 13:41:01.426   462   462 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,09-09 13:41:01.426  6221  6221 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
09-09 13:41:01.426  6221  6221 I wpa_supplicant: ssSupport state is = 1
,09-09 13:41:01.426  6221  6221 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 13:41:01.426   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-09 13:41:01.426   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:01.426   552  1406 D Netd    : Iface p2p0 link down
,09-09 13:41:01.426   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:01.426   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:41:01.426   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=16 Family=0 Type=0x1 Change=[0x1]UP  Flags=[0x1043]UP BROADCAST RUNNING MULTICAST 
09-09 13:41:01.426   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:41:01.426   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:41:01.426   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 16, disable link
09-09 13:41:01.426   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-09 13:41:01.426   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:01.426   552  1406 D Netd    : Iface p2p0 link down
09-09 13:41:01.436   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:01.436   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:41:01.436   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=16 Family=0 Type=0x1 Change=[0x0] Flags=[0x1003]UP BROADCAST MULTICAST 
09-09 13:41:01.436   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:41:01.436   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:41:01.436   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 16, disable link
,09-09 13:41:01.616   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-09 13:41:01.616   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:01.616   552  1406 D Netd    : Iface p2p0 link down
09-09 13:41:01.616   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:01.616   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:41:01.616   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=16 Family=0 Type=0x1 Change=[0x0] Flags=[0x1003]UP BROADCAST MULTICAST 
09-09 13:41:01.616   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:41:01.616   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:41:01.616   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 16, disable link
,09-09 13:41:01.646  6221  6221 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,09-09 13:41:01.656  1259  1623 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-09 13:41:01.656  1259  1623 E WifiStateMachine: Deffering msg in Supplicant Starting State131085
,09-09 13:41:01.666  1259  1623 D WifiNative-wlan0: callSECApiBoolean - ID [301]
,09-09 13:41:01.666  6221  6221 I wpa_supplicant: HOTSPOT20_ENABLE called ON
09-09 13:41:01.666  6221  6221 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 13:41:01.686  6221  6221 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-09 13:41:01.706  6221  6221 I wpa_supplicant: wlan0: Skip scan - bUseNetwork false
09-09 13:41:01.706  1259  1623 D WifiNative-wlan0: callSECApiInt - ID [210]
,09-09 13:41:01.706  1259  1259 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:01.706  1259  1625 D HS20StateMachine: WIFI_STATE_ENABLED
09-09 13:41:01.706  1259  1625 D HS20StateMachine: reloadCredentialsToSupplicant
09-09 13:41:01.706  1259  1625 D HotspotDBHandler: getCredentialIds
,09-09 13:41:01.706  1259  1259 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:01.706  1259  1628 I WifiHs20Service: Message received 5011
09-09 13:41:01.706  1259  1631 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,09-09 13:41:01.706  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-09 13:41:01.706  1694  1694 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:01.706  1974  5601 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
09-09 13:41:01.706  1259  1623 D WifiConfigStore: Loading config and enabling all networks 
09-09 13:41:01.706  1694  1694 D HotspotTile: onReceive : 3, 0
09-09 13:41:01.706  1694  2108 D QSTile.WifiTile: handleUpdateState  cb.changed 5 wifiEnabled : ON 
,09-09 13:41:01.706  1974  5601 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-09 13:41:01.706  1259  1631 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,09-09 13:41:01.716  1694  1694 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 148
,09-09 13:41:01.716  5955  5955 D BluetoothAdapter: STATE_ON
,09-09 13:41:01.716  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c90e8e4 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{345119e 6197:com.samsung.android.securitylogagent/1000}
,09-09 13:41:01.716  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:01.716  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:01.716  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:01.716  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:01.716  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:01.716  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:01.716  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:01.716  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:01.726  5955  5955 D BluetoothAdapter: STATE_ON
,09-09 13:41:01.726  1259  1623 I WifiConfigStore: "NG700" is a verified password AP: true
09-09 13:41:01.726  1259  1623 E WifiConfigStore: Not a HS20
,09-09 13:41:01.726  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:01.726  1259  1623 D WifiConfigStore: loaded 0 passpoint configs
09-09 13:41:01.726  1259  1623 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-09 13:41:01.726  1259  1623 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-09 13:41:01.726  1259  1623 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
09-09 13:41:01.726  1259  1623 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-09 13:41:01.726  5955  5955 D BluetoothAdapter: STATE_ON
,09-09 13:41:01.736  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:01.736  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:01.736  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:01.736  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:01.736  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:01.736  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:01.736  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:01.736  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:01.736  5955  5955 D BluetoothAdapter: STATE_ON
,09-09 13:41:01.736  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:01.746  5955  5955 D BluetoothAdapter: STATE_ON
,09-09 13:41:01.746  1259  1625 I ActivityManager: Start proc 6229:com.samsung.hs20provider/u0a85 for content provider com.samsung.hs20provider/.Hs20Provider
,09-09 13:41:01.746  1259  1259 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
09-09 13:41:01.746  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:01.746  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:01.746  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:01.746  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:01.746  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:01.746  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:01.746  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:01.746  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:01.746  1259  1259 D WifiHs20Service: reason: 2
09-09 13:41:01.746  1259  1623 D WifiConfigStore: setNetworkPriorityDefault: networkId = 0, priority = 1
09-09 13:41:01.746  1259  1628 I WifiHs20Service: Message received 5014
09-09 13:41:01.746  1259  1628 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
09-09 13:41:01.746  1259  1628 E WifiHs20Service: The changed config is NULL
09-09 13:41:01.746  1259  1623 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-09 13:41:01.746  5955  5955 D BluetoothAdapter: STATE_ON
,09-09 13:41:01.746  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:01.746  6229  6229 E Zygote  : v2
09-09 13:41:01.746  6229  6229 I libpersona: KNOX_SDCARD checking this for 10085
09-09 13:41:01.746  6229  6229 I libpersona: KNOX_SDCARD not a persona
09-09 13:41:01.746  6229  6229 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-09 13:41:01.756  1259  1623 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,09-09 13:41:01.756  6229  6229 E Zygote  : accessInfo : 0
,09-09 13:41:01.756  6221  6221 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-09 13:41:01.756  6221  6221 I wpa_supplicant: resume autoscan
09-09 13:41:01.756  6221  6221 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
09-09 13:41:01.756  6221  6221 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
09-09 13:41:01.756  6221  6221 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-09 13:41:01.756  6229  6229 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
09-09 13:41:01.756  6221  6221 I wpa_supplicant: reset timer : RESET_TIMER 0
09-09 13:41:01.756  6221  6221 I wpa_supplicant: P2P: Current p2p state = IDLE
09-09 13:41:01.756  6221  6221 I wpa_supplicant: First Scan Start
09-09 13:41:01.756  6221  6221 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-09 13:41:01.756  1259  2304 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c90e8e4 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5827062 5955:com.test.thalitest/u0a136}
,09-09 13:41:01.756  1259  1989 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:01.756  1259  1989 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:01.756  1259  1989 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:01.756  1259  1989 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:01.756  1259  1989 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:01.756  1259  1989 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:01.756  1259  1989 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:01.756  1259  1989 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:01.756  1259  1989 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:01.756  1259  1989 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:01.756  1259  1989 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:01.756  1259  1989 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-09 13:41:01.756  1259  1989 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:01.756  1259  1989 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:01.756  1259  1989 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-09 13:41:01.756  1259  1623 D WifiNative-wlan0: Setting external_sim to 1
,09-09 13:41:01.756  1259  1623 D WifiStateMachine: [setCountryCode()] Airplane mode return !!!
09-09 13:41:01.756  1259  1623 D WifiStateMachine: Setting OUI to DA-A1-19
,09-09 13:41:01.756  6221  6221 I wpa_supplicant: bt_status is set be DISCONNECTED
,09-09 13:41:01.766  1259  1623 E WifiNative-wlan0: do suspend true
,09-09 13:41:01.766  1259  1623 D WifiNative-HAL: Failing getSupportedFeatureset because HAL isn't started
09-09 13:41:01.766  1259  1622 D WifiP2pService: P2pDisabledState{ what=131203 }
09-09 13:41:01.766  1259  1623 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-09 13:41:01.766  1259  1623 D WifiStateMachine: [FCC]Airplane on, setFccChannel(0)!!!
09-09 13:41:01.766  1259  1623 D WifiStateMachine: setFccChannelNative: channel = 0
09-09 13:41:01.766  1259  1623 D WifiNative-wlan0: callSECApiInt - ID [230]
,09-09 13:41:01.766  1259  1259 D RttService: SCAN_AVAILABLE : 3
09-09 13:41:01.766  1259  1650 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:01.766  1259  1649 E WifiScanningService: could not start HAL
09-09 13:41:01.766   552  1413 D CommandListener: Setting iface cfg
09-09 13:41:01.766   552  1413 D CommandListener: Trying to bring up p2p0
,09-09 13:41:01.766  1259  1622 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 13:41:01.766  1259  1622 D SecContentProvider: insert(), uri = 2
,09-09 13:41:01.766  1259  1622 D WifiP2pService: P2pEnablingState
,09-09 13:41:01.766  1259  1622 D WifiP2pService: P2pEnablingState{ what=147457 }
09-09 13:41:01.766  1259  1622 D WifiP2pService: P2p socket connection successful
09-09 13:41:01.766  1259  1622 D WifiP2pService: P2pEnabledState
09-09 13:41:01.766  1259  1622 D SecContentProvider: insert(), uri = 2
,09-09 13:41:01.776  1259  1622 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-09 13:41:01.776  1259  1630 E ConnectivityService: updateNetworkInfo()
09-09 13:41:01.776  1259  1630 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,09-09 13:41:01.776  1259  1259 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-09 13:41:01.776  1259  1417 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
09-09 13:41:01.776  1259  1417 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-09 13:41:01.776  1259  1417 D WifiDisplayController: disconnect
09-09 13:41:01.776  1259  1417 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 13:41:01.776  6229  6229 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:41:01.776  6229  6229 D ActivityThread: Added TimaKeyStore provider
09-09 13:41:01.776  1259  1623 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-09 13:41:01.776  1694  1694 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-09 13:41:01.776  1694  1694 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-09 13:41:01.776  1694  1694 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-09 13:41:01.776  1259  2621 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 13:41:01.776  1694  1694 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-09 13:41:01.776  1259  1623 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-09 13:41:01.776  6221  6221 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 512
,09-09 13:41:01.786  6221  6221 I wpa_supplicant: P2P: Set Samsung Discovery name = 
,09-09 13:41:01.786  1259  1417 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:01.786  1259  1417 I WifiDisplayAdapter: onP2pDisconnected
09-09 13:41:01.786  1259  1417 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 13:41:01.786  1259  1417 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-09 13:41:01.786  1694  1694 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-09 13:41:01.786  1974  2242 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
09-09 13:41:01.786  1259  2124 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-09 13:41:01.786  1259  2124 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 3, Mac address valid: false, AP MAC address: [00:00:00:00:00:00], Wifi-Ap SSID Valid: false, SSID: 
,09-09 13:41:01.786  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{facc402 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fea34f9 6088:com.samsung.android.app.FileShareClient/5005}
,09-09 13:41:01.796  6088  6088 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:41:01.796  1259  2124 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-09 13:41:01.796  1259  2124 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 3, Mac address valid: false, AP MAC address: [00:00:00:00:00:00], Wifi-Ap SSID Valid: false, SSID: 
,09-09 13:41:01.796  6088  6088 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-09 13:41:01.796  6088  6088 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 13:41:01.796  6229  6229 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm64
,09-09 13:41:01.796  1259  2320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{facc402 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dcd9326 5659:com.samsung.android.app.FileShareServer/5005}
,09-09 13:41:01.806  5659  5659 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:41:01.806  5659  5659 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
09-09 13:41:01.806  5659  5659 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,09-09 13:41:01.806  1259  1622 E WifiP2pService: Failed to set my phone number info into probe response
09-09 13:41:01.806  1259  1721 W ActivityManager: Permission Denial: getCurrentUser() from pid=6229, uid=10085 requires android.permission.INTERACT_ACROSS_USERS
,09-09 13:41:01.806  1259  1622 D WifiNative-p2p0: p2pGetDeviceAddress
09-09 13:41:01.806  1259  1622 D WifiNative-p2p0: p2pGetDeviceAddress returning 46:78:3e:eb:95:ef
,09-09 13:41:01.806  1259  1622 D WifiP2pService: DeviceAddress: 46:95:ef
09-09 13:41:01.806  1259  1417 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Tablet] Galaxy Tab S2
09-09 13:41:01.806  1259  1417 D WifiDisplayController:  deviceAddress: 46:78:3e:eb:95:ef
09-09 13:41:01.806  1259  1417 D WifiDisplayController:  primary type: 1-0050F204-9
09-09 13:41:01.806  1259  1417 D WifiDisplayController:  secondary type: null
09-09 13:41:01.806  1259  1417 D WifiDisplayController:  wps: 0
09-09 13:41:01.806  1259  1417 D WifiDisplayController:  grpcapab: 0
09-09 13:41:01.806  1259  1417 D WifiDisplayController:  devcapab: 0
09-09 13:41:01.806  1259  1417 D WifiDisplayController:  status: 3
09-09 13:41:01.806  1259  1417 D WifiDisplayController:  wfdInfo: null
09-09 13:41:01.806  1259  1417 D WifiDisplayController:  groupownerAddress: null
09-09 13:41:01.806  1259  1417 D WifiDisplayController:  GOdeviceName: null
09-09 13:41:01.806  1259  1417 D WifiDisplayController:  interfaceAddress: 
09-09 13:41:01.806  1259  1417 D WifiDisplayController:  SConnectInfo : null
09-09 13:41:01.806  1259  1417 D WifiDisplayController:  contactInfoHash : null
09-09 13:41:01.806  1259  1417 D WifiDisplayController:  ssDevInfo : 0
09-09 13:41:01.806  1259  1417 D WifiDisplayController:  iconIdx : 0
,09-09 13:41:01.816  6229  6240 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
09-09 13:41:01.816  6229  6240 D HotspotProvider: CREDENTIAL
09-09 13:41:01.816  6229  6240 D HotspotProvider: No prepend tags
,09-09 13:41:01.816  1259  1625 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
09-09 13:41:01.816  1259  1625 D HS20StateMachine: enter : DiscoveringState
,09-09 13:41:01.816  1259  1259 I ActivityManager: Killing 5704:com.android.defcontainer/u0a6 (adj 15): DHA:empty #31
,09-09 13:41:01.826  1259  1622 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-09 13:41:01.826  1259  1622 D WifiP2pService: InactiveState
09-09 13:41:01.826  1259  1622 D WifiP2pService: InactiveState{ what=143376 }
,09-09 13:41:01.826  1259  1622 D WifiP2pService: P2pEnabledState{ what=143376 }
09-09 13:41:01.826  1259  1622 E WifiP2pService: Airplane mode : skipped SET_COUNTRY_CODE
,09-09 13:41:01.906  1259  1853 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5704 ,hash=131538473 ,name=com.android.defcontainer
09-09 13:41:01.906  1259  1853 D ActivityManager: isAutoRunBlockedApp:: com.android.defcontainer, Auto Run ON
,09-09 13:41:02.066  5955  6098 E io.jxcore.node.ConnectivityMonitorTest: Wifi state didn't after 5s!
09-09 13:41:02.066  5955  6005 D BluetoothAdapter: enable()
,09-09 13:41:02.076  5955  6005 D BluetoothAdapter: enable(): BT is already enabled..!
,09-09 13:41:02.076  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ce5af50 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1f7ee83 2608:com.samsung.android.providers.context/u0a5}
,09-09 13:41:02.146  1259  3546 D SSRM:s  : SIOP:: AP = 360, PST = 384 (W:11), CP = 43, LCD = 0
,09-09 13:41:02.146  1259  3546 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-09 13:41:02.206  2970  2970 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
09-09 13:41:02.206  2970  2970 I WCNSS_FILTER: do_write: IBS write: fc
,09-09 13:41:02.216  2569  3029 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
09-09 13:41:02.216  2569  3029 E bt_btif_sock_rfcomm: SDP - Failed to look up a channel number to connect to
09-09 13:41:02.216  2569  3029 W bt_btif : bta_dm_acl_change(), event : 2
09-09 13:41:02.216  2569  3029 W bt_btif : bta_dm_acl_change(), event : 5
09-09 13:41:02.216  2569  3146 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 7
,09-09 13:41:02.216  5955  6024 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 212)
09-09 13:41:02.216  1259  2629 V AlarmManager:  remove PendingIntent] PendingIntent{1163549: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:02.216  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 14 : bytes_written: 14
,09-09 13:41:02.226  1259  2621 V AlarmManager:  remove PendingIntent] PendingIntent{a271e4e: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:02.226  2569  2730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b2cb7b
09-09 13:41:02.226  1259  1987 V AlarmManager:  remove PendingIntent] PendingIntent{c37db6f: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:02.226  2569  2739 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 1
,09-09 13:41:02.226  2569  2739 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 13:41:02.226  2569  2739 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 241
09-09 13:41:02.226  1694  2072 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
,09-09 13:41:02.246  2970  2970 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-09 13:41:02.396  1259  2008 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-09 13:41:02.396  1259  2008 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4386, temperature: 322, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-09 13:41:02.396  1259  2008 D BatteryService: online:4, current avg:141, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:148
09-09 13:41:02.396  1259  1259 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 13:41:02.396  1694  1694 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-09 13:41:02.396  1694  1694 D PowerUI : priorPlugType = 2 mPlugType =  2
09-09 13:41:02.396  1694  1694 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 13:41:02.406  2569  2569 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-09 13:41:02.406  2569  3088 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-09 13:41:02.416  1694  1694 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-09 13:41:02.416  1694  1694 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-09 13:41:02.416  1694  1694 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-09 13:41:02.596   720   720 I MSM-irqbalance: Decided to move IRQ155 from CPU3 to CPU1
,09-09 13:41:02.726  2569  2730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b2cb7b
,09-09 13:41:02.736  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f7e707c u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1f7ee83 2608:com.samsung.android.providers.context/u0a5}
,09-09 13:41:02.826  6221  6221 I wpa_supplicant: nl80211: Received scan results (15 BSSes)
,09-09 13:41:02.836  6221  6221 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
09-09 13:41:02.836  6221  6221 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
09-09 13:41:02.836  6221  6221 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-09 13:41:02.836  6221  6221 I wpa_supplicant:    allow  - level is under -85dBm [-44] or selected nid [-1] [0]
,09-09 13:41:02.836  6221  6221 I wpa_supplicant:  selected from pick network BSS F4.99.3E ssid='NG700' et= 090,gp=03,cu=987654321,sc=987654321
09-09 13:41:02.836  6221  6221 I wpa_supplicant:    allow  - level is under -85dBm [-44] or selected nid [-1] [0]
09-09 13:41:02.836  6221  6221 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
09-09 13:41:02.836  1259  6227 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-09 13:41:02.856  1259  1623 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-09 13:41:02.866  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b03dd05 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8b6b662 1694:com.android.systemui/u0a46}
,09-09 13:41:02.866  1259  2124 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-09 13:41:02.866  1259  2124 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 5, Mac address valid: false, AP MAC address: [00:00:00:00:00:00], Wifi-Ap SSID Valid: false, SSID: 
,09-09 13:41:02.916   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 320
09-09 13:41:02.916   552  1406 D Netd    : Iface wlan0 link down
09-09 13:41:02.916   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:02.916   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 188
09-09 13:41:02.916   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:02.916   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 72
09-09 13:41:02.916   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:02.916   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:02.916   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:41:02.916   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=15 Family=0 Type=0x1 Change=[0x0] Flags=[0x1003]UP BROADCAST MULTICAST 
09-09 13:41:02.916   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:41:02.916   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:41:02.916   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 15, disable link
09-09 13:41:02.916   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:02.916   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:41:02.916   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=15 Family=0 Type=0x1 Change=[0x0] Flags=[0x1003]UP BROADCAST MULTICAST 
09-09 13:41:02.916   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:41:02.916   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:41:02.916   552  1406 D Netd    : Iface wlan0 link down
09-09 13:41:02.916   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 15, disable link
09-09 13:41:02.916   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:02.916   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:41:02.916   552  1406 D Netd    : Iface wlan0 link down
09-09 13:41:02.916   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=15 Family=0 Type=0x1 Change=[0x0] Flags=[0x1003]UP BROADCAST MULTICAST 
09-09 13:41:02.916   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:41:02.916   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:41:02.916   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 15, disable link
,09-09 13:41:02.916   552  1406 D Netd    : Iface wlan0 link up,
,09-09 13:41:02.916   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-09 13:41:02.916   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:02.916   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:02.916   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:41:02.916   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=15 Family=0 Type=0x1 Change=[0x0] Flags=[0x11003]UP BROADCAST MULTICAST LOWER_UP 
09-09 13:41:02.916   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:41:02.916   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:41:02.916   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 15, disable link
09-09 13:41:02.916  6221  6221 E wpa_supplicant: Cmd 35605 not handled
,09-09 13:41:02.916  1259  1416 D Tethering: enter TetherInterfaceSM  and send tetherstatechangebroadcast
09-09 13:41:02.916  1259  1416 D Tethering: NAP Supported and not Wifi Model
09-09 13:41:02.916  6221  6221 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-09 13:41:02.926  1259  1416 E Tethering: No numeric data
,09-09 13:41:02.926  1259  1416 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-09 13:41:02.926  1259  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:02.926  1259  1620 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:41:02.926  1694  1694 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-09 13:41:02.926  1694  1694 D HotspotTile: updateTetherState():false, false
,09-09 13:41:02.926  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f725314 u-1 android.net.conn.TETHER_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a8d25ef 1259:system/1000}
09-09 13:41:02.926  1259  1623 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
09-09 13:41:02.926  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:02.926  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:02.926  1259  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:02.926  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:02.926  1259  1620 D NetworkStatsRecorder: entry.iface is null
,09-09 13:41:02.926  1259  1620 V NetworkStats: performPollLocked() took 5ms
,09-09 13:41:02.936  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:02.936  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:02.936  1259  2124 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
,09-09 13:41:02.936  1259  2124 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 6, Mac address valid: false, AP MAC address: [00:00:00:00:00:00], Wifi-Ap SSID Valid: false, SSID: 
,09-09 13:41:03.916  6221  6221 I wpa_supplicant: wlan0: WPA: RX message 1 of 4-Way Handshake from F4.99.3E (ver=2)
,09-09 13:41:03.916  6221  6221 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 2/4
,09-09 13:41:03.926  1259  1623 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-09 13:41:03.926  1259  2124 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-09 13:41:03.926  1259  2124 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 7, Mac address valid: false, AP MAC address: [00:00:00:00:00:00], Wifi-Ap SSID Valid: false, SSID: 
,09-09 13:41:03.926  6221  6221 I wpa_supplicant: wlan0: WPA: RX message 3 of 4-Way Handshake from F4.99.3E (ver=2)
,09-09 13:41:03.926  6221  6221 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 4/4
,09-09 13:41:03.936  6221  6221 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 13:41:03.936  6221  6221 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-09 13:41:03.936  6221  6221 I wpa_supplicant: Blacklist: Clear (temp) 
09-09 13:41:03.936   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-09 13:41:03.936   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:03.936   552  1406 D Netd    : Iface wlan0 link up
09-09 13:41:03.936   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:03.936   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:41:03.936   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=15 Family=0 Type=0x1 Change=[0x0] Flags=[0x11043]UP BROADCAST RUNNING MULTICAST LOWER_UP 
09-09 13:41:03.936   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:41:03.936   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:41:03.936   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 15, disable link
,09-09 13:41:03.936  1259  1623 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-09 13:41:03.956  1259  1623 V AlarmManager:  remove PendingIntent] PendingIntent{3c13edd: PendingIntentRecord{65d4a52 android broadcastIntent}}
,09-09 13:41:03.956  1259  1623 D WifiNetworkAgent: NetworkAgent: Registering NetworkAgent
,09-09 13:41:03.956  1259  1623 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-09 13:41:03.956  1259  1630 E ConnectivityService: updateNetworkInfo()
09-09 13:41:03.956  1259  1630 D ConnectivityService: Got NetworkAgent Messenger
09-09 13:41:03.956  1259  1630 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:03.956  1259  1630 D ConnectivityService: NetworkAgent connected
09-09 13:41:03.956  1259  1259 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
09-09 13:41:03.956  1259  1259 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-09 13:41:03.956  1259  1259 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
09-09 13:41:03.966  1259  1628 I WifiHs20Service: Message received 5007
,09-09 13:41:03.966   552  1413 D CommandListener: Setting iface cfg
,09-09 13:41:03.966  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-09 13:41:03.966  1974  1974 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,09-09 13:41:03.976  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b1e6b98 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{54b8953 6035:com.sec.android.diagmonagent/1000}
,09-09 13:41:03.976  6035  6035 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:03.976  6035  6035 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
09-09 13:41:03.976  6035  6035 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
09-09 13:41:03.976  1259  1623 D WifiStateMachine: Start Dhcp Watchdog 2
09-09 13:41:03.976  6035  6035 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
09-09 13:41:03.976  1259  2008 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b1e6b98 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a6a9da7 6058:com.sec.app.RilErrorNotifier/1000}
,09-09 13:41:03.976  1259  1623 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
09-09 13:41:03.976  6058  6058 I PhoneErrorReceiver: onReceive
09-09 13:41:03.976  6058  6058 I MIPErrReceiver: isWiFiConnected
,09-09 13:41:03.976  1259  1987 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-09 13:41:03.986  1259  1623 D WifiNetworkAgent: NetworkAgent: NetworkAgent fully connected
09-09 13:41:03.986  1259  2124 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-09 13:41:03.986  1259  2124 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 8, Mac address valid: false, AP MAC address: [00:00:00:00:00:00], Wifi-Ap SSID Valid: false, SSID: 
,09-09 13:41:03.986  1259  1630 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,09-09 13:41:03.986  1259  1325 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b1e6b98 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8c16b67 5671:com.enhance.gameservice/u0a79}
,09-09 13:41:03.986  1259  1630 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]
09-09 13:41:03.986  1259  1630 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,09-09 13:41:03.996  1259  1325 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b1e6b98 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f996d43 6074:com.sec.knox.switcher/1000}
,09-09 13:41:03.996  6074  6074 I usagelog: received in receiver
09-09 13:41:03.996  6074  6074 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
09-09 13:41:03.996  6074  6074 I KnoxUsageLogPro: premStatus:2
,09-09 13:41:03.996  6074  6074 I KnoxUsageLogPro: isEulaShown : false
09-09 13:41:03.996  6074  6074 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,09-09 13:41:03.996  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-09 13:41:04.006  1259  1623 E WifiNative-wlan0: do suspend false
,09-09 13:41:04.006  1259  1623 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
09-09 13:41:04.006  1259  1622 D WifiP2pService: InactiveState{ what=143375 }
,09-09 13:41:04.006  1259  1622 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 13:41:04.016  1259  2124 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-09 13:41:04.016  1259  2124 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 9, Mac address valid: true, AP MAC address: [f4:f2:6d:22:99:3e], Wifi-Ap SSID Valid: true, SSID: NG700
,09-09 13:41:04.016  1259  2136 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 131 QMI_LOC_NOTIFY_WIFI_ATTACHMENT_STATUS_REQ_V02
,09-09 13:41:04.026  6244  6244 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-09 13:41:04.026  6244  6244 I dhcpcd  : version 5.5.6 starting,
,09-09 13:41:04.036  6244  6244 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-09 13:41:04.126  6244  6244 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-09 13:41:04.126  6244  6244 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-09 13:41:04.126  6244  6244 I dhcpcd  : bssid match
09-09 13:41:04.126  6244  6244 I dhcpcd  : wlan0: rebinding lease of 192.168.1.106
,09-09 13:41:04.266  6244  6244 I dhcpcd  : wlan0: acknowledged 192.168.1.106 from 192.168.1.1,
,09-09 13:41:04.316  6244  6244 I dhcpcd  : wlan0: leased 192.168.1.106 for 172800 seconds,
09-09 13:41:04.316   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 80
09-09 13:41:04.316   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:04.316   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:04.316   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWADDR
,09-09 13:41:04.316   746  1442 I QC-NETMGR-LIB: Metainfo:  Family=2 PrefixLen=24 Scope=0x0 Index=15 Flags=[0x80]PERMANENT 
09-09 13:41:04.316   746  1442 I QC-NETMGR-LIB: Attribute: PrefixIPv4 addr [192.168.1.106]
09-09 13:41:04.316   746  1442 I QC-NETMGR-LIB: Attribute: LocalIPv4 addr [192.168.1.106]
09-09 13:41:04.316   746  1442 I QC-NETMGR-LIB: Attribute: BroadcastIPv4 addr [192.168.1.255]
09-09 13:41:04.316   746  1442 I QC-NETMGR-LIB: Attribute: Label name wlan0
09-09 13:41:04.316   746  1442 I QC-NETMGR-LIB: Attribute: Address Cache Info - prefered=-1 valid=-1 cstamp=0x2f21 tstamp=0x2f21
,09-09 13:41:04.316   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [20]
09-09 13:41:04.316   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 15
,09-09 13:41:04.326  1259  1630 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false,
,09-09 13:41:04.816  1259  1623 E WifiNative-wlan0: do suspend true
,09-09 13:41:04.816  1259  1630 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,09-09 13:41:04.816  1259  1622 D WifiP2pService: InactiveState{ what=143375 }
09-09 13:41:04.816  1259  1622 D WifiP2pService: P2pEnabledState{ what=143375 }
09-09 13:41:04.816  1259  1623 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-09 13:41:04.816  1259  1623 D WifiStateMachine: VerifyingLinkState enter
09-09 13:41:04.816  1259  1630 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]
,09-09 13:41:04.816  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-09 13:41:04.826  1259  1259 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
,09-09 13:41:04.826  1259  1630 E ConnectivityService: updateNetworkInfo()
,09-09 13:41:04.826  1259  1630 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}, oldLp = null
09-09 13:41:04.826  1259  1630 D ConnectivityService: Adding iface wlan0 to network 503
,09-09 13:41:04.836  1259  1259 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
09-09 13:41:04.836  1259  1259 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-09 13:41:04.836  1259  1259 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
09-09 13:41:04.836  1259  1628 I WifiHs20Service: Message received 5007
,09-09 13:41:04.846  1259  1642 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
09-09 13:41:04.846  1259  1642 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}
09-09 13:41:04.846  1259  1642 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}
09-09 13:41:04.846  1259  1642 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}
09-09 13:41:04.846  1259  1642 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}
,09-09 13:41:04.846  1974  1974 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,09-09 13:41:04.846  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-09 13:41:04.846  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c67bd4f u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{54b8953 6035:com.sec.android.diagmonagent/1000}
09-09 13:41:04.846  1259  1642 I WifiManager: isCaptivePortalException
,09-09 13:41:04.856  1259  1642 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:41:04.856  1259  1642 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:41:04.856  1259  1642 D WifiWatchdogStateMachine: 3Captive portal check should be processed whether SNS option is on or off.
09-09 13:41:04.856  1259  1642 D WifiWatchdogStateMachine.CaptivePortalHandler: [checkCaptivePortal] - callbackHandler=Handler (com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalHandler) {68fc0d3}
09-09 13:41:04.856  1259  1642 I WifiManager: isCaptivePortalException
09-09 13:41:04.856  1259  1642 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:41:04.856  1259  1642 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
,09-09 13:41:04.856  6035  6035 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:04.856  6035  6035 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
09-09 13:41:04.856  6035  6035 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
09-09 13:41:04.856  6035  6035 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
09-09 13:41:04.856  1259  1623 D WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to CONNECTED
,09-09 13:41:04.856  1259  1637 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c67bd4f u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a6a9da7 6058:com.sec.app.RilErrorNotifier/1000}
,09-09 13:41:04.856  6058  6058 I PhoneErrorReceiver: onReceive
,09-09 13:41:04.856  6058  6058 I MIPErrReceiver: isWiFiConnected
,09-09 13:41:04.856  1259  2621 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-09 13:41:04.866  1259  1630 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
,09-09 13:41:04.866  1259  2310 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c67bd4f u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8c16b67 5671:com.enhance.gameservice/u0a79}
,09-09 13:41:04.866  1259  1630 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,09-09 13:41:04.866  1259  1259 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
,09-09 13:41:04.866  1259  1630 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
09-09 13:41:04.866  1259  1623 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 13:41:04.866  1259  1259 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-09 13:41:04.866  1259  1259 I WifiTrafficPoller: mBoosterFLAG : 0
09-09 13:41:04.866  1259  1259 I WifiTrafficPoller: current booster mode : FullMode
09-09 13:41:04.866  1259  1259 I Wifi-SensorMonitor: enable sensor monitoring : true
09-09 13:41:04.866  1259  1623 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 13:41:04.876  1259  1259 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 4096, 8388608
09-09 13:41:04.876  1259  1630 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 13:41:04.876  1259  1259 D SensorHAL: GRIP_WIFI  set_enable 
09-09 13:41:04.876  1259  1630 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
,09-09 13:41:04.876  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-09 13:41:04.876  1974  1974 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
09-09 13:41:04.876  1259  1324 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-09 13:41:04.876  1259  1630 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:04.876  1259  1630 V NetworkStats: updateIfacesLocked()
09-09 13:41:04.876  1259  1630 V NetworkStats: performPollLocked(flags=0x1)
,09-09 13:41:04.886  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:04.886  1259  1630 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:04.886  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:04.886  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:04.886  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:04.886  1259  1630 V NetworkStats: performPollLocked() took 6ms
09-09 13:41:04.886  1259  2629 D SecContentProvider2: query(), uri = 15 selection = getToastGravityEnabledState
,09-09 13:41:04.886  1259  2304 D SecContentProvider2: query(), uri = 15 selection = getToastEnabledState
09-09 13:41:04.886  1259  2008 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c67bd4f u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f996d43 6074:com.sec.knox.switcher/1000}
09-09 13:41:04.886  6074  6074 I usagelog: received in receiver
09-09 13:41:04.886  6074  6074 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
09-09 13:41:04.886  6074  6074 I KnoxUsageLogPro: premStatus:2
,09-09 13:41:04.896  6074  6074 I KnoxUsageLogPro: isEulaShown : false
09-09 13:41:04.896  6074  6074 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
09-09 13:41:04.896  1259  1630 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:04.896  1259  1630 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]
09-09 13:41:04.896  1259  1637 D SecContentProvider2: query(), uri = 15 selection = getToastShowPackageNameState
,09-09 13:41:04.896  1259  1630 D ConnectivityService: Not required to send intent.
09-09 13:41:04.896  1259  1630 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
09-09 13:41:04.896  1259  1630 E ConnectivityService: updateNetworkInfo()
09-09 13:41:04.896  1259  1630 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
,09-09 13:41:04.896  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:04.896  1259  1630 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]
09-09 13:41:04.896  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:04.896  1259  1630 V NetworkStats: updateIfacesLocked()
09-09 13:41:04.896  1259  1630 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:04.896  1259  1630 V NetworkStats: performPollLocked(flags=0x1)
,09-09 13:41:04.896  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:04.896  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:04.896  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:04.896  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:04.896  1259  1630 V NetworkStats: performPollLocked() took 3ms
09-09 13:41:04.896  1259  1630 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:04.896  1259  2310 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4841e5 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{54b8953 6035:com.sec.android.diagmonagent/1000}
,09-09 13:41:04.896  6035  6035 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:04.896  1259  1630 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:04.896  6035  6035 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
09-09 13:41:04.896  6035  6035 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
09-09 13:41:04.896  1259  1630 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]
09-09 13:41:04.896  1259  6242 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:04.896  1259  1630 D ConnectivityService: scheduleUnvalidatedPrompt 503
09-09 13:41:04.896  1259  6242 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Connected
09-09 13:41:04.896  6035  6035 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 android.content.ContextWrapper.sendBroadcast:410 android.content.ContextWrapper.sendBroadcast:410 com.sec.android.diagmonagent.DiagMonConnectivityChangeReciever.onReceive:19 android.app.ActivityThread.handleReceiver:3637 
09-09 13:41:04.896  1259  6242 D NetworkMonitor: registerReceiver Captive portal receiver
09-09 13:41:04.896  1259  1630 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 503]
09-09 13:41:04.896  1259  1623 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-09 13:41:04.896  1259  1630 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
09-09 13:41:04.896  1259  1630 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-09 13:41:04.896  1259  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: true
09-09 13:41:04.896  1259  1623 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 13:41:04.906  1259  1630 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,09-09 13:41:04.906  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:04.906  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:04.906  1259  6242 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:04.906  1259  6242 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Validated
09-09 13:41:04.906  1974  2242 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,09-09 13:41:04.906  1694  2108 D QSTile.WifiTile: handleUpdateState  cb.changed 14 wifiEnabled : ON cb.enabledDesc NG700
09-09 13:41:04.906  1974  2242 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-09 13:41:04.906  1259  1630 D ConnectivityService: currentScore = 0, newScore = 20
09-09 13:41:04.906  1259  1630 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
09-09 13:41:04.906  1259  1630 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 503]
09-09 13:41:04.906  1259  1630 D ConnectivityService:    accepting network in place of null
09-09 13:41:04.906  1259  1630 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 13:41:04.906  1259  1623 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:04.906  1259  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-09 13:41:04.906  1259  1623 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:04.906  1259  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
09-09 13:41:04.906  1259  1651 D Ethernet: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:04.906  1259  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-09 13:41:04.906  1259  1623 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 13:41:04.906  1259  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
09-09 13:41:04.906  1259  1623 D WIFI    : evalRequest
09-09 13:41:04.906  1259  1630 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-09 13:41:04.906  1259  1623 D WIFI    :   done
09-09 13:41:04.906  1259  1651 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
09-09 13:41:04.906  1259  1622 D WIFI_P2P: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:04.906  1259  1623 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:04.906  1259  1651 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 13:41:04.906  1259  1651 D Ethernet: evalRequest
09-09 13:41:04.906  1259  1651 D Ethernet:   done
09-09 13:41:04.906  1259  1622 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:04.906  1259  1623 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:04.906  1259  1622 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 13:41:04.906  1259  1622 D WIFI_P2P: evalRequest
09-09 13:41:04,.906  1259  1622 D WIFI_P2P:   done
09-09 13:41:04.906  1259  1623 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 13:41:04.906  1259  1623 D WIFI    : evalRequest
09-09 13:41:04.906  1259  1623 D WIFI    :   done
09-09 13:41:04.906  1259  1623 D WIFI_UT : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:04.906  1259  1623 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:04.906  1259  1623 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 13:41:04.906  1259  1623 D WIFI_UT : evalRequest
09-09 13:41:04.906  1259  1623 D WIFI_UT :   done
09-09 13:41:04.906  1259  1259 D SensorHAL: sx9310_grip_wifi: power-on.
09-09 13:41:04.906  1259  2294 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4841e5 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a6a9da7 6058:com.sec.app.RilErrorNotifier/1000}
09-09 13:41:04.906  1259  1259 D SensorManager: registerListener :: 17, SX9310 Grip Sensor wifi, 200000, 0,  
09-09 13:41:04.906  1259  1259 I Wifi-SensorMonitor: disable powerbackoff
09-09 13:41:04.906  1259  1259 D WifiNative-wlan0: callSECApiInt - ID [70]
09-09 13:41:04.906  1259  1259 D WifiNative-wlan0: callSECApiVoid - ID [212]
09-09 13:41:04.906  6221  6221 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-09 13:41:04.906  6221  6221 I wpa_supplicant: P2P: Current p2p state = IDLE
09-09 13:41:04.906  6058  6058 I PhoneErrorReceiver: onReceive
09-09 13:41:04.906  6058  6058 I MIPErrReceiver: isWiFiConnected
09-09 13:41:04.906  6221  6221 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-09 13:41:04.906  1259  2621 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-09 13:41:04.906  1259  1259 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
09-09 13:41:04.906  1259  1259 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-09 13:41:04.906  1694  2072 D ViewRootImpl: #1 mView = android.widget.LinearLayout{96e0187 V.E...... ......I. 0,0-0,0 #102039d android:id/toast_layout_root}
09-09 13:41:04.906  1259  1259 D HS20StateMachine: SSID : "NG700"
09-09 13:41:04.906  1259  1259 D HS20StateMachine: NetId : 0
,09-09 13:41:04.906  1259  1259 D HS20StateMachine: checkifOSUAP  null
09-09 13:41:04.906  1259  1259 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
09-09 13:41:04.906  1259  1628 I WifiHs20Service: Message received 5007
,09-09 13:41:04.916  1259  1853 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4841e5 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8c16b67 5671:com.enhance.gameservice/u0a79}
,09-09 13:41:04.916  1259  1987 V MARsPolicyManager: handelAlertToastWindowStarted pkgName = com.android.systemui
,09-09 13:41:04.916  1259  2629 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4841e5 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f996d43 6074:com.sec.knox.switcher/1000}
,09-09 13:41:04.926  6074  6074 I usagelog: received in receiver
,09-09 13:41:04.926  6074  6074 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
09-09 13:41:04.926  6074  6074 I KnoxUsageLogPro: premStatus:2
09-09 13:41:04.926  6074  6074 I KnoxUsageLogPro: isEulaShown : false
,09-09 13:41:04.926  6074  6074 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,09-09 13:41:04.926  1259  2008 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{185c89d u0 com.sec.android.diagmonagent.intent.NETWORK_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{54b8953 6035:com.sec.android.diagmonagent/1000}
,09-09 13:41:04.926  6035  6035 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: com.sec.android.diagmonagent.intent.NETWORK_CHANGED
,09-09 13:41:04.926   552  1413 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-09 13:41:04.926   443   443 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=4, Uoast
,09-09 13:41:04.926  6035  6035 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
,09-09 13:41:04.936  6035  6035 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(67/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,09-09 13:41:04.936  1694  1694 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 148
,09-09 13:41:04.936  1259  2294 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1259
,09-09 13:41:04.946   552  1413 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 13:41:04.946  1694  2072 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,09-09 13:41:04.956  1259  1416 D EntConnectivity: Not allowed due to - mEnabled false
,09-09 13:41:04.956  1259  1630 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:04.956  1259  1630 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 13:41:04.956  1259  1630 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=5, legacyType=-1, [] ]
09-09 13:41:04.956  1259  1630 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } for legacy network type 1
09-09 13:41:04.956  1259  1630 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
09-09 13:41:04.956  1259  1630 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:04.956  1259  2304 D ConnectivityService: getVpnConfig > userId : 0
,09-09 13:41:04.956  1259  1416 D EntConnectivity: Not allowed due to - mEnabled false
,09-09 13:41:04.956  1259  1630 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 13:41:04.956  1259  1630 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-09 13:41:04.956  1259  1416 D Tethering: MasterInitialState.processMessage what=3
,09-09 13:41:04.956  1259  1259 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-09 13:41:04.956  1259  1630 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/1259 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:04.956  1259  1630 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
,09-09 13:41:04.966   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 64
09-09 13:41:04.966  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:04.966   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:04.966  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:04.966   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:04.966  1259  1630 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:04.966   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWADDR
09-09 13:41:04.966  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
09-09 13:41:04.966   746  1442 I QC-NETMGR-LIB: Metainfo:  Family=10 PrefixLen=64 Scope=0xfd Index=15 Flags=[0x80]PERMANENT 
09-09 13:41:04.966  1259  1630 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=5, legacyType=-1, [] ]
09-09 13:41:04.966   746  1442 I QC-NETMGR-LIB: Attribute: PrefixIPv6 addr [fe80:0000:0000:0000:4678:3eff:feeb:95ef]
09-09 13:41:04.966  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:04.966   746  1442 I QC-NETMGR-LIB: Attribute: Address Cache Info - prefered=-1 valid=-1 cstamp=0x2efd tstamp=0x2efd
09-09 13:41:04.966  1259  1630 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:04.966   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [20]
09-09 13:41:04.966  1259  1630 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-09 13:41:04.966   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 15
09-09 13:41:04.966  1259  1630 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] validation  passed
09-09 13:41:04.966  1259  1630 D ConnectivityService: EVENT_PROVISIONING_NOTIFICATION is sent for TYPE_MOBILE.
09-09 13:41:04.966  1259  1874 V AlarmManager:  remove PendingIntent] PendingIntent{39adc39: PendingIntentRecord{51f527e android broadcastIntent}}
09-09 13:41:04.966  1259  1630 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]
09-09 13:41:04.966  1259  1259 D LocSvc_java: onReceive
09-09 13:41:04.966  1259  1630 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
09-09 13:41:04.966  1259  1259 D LocSvc_java: got connectivity action
09-09 13:41:04.966  1259  1630 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePorta,lDetected{false} }
09-09 13:41:04.966  1259  1259 D LocSvc_java: Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
09-09 13:41:04.966  1259  1630 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
09-09 13:41:04.966  1259  1259 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-09 13:41:04.966  1259  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-09 13:41:04.966  1259  1259 D LocSvc_java: handleMessage msg = 4
09-09 13:41:04.966  1259  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
09-09 13:41:04.966  1259  1259 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 13:41:04.966  1259  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-09 13:41:04.966  1259  1259 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true] info.getType():1
09-09 13:41:04.966  1259  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
09-09 13:41:04.966  1259  1630 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 13:41:04.966  1259  1630 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} },
,09-09 13:41:04.966  1259  1651 D Ethernet: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 13:41:04.966  1259  1630 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/1259 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:04.966  1259  1651 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
09-09 13:41:04.966  1259  1630 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
09-09 13:41:04.966  1259  1651 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 13:41:04.966  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:04.966  1259  1651 D Ethernet: evalRequest
09-09 13:41:04.966  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:04.966  1259  1651 D Ethernet:   done
,09-09 13:41:04.966  1259  1630 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:04.966  1259  1622 D WIFI_P2P: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:04.966  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
09-09 13:41:04.966  1259  1622 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:04.966  1259  1630 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
09-09 13:41:04.966  1259  1622 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 13:41:04.966  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 13:41:04.966  1259  1622 D WIFI_P2P: evalRequest
09-09 13:41:04.966  1259  1630 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:04.966  1259  1622 D WIFI_P2P:   done
09-09 13:41:04.966  1259  1630 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:04.966  1259  1630 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-09 13:41:04.976  1259  1631 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
09-09 13:41:04.976  1974  2242 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
09-09 13:41:04.976  1259  1259 V MARsPolicyManager: DataConnection: true
09-09 13:41:04.976  1974  2242 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-09 13:41:04.976  1259  1631 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
09-09 13:41:04.976  3109  3109 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@3390fb1 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-09 13:41:04.976  3109  3109 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-09 13:41:04.986  1259  1378 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:04.986  1259  1378 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-09 13:41:04.986  1259  1378 D GpsLocationProvider: handleMessage msg = 4
09-09 13:41:04.986  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:04.986  1259  1621 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:04.986  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:04.986  1259  1621 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]
09-09 13:41:04.986  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:04.986  1259  1621 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-09 13:41:04.986  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:04.986  1974  2242 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
09-09 13:41:04.986  1974  2242 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-09 13:41:04.986  1259  2320 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-09 13:41:04.986  1259  1378 D TelephonyManager: getDataEnabled: retVal=true
09-09 13:41:04.996  1259  1630 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,fe80::4678:3eff:feeb:95ef/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}
09-09 13:41:04.996  1259  1630 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
09-09 13:41:04.996  5955  5955 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
09-09 13:41:04.996  1259  1630 D ConnectivityService: identical MTU - not setting
09-09 13:41:04.996  1259  1630 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:04.996  1259  1630 V NetworkStats: updateIfacesLocked()
09-09 13:41:04.996  1259  1630 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:41:04.996  1259  2008 V WindowStateAnimator: Finishing drawing window Window{2980747 u0 d0 Toast}: mDrawState=DRAW_PENDING
09-09 13:41:04.996  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-09 13:41:04.996  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:04.996  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:04.996  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:04.996  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:04.996  1259  1630 V NetworkStats: performPollLocked() took 4ms
09-09 13:41:04.996  1259  1630 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:04.996  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-09 13:41:05.006  5955  5955 D BluetoothAdapter: STATE_ON
09-09 13:41:05.006  1259  1623 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:05.006  1259  1623 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:05.006  1259  1623 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 13:41:05.006  1259  1623 D WIFI    : evalRequest
09-09 13:41:05.006  1259  1623 D WIFI    :   done
09-09 13:41:05.006  1974  1988 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@609e42c, selection=nullselectionArgs=null, sort=name ASC
09-09 13:41:05.006  1259  1623 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:05.006  1259  1623 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:05.006  1259  1623 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 13:41:05.006  1259  1623 D WIFI    : evalRequest
09-09 13:41:05.006  1259  1623 D WIFI    :   done
09-09 13:41:05.006  1259  1623 D WIFI_UT : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:05.006  1259  1623 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:05.006  1259  1623 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 13:41:05.006  1259  1623 D WIFI_UT : evalRequest
09-09 13:41:05.006  1259  1623 D WIFI_UT :   done
09-09 13:41:05.006  1259  1623 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(VALID)
09-09 13:41:05.006  1259  1623 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(1)
,09-09 13:41:05.006  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:05.006  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:05.006  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:05.006  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:05.006  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:05.006  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:05.006  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:05.006  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:05.006  1259  1259 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-09 13:41:05.006  1259  1630 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:05.006  1259  1630 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]
09-09 13:41:05.006  1259  1630 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
09-09 13:41:05.006  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:05.006  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:05.006  1259  1630 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:05.006  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
09-09 13:41:05.006  2137  2223 W System  : ClassLoader referenced unknown path: /system/priv-app/Velvet/lib/arm64
09-09 13:41:05.006  1259  1630 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
09-09 13:41:05.006  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:05.006  1974  1988 D TelephonyProvider: query: match = 5
09-09 13:41:05.006  1259  1630 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:05.006  1259  1630 D ConnectivityService: Not required to send intent.
09-09 13:41:05.006  1259  1630 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
09-09 13:41:05.006  5955  5955 D BluetoothAdapter: STATE_ON
09-09 13:41:05.006  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:05.006  1974  1988 D TelephonyProvider: getPreferredApnId(subId = 2147483643),return -1
09-09 13:41:05.006  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:05.006  1974  1988 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
09-09 13:41:05.006  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:05.006  1259  1630 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:05.006  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:05.006  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
09-09 13:41:05.006  1259  1630 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
09-09 13:41:05.006  1259  1623 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:41:05.006  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:05.006  1259  1623 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:41:05.006  1259  1623 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
09-09 13:41:05.006  1259  1630 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:05.016  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:05.016  1259  1623 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:41:05.016  1259  1623 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:41:05.016  1694  2072 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-09 13:41:05.016  1694  2072 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
09-09 13:41:05.016  6102  6113 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(47/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
09-09 13:41:05.016  5955  5955 D BluetoothAdapter: STATE_ON
09-09 13:41:05.016  6102  6113 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(47/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
09-09 13:41:05.026  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:05.026  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:05.026  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:05.026  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:05.026  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:05.026  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:05.026  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:05.026  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:05.026  6102  6113 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(43/llIIIIlllllIIllIIllI)] already Eula Agree
09-09 13:41:05.026  5955  5955 D BluetoothAdapter: STATE_ON
09-09 13:41:05.026  1259  1378 E GpsLocationProvider: No APN found to select.
09-09 13:41:05.026  6102  6112 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(47/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
09-09 13:41:05.026  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:05.026  6102  6112 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(47/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
09-09 13:41:05.026  6102  6112 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(43/llIIIIlllllIIllIIllI)] already Eula Agree
09-09 13:41:05.036  5955  5955 D BluetoothAdapter: STATE_ON
09-09 13:41:05.036  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:05.036  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:05.036  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:05.036  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:05.036  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:05.036  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:05.036  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:05.036  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:05.036  5955  5955 D BluetoothAdapter: STATE_ON
09-09 13:41:05.036  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:05.046  1259  2294 I ActivityManager: Start proc 6287:com.sec.android.soagent/1000 for content provider com.sec.android.soagent/.log.MasterLogProvider
09-09 13:41:05.046  6287  6287 E Zygote  : v2
09-09 13:41:05.046  6287  6287 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:41:05.046  6287  6287 I libpersona: KNOX_SDCARD not a persona
09-09 13:41:05.046  6287  6287 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-09 13:41:05.046  6287  6287 E Zygote  : accessInfo : 0
,09-09 13:41:05.056  1259  3576 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
09-09 13:41:05.066  6287  6287 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:41:05.066  6287  6287 D ActivityThread: Added TimaKeyStore provider
09-09 13:41:05.086  6287  6287 W System  : ClassLoader referenced unknown path: /system/priv-app/SOAgent/lib/arm64
,09-09 13:41:05.116  1259  1987 I ActivityManager: Killing 5798:com.google.android.partnersetup/u0a14 (adj 15): DHA:empty #31
,09-09 13:41:05.126  1259  1987 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e974ae0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a8d25ef 1259:system/1000}
,09-09 13:41:05.126  1259  1259 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e974ae0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3be25b9 2236:com.google.android.gms/u0a10}
,09-09 13:41:05.136  2236  2236 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 13:41:05.136  2236  3189 I iu.UploadsManager: num queued entries: 0
09-09 13:41:05.136  2236  3189 I iu.UploadsManager: num updated entries: 0
,09-09 13:41:05.136  2236  3189 I iu.SyncManager: NEXT; no task
09-09 13:41:05.136  1259  1853 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e974ae0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3be25b9 2236:com.google.android.gms/u0a10}
,09-09 13:41:05.136  1259  1989 D ActivityManager: isAutoRunBlockedApp:: com.google.android.partnersetup, Auto Run ON
09-09 13:41:05.136  1259  1989 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5798 ,hash=181534901 ,name=com.google.android.partnersetup
,09-09 13:41:05.146  1259  2320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e974ae0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fadd615 1868:com.google.android.gms.persistent/u0a10}
,09-09 13:41:05.146  1259  1637 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e974ae0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{41777ec 6102:com.policydm/1000}
,09-09 13:41:05.156   552  1409 D EnterpriseController: netId is 0
09-09 13:41:05.156   552  1409 D Netd    : getNetworkForDns: using netid 503 for uid 10010
,09-09 13:41:05.156  1259  1646 D WifiWatchdogStateMachine.CaptivePortalHandler: start check captive portal 
,09-09 13:41:05.156  6102  6102 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,09-09 13:41:05.166  6102  6102 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,09-09 13:41:05.166  6102  6102 I DBG_POLICYDM: [com.policydm.XDMService(574/llIlIllllllllllllllI)] get NotibarState : 0
,09-09 13:41:05.166  1259  2310 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e974ae0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{41777ec 6102:com.policydm/1000}
,09-09 13:41:05.166  6102  6102 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:05.186  6102  6102 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(87/llllIIIllIlIIIIllllI)] device register flag at setting DB : true
,09-09 13:41:05.186  6102  6102 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(96/onReceive)] Already device registered...
,09-09 13:41:05.196  6102  6102 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(87/llllIIIllIlIIIIllllI)] device register flag at setting DB : true
,09-09 13:41:05.196  6102  6102 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(337/lllIlIlIIIllIIlIllIl)] OMC not Supported model
,09-09 13:41:05.196  6102  6102 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(110/llIlIIIIlIIIIIlIlIII)] Polling time is vaild
,09-09 13:41:05.206  6102  6102 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(277/llIIIIlllllIIllIIllI)] Heartbeat settings is activated.
,09-09 13:41:05.206  6102  6102 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(49/llllIIIllIlIIIIllllI)] Next heartbeat time:2016/09/17/23:24:10
,09-09 13:41:05.206  6102  6102 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(52/llllIIIllIlIIIIllllI)] heartbeat time is vaild
,09-09 13:41:05.216  1259  1385 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e974ae0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{56d884 6129:com.osp.app.signin/u0a27}
,09-09 13:41:05.216  6129  6129 I SA      : [OR] onReceive log=[SA = 2.2.01-51 V = 23 HWD = 2048X1536 2.0 dpi = 320  SIZE = 4 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = gts28velte P = gts28veltexx I = MMB29M M = SM-T719 OKLEFT false DIS MMB29M.T719XXU1APF6 PSS = 8.00525302084415  ]
09-09 13:41:05.216  6129  6129 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
09-09 13:41:05.216  6129  6129 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-09 13:41:05.226  6129  6129 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-09 13:41:05.226  6129  6129 I SA      : [OR] == isSIMCardReady false ==
,09-09 13:41:05.226  6129  6129 I SA      : [SCU] == networkStateCheck == true
,09-09 13:41:05.226  6129  6129 I SA      : [DM] getCountryCodeFromCSC : PL
09-09 13:41:05.226  6129  6129 I SA      : isChinaCountryCode : false
09-09 13:41:05.226  6129  6129 I SA      : [SCU] is ChinestModel Data Restricted   : false
09-09 13:41:05.226  6129  6129 I SA      : [OR] == networkStateCheck true ==
,09-09 13:41:05.226  6129  6129 I SA      : [OR] GetMyCountryZoneTask
,09-09 13:41:05.226  6129  6129 I SA      : [OR] onReceive END
,09-09 13:41:05.226  6129  6303 I SA      : [SRS] prepareGetMyCountryZone
09-09 13:41:05.226  1259  1721 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e974ae0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5827062 5955:com.test.thalitest/u0a136}
,09-09 13:41:05.236  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:05.236  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-09 13:41:05.236  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:05.236  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:05.236  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:05.236  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:05.236  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:05.236  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:05.236  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:05.236  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:05.236  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:05.236  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:05.236  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:05.236  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:05.236  1259  1853 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-09 13:41:05.236  1259  1637 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e974ae0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1ce268a 5214:com.wssyncmldm/1000}
,09-09 13:41:05.236  6129  6303 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-09 13:41:05.236  6129  6303 I SA      : [SSP] query invoked
,09-09 13:41:05.246  6129  6303 I SA      : [TPMU] GetMccFromDB : null
09-09 13:41:05.246  6129  6303 I SA      : [SCU] getMccFromPreferece mcc = 260
09-09 13:41:05.246  6129  6303 I SA      : [LBE] isSupportCheckDomainRegion : true
09-09 13:41:05.246  6129  6303 I SA      : [TPM] isNoProxy(default) : true
,09-09 13:41:05.246  1259  2310 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e974ae0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a6a9da7 6058:com.sec.app.RilErrorNotifier/1000}
09-09 13:41:05.246  6058  6058 I PhoneErrorReceiver: onReceive
09-09 13:41:05.246  6058  6058 V PhoneErrorReceiver: beginStartingService
09-09 13:41:05.246  6058  6058 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1311 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.sec.app.RilErrorNotifier.PhoneErrorReceiver.beginStartingService:194 com.sec.app.RilErrorNotifier.PhoneErrorReceiver.onReceiveWithPrivilege:171 
,09-09 13:41:05.246  5214  6305 I FOTA_AGENT: [com.samsung.android.app.fotaclient.llIlIIIIlIIIIIlIlIII(87/llIIIIlllllIIllIIllI)] Nothing to do action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:05.256  6058  6058 V PhoneErrService: Creating SmsReceiverService
09-09 13:41:05.256  6058  6058 V MIP_PhoneErrService: mTelephonyManager is not null
,09-09 13:41:05.256  6129  6303 I System.out: (HTTPLog)-Static: Hongbao
,09-09 13:41:05.256  1259  2008 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e974ae0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ace8b17 4424:com.sec.spp.push/u0a26}
,09-09 13:41:05.256  4424  4424 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:05.256  4424  4424 E SPPClientService: [SystemStateMoniter] Current Time : 121583
,09-09 13:41:05.256  4424  4424 E SPPClientService: [SystemStateMoniter] No Connect : false
,09-09 13:41:05.256  1259  1853 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e974ae0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ce11b0e 2481:android.process.media/u0a33}
,09-09 13:41:05.266  2481  2481 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:05.266  6058  6058 V PhoneErrService: Starting #1: Bundle[mParcelledData.dataSize=388]
,09-09 13:41:05.266  6058  6058 I PhoneErrService: mResultCode: 0
09-09 13:41:05.266  6058  6058 V MIP_PhoneErrService: onDataConnectionState : -1
09-09 13:41:05.266  6058  6306 V PhoneErrService: Handling incoming message: { when=0 what=0 arg1=1 obj=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.sec.app.RilErrorNotifier/.PhoneErrService bqHint=3 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } target=com.sec.app.RilErrorNotifier.PhoneErrService$ServiceHandler }
09-09 13:41:05.266  6058  6306 V PhoneErrorReceiver: finishStartingService
,09-09 13:41:05.266  6058  6058 V PhoneErrService: Destroying PhoneErrorReceiverService
,09-09 13:41:05.276  1259  2294 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e974ae0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6454e69 6147:com.samsung.android.SettingsReceiver/1000}
,09-09 13:41:05.276  1259  2294 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e974ae0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bb1cd0d 2464:com.microsoft.skydrive/u0a93}
,09-09 13:41:05.276  1259  2320 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,09-09 13:41:05.286  1259  2310 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
,09-09 13:41:05.286  1259  2310 D PackageManager: findPreferredActivity: No PreferredActivities set
09-09 13:41:05.286  1259  2310 I PackageManager: No preferred activity: intent should not be shown
,09-09 13:41:05.296  1259  1637 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e974ae0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e6698f 6172:com.google.android.apps.photos/u0a97}
,09-09 13:41:05.296  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dd6350c u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e6698f 6172:com.google.android.apps.photos/u0a97}
,09-09 13:41:05.306  1259  1987 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e974ae0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e6698f 6172:com.google.android.apps.photos/u0a97}
,09-09 13:41:05.316  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{639106a u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e6698f 6172:com.google.android.apps.photos/u0a97}
,09-09 13:41:05.316  1259  2621 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e974ae0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ba36c24 4746:com.sec.android.daemonapp/u0a127}
,09-09 13:41:05.316  4746  4746 D [WeatherWidget(1210)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
,09-09 13:41:05.316  4746  4746 D [WeatherWidget(1210)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78152C254DDD0027D207FA50AD616546E30965FECE0D7B834EEF4B0E211833EA2B]}
,09-09 13:41:05.326  1259  1324 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e974ae0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bd6dd8 5344:com.sec.android.app.samsungapps/u0a9}
,09-09 13:41:05.326  5344  5344 D WaitQueueForNetworkActivate: notifyNetworkActivated
,09-09 13:41:05.326  5344  5344 D hcjo    : AutoUpdateManager:IDLE:execute
,09-09 13:41:05.336  5344  5344 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
09-09 13:41:05.336  5344  5344 D InitializeManagerStateMachine: exit::IDLE
09-09 13:41:05.336  5344  5344 D InitializeManagerStateMachine: entry::NETWORK_CHECK
09-09 13:41:05.336  1259  2304 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-09 13:41:05.336  1259  1987 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-09 13:41:05.336  5344  5344 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
09-09 13:41:05.336  5344  5344 D InitializeManagerStateMachine: exit::NETWORK_CHECK
09-09 13:41:05.336  5344  5344 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
09-09 13:41:05.336  5344  5344 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
09-09 13:41:05.336  5344  5344 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
09-09 13:41:05.336  5344  5344 D InitializeManagerStateMachine: entry::SUCCESS
09-09 13:41:05.336  5344  5344 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,09-09 13:41:05.336  5344  5344 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
09-09 13:41:05.336  5344  5344 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,09-09 13:41:05.336  1259  1324 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-09 13:41:05.336  5344  5344 D InitializeManagerStateMachine: exit::SUCCESS
09-09 13:41:05.336  5344  5344 D InitializeManagerStateMachine: entry::IDLE
,09-09 13:41:05.346  1259  1646 D WifiWatchdogStateMachine.CaptivePortalHandler: result = 0, mCaptivePortalCheckMode = 11, mCouldNotIdentifyCaptivePortalState = true
,09-09 13:41:05.436  1259  1987 V AlarmManager:  remove PendingIntent] PendingIntent{68b5037: PendingIntentRecord{f644eec com.google.android.gms broadcastIntent}}
,09-09 13:41:05.456  6129  6303 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
09-09 13:41:05.456  6129  6303 I System.out: (HTTPLog)-Static: Hongbao
,09-09 13:41:05.466  6129  6303 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
,09-09 13:41:05.466  6129  6303 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-09 13:41:05.466  6129  6303 I System.out: (HTTPLog)-Static: Hongbao
09-09 13:41:05.466  6129  6303 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:41:05.476   552  1409 D EnterpriseController: netId is 0
09-09 13:41:05.476   552  1409 D Netd    : getNetworkForDns: using netid 503 for uid 10027
,09-09 13:41:05.746  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d4c19a4 u0 com.google.android.gcm.CONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9ff3cb0 5496:com.google.android.talk/u0a84}
,09-09 13:41:05.756  1259  1987 V AlarmManager:  remove PendingIntent] PendingIntent{20f130d: PendingIntentRecord{1a062e8 com.google.android.gms broadcastIntent}}
,09-09 13:41:05.956  1259  1630 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-09 13:41:06.456  6129  6303 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 985
,09-09 13:41:06.456  6129  6303 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,09-09 13:41:06.466  6129  6303 I SA      : [OCP] update openData : PL
,09-09 13:41:06.476  6129  6303 I SA      : [TPMU] getNetworkMcc : 
,09-09 13:41:06.486  6129  6303 I SA      : [SCU] saveMccToPreferece Start
09-09 13:41:06.486  6129  6303 I SA      : [SCU] RegionMCC : 260
09-09 13:41:06.486  6129  6303 I SA      : [SSP] query invoked
,09-09 13:41:06.496  6129  6303 I SA      : [TPMU] GetMccFromDB : null
09-09 13:41:06.496  6129  6303 I SA      : [SCU] getMccFromPreferece mcc = 260
09-09 13:41:06.496  6129  6303 I SA      : [SCU] saveMccToPreferece End
09-09 13:41:06.496  6129  6303 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 1034
09-09 13:41:06.496  6129  6303 I SA_HTTPURLCONNECTION: [RC New] Execute end
,09-09 13:41:06.496  6129  6129 I SA      : [OR] GetMyCountryZoneTask mcc = 260
09-09 13:41:06.496  6129  6129 I SA      : [OR] GetMyCountryZoneTask Success
,09-09 13:41:06.906  1694  2072 D ViewRootImpl: #3 mView = null
,09-09 13:41:06.906   443  2007 I SurfaceFlinger: id=20 Removed Uoast (11/14)
,09-09 13:41:06.906   443   466 I SurfaceFlinger: id=20 Removed Uoast (-2/14)
,09-09 13:41:06.916  1259  2294 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1259 (0x0)
09-09 13:41:06.916  1259  2294 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1259, ws=WorkSource{10046}) (elapsedTime=1974)
,09-09 13:41:07.096  5955  6241 E io.jxcore.node.ConnectivityMonitorTest: BT state didn't change after 5s!
,09-09 13:41:07.096  5955  6005 D BluetoothAdapter: disable()
,09-09 13:41:07.096  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{14742c2 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1f7ee83 2608:com.samsung.android.providers.context/u0a5}
,09-09 13:41:07.106  1259  2008 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,09-09 13:41:07.116  1259  1416 D SecContentProvider: insert(), uri = 2
,09-09 13:41:07.116  2569  2730 D BluetoothAdapterState: Current state: ON, message: BLE_TURN_OFF
09-09 13:41:07.116  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:07.116  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:07.116  2569  2730 D BluetoothAdapterProperties: Setting state to 13
09-09 13:41:07.116  2569  2730 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 13:41:07.116  2569  2730 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 13:41:07.116  2569  2730 D BluetoothAdapterService: updateAdapterState state is 13
09-09 13:41:07.116  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:07.116  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:07.116  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:07.116  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:07.116  5955  6005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8cb7be removed from the list
09-09 13:41:07.116  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:07.116  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6da501f removed from the list
09-09 13:41:07.116  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:07.116  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:07.116  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:07.116  5955  6005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:07.116  5955  6005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15891ca added. We now have 3 listener(s)
,09-09 13:41:07.126  2569  2569 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
09-09 13:41:07.126  2569  2730 D BluetoothAdapterService: Autoconnection is available 
09-09 13:41:07.126  2569  2730 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-09 13:41:07.126  2569  2730 D BluetoothAdapterService: terminating service from this receiver
09-09 13:41:07.126  1259  1416 D BluetoothManagerService: Turning On/Off, G state: 3, S state: 3, mBLE count: 0, s BLE count: 0
09-09 13:41:07.126  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-09 13:41:07.126  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:07.126  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:07.126  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:07.126  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5dcf3b added. We now have 3 listener(s)
09-09 13:41:07.126  5955  6005 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:07.126  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:41:07.126  2569  2730 D BluetoothAdapterProperties: onBluetoothDisable()
,09-09 13:41:07.126  2569  2730 W bt_btif : btif_dm_cancel_discovery
09-09 13:41:07.126  1259  1259 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:07.126  1259  1259 I InputMethodManagerService: [BT Setting State] State =13
,09-09 13:41:07.126  1259  2310 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,09-09 13:41:07.126  2039  2039 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:41:07.126  1694  2072 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:07.126  1694  2072 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-09 13:41:07.136  1259  1259 D BluetoothPhoneService: Bluetooth Adapter state : 13
09-09 13:41:07.136  1259  1989 D SecContentProvider: insert(), uri = 2
,09-09 13:41:07.136  2569  2730 I BluetoothAdapterState: Entering PendingCommandState
09-09 13:41:07.136  1259  2310 V AlarmManager:  remove PendingIntent] PendingIntent{5bab8d3: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:07.136  2970  2971 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
,09-09 13:41:07.136  1259  1259 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
09-09 13:41:07.136  1259  1259 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:07.136  1259  1259 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,09-09 13:41:07.146  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b032c10 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{aad911c 5814:com.android.settings/1000}
09-09 13:41:07.146  1694  1694 D BluetoothPbap: Proxy object disconnected
09-09 13:41:07.146  1694  1694 D PbapServerProfile: Bluetooth service disconnected
09-09 13:41:07.146  2970  2971 I WCNSS_FILTER: do_write: IBS write: fd
,09-09 13:41:07.146  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:07.146  5955  5955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:07.146  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:07.146  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:07.146  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:07.146  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:07.146  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:07.146  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:07.146  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:07.146  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:07.146  5955  5955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:07.146  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:07.146  2569  2739 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 13:41:07.146  2569  2739 D BluetoothAdapterProperties: Scan Mode:20
09-09 13:41:07.146  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
,09-09 13:41:07.146  2970  2970 I WCNSS_FILTER: do_write: IBS write: fc
09-09 13:41:07.146  5814  5814 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1311 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 13:41:07.146  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-09 13:41:07.156  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
,09-09 13:41:07.156  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-09 13:41:07.156  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:07.156  5955  6005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:07.156  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:07.156  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:07.156  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:07.156  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:07.156  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:07.156  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:07.156  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:07.156  1259  1721 V AlarmManager:  remove PendingIntent] PendingIntent{cd6f93c: PendingIntentRecord{7e096c5 com.android.bluetooth broadcastIntent}}
,09-09 13:41:07.156  5955  5955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:07.156  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:07.156  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:07.156  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:07.156  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:07.156  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:07.156  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:07.156  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:07.156  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:07.156  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:07.156  5955  6005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:07.156  5955  6005 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:07.156  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:07.156  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:07.156  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:07.156  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:07.156  5955  6005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15891ca removed from the list
09-09 13:41:07.156  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:07.156  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5dcf3b removed from the list
09-09 13:41:07.156  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:07.156  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:07.156  2569  2730 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BEGIN_DISABLE
,09-09 13:41:07.166  5814  5814 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
09-09 13:41:07.166  1259  1324 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-09 13:41:07.166  1694  2108 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
09-09 13:41:07.166  1259  2304 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b032c10 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1f7ee83 2608:com.samsung.android.providers.context/u0a5}
,09-09 13:41:07.166  5955  5955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:07.166  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:07.166  5814  5814 D LocalBluetoothManager: LocalBluetoothManager :: constructor
09-09 13:41:07.166  1259  2304 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b032c10 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fadd615 1868:com.google.android.gms.persistent/u0a10}
,09-09 13:41:07.166  2569  2730 E BluetoothServiceJni: disableBrEdrNative:
09-09 13:41:07.176  1259  1325 V AlarmManager:  remove PendingIntent] PendingIntent{17aebe6: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:07.166  2569  2730 E bt_bluedroid: disable_bredr
09-09 13:41:07.166  5955  6005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:07.166  5955  6005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@55593b1 added. We now have 3 listener(s)
09-09 13:41:07.166  1868  1868 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
09-09 13:41:07.166  5814  5814 D BluetoothEventManager: BluetoothEventManager Constructor :: 
09-09 13:41:07.166  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-09 13:41:07.166  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:07.166  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:07.166  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:07.166  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4560096 added. We now have 3 listener(s)
09-09 13:41:07.166  5955  6005 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:07.166  2569  2732 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-09 13:41:07.166  2569  2732 E bt_btif : BTA_DisableBluetoothOnly
09-09 13:41:07.166  2569  3162 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 13:41:07.166  2569  3162 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-09 13:41:07.166  2569  3029 W bt_btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
09-09 13:41:07.166  2569  3029 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:41:07.166  2569  3163 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 13:41:07.166  2569  3163 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-09 13:41:07.166  2569  3159 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 13:41:07.176  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:07.176  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
09-09 13:41:07.176  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:07.176  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-09 13:41:07.176  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
,09-09 13:41:07.176  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-09 13:41:07.176  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
09-09 13:41:07.176  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:07.176  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:07.176  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-09 13:41:07.176  2569  2732 D IOP_DB_BT: db_close: nbr users 0
09-09 13:41:07.176  2569  2732 D IOP_DB_BT: db_close: free database
09-09 13:41:07.176  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
,09-09 13:41:07.176  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-09 13:41:07.176  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
,09-09 13:41:07.176  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,09-09 13:41:07.176  1259  2304 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b032c10 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{aad911c 5814:com.android.settings/1000}
09-09 13:41:07.186  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:07.186  5955  6005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:07.186  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:07.186  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:07.186  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:07.186  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:07.186  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:07.186  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:07.186  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:07.186  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:07.186  5955  6005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:07.186  5955  6005 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:07.186  5955  6005 D BluetoothAdapter: disable()
,09-09 13:41:07.186  2569  2569 D ObexServerSockets: shutdown(block = true)
09-09 13:41:07.186  2569  2569 D ObexServerSockets: shutdown called from another thread - interrupt().
09-09 13:41:07.186  2569  2569 D ObexServerSockets: shutdown called from another thread - interrupt().
09-09 13:41:07.186  2569  2569 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
09-09 13:41:07.186  2569  2569 D BluetoothSdpJni: SDP Remove record success - handle: 0,
09-09 13:41:07.186  2569  2569 I BtOppRfcommListener: stopping Accept Thread
09-09 13:41:07.186  2569  3159 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 13:41:07.186  2569  3029 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 13:41:07.186  2569  3029 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:41:07.186  2569  3029 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:41:07.186  2569  3029 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:41:07.186  2569  3029 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:41:07.186  2569  3029 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:41:07.186  2569  3029 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:41:07.186  2569  3029 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:41:07.186  1694  1694 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 148
09-09 13:41:07.186  5814  5814 D LocalBluetoothProfileManager: LocalBluetoothProfileManager :: uuid is null
09-09 13:41:07.186  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
09-09 13:41:07.186  5814  5814 D LocalBluetoothProfileManager: PANU : true
09-09 13:41:07.186  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-09 13:41:07.186  2569  2569 V BluetoothOppManager: cleanUp...
09-09 13:41:07.186  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
09-09 13:41:07.186  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:07.186  1259  1987 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
09-09 13:41:07.186  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-09 13:41:07.186  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
09-09 13:41:07.196  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-09 13:41:07.196  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
,09-09 13:41:07.196  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:07.196  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-09 13:41:07.196  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
,09-09 13:41:07.196  5814  5814 D BluetoothSap: Create BluetoothSap proxy object
09-09 13:41:07.196  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,09-09 13:41:07.196  5814  5814 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-09 13:41:07.196  5814  5814 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
,09-09 13:41:07.196  5955  6005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:07.196  5955  6005 D BluetoothAdapter: enable()
,09-09 13:41:07.206  1259  2320 W ActivityManager: Permission Denial: getCurrentUser() from pid=5955, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
09-09 13:41:07.206  1259  2320 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-09 13:41:07.206  1259  2320 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5955, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
09-09 13:41:07.206  1259  2320 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28130)
09-09 13:41:07.206  1259  2320 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2879)
09-09 13:41:07.206  1259  2320 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2869)
09-09 13:41:07.206  1259  2320 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1244)
09-09 13:41:07.206  1259  2320 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:262)
09-09 13:41:07.206  1259  2320 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
09-09 13:41:07.206  1259  2320 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 13:41:07.206  5814  5814 D DockEventReceiver: finishStartingService: stopping service
09-09 13:41:07.206  1259  2320 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,09-09 13:41:07.206  1259  2320 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
09-09 13:41:07.206  5814  5814 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:07.206  5814  5814 D BluetoothStatusReceiver: AdapterStateChanged :: state = 13
09-09 13:41:07.206  5814  5814 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 13:41:07.206  5814  5814 D PanProfile: Bluetooth service connected
,09-09 13:41:07.206  5955  6005 D BluetoothAdapter: BT is in BLE_ON State or TURNING_OFF state
09-09 13:41:07.206  5814  5814 D BluetoothSap: Proxy object connected
09-09 13:41:07.206  5814  5814 D SapProfile: Bluetooth service connected
,09-09 13:41:07.216  1259  2320 I ActivityManager: Start proc 6322:com.samsung.android.intelligenceservice2/5010 for broadcast-3 com.samsung.android.intelligenceservice2/com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor$BtConnectionReceiver
,09-09 13:41:07.216  6322  6322 E Zygote  : v2
09-09 13:41:07.216  6322  6322 I libpersona: KNOX_SDCARD checking this for 5010
09-09 13:41:07.216  6322  6322 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:07.226  6322  6322 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-09 13:41:07.226  6322  6322 E Zygote  : accessInfo : 0
,09-09 13:41:07.226  6322  6322 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.intelligenceservice2 
,09-09 13:41:07.226  2569  2730 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: USER_TURN_ON
,09-09 13:41:07.226  2569  2730 I BluetoothAdapterState: Deferring USER_TURN_ON request...
,09-09 13:41:07.246  6322  6322 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:41:07.246  6322  6322 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:07.256  1259  2621 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b032c10 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f4c1a96 6322:com.samsung.android.intelligenceservice2/5010}
,09-09 13:41:07.266  6322  6322 W System  : ClassLoader referenced unknown path: /system/priv-app/intelligenceservice2/lib/arm64
,09-09 13:41:07.266  6322  6322 D UserAnalysis.Provider: PlaceProvider onCreate()
,09-09 13:41:07.296  6322  6322 D UserAnalysis.Secu: Key for secure DB is newly created
,09-09 13:41:07.296  6322  6322 D UserAnalysis.SDBH: SecurePlaceDbHelper() 
09-09 13:41:07.296  6322  6322 D UserAnalysis: Create SecureDbHelper
,09-09 13:41:07.316  1259  2008 W ActivityManager: Permission Denial: getCurrentUser() from pid=6322, uid=5010 requires android.permission.INTERACT_ACROSS_USERS
,09-09 13:41:07.316  6322  6322 D UserAnalysis.App: onCreate()
,09-09 13:41:07.316  6322  6322 D UserAnalysis.App: no applications having user consent for prediction
,09-09 13:41:07.326  1259  1324 I ActivityManager: Killing 5826:com.samsung.android.provider.shootingmodeprovider/u0a41 (adj 15): DHA:empty #31
,09-09 13:41:07.326  1259  1324 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b032c10 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{871053d 2569:com.android.bluetooth/1002}
,09-09 13:41:07.326  6322  6322 V PlaceDetection v1.0.29 : [PlaceDetection::stopService] Service stopped.
,09-09 13:41:07.336  6322  6322 V PlaceDetection v1.0.29 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-09 13:41:07.336  6336  6336 E Zygote  : v2
09-09 13:41:07.336  6336  6336 I libpersona: KNOX_SDCARD checking this for 10089
09-09 13:41:07.336  6336  6336 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:07.346  6336  6336 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-09 13:41:07.346  6336  6336 E Zygote  : accessInfo : 0
09-09 13:41:07.346  1259  1989 I ActivityManager: Start proc 6336:com.google.android.apps.maps/u0a89 for broadcast-3 com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
09-09 13:41:07.346  6336  6336 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.maps 
,09-09 13:41:07.346  1259  2621 V AlarmManager:  remove PendingIntent] PendingIntent{fd3a04: PendingIntentRecord{6971bed com.samsung.android.intelligenceservice2 broadcastIntent}}
,09-09 13:41:07.366  6336  6336 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:41:07.366  6336  6336 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:07.366  2569  2739 E BluetoothAdapterState: stateChangeCallback : 16
,09-09 13:41:07.366  1259  2320 V AlarmManager:  remove PendingIntent] PendingIntent{f274a22: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:07.366  2569  2730 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STOPED
,09-09 13:41:07.376  1259  2310 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b032c10 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9853617 6336:com.google.android.apps.maps/u0a89}
,09-09 13:41:07.376  2569  2730 D BtConfig.SecureMode: isSecureModeOn:false
09-09 13:41:07.376  2569  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-09 13:41:07.376  2569  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-09 13:41:07.376  2569  2569 D HeadsetService: Received stop request...Stopping profile...
,09-09 13:41:07.376  2569  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 13:41:07.376  2569  2569 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Message sending
09-09 13:41:07.376  2569  2569 E HeadsetService: notifyProfileServiceStateChanged
,09-09 13:41:07.376  2569  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-09 13:41:07.386  2569  2569 D A2dpService: Received stop request...Stopping profile...
09-09 13:41:07.386  2569  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-09 13:41:07.386  1694  1694 D HeadsetProfile: Bluetooth service disconnected
09-09 13:41:07.386  1259  1259 D BluetoothHeadset: unRegisterMessageListener : 11
09-09 13:41:07.386  1259  1259 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
09-09 13:41:07.386  1259  1259 W BluetoothHeadset: Proxy not attached to service
09-09 13:41:07.386  1259  1259 I Telecom : BluetoothManager : unregister MessageListener
09-09 13:41:07.386  2569  3138 D A2dpStateMachine: Exit Disconnected: -1
09-09 13:41:07.386  2569  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 13:41:07.386  2569  2569 D Avrcp   : unregisterContentObserver
09-09 13:41:07.386  2569  2569 D Avrcp   : removeOnActiveSessionsChangedListener
,09-09 13:41:07.386  2569  2569 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Message sending
09-09 13:41:07.386  2569  2569 E A2dpService: notifyProfileServiceStateChanged
09-09 13:41:07.386  2569  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
09-09 13:41:07.386  2608  2608 D BluetoothA2dp: Proxy object disconnected
09-09 13:41:07.386  1259  1259 D BluetoothA2dp: Proxy object disconnected
09-09 13:41:07.386  2569  2569 E BluetoothAdapterService: handleMessage() - Message: 1
09-09 13:41:07.386  2569  2569 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Before synchronized
09-09 13:41:07.386  2569  2569 V BluetoothAdapterState: isTurningOff()=true
09-09 13:41:07.386  2569  2569 V BluetoothAdapterState: isTurningOn()=false
09-09 13:41:07.386  2569  2569 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:41:07.386  2569  2569 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:41:07.386  1694  1694 D BluetoothA2dp: Proxy object disconnected
09-09 13:41:07.386  1694  1694 D A2dpProfile: Bluetooth service disconnected
09-09 13:41:07.386  2569  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:41:07.386  2569  2730 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:41:07.386  2569  2569 D HidService: Received stop request...Stopping profile...
09-09 13:41:07.386  2569  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:41:07.386  2569  2569 D HidService: Stopping Bluetooth HidService
09-09 13:41:07.386  2569  2730 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:41:07.386  2569  2569 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 13:41:07.386  2569  2569 W bt_btif : cleanup: HH disabling or disabled already, status = 0
09-09 13:41:07.386  2569  2569 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 13:41:07.386  2569  2569 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Message sending
09-09 13:41:07.386  2569  2569 E HidService: notifyProfileServiceStateChanged
09-09 13:41:07.386  1694  1694 D BluetoothInputDevice: Proxy object disconnected
09-09 13:41:07.386  1694  1694 D HidProfile: Bluetooth service disconnected
,09-09 13:41:07.396  2569  2569 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 13:41:07.396  2569  2569 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 13:41:07.396  2569  2569 D HeadsetProvider: cleanup
09-09 13:41:07.396  2569  2569 I HeadsetProvider: clearAllHeadsetSettings(0)
09-09 13:41:07.396  6336  6336 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-09 13:41:07.406  2569  2569 D HealthService: Received stop request...Stopping profile...
,09-09 13:41:07.406  2569  2569 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Message sending
09-09 13:41:07.406  2569  2569 E HealthService: notifyProfileServiceStateChanged
,09-09 13:41:07.406  2569  2569 D PanService: Received stop request...Stopping profile...
09-09 13:41:07.406  2569  2569 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Message sending
09-09 13:41:07.406  2569  2569 E PanService: notifyProfileServiceStateChanged
09-09 13:41:07.406  1259  1259 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 13:41:07.406  1694  1694 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 13:41:07.406  1694  1694 D PanProfile: Bluetooth service disconnected
09-09 13:41:07.406  2569  2569 E BluetoothAdapterService: handleMessage() - Message: 1
09-09 13:41:07.406  2569  2569 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Before synchronized
,09-09 13:41:07.406  5814  5814 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 13:41:07.406  2569  2569 V BluetoothAdapterState: isTurningOff()=true
09-09 13:41:07.406  5814  5814 D PanProfile: Bluetooth service disconnected
09-09 13:41:07.406  2569  2569 V BluetoothAdapterState: isTurningOn()=false
09-09 13:41:07.406  2569  2569 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:41:07.406  2569  2569 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:41:07.406  2569  2569 D BluetoothMapService: Received stop request...Stopping profile...
,09-09 13:41:07.406  2569  2569 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Message sending
09-09 13:41:07.406  2569  2569 E BluetoothMapService: notifyProfileServiceStateChanged
,09-09 13:41:07.416  1694  1694 D BluetoothMap: Proxy object disconnected
09-09 13:41:07.416  1694  1694 D MapProfile: Bluetooth service disconnected
,09-09 13:41:07.416  1259  1274 I art     : Background sticky concurrent mark sweep GC freed 180084(11MB) AllocSpace objects, 67(1480KB) LOS objects, 27% free, 37MB/51MB, paused 2.767ms total 107.379ms
09-09 13:41:07.416  2569  2569 D SapService: Received stop request...Stopping profile...
09-09 13:41:07.416  2569  2569 V SapService: stop()
09-09 13:41:07.416  2569  2569 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Message sending
09-09 13:41:07.416  2569  2569 E SapService: notifyProfileServiceStateChanged
,09-09 13:41:07.416  5814  5814 D BluetoothSap: Proxy object disconnected
09-09 13:41:07.416  5814  5814 D SapProfile: Bluetooth service disconnected
09-09 13:41:07.416  1694  1694 D BluetoothSap: Proxy object disconnected
09-09 13:41:07.416  1694  1694 D SapProfile: Bluetooth service disconnected
09-09 13:41:07.416  2569  2569 E BluetoothAdapterService: handleMessage() - Message: 1
09-09 13:41:07.416  2569  2569 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Before synchronized
09-09 13:41:07.426  2569  2569 V BluetoothAdapterState: isTurningOff()=true
09-09 13:41:07.426  2569  2569 V BluetoothAdapterState: isTurningOn()=false
09-09 13:41:07.426  2569  2569 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:41:07.426  2569  2569 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:41:07.426  2569  2569 D BluetoothAdapterService: HID Host service will be diabled
09-09 13:41:07.426  1259  1325 W ActivityManager: Permission Denial: getCurrentUser() from pid=6336, uid=10089 requires android.permission.INTERACT_ACROSS_USERS
,09-09 13:41:07.426  2569  2569 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-09 13:41:07.426  2569  2569 E BluetoothAdapterService: handleMessage() - Message: 1
09-09 13:41:07.426  2569  2569 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Before synchronized
09-09 13:41:07.426  2569  2569 V BluetoothAdapterState: isTurningOff()=true
09-09 13:41:07.426  2569  2569 V BluetoothAdapterState: isTurningOn()=false
09-09 13:41:07.426  2569  2569 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:41:07.426  2569  2569 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:41:07.426  2569  2569 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-09 13:41:07.426  2569  2569 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 13:41:07.426  2569  2569 E BluetoothAdapterService: handleMessage() - Message: 1
09-09 13:41:07.426  2569  2569 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Before synchronized
,09-09 13:41:07.426  2569  2569 V BluetoothAdapterState: isTurningOff()=true
09-09 13:41:07.426  2569  2569 V BluetoothAdapterState: isTurningOn()=false
09-09 13:41:07.426  2569  2569 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:41:07.426  2569  2569 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:41:07.426  2569  2569 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 13:41:07.426  2569  2569 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-09 13:41:07.426  2569  2569 E BluetoothAdapterService: handleMessage() - Message: 1
09-09 13:41:07.426  2569  2569 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Before synchronized
09-09 13:41:07.426  2569  2569 V BluetoothAdapterState: isTurningOff()=true
09-09 13:41:07.426  2569  2569 V BluetoothAdapterState: isTurningOn()=false
09-09 13:41:07.426  2569  2569 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:41:07.426  2569  2569 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:41:07.426  2569  2569 E BluetoothAdapterService: handleMessage() - Message: 1
09-09 13:41:07.426  2569  2569 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Before synchronized
09-09 13:41:07.426  2569  2569 V BluetoothAdapterState: isTurningOff()=true
09-09 13:41:07.426  2569  2569 V BluetoothAdapterState: isTurningOn()=false
09-09 13:41:07.426  2569  2569 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:41:07.426  2569  2569 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:41:07.426  2569  2730 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STOPPED
,09-09 13:41:07.426  2569  2730 D BtGatt.GattService: getGattService(): returning com.android.bluetooth.gatt.GattService@673cdae
09-09 13:41:07.426  2569  2730 D BtGatt.GattService: serverDisconnectIncomingConnClients()
09-09 13:41:07.426  2569  2739 E bt_btif_gatt: btgatts_handle_event: Unknown event (2014)!
09-09 13:41:07.426  2569  2730 D BluetoothAdapterProperties: Setting state to 15
09-09 13:41:07.426  2569  3029 W bt_btif : BTA got unregistered event id 32
09-09 13:41:07.426  2569  2730 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-09 13:41:07.436  2569  2730 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 13:41:07.436  2569  2730 D BluetoothAdapterService: updateAdapterState state is 15
,09-09 13:41:07.436  2569  2730 D BluetoothAdapterService: Autoconnection is available 
09-09 13:41:07.436  2569  2730 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 15
09-09 13:41:07.436  2569  2730 I BluetoothAdapterState: Entering BleOnState
09-09 13:41:07.436  1694  1707 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 13:41:07.436  2569  2730 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_ON
09-09 13:41:07.436  1694  2171 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:41:07.436  1694  2171 D BluetoothAdapter: Bluetooth is turned off, stop adv
,09-09 13:41:07.436  2569  2730 D BluetoothAdapterProperties: Setting state to 11
09-09 13:41:07.436  2569  2730 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-09 13:41:07.436  2569  2730 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 13:41:07.436  2569  2730 D BluetoothAdapterService: updateAdapterState state is 11
09-09 13:41:07.436  1694  2171 D BluetoothAdapter: There are no active google scan apps, stop scan
09-09 13:41:07.436  2569  2730 D BluetoothAdapterService: Autoconnection is available 
09-09 13:41:07.436  2569  2730 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 11
09-09 13:41:07.436  1694  3015 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 13:41:07.436  2569  2730 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:41:07.436  2569  2730 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,09-09 13:41:07.436  2569  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-09 13:41:07.436  1259  1416 D BluetoothPan: onBluetoothStateChange on: false
,09-09 13:41:07.436  1694  1705 D BluetoothSap: onBluetoothStateChange: up=false
09-09 13:41:07.436  1259  2621 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.provider.shootingmodeprovider, Auto Run ON
09-09 13:41:07.436  1259  2621 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5826 ,hash=96829733 ,name=com.samsung.android.provider.shootingmodeprovider
,09-09 13:41:07.436  2569  2569 D HeadsetService: Received start request. Starting profile...
09-09 13:41:07.436  2569  2569 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b2cb7b
09-09 13:41:07.436  2569  2569 D HeadsetProvider: make
09-09 13:41:07.436  2569  2569 D HeadsetProvider: HeadsetProvider
09-09 13:41:07.436  2569  2569 I HeadsetProvider: clearAllHeadsetSettings(0)
09-09 13:41:07.436  2569  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-09 13:41:07.446  1694  1707 D BluetoothMap: onBluetoothStateChange: up=false
,09-09 13:41:07.446  2569  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 13:41:07.446  5814  5825 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:41:07.446  5814  5825 D BluetoothAdapter: Bluetooth is turned off, stop adv
09-09 13:41:07.446  2569  2569 D HeadsetStateMachine: make
09-09 13:41:07.446  5814  5825 D BluetoothAdapter: There are no active google scan apps, stop scan
,09-09 13:41:07.446  2608  2705 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 13:41:07.446  2569  2569 E HeadsetStateMachine: # of Max HF connection is 2
,09-09 13:41:07.446  1259  1416 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 13:41:07.446  2569  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-09 13:41:07.446  5814  5824 D BluetoothPan: onBluetoothStateChange on: false
,09-09 13:41:07.456  2569  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-09 13:41:07.456  5955  5966 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:41:07.456  5955  5966 D BluetoothAdapter: Bluetooth is turned off, stop adv
09-09 13:41:07.456  5955  5966 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-09 13:41:07.456  5955  5966 D BluetoothLeAdvertiser: Exit stop advertising
09-09 13:41:07.456  5955  5966 D BluetoothAdapter: There are no active google scan apps, stop scan
09-09 13:41:07.456  5955  5966 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-09 13:41:07.456  5955  5966 D BluetoothLeScanner: Exiting stopAllScan
09-09 13:41:07.456  1974  1988 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:41:07.456  1974  1988 D BluetoothAdapter: Bluetooth is turned off, stop adv
,09-09 13:41:07.456  1974  1988 D BluetoothAdapter: There are no active google scan apps, stop scan
09-09 13:41:07.456  1259  1416 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:41:07.456  1259  1416 D BluetoothAdapter: Bluetooth is turned off, stop adv
,09-09 13:41:07.456  1259  1416 D BluetoothAdapter: There are no active google scan apps, stop scan
09-09 13:41:07.456  1694  3015 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 13:41:07.456  2569  2569 I bt_bluedroid: get_profile_interface handsfree
09-09 13:41:07.456  2569  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 13:41:07.456  1694  1705 D BluetoothPan: onBluetoothStateChange on: false
,09-09 13:41:07.456  2569  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,09-09 13:41:07.466  2569  3151 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:41:07.466  2569  3151 D BluetoothAdapter: Bluetooth is turned off, stop adv
,09-09 13:41:07.466  2569  3151 D BluetoothAdapter: There are no active google scan apps, stop scan
,09-09 13:41:07.466  1868  2412 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:41:07.466  1868  2412 D BluetoothAdapter: Bluetooth is turned off, stop adv
09-09 13:41:07.466  2569  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:41:07.466  2569  2730 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:41:07.466  2569  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:41:07.466  2569  2730 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:41:07.466  2569  2730 I BluetoothAdapterState: Entering PendingCommandState
,09-09 13:41:07.466  1868  2412 D BluetoothAdapter: There are no active google scan apps, stop scan
09-09 13:41:07.466  2608  2645 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:41:07.466  2608  2645 D BluetoothAdapter: Bluetooth is turned off, stop adv
,09-09 13:41:07.466  2569  2569 E DualScoManager: Dual Sco Manager already instantiated
09-09 13:41:07.466  2569  2569 I DualScoManager: Set HeadsetServiceHelper
09-09 13:41:07.466  2569  2569 D BluetoothAtMessage: createCMTIContentObservers
09-09 13:41:07.466  2608  2645 D BluetoothAdapter: There are no active google scan apps, stop scan
09-09 13:41:07.466  5814  5825 D BluetoothSap: onBluetoothStateChange: up=false
,09-09 13:41:07.466  2569  2730 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: USER_TURN_OFF
,09-09 13:41:07.466  1259  1416 D BluetoothManagerService: Turning On/Off, G state: 3, S state: 3, mBLE count: 0, s BLE count: 0
09-09 13:41:07.466  1259  1259 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:07.466  1259  1259 I InputMethodManagerService: [BT Setting State] State =10
09-09 13:41:07.466  1259  1259 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-09 13:41:07.476  2039  2039 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:41:07.476  2569  2569 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@bc882a3
09-09 13:41:07.476  1694  2072 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:07.476  1694  2072 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
09-09 13:41:07.476  2569  2569 D HeadsetProvider: setHeadsetDB - Can't find 300 for 44:78:3E:EB:95:XX
,09-09 13:41:07.476  1259  1259 D BluetoothPhoneService: Bluetooth Adapter state : 10
,09-09 13:41:07.476  1259  1259 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
09-09 13:41:07.476  1259  1259 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:07.476  1259  1259 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,09-09 13:41:07.476  2569  2730 I BluetoothAdapterState: Deferring USER_TURN_OFF request...
09-09 13:41:07.476  5814  5814 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:41:07.476  5814  5814 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-09 13:41:07.486  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:07.486  1694  2108 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
,09-09 13:41:07.486  1259  1721 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-09 13:41:07.486  2039  2039 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:41:07.486  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:07.486  1694  2072 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:07.486  1694  2072 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-09 13:41:07.486  2569  2569 I HeadsetProvider: setHeadsetDB - 44:78:3E:EB:95:XX, 300, 0, true
,09-09 13:41:07.486  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:07.486  1259  1259 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:07.486  1259  1259 D BluetoothPhoneService: Bluetooth Adapter state : 11
09-09 13:41:07.486  1259  1259 I InputMethodManagerService: [BT Setting State] State =11
09-09 13:41:07.486  1259  1259 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
09-09 13:41:07.486  1259  1259 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:07.486  1259  1259 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,09-09 13:41:07.486  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:07.486  1694  2108 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = true, connected = false, connecting = false, mController.getLastDeviceName() = null
,09-09 13:41:07.486  1259  2008 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-09 13:41:07.496  1694  1694 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 148
09-09 13:41:07.496  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:07.496  2569  2569 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@54f391e
09-09 13:41:07.496  2569  2569 D HeadsetProvider: setHeadsetDB - Can't find 400 for 44:78:3E:EB:95:XX
,09-09 13:41:07.496  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:07.496  5814  5814 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:07.496  5814  5814 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-09 13:41:07.506  2569  2569 I HeadsetProvider: setHeadsetDB - 44:78:3E:EB:95:XX, 400, 1, true
,09-09 13:41:07.506  2569  6349 D HeadsetStateMachine: Enter Disconnected: -2, size: 0/0
09-09 13:41:07.506  2569  2569 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Message sending
09-09 13:41:07.506  2569  2569 E HeadsetService: notifyProfileServiceStateChanged
,09-09 13:41:07.506  2569  2569 D A2dpService: Received start request. Starting profile...
09-09 13:41:07.506  2569  2569 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b2cb7b
09-09 13:41:07.506  2569  2569 I bt_bluedroid: get_profile_interface avrcp
,09-09 13:41:07.506  2569  6349 D HeadsetStateMachine: Clear mHeadsetBrsf
09-09 13:41:07.506  2569  6349 D HeadsetStateMachine: map size, before remove : 0
09-09 13:41:07.506  2569  6349 D HeadsetStateMachine: map size, after remove: 0
,09-09 13:41:07.506  2569  2569 I Avrcp   : No of Audio players :: 1
09-09 13:41:07.506  2569  2569 I Avrcp   : App Package name is GM
,09-09 13:41:07.506  2569  2569 V Avrcp   : MediaPlayerInfo: mPlayerId=1
09-09 13:41:07.506  6336  6353 W System.err: mkdir failed: EEXIST (File exists) : /storage/emulated/0/Android/data/com.google.android.apps.maps/testdata
,09-09 13:41:07.506  2569  2569 I Avrcp   : No of Video players :: 2
09-09 13:41:07.506  2569  2569 I Avrcp   : Video App Package name is others
09-09 13:41:07.516  6336  6353 W System.err: mkdir failed: EEXIST (File exists) : /data/user/0/com.google.android.apps.maps/app_/testdata
,09-09 13:41:07.516  2569  2569 V Avrcp   : MediaPlayerInfo: mPlayerId=2
09-09 13:41:07.516  2569  2569 I Avrcp   : Video App Package name is VP
,09-09 13:41:07.516  2569  2569 V Avrcp   : MediaPlayerInfo: mPlayerId=3
09-09 13:41:07.516  2569  2569 I Avrcp   : Add tempPlayer
09-09 13:41:07.516  2569  2569 V Avrcp   : MediaPlayerInfo: mPlayerId=4
09-09 13:41:07.516  2569  2569 V Avrcp   : no_of_players : 4
09-09 13:41:07.516  2569  2569 I Avrcp   : Total no of players: 4
09-09 13:41:07.516  2569  2569 V Avrcp   : Samsung player is the 1st player
09-09 13:41:07.516  2569  2569 D Avrcp   : Compose Browsing Service Candidate
,09-09 13:41:07.516  2569  2569 D Avrcp   : ResolveInfo info ResolveInfo{f79a31b com.google.android.music/.browse.MediaBrowserService m=0x108000}
09-09 13:41:07.516  2569  2569 D Avrcp   : Initialize Media Controller
09-09 13:41:07.516  2569  2569 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-09 13:41:07.516  2569  2569 E Avrcp   : getActiveSessions
09-09 13:41:07.516  2569  2569 D Avrcp   : pick active media Controller
09-09 13:41:07.516  2569  2569 D Avrcp   : Get the active Media Controller 
09-09 13:41:07.516  2569  2569 D A2dpStateMachine: make
,09-09 13:41:07.516  2569  2569 I bt_bluedroid: get_profile_interface a2dp
09-09 13:41:07.516  6336  6353 W System.err: mkdir failed: EEXIST (File exists) : /storage/emulated/0/Android/data/com.google.android.apps.maps/cache
,09-09 13:41:07.516  2569  2569 E bt_btif : ### uipc_main_init ###tarted media_task_refcnt 1 
09-09 13:41:07.516  2569  2569 E bt_btif : warning : no command pending, ignore ack
,09-09 13:41:07.526  2569  6358 D A2dpStateMachine: Enter Disconnected: -2
,09-09 13:41:07.526  2569  2569 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Message sending
09-09 13:41:07.526  2569  2569 E A2dpService: notifyProfileServiceStateChanged
09-09 13:41:07.526  2569  2569 D HidService: Received start request. Starting profile...
09-09 13:41:07.526  2569  2569 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b2cb7b
09-09 13:41:07.526  2569  2569 I bt_bluedroid: get_profile_interface hidhost
09-09 13:41:07.526  2569  2569 D HidService: setHidService(): set to: null
09-09 13:41:07.526  2569  2569 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Message sending
09-09 13:41:07.526  2569  2569 E HidService: notifyProfileServiceStateChanged
,09-09 13:41:07.526  2569  2569 D HealthService: Received start request. Starting profile...
09-09 13:41:07.526  2569  2569 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b2cb7b
,09-09 13:41:07.526  2569  2569 I bt_bluedroid: get_profile_interface health
,09-09 13:41:07.526  2569  2569 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Message sending
09-09 13:41:07.526  2569  2569 E HealthService: notifyProfileServiceStateChanged
09-09 13:41:07.526  2569  2569 D HeadsetStateMachine: Try to query the phonestate on bind
09-09 13:41:07.526  1259  1853 I BluetoothPhoneService: queryPhoneState
09-09 13:41:07.526  1259  1853 I BluetoothPhoneService: updateHeadsetWithCallState : true
,09-09 13:41:07.536  2569  2569 D PanService: Received start request. Starting profile...
09-09 13:41:07.536  2569  2569 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b2cb7b
09-09 13:41:07.536  2569  2569 D BluetoothPanServiceJni: initializeNative(L118): pan
09-09 13:41:07.536  2569  2569 I bt_bluedroid: get_profile_interface pan
09-09 13:41:07.536  2569  2569 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Message sending
09-09 13:41:07.536  2569  2569 E PanService: notifyProfileServiceStateChanged
,09-09 13:41:07.536  2569  2569 D HeadsetStateMachine: Proxy object connected
09-09 13:41:07.536  2569  2569 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
09-09 13:41:07.536  2569  6349 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-09 13:41:07.536  2569  6349 E HeadsetStateMachine: Unknown message: 11
,09-09 13:41:07.536  2569  2569 D BluetoothMapService: Received start request. Starting profile...
09-09 13:41:07.536  2569  2569 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b2cb7b
,09-09 13:41:07.536  2569  2569 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Message sending
09-09 13:41:07.536  2569  2569 E BluetoothMapService: notifyProfileServiceStateChanged
,09-09 13:41:07.536  2569  2569 V SapService: SapBinder()
,09-09 13:41:07.536  2569  2569 D SapService: Received start request. Starting profile...
09-09 13:41:07.536  2569  2569 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b2cb7b
09-09 13:41:07.536  2569  2569 V SapService: start()
09-09 13:41:07.536  2569  2569 V SapService: SAP UUID disabled
09-09 13:41:07.536  2569  2569 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Message sending
09-09 13:41:07.536  2569  2569 E SapService: notifyProfileServiceStateChanged
09-09 13:41:07.536  2569  2569 D HeadsetPhoneState: sendDeviceDataStateChanged
09-09 13:41:07.536  2569  6349 D HeadsetStateMachine: Disconnected process message: 19, size: 0
09-09 13:41:07.536  2569  6349 E HeadsetStateMachine: Unknown message: 19
09-09 13:41:07.536  2569  2569 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-09 13:41:07.536  2569  2569 E BluetoothAdapterService: handleMessage() - Message: 1
09-09 13:41:07.536  2569  2569 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Before synchronized
,09-09 13:41:07.536  2569  2569 V BluetoothAdapterState: isTurningOff()=false
09-09 13:41:07.536  2569  2569 V BluetoothAdapterState: isTurningOn()=true
09-09 13:41:07.536  2569  2569 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:41:07.536  2569  2569 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:41:07.536  2569  2569 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-09 13:41:07.536  2569  2569 E BluetoothAdapterService: handleMessage() - Message: 1
09-09 13:41:07.536  2569  2569 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Before synchronized
09-09 13:41:07.536  2569  6349 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-09 13:41:07.536  2569  6349 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-09 13:41:07.536  2569  6349 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-09 13:41:07.536  2569  6349 E HeadsetStateMachine: Unknown message: 11
09-09 13:41:07.536  2569  2569 V BluetoothAdapterState: isTurningOff()=false
09-09 13:41:07.536  2569  2569 V BluetoothAdapterState: isTurningOn()=true
09-09 13:41:07.536  2569  2569 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:41:07.536  2569  2569 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:41:07.536  2569  2569 E BluetoothAdapterService: handleMessage() - Message: 1
09-09 13:41:07.536  2569  2569 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Before synchronized
,09-09 13:41:07.536  2569  2569 V BluetoothAdapterState: isTurningOff()=false
09-09 13:41:07.536  2569  2569 V BluetoothAdapterState: isTurningOn()=true
09-09 13:41:07.536  2569  2569 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:41:07.536  2569  2569 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:41:07.536  2569  2569 D BluetoothAdapterService: HID Host service started
,09-09 13:41:07.546  1694  2072 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
09-09 13:41:07.546  1694  2072 W LocalBluetoothProfileManager: updateLocalProfiles :: A2DP profile was previously added but the UUID is now missing.
09-09 13:41:07.546  1694  2072 W LocalBluetoothProfileManager: updateLocalProfiles :: HEADSET profile was previously added but the UUID is now missing.
,09-09 13:41:07.546  2569  2569 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 13:41:07.546  1694  2072 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
09-09 13:41:07.546  2569  2569 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-09 13:41:07.546  1694  2072 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
09-09 13:41:07.546  1694  2072 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
09-09 13:41:07.546  1694  2072 D HidProfile: mService is null. need to get proxy again!!
09-09 13:41:07.546  2569  2569 D HeadsetPhoneState: sendDeviceDataStateChanged
09-09 13:41:07.546  2569  2569 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-09 13:41:07.546  2569  2569 E BluetoothAdapterService: handleMessage() - Message: 1
09-09 13:41:07.546  2569  2569 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Before synchronized
09-09 13:41:07.546  2569  6349 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-09 13:41:07.546  2569  6349 E HeadsetStateMachine: Unknown message: 11
09-09 13:41:07.546  2569  6349 D HeadsetStateMachine: Disconnected process message: 19, size: 0
09-09 13:41:07.546  2569  6349 E HeadsetStateMachine: Unknown message: 19
,09-09 13:41:07.546  5814  5814 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
09-09 13:41:07.546  2569  2569 V BluetoothAdapterState: isTurningOff()=false
09-09 13:41:07.546  2569  2569 V BluetoothAdapterState: isTurningOn()=true
09-09 13:41:07.546  2569  2569 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:41:07.546  2569  2569 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:41:07.546  2569  2569 E BluetoothAdapterService: handleMessage() - Message: 1
09-09 13:41:07.546  2569  2569 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Before synchronized
,09-09 13:41:07.546  5814  5814 D BluetoothMap: Create BluetoothMap proxy object
09-09 13:41:07.546  2569  2569 V BluetoothAdapterState: isTurningOff()=false
09-09 13:41:07.546  2569  2569 V BluetoothAdapterState: isTurningOn()=true
09-09 13:41:07.546  2569  2569 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:41:07.546  2569  2569 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:41:07.546  2569  2569 E BluetoothAdapterService: handleMessage() - Message: 1
09-09 13:41:07.546  2569  2569 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Before synchronized
,09-09 13:41:07.546  2569  2569 V BluetoothAdapterState: isTurningOff()=false
09-09 13:41:07.546  2569  2569 V BluetoothAdapterState: isTurningOn()=true
09-09 13:41:07.546  2569  2569 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:41:07.546  2569  2569 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:41:07.546  2569  2569 E BluetoothAdapterService: handleMessage() - Message: 1
09-09 13:41:07.546  2569  2569 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Before synchronized
,09-09 13:41:07.546  2569  2569 V BluetoothAdapterState: isTurningOff()=false
09-09 13:41:07.546  2569  2569 V BluetoothAdapterState: isTurningOn()=true
09-09 13:41:07.546  2569  2569 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:41:07.546  2569  2569 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:41:07.546  2569  2730 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STARTED
,09-09 13:41:07.546  2569  2730 E BluetoothServiceJni: enableBrEdrNative:
09-09 13:41:07.546  2569  2730 I bt_bluedroid: enable_bredr
09-09 13:41:07.546  1694  1694 D BluetoothInputDevice: Proxy object connected
09-09 13:41:07.546  1694  1694 D HidProfile: Bluetooth service connected
,09-09 13:41:07.556  2569  3029 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
09-09 13:41:07.556  2569  3029 D CODEC_IF_MOD: codec_open: codec_open
09-09 13:41:07.556  2569  3029 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
09-09 13:41:07.556  2569  3029 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
09-09 13:41:07.556  2569  3029 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
09-09 13:41:07.556  2569  3029 D CODEC_IF: codec_if_open: codec module opened (v0.1
09-09 13:41:07.556  2569  3029 D CODEC_IF: codec_if_close: codec_if_close hdl -284708860
09-09 13:41:07.556  2569  3029 D CODEC_IF_MOD: codec_close: codec_close
09-09 13:41:07.556  2569  3029 D CODEC_IF_MOD: codec_close: freed apt-x encoder
09-09 13:41:07.556  2569  3029 D         : Codec ==> check 44.1kHz mode : check_sshd_encoder_available:356
09-09 13:41:07.556  2569  3029 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
09-09 13:41:07.556  2569  3029 D CODEC_IF_SSHD: codec_open: codec_open
09-09 13:41:07.556  2569  3029 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 44100
09-09 13:41:07.556  2569  3029 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
09-09 13:41:07.556  2569  3029 D CODEC_IF: codec_if_open: codec module opened (v0.1
09-09 13:41:07.556  2569  3029 D CODEC_IF: codec_if_close: codec_if_close hdl -390185600
09-09 13:41:07.556  2569  3029 D CODEC_IF_SSHD: codec_close: codec_close
09-09 13:41:07.556  2569  3029 D         : Codec ==> check 44.1kHz mode : check_sshd_encoder_available:356
09-09 13:41:07.556  2569  3029 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
09-09 13:41:07.556  2569  3029 D CODEC_IF_SSHD: codec_open: codec_open
09-09 13:41:07.556  2569  3029 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 44100
09-09 13:41:07.556  2569  3029 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
09-09 13:41:07.556  2569  3029 D CODEC_IF: codec_if_open: codec module opened (v0.1
09-09 13:41:07.556  2569  3029 D CODEC_IF: codec_if_close: codec_if_close hdl -390185600
09-09 13:41:07.556  2569  3029 D CODEC_IF_SSHD: codec_close: codec_close
09-09 13:41:07.556  2569  3029 D         : Codec ==> copy capability info [bta_av_co_audio_init:646]
09-09 13:41:07.556  2569  2739 I bt_bta_hh: BTA_HhEnable sec_mask:0x24 p_cback:0xf38f1ca9
09-09 13:41:07.556  2569  2739 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x100048
09-09 13:41:07.556  2569  2739 D BluetoothAdapterProperties: Address is:44:78:3E:EB:95:EE
09-09 13:41:07.556  2569  2739 E BluetoothServiceJni: populateRssiValuesNative
09-09 13:41:07.556  1259  1987 V AlarmManager:  remove PendingIntent] PendingIntent{7eb30c9: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:07.556  2569  2739 I bt_bluedroid: getModelRssiValues
09-09 13:41:07.556  2569  2739 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-09 13:41:07.556  2569  2739 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
09-09 13:41:07.556  5814  5814 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
,09-09 13:41:07.556  2569  2739 D BluetoothAdapterProperties: Name is: Galaxy Tab S2
,09-09 13:41:07.556  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
09-09 13:41:07.556  1259  1259 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
09-09 13:41:07.566  2970  2970 I WCNSS_FILTER: do_write: IBS write: fc
,09-09 13:41:07.566  1259  1987 V AlarmManager:  remove PendingIntent] PendingIntent{7d6beda: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:07.566  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,09-09 13:41:07.566  5814  5814 D BluetoothMap: Proxy object connected
09-09 13:41:07.566  5814  5814 D MapProfile: Bluetooth service connected
09-09 13:41:07.566  5814  5814 D BluetoothMap: getConnectedDevices()
09-09 13:41:07.566  5814  5814 D BluetoothMap: Bluetooth is Not enabled
09-09 13:41:07.566  5814  5814 D BluetoothInputDevice: Proxy object connected
,09-09 13:41:07.566  5814  5814 D HidProfile: Bluetooth service connected
09-09 13:41:07.566  1259  2621 V AlarmManager:  remove PendingIntent] PendingIntent{b31df0b: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:07.566  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:07.566  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
,09-09 13:41:07.566  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-09 13:41:07.566  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
,09-09 13:41:07.576  1259  2294 V AlarmManager:  remove PendingIntent] PendingIntent{3b381e8: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:07.576  2569  2739 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 13:41:07.576  2569  2739 D BluetoothAdapterProperties: Scan Mode:20
09-09 13:41:07.576  2569  2739 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 13:41:07.576  2569  2739 E bt_btif : btif_handle_bluetooth_enable_evt
,09-09 13:41:07.576  2569  2739 E bt_btif : JVenable fails
09-09 13:41:07.576  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-09 13:41:07.576  2569  2739 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
09-09 13:41:07.576  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
09-09 13:41:07.576  2569  2739 D IOP_DB_BT: db_open: db_open : handle 4085833744l, read 18559 bytes onto local cache
09-09 13:41:07.576  2569  2739 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
09-09 13:41:07.576  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:07.576  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-09 13:41:07.576  2569  2739 D IOP_DB_BT: db_query: result 1
09-09 13:41:07.576  2569  2739 I         : iop_db_open: iop_db_open status 0
09-09 13:41:07.576  2569  2739 E BluetoothAdapterState: stateChangeCallback : 17
09-09 13:41:07.576  2569  2730 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STARTED
09-09 13:41:07.576  2569  2739 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-09 13:41:07.576  2569  2730 D BluetoothAdapterProperties: ScanMode =  20
09-09 13:41:07.576  2569  2730 D BluetoothAdapterProperties: State =  11
09-09 13:41:07.576  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
09-09 13:41:07.576  1259  2304 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
09-09 13:41:07.576  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-09 13:41:07.576  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:07.576  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
09-09 13:41:07.576  1259  1637 D SecContentProvider: insert(), uri = 2
09-09 13:41:07.576  2569  2730 D BluetoothAdapterProperties: Setting state to 12
09-09 13:41:07.576  2569  2730 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 13:41:07.576  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-09 13:41:07.576  2569  2730 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 13:41:07.576  2569  2730 D BluetoothAdapterService: updateAdapterState state is 12
09-09 13:41:07.586  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 8 : bytes_written: 8
09-09 13:41:07.586  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-09 13:41:07.586  2569  2739 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 13:41:07.586  2569  2739 D BluetoothAdapterProperties: Scan Mode:21
09-09 13:41:07.586  2569  2739 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 13:41:07.586  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
,09-09 13:41:07.586  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,09-09 13:41:07.586  5955  5955 D BluetoothAdapter: STATE_ON
,09-09 13:41:07.586  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
09-09 13:41:07.586  5955  5955 D BluetoothAdapter: STATE_ON
09-09 13:41:07.586  1259  2621 V AlarmManager:  remove PendingIntent] PendingIntent{971eea6: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:07.586  5955  5955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-09 13:41:07.586  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,09-09 13:41:07.586  2569  2569 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
09-09 13:41:07.586  2569  2569 I BluetoothPbapService: Handler(): got msg=1
09-09 13:41:07.596  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
09-09 13:41:07.596  2569  2730 V BluetoothAdapterService: start opp service
09-09 13:41:07.596  1259  2310 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-09 13:41:07.596   720   720 I MSM-irqbalance: Decided to move IRQ215 from CPU3 to CPU1
,09-09 13:41:07.596  1694  2171 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 13:41:07.596  1694  2171 D BluetoothA2dp: Binding service...
09-09 13:41:07.596  1259  2008 V AlarmManager:  remove PendingIntent] PendingIntent{e32d494: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:07.596  2569  2730 D BluetoothAdapterService: Autoconnection is available 
09-09 13:41:07.596  2569  2730 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-09 13:41:07.596  2569  2730 D BluetoothAdapterService: starting service from this receiver
,09-09 13:41:07.596  1694  2171 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-09 13:41:07.596  2569  6371 V BluetoothPbapService: PBAP Service initSocket try: 0
09-09 13:41:07.596  2569  2730 D BluetoothAdapterService: BT on, init HID DEV count : 0
09-09 13:41:07.596  2569  2730 I BluetoothAdapterState: Entering OnState
09-09 13:41:07.596  5814  5814 D BluetoothPbap: Proxy object connected
09-09 13:41:07.596  2569  2569 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
09-09 13:41:07.606  2569  2569 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
09-09 13:41:07.606  5955  5955 D BluetoothAdapter: STATE_ON
09-09 13:41:07.606  2569  2569 V BtOppService: isOwner == true
09-09 13:41:07.606  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-09 13:41:07.606  5814  5824 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 13:41:07.606  5814  5824 D BluetoothPbap: Binding service...
09-09 13:41:07.606  2569  2730 D BluetoothAdapterState: Current state: ON, message: USER_TURN_OFF
09-09 13:41:07.606  5955  5955 D BluetoothAdapter: STATE_ON
09-09 13:41:07.606  1259  2320 V AlarmManager:  remove PendingIntent] PendingIntent{8a4de39: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:07.606  2569  6371 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:41:07.606  2569  6371 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:41:07.606  5955  5955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-09 13:41:07.606  1694  3015 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:41:07.606  1694  3015 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 13:41:07.606  5814  5825 D BluetoothMap: onBluetoothStateChange: up=true
09-09 13:41:07.606  5814  5814 D PbapServerProfile: Bluetooth service connected
09-09 13:41:07.606  1694  1705 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 13:41:07.606  1694  1705 D BluetoothInputDevice: Binding service...
,09-09 13:41:07.606  2569  6371 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
09-09 13:41:07.606  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
09-09 13:41:07.616  1259  2629 V AlarmManager:  remove PendingIntent] PendingIntent{4bb8f30: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:07.606  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-09 13:41:07.606  1694  1694 D BluetoothInputDevice: Proxy object connected
09-09 13:41:07.606  1694  1694 D HidProfile: Bluetooth service connected
09-09 13:41:07.616  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
09-09 13:41:07.616  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-09 13:41:07.616  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
09-09 13:41:07.616  1259  1416 D BluetoothPan: onBluetoothStateChange on: true
09-09 13:41:07.616  1259  1416 D BluetoothPan: onBluetoothStateChange calling doBind()
,09-09 13:41:07.616  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-09 13:41:07.616  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
09-09 13:41:07.616  1694  2171 D BluetoothSap: onBluetoothStateChange: up=true
09-09 13:41:07.616  1694  2171 D BluetoothSap: Binding service...
,09-09 13:41:07.616  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-09 13:41:07.616  5955  5955 D BluetoothAdapter: STATE_ON
,09-09 13:41:07.616  1694  3015 D BluetoothMap: onBluetoothStateChange: up=true
09-09 13:41:07.616  1259  1989 V AlarmManager:  remove PendingIntent] PendingIntent{7761448: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:07.616  1694  3015 D BluetoothMap: Binding service...
,09-09 13:41:07.626  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
,09-09 13:41:07.626  1694  1694 D BluetoothMap: Proxy object connected
09-09 13:41:07.626  1694  1694 D MapProfile: Bluetooth service connected
09-09 13:41:07.626  1694  1694 D BluetoothMap: getConnectedDevices()
09-09 13:41:07.626  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-09 13:41:07.626  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
,09-09 13:41:07.626  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:07.626  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:07.626  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:07.626  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:07.626  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:07.626  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:07.626  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:07.626  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:07.626  1259  2621 V AlarmManager:  remove PendingIntent] PendingIntent{b8d5ec7: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:07.626  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-09 13:41:07.626  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
09-09 13:41:07.626  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-09 13:41:07.626  1259  1637 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-09 13:41:07.626  5814  5824 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:41:07.626  5814  5824 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:41:07.626  5955  5955 D BluetoothAdapter: STATE_ON
09-09 13:41:07.626  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
,09-09 13:41:07.626  1694  1694 D BluetoothA2dp: Proxy object connected
09-09 13:41:07.626  1694  1694 D A2dpProfile: Bluetooth service connected
09-09 13:41:07.626  2608  2645 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 13:41:07.626  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-09 13:41:07.626  2608  2645 D BluetoothA2dp: Binding service...
09-09 13:41:07.626  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
,09-09 13:41:07.626  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,09-09 13:41:07.636  1259  1324 V AlarmManager:  remove PendingIntent] PendingIntent{2fc2cf4: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:07.636  2569  3151 D A2dpStateMachine: getConnectedDevices : size=0
,09-09 13:41:07.636  2608  2645 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:41:07.636  2608  2608 D BluetoothA2dp: Proxy object connected
09-09 13:41:07.636  1259  1416 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 13:41:07.636  1259  1416 D BluetoothA2dp: Binding service...
09-09 13:41:07.636  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:07.636  1259  1416 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:41:07.636  1259  1259 D BluetoothA2dp: Proxy object connected
09-09 13:41:07.636  1259  1987 V AlarmManager:  remove PendingIntent] PendingIntent{1d9ed19: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:07.636  2569  3151 D A2dpStateMachine: getConnectedDevices : size=0
,09-09 13:41:07.636  5814  6372 D BluetoothPan: onBluetoothStateChange on: true
09-09 13:41:07.636  5814  6372 D BluetoothPan: onBluetoothStateChange calling doBind()
,09-09 13:41:07.636  1259  1259 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 13:41:07.636  1259  2008 V AlarmManager:  remove PendingIntent] PendingIntent{a5dc1de: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:07.646  1694  1694 D BluetoothSap: Proxy object connected
09-09 13:41:07.646  1694  1694 D SapProfile: Bluetooth service connected
09-09 13:41:07.646  5955  5955 D BluetoothAdapter: STATE_ON
,09-09 13:41:07.646  5814  5814 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 13:41:07.646  5814  5814 D PanProfile: Bluetooth service connected
,09-09 13:41:07.646  5955  5966 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:41:07.646  5955  5966 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 13:41:07.646  1974  1988 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:41:07.646  1974  1988 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 13:41:07.646  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:07.646  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:07.646  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:07.646  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:07.646  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:07.646  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:07.646  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:07.646  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:07.646  1259  1416 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:41:07.646  1259  1416 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 13:41:07.646  1694  1707 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 13:41:07.646  1694  1705 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 13:41:07.646  1694  1705 D BluetoothPbap: Binding service...
09-09 13:41:07.646  5955  5955 D BluetoothAdapter: STATE_ON
,09-09 13:41:07.646  1694  1694 D BluetoothPbap: Proxy object connected
09-09 13:41:07.646  1694  1694 D PbapServerProfile: Bluetooth service connected
09-09 13:41:07.646  5814  5824 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 13:41:07.646  1694  3015 D BluetoothPan: onBluetoothStateChange on: true
09-09 13:41:07.646  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:07.646  1694  3015 D BluetoothPan: onBluetoothStateChange calling doBind()
09-09 13:41:07.646  2569  6376 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:41:07.646  2569  6376 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:41:07.656  1694  1694 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 13:41:07.656  1694  1694 D PanProfile: Bluetooth service connected
09-09 13:41:07.656  2569  3085 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:41:07.656  2569  3085 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:41:07.656  2569  6376 I BtOppRfcommListener: Accept thread started.
09-09 13:41:07.656  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
,09-09 13:41:07.656  1868  2412 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:41:07.656  1868  2412 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:41:07.656  2608  2705 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:41:07.656  2608  2705 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 13:41:07.656  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-09 13:41:07.656  5814  5825 D BluetoothSap: onBluetoothStateChange: up=true
09-09 13:41:07.656  5814  5825 D BluetoothSap: Binding service...
,09-09 13:41:07.656  5955  5955 D BluetoothAdapter: STATE_ON
,09-09 13:41:07.656  5814  5814 D BluetoothSap: Proxy object connected
09-09 13:41:07.656  5814  5814 D SapProfile: Bluetooth service connected
,09-09 13:41:07.656  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:07.656  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:07.656  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:07.656  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:07.656  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:07.656  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:07.656  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:07.656  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:07.656  1259  1259 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:07.666  1259  1259 I InputMethodManagerService: [BT Setting State] State =12
09-09 13:41:07.666  1259  1259 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-09 13:41:07.666  2039  2039 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:07.666  1694  2072 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:07.666  1694  2072 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-09 13:41:07.666  5955  5955 D BluetoothAdapter: STATE_ON
09-09 13:41:07.666  1259  1259 D BluetoothPhoneService: Bluetooth Adapter state : 12
09-09 13:41:07.666  1259  1259 I BluetoothPhoneService: queryPhoneState
09-09 13:41:07.666  1259  1259 I BluetoothPhoneService: updateHeadsetWithCallState : true
09-09 13:41:07.666  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:07.666  1259  1259 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
09-09 13:41:07.666  1259  1259 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:07.666  1259  1259 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,09-09 13:41:07.676  5814  5814 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:07.676  5814  5814 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-09 13:41:07.676  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:07.676  5814  5814 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-09 13:41:07.676  1694  2072 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
,09-09 13:41:07.676  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:07.676  1694  2072 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
,09-09 13:41:07.676  1694  2072 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
09-09 13:41:07.676  1694  2072 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
,09-09 13:41:07.676  5814  5814 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:41:07.686  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:07.686  6380  6380 E Zygote  : v2
09-09 13:41:07.686  1259  2320 I ActivityManager: Start proc 6380:com.samsung.android.email.provider/u0a34 for content provider com.samsung.android.email.provider/.provider.database.EmailProvider
09-09 13:41:07.686  6380  6380 E Zygote  : isSdpEnabledProcess - SDP enabled
09-09 13:41:07.686  6380  6380 I libpersona: KNOX_SDCARD checking this for 10034
09-09 13:41:07.686  6380  6380 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:07.686  6380  6380 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-09 13:41:07.686  5814  5814 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-09 13:41:07.686  6380  6380 E Zygote  : accessInfo : 64
09-09 13:41:07.686  6380  6380 E Zygote  : isSdpEnabledProcess - SDP enabled
09-09 13:41:07.686  6380  6380 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10034 / [uid]: 10034
09-09 13:41:07.686  6380  6380 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider 
,09-09 13:41:07.696  5814  5814 E BluetoothHeadset: BTStateChangeCB is registed
,09-09 13:41:07.696  5814  5814 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
09-09 13:41:07.696  5814  5814 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
09-09 13:41:07.696  5814  5814 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
09-09 13:41:07.696  5814  5814 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
,09-09 13:41:07.696  1694  2108 D BluetoothTile: handleUpdateState :  supported = true, enabled = true, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
09-09 13:41:07.696  1259  1989 D StatusBarManagerService: setIcon slot=bluetooth index=18 icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0204c1) visible user=0 )
,09-09 13:41:07.696  1259  1987 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-09 13:41:07.696  5814  5814 D BluetoothA2dp: Proxy object connected
,09-09 13:41:07.696  5814  5814 D A2dpProfile: Bluetooth service connected
,09-09 13:41:07.706  2569  6379 D A2dpStateMachine: getConnectedDevices : size=0
,09-09 13:41:07.716  6380  6380 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:41:07.716  6380  6380 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:07.736  5955  6005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:07.736  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:07.736  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:07.736  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:07.736  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:07.736  5955  6005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@55593b1 removed from the list
09-09 13:41:07.736  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:07.736  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4560096 removed from the list
09-09 13:41:07.736  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:07.736  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:07.736  5955  6005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:07.736  5955  6005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2689004 added. We now have 3 listener(s)
,09-09 13:41:07.736  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-09 13:41:07.736  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:07.736  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:07.736  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:07.736  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97eb9ed added. We now have 3 listener(s)
09-09 13:41:07.736  5955  6005 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:41:07.736  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:41:07.736  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:07.746  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:07.746  5955  6005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:07.746  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:07.746  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:07.746  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:07.746  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:07.746  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:07.746  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:07.746  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:07.746  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:07.746  6380  6380 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_M/lib/arm64
,09-09 13:41:07.746  5955  6005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:07.746  5955  6005 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:07.756  1259  1987 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,09-09 13:41:07.756  1259  1987 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,09-09 13:41:07.756  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:07.756  1259  1987 D WifiService: setWifiEnabled: false pid=5955, uid=10136
09-09 13:41:07.756  1259  1987 D SettingsProvider: isChangeAllowed() : name = wifi_on
,09-09 13:41:07.756  1259  1624 D WifiStateMachine: setFccChannel: channel = 0
09-09 13:41:07.756  1259  1624 D WifiController: [FCC]setFccChannel() is called !!!
09-09 13:41:07.756  1259  1624 D WifiController: MHS off and WIFI tunred off and move to mApStaDisabledState
09-09 13:41:07.756  1259  1624 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
09-09 13:41:07.756  1259  1624 D SecContentProvider: insert(), uri = 2
09-09 13:41:07.756  1259  1623 D WifiBigDataLog: getJsonFormat() - feature : ONOF
09-09 13:41:07.756  1259  1623 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.android.server.wifi.WifiStateMachine.insertLog:18843 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8707 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
09-09 13:41:07.756  1259  2124 E OsAgent :  Wifi Scan Always Available: 0
09-09 13:41:07.756  1259  2124 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-09 13:41:07.756  1259  2124 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: IS_WIFI_HARDWARE_ON: false
09-09 13:41:07.756  1259  1623 D WifiBigDataLog: init : 
,09-09 13:41:07.756  1259  2124 E OsAgent :  Wifi Scan Always Available: 0
09-09 13:41:07.756  1259  2124 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-09 13:41:07.756  1259  2124 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: IS_WIFI_HARDWARE_ON: false
09-09 13:41:07.756  1259  2149 E LocSvc_libulp: I/int ulp_msg_process_phone_setting_update(const UlpPhoneContextSettings*), context type: 0x4
09-09 13:41:07.756  1259  2149 E LocSvc_libulp:   gps enabled: 0
09-09 13:41:07.756  1259  2149 E LocSvc_libulp:  network position available 0
09-09 13:41:07.756  1259  2149 E LocSvc_libulp:  wifi setting enabled 0
09-09 13:41:07.756  1259  2149 E LocSvc_libulp:  battery charging 0, agps enabled 0, enh_location_services_enabled 0is_pip_user_setting_enabled 0
09-09 13:41:07.756  1259  2149 E LocSvc_libulp: I/int ulp_msg_process_system_update(UlpSystemEvent): systemEvent:4 
09-09 13:41:07.756  1259  2124 E OsAgent :  Wifi Scan Always Available: 0
09-09 13:41:07.756  1259  2124 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-09 13:41:07.756  1259  2124 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: IS_WIFI_HARDWARE_ON: false
,09-09 13:41:07.756  1259  2129 E LocSvc_LBSApiV02: E/virtual int lbs_core::LBSApiV02::wifiEnabledStatusInject(int):677]: Error : st = 2, ind.status = 1588437952
09-09 13:41:07.756  1259  1623 D WifiStateMachine: setFccChannelNative: channel = 0
09-09 13:41:07.756  1259  1623 D WifiNative-wlan0: callSECApiInt - ID [230]
,09-09 13:41:07.766  1259  1623 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-09 13:41:07.766  1259  1623 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:41:07.766  1259  1623 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:41:07.766  1259  1623 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,09-09 13:41:07.766  1259  1623 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:41:07.766  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:07.766  1259  1623 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:41:07.766  1259  1623 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:41:07.766  1259  1623 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:41:07.766  1259  1623 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,09-09 13:41:07.766  1694  2072 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-09 13:41:07.766  1694  2072 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,09-09 13:41:07.766  1259  1623 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:41:07.766  1259  1623 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:41:07.766  1694  2072 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-09 13:41:07.766  1694  2072 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
09-09 13:41:07.766  1259  1623 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 13:41:07.766  1259  1623 E WifiNative-wlan0: do suspend true
,09-09 13:41:07.766  1259  1622 D WifiP2pService: InactiveState{ what=143375 }
,09-09 13:41:07.766  1259  1622 D WifiP2pService: P2pEnabledState{ what=143375 }
09-09 13:41:07.776   552  1413 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:41:07.776  1259  6243 V AlarmManager:  remove PendingIntent] PendingIntent{153d59a: PendingIntentRecord{bab6ac2 android broadcastIntent}}
09-09 13:41:07.776  1259  1853 D RCPManagerService: exchangeData() failure , invalid userId
09-09 13:41:07.776   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 80
09-09 13:41:07.776   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:07.776   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:07.776   746  1442 I QC-NETMGR-LIB: Processing RTM_DELADDR
09-09 13:41:07.776   746  1442 I QC-NETMGR-LIB: Metainfo:  Family=2 PrefixLen=24 Scope=0x0 Index=15 Flags=[0x80]PERMANENT 
09-09 13:41:07.776   746  1442 I QC-NETMGR-LIB: Attribute: PrefixIPv4 addr [192.168.1.106]
09-09 13:41:07.776   746  1442 I QC-NETMGR-LIB: Attribute: LocalIPv4 addr [192.168.1.106]
09-09 13:41:07.776   746  1442 I QC-NETMGR-LIB: Attribute: BroadcastIPv4 addr [192.168.1.255]
09-09 13:41:07.776   746  1442 I QC-NETMGR-LIB: Attribute: Label name wlan0
09-09 13:41:07.776   746  1442 I QC-NETMGR-LIB: Attribute: Address Cache Info - prefered=-1 valid=-1 cstamp=0x2f21 tstamp=0x2f21
09-09 13:41:07.776   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [21]
09-09 13:41:07.776   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 15
09-09 13:41:07.776  1868  6311 V NativeCrypto: Read error: ssl=0x7f6bda2000: I/O error during system call, Connection timed out
09-09 13:41:07.776  1259  2008 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:41:07.776   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 64
09-09 13:41:07.776  1868  6311 V NativeCrypto: SSL shutdown failed: ssl=0x7f6bda2000: I/O error during system call, Broken pipe
09-09 13:41:07.776   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
,09-09 13:41:07.776   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:07.776  1259  2629 V AlarmManager:  remove PendingIntent] PendingIntent{ae30ecb: PendingIntentRecord{1a062e8 com.google.android.gms broadcastIntent}}
09-09 13:41:07.786   746  1442 I QC-NETMGR-LIB: Processing RTM_DELADDR
09-09 13:41:07.786   746  1442 I QC-NETMGR-LIB: Metainfo:  Family=10 PrefixLen=64 Scope=0xfd Index=15 Flags=[0x80]PERMANENT 
09-09 13:41:07.786   746  1442 I QC-NETMGR-LIB: Attribute: PrefixIPv6 addr [fe80:0000:0000:0000:4678:3eff:feeb:95ef]
09-09 13:41:07.786   746  1442 I QC-NETMGR-LIB: Attribute: Address Cache Info - prefered=-1 valid=-1 cstamp=0x2efd tstamp=0x2efd
09-09 13:41:07.786   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [21]
09-09 13:41:07.786   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 15
09-09 13:41:07.786  1868  6311 E GCM     : Wifi connection closed with errorCode 20
,09-09 13:41:07.786  1259  1989 D ConnectivityService: reportNetworkConnectivity(503, false) by 10010
09-09 13:41:07.786  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-09 13:41:07.786  1259  1630 E ConnectivityService: updateNetworkInfo()
09-09 13:41:07.786  1259  1630 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]
09-09 13:41:07.786  1259  1630 E ConnectivityService: updateNetworkInfo()
09-09 13:41:07.786  1259  1630 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
09-09 13:41:07.786  1259  1630 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:07.786  1259  1630 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 4
09-09 13:41:07.786  1259  1630 V NetworkStats: updateIfacesLocked()
09-09 13:41:07.786  1259  1630 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:41:07.786  1259  1623 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 13:41:07.786  1259  1622 D WifiP2pService: InactiveState{ what=131204 }
09-09 13:41:07.786  6221  6221 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
09-09 13:41:07.786  1259  1622 D WifiP2pService: P2pEnabledState{ what=131204 }
09-09 13:41:07.786  6221  6221 I wpa_supplicant: P2P: Clear a pre-passphrase (State NONE)
09-09 13:41:07.786  1259  1259 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-09 13:41:07.786  1259  1622 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-09 13:41:07.786  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:07.786  1259  1630 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:07.786  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:07.786  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:07.786  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:07.786  1259  1630 V NetworkStats: performPollLocked() took 4ms
09-09 13:41:07.786  1259  1259 I Wifi-SensorMonitor: enable sensor monitoring : false
09-09 13:41:07.796  1259  1259 D SensorHAL: GRIP_WIFI  set_enable 
09-09 13:41:07.796  1259  6242 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: ValidatedState{ when=-8ms what=532488 arg1=10010 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:07.796  1259  6242 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=-8ms what=532488 arg1=10010 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:07.796  1259  6242 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Forcing reevaluation for UID 10010
09-09 13:41:07.796  1259  6242 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:07.796  1259  6242 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Validated
09-09 13:41:07.796  1259  1259 D SensorHAL: sx9310_grip_wifi: power-off.
09-09 13:41:07.796  1259  1259 E Sensors : ~SensorEventQueue 0
09-09 13:41:07.796  1259  1259 E         : BitTube(): close sendFd (361)
09-09 13:41:07.796  1259  1259 E         : BitTube(): close receivedFd (358)
09-09 13:41:07.796  1259  1259 D SensorManager: unregisterListener ::   
09-09 13:41:07.796  1259  1259 D WifiNative-wlan0: callSECApiInt - ID [70]
,09-09 13:41:07.796  1259  1259 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
09-09 13:41:07.796  1259  1259 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]
09-09 13:41:07.796  1259  1259 D HS20StateMachine: checkifOSUAP  null disconnectedFromSsid"NG700"
09-09 13:41:07.796  1259  1259 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
09-09 13:41:07.796  1259  1628 I WifiHs20Service: Message received 5007
,09-09 13:41:07.796  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-09 13:41:07.796  1974  1974 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,09-09 13:41:07.796  1694  2108 D QSTile.WifiTile: handleUpdateState  cb.changed 14 wifiEnabled : ON 
,09-09 13:41:07.806  1259  1630 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:07.806  1259  1630 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]
09-09 13:41:07.806  1259  1630 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
09-09 13:41:07.806  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:07.806  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:07.806  1259  1630 D ConnectivityService: sending notification LOST for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:07.806  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
09-09 13:41:07.806  1259  1630 D ConnectivityService: sending notification LOST for NetworkRequest [ id=5, legacyType=-1, [] ]
09-09 13:41:07.806  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:07.806  1259  1630 D ConnectivityService: sending notification LOST for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:07.806  1259  1630 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:07.806  1259  1622 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-09 13:41:07.806  1259  1623 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:07.806  1259  1623 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:07.806  1259  1623 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 13:41:07.806  1259  1623 D WIFI    : evalRequest
09-09 13:41:07.806  1259  1623 D WIFI    :   done
09-09 13:41:07.806  1259  1623 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:07.806  1259  1623 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:07.806  1259  1623 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 13:41:07.806  1259  1623 D WIFI    : evalRequest
09-09 13:41:07.806  1259  1623 D WIFI    :   done
09-09 13:41:07.806  1259  1623 D WIFI_UT : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:07.806  1259  1623 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:07.806  1259  1623 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 13:41:07.806  1259  1623 D WIFI_UT : evalRequest
09-09 13:41:07.806  1259  1623 D WIFI_UT :   done
09-09 13:41:07.806  1259  6242 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:07.806  1259  1651 D Ethernet: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:07.806  1259  1651 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
09-09 13:41:07.806  1259  1651 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 13:41:07.806  1259  1651 D Ethernet: evalRequest
09-09 13:41:07.806  1259  1651 D Ethernet:   done
09-09 13:41:07.806  1259  1637 D ConnectivityService: getVpnConfig > userId : 0
,09-09 13:41:07.806  1259  1416 D EntConnectivity: Not allowed due to - mEnabled false
09-09 13:41:07.806  1259  1417 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:07.806  1259  1417 I WifiDisplayAdapter: onP2pDisconnected
09-09 13:41:07.806  1259  1417 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 13:41:07.806  1259  1417 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-09 13:41:07.816  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:07.816  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:07.816  1259  1417 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
09-09 13:41:07.816  1259  1417 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-09 13:41:07.816  1259  1417 D WifiDisplayController: disconnect
09-09 13:41:07.816  1259  1417 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 13:41:07.816  1259  1622 D SecContentProvider: insert(), uri = 2
09-09 13:41:07.816  1259  1259 D RttService: SCAN_AVAILABLE : 1
09-09 13:41:07.816  1259  1650 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:41:07.816  1259  1622 D WifiP2pService: P2pDisablingState
09-09 13:41:07.816  1259  1622 D SecContentProvider: insert(), uri = 2
09-09 13:41:07.816  1259  1622 D WifiP2pService: P2pDisablingState{ what=147458 }
09-09 13:41:07.816  1259  1622 D WIFI_P2P: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:07.816  1259  1622 D WifiP2pService: p2p socket connection lost
09-09 13:41:07.816  1259  1622 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:07.816  1259  1622 D WifiP2pService: P2pDisabledState
09-09 13:41:07.816  1259  1623 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 13:41:07.816  1259  1622 D WifiP2pService: P2pDisabledState{ what=143375 }
09-09 13:41:07.816  1259  1623 E WifiNative-wlan0: do suspend true
09-09 13:41:07.826  1694  1694 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 148
09-09 13:41:07.816  1259  1622 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 13:41:07.826  1259  1622 D WifiP2pService: DefaultState{ what=143375 }
09-09 13:41:07.816  1259  1622 D WIFI_P2P: evalRequest
09-09 13:41:07.816  1259  1622 D WIFI_P2P:   done
09-09 13:41:07.826  1694  1694 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 13:41:07.826  1694  1694 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-09 13:41:07.826  1259  1721 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{45945c1 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1f7ee83 2608:com.samsung.android.providers.context/u0a5}
,09-09 13:41:07.826  1259  1259 I ActivityManager: Killing 5717:com.samsung.android.sm.devicesecurity/5012 (adj 15): DHA:empty #31
,09-09 13:41:07.826  1259  1259 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-09 13:41:07.826  1259  1259 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
09-09 13:41:07.826  1259  1259 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
,09-09 13:41:07.836  1259  1721 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{189b166 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1f7ee83 2608:com.samsung.android.providers.context/u0a5}
,09-09 13:41:07.836  1259  1417 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-09 13:41:07.836  1259  1417 I WifiDisplayAdapter: onP2pDisconnected
09-09 13:41:07.836  1259  1417 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 13:41:07.836  1259  1417 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-09 13:41:07.836  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-09 13:41:07.846  6336  6353 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-09 13:41:07.846  1694  1694 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-09 13:41:07.846  1694  1694 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-09 13:41:07.846  1694  1694 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-09 13:41:07.846  1259  2320 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 13:41:07.846  1259  1325 D RCPManagerService: exchangeData() failure , invalid userId
09-09 13:41:07.846  1259  2008 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{691cca7 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{aad911c 5814:com.android.settings/1000}
,09-09 13:41:07.846  1694  1694 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-09 13:41:07.856   552  1413 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 13:41:07.856  5814  5814 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1311 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 13:41:07.856  1259  1325 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{691cca7 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1f7ee83 2608:com.samsung.android.providers.context/u0a5}
,09-09 13:41:07.866  1259  1325 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{691cca7 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fadd615 1868:com.google.android.gms.persistent/u0a10}
,09-09 13:41:07.866  1868  1868 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,09-09 13:41:07.866  1259  1325 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{691cca7 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{aad911c 5814:com.android.settings/1000}
,09-09 13:41:07.876  5814  5814 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:41:07.876  5814  5814 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:07.876  5814  5814 D BluetoothStatusReceiver: AdapterStateChanged :: state = 10
,09-09 13:41:07.886  1259  2621 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{691cca7 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f4c1a96 6322:com.samsung.android.intelligenceservice2/5010}
,09-09 13:41:07.886   552  1413 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-09 13:41:07.886   552  1413 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:41:07.886  1259  1630 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,fe80::4678:3eff:feeb:95ef/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } wasDefault=true
09-09 13:41:07.886  1259  1630 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
09-09 13:41:07.886  1259  1630 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:07.886  1259  1416 D EntConnectivity: Not allowed due to - mEnabled false
,09-09 13:41:07.886  1259  2621 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{691cca7 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{871053d 2569:com.android.bluetooth/1002}
,09-09 13:41:07.896  1259  1623 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-09 13:41:07.896  1694  1694 D HeadsetProfile: Bluetooth service connected
,09-09 13:41:07.896  5814  5814 D HeadsetProfile: Bluetooth service connected
,09-09 13:41:07.906  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-09 13:41:07.906  1974  1974 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,09-09 13:41:07.916  2569  2569 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2) for masId0
,09-09 13:41:07.916  1259  1378 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:07.916  1259  1378 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:07.916  1259  1378 D GpsLocationProvider: handleMessage msg = 4
,09-09 13:41:07.916  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-09 13:41:07.926  1974  1988 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,09-09 13:41:07.926  3109  3109 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@3390fb1 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-09 13:41:07.926  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:07.926  1259  1621 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:07.926  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:07.926  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:07.926  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:07.926  1259  1621 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,09-09 13:41:07.926  1974  1988 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,09-09 13:41:07.936  5955  5955 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-09 13:41:07.936  1259  1378 D TelephonyManager: getDataEnabled: retVal=true
,09-09 13:41:07.936  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-09 13:41:07.936  5955  5955 D BluetoothAdapter: STATE_ON
,09-09 13:41:07.936  1259  2008 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.devicesecurity, Auto Run ON
09-09 13:41:07.936  1259  2008 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5717 ,hash=105354972 ,name=com.samsung.android.sm.devicesecurity
,09-09 13:41:07.936  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:07.936  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:07.936  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:07.936  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:07.936  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:07.936  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:07.936  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:07.936  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:07.946  5955  5955 D BluetoothAdapter: STATE_ON
,09-09 13:41:07.946  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:07.946  1259  1989 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{691cca7 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9853617 6336:com.google.android.apps.maps/u0a89}
,09-09 13:41:07.946  5955  5955 D BluetoothAdapter: STATE_ON
,09-09 13:41:07.946  1259  1989 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{94a4eb5 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{aad911c 5814:com.android.settings/1000}
,09-09 13:41:07.946  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:07.946  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:07.946  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:07.946  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:07.946  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:07.946  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:07.946  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:07.946  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:07.956  5955  5955 D BluetoothAdapter: STATE_ON
,09-09 13:41:07.956  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:07.956   552  1413 E Netd    : netlink response contains error (No such file or directory)
09-09 13:41:07.956  1259  1630 D ConnectivityService: nai.networkMonitor.doQuit()
09-09 13:41:07.956  1259  1630 D ConnectivityService: setProvNotificationVisibleIntent SIGN_IN visible=false networkType=WIFI extraInfo=null highPriority=false
09-09 13:41:07.956  1259  1630 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: doQuit - quitNow()
09-09 13:41:07.956  1259  1630 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
09-09 13:41:07.956  1259  1630 E ConnectivityService: updateNetworkInfo()
09-09 13:41:07.956  1259  1630 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-09 13:41:07.956  1259  1630 D ConnectivityService: EVENT_PROVISIONING_NOTIFICATION is sent for TYPE_MOBILE.
09-09 13:41:07.956  1259  1630 E ConnectivityService: EVENT_NETWORK_TESTED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,fe80::4678:3eff:feeb:95ef/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-09 13:41:07.956  1259  1630 E ConnectivityService: updateNetworkInfo()
09-09 13:41:07.956  1259  1630 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
09-09 13:41:07.956  1259  1623 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
09-09 13:41:07.956  5955  5955 D BluetoothAdapter: STATE_ON
,09-09 13:41:07.966  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:07.966  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:07.966  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:07.966  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:07.966  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:07.966  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:07.966  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:07.966  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:07.966  5955  5955 D BluetoothAdapter: STATE_ON
,09-09 13:41:07.966  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:07.966  6417  6417 E Zygote  : v2
09-09 13:41:07.966  1259  2304 I ActivityManager: Start proc 6417:com.sec.android.provider.badge/u0a1 for content provider com.sec.android.provider.badge/.BadgeProvider
09-09 13:41:07.966  6417  6417 I libpersona: KNOX_SDCARD checking this for 10001
09-09 13:41:07.966  6417  6417 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:07.966  6417  6417 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-09 13:41:07.966  6417  6417 E Zygote  : accessInfo : 0
,09-09 13:41:07.966  6417  6417 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.provider.badge 
09-09 13:41:07.966  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:07.966  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:07.976  2569  2569 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:41:07.976  2569  2569 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:41:07.976  1259  2124 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-09 13:41:07.976  1259  1259 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@8bbb9d8
09-09 13:41:07.976  1259  1259 D BluetoothHeadset: registerMessageListener
09-09 13:41:07.976  1259  2124 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 0, Mac address valid: false, AP MAC address: [00:00:00:00:00:00], Wifi-Ap SSID Valid: false, SSID: 
,09-09 13:41:07.976  1694  1694 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:07.976  1259  2136 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 131 QMI_LOC_NOTIFY_WIFI_ATTACHMENT_STATUS_REQ_V02
09-09 13:41:07.976  2569  6413 D HeadsetService: registerMessageListener
09-09 13:41:07.976  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:07.976  2569  2569 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:41:07.976  2569  2569 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:41:07.976  2569  6413 D HeadsetService: registerMessageListener
09-09 13:41:07.976  1259  1259 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
09-09 13:41:07.976  1694  1694 D HotspotTile: onReceive : 0, 0
09-09 13:41:07.976  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:07.976  2569  6349 D HeadsetStateMachine: Disconnected process message: 70, size: 0
09-09 13:41:07.976  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:07.976  2569  6349 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@b56d839
09-09 13:41:07.976  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:07.976  1259  1259 I Telecom : BluetoothManager : register MessageListener
09-09 13:41:07.976  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:07.976  1259  1259 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-09 13:41:07.976  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:07.976  1259  1259 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
09-09 13:41:07.976  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:07.976  1259  1259 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false]
09-09 13:41:07.976  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:07.976  1259  1259 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
09-09 13:41:07.976  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:07.976  1259  1628 I WifiHs20Service: Message received 5007
09-09 13:41:07.976  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:07.976  1259  1259 D LocSvc_java: onReceive
09-09 13:41:07.976  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:07.976  1259  1259 D LocSvc_java: got connectivity action
09-09 13:41:07.976  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 ,13:41:07.976  1259  1416 D Tethering: MasterInitialState.processMessage what=3
09-09 13:41:07.976  1259  1259 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:07.976  1259  1259 D LocSvc_java: broadcast - no network connections
09-09 13:41:07.976  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-09 13:41:07.976  1259  1259 D LocSvc_java: Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
09-09 13:41:07.976  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:07.976  1259  1259 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 13:41:07.976  1259  1259 V MARsPolicyManager: DataConnection: false
09-09 13:41:07.976  1259  1259 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:07.976  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:07.976  1259  1259 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:07.976  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:07.976  1259  1628 I WifiHs20Service: Message received 5011
09-09 13:41:07.976  1259  1874 V AlarmManager:  remove PendingIntent] PendingIntent{39adc39: PendingIntentRecord{51f527e android broadcastIntent}}
09-09 13:41:07.986  1259  1631 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
09-09 13:41:07.986  2569  2569 D ObexServerSockets: Succeed to create listening sockets 
09-09 13:41:07.986  1259  1259 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
09-09 13:41:07.986  2569  2569 D ObexServerSockets: startAccept()
09-09 13:41:07.986  1259  1259 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
09-09 13:41:07.986  1694  2108 D QSTile.WifiTile: handleUpdateState  cb.changed 5 wifiEnabled : OFF 
09-09 13:41:07.986  1259  1259 D LocSvc_java: handleMessage msg = 4
09-09 13:41:07.986  1259  1259 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 13:41:07.986  1974  5601 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
09-09 13:41:07.986  1259  1259 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true] info.getType():1
09-09 13:41:07.986  2569  2569 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-09 13:41:07.986  2569  2569 D BluetoothSdpJni: SDP Create record success - handle: 0
09-09 13:41:07.986  1974  2707 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@bc3bef5, selection=nullselectionArgs=null, sort=name ASC
09-09 13:41:07.986  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
,09-09 13:41:07.986  1974  5601 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-09 13:41:07.986  1259  1631 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,09-09 13:41:07.986  2970  2970 I WCNSS_FILTER: do_write: IBS write: fc
09-09 13:41:07.986  1259  6428 I ApplicationPolicy: updateDataUsageMap
09-09 13:41:07.986  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,09-09 13:41:07.986  2569  6430 D ObexServerSockets: Accepting socket connection for masId0
,09-09 13:41:07.986  2569  6429 D ObexServerSockets: Accepting socket connection for masId0
09-09 13:41:07.986  1259  1631 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
09-09 13:41:07.986  1974  1985 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,09-09 13:41:07.986  1974  1985 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-09 13:41:07.986  1694  1694 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 148
09-09 13:41:07.986  1259  1631 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
09-09 13:41:07.986  1259  1989 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{94a4eb5 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1f7ee83 2608:com.samsung.android.providers.context/u0a5}
,09-09 13:41:07.996  2569  3151 D A2dpStateMachine: getConnectedDevices : size=0
,09-09 13:41:07.996  1259  2310 I ActivityManager: Killing 5840:com.samsung.android.bbc.bbcagent/1000 (adj 15): DHA:empty #31
,09-09 13:41:07.996  1259  2008 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{94a4eb5 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fadd615 1868:com.google.android.gms.persistent/u0a10}
,09-09 13:41:08.006  1868  1868 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,09-09 13:41:08.006  1974  2707 D TelephonyProvider: query: match = 5
09-09 13:41:08.006  1259  2008 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{94a4eb5 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{aad911c 5814:com.android.settings/1000}
09-09 13:41:08.006  1974  2707 D TelephonyProvider: getPreferredApnId(subId = 2147483643),return -1
09-09 13:41:08.006  1974  2707 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
09-09 13:41:08.006  5814  5814 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:08.006  5814  5814 D BluetoothStatusReceiver: AdapterStateChanged :: state = 11
09-09 13:41:08.006  6417  6417 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:41:08.006  6417  6417 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:08.006  1259  2008 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{94a4eb5 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f4c1a96 6322:com.samsung.android.intelligenceservice2/5010}
,09-09 13:41:08.016  1259  1378 E GpsLocationProvider: No APN found to select.
,09-09 13:41:08.016  1259  2310 I ActivityManager: Killing 5853:com.google.android.apps.docs/u0a71 (adj 15): DHA:empty #31
,09-09 13:41:08.016  1259  2310 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{94a4eb5 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{871053d 2569:com.android.bluetooth/1002}
,09-09 13:41:08.026  1259  2310 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{94a4eb5 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9853617 6336:com.google.android.apps.maps/u0a89}
,09-09 13:41:08.036  1259  1987 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f9e2131 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{aad911c 5814:com.android.settings/1000}
,09-09 13:41:08.036  6417  6417 W System  : ClassLoader referenced unknown path: /system/priv-app/BadgeProvider_M/lib/arm64
09-09 13:41:08.036  5814  5814 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1311 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 13:41:08.036  6417  6417 D BadgeProvider: onCreate
,09-09 13:41:08.036  6417  6417 D BadgeProvider: DatabaseHelper
09-09 13:41:08.036  1259  2629 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f9e2131 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1f7ee83 2608:com.samsung.android.providers.context/u0a5}
,09-09 13:41:08.046  1259  1989 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f9e2131 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fadd615 1868:com.google.android.gms.persistent/u0a10}
09-09 13:41:08.046  1868  1868 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,09-09 13:41:08.046  5814  5814 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:41:08.056  1259  1637 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f9e2131 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{aad911c 5814:com.android.settings/1000}
,09-09 13:41:08.056  5814  5814 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:08.056  5814  5814 D BluetoothStatusReceiver: AdapterStateChanged :: state = 12
,09-09 13:41:08.056  1259  1325 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f9e2131 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f4c1a96 6322:com.samsung.android.intelligenceservice2/5010}
,09-09 13:41:08.056  1259  2294 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f9e2131 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{871053d 2569:com.android.bluetooth/1002}
,09-09 13:41:08.056  2569  2569 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b2cb7b
09-09 13:41:08.056  2569  2569 D BtConfig.SecureMode: isSecureModeOn:false
,09-09 13:41:08.066  6417  6427 D BaseReflect: null getOwnClass TEST
,09-09 13:41:08.066  6417  6427 D MethodReflector: android.content.ContentResolver getClass TEST
09-09 13:41:08.066  6417  6427 D BaseReflect: class android.content.ContentResolver isSupportClass TEST
09-09 13:41:08.066  6417  6427 D BaseReflect: class android.content.ContentResolver getOwnClass TEST
,09-09 13:41:08.066  1259  1989 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f9e2131 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9853617 6336:com.google.android.apps.maps/u0a89}
,09-09 13:41:08.066  1259  2310 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5840 ,hash=83382443 ,name=com.samsung.android.bbc.bbcagent
09-09 13:41:08.066  1259  2310 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.bbc.bbcagent, Auto Run ON
,09-09 13:41:08.066  6417  6427 D MethodReflector: notifyChange is called
,09-09 13:41:08.066  6417  6427 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
09-09 13:41:08.066  1995  1995 D Launcher.Model: reloadBadges entered.
09-09 13:41:08.066  6417  6427 D BadgeProvider: sendNotify, [notify] : null
09-09 13:41:08.076  1259  1721 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{eb12d97 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1f7ee83 2608:com.samsung.android.providers.context/u0a5}
09-09 13:41:08.076  1995  1995 D Launcher.Model: reloadBadges entered.
,09-09 13:41:08.076  6417  6427 D BadgeProvider: update, getCallingPackage() : com.samsung.android.email.provider
09-09 13:41:08.076  6417  6427 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
09-09 13:41:08.076  6417  6427 D BadgeProvider: update, [uri.query] : null
09-09 13:41:08.076  6417  6427 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-09 13:41:08.076  6417  6427 D BadgeProvider: update, [UpdateCount] : 1
,09-09 13:41:08.076  1259  1721 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{71e9b84 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{54b8953 6035:com.sec.android.diagmonagent/1000}
,09-09 13:41:08.076  6035  6035 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:08.076  6035  6035 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
09-09 13:41:08.076  6035  6035 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,09-09 13:41:08.086  6035  6035 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-09 13:41:08.086  6417  6427 D BadgeProvider: query, [selection] : null
,09-09 13:41:08.086  1259  1987 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{71e9b84 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a6a9da7 6058:com.sec.app.RilErrorNotifier/1000}
09-09 13:41:08.086  6058  6058 I PhoneErrorReceiver: onReceive
09-09 13:41:08.086  6058  6058 I MIPErrReceiver: isWiFiConnected
,09-09 13:41:08.086  1259  2320 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-09 13:41:08.086  1259  1987 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{71e9b84 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8c16b67 5671:com.enhance.gameservice/u0a79}
,09-09 13:41:08.086  1995  2125 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
09-09 13:41:08.086  1995  2125 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
09-09 13:41:08.086  1995  2125 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
09-09 13:41:08.096  1995  2125 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
,09-09 13:41:08.096  1259  1987 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{71e9b84 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f996d43 6074:com.sec.knox.switcher/1000}
,09-09 13:41:08.096  6074  6074 I usagelog: received in receiver
09-09 13:41:08.096  6074  6074 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
09-09 13:41:08.096  6074  6074 I KnoxUsageLogPro: premStatus:2
,09-09 13:41:08.096  6074  6074 I KnoxUsageLogPro: isEulaShown : false
09-09 13:41:08.096  6074  6074 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,09-09 13:41:08.096  1259  2294 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7829f6d u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fea34f9 6088:com.samsung.android.app.FileShareClient/5005}
,09-09 13:41:08.096  6088  6088 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:41:08.096  6088  6088 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-09 13:41:08.096  6088  6088 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 13:41:08.106  6221  6221 I wpa_supplicant: Blacklist: Clear (all) 
09-09 13:41:08.106  6221  6221 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,09-09 13:41:08.106  6417  6427 D BadgeProvider: query, [selection] : null
09-09 13:41:08.106  1259  2294 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7829f6d u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dcd9326 5659:com.samsung.android.app.FileShareServer/5005}
,09-09 13:41:08.106  5659  5659 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:41:08.106  1995  2125 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
09-09 13:41:08.106  1995  2125 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
09-09 13:41:08.106  1995  2125 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
09-09 13:41:08.106  1995  2125 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
09-09 13:41:08.106  5659  5659 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,09-09 13:41:08.106  5659  5659 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,09-09 13:41:08.116  1259  2629 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a7f47a2 u0 com.google.android.gcm.DISCONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9ff3cb0 5496:com.google.android.talk/u0a84}
,09-09 13:41:08.126  1259  2629 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9510c33 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{54b8953 6035:com.sec.android.diagmonagent/1000}
,09-09 13:41:08.126  6035  6035 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:08.126  1259  1721 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.docs, Auto Run ON
,09-09 13:41:08.126  1259  1721 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5853 ,hash=7473825 ,name=com.google.android.apps.docs
09-09 13:41:08.126  6035  6035 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
09-09 13:41:08.126  6035  6035 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-09 13:41:08.126  1259  2008 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9510c33 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a6a9da7 6058:com.sec.app.RilErrorNotifier/1000}
,09-09 13:41:08.126  6058  6058 I PhoneErrorReceiver: onReceive
09-09 13:41:08.126  6058  6058 I MIPErrReceiver: isWiFiConnected
,09-09 13:41:08.126  1259  2304 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-09 13:41:08.136  1259  2320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9510c33 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8c16b67 5671:com.enhance.gameservice/u0a79}
,09-09 13:41:08.136  1259  2320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9510c33 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f996d43 6074:com.sec.knox.switcher/1000}
,09-09 13:41:08.136  6074  6074 I usagelog: received in receiver
09-09 13:41:08.136  6074  6074 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
09-09 13:41:08.136  6074  6074 I KnoxUsageLogPro: premStatus:2
,09-09 13:41:08.136  6074  6074 I KnoxUsageLogPro: isEulaShown : false
09-09 13:41:08.136  6074  6074 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,09-09 13:41:08.146  1259  2320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{babebf0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a8d25ef 1259:system/1000}
,09-09 13:41:08.146  1259  1259 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{babebf0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3be25b9 2236:com.google.android.gms/u0a10}
,09-09 13:41:08.146  2236  2236 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 13:41:08.146  2236  3189 I iu.UploadsManager: num queued entries: 0
09-09 13:41:08.146  1259  2629 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{babebf0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3be25b9 2236:com.google.android.gms/u0a10}
,09-09 13:41:08.156  2236  3189 I iu.UploadsManager: num updated entries: 0
,09-09 13:41:08.156  2236  3189 I iu.SyncManager: NEXT; no task
,09-09 13:41:08.156  1259  2629 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{babebf0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fadd615 1868:com.google.android.gms.persistent/u0a10}
,09-09 13:41:08.166  1259  2629 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{babebf0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{41777ec 6102:com.policydm/1000}
,09-09 13:41:08.166   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-09 13:41:08.166   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:08.166   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:08.166   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:41:08.166   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=16 Family=0 Type=0x1 Change=[0x1]UP  Flags=[0x1002]BROADCAST MULTICAST 
,09-09 13:41:08.166   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:41:08.166   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:41:08.166   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 16, disable link
09-09 13:41:08.166  6221  6221 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-09 13:41:08.166   552  1406 D Netd    : Iface p2p0 link down
,09-09 13:41:08.176  6102  6102 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,09-09 13:41:08.176  6221  6221 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 13:41:08.176  6221  6221 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
,09-09 13:41:08.176   552  1406 D Netd    : Iface wlan0 link down
09-09 13:41:08.176   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-09 13:41:08.176   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
,09-09 13:41:08.176   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:08.176   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:41:08.176   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=15 Family=0 Type=0x1 Change=[0x0] Flags=[0x1003]UP BROADCAST MULTICAST 
09-09 13:41:08.176   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:41:08.176   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:41:08.176   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 15, disable link
09-09 13:41:08.176   552  1406 D Netd    : Iface wlan0 link down
09-09 13:41:08.176  1259  1416 D Tethering: InitialState.processMessage what=4
09-09 13:41:08.176  1259  1416 D Tethering: NAP Supported and not Wifi Model
09-09 13:41:08.176   552  1406 D Netd    : Iface wlan0 link down
09-09 13:41:08.176   552  1406 D Netd    : Iface wlan0 link down
09-09 13:41:08.176   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-09 13:41:08.176   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:08.176   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 76
09-09 13:41:08.176   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:08.176   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 72
09-09 13:41:08.176   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:08.176   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:08.176   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:41:08.176   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=15 Family=0 Type=0x1 Change=[0x0] Flags=[0x1003]UP BROADCAST MULTICAST 
09-09 13:41:08.176   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:41:08.176   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:41:08.176   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 15, disable link
09-09 13:41:08.176   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
,09-09 13:41:08.176   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:41:08.176   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=15 Family=0 Type=0x1 Change=[0x0] Flags=[0x1043]UP BROADCAST RUNNING MULTICAST 
09-09 13:41:08.176   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:41:08.176   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:41:08.176   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 15, disable link
09-09 13:41:08.176   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:08.176   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:41:08.176   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=15 Family=0 Type=0x1 Change=[0x0] Flags=[0x1043]UP BROADCAST RUNNING MULTICAST 
09-09 13:41:08.176   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:41:08.176   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:41:08.176   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 15, disable link
,09-09 13:41:08.176  1259  1416 E Tethering: No numeric data
,09-09 13:41:08.176  6102  6102 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,09-09 13:41:08.186  6102  6102 I DBG_POLICYDM: [com.policydm.XDMService(574/llIlIllllllllllllllI)] get NotibarState : 0
,09-09 13:41:08.186  1259  1416 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 13:41:08.186  1259  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:08.186  1259  1620 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:41:08.186  1694  1694 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 13:41:08.186  1694  1694 D HotspotTile: updateTetherState():false, false
,09-09 13:41:08.186  1259  1721 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{babebf0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{41777ec 6102:com.policydm/1000}
,09-09 13:41:08.186  6102  6102 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:08.186  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:08.186  1259  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:08.186  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:08.186  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:08.186  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:08.186  1259  1620 V NetworkStats: performPollLocked() took 5ms
,09-09 13:41:08.196  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:08.196  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:08.196  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5b6c569 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{345119e 6197:com.samsung.android.securitylogagent/1000}
,09-09 13:41:08.196  1259  1385 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{babebf0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{56d884 6129:com.osp.app.signin/u0a27}
,09-09 13:41:08.206  6129  6129 I SA      : [OR] onReceive log=[SA = 2.2.01-51 V = 23 HWD = 2048X1536 2.0 dpi = 320  SIZE = 4 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = gts28velte P = gts28veltexx I = MMB29M M = SM-T719 OKLEFT false DIS MMB29M.T719XXU1APF6 PSS = 8.00525302084415  ]
,09-09 13:41:08.206  6129  6129 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,09-09 13:41:08.206  6129  6129 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-09 13:41:08.206  1259  2621 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5b6c569 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5827062 5955:com.test.thalitest/u0a136}
09-09 13:41:08.206  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.206  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.206  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.206  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.206  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.206  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.206  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.206  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.206  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.206  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.206  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.206  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-09 13:41:08.206  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.206  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.206  1259  2310 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false,, isAvailable: true]
,09-09 13:41:08.206  1259  1989 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{72e3bee u-1 android.net.conn.TETHER_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a8d25ef 1259:system/1000}
,09-09 13:41:08.206  6129  6129 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-09 13:41:08.206  6129  6129 I SA      : [OR] == isSIMCardReady false ==
,09-09 13:41:08.216  6129  6129 I SA      : [SCU] == networkStateCheck == false
09-09 13:41:08.216  6129  6129 I SA      : [OR] onReceive END
,09-09 13:41:08.216  1259  1637 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{babebf0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5827062 5955:com.test.thalitest/u0a136}
,09-09 13:41:08.216  1259  1325 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.216  1259  1325 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.216  1259  1325 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.216  1259  1325 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.216  1259  1325 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.216  1259  1325 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.216  1259  1325 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.216  1259  1325 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.216  1259  1325 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.216  1259  1325 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.216  1259  1325 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.216  1259  1325 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-09 13:41:08.216  1259  1325 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.216  1259  1325 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.216  1259  1325 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-09 13:41:08.216  1259  2629 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{babebf0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1ce268a 5214:com.wssyncmldm/1000}
,09-09 13:41:08.226  1259  1324 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{babebf0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a6a9da7 6058:com.sec.app.RilErrorNotifier/1000}
,09-09 13:41:08.226  6058  6058 I PhoneErrorReceiver: onReceive
09-09 13:41:08.226  6058  6058 V PhoneErrorReceiver: beginStartingService
,09-09 13:41:08.226  6058  6058 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1311 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.sec.app.RilErrorNotifier.PhoneErrorReceiver.beginStartingService:194 com.sec.app.RilErrorNotifier.PhoneErrorReceiver.onReceiveWithPrivilege:171 
,09-09 13:41:08.236  6058  6058 V PhoneErrService: Creating SmsReceiverService
09-09 13:41:08.236  6058  6058 V MIP_PhoneErrService: mTelephonyManager is not null
,09-09 13:41:08.236  1259  2008 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{babebf0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ace8b17 4424:com.sec.spp.push/u0a26}
,09-09 13:41:08.236  4424  4424 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:08.236  4424  4424 E SPPClientService: [SystemStateMoniter] Current Time : 124563
,09-09 13:41:08.236  4424  4424 E SPPClientService: [SystemStateMoniter] No Connect : true
,09-09 13:41:08.236  1259  1989 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{babebf0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ce11b0e 2481:android.process.media/u0a33}
,09-09 13:41:08.236  2481  2481 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:08.246  6058  6058 V PhoneErrService: Starting #1: Bundle[mParcelledData.dataSize=448]
09-09 13:41:08.246  6058  6058 I PhoneErrService: mResultCode: 0
09-09 13:41:08.246  6058  6058 V MIP_PhoneErrService: onDataConnectionState : -1
09-09 13:41:08.246  6058  6434 V PhoneErrService: Handling incoming message: { when=0 what=0 arg1=1 obj=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.sec.app.RilErrorNotifier/.PhoneErrService bqHint=3 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } target=com.sec.app.RilErrorNotifier.PhoneErrService$ServiceHandler }
09-09 13:41:08.246  6058  6434 V PhoneErrorReceiver: finishStartingService
,09-09 13:41:08.246  1259  2304 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{babebf0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6454e69 6147:com.samsung.android.SettingsReceiver/1000}
,09-09 13:41:08.246  4424  6435 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-09 13:41:08.246  6058  6058 V PhoneErrService: Destroying PhoneErrorReceiverService
,09-09 13:41:08.256  1259  2629 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{babebf0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bb1cd0d 2464:com.microsoft.skydrive/u0a93}
,09-09 13:41:08.256  1259  2320 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-09 13:41:08.266  1259  2621 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
,09-09 13:41:08.266  1259  2621 D PackageManager: findPreferredActivity: No PreferredActivities set
09-09 13:41:08.266  1259  2621 I PackageManager: No preferred activity: intent should not be shown
,09-09 13:41:08.266  5955  6005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:08.266  5955  6005 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,09-09 13:41:08.276  1259  2294 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,09-09 13:41:08.276  1259  2294 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,09-09 13:41:08.276  1259  2294 D WifiService: System do NOT have com.sec.feature.sensorhub feature
09-09 13:41:08.276  1259  2294 D WifiService: Wi-Fi on and Screen on , checkSensorStatus !!
09-09 13:41:08.276  1259  2294 D WifiService: setWifiEnabled: true pid=5955, uid=10136
,09-09 13:41:08.276  1259  2304 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{babebf0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e6698f 6172:com.google.android.apps.photos/u0a97}
,09-09 13:41:08.276  1259  2294 W WifiService: Failed getting userId using ActivityManagerNative
09-09 13:41:08.276  1259  2294 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5955, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
09-09 13:41:08.276  1259  2294 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28130)
09-09 13:41:08.276  1259  2294 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2542)
09-09 13:41:08.276  1259  2294 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2530)
09-09 13:41:08.276  1259  2294 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
09-09 13:41:08.276  1259  2294 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
09-09 13:41:08.276  1259  2294 W ActivityManager: Permission Denial: getCurrentUser() from pid=5955, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
09-09 13:41:08.276  1259  1623 D WifiBigDataLog: getJsonFormat() - feature : ONOF
09-09 13:41:08.276  1259  2294 D SettingsProvider: isChangeAllowed() : name = wifi_on
09-09 13:41:08.276  1259  1623 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.android.server.wifi.WifiStateMachine.insertLog:18843 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8707 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
09-09 13:41:08.286  1259  1624 D WifiStateMachine: setFccChannel: channel = 0
09-09 13:41:08.286  1259  1624 D WifiController: [FCC]setFccChannel() is called !!!
09-09 13:41:08.286  1259  1624 D SecContentProvider: insert(), uri = 2
09-09 13:41:08.286  1259  1624 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,09-09 13:41:08.286  1259  2124 E OsAgent :  Wifi Scan Always Available: 0
09-09 13:41:08.286  1259  2124 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-09 13:41:08.286  1259  2124 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: IS_WIFI_HARDWARE_ON: true
09-09 13:41:08.286  1259  2124 E OsAgent :  Wifi Scan Always Available: 0
09-09 13:41:08.286  1259  2124 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-09 13:41:08.286  1259  2149 E LocSvc_libulp: I/int ulp_msg_process_phone_setting_update(const UlpPhoneContextSettings*), context type: 0x4
09-09 13:41:08.286  1259  2149 E LocSvc_libulp:   gps enabled: 0
09-09 13:41:08.286  1259  2149 E LocSvc_libulp:  network position available 0
09-09 13:41:08.286  1259  2149 E LocSvc_libulp:  wifi setting enabled 1
09-09 13:41:08.286  1259  2149 E LocSvc_libulp:  battery charging 0, agps enabled 0, enh_location_services_enabled 0is_pip_user_setting_enabled 0
09-09 13:41:08.286  1259  2124 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: IS_WIFI_HARDWARE_ON: true
09-09 13:41:08.286  1259  2149 E LocSvc_libulp: I/int ulp_msg_process_system_update(UlpSystemEvent): systemEvent:4 
09-09 13:41:08.286  1259  2124 E OsAgent :  Wifi Scan Always Available: 0
09-09 13:41:08.286  1259  2124 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-09 13:41:08.286  1259  2124 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: IS_WIFI_HARDWARE_ON: true
09-09 13:41:08.286  1259  2129 E LocSvc_LBSApiV02: E/virtual int lbs_core::LBSApiV02::wifiEnabledStatusInject(int):677]: Error : st = 2, ind.status = 1588437952
09-09 13:41:08.286  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bc628fa u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e6698f 6172:com.google.android.apps.photos/u0a97}
09-09 13:41:08.286  1259  1623 D WifiBigDataLog: init : 
09-09 13:41:08.286  1259  2629 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{babebf0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e6698f 6172:com.google.android.apps.photos/u0a97}
,09-09 13:41:08.296  1259  2629 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f37ceab u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1f7ee83 2608:com.samsung.android.providers.context/u0a5}
,09-09 13:41:08.306  1259  2629 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{babebf0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ba36c24 4746:com.sec.android.daemonapp/u0a127}
,09-09 13:41:08.306  4746  4746 D [WeatherWidget(1210)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
,09-09 13:41:08.306  4746  4746 D [WeatherWidget(1210)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78F9CD3967C07B6DE6AAB9923C4C53919020112019F4465EB3AA6FD266958B212E]}
,09-09 13:41:08.306  1259  2304 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{efd4908 u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e6698f 6172:com.google.android.apps.photos/u0a97}
,09-09 13:41:08.316  1259  2310 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{babebf0 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bd6dd8 5344:com.sec.android.app.samsungapps/u0a9}
,09-09 13:41:08.406  6221  6221 I wpa_supplicant: Blacklist: Clear (all) 
09-09 13:41:08.406  6221  6221 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-09 13:41:08.466   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-09 13:41:08.466   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:08.466   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:08.466   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:41:08.466   552  1406 D Netd    : Iface wlan0 link down
09-09 13:41:08.466   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=15 Family=0 Type=0x1 Change=[0x1]UP  Flags=[0x1002]BROADCAST MULTICAST 
09-09 13:41:08.466   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:41:08.466   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:41:08.466   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 15, disable link
09-09 13:41:08.466  6221  6221 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-09 13:41:08.466   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 64
09-09 13:41:08.466   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:08.466   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:08.466   746  1442 I QC-NETMGR-LIB: Processing RTM_DELADDR
09-09 13:41:08.466   746  1442 I QC-NETMGR-LIB: Metainfo:  Family=10 PrefixLen=64 Scope=0xfd Index=15 Flags=[0xc4]OPTIMISTIC TENTATIVE PERMANENT 
09-09 13:41:08.466   746  1442 I QC-NETMGR-LIB: Attribute: PrefixIPv6 addr [fe80:0000:0000:0000:4678:3eff:feeb:95ef]
09-09 13:41:08.466   746  1442 I QC-NETMGR-LIB: Attribute: Address Cache Info - prefered=-1 valid=-1 cstamp=0x308d tstamp=0x308d
09-09 13:41:08.466   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [21]
09-09 13:41:08.466   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 15
,09-09 13:41:08.566  1259  1623 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-09 13:41:08.566  1259  1259 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : -1
,09-09 13:41:08.566  1259  1259 D WifiNotificationController: SHOW_NOTI_MESSAGE : 13, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : 0
09-09 13:41:08.566  1259  1259 D WifiNotificationController: showCaptivePortalDisabledStatus with ssid/visible/title:null/false/0
,09-09 13:41:08.576  1259  1259 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:08.576  1259  1259 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:08.576  1259  1625 D HS20StateMachine: WIFI_STATE_DISABLED
09-09 13:41:08.576  1259  1625 D HS20StateMachine: CMD_HOTSPOT20_DISABLE
09-09 13:41:08.576  1259  1625 D HS20StateMachine: enter : DisablingState
09-09 13:41:08.576  1259  1628 I WifiHs20Service: Message received 5011
09-09 13:41:08.576  1259  1627 D HS20SubscriptionManager: Received CMD_RELEASE_TLS, flag=1
09-09 13:41:08.576  1259  1625 D HS20StateMachine: enter : DisabledState
,09-09 13:41:08.576  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-09 13:41:08.576  1694  1694 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:08.576  1259  1631 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,09-09 13:41:08.576  1694  1694 D HotspotTile: onReceive : 1, 0
09-09 13:41:08.576  1974  1988 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,09-09 13:41:08.576  1974  1988 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,09-09 13:41:08.576  1259  1631 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
09-09 13:41:08.576  1868  2348 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:41:08.586  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:08.586  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2a1edb4 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{345119e 6197:com.samsung.android.securitylogagent/1000}
09-09 13:41:08.586  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:08.586  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:08.586  1259  2629 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.586  1259  2629 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.586  1259  2629 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.586  1259  2629 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.586  1259  2629 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.586  1259  2629 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.586  1259  2629 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.586  1259  2629 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.586  1259  2629 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.586  1259  2629 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.586  1259  2629 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.586  1259  2629 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-09 13:41:08.586  1259  2629 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.586  1259  2629 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:08.586  1259  2629 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-09 13:41:08.596  1259  1637 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2a1edb4 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5827062 5955:com.test.thalitest/u0a136}
,09-09 13:41:08.986  2970  3035 I WCNSS_FILTER: do_write: IBS write: fe
09-09 13:41:08.986  2970  3035 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-09 13:41:09.666   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 476
09-09 13:41:09.666   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
,09-09 13:41:09.666   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:09.666   746  1442 I QC-NETMGR-LIB: Processing RTM_DELLINK
09-09 13:41:09.666   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=15 Family=0 Type=0x1 Change=[0xffffffff]UP BROADCAST DEBUG LOOPBACK POINTOPOINT NOTRAILERS RUNNING NOARP PROMISC ALLMULTI MASTER SLAVE MULTICAST PORTSEL AUTOMEDIA DYNAMIC LOWER_UP DORMANT  Flags=[0x1002]BROADCAST MULTICAST 
09-09 13:41:09.666   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [17]
09-09 13:41:09.666   746  1442 I QC-NETMGR-LIB: Received RTM_DELLINK
09-09 13:41:09.666   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 15, disable link
,09-09 13:41:09.666  1259  1392 E EthernetNetworkFactory: stopTrackingInterface : not matched eth0/usb0 iface is wlan0
,09-09 13:41:09.906   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 476
09-09 13:41:09.906   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:09.906   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:09.906   746  1442 I QC-NETMGR-LIB: Processing RTM_DELLINK
09-09 13:41:09.906   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=16 Family=0 Type=0x1 Change=[0xffffffff]UP BROADCAST DEBUG LOOPBACK POINTOPOINT NOTRAILERS RUNNING NOARP PROMISC ALLMULTI MASTER SLAVE MULTICAST PORTSEL AUTOMEDIA DYNAMIC LOWER_UP DORMANT  Flags=[0x1002]BROADCAST MULTICAST 
09-09 13:41:09.906   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [17]
09-09 13:41:09.906   746  1442 I QC-NETMGR-LIB: Received RTM_DELLINK
09-09 13:41:09.906   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 16, disable link
,09-09 13:41:09.906  1259  1392 E EthernetNetworkFactory: stopTrackingInterface : not matched eth0/usb0 iface is p2p0
,09-09 13:41:10.586  1259  1987 V AlarmManager:  remove PendingIntent] PendingIntent{2973ddd: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:10.666  1259  1623 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
09-09 13:41:10.666  1259  1623 E WifiHW  : ##################### set firmware type 0 #####################
,09-09 13:41:11.836  1259  1392 E EthernetNetworkFactory: maybeTrackInterface : not matched eth0/usb0 iface is wlan0
,09-09 13:41:11.836  1259  1416 D Tethering: enter TetherInterfaceSM  and send tetherstatechangebroadcast
,09-09 13:41:11.846  1259  1416 D Tethering: NAP Supported and not Wifi Model
09-09 13:41:11.846   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1088
09-09 13:41:11.846   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:11.846   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:11.846   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:41:11.846   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=17 Family=0 Type=0x1 Change=[0xffffffff]UP BROADCAST DEBUG LOOPBACK POINTOPOINT NOTRAILERS RUNNING NOARP PROMISC ALLMULTI MASTER SLAVE MULTICAST PORTSEL AUTOMEDIA DYNAMIC LOWER_UP DORMANT  Flags=[0x1002]BROADCAST MULTICAST 
09-09 13:41:11.846   552  1406 D Netd    : Iface wlan0 link down
09-09 13:41:11.846   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:41:11.846   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:41:11.846   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 17, disable link
,09-09 13:41:11.846  1259  1416 E Tethering: No numeric data
,09-09 13:41:11.846   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1088
09-09 13:41:11.846   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:11.846   552  1406 D Netd    : Iface p2p0 link down
09-09 13:41:11.846   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:11.846   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:41:11.846   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=18 Family=0 Type=0x1 Change=[0xffffffff]UP BROADCAST DEBUG LOOPBACK POINTOPOINT NOTRAILERS RUNNING NOARP PROMISC ALLMULTI MASTER SLAVE MULTICAST PORTSEL AUTOMEDIA DYNAMIC LOWER_UP DORMANT  Flags=[0x1002]BROADCAST MULTICAST 
09-09 13:41:11.846   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:41:11.846   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:41:11.846   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 18, disable link
,09-09 13:41:11.856  1259  1392 E EthernetNetworkFactory: maybeTrackInterface : not matched eth0/usb0 iface is p2p0
,09-09 13:41:11.856  1259  1416 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 13:41:11.856  1259  1620 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:41:11.856  1259  1416 D Tethering: InitialState.processMessage what=4
09-09 13:41:11.856  1259  1416 D Tethering: NAP Supported and not Wifi Model
09-09 13:41:11.856  1694  1694 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 13:41:11.856  1694  1694 D HotspotTile: updateTetherState():false, false
09-09 13:41:11.856  1259  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:11.856   552  1413 I WifiHW  : wifi_change_fw_path(): fwpath = sta,
09-09 13:41:11.856   552  1413 D SoftapController: Softap fwReload - Ok
09-09 13:41:11.856  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2713f4c u-1 android.net.conn.TETHER_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a8d25ef 1259:system/1000}
09-09 13:41:11.866  1259  1416 E Tethering: No numeric data
09-09 13:41:11.866  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:11.866   552  1413 D CommandListener: Setting iface cfg
09-09 13:41:11.866  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:11.866   552  1413 D CommandListener: Trying to bring down wlan0
09-09 13:41:11.866  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:11.866  1259  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:11.866  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:11.866   552  1413 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:41:11.866  1259  1620 V NetworkStats: performPollLocked() took 8ms
,09-09 13:41:11.866  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:11.866  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:11.866  1259  1416 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-09 13:41:11.866  1259  1620 D NtpTrustedTime: currentTimeMillis() cache hit,
09-09 13:41:11.866  1259  1620 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:41:11.866  1694  1694 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-09 13:41:11.866  1694  1694 D HotspotTile: updateTetherState():false, false
09-09 13:41:11.866  1259  1623 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-09 13:41:11.866  1259  1623 D wifi    : Can not initialize the vendor function pointer table
09-09 13:41:11.866  1259  1623 E WifiNative-HAL: Could not start hal
09-09 13:41:11.866  1259  1623 E WifiStateMachine: Failed to start HAL
,09-09 13:41:11.876  1259  1623 E WifiHW  : supplicant_name : p2p_supplicant,
09-09 13:41:11.876  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c494b95 u-1 android.net.conn.TETHER_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a8d25ef 1259:system/1000}
,09-09 13:41:11.876  1259  1620 D NetworkStatsRecorder: entry.iface is null
,09-09 13:41:11.876  1259  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:11.876  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:11.876  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:11.876  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:11.876  1259  1620 V NetworkStats: performPollLocked() took 8ms
,09-09 13:41:11.876  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:11.876  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:11.926  6454  6454 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-09 13:41:11.926  6454  6454 I wpa_supplicant: Successfully initialized wpa_supplicant
09-09 13:41:11.926  6454  6454 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x20000), vendorssid_list()
,09-09 13:41:11.926  6454  6454 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-09 13:41:11.956  6454  6454 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-09 13:41:11.956   462   462 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 6454
09-09 13:41:11.956   462   462 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
09-09 13:41:11.956  6454  6454 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-09 13:41:11.956  6454  6454 I wpa_supplicant: ssSupport state is = 1
09-09 13:41:11.956  6454  6454 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-09 13:41:11.956  6454  6454 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-09 13:41:11.956   462   462 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 6454
09-09 13:41:11.956   462   462 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
,09-09 13:41:11.966  6454  6454 I SecureStorage: [INFO]: SPID(0x00000006)ss_id will be loaded by secure_storage_daemon: /system/bin/wpa_supplicant
,09-09 13:41:11.976  1259  1623 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-09 13:41:11.976  1259  1259 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:41:11.976  1259  1259 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:11.976  1259  1628 I WifiHs20Service: Message received 5011
,09-09 13:41:11.976  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-09 13:41:11.976  1259  1631 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
09-09 13:41:11.976  1694  1694 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:11.976  1974  1985 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,09-09 13:41:11.976  1694  1694 D HotspotTile: onReceive : 2, 0
09-09 13:41:11.976  1974  1985 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-09 13:41:11.976  1259  1631 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,09-09 13:41:11.986  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:11.986  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a7ac4aa u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{345119e 6197:com.samsung.android.securitylogagent/1000}
,09-09 13:41:11.986  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:11.986  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:11.996  1259  1989 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a7ac4aa u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5827062 5955:com.test.thalitest/u0a136}
,09-09 13:41:11.996  1259  2304 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:11.996  1259  2304 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:11.996  1259  2304 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:11.996  1259  2304 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:11.996  1259  2304 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:11.996  1259  2304 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:11.996  1259  2304 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:11.996  1259  2304 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:11.996  1259  2304 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:11.996  1259  2304 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:11.996  1259  2304 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:11.996  1259  2304 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-09 13:41:11.996  1259  2304 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:11.996  1259  2304 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:11.996  1259  2304 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-09 13:41:12.166  1259  3546 D SSRM:s  : SIOP:: AP = 350, PST = 381 (W:12), CP = 43, LCD = 0
,09-09 13:41:12.166  1259  3546 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-09 13:41:12.186   462   462 I SecureStorage: [INFO]: SPID(0x00000006)Secure Storage Daemon finished processing with result: 0
09-09 13:41:12.186  6454  6454 I SecureStorage: [INFO]: SPID(0x00000006)Processing data has been completed
,09-09 13:41:12.226  6454  6454 I wpa_supplicant: Loading default cred
09-09 13:41:12.226  6454  6454 I SecureStorage: [INFO]: SPID(0x00000006)Checking if this device supports Secure Storage
,09-09 13:41:12.256  6454  6454 I SecureStorage: [INFO]: SPID(0x00000006)This device supports Secure Storage
,09-09 13:41:12.256   462   462 I SecureStorage: [INFO]: SPID(0x00000006)Credentials: uid 1010, gid 1010, pid 6454
09-09 13:41:12.256   462   462 I SecureStorage: [INFO]: SPID(0x00000006)Received function mask & code: 0x0000010C
09-09 13:41:12.256  6454  6454 I SecureStorage: [INFO]: SPID(0x00000006)SS Daemon is running
09-09 13:41:12.256  6454  6454 I wpa_supplicant: ssSupport state is = 1
09-09 13:41:12.256  6454  6454 W wpa_supplicant: Loading system cred
09-09 13:41:12.256  6454  6454 I SecureStorage: [INFO]: SPID(0x00000006)Checking if this device supports Secure Storage
,09-09 13:41:12.276  6454  6454 I SecureStorage: [INFO]: SPID(0x00000006)This device supports Secure Storage
,09-09 13:41:12.276   462   462 I SecureStorage: [INFO]: SPID(0x00000006)Credentials: uid 1010, gid 1010, pid 6454
09-09 13:41:12.276   462   462 I SecureStorage: [INFO]: SPID(0x00000006)Received function mask & code: 0x0000010C
09-09 13:41:12.276  6454  6454 I SecureStorage: [INFO]: SPID(0x00000006)SS Daemon is running
09-09 13:41:12.276  6454  6454 I wpa_supplicant: ssSupport state is = 1
,09-09 13:41:12.276  6454  6454 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 13:41:12.286  6454  6454 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 13:41:12.286  6454  6454 I wpa_supplicant: [getIMSI]: sim_num 0
,09-09 13:41:12.286  6454  6454 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 13:41:12.286   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-09 13:41:12.286   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:12.286   552  1406 D Netd    : Iface wlan0 link down
09-09 13:41:12.286   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:12.286   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:41:12.286   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=17 Family=0 Type=0x1 Change=[0x1]UP  Flags=[0x1003]UP BROADCAST MULTICAST 
09-09 13:41:12.286   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:41:12.286   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:41:12.286   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 17, disable link
,09-09 13:41:12.446  1259  2294 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-09 13:41:12.446  1259  2294 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4390, temperature: 328, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-09 13:41:12.446  1259  2294 D BatteryService: online:4, current avg:150, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:164
,09-09 13:41:12.456  1259  1259 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 13:41:12.456  1694  1694 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-09 13:41:12.456  1694  1694 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 13:41:12.456  1694  1694 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-09 13:41:12.456  1694  1694 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-09 13:41:12.456  2569  2569 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-09 13:41:12.456  2569  6349 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-09 13:41:12.476  1694  1694 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-09 13:41:12.476  1694  1694 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-09 13:41:12.616   720   720 I MSM-irqbalance: Decided to move IRQ216 from CPU3 to CPU1
,09-09 13:41:12.666  6454  6454 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
09-09 13:41:12.666  6454  6454 I SecureStorage: [INFO]: SPID(0x00000006)Checking if this device supports Secure Storage
,09-09 13:41:12.696  6454  6454 I SecureStorage: [INFO]: SPID(0x00000006)This device supports Secure Storage
,09-09 13:41:12.696   462   462 I SecureStorage: [INFO]: SPID(0x00000006)Credentials: uid 1010, gid 1010, pid 6454
09-09 13:41:12.696   462   462 I SecureStorage: [INFO]: SPID(0x00000006)Received function mask & code: 0x0000010C
09-09 13:41:12.696  6454  6454 I SecureStorage: [INFO]: SPID(0x00000006)SS Daemon is running
09-09 13:41:12.696  6454  6454 I wpa_supplicant: ssSupport state is = 1
09-09 13:41:12.706  6454  6454 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 13:41:12.706   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-09 13:41:12.706   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:12.706   552  1406 D Netd    : Iface p2p0 link down
09-09 13:41:12.706   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:12.706   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:41:12.706   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=18 Family=0 Type=0x1 Change=[0x1]UP  Flags=[0x1043]UP BROADCAST RUNNING MULTICAST 
09-09 13:41:12.706   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:41:12.706   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:41:12.706   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 18, disable link
09-09 13:41:12.706   552  1406 D Netd    : Iface p2p0 link down
09-09 13:41:12.706   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-09 13:41:12.706   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:12.706   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:12.706   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:41:12.706   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=18 Family=0 Type=0x1 Change=[0x0] Flags=[0x1003]UP BROADCAST MULTICAST 
09-09 13:41:12.706   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:41:12.706   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:41:12.706   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 18, disable link
,09-09 13:41:12.846   552  1406 D Netd    : Iface p2p0 link down
09-09 13:41:12.846   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-09 13:41:12.846   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:12.846   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:12.846   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:41:12.846   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=18 Family=0 Type=0x1 Change=[0x0] Flags=[0x1003]UP BROADCAST MULTICAST 
09-09 13:41:12.846   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:41:12.846   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:41:12.846   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 18, disable link
,09-09 13:41:12.876  6454  6454 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE),
,09-09 13:41:12.886  1259  1623 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-09 13:41:12.886  1259  1623 E WifiStateMachine: Deffering msg in Supplicant Starting State131085
,09-09 13:41:12.886  1259  1623 D WifiNative-wlan0: callSECApiBoolean - ID [301]
09-09 13:41:12.886  6454  6454 I wpa_supplicant: HOTSPOT20_ENABLE called ON
09-09 13:41:12.886  6454  6454 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 13:41:12.906  1259  1630 D ConnectivityService: handlePromptUnvalidated 503
,09-09 13:41:12.906  6454  6454 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-09 13:41:12.916  6454  6454 I wpa_supplicant: wlan0: Skip scan - bUseNetwork false
09-09 13:41:12.916  1259  1623 D WifiNative-wlan0: callSECApiInt - ID [210]
,09-09 13:41:12.916  1259  1259 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:41:12.916  1259  1259 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:12.916  1259  1625 D HS20StateMachine: WIFI_STATE_ENABLED
09-09 13:41:12.916  1259  1625 D HS20StateMachine: reloadCredentialsToSupplicant
09-09 13:41:12.916  1259  1625 D HotspotDBHandler: getCredentialIds
09-09 13:41:12.916  1259  1628 I WifiHs20Service: Message received 5011
,09-09 13:41:12.916  1259  1623 D WifiConfigStore: Loading config and enabling all networks 
,09-09 13:41:12.926  1259  1631 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,09-09 13:41:12.926  1694  1694 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:12.926  1694  1694 D HotspotTile: onReceive : 3, 0
,09-09 13:41:12.926  1974  1988 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
09-09 13:41:12.926  1974  1988 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-09 13:41:12.926  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-09 13:41:12.926  1259  1631 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,09-09 13:41:12.926  1694  2108 D QSTile.WifiTile: handleUpdateState  cb.changed 5 wifiEnabled : ON 
,09-09 13:41:12.926  1694  1694 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 148
09-09 13:41:12.936  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3adb89b u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{345119e 6197:com.samsung.android.securitylogagent/1000}
09-09 13:41:12.936  5955  5955 D BluetoothAdapter: STATE_ON
09-09 13:41:12.936  1259  1623 I WifiConfigStore: "NG700" is a verified password AP: true
,09-09 13:41:12.936  1259  1623 E WifiConfigStore: Not a HS20
,09-09 13:41:12.936  6229  6240 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
09-09 13:41:12.936  6229  6240 D HotspotProvider: CREDENTIAL
09-09 13:41:12.936  6229  6240 D HotspotProvider: No prepend tags
09-09 13:41:12.936  1259  1623 D WifiConfigStore: loaded 0 passpoint configs
09-09 13:41:12.936  1259  1623 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-09 13:41:12.946  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:12.946  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:12.946  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:12.946  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:12.946  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:12.946  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:12.946  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:12.946  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:12.946  1259  1623 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-09 13:41:12.946  1259  1623 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
,09-09 13:41:12.946  1259  1623 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-09 13:41:12.946  1259  1259 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
09-09 13:41:12.946  1259  1259 D WifiHs20Service: reason: 2
09-09 13:41:12.946  1259  1628 I WifiHs20Service: Message received 5014
09-09 13:41:12.946  1259  1628 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
09-09 13:41:12.946  1259  1628 E WifiHs20Service: The changed config is NULL
09-09 13:41:12.946  5955  5955 D BluetoothAdapter: STATE_ON
09-09 13:41:12.946  1259  1623 D WifiConfigStore: setNetworkPriorityDefault: networkId = 0, priority = 1
09-09 13:41:12.946  1259  1623 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-09 13:41:12.946  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:12.956  1259  1623 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-09 13:41:12.956  1259  1637 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3adb89b u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5827062 5955:com.test.thalitest/u0a136}
09-09 13:41:12.956  6454  6454 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-09 13:41:12.956  6454  6454 I wpa_supplicant: resume autoscan
09-09 13:41:12.956  6454  6454 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
09-09 13:41:12.956  6454  6454 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
09-09 13:41:12.956  6454  6454 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-09 13:41:12.956  6454  6454 I wpa_supplicant: reset timer : RESET_TIMER 0
09-09 13:41:12.956  6454  6454 I wpa_supplicant: P2P: Current p2p state = IDLE
09-09 13:41:12.956  6454  6454 I wpa_supplicant: First Scan Start
09-09 13:41:12.956  6454  6454 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-09 13:41:12.956  1259  1625 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
09-09 13:41:12.956  1259  1625 D HS20StateMachine: enter : DiscoveringState
,09-09 13:41:12.956  5955  5955 D BluetoothAdapter: STATE_ON
09-09 13:41:12.956  1259  1623 D WifiNative-wlan0: Setting external_sim to 1
,09-09 13:41:12.956  1259  1623 D WifiStateMachine: [setCountryCode()] Airplane mode return !!!
09-09 13:41:12.956  1259  1623 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 13:41:12.956  6454  6454 I wpa_supplicant: bt_status is set be DISCONNECTED
,09-09 13:41:12.956  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:12.956  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:12.956  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:12.956  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:12.956  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:12.956  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:12.956  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:12.956  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:12.966  5955  5955 D BluetoothAdapter: STATE_ON
09-09 13:41:12.966  1259  1623 E WifiNative-wlan0: do suspend true
,09-09 13:41:12.966  1259  1623 D WifiNative-HAL: Failing getSupportedFeatureset because HAL isn't started
09-09 13:41:12.966  1259  1622 D WifiP2pService: P2pDisabledState{ what=131203 }
09-09 13:41:12.966  1259  1623 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-09 13:41:12.966  1259  1623 D WifiStateMachine: [FCC]Airplane on, setFccChannel(0)!!!
09-09 13:41:12.966  1259  1623 D WifiStateMachine: setFccChannelNative: channel = 0
09-09 13:41:12.966  1259  1623 D WifiNative-wlan0: callSECApiInt - ID [230]
09-09 13:41:12.966  1259  1259 D RttService: SCAN_AVAILABLE : 3
09-09 13:41:12.966  1259  1649 E WifiScanningService: could not start HAL
09-09 13:41:12.966  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:12.966  1259  1650 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:12.966   552  1413 D CommandListener: Setting iface cfg
09-09 13:41:12.966   552  1413 D CommandListener: Trying to bring up p2p0
,09-09 13:41:12.966  1259  1622 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 13:41:12.966  1259  1622 D SecContentProvider: insert(), uri = 2
,09-09 13:41:12.966  1259  1622 D WifiP2pService: P2pEnablingState
09-09 13:41:12.966  1259  1622 D WifiP2pService: P2pEnablingState{ what=147457 }
09-09 13:41:12.966  1259  1622 D WifiP2pService: P2p socket connection successful
09-09 13:41:12.966  1259  1622 D WifiP2pService: P2pEnabledState
09-09 13:41:12.966  5955  5955 D BluetoothAdapter: STATE_ON
09-09 13:41:12.966  1259  1622 D SecContentProvider: insert(), uri = 2
,09-09 13:41:12.966  1259  1259 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-09 13:41:12.966  1259  1417 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
09-09 13:41:12.966  1259  1417 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-09 13:41:12.966  1259  1417 D WifiDisplayController: disconnect
09-09 13:41:12.966  1259  1417 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 13:41:12.966  1259  1622 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-09 13:41:12.976  1694  1694 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-09 13:41:12.976  1259  1630 E ConnectivityService: updateNetworkInfo()
09-09 13:41:12.976  1259  1630 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,09-09 13:41:12.976  1694  1694 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-09 13:41:12.976  1694  1694 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-09 13:41:12.976  1259  1987 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 13:41:12.976  1694  1694 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-09 13:41:12.976  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:12.976  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:12.976  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:12.976  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:12.976  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:12.976  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:12.976  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:12.976  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:12.976  1259  1623 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
09-09 13:41:12.976  5955  5955 D BluetoothAdapter: STATE_ON
,09-09 13:41:12.976  1259  1623 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
09-09 13:41:12.976  6454  6454 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 512
,09-09 13:41:12.976  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:12.976  1259  1417 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:12.976  6454  6454 I wpa_supplicant: P2P: Set Samsung Discovery name = 
09-09 13:41:12.976  1259  1417 I WifiDisplayAdapter: onP2pDisconnected
09-09 13:41:12.976  1259  1417 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 13:41:12.976  1259  1417 D IpRemoteDisplayController: WfdBridgeServer is already null
09-09 13:41:12.976  1694  1694 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-09 13:41:12.976  1259  1324 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:12.976  1259  1324 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:12.976  1259  1324 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:12.976  1259  1324 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:12.976  1259  1324 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:12.976  1259  2124 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-09 13:41:12.976  1259  1324 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:12.976  1259  2124 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 3, Mac address valid: false, AP MAC address: [00:00:00:00:00:00], Wifi-Ap SSID Valid: false, SSID: 
09-09 13:41:12.976  1259  1324 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:12.976  1259  1324 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:12.976  1259  1324 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:12.976  1259  1324 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-09 13:41:12.976  1259  1324 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:12.976  1259  1324 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:12.976  1259  1324 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:12.976  1259  1324 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-09 13:41:12.976  1259  1324 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-09 13:41:12.986  1259  2124 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-09 13:41:12.986  1259  2124 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 3, Mac address valid: false, AP MAC address: [00:00:00:00:00:00], Wifi-Ap SSID Valid: false, SSID: 
,09-09 13:41:12.986  1259  2320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2190438 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fea34f9 6088:com.samsung.android.app.FileShareClient/5005}
,09-09 13:41:12.986  1974  2707 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
09-09 13:41:12.986  6088  6088 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:41:12.986  6088  6088 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-09 13:41:12.986  6088  6088 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 13:41:12.986  1259  2629 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2190438 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dcd9326 5659:com.samsung.android.app.FileShareServer/5005}
,09-09 13:41:12.996  5659  5659 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:41:12.996  5659  5659 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,09-09 13:41:12.996  5659  5659 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,09-09 13:41:13.006  1259  1622 E WifiP2pService: Failed to set my phone number info into probe response
,09-09 13:41:13.006  1259  1622 D WifiNative-p2p0: p2pGetDeviceAddress
,09-09 13:41:13.006  1259  1622 D WifiNative-p2p0: p2pGetDeviceAddress returning 46:78:3e:eb:95:ef
,09-09 13:41:13.006  1259  1622 D WifiP2pService: DeviceAddress: 46:95:ef
09-09 13:41:13.006  1259  1417 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Tablet] Galaxy Tab S2
09-09 13:41:13.006  1259  1417 D WifiDisplayController:  deviceAddress: 46:78:3e:eb:95:ef
09-09 13:41:13.006  1259  1417 D WifiDisplayController:  primary type: 1-0050F204-9
09-09 13:41:13.006  1259  1417 D WifiDisplayController:  secondary type: null
09-09 13:41:13.006  1259  1417 D WifiDisplayController:  wps: 0
09-09 13:41:13.006  1259  1417 D WifiDisplayController:  grpcapab: 0
09-09 13:41:13.006  1259  1417 D WifiDisplayController:  devcapab: 0
09-09 13:41:13.006  1259  1417 D WifiDisplayController:  status: 3
09-09 13:41:13.006  1259  1417 D WifiDisplayController:  wfdInfo: null
09-09 13:41:13.006  1259  1417 D WifiDisplayController:  groupownerAddress: null
09-09 13:41:13.006  1259  1417 D WifiDisplayController:  GOdeviceName: null
09-09 13:41:13.006  1259  1417 D WifiDisplayController:  interfaceAddress: 
09-09 13:41:13.006  1259  1417 D WifiDisplayController:  SConnectInfo : null
09-09 13:41:13.006  1259  1417 D WifiDisplayController:  contactInfoHash : null
09-09 13:41:13.006  1259  1417 D WifiDisplayController:  ssDevInfo : 0
09-09 13:41:13.006  1259  1417 D WifiDisplayController:  iconIdx : 0
,09-09 13:41:13.016  1259  1622 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-09 13:41:13.016  1259  1622 D WifiP2pService: InactiveState
09-09 13:41:13.016  1259  1622 D WifiP2pService: InactiveState{ what=143376 }
,09-09 13:41:13.016  1259  1622 D WifiP2pService: P2pEnabledState{ what=143376 }
09-09 13:41:13.016  1259  1622 E WifiP2pService: Airplane mode : skipped SET_COUNTRY_CODE
,09-09 13:41:13.296  5955  6437 E io.jxcore.node.ConnectivityMonitorTest: Wifi is not enabled after 5s!
,09-09 13:41:13.296  5955  6005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:13.296  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:13.296  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:13.296  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:13.296  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:13.296  5955  6005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2689004 removed from the list
09-09 13:41:13.296  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:13.296  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97eb9ed removed from the list
09-09 13:41:13.296  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:13.296  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:13.306  5955  6461 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-09 13:41:13.306  5955  6461 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 13:41:13.816   552  1409 D EnterpriseController: netId is 0
09-09 13:41:13.816   552  1409 D Netd    : getNetworkForDns: using netid 0 for uid 10136
,09-09 13:41:13.826  5955  6463 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-09 13:41:13.826  5955  6461 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-09 13:41:13.826  5955  6461 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:41:13.826  5955  6463 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-09 13:41:13.826  5955  6461 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:13.826  5955  6463 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:41:13.826  5955  6461 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:13.826  5955  6463 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:13.826  5955  6466 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 274, name: IncomingSocketThread/Sender)
,09-09 13:41:13.826  5955  6467 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 275, name: OutgoingSocketThread/Sender)
09-09 13:41:13.826  5955  6463 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-09 13:41:13.826  5955  6461 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-09 13:41:13.826  5955  6468 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 277, name: IncomingSocketThread/Receiver)
,09-09 13:41:13.826  5955  6469 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 276, name: OutgoingSocketThread/Receiver)
09-09 13:41:13.826  5955  6468 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 277, thread name: IncomingSocketThread/Receiver)
09-09 13:41:13.826  5955  6468 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 13:41:13.826  5955  6468 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 277, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-09 13:41:13.826  5955  6469 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 276, thread name: OutgoingSocketThread/Receiver)
09-09 13:41:13.826  5955  6469 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-09 13:41:13.826  5955  6469 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 276, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-09 13:41:14.026  6454  6454 I wpa_supplicant: nl80211: Received scan results (26 BSSes)
,09-09 13:41:14.036  6454  6454 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
09-09 13:41:14.036  6454  6454 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
09-09 13:41:14.036  6454  6454 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-09 13:41:14.036  6454  6454 I wpa_supplicant:    allow  - level is under -85dBm [-46] or selected nid [-1] [0]
,09-09 13:41:14.036  6454  6454 I wpa_supplicant:  selected from pick network BSS F4.99.3E ssid='NG700' et= 090,gp=03,cu=987654321,sc=987654321
09-09 13:41:14.036  6454  6454 I wpa_supplicant:    allow  - level is under -85dBm [-46] or selected nid [-1] [0]
,09-09 13:41:14.036  6454  6454 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700',
09-09 13:41:14.036  1259  6459 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-09 13:41:14.066  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f400c11 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8b6b662 1694:com.android.systemui/u0a46},
09-09 13:41:14.066  1259  1623 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-09 13:41:14.076  1259  2124 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-09 13:41:14.076  1259  2124 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 5, Mac address valid: false, AP MAC address: [00:00:00:00:00:00], Wifi-Ap SSID Valid: false, SSID: 
,09-09 13:41:14.116   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 320,
,09-09 13:41:14.116   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:14.116   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
,09-09 13:41:14.116   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:41:14.116   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=17 Family=0 Type=0x1 Change=[0x0] Flags=[0x1003]UP BROADCAST MULTICAST 
09-09 13:41:14.116   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
,09-09 13:41:14.116   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:41:14.116   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 17, disable link
09-09 13:41:14.116   552  1406 D Netd    : Iface wlan0 link down,
09-09 13:41:14.116   552  1406 D Netd    : Iface wlan0 link down
09-09 13:41:14.116   552  1406 D Netd    : Iface wlan0 link down
09-09 13:41:14.116   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 188
,09-09 13:41:14.116   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:14.116   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 72
,09-09 13:41:14.116   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:14.116   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:14.116   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:41:14.116   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=17 Family=0 Type=0x1 Change=[0x0] Flags=[0x1003]UP BROADCAST MULTICAST 
09-09 13:41:14.116   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:41:14.116   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:41:14.116   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 17, disable link
09-09 13:41:14.116   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:14.116   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:41:14.116   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=17 Family=0 Type=0x1 Change=[0x0] Flags=[0x1003]UP BROADCAST MULTICAST 
09-09 13:41:14.116   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:41:14.116   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
,09-09 13:41:14.116   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 17, disable link
09-09 13:41:14.116   552  1406 D Netd    : Iface wlan0 link up
09-09 13:41:14.116   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-09 13:41:14.116   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:14.116   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
,09-09 13:41:14.116   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:41:14.116   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=17 Family=0 Type=0x1 Change=[0x0] Flags=[0x11003]UP BROADCAST MULTICAST LOWER_UP 
09-09 13:41:14.116   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:41:14.116   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-09 13:41:14.126  1259  1620 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:41:14.116   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 17, disable link
,09-09 13:41:14.116  6454  6454 E wpa_supplicant: Cmd 35605 not handled
09-09 13:41:14.116  1259  1416 D Tethering: enter TetherInterfaceSM  and send tetherstatechangebroadcast
09-09 13:41:14.116  1259  1416 D Tethering: NAP Supported and not Wifi Model
09-09 13:41:14.116  6454  6454 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-09 13:41:14.116  1259  1416 E Tethering: No numeric data
09-09 13:41:14.116  1259  1416 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 13:41:14.126  1259  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:14.126  1694  1694 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 13:41:14.126  1694  1694 D HotspotTile: updateTetherState():false, false
,09-09 13:41:14.126  1259  1623 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
09-09 13:41:14.126  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:14.126  1259  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:14.126  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:14.126  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:14.126  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:14.126  1259  1620 V NetworkStats: performPollLocked() took 4ms
09-09 13:41:14.126  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95c2250 u-1 android.net.conn.TETHER_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a8d25ef 1259:system/1000}
,09-09 13:41:14.126  1259  2124 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-09 13:41:14.126  1259  2124 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 6, Mac address valid: false, AP MAC address: [00:00:00:00:00:00], Wifi-Ap SSID Valid: false, SSID: 
,09-09 13:41:14.136  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:14.136  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:14.316  5955  6005 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}],
09-09 13:41:14.316  5955  6005 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-09 13:41:14.316  5955  6005 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@bc4fe5e Bundle[{}]
,09-09 13:41:14.316  5955  6005 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 13:41:14.316  5955  6005 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-09 13:41:14.316  5955  6005 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-09 13:41:14.316  5955  6005 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 13:41:14.316  5955  6005 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-09 13:41:14.316  5955  6005 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 13:41:14.326  5955  6470 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775,
09-09 13:41:14.326  5955  6470 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 13:41:14.836  5955  6472 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-09 13:41:14.836  5955  6472 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:41:14.836  5955  6470 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-09 13:41:14.836  5955  6470 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:41:14.836  5955  6472 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:14.836  5955  6470 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:14.836  5955  6472 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:14.836  5955  6470 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:41:14.836  5955  6470 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-09 13:41:14.836  5955  6472 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321),
,09-09 13:41:14.836  5955  6474 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 288, name: IncomingSocketThread/Sender)
,09-09 13:41:14.836  5955  6475 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 289, name: OutgoingSocketThread/Sender)
,09-09 13:41:14.836  5955  6477 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 290, name: IncomingSocketThread/Receiver),
,09-09 13:41:14.836  5955  6476 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 291, name: OutgoingSocketThread/Receiver)
09-09 13:41:14.836  5955  6477 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 290, thread name: IncomingSocketThread/Receiver)
,09-09 13:41:14.836  5955  6477 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 13:41:14.836  5955  6477 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 290, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192,
09-09 13:41:14.836  5955  6476 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 291, thread name: OutgoingSocketThread/Receiver)
09-09 13:41:14.836  5955  6476 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done,
09-09 13:41:14.836  5955  6476 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 291, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-09 13:41:15.116  6454  6454 I wpa_supplicant: wlan0: WPA: RX message 1 of 4-Way Handshake from F4.99.3E (ver=2),
,09-09 13:41:15.116  6454  6454 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 2/4
,09-09 13:41:15.126  1259  1623 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-09 13:41:15.126  1259  2124 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
,09-09 13:41:15.126  1259  2124 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 7, Mac address valid: false, AP MAC address: [00:00:00:00:00:00], Wifi-Ap SSID Valid: false, SSID: 
,09-09 13:41:15.146  6454  6454 I wpa_supplicant: wlan0: WPA: RX message 3 of 4-Way Handshake from F4.99.3E (ver=2),
09-09 13:41:15.156  6454  6454 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 4/4
,09-09 13:41:15.156  6454  6454 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 13:41:15.156  6454  6454 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-09 13:41:15.156   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084,
,09-09 13:41:15.156   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:15.156   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
,09-09 13:41:15.156   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-09 13:41:15.156   746  1442 I QC-NETMGR-LIB: Metainfo:  Index=17 Family=0 Type=0x1 Change=[0x0] Flags=[0x11043]UP BROADCAST RUNNING MULTICAST LOWER_UP 
,09-09 13:41:15.156   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-09 13:41:15.156   746  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
,09-09 13:41:15.156   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 17, disable link
09-09 13:41:15.156   552  1406 D Netd    : Iface wlan0 link up
09-09 13:41:15.156  6454  6454 I wpa_supplicant: Blacklist: Clear (temp) 
,09-09 13:41:15.166  1259  1623 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-09 13:41:15.176  1259  1623 V AlarmManager:  remove PendingIntent] PendingIntent{3c13edd: PendingIntentRecord{65d4a52 android broadcastIntent}}
,09-09 13:41:15.176  1259  1259 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
09-09 13:41:15.176  1259  1259 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-09 13:41:15.176  1259  1259 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
09-09 13:41:15.176  1259  1628 I WifiHs20Service: Message received 5007
09-09 13:41:15.176  1259  1623 D WifiNetworkAgent: NetworkAgent: Registering NetworkAgent
,09-09 13:41:15.186  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) },
09-09 13:41:15.186  1259  1623 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-09 13:41:15.186  1259  1630 E ConnectivityService: updateNetworkInfo()
09-09 13:41:15.186  1259  1630 D ConnectivityService: Got NetworkAgent Messenger
09-09 13:41:15.186  1974  1974 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
09-09 13:41:15.186  1259  1630 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-09 13:41:15.186  1259  1630 D ConnectivityService: NetworkAgent connected,
,09-09 13:41:15.186   552  1413 D CommandListener: Setting iface cfg
,09-09 13:41:15.186  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8823426 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{54b8953 6035:com.sec.android.diagmonagent/1000},
09-09 13:41:15.186  6035  6035 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:15.186  6035  6035 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
09-09 13:41:15.186  6035  6035 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,09-09 13:41:15.186  6035  6035 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-09 13:41:15.196  1259  2008 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8823426 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a6a9da7 6058:com.sec.app.RilErrorNotifier/1000}
,09-09 13:41:15.196  6058  6058 I PhoneErrorReceiver: onReceive
09-09 13:41:15.196  6058  6058 I MIPErrReceiver: isWiFiConnected
,09-09 13:41:15.196  1259  1989 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-09 13:41:15.196  1259  1623 D WifiStateMachine: Start Dhcp Watchdog 3,
,09-09 13:41:15.206  1259  1623 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
09-09 13:41:15.206  1259  2008 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8823426 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8c16b67 5671:com.enhance.gameservice/u0a79}
,09-09 13:41:15.206  1259  2124 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
,09-09 13:41:15.206  1259  2124 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 8, Mac address valid: false, AP MAC address: [00:00:00:00:00:00], Wifi-Ap SSID Valid: false, SSID: 
,09-09 13:41:15.216  1259  2008 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8823426 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f996d43 6074:com.sec.knox.switcher/1000}
,09-09 13:41:15.216  6074  6074 I usagelog: received in receiver
,09-09 13:41:15.216  6074  6074 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
09-09 13:41:15.216  6074  6074 I KnoxUsageLogPro: premStatus:2
,09-09 13:41:15.216  6074  6074 I KnoxUsageLogPro: isEulaShown : false
09-09 13:41:15.216  6074  6074 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,09-09 13:41:15.216  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-09 13:41:15.226  1259  1623 D WifiNetworkAgent: NetworkAgent: NetworkAgent fully connected,
09-09 13:41:15.226  1259  1630 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]
,09-09 13:41:15.226  1259  1630 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,09-09 13:41:15.226  1259  1630 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,09-09 13:41:15.226  1259  1623 E WifiNative-wlan0: do suspend false
,09-09 13:41:15.226  1259  1623 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-09 13:41:15.226  1259  1622 D WifiP2pService: InactiveState{ what=143375 }
09-09 13:41:15.226  1259  1622 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 13:41:15.236  1259  2124 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-09 13:41:15.236  1259  2124 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 9, Mac address valid: true, AP MAC address: [f4:f2:6d:22:99:3e], Wifi-Ap SSID Valid: true, SSID: NG700
,09-09 13:41:15.236  1259  2136 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 131 QMI_LOC_NOTIFY_WIFI_ATTACHMENT_STATUS_REQ_V02
,09-09 13:41:15.246  6480  6480 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-09 13:41:15.256  6480  6480 I dhcpcd  : version 5.5.6 starting
,09-09 13:41:15.256  6480  6480 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-09 13:41:15.336  5955  6005 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 300)
,09-09 13:41:15.336  5955  6005 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-09 13:41:15.336  5955  6005 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 301)
,09-09 13:41:15.336  5955  6005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:15.336  5955  6005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a8eab3 added. We now have 3 listener(s)
09-09 13:41:15.346  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-09 13:41:15.346  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:15.346  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:15.346  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:15.346  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0a870 added. We now have 3 listener(s)
09-09 13:41:15.346  5955  6005 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:15.346  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:41:15.346  5344  5344 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
09-09 13:41:15.346  5344  5344 D PreloadUpdateManagerStateMachine: exit::IDLE
09-09 13:41:15.346  5344  5344 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,09-09 13:41:15.346  5344  5344 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
09-09 13:41:15.346  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:15.346  5344  5344 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,09-09 13:41:15.346  5344  5344 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
09-09 13:41:15.346  5344  5344 D PreloadUpdateManagerStateMachine: entry::IDLE
,09-09 13:41:15.346  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:15.356  5955  6005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:15.356  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:15.356  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:15.356  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:15.356  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:15.356  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:15.356  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:15.356  5955  6005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:15.356  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:15.356  5955  6005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:15.356  5955  6005 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:15.356  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:15.356  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:15.366  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:15.366  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:15.366  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:15.366  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:15.366  5955  6005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a8eab3 removed from the list
09-09 13:41:15.366  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:15.366  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0a870 removed from the list
,09-09 13:41:15.366  6480  6480 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-09 13:41:15.366  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:15.366  6480  6480 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-09 13:41:15.366  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:15.366  6480  6480 I dhcpcd  : bssid match
09-09 13:41:15.366  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:15.366  6480  6480 I dhcpcd  : wlan0: rebinding lease of 192.168.1.106
09-09 13:41:15.366  5955  6005 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-09 13:41:15.366  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
09-09 13:41:15.366  5955  6005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:41:15.366  5955  6005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:41:15.366  5955  6005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:41:15.366  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:15.366  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 13:41:15.366  5955  6005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-09 13:41:15.366  5955  6005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:41:15.366  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:41:15.366  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:41:15.366  5955  5955 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:41:15.366  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:15.366  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:41:15.366  5955  6487 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:41:15.366  5955  6487 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:41:15.366  5955  6005 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 13:41:15.366  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:41:15.376  5955  6487 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-09 13:41:15.376  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:15.376  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:15.376  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:15.376  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:41:15.376  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:15.376  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:41:15.376  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 13:41:15.376  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:41:15.376  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:15.376  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-09 13:41:15.376  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-09 13:41:15.376  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 44 78 3E EB 95 EE
09-09 13:41:15.376  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:41:15.376  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:41:15.376  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 13:41:15.386  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:15.386  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:15.386  5955  6005 D BluetoothLeAdvertiser: start advertising
,09-09 13:41:15.386  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:15.386  2569  6412 D BtGatt.GattService: registerClient() - UUID=4c2cc959-a195-4023-b5ad-02e4adb94af5
,09-09 13:41:15.426  2569  2739 D BtGatt.GattService: onClientRegistered() - UUID=4c2cc959-a195-4023-b5ad-02e4adb94af5, clientIf=6
,09-09 13:41:15.426  5955  6348 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-09 13:41:15.426  2569  3085 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-09 13:41:15.436  2569  3085 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-09 13:41:15.436  2569  3085 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-09 13:41:15.436  2569  2761 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-09 13:41:15.436  2569  2761 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
,09-09 13:41:15.436  2569  2746 D BtGatt.AdvertiseManager: message : 0,
09-09 13:41:15.436  2569  2746 D BtGatt.AdvertiseManager: number of adv instance running = 0
09-09 13:41:15.436  2569  2746 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:41:15.436  2569  2746 D BtGatt.AdvertiseManager: starting advertising
,09-09 13:41:15.436  2569  2746 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-09 13:41:15.446  2970  2971 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
,09-09 13:41:15.446  2569  2761 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 14,
09-09 13:41:15.446  2970  2971 I WCNSS_FILTER: do_write: IBS write: fd,
,09-09 13:41:15.456  6480  6480 I dhcpcd  : wlan0: acknowledged 192.168.1.106 from 192.168.1.1,
09-09 13:41:15.456  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 28 : bytes_written: 28
09-09 13:41:15.456  2970  2970 I WCNSS_FILTER: do_write: IBS write: fc
,09-09 13:41:15.456  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-09 13:41:15.456  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
,09-09 13:41:15.456  1259  1324 V AlarmManager:  remove PendingIntent] PendingIntent{4166662: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:15.456  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-09 13:41:15.456  2569  2739 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
09-09 13:41:15.456  2569  2746 D BtGatt.AdvertiseManager: starting multi advertising
09-09 13:41:15.456  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 38 : bytes_written: 38
09-09 13:41:15.456  2569  2761 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24557021
09-09 13:41:15.456  2569  2761 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-09 13:41:15.456  2569  2761 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-09 13:41:15.456  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8,
09-09 13:41:15.456  2569  2761 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-09 13:41:15.456  2569  2739 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
09-09 13:41:15.456  2569  2746 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-09 13:41:15.456  2569  2746 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-09 13:41:15.456  1259  1987 V AlarmManager:  remove PendingIntent] PendingIntent{287a3f3: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:15.456  2569  2746 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
,09-09 13:41:15.456  2569  2746 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
09-09 13:41:15.456  5955  5965 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
09-09 13:41:15.456  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-09 13:41:15.456  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 13:41:15.466  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-09 13:41:15.466  1259  2621 V AlarmManager:  remove PendingIntent] PendingIntent{8a708b0: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:15.466  5955  5955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:41:15.466  5955  5955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-09 13:41:15.466  5955  5955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-09 13:41:15.466  5955  5955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 13:41:15.466  5955  5955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-09 13:41:15.466  5955  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-09 13:41:15.466  1259  2629 V AlarmManager:  remove PendingIntent] PendingIntent{be48329: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:15.466  5955  5955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-09 13:41:15.466  5955  5955 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:15.466  1259  1721 V AlarmManager:  remove PendingIntent] PendingIntent{af886ae: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:15.546  6480  6480 I dhcpcd  : wlan0: leased 192.168.1.106 for 172800 seconds
09-09 13:41:15.546   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 80
09-09 13:41:15.546   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
,09-09 13:41:15.546   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:15.546   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWADDR
09-09 13:41:15.546   746  1442 I QC-NETMGR-LIB: Metainfo:  Family=2 PrefixLen=24 Scope=0x0 Index=17 Flags=[0x80]PERMANENT 
09-09 13:41:15.546   746  1442 I QC-NETMGR-LIB: Attribute: PrefixIPv4 addr [192.168.1.106]
09-09 13:41:15.546   746  1442 I QC-NETMGR-LIB: Attribute: LocalIPv4 addr [192.168.1.106]
09-09 13:41:15.546   746  1442 I QC-NETMGR-LIB: Attribute: BroadcastIPv4 addr [192.168.1.255]
,09-09 13:41:15.546   746  1442 I QC-NETMGR-LIB: Attribute: Label name wlan0
09-09 13:41:15.546   746  1442 I QC-NETMGR-LIB: Attribute: Address Cache Info - prefered=-1 valid=-1 cstamp=0x3384 tstamp=0x3384
09-09 13:41:15.546   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [20]
09-09 13:41:15.546   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 17
,09-09 13:41:15.546  1259  1630 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,09-09 13:41:15.966  5955  5955 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-09 13:41:15.966  5955  5955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 13:41:15.966  5955  5955 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:41:16.036  1259  1623 E WifiNative-wlan0: do suspend true
,09-09 13:41:16.036  1259  1630 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,09-09 13:41:16.036  1259  1622 D WifiP2pService: InactiveState{ what=143375 }
09-09 13:41:16.036  1259  1622 D WifiP2pService: P2pEnabledState{ what=143375 }
09-09 13:41:16.036  1259  1623 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,09-09 13:41:16.036  1259  1623 D WifiStateMachine: VerifyingLinkState enter
09-09 13:41:16.036  1259  1630 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]
,09-09 13:41:16.036  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-09 13:41:16.046  1259  1259 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
,09-09 13:41:16.046  1259  1630 E ConnectivityService: updateNetworkInfo()
,09-09 13:41:16.046  1259  1630 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}, oldLp = null
09-09 13:41:16.046  1259  1630 D ConnectivityService: Adding iface wlan0 to network 504
,09-09 13:41:16.056  1259  1259 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
09-09 13:41:16.056  1259  1259 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-09 13:41:16.056  1259  1259 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
09-09 13:41:16.056  1259  1628 I WifiHs20Service: Message received 5007
09-09 13:41:16.056  1259  1642 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
09-09 13:41:16.056  1259  1642 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}
09-09 13:41:16.056  1259  1642 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}
09-09 13:41:16.056  1259  1642 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}
09-09 13:41:16.056  1259  1642 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}
,09-09 13:41:16.066  1974  1974 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,09-09 13:41:16.066  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-09 13:41:16.066  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d6e8c4f u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{54b8953 6035:com.sec.android.diagmonagent/1000}
09-09 13:41:16.066  1259  1642 I WifiManager: isCaptivePortalException
,09-09 13:41:16.066  1259  1642 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:41:16.066  1259  1642 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:41:16.066  1259  1642 D WifiWatchdogStateMachine: 3Captive portal check should be processed whether SNS option is on or off.
09-09 13:41:16.066  1259  1642 D WifiWatchdogStateMachine.CaptivePortalHandler: [checkCaptivePortal] - callbackHandler=Handler (com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalHandler) {68fc0d3}
09-09 13:41:16.066  1259  1642 I WifiManager: isCaptivePortalException
09-09 13:41:16.066  1259  1642 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:41:16.066  1259  1642 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
,09-09 13:41:16.066  6035  6035 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:16.066  6035  6035 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
09-09 13:41:16.066  6035  6035 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,09-09 13:41:16.066  6035  6035 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-09 13:41:16.076  1259  2310 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d6e8c4f u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a6a9da7 6058:com.sec.app.RilErrorNotifier/1000}
,09-09 13:41:16.076  6058  6058 I PhoneErrorReceiver: onReceive
09-09 13:41:16.076  6058  6058 I MIPErrReceiver: isWiFiConnected
09-09 13:41:16.076  1259  1623 D WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to CONNECTED
09-09 13:41:16.076  1259  1325 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-09 13:41:16.086  1259  2008 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d6e8c4f u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8c16b67 5671:com.enhance.gameservice/u0a79}
,09-09 13:41:16.086  1259  1630 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,09-09 13:41:16.086  1259  1630 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,09-09 13:41:16.086  1259  1259 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
,09-09 13:41:16.086  1259  1630 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,09-09 13:41:16.086  1259  1630 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 13:41:16.086  1259  1630 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
,09-09 13:41:16.086  1259  2008 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d6e8c4f u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f996d43 6074:com.sec.knox.switcher/1000}
,09-09 13:41:16.086  6074  6074 I usagelog: received in receiver
09-09 13:41:16.086  6074  6074 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
09-09 13:41:16.086  6074  6074 I KnoxUsageLogPro: premStatus:2
,09-09 13:41:16.086  6074  6074 I KnoxUsageLogPro: isEulaShown : false
09-09 13:41:16.086  6074  6074 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,09-09 13:41:16.096  1259  1630 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:16.096  1259  1630 V NetworkStats: updateIfacesLocked()
09-09 13:41:16.096  1259  1623 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-09 13:41:16.096  1259  1630 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:41:16.096  1259  1623 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 13:41:16.096  1259  1259 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-09 13:41:16.096  1259  1259 I WifiTrafficPoller: mBoosterFLAG : 0
09-09 13:41:16.096  1259  1259 I WifiTrafficPoller: current booster mode : FullMode
09-09 13:41:16.096  1259  1259 I Wifi-SensorMonitor: enable sensor monitoring : true
,09-09 13:41:16.096  1259  1259 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 4096, 8388608
09-09 13:41:16.096  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:16.096  1259  1259 D SensorHAL: GRIP_WIFI  set_enable 
09-09 13:41:16.096  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:16.096  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:16.106  1259  1630 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:16.096  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:16.106  1259  1630 V NetworkStats: performPollLocked() took 4ms
09-09 13:41:16.106  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-09 13:41:16.106  1259  2304 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
09-09 13:41:16.106  1974  1974 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,09-09 13:41:16.106  1259  1987 D SecContentProvider2: query(), uri = 15 selection = getToastGravityEnabledState
,09-09 13:41:16.106  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aebffdc u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{54b8953 6035:com.sec.android.diagmonagent/1000}
09-09 13:41:16.106  6035  6035 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:16.106  6035  6035 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
09-09 13:41:16.106  6035  6035 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
09-09 13:41:16.106  1259  1630 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:16.106  1259  1630 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]
09-09 13:41:16.106  1259  1630 D ConnectivityService: Not required to send intent.
09-09 13:41:16.106  1259  1630 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
09-09 13:41:16.106  1259  1630 E ConnectivityService: updateNetworkInfo()
09-09 13:41:16.106  1259  1630 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
,09-09 13:41:16.106  1259  1630 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]
09-09 13:41:16.106  1259  1630 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:16.106  1259  1630 V NetworkStats: updateIfacesLocked()
09-09 13:41:16.106  1259  1630 V NetworkStats: performPollLocked(flags=0x1)
,09-09 13:41:16.116  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:16.116  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:16.116  6035  6035 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 android.content.ContextWrapper.sendBroadcast:410 android.content.ContextWrapper.sendBroadcast:410 com.sec.android.diagmonagent.DiagMonConnectivityChangeReciever.onReceive:19 android.app.ActivityThread.handleReceiver:3637 
09-09 13:41:16.116  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:16.116  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:16.116  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:16.116  1259  1630 D NetworkStatsRecorder: entry.iface is null
,09-09 13:41:16.116  1259  1630 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:16.116  1259  1630 V NetworkStats: performPollLocked() took 4ms
09-09 13:41:16.116  1259  1630 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:16.116  1259  1630 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]
,09-09 13:41:16.116  1259  1630 D ConnectivityService: scheduleUnvalidatedPrompt 504
09-09 13:41:16.116  1259  6478 D NetworkMonitor/NetworkAgentInfo [WIFI () - 504]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:16.116  1259  1630 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 504]
09-09 13:41:16.116  1259  6478 D NetworkMonitor/NetworkAgentInfo [WIFI () - 504]: Connected
09-09 13:41:16.116  1259  1630 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-09 13:41:16.116  1259  6478 D NetworkMonitor: registerReceiver Captive portal receiver
09-09 13:41:16.116  1259  1623 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-09 13:41:16.116  1259  1630 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-09 13:41:16.116  1259  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: true
09-09 13:41:16.116  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:16.116  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:16.116  1259  1623 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 13:41:16.116  1259  6478 D NetworkMonitor/NetworkAgentInfo [WIFI () - 504]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:16.116  1259  6478 D NetworkMonitor/NetworkAgentInfo [WIFI () - 504]: Validated
09-09 13:41:16.116  1259  1630 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,09-09 13:41:16.116  1974  5601 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
09-09 13:41:16.116  1974  5601 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-09 13:41:16.116  1259  1630 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
09-09 13:41:16.116  1259  1630 D ConnectivityService: currentScore = 0, newScore = 20
09-09 13:41:16.116  1259  1630 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 504]
09-09 13:41:16.116  1259  1630 D ConnectivityService:    accepting network in place of null
09-09 13:41:16.116  1259  1630 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.116  1259  1651 D Ethernet: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.116  1259  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-09 13:41:16.116  1259  1651 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
09-09 13:41:16.116  1259  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
09-09 13:41:16.116  1259  1623 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.116  1259  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-09 13:41:16.116  1259  1651 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 13:41:16.116  1259  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
09-09 13:41:16.116  1259  1651 D Ethernet: evalRequest
09-09 13:41:16.116  1259  1630 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-09 13:41:16.116  1259  1651 D Ethernet:   done
09-09 13:41:16.116  1259  1623 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:16.116  1259  1623 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 13:41:16.116  1259  1623 D WIFI    : evalRequest
09-09 13:41:16.116  1259  1623 D WIFI    :   done
09-09 13:41:16.116  1259  1623 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.116  1259  16,23 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:16.116  1259  1623 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 13:41:16.116  1259  1623 D WIFI    : evalRequest
09-09 13:41:16.116  1259  1623 D WIFI    :   done
09-09 13:41:16.116  1259  1623 D WIFI_UT : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.116  1259  1623 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:16.116  1259  1989 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aebffdc u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a6a9da7 6058:com.sec.app.RilErrorNotifier/1000}
09-09 13:41:16.116  1259  1623 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 13:41:16.116  1259  1623 D WIFI_UT : evalRequest
09-09 13:41:16.116  1259  1623 D WIFI_UT :   done
09-09 13:41:16.116  1259  1622 D WIFI_P2P: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.116  1259  1622 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:16.116  1259  1622 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 13:41:16.116  1259  1622 D WIFI_P2P: evalRequest
09-09 13:41:16.116  1259  1622 D WIFI_P2P:   done
09-09 13:41:16.116  6058  6058 I PhoneErrorReceiver: onReceive
09-09 13:41:16.126  6058  6058 I MIPErrReceiver: isWiFiConnected
,09-09 13:41:16.126  1259  2294 D SecContentProvider2: query(), uri = 15 selection = getToastEnabledState
09-09 13:41:16.126  1259  2621 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-09 13:41:16.126  1259  2310 D SecContentProvider2: query(), uri = 15 selection = getToastShowPackageNameState
,09-09 13:41:16.126  1259  1324 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aebffdc u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8c16b67 5671:com.enhance.gameservice/u0a79}
,09-09 13:41:16.136  1694  2108 D QSTile.WifiTile: handleUpdateState  cb.changed 14 wifiEnabled : ON cb.enabledDesc NG700
09-09 13:41:16.136  1259  1259 D SensorHAL: sx9310_grip_wifi: power-on.
09-09 13:41:16.136  1259  1259 D SensorManager: registerListener :: 17, SX9310 Grip Sensor wifi, 200000, 0,  
09-09 13:41:16.136  1259  1259 I Wifi-SensorMonitor: disable powerbackoff
09-09 13:41:16.136  1259  1259 D WifiNative-wlan0: callSECApiInt - ID [70]
,09-09 13:41:16.136  1259  1259 D WifiNative-wlan0: callSECApiVoid - ID [212]
09-09 13:41:16.136  6454  6454 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-09 13:41:16.136  6454  6454 I wpa_supplicant: P2P: Current p2p state = IDLE
09-09 13:41:16.136  1259  1259 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
09-09 13:41:16.136  1259  1259 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-09 13:41:16.136  6454  6454 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-09 13:41:16.136  1259  1259 D HS20StateMachine: SSID : "NG700"
09-09 13:41:16.136  1259  1259 D HS20StateMachine: NetId : 0
09-09 13:41:16.136  1259  1259 D HS20StateMachine: checkifOSUAP  null
09-09 13:41:16.136  1259  1259 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,09-09 13:41:16.136  1259  1628 I WifiHs20Service: Message received 5007
09-09 13:41:16.136  1694  2072 D ViewRootImpl: #1 mView = android.widget.LinearLayout{49f2f23 V.E...... ......I. 0,0-0,0 #102039d android:id/toast_layout_root}
09-09 13:41:16.136  1259  2621 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aebffdc u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f996d43 6074:com.sec.knox.switcher/1000}
09-09 13:41:16.136  6074  6074 I usagelog: received in receiver
,09-09 13:41:16.136  6074  6074 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
09-09 13:41:16.136  6074  6074 I KnoxUsageLogPro: premStatus:2
09-09 13:41:16.136  6074  6074 I KnoxUsageLogPro: isEulaShown : false
09-09 13:41:16.136  6074  6074 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,09-09 13:41:16.146  1259  2008 V MARsPolicyManager: handelAlertToastWindowStarted pkgName = com.android.systemui
09-09 13:41:16.146  1259  2320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{22c8f9d u0 com.sec.android.diagmonagent.intent.NETWORK_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{54b8953 6035:com.sec.android.diagmonagent/1000}
,09-09 13:41:16.146  6035  6035 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: com.sec.android.diagmonagent.intent.NETWORK_CHANGED
,09-09 13:41:16.146  6035  6035 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
09-09 13:41:16.146  6035  6035 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(67/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,09-09 13:41:16.146   552  1413 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 13:41:16.156   443   443 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=4, Uoast
,09-09 13:41:16.166  1694  1694 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 148
,09-09 13:41:16.166  1259  1325 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1259
,09-09 13:41:16.166   552  1413 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 13:41:16.176  1259  1630 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.176  1259  1630 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.176  1259  1630 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=5, legacyType=-1, [] ]
,09-09 13:41:16.176  1259  1630 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } for legacy network type 1
09-09 13:41:16.176  1259  1630 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
09-09 13:41:16.176  1259  1630 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:16.176  1259  1416 D EntConnectivity: Not allowed due to - mEnabled false
09-09 13:41:16.176  1259  2320 D ConnectivityService: getVpnConfig > userId : 0
,09-09 13:41:16.176  1259  1630 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-09 13:41:16.176  1259  1630 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-09 13:41:16.176  1259  1630 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/1259 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.176  1259  1630 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
09-09 13:41:16.176  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.176  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 13:41:16.176  1259  1630 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.176  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
09-09 13:41:16.176  1259  1630 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=5, legacyType=-1, [] ]
09-09 13:41:16.176  1694  2072 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-09 13:41:16.176  1259  1416 D EntConnectivity: Not allowed due to - mEnabled false
09-09 13:41:16.176  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.176  1259  1630 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.176  1259  1630 D ConnectivityService: EVENT_PROVISIONING_NOTIFICATION is sent for TYPE_MOBILE.
09-09 13:41:16.176  1259  1630 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-09 13:41:16.176  1259  1630 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] validation  passed
09-09 13:41:16.176  1259  1630 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]
09-09 13:41:16.176  1259  1630 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,09-09 13:41:16.176  1259  1416 D Tethering: MasterInitialState.processMessage what=3
09-09 13:41:16.176  1259  1630 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-09 13:41:16.176  1259  1623 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.176  1259  1630 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
09-09 13:41:16.176  1259  1623 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:16.176  1259  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-09 13:41:16.176  1259  1651 D Ethernet: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.176  1259  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
09-09 13:41:16.176  1259  1623 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 13:41:16.176  1259  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-09 13:41:16.176  1259  1623 D WIFI    : evalRequest
09-09 13:41:16.176  1259  1259 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-09 13:41:16.176  1259  1623 D WIFI    :   done
09-09 13:41:16.176  1259  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
09-09 13:41:16.176  1259  1651 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
09-09 13:41:16.176  1259  1630 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-09 13:41:16.176  1259  1651 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Ca,pabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 13:41:16.176  1259  1630 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-09 13:41:16.176  1259  1651 D Ethernet: evalRequest
09-09 13:41:16.176  1259  1630 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/1259 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.176  1259  1651 D Ethernet:   done
09-09 13:41:16.176  1259  1630 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 504]
09-09 13:41:16.176  1259  1623 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.176  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.176  1259  1623 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:16.176  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.176  1259  1623 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 13:41:16.176  1259  1630 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.176  1259  1623 D WIFI    : evalRequest
09-09 13:41:16.176  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
09-09 13:41:16.176  1259  1623 D WIFI    :   done
09-09 13:41:16.176  1259  1630 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
09-09 13:41:16.176  1259  1623 D WIFI_UT : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.176  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.176  1259  1623 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:16.176  1259  1630 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.176  1259  1623 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 13:41:16.176  1259  1630 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.176  1259  1630 D ConnectivityService: sendStick,yBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-09 13:41:16.186  1259  1623 D WIFI_UT : evalRequest
09-09 13:41:16.186  1259  1623 D WIFI_UT :   done
09-09 13:41:16.186  1259  1874 V AlarmManager:  remove PendingIntent] PendingIntent{39adc39: PendingIntentRecord{51f527e android broadcastIntent}}
09-09 13:41:16.186  1259  1622 D WIFI_P2P: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.186  1259  1622 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:16.186  1259  1631 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
09-09 13:41:16.186  1259  1622 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 13:41:16.186  1259  1622 D WIFI_P2P: evalRequest
09-09 13:41:16.186  1259  1622 D WIFI_P2P:   done
09-09 13:41:16.186  1974  1985 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
09-09 13:41:16.186  1974  1985 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-09 13:41:16.186  1259  1631 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
09-09 13:41:16.186  1259  1259 D LocSvc_java: onReceive
09-09 13:41:16.186  1259  1259 D LocSvc_java: got connectivity action
09-09 13:41:16.186  1259  1259 D LocSvc_java: Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
09-09 13:41:16.186  1259  1259 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-09 13:41:16.186  1259  1259 D LocSvc_java: handleMessage msg = 4
09-09 13:41:16.186  1259  1259 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 13:41:16.186  1259  1259 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true] info.getType():1
09-09 13:41:16.186  1259  1378 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:16.186  1259  1259 V MARsPolicyManager: DataConnection: true
09-09 13:41:16.186  1259  1378 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-09 13:41:16.196   746  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 64
09-09 13:41:16.196   746  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-09 13:41:16.196   746  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-09 13:41:16.196   746  1442 I QC-NETMGR-LIB: Processing RTM_NEWADDR
09-09 13:41:16.196   746  1442 I QC-NETMGR-LIB: Metainfo:  Family=10 PrefixLen=64 Scope=0xfd Index=17 Flags=[0x80]PERMANENT 
09-09 13:41:16.196   746  1442 I QC-NETMGR-LIB: Attribute: PrefixIPv6 addr [fe80:0000:0000:0000:4678:3eff:feeb:95ef]
09-09 13:41:16.196   746  1442 I QC-NETMGR-LIB: Attribute: Address Cache Info - prefered=-1 valid=-1 cstamp=0x3360 tstamp=0x3360
09-09 13:41:16.196   746  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [20]
09-09 13:41:16.196   746  1442 E QC-NETMGR-LIB: unrecognized ifindex 17
09-09 13:41:16.196  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:16.196  1259  1621 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:16.196  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:16.196  1259  1621 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]
09-09 13:41:16.196  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:16.196  1259  1621 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-09 13:41:16.196  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:16.196  3109  3109 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@3390fb1 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-09 13:41:16.196  1259  1378 D GpsLocationProvider: handleMessage msg = 4
09-09 13:41:16.196  3109  3109 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-09 13:41:16.196  1259  1630 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=true
09-09 13:41:16.196  1259  1630 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,fe80::4678:3eff:feeb:95ef/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}
09-09 13:41:16.196  1259  1630 D ConnectivityService: identical MTU - not setting
09-09 13:41:16.206  1259  1630 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:16.206  1259  1630 V NetworkStats: updateIfacesLocked()
09-09 13:41:16.206  1259  1630 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:41:16.206  1259  2304 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-09 13:41:16.206  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:16.206  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:16.206  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:16.206  1259  1630 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:16.206  1259  1630 V NetworkStats: performPollLocked() took 3ms
09-09 13:41:16.206  1259  1630 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:16.206  1259  1987 V WindowStateAnimator: Finishing drawing window Window{e566e74 u0 d0 Toast}: mDrawState=DRAW_PENDING
09-09 13:41:16.206  1974  2242 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
09-09 13:41:16.206  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-09 13:41:16.206  1694  2072 D NetworkController: onReceive: intent=Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-09 13:41:16.216  1974  2242 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-09 13:41:16.216  1259  1378 D TelephonyManager: getDataEnabled: retVal=true
09-09 13:41:16.216  1259  1623 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(VALID)
09-09 13:41:16.216  1259  1623 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(1)
09-09 13:41:16.216  1259  1259 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-09 13:41:16.216  1259  1630 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:16.216  1259  1630 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]
09-09 13:41:16.216  5955  5955 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
09-09 13:41:16.216  1259  1630 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
09-09 13:41:16.216  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.216  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.216  1259  1630 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.216  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:16.216  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
09-09 13:41:16.216  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:16.216  1259  1630 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
09-09 13:41:16.216  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.216  1259  1630 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.216  1259  1630 D ConnectivityService: Not required to send intent.
09-09 13:41:16.216  1259  1630 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
09-09 13:41:16.216  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.216  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.216  1259  1630 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.216  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
09-09 13:41:16.216  1259  1623 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:41:16.216  1259  1623 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:41:16.216  1259  1623 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,09-09 13:41:16.216  1259  1630 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
09-09 13:41:16.216  1974  1988 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@d05248a, selection=nullselectionArgs=null, sort=name ASC
09-09 13:41:16.216  1259  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.216  1259  1630 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:16.216  1259  1623 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:41:16.216  1259  1623 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
09-09 13:41:16.216  1694  2072 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-09 13:41:16.216  1694  2072 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
09-09 13:41:16.216  1974  1988 D TelephonyProvider: query: match = 5
09-09 13:41:16.216  1974  1988 D TelephonyProvider: getPreferredApnId(subId = 2147483643),return -1
09-09 13:41:16.216  1974  1988 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
09-09 13:41:16.216  6102  6113 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(47/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
09-09 13:41:16.226  5955  5955 D BluetoothAdapter: STATE_ON
09-09 13:41:16.226  6102  6113 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(47/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
09-09 13:41:16.226  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:16.226  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:16.226  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:16.226  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:16.226  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:16.226  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:16.226  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:16.226  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:16.226  6102  6113 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(43/llIIIIlllllIIllIIllI)] already Eula Agree
09-09 13:41:16.226  1259  1378 E GpsLocationProvider: No APN found to select.
09-09 13:41:16.226  5955  5955 D BluetoothAdapter: STATE_ON
09-09 13:41:16.226  6102  6112 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(47/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
09-09 13:41:16.236  6102  6112 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(47/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
09-09 13:41:16.236  6102  6112 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(43/llIIIIlllllIIllIIllI)] already Eula Agree
09-09 13:41:16.236  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:16.236  5955  5955 D BluetoothAdapter: STATE_ON
09-09 13:41:16.246  5955  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:16.246  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:16.246  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:16.246  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:16.246  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:16.246  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:16.246  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:16.246  5955  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:16.246  5955  5955 D BluetoothAdapter: STATE_ON
09-09 13:41:16.246  5955  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:16.256  1259  2320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1e16fe3 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a8d25ef 1259:system/1000}
,09-09 13:41:16.266  1259  1259 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1e16fe3 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3be25b9 2236:com.google.android.gms/u0a10}
,09-09 13:41:16.266  2236  2236 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 13:41:16.266  2236  3189 I iu.UploadsManager: num queued entries: 0
,09-09 13:41:16.266  2236  3189 I iu.UploadsManager: num updated entries: 0
,09-09 13:41:16.266  2236  3189 I iu.SyncManager: NEXT; no task
09-09 13:41:16.266  1259  2294 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1e16fe3 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3be25b9 2236:com.google.android.gms/u0a10}
,09-09 13:41:16.276  1259  2294 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1e16fe3 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fadd615 1868:com.google.android.gms.persistent/u0a10}
,09-09 13:41:16.276  1259  2320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1e16fe3 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{41777ec 6102:com.policydm/1000}
,09-09 13:41:16.286   552  1409 D EnterpriseController: netId is 0
09-09 13:41:16.286   552  1409 D Netd    : getNetworkForDns: using netid 504 for uid 10010
,09-09 13:41:16.286  6102  6102 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,09-09 13:41:16.296  6102  6102 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,09-09 13:41:16.296  6102  6102 I DBG_POLICYDM: [com.policydm.XDMService(574/llIlIllllllllllllllI)] get NotibarState : 0
,09-09 13:41:16.296  1259  1325 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1e16fe3 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{41777ec 6102:com.policydm/1000}
,09-09 13:41:16.296  6102  6102 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:16.316  6102  6102 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(87/llllIIIllIlIIIIllllI)] device register flag at setting DB : true
,09-09 13:41:16.316  6102  6102 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(96/onReceive)] Already device registered...
,09-09 13:41:16.316  6102  6102 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(87/llllIIIllIlIIIIllllI)] device register flag at setting DB : true
,09-09 13:41:16.326  6102  6102 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(337/lllIlIlIIIllIIlIllIl)] OMC not Supported model
,09-09 13:41:16.326  6102  6102 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(110/llIlIIIIlIIIIIlIlIII)] Polling time is vaild
,09-09 13:41:16.326  6102  6102 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(277/llIIIIlllllIIllIIllI)] Heartbeat settings is activated.
,09-09 13:41:16.326  6102  6102 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(49/llllIIIllIlIIIIllllI)] Next heartbeat time:2016/09/17/23:24:10
,09-09 13:41:16.326  6102  6102 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(52/llllIIIllIlIIIIllllI)] heartbeat time is vaild
,09-09 13:41:16.336  1259  1385 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1e16fe3 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{56d884 6129:com.osp.app.signin/u0a27}
,09-09 13:41:16.336  6129  6129 I SA      : [OR] onReceive log=[SA = 2.2.01-51 V = 23 HWD = 2048X1536 2.0 dpi = 320  SIZE = 4 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = gts28velte P = gts28veltexx I = MMB29M M = SM-T719 OKLEFT false DIS MMB29M.T719XXU1APF6 PSS = 8.00525302084415  ]
09-09 13:41:16.336  6129  6129 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
09-09 13:41:16.336  6129  6129 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-09 13:41:16.346  6129  6129 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-09 13:41:16.346  6129  6129 I SA      : [OR] == isSIMCardReady false ==
,09-09 13:41:16.346  6129  6129 I SA      : [SCU] == networkStateCheck == true
09-09 13:41:16.346  6129  6129 I SA      : [DM] getCountryCodeFromCSC : PL
09-09 13:41:16.346  6129  6129 I SA      : isChinaCountryCode : false
09-09 13:41:16.346  6129  6129 I SA      : [SCU] is ChinestModel Data Restricted   : false
,09-09 13:41:16.346  6129  6129 I SA      : [OR] == networkStateCheck true ==
09-09 13:41:16.346  6129  6129 I SA      : [OR] GetMyCountryZoneTask
,09-09 13:41:16.346  6129  6129 I SA      : [OR] onReceive END
09-09 13:41:16.346  6129  6523 I SA      : [SRS] prepareGetMyCountryZone
,09-09 13:41:16.356  1259  2008 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1e16fe3 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5827062 5955:com.test.thalitest/u0a136}
,09-09 13:41:16.356  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:16.356  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-09 13:41:16.356  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:16.356  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:16.356  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:16.356  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:16.356  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:16.356  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:16.356  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:16.356  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:16.356  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:16.356  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:16.356  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:16.356  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:16.356  1259  1637 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-09 13:41:16.356  6129  6523 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-09 13:41:16.356  6129  6523 I SA      : [SSP] query invoked
09-09 13:41:16.356  1259  2629 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1e16fe3 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1ce268a 5214:com.wssyncmldm/1000}
,09-09 13:41:16.356  6129  6523 I SA      : [TPMU] GetMccFromDB : null
09-09 13:41:16.356  6129  6523 I SA      : [SCU] getMccFromPreferece mcc = 260
09-09 13:41:16.356  6129  6523 I SA      : [LBE] isSupportCheckDomainRegion : true
09-09 13:41:16.356  6129  6523 I SA      : [TPM] isNoProxy(default) : true
,09-09 13:41:16.356  6129  6523 I System.out: (HTTPLog)-Static: Hongbao
09-09 13:41:16.366  6129  6523 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
09-09 13:41:16.366  6129  6523 I System.out: (HTTPLog)-Static: Hongbao
,09-09 13:41:16.366  6058  6058 I PhoneErrorReceiver: onReceive
09-09 13:41:16.366  1259  2621 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1e16fe3 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a6a9da7 6058:com.sec.app.RilErrorNotifier/1000}
09-09 13:41:16.366  6058  6058 V PhoneErrorReceiver: beginStartingService
09-09 13:41:16.376  6058  6058 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1311 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.sec.app.RilErrorNotifier.PhoneErrorReceiver.beginStartingService:194 com.sec.app.RilErrorNotifier.PhoneErrorReceiver.onReceiveWithPrivilege:171 
09-09 13:41:16.376  5214  6524 I FOTA_AGENT: [com.samsung.android.app.fotaclient.llIlIIIIlIIIIIlIlIII(87/llIIIIlllllIIllIIllI)] Nothing to do action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:16.376  1259  1646 D WifiWatchdogStateMachine.CaptivePortalHandler: start check captive portal 
,09-09 13:41:16.376  6058  6058 V PhoneErrService: Creating SmsReceiverService
09-09 13:41:16.376  6058  6058 V MIP_PhoneErrService: mTelephonyManager is not null
,09-09 13:41:16.376  1259  1324 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1e16fe3 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ace8b17 4424:com.sec.spp.push/u0a26}
,09-09 13:41:16.386  4424  4424 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:16.386  4424  4424 E SPPClientService: [SystemStateMoniter] Current Time : 132711
,09-09 13:41:16.386  4424  4424 E SPPClientService: [SystemStateMoniter] No Connect : false
,09-09 13:41:16.386  6129  6523 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
09-09 13:41:16.386  6129  6523 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-09 13:41:16.386  6129  6523 I System.out: (HTTPLog)-Static: Hongbao
09-09 13:41:16.386  6129  6523 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-09 13:41:16.386   552  1409 D EnterpriseController: netId is 0
09-09 13:41:16.386   552  1409 D Netd    : getNetworkForDns: using netid 504 for uid 10027
,09-09 13:41:16.386  1259  1637 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1e16fe3 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ce11b0e 2481:android.process.media/u0a33}
09-09 13:41:16.386  6058  6058 V PhoneErrService: Starting #1: Bundle[mParcelledData.dataSize=388]
09-09 13:41:16.386  6058  6058 I PhoneErrService: mResultCode: 0
09-09 13:41:16.386  6058  6058 V MIP_PhoneErrService: onDataConnectionState : -1
09-09 13:41:16.386  6058  6526 V PhoneErrService: Handling incoming message: { when=0 what=0 arg1=1 obj=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.sec.app.RilErrorNotifier/.PhoneErrService bqHint=3 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } target=com.sec.app.RilErrorNotifier.PhoneErrService$ServiceHandler }
09-09 13:41:16.386  6058  6526 V PhoneErrorReceiver: finishStartingService
,09-09 13:41:16.386  2481  2481 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:16.386  6058  6058 V PhoneErrService: Destroying PhoneErrorReceiverService
,09-09 13:41:16.396  1259  1989 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1e16fe3 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6454e69 6147:com.samsung.android.SettingsReceiver/1000}
,09-09 13:41:16.406  1259  2304 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
09-09 13:41:16.406  1259  2320 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1e16fe3 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bb1cd0d 2464:com.microsoft.skydrive/u0a93}
,09-09 13:41:16.416  1259  1637 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
,09-09 13:41:16.416  1259  1637 D PackageManager: findPreferredActivity: No PreferredActivities set
09-09 13:41:16.416  1259  1637 I PackageManager: No preferred activity: intent should not be shown
,09-09 13:41:16.416  1259  2629 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1e16fe3 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e6698f 6172:com.google.android.apps.photos/u0a97}
,09-09 13:41:16.426  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{631273f u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e6698f 6172:com.google.android.apps.photos/u0a97}
,09-09 13:41:16.426  1259  2629 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1e16fe3 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e6698f 6172:com.google.android.apps.photos/u0a97}
,09-09 13:41:16.436  1259  1646 D WifiWatchdogStateMachine.CaptivePortalHandler: result = 0, mCaptivePortalCheckMode = 11, mCouldNotIdentifyCaptivePortalState = true
,09-09 13:41:16.446  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f9af85b u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e6698f 6172:com.google.android.apps.photos/u0a97}
,09-09 13:41:16.446  1259  1637 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1e16fe3 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ba36c24 4746:com.sec.android.daemonapp/u0a127}
,09-09 13:41:16.446  4746  4746 D [WeatherWidget(1210)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
09-09 13:41:16.446  4746  4746 D [WeatherWidget(1210)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78152C254DDD0027D207FA50AD616546E30965FECE0D7B834EEF4B0E211833EA2B]}
,09-09 13:41:16.456  1259  1637 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1e16fe3 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bd6dd8 5344:com.sec.android.app.samsungapps/u0a9}
,09-09 13:41:16.456  5344  5344 D WaitQueueForNetworkActivate: notifyNetworkActivated
,09-09 13:41:16.456  2970  3035 I WCNSS_FILTER: do_write: IBS write: fe
09-09 13:41:16.456  2970  3035 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-09 13:41:16.466  5344  5344 D hcjo    : AutoUpdateManager:IDLE:execute
,09-09 13:41:16.466  5344  5344 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
09-09 13:41:16.466  5344  5344 D InitializeManagerStateMachine: exit::IDLE
09-09 13:41:16.466  5344  5344 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,09-09 13:41:16.466  1259  2320 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-09 13:41:16.466  1259  2621 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-09 13:41:16.466  5344  5344 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
09-09 13:41:16.466  5344  5344 D InitializeManagerStateMachine: exit::NETWORK_CHECK
09-09 13:41:16.466  5344  5344 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
09-09 13:41:16.466  5344  5344 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
09-09 13:41:16.466  5344  5344 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
09-09 13:41:16.466  5344  5344 D InitializeManagerStateMachine: entry::SUCCESS
09-09 13:41:16.466  5344  5344 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,09-09 13:41:16.466  5344  5344 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
09-09 13:41:16.466  5344  5344 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,09-09 13:41:16.466  1259  2294 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-09 13:41:16.466  5344  5344 D InitializeManagerStateMachine: exit::SUCCESS
09-09 13:41:16.466  5344  5344 D InitializeManagerStateMachine: entry::IDLE
,09-09 13:41:16.726  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2679436 u0 com.google.android.gcm.CONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9ff3cb0 5496:com.google.android.talk/u0a84}
,09-09 13:41:16.736  1259  1987 V AlarmManager:  remove PendingIntent] PendingIntent{d06bf37: PendingIntentRecord{1a062e8 com.google.android.gms broadcastIntent}}
,09-09 13:41:17.176  1259  1630 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 503] cleared because we found a replacement network
,09-09 13:41:17.206  6129  6523 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 816
,09-09 13:41:17.206  6129  6523 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,09-09 13:41:17.216  6129  6523 I SA      : [OCP] update openData : PL
,09-09 13:41:17.216  6129  6523 I SA      : [TPMU] getNetworkMcc : 
,09-09 13:41:17.216  6129  6523 I SA      : [SCU] saveMccToPreferece Start
09-09 13:41:17.216  6129  6523 I SA      : [SCU] RegionMCC : 260
09-09 13:41:17.216  6129  6523 I SA      : [SSP] query invoked
,09-09 13:41:17.226  6129  6523 I SA      : [TPMU] GetMccFromDB : null
09-09 13:41:17.226  6129  6523 I SA      : [SCU] getMccFromPreferece mcc = 260
09-09 13:41:17.226  6129  6523 I SA      : [SCU] saveMccToPreferece End
09-09 13:41:17.226  6129  6523 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 864
09-09 13:41:17.226  6129  6523 I SA_HTTPURLCONNECTION: [RC New] Execute end
,09-09 13:41:17.226  6129  6129 I SA      : [OR] GetMyCountryZoneTask mcc = 260
09-09 13:41:17.226  6129  6129 I SA      : [OR] GetMyCountryZoneTask Success
,09-09 13:41:17.616   720   720 I MSM-irqbalance: Decided to move IRQ65 from CPU3 to CPU1
,09-09 13:41:18.136  1694  2072 D ViewRootImpl: #3 mView = null
,09-09 13:41:18.136   443   466 I SurfaceFlinger: id=21 Removed Uoast (11/14)
,09-09 13:41:18.136   443   464 I SurfaceFlinger: id=21 Removed Uoast (-2/14)
,09-09 13:41:18.146  1259  1325 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1259 (0x0)
,09-09 13:41:18.146  1259  1325 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1259, ws=WorkSource{10046}) (elapsedTime=1978)
,09-09 13:41:18.966  5955  6005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-09 13:41:18.966  5955  6005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 13:41:18.966  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:41:18.966  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:41:18.966  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:41:18.966  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:18.966  5955  6487 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:41:18.966  5955  6487 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:41:18.966  5955  6005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:41:18.966  5955  6487 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:41:18.966  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:41:18.966  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:41:18.966  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:41:18.966  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:41:18.966  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:41:18.966  5955  5955 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:41:18.966  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:18.966  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:41:18.966  5955  6005 D BluetoothLeScanner: could not find callback wrapper
09-09 13:41:18.966  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:41:18.966  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-09 13:41:18.966  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:41:18.966  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:41:18.966  5955  6005 D BluetoothLeAdvertiser: stop advertising
,09-09 13:41:18.976  2569  6413 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-09 13:41:18.976  2569  6413 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-09 13:41:18.976  2569  2761 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
09-09 13:41:18.976  2569  2761 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
09-09 13:41:18.976  2569  2761 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-09 13:41:18.976  2569  2761 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-09 13:41:18.976  2569  2761 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
09-09 13:41:18.976  2569  2746 D BtGatt.AdvertiseManager: message : 1
09-09 13:41:18.976  2569  2746 D BtGatt.AdvertiseManager: stop advertise for client =  6
09-09 13:41:18.976  2569  2746 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
,09-09 13:41:18.976  2569  2746 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-09 13:41:18.976  2970  2971 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl(),
09-09 13:41:18.976  1259  2304 V AlarmManager:  remove PendingIntent] PendingIntent{5ac5ca4: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:18.986  2970  2971 I WCNSS_FILTER: do_write: IBS write: fd
,09-09 13:41:18.986  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
,09-09 13:41:18.986  2970  2970 I WCNSS_FILTER: do_write: IBS write: fc
,09-09 13:41:18.986  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-09 13:41:18.986  2970  2971 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-09 13:41:18.986  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
09-09 13:41:18.986  2569  2739 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-09 13:41:18.986  2569  2739 D BtGatt.GattService: Client app is not null!
09-09 13:41:18.986  5955  5965 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
09-09 13:41:18.986  1259  1853 V AlarmManager:  remove PendingIntent] PendingIntent{9759a0d: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:18.986  2569  6412 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 13:41:18.986  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 13:41:18.986  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:41:18.986  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-09 13:41:18.986  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-09 13:41:18.996  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-09 13:41:18.996  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:18.996  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:41:18.996  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:41:18.996  1259  1721 V AlarmManager:  remove PendingIntent] PendingIntent{f10bdc2: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:18.996  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:18.996  5955  5955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:41:18.996  5955  5955 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-09 13:41:18.996  5955  5955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:41:18.996  5955  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:18.996  5955  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:18.996  5955  5955 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:18.996  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:18.996  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:18.996  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:18.996  5955  6005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a8eab3 not in the list
09-09 13:41:18.996  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:18.996  5955  6005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0a870 not in the list
09-09 13:41:18.996  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:18.996  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:18.996  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:18.996  5955  6005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:41:18.996  5955  6005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:41:18.996  5955  6005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:41:18.996  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:41:18.996  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:18.996  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:41:19.006  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
,09-09 13:41:19.006  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
,09-09 13:41:19.006  1259  1989 V AlarmManager:  remove PendingIntent] PendingIntent{330f40e: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:19.006  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-09 13:41:19.006  5955  6005 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 13:41:19.006  1259  2304 V AlarmManager:  remove PendingIntent] PendingIntent{7085e2f: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:19.006  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:41:19.006  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:19.016  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:41:19.016  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:19.016  1259  2621 V AlarmManager:  remove PendingIntent] PendingIntent{29c9c3c: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:19.016  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:41:19.016  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:41:19.016  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:41:19.016  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 13:41:19.016  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:41:19.016  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:19.026  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:19.026  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:19.026  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:41:19.026  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 13:41:19.026  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 13:41:19.026  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 13:41:19.026  5955  6005 D BluetoothLeScanner: Start Scan
,09-09 13:41:19.026  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:19.026  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:19.026  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:19.036  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:19.036  2569  2589 D BtGatt.GattService: registerClient() - UUID=07ef2414-f571-4f40-b471-03fed5606cf3
,09-09 13:41:19.076  2569  2739 D BtGatt.GattService: onClientRegistered() - UUID=07ef2414-f571-4f40-b471-03fed5606cf3, clientIf=6
09-09 13:41:19.076  5955  5965 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-09 13:41:19.076  2569  3151 D BtGatt.GattService: start scan with filters
,09-09 13:41:19.076  2569  3151 D BtGatt.GattService: getScanSettings
,09-09 13:41:19.086  2569  3151 D BtGatt.GattService: Is it foreground application = false
,09-09 13:41:19.086  2569  3151 D BtGatt.GattService: not a background application
,09-09 13:41:19.086  2569  3151 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-09 13:41:19.096  2569  3151 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest,
09-09 13:41:19.096  2569  3151 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-09 13:41:19.096  2569  2761 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
,09-09 13:41:19.096  2569  2761 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
,09-09 13:41:19.096  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 13:41:19.096  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 13:41:19.096  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 13:41:19.096  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 13:41:19.096  2569  2748 D BtGatt.ScanManager: handling starting scan
09-09 13:41:19.096  2569  2748 D BtGatt.ScanManager: isFilteringSupported
09-09 13:41:19.096  2569  2748 D BluetoothAdapter: enableStandAloneBleMode=
09-09 13:41:19.096  2569  2748 D BluetoothAdapter: STATE_ON
,09-09 13:41:19.096  2569  2748 D BluetoothAdapter: STATE_ON,
,09-09 13:41:19.096  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
09-09 13:41:19.096  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 13:41:19.096  5955  5955 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 13:41:19.106  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-09 13:41:19.106  2569  2748 D BluetoothAdapter: STATE_ON
,09-09 13:41:19.106  2569  2748 D BluetoothAdapter: STATE_ON
09-09 13:41:19.106  2569  2748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b2cb7b
,09-09 13:41:19.106  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-09 13:41:19.106  2970  2970 I WCNSS_FILTER: do_write: IBS write: fc
09-09 13:41:19.106  1259  1324 V AlarmManager:  remove PendingIntent] PendingIntent{6b0fdc5: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:19.106  2569  2739 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-09 13:41:19.106  2569  2739 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 13:41:19.106  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 9 : bytes_written: 9
,09-09 13:41:19.106  2569  2748 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
09-09 13:41:19.106  2569  2748 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-09 13:41:19.106  2569  2748 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-09 13:41:19.106  2569  2748 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
,09-09 13:41:19.106  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 22 : bytes_written: 22
09-09 13:41:19.116  1259  1853 V AlarmManager:  remove PendingIntent] PendingIntent{20c431a: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:19.116  2569  2761 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 17
09-09 13:41:19.116  2569  2761 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
09-09 13:41:19.116  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 10 : bytes_written: 10
09-09 13:41:19.116  2569  2739 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-09 13:41:19.116  2569  2739 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 13:41:19.116  2569  2748 D BtGatt.ScanManager: Starting BLE batch scan
09-09 13:41:19.116  2569  2748 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-09 13:41:19.116  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-09 13:41:19.116  1259  2320 V AlarmManager:  remove PendingIntent] PendingIntent{bc6ae4b: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:19.116  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-09 13:41:19.116  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 8 : bytes_written: 8
,09-09 13:41:19.116  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-09 13:41:19.116  2569  2739 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-09 13:41:19.116  2569  2739 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 13:41:19.116  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 16 : bytes_written: 16
09-09 13:41:19.116  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-09 13:41:19.126  2569  2739 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-09 13:41:19.126  2569  2739 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 13:41:19.126  2569  2761 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 442
09-09 13:41:19.126  1259  2008 V AlarmManager:  remove PendingIntent] PendingIntent{5b54028: PendingIntentRecord{ea8b141 com.android.bluetooth broadcastIntent}}
09-09 13:41:19.126  1259  2621 V AlarmManager:  remove PendingIntent] PendingIntent{d1b76e6: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:19.126  1259  2304 V AlarmManager:  remove PendingIntent] PendingIntent{ecfe427: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:19.126  1259  1637 V AlarmManager:  remove PendingIntent] PendingIntent{33236d4: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:19.126  2569  2761 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24557021
,09-09 13:41:19.136  2569  2761 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
09-09 13:41:19.136  2569  2761 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-09 13:41:19.136  2569  2761 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,09-09 13:41:19.136  2569  2761 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-09 13:41:19.136  2569  2761 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-09 13:41:19.136  2569  2761 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-09 13:41:19.136  2569  2761 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-09 13:41:19.136  1259  1989 V AlarmManager:  remove PendingIntent] PendingIntent{50e207d: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:19.136  2569  2761 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
,09-09 13:41:19.136  2569  2761 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-09 13:41:19.136  2569  2761 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-09 13:41:19.136  2569  2761 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-09 13:41:19.136  2569  2761 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-09 13:41:19.136  2569  2761 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24557021
,09-09 13:41:19.136  1259  2621 V AlarmManager:  remove PendingIntent] PendingIntent{2981b72: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:19.136  1259  1721 V AlarmManager:  remove PendingIntent] PendingIntent{f4c9bc3: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:19.146  1259  1325 V AlarmManager:  remove PendingIntent] PendingIntent{6e5ec40: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:19.606  5955  5955 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-09 13:41:19.606  5955  5955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:41:19.606  5955  5955 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:41:19.736  6480  6480 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,09-09 13:41:20.116  2970  3035 I WCNSS_FILTER: do_write: IBS write: fe
09-09 13:41:20.116  2970  3035 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-09 13:41:20.126  1259  1590 V AlarmManager: Expired Alarm result :4
,09-09 13:41:20.126  2569  2569 D BtGatt.ScanManager: awakened up at time 136456
09-09 13:41:20.126  2569  2748 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 13:41:20.126  2970  2971 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
09-09 13:41:20.126  2970  2971 I WCNSS_FILTER: do_write: IBS write: fd
09-09 13:41:20.126  1259  1324 V AlarmManager:  remove PendingIntent] PendingIntent{55d8c6c: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:20.136  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-09 13:41:20.136  1259  1259 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
09-09 13:41:20.136  1259  1259 V AlarmManagerEXT: <AppSync3 Whitelist>
09-09 13:41:20.136  1259  1259 V AlarmManagerEXT: (AppSync) ### 0 added ###
09-09 13:41:20.136  2970  2970 I WCNSS_FILTER: do_write: IBS write: fc
,09-09 13:41:20.136  1694  1694 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
09-09 13:41:20.136  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 78 : bytes_written: 78
09-09 13:41:20.136  1694  1694 D KeyguardUpdateMonitor: handleTimeUpdate
09-09 13:41:20.136  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
09-09 13:41:20.136  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 53 : bytes_written: 53
09-09 13:41:20.136  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-09 13:41:20.136  1694  1694 D Clock   : received broadcast android.intent.action.TIME_TICK
09-09 13:41:20.136  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 78 : bytes_written: 78
09-09 13:41:20.136  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-09 13:41:20.136  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 78 : bytes_written: 78
09-09 13:41:20.136  1259  2008 V AlarmManager:  remove PendingIntent] PendingIntent{125e235: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:20.136  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
09-09 13:41:20.146  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 52 : bytes_written: 52
09-09 13:41:20.146  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-09 13:41:20.146  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 78 : bytes_written: 78
09-09 13:41:20.146  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-09 13:41:20.146  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 10 : bytes_written: 10
09-09 13:41:20.146  2569  2739 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=6
09-09 13:41:20.146  2569  2739 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 13:41:20.146  2569  2739 D BtGatt.GattService: current time is 136475171352
09-09 13:41:20.146  2569  2739 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -72, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -84, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -70, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -66, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 127, -55, -87, 90, -14, 90, 1, -128, -47, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111, 0, 37, -47, 14, -113, 116, -46, 1, -128, -72, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-09 13:41:20.146  1259  2304 V AlarmManager:  remove PendingIntent] PendingIntent{20ba6ca: PendingIntentRecord{ea8b141 com.android.bluetooth broadcastIntent}}
09-09 13:41:20.146  2569  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-09 13:41:20.146  2569  2739 D ScanRecord: parseFromBytes
09-09 13:41:20.146  2569  2739 D ScanRecord: first manudata for manu ID
09-09 13:41:20.146  1259  1325 V AlarmManager:  remove PendingIntent] PendingIntent{603c03b: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:20.146  2569  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
09-09 13:41:20.146  2569  2739 D ScanRecord: parseFromBytes
09-09 13:41:20.146  2569  2739 D ScanRecord: first manudata for manu ID
09-09 13:41:20.146  2569  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-09 13:41:20.146  2569  2739 D ScanRecord: parseFromBytes
09-09 13:41:20.146  2569  2739 D ScanRecord: first manudata for manu ID
09-09 13:41:20.146  2569  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-09 13:41:20.146  2569  2739 D ScanRecord: parseFromBytes
09-09 13:41:20.146  2569  2739 D ScanRecord: first manudata for manu ID
09-09 13:41:20.146  2569  2739 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, ,58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111]
09-09 13:41:20.146  2569  2739 D ScanRecord: parseFromBytes
09-09 13:41:20.146  2569  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-09 13:41:20.146  2569  2739 D ScanRecord: parseFromBytes
09-09 13:41:20.146  2569  2739 D ScanRecord: first manudata for manu ID
09-09 13:41:20.156  5955  5966 D ScanRecord: parseFromBytes
09-09 13:41:20.156  5955  5966 D ScanRecord: first manudata for manu ID
09-09 13:41:20.156  5955  5966 D ScanRecord: parseFromBytes
09-09 13:41:20.156  5955  5966 D ScanRecord: first manudata for manu ID
09-09 13:41:20.156  5955  5966 D ScanRecord: parseFromBytes
09-09 13:41:20.156  5955  5966 D ScanRecord: parseFromBytes
09-09 13:41:20.156  5955  5966 D ScanRecord: first manudata for manu ID
09-09 13:41:20.156  5955  5966 D ScanRecord: parseFromBytes
09-09 13:41:20.156  5955  5966 D ScanRecord: first manudata for manu ID
09-09 13:41:20.156  5955  5966 D ScanRecord: parseFromBytes
09-09 13:41:20.156  5955  5966 D ScanRecord: first manudata for manu ID
09-09 13:41:20.156  1259  1637 V AlarmManager:  remove PendingIntent] PendingIntent{ccd0358: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:20.156  5955  5955 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> A8:81:95:E9:5F:6F 6], added - the peer count is 1
09-09 13:41:20.156  5955  5955 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 6], Bluetooth address: A8:81:95:E9:5F:6F, device name: '', device address: ''
09-09 13:41:20.156  1259  2621 V AlarmManager:  remove PendingIntent] PendingIntent{85f6cb1: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:20.166  1259  1721 V AlarmManager:  remove PendingIntent] PendingIntent{5a56596: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:20.176  1259  2310 V AlarmManager:  remove PendingIntent] PendingIntent{4642517: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:20.176  1259  1637 V AlarmManager:  remove PendingIntent] PendingIntent{8bafd04: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:20.176  1259  2621 V AlarmManager:  remove PendingIntent] PendingIntent{5cd22ed: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:20.186  1259  2320 V AlarmManager:  remove PendingIntent] PendingIntent{94a4522: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:20.186  1694  1694 D DateView: received broadcast android.intent.action.TIME_TICK
,09-09 13:41:20.196  1259  1853 V AlarmManager:  remove PendingIntent] PendingIntent{ffbfbb3: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}},
,09-09 13:41:20.206  1259  1324 V AlarmManager:  remove PendingIntent] PendingIntent{46ce570: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}},
,09-09 13:41:20.206  1259  1989 V AlarmManager:  remove PendingIntent] PendingIntent{4e600e9: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:20.226  4746  4746 D [WeatherWidget(1210)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB74266231DDCB0F9D898ABD6AE7EAFE9924B51C1628AB73EB6B27EF850A160BD15DCFDBE96F420541C45EF3419D3AD67E2]},
,09-09 13:41:20.226  4746  4746 D [WeatherWidget(1210)]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
09-09 13:41:20.226  1259  1325 V AlarmManager:  remove PendingIntent] PendingIntent{76b916e: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:21.146  2970  3035 I WCNSS_FILTER: do_write: IBS write: fe,
09-09 13:41:21.146  2970  3035 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-09 13:41:21.156  1259  1590 V AlarmManager: Expired Alarm result :4
,09-09 13:41:21.156  2569  2569 D BtGatt.ScanManager: awakened up at time 137482,
09-09 13:41:21.156  2569  2748 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-09 13:41:21.156  2970  2971 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
09-09 13:41:21.156  2970  2971 I WCNSS_FILTER: do_write: IBS write: fd
,09-09 13:41:21.156  1259  1987 V AlarmManager:  remove PendingIntent] PendingIntent{812e89c: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:21.156  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6,
,09-09 13:41:21.156  2970  2970 I WCNSS_FILTER: do_write: IBS write: fc
,09-09 13:41:21.156  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 10 : bytes_written: 10
,09-09 13:41:21.166  2569  2739 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-09 13:41:21.166  2569  2739 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 13:41:21.166  1259  1324 V AlarmManager:  remove PendingIntent] PendingIntent{794c2a5: PendingIntentRecord{ea8b141 com.android.bluetooth broadcastIntent}}
,09-09 13:41:21.166  1259  1325 V AlarmManager:  remove PendingIntent] PendingIntent{e43567a: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}},
,09-09 13:41:21.526  1259  1833 E Watchdog: !@Sync 4 [09-09 13:41:21.530]
,09-09 13:41:22.106  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:22.106  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:22.106  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:22.106  5955  6005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a8eab3 not in the list
09-09 13:41:22.106  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:22.106  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:41:22.106  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:41:22.106  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:41:22.106  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:41:22.106  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 13:41:22.106  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:22.106  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:41:22.106  5955  6005 D BluetoothLeScanner: Stop Scan
,09-09 13:41:22.116  2569  3151 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-09 13:41:22.116  2569  3151 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-09 13:41:22.116  2569  3151 D BtGatt.GattService: stopScan() - queue size =1
09-09 13:41:22.116  2569  2761 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
09-09 13:41:22.116  2569  2761 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
09-09 13:41:22.116  2569  2761 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-09 13:41:22.116  2569  2761 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-09 13:41:22.116  2569  2761 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-09 13:41:22.116  2569  2761 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
,09-09 13:41:22.116  2569  2761 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
09-09 13:41:22.116  2569  6412 D BtGatt.GattService: unregisterClient() - clientIf=6
09-09 13:41:22.116  2569  2748 D BtGatt.ScanManager: filter size is 1
09-09 13:41:22.116  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:41:22.116  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 13:41:22.116  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 13:41:22.116  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 13:41:22.116  2569  2748 D BtGatt.ScanManager: delete FilterIndex - 3
09-09 13:41:22.116  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 13:41:22.116  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
,09-09 13:41:22.116  2970  2970 I WCNSS_FILTER: do_write: IBS write: fc
09-09 13:41:22.116  1259  1325 V AlarmManager:  remove PendingIntent] PendingIntent{3612e2b: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:22.116  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 10 : bytes_written: 10
09-09 13:41:22.116  2569  2739 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-09 13:41:22.116  2569  2739 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 13:41:22.116  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:22.116  2569  2748 D BtGatt.ScanManager: stopping BLe Batch
09-09 13:41:22.116  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 16 : bytes_written: 16
,09-09 13:41:22.116  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:41:22.116  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-09 13:41:22.126  2569  2739 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-09 13:41:22.126  2569  2739 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 13:41:22.126  1259  1987 V AlarmManager:  remove PendingIntent] PendingIntent{cb3f288: PendingIntentRecord{ea8b141 com.android.bluetooth broadcastIntent}}
09-09 13:41:22.126  2569  2748 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-09 13:41:22.126  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-09 13:41:22.126  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:41:22.126  5955  6005 D BluetoothLeAdvertiser: stop advertising
09-09 13:41:22.126  5955  6005 D BluetoothLeAdvertiser: wrapper is null
09-09 13:41:22.126  1259  2294 V AlarmManager:  remove PendingIntent] PendingIntent{9b3e421: PendingIntentRecord{ea8b141 com.android.bluetooth broadcastIntent}}
09-09 13:41:22.126  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 13:41:22.126  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:41:22.126  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:41:22.126  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 10 : bytes_written: 10
09-09 13:41:22.126  2569  2739 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-09 13:41:22.126  2569  2739 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 13:41:22.126  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:22.126  1259  2304 V AlarmManager:  remove PendingIntent] PendingIntent{3a06046: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:22.126  5955  6005 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
09-09 13:41:22.126  5955  6005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0a870 not in the list
09-09 13:41:22.126  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:22.126  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:22.126  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:22.126  5955  6005 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
09-09 13:41:22.126  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
09-09 13:41:22.126  5955  6005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:41:22.126  5955  6005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything,
09-09 13:41:22.126  5955  6005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:41:22.126  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:22.126  5955  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:22.126  5955  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:22.126  5955  5955 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:41:22.136  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 13:41:22.136  5955  6005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-09 13:41:22.136  5955  6005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:41:22.136  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:41:22.136  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:41:22.136  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:22.136  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:41:22.136  5955  5955 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-09 13:41:22.136  5955  6536 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:41:22.136  5955  6536 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:41:22.136  5955  6005 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 13:41:22.136  5955  6005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:41:22.136  5955  6536 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-09 13:41:22.136  1259  2310 V AlarmManager:  remove PendingIntent] PendingIntent{9723ad2: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:22.146  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:22.146  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:41:22.146  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:22.146  1259  2304 V AlarmManager:  remove PendingIntent] PendingIntent{3fb37a3: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:22.146  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:41:22.146  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:22.146  1259  2320 V AlarmManager:  remove PendingIntent] PendingIntent{7fc8aa0: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:22.146  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:41:22.146  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 13:41:22.146  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:41:22.156  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:22.156  1259  2621 V AlarmManager:  remove PendingIntent] PendingIntent{83f659: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:22.156  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-09 13:41:22.156  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-09 13:41:22.156  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 44 78 3E EB 95 EE
09-09 13:41:22.156  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:41:22.156  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:41:22.156  5955  6005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 13:41:22.156  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:22.156  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:41:22.156  5955  6005 D BluetoothLeAdvertiser: start advertising
09-09 13:41:22.156  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:22.156  2569  6412 D BtGatt.GattService: registerClient() - UUID=00a46fe4-a359-451e-9d0e-71e461514c64
,09-09 13:41:22.206  2569  2739 D BtGatt.GattService: onClientRegistered() - UUID=00a46fe4-a359-451e-9d0e-71e461514c64, clientIf=6,
09-09 13:41:22.206  5955  5966 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-09 13:41:22.206  2569  6413 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-09 13:41:22.216  2569  6413 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest,
09-09 13:41:22.216  2569  6413 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-09 13:41:22.216  2569  2761 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
,09-09 13:41:22.216  2569  2761 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
09-09 13:41:22.216  2569  2746 D BtGatt.AdvertiseManager: message : 0
09-09 13:41:22.216  2569  2746 D BtGatt.AdvertiseManager: number of adv instance running = 0
09-09 13:41:22.216  2569  2746 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:41:22.216  2569  2746 D BtGatt.AdvertiseManager: starting advertising
,09-09 13:41:22.216  2569  2746 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-09 13:41:22.216  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 28 : bytes_written: 28
09-09 13:41:22.226  1259  2629 V AlarmManager:  remove PendingIntent] PendingIntent{f15321e: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:22.226  2569  2761 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 15
09-09 13:41:22.226  2569  2761 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24557021
09-09 13:41:22.226  2569  2761 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-09 13:41:22.226  2569  2761 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-09 13:41:22.226  2569  2761 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-09 13:41:22.226  2970  2970 I WCNSS_FILTER: do_write: IBS write: fc
09-09 13:41:22.226  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-09 13:41:22.226  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
09-09 13:41:22.226  1259  2621 V AlarmManager:  remove PendingIntent] PendingIntent{27faaff: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:22.226  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-09 13:41:22.226  2569  2739 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
09-09 13:41:22.226  2569  2746 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:41:22.226  1259  3546 D SSRM:s  : SIOP:: AP = 350, PST = 378 (W:12), CP = 41, LCD = 0
09-09 13:41:22.226  1259  3546 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-09 13:41:22.236  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 38 : bytes_written: 38
09-09 13:41:22.236  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-09 13:41:22.236  1259  2304 V AlarmManager:  remove PendingIntent] PendingIntent{6afb0cc: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:22.236  2569  2739 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-09 13:41:22.236  2569  2746 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-09 13:41:22.236  2569  2746 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-09 13:41:22.236  2569  2746 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
09-09 13:41:22.236  1259  2310 V AlarmManager:  remove PendingIntent] PendingIntent{a749f15: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:22.236  2569  2746 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
09-09 13:41:22.236  5955  5965 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
09-09 13:41:22.236  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-09 13:41:22.236  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 13:41:22.236  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:41:22.236  5955  5955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:41:22.236  5955  5955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-09 13:41:22.236  5955  5955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-09 13:41:22.246  1259  1721 V AlarmManager:  remove PendingIntent] PendingIntent{b5e522a: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:22.236  5955  5955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 13:41:22.236  5955  5955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-09 13:41:22.236  5955  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-09 13:41:22.246  5955  5955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-09 13:41:22.246  5955  5955 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:22.246  1259  2304 V AlarmManager:  remove PendingIntent] PendingIntent{aadf81b: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:22.506  1259  1989 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-09 13:41:22.506  1259  1989 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4390, temperature: 332, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-09 13:41:22.506  1259  1989 D BatteryService: online:4, current avg:114, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:46
,09-09 13:41:22.506  1259  1259 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 13:41:22.506  1694  1694 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-09 13:41:22.506  1694  1694 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 13:41:22.506  1694  1694 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-09 13:41:22.516  1694  1694 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-09 13:41:22.516  1694  1694 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-09 13:41:22.516  2569  2569 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-09 13:41:22.516  2569  6349 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-09 13:41:22.536  1694  1694 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-09 13:41:22.676  2103  2153 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-09 13:41:22.676  2103  2153 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-09 13:41:22.746  5955  5955 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-09 13:41:22.746  5955  5955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 13:41:22.746  5955  5955 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:41:23.236  2970  3035 I WCNSS_FILTER: do_write: IBS write: fe
09-09 13:41:23.236  2970  3035 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-09 13:41:23.746  6480  6480 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,09-09 13:41:24.126  1259  1630 D ConnectivityService: handlePromptUnvalidated 504
,09-09 13:41:25.066  1259  3576 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 13:41:25.566  6454  6454 I wpa_supplicant: nl80211: Received scan results (38 BSSes)
,09-09 13:41:25.576  1259  1622 D WifiP2pService: InactiveState{ what=147461 }
09-09 13:41:25.576  1259  1622 D WifiP2pService: P2pEnabledState{ what=147461 }
09-09 13:41:25.576  1259  1622 D WifiP2pService: DefaultState{ what=147461 }
,09-09 13:41:25.616  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d8d0db8 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8b6b662 1694:com.android.systemui/u0a46}
,09-09 13:41:25.736  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:25.736  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:41:25.736  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:41:25.736  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:41:25.736  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:41:25.736  5955  6005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:41:25.736  5955  6005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a8eab3 not in the list
09-09 13:41:25.736  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.736  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:41:25.736  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:41:25.736  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:41:25.736  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:41:25.736  5955  5955 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:41:25.746  5955  6536 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:41:25.746  5955  6536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:41:25.746  5955  6536 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:41:25.746  5955  6005 D BluetoothAdapter: STATE_ON
,09-09 13:41:25.746  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:41:25.746  5955  6005 D BluetoothLeScanner: could not find callback wrapper
09-09 13:41:25.746  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:41:25.746  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-09 13:41:25.746  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:41:25.746  5955  6005 D BluetoothAdapter: STATE_ON
09-09 13:41:25.746  5955  6005 D BluetoothLeAdvertiser: stop advertising
,09-09 13:41:25.746  2569  6379 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-09 13:41:25.746  1259  2621 V AlarmManager:  remove PendingIntent] PendingIntent{38d1791: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:25.746  2569  6379 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-09 13:41:25.746  2569  2761 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
09-09 13:41:25.746  2569  2761 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
09-09 13:41:25.746  2569  2761 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-09 13:41:25.746  2569  2761 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-09 13:41:25.746  2569  2761 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
09-09 13:41:25.746  2569  2746 D BtGatt.AdvertiseManager: message : 1
09-09 13:41:25.746  2569  2746 D BtGatt.AdvertiseManager: stop advertise for client =  6
09-09 13:41:25.746  2569  2746 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
09-09 13:41:25.746  2569  2746 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
09-09 13:41:25.746  2970  2971 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
,09-09 13:41:25.756  2970  2971 I WCNSS_FILTER: do_write: IBS write: fd
09-09 13:41:25.756  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
09-09 13:41:25.756  2970  2970 I WCNSS_FILTER: do_write: IBS write: fc
,09-09 13:41:25.756  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-09 13:41:25.766  1259  2294 V AlarmManager:  remove PendingIntent] PendingIntent{b6766f6: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:25.756  2569  2739 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-09 13:41:25.756  2569  2739 D BtGatt.GattService: Client app is not null!
09-09 13:41:25.756  5955  6348 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
09-09 13:41:25.766  2970  2971 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-09 13:41:25.766  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
09-09 13:41:25.766  2569  3085 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 13:41:25.766  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 13:41:25.766  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:41:25.766  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-09 13:41:25.766  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-09 13:41:25.766  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:41:25.766  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:25.766  5955  6005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:41:25.766  5955  6005 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:41:25.766  1259  1324 V AlarmManager:  remove PendingIntent] PendingIntent{4a9faf7: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:25.766  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:25.766  5955  6005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0a870 not in the list
09-09 13:41:25.766  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:25.766  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.766  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:25.766  5955  6005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:25.766  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.766  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.766  5955  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:25.766  5955  6005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a8eab3 not in the list
09-09 13:41:25.766  5955  6005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.766  5955  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:25.766  5955  5955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:41:25.766  5955  6005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0a870 not in the list
09-09 13:41:25.766  5955  6005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:25.766  5955  6005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.766  5955  5955 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:25.766  5955  6005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.766  5955  6005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-09 13:41:25.766  5955  6005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-09 13:41:25.766  5955  6005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-09 13:41:25.766  5955  6005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:41:25.766  5955  6005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 13:41:25.766  5955  6005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:41:25.776  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
,09-09 13:41:25.776  2970  2971 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-09 13:41:25.776  1259  1853 V AlarmManager:  remove PendingIntent] PendingIntent{8e14d64: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
09-09 13:41:25.776  5955  6539 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 321, name: My test thread name)
,09-09 13:41:25.776  2970  2970 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-09 13:41:25.776  1259  2304 V AlarmManager:  remove PendingIntent] PendingIntent{cda9bcd: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:25.786  1259  1989 V AlarmManager:  remove PendingIntent] PendingIntent{21afc82: PendingIntentRecord{c864925 com.android.bluetooth broadcastIntent}}
,09-09 13:41:26.276  5955  5955 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,09-09 13:41:26.486  5344  5344 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
09-09 13:41:26.486  5344  5344 D PreloadUpdateManagerStateMachine: exit::IDLE
09-09 13:41:26.486  5344  5344 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,09-09 13:41:26.486  5344  5344 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,09-09 13:41:26.486  5344  5344 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,09-09 13:41:26.486  5344  5344 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,09-09 13:41:26.486  5344  5344 D PreloadUpdateManagerStateMachine: entry::IDLE
,09-09 13:41:26.776  2970  3035 I WCNSS_FILTER: do_write: IBS write: fe
09-09 13:41:26.776  2970  3035 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-09 13:41:27.746  6480  6480 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-09 13:41:27.746  6480  6480 I dhcpcd  : wlan0: no IPv6 Routers available
,09-09 13:41:27.776  5955  6005 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 321
09-09 13:41:27.776  5955  6005 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 321, name: My test thread name)
,09-09 13:41:27.776  5955  6540 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 322, name: My test thread name)
09-09 13:41:27.776  5955  6540 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 322, thread name: My test thread name)
09-09 13:41:27.776  5955  6540 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 322, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-09 13:41:27.776  5955  6005 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:41:27.786  5955  6541 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 326, name: My test thread name)
09-09 13:41:27.786  5955  6541 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 326, thread name: My test thread name): Test exception.
09-09 13:41:27.786  5955  6541 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 326, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-09 13:41:27.786  5955  6005 I jxcore-log: Total number of executed tests:  82
09-09 13:41:27.786  5955  6005 I jxcore-log: 
09-09 13:41:27.786  5955  6005 I jxcore-log: Number of passed tests:  82
09-09 13:41:27.786  5955  6005 I jxcore-log: 
09-09 13:41:27.786  5955  6005 I jxcore-log: Number of failed tests:  0
09-09 13:41:27.786  5955  6005 I jxcore-log: 
09-09 13:41:27.786  5955  6005 I jxcore-log: Number of ignored tests:  0
09-09 13:41:27.786  5955  6005 I jxcore-log: 
09-09 13:41:27.786  5955  6005 I jxcore-log: Total duration:  34020
09-09 13:41:27.786  5955  6005 I jxcore-log: 
09-09 13:41:27.786  5955  6005 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-09 13:41:27.786  5955  6005 I jxcore-log: 
09-09 13:41:27.796  5955  6005 I jxcore-log: My device name is: samsung-SM-T719
09-09 13:41:27.796  5955  6005 I jxcore-log: 
,09-09 13:41:27.796  5955  6005 I jxcore-log: WARN testUtils: myNameCallback not set!
09-09 13:41:27.796  5955  6005 I jxcore-log: 
09-09 13:41:27.806  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:27.806  5955  6005 I jxcore-log: 
09-09 13:41:27.806  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:27.806  5955  6005 I jxcore-log: 
09-09 13:41:27.806  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:27.806  5955  6005 I jxcore-log: 
09-09 13:41:27.806  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:41:27.806  5955  6005 I jxcore-log: 
,09-09 13:41:27.816  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:41:27.816  5955  6005 I jxcore-log: 
,09-09 13:41:27.816  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:27.816  5955  6005 I jxcore-log: 
,09-09 13:41:27.816  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:41:27.816  5955  6005 I jxcore-log: 
,09-09 13:41:27.816  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:27.816  5955  6005 I jxcore-log: 
,09-09 13:41:27.816  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:41:27.816  5955  6005 I jxcore-log: 
09-09 13:41:27.816  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:27.816  5955  6005 I jxcore-log: 
,09-09 13:41:27.816  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:27.816  5955  6005 I jxcore-log: 
,09-09 13:41:27.816  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:27.816  5955  6005 I jxcore-log: 
,09-09 13:41:27.816  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:27.816  5955  6005 I jxcore-log: 
,09-09 13:41:27.826  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:41:27.826  5955  6005 I jxcore-log: 
,09-09 13:41:27.826  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:41:27.826  5955  6005 I jxcore-log: 
09-09 13:41:27.826  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:41:27.826  5955  6005 I jxcore-log: 
,09-09 13:41:27.826  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 13:41:27.826  5955  6005 I jxcore-log: 
,09-09 13:41:27.826  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:27.826  5955  6005 I jxcore-log: 
09-09 13:41:27.826  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:27.826  5955  6005 I jxcore-log: 
,09-09 13:41:27.826  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:27.826  5955  6005 I jxcore-log: 
,09-09 13:41:27.826  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:27.826  5955  6005 I jxcore-log: 
,09-09 13:41:27.836  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:27.836  5955  6005 I jxcore-log: 
,09-09 13:41:27.836  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:27.836  5955  6005 I jxcore-log: 
,09-09 13:41:27.836  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:27.836  5955  6005 I jxcore-log: 
,09-09 13:41:27.836  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:27.836  5955  6005 I jxcore-log: 
,09-09 13:41:27.836  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:27.836  5955  6005 I jxcore-log: 
,09-09 13:41:27.836  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:27.836  5955  6005 I jxcore-log: 
,09-09 13:41:27.836  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
09-09 13:41:27.836  5955  6005 I jxcore-log: 
09-09 13:41:27.836  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:27.836  5955  6005 I jxcore-log: 
,09-09 13:41:27.836  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:27.836  5955  6005 I jxcore-log: 
,09-09 13:41:27.836  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:27.836  5955  6005 I jxcore-log: 
,09-09 13:41:27.836  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
,09-09 13:41:27.836  5955  6005 I jxcore-log: 
,09-09 13:41:27.846  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:41:27.846  5955  6005 I jxcore-log: 
,09-09 13:41:27.846  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:41:27.846  5955  6005 I jxcore-log: 
,09-09 13:41:27.846  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:27.846  5955  6005 I jxcore-log: 
,09-09 13:41:27.846  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:27.846  5955  6005 I jxcore-log: 
,09-09 13:41:27.846  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:27.846  5955  6005 I jxcore-log: 
,09-09 13:41:27.846  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:27.846  5955  6005 I jxcore-log: 
,09-09 13:41:27.846  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:41:27.846  5955  6005 I jxcore-log: 
,09-09 13:41:27.846  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:27.846  5955  6005 I jxcore-log: 
,09-09 13:41:27.846  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:27.846  5955  6005 I jxcore-log: 
,09-09 13:41:27.846  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-09 13:41:27.846  5955  6005 I jxcore-log: 
,09-09 13:41:27.846  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-09 13:41:27.846  5955  6005 I jxcore-log: 
,09-09 13:41:27.856  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:41:27.856  5955  6005 I jxcore-log: 
,09-09 13:41:27.856  5955  6005 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 13:41:27.856  5955  6005 I jxcore-log: 
,09-09 13:41:27.956  5955  6539 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 321, name: My test thread name), during the lifetime of the thread the total number of bytes read was 198 and the total number of bytes written 198
,09-09 13:41:28.376  6542  6542 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-09 13:41:28.376  6542  6542 D AndroidRuntime: CheckJNI is OFF
,09-09 13:41:28.376  6542  6542 D AndroidRuntime: readGMSProperty: start
09-09 13:41:28.376  6542  6542 D AndroidRuntime: readGMSProperty: already setted!!
09-09 13:41:28.376  6542  6542 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-09 13:41:28.376  6542  6542 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-09 13:41:28.376  6542  6542 D AndroidRuntime: readGMSProperty: end
09-09 13:41:28.376  6542  6542 D AndroidRuntime: addProductProperty: start
,09-09 13:41:28.406  6542  6542 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-09 13:41:28.436  6542  6542 I Radio-JNI: register_android_hardware_Radio DONE
,09-09 13:41:28.446  6542  6542 E AffinityControl: AffinityControl: registerfunction enter
,09-09 13:41:28.466  6542  6542 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-09 13:41:28.476  1259  2629 D PackageManager: START PACKAGE DELETE: observer{186112976}
09-09 13:41:28.476  1259  2629 D PackageManager: pkg{<packageName>}
09-09 13:41:28.476  1259  2629 D PackageManager: user{0}
09-09 13:41:28.476  1259  2629 D PackageManager: caller{2000}
09-09 13:41:28.476  1259  2629 D PackageManager: flags{2}
09-09 13:41:28.476  1259  2629 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-09 13:41:28.476  1259  2629 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-09 13:41:28.476  1259  2629 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-09 13:41:28.476  1259  2629 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-09 13:41:28.476  1259  2629 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-09 13:41:28.476  1259  1425 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-09 13:41:28.476  1259  1425 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-09 13:41:28.476  1259  1425 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-09 13:41:28.476  1259  1425 D ApplicationPolicy: getApplicationUninstallationEnabled
09-09 13:41:28.476  1259  1425 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
09-09 13:41:28.476  1259  1425 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-09 13:41:28.476  1259  1425 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,09-09 13:41:28.476  1259  1425 D PackageManager: !@killApplicatoin: 10136, uninstall pkg
,09-09 13:41:28.476  1259  1425 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-09 13:41:28.476  1259  1385 I ActivityManager: Force stopping com.test.thalitest appid=10136 user=-1: uninstall pkg
09-09 13:41:28.476  1259  1425 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
09-09 13:41:28.476  1259  1385 I ActivityManager: Killing 5955:com.test.thalitest/u0a136 (adj 1): stop com.test.thalitest cause uninstall pkg
09-09 13:41:28.476  1259  1385 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5955 ,hash=92434530 ,name=com.test.thalitest
09-09 13:41:28.486  1259  1385 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-09 13:41:28.496  1259  1425 D AASAinstall: there is not AASApackages.xml file
,09-09 13:41:28.506  6551  6551 E Zygote  : v2
09-09 13:41:28.506  6551  6551 I libpersona: KNOX_SDCARD checking this for 10136
09-09 13:41:28.506  6551  6551 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:28.506  6551  6551 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-09 13:41:28.506  6551  6551 E Zygote  : accessInfo : 0
09-09 13:41:28.506  1259  1385 I ActivityManager: Start proc 6551:com.test.thalitest/u0a136 for activity com.test.thalitest/.MainActivity
09-09 13:41:28.506  6551  6551 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-09 13:41:28.506  1259  1385 I ActivityManager:   Force finishing activity ActivityRecord{5f14bb9 u0 com.test.thalitest/.MainActivity t18}
09-09 13:41:28.506  1259  1385 W VirtualScreenManagerService: moveTaskBackToDisplayIfNeeded(): top activity or app is null
09-09 13:41:28.506   443   466 I SurfaceFlinger: id=17 Removed NainActivit (6/13)
,09-09 13:41:28.506   443   464 I SurfaceFlinger: id=17 Removed NainActivit (-2/13)
,09-09 13:41:28.546  6551  6551 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:41:28.546  6551  6551 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:28.606  1259  2310 D GraphicsStats: Buffer count: 5
,09-09 13:41:28.606   443   464 E         : BitTube(): close sendFd (41)
09-09 13:41:28.606   443   464 E         : BitTube(): close sendFd (42)
09-09 13:41:28.606  1259  1853 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@4805ece)
,09-09 13:41:28.606  1259  1630 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:28.606  1259  1630 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 13:41:28.606  1259  1630 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 13:41:28.786  1259  1425 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,09-09 13:41:28.886  1259  1425 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
09-09 13:41:28.886  1259  1637 I ActivityManager: Killing 5889:com.samsung.android.app.filterinstaller/1000 (adj 15): DHA:empty #31
,09-09 13:41:28.886   567   567 W keystore: ENTER clear_uid from uid 1000 for 10136
,09-09 13:41:28.896  1259  1425 I art     : Starting a blocking GC Explicit
,09-09 13:41:28.906  6551  6551 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
09-09 13:41:28.906  6551  6551 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
09-09 13:41:28.906  6551  6551 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
09-09 13:41:28.906  6551  6551 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
,09-09 13:41:28.916  6551  6551 D AndroidRuntime: Shutting down VM
,09-09 13:41:28.926  6551  6551 E AndroidRuntime: FATAL EXCEPTION: main
09-09 13:41:28.926  6551  6551 E AndroidRuntime: Process: com.test.thalitest, PID: 6551
09-09 13:41:28.926  6551  6551 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
09-09 13:41:28.926  6551  6551 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:676)
09-09 13:41:28.926  6551  6551 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6296)
09-09 13:41:28.926  6551  6551 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:223)
09-09 13:41:28.926  6551  6551 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1863)
09-09 13:41:28.926  6551  6551 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:28.926  6551  6551 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
09-09 13:41:28.926  6551  6551 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7231)
09-09 13:41:28.926  6551  6551 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:28.926  6551  6551 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
09-09 13:41:28.926  6551  6551 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
09-09 13:41:28.926  6551  6551 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
09-09 13:41:28.926  6551  6551 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:485)
09-09 13:41:28.926  6551  6551 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:661)
09-09 13:41:28.926  6551  6551 E AndroidRuntime: 	... 9 more
,09-09 13:41:28.926  6551  6551 I Process : Sending signal. PID: 6551 SIG: 9
,09-09 13:41:28.946  6564  6564 E Zygote  : v2
09-09 13:41:28.946  6564  6564 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:41:28.946  6564  6564 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:28.946  6564  6564 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-09 13:41:28.946  1259  1385 I ActivityManager: Start proc 6564:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
09-09 13:41:28.946  6564  6564 E Zygote  : accessInfo : 0
,09-09 13:41:28.956  1259  1853 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5889 ,hash=127008149 ,name=com.samsung.android.app.filterinstaller
09-09 13:41:28.956  1259  1853 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.filterinstaller, Auto Run ON
,09-09 13:41:28.966  6564  6564 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:41:28.966  6564  6564 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:28.976  1259  2294 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fe6e4fc u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8df51ef 6564:com.samsung.android.sm/1000}
,09-09 13:41:29.006  6564  6564 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1311 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.samsung.android.sm.common.SmartManagerReceiver.b:259 com.samsung.android.sm.common.SmartManagerReceiver.onReceive:107 
,09-09 13:41:29.026  1259  2304 I ActivityManager: Killing 5904:com.sec.android.widgetapp.samsungapps/u0a78 (adj 15): DHA:empty #31
,09-09 13:41:29.066  1259  1987 I ActivityManager: Process com.test.thalitest (pid 6551)(adj 9) has died(153,1514)
,09-09 13:41:29.066  1259  1987 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=6551 ,hash=16918473 ,name=com.test.thalitest
09-09 13:41:29.066  1259  1987 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-09 13:41:29.066  1259  1987 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.android.server.am.ActivityManagerService.updateOomAdjLocked:26615 com.android.server.am.ActivityManagerService.appDiedLocked:7605 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1888 android.os.BinderProxy.sendDeathNotice:558 
,09-09 13:41:29.086  1259  1721 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5904 ,hash=178949802 ,name=com.sec.android.widgetapp.samsungapps
09-09 13:41:29.086  1259  1721 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.samsungapps, Auto Run ON
,09-09 13:41:29.126  1259  1425 I art     : Explicit concurrent mark sweep GC freed 289816(18MB) AllocSpace objects, 38(2MB) LOS objects, 33% free, 29MB/44MB, paused 3.447ms total 230.470ms
,09-09 13:41:29.146  1259  1425 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-09 13:41:29.146  1259  1425 D AASAuninstall: userId = 0, info.removedAppID = 10136, info.uid = 10136, packageName = com.test.thalitest
,09-09 13:41:29.146  1259  1425 D AASAinstall: there is not AASApackages.xml file
09-09 13:41:29.146  1259  1425 D PackageManager: result of delete: 1{186112976}
,09-09 13:41:29.146  1259  1425 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-09 13:41:29.146  1259  1425 D PackageManager: userId{-1}
09-09 13:41:29.146  1259  1425 D PackageManager: andCode{true}
,09-09 13:41:29.146  6542  6542 I art     : System.exit called, status: 0
09-09 13:41:29.146  6542  6542 I AndroidRuntime: VM exiting with result code 0.
,09-09 13:41:29.166  6578  6578 E Zygote  : v2
09-09 13:41:29.166  6578  6578 I libpersona: KNOX_SDCARD checking this for 10006
09-09 13:41:29.166  6578  6578 I libpersona: KNOX_SDCARD not a persona
09-09 13:41:29.166  6578  6578 E libpersona: scanKnoxPersonas
09-09 13:41:29.166  6578  6578 E libpersona: Couldn't open the File - /data/system/users/0/personalist.xml - No such file or directory
,09-09 13:41:29.166  6578  6578 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-09 13:41:29.166  1259  1425 I ActivityManager: Start proc 6578:com.android.defcontainer/u0a6 for service com.android.defcontainer/.DefaultContainerService
,09-09 13:41:29.166  1259  1425 I ActivityManager: Force stopping com.test.thalitest appid=10136 user=0: pkg removed
09-09 13:41:29.166  6578  6578 E Zygote  : accessInfo : 0
09-09 13:41:29.166  6578  6578 E libpersona: scanKnoxPersonas
09-09 13:41:29.166  6578  6578 E libpersona: Couldn't open the File - /data/system/users/0/personalist.xml - No such file or directory
,09-09 13:41:29.196  1694  1694 D ShortcutManager: onReceive : android.intent.action.PACKAGE_REMOVED
09-09 13:41:29.196  1694  1694 D ShortcutManager: onReceive : Intent.EXTRA_REPLACING false,com.test.thalitest
,09-09 13:41:29.196  1694  1694 D CoverUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
,09-09 13:41:29.206  1868  2384 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-09 13:41:29.216  1259  1592 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-09 13:41:29.226  6578  6578 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:41:29.226  1259  1385 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b29b271 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fb388ec 3898:com.samsung.klmsagent/u0a16}
09-09 13:41:29.226  6578  6578 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:29.226  1792  1792 I Recents_MultiWindowAppListInfo: android.intent.action.PACKAGE_REMOVE
,09-09 13:41:29.226  3898  3898 I KLMS-2.6.094: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } | timestamp: Fri Sep 09 13:41:29 GMT+02:00 2016
,09-09 13:41:29.226  1974  1974 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-09 13:41:29.236  1259  1620 V NetworkStats: removeUidsLocked() for UIDs [10136]
09-09 13:41:29.236  1259  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:29.236  1259  1620 V NetworkStats: performPollLocked(flags=0x3)
,09-09 13:41:29.236  1259  1378 D EnterpriseDeviceManagerService: Package has changed for user 0
09-09 13:41:29.236  1259  1378 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,09-09 13:41:29.236  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:29.236  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:29.236  1259  1620 D NetworkStatsRecorder: entry.iface is null
09-09 13:41:29.236  1259  1620 D NetworkStatsRecorder: entry.iface is null
,09-09 13:41:29.236  1259  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:29.236  1259  1620 V NetworkStats: performPollLocked() took 4ms
,09-09 13:41:29.236  1259  1324 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=2464, uid=10093 that is not exported from uid 10091
,09-09 13:41:29.256  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:29.256  1259  1621 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:29.256  3898  3898 I KLMS-2.6.094: : KLMSAbstractReciever(): onReceive().END.
,09-09 13:41:29.256  3898  3898 I KLMS-2.6.094: : KLMSIntentService(): onCreate()
,09-09 13:41:29.256  3898  3898 I KLMS-2.6.094: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-09 13:41:29.256  1259  2310 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b29b271 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a8d25ef 1259:system/1000}
,09-09 13:41:29.266  3898  3898 I KLMS-2.6.094: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-09 13:41:29.266  3898  6593 I KLMS-2.6.094: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-09 13:41:29.266  3898  6593 D KLMS-2.6.094: : KLMSIntentService(): PACKAGE_REMOVED
09-09 13:41:29.266  3898  6593 I KLMS-2.6.094: : Systemprocess(): listeningToPackageRemoved().START
09-09 13:41:29.266  3898  6593 I KLMS-2.6.094: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
09-09 13:41:29.266  3898  6593 I KLMS-2.6.094: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
09-09 13:41:29.266  3898  6593 I KLMS-2.6.094: : MDMBridge(): getAllLicenseInfoFromSDK()
,09-09 13:41:29.266  3898  6593 I KLMS-2.6.094: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-09 13:41:29.266  3898  6593 I KLMS-2.6.094: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-09 13:41:29.276  3898  6593 I KLMS-2.6.094: : MDMBridge(): getAllLicenseInfoFromSDK()
,09-09 13:41:29.276  3898  6593 D KLMS-2.6.094: : Systemprocess(): arrayLicenseInfo is null
,09-09 13:41:29.286  6578  6594 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,09-09 13:41:29.286  6578  6594 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
09-09 13:41:29.286  3898  6593 D KLMS-2.6.094: : DataSource(): Fetched Data from data base count : 0
,09-09 13:41:29.286  1259  2310 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
09-09 13:41:29.286  1259  2310 D SettingsProvider: isChangeAllowed() : name = klm_eula_shown
09-09 13:41:29.286  6578  6594 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
09-09 13:41:29.286  1259  2310 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 13:41:29.286  1259  2310 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 13:41:29.286  1259  2310 D SettingsProvider: selectionArgs: false
09-09 13:41:29.286  1259  2310 D SettingsProvider: selectionArgs: 10016
,09-09 13:41:29.296  1259  2310 D SettingsProvider: ret = -1
09-09 13:41:29.296  1259  1259 V AlarmManager: Remove alarm for next reason : android.intent.action.PACKAGE_REMOVED : package: com.test.thalitest
,09-09 13:41:29.296  1259  1259 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
09-09 13:41:29.296  1259  1259 D UniversalCredentialManagerService: inside mPkgReciever onReceive : android.intent.action.PACKAGE_REMOVED
09-09 13:41:29.296  1259  1259 D UniversalCredentialManagerService: ACTION_PACKAGE_REMOVED is called....
09-09 13:41:29.296  1259  1259 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-09 13:41:29.296  1259  1259 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-09 13:41:29.296  1259  1259 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10136 container id = 0
09-09 13:41:29.296  1259  1259 I OTPFW   : ProvisionData::getAllEntries Enter
,09-09 13:41:29.296  1259  1259 E OTPFW   : ProvisionData::getAllEntries Table is empty
09-09 13:41:29.296  1259  1259 E SDAgentPackageStateReceiver: Not going to handle 'com.test.thalitest'!
,09-09 13:41:29.296  1259  1259 D UcmService: onReceive android.intent.action.PACKAGE_REMOVED
09-09 13:41:29.296  1259  1259 D UcmService: Package update in userId-0 and uid-10136
,09-09 13:41:29.296  1259  1259 D GameManager.DatabaseHelper: removeGame(), packageName: com.test.thalitest, ret: 0
09-09 13:41:29.296  1259  1259 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-09 13:41:29.296  1259  1259 V EnterpriseBillingAsyncHandler: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-09 13:41:29.296  1259  1655 V EnterpriseBillingPolicyInternal: packageModification -  start - android.intent.action.PACKAGE_REMOVED
09-09 13:41:29.296  1259  1655 V EnterpriseBillingPolicyInternal: uID is 10136
09-09 13:41:29.296  1259  1655 V EnterpriseBillingPolicyInternal: Removed Packageuid is0
09-09 13:41:29.296  1259  1655 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-09 13:41:29.306  1259  1655 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-09 13:41:29.306  1259  1655 V EnterpriseBillingPolicyInternal: packageModificationReceiver - onreceive - personal application - profile null
,09-09 13:41:29.306  1259  1259 D SdpManagerService:  ActionReceiver::onReceive() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-09 13:41:29.306  1259  1259 D SdpManagerService: ACTION_PACKAGE_REMOVED Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } DATA= package:com.test.thalitest UID 1000 userId 0
09-09 13:41:29.306  1259  1259 D SdpManagerService: ACTION_PACKAGE_REMOVED packageName:: com.test.thalitest
09-09 13:41:29.306  1259  1259 D EnterprisePartitionManager: SND -> {secure_fs remove_enc_dir}
,09-09 13:41:29.306   383   437 D epmd    : Partition obj created
09-09 13:41:29.306   383   437 D epmd    : Partition::dump============== 0
09-09 13:41:29.306   383   437 D epmd    : Partition::mType > INTERNAL-SDCARD mSrcPath > /data/knox/secure_fs/enc_user mMntPath > /data/enc_user
09-09 13:41:29.306   383   437 D epmd    : Partition::SDP > not supported
,09-09 13:41:29.306   383   437 E epmd    : removeEncPkgDir ERROR
09-09 13:41:29.306   383   437 D epmd    : deleting Partition object.
09-09 13:41:29.306  1259  1427 D EnterprisePartitionManager: RCV <-
09-09 13:41:29.306   383   437 W FrameworkListener: Handler 'secure_fs' error (No such file or directory)
09-09 13:41:29.306  1259  1259 D EnterprisePartitionManager: RMV <-
09-09 13:41:29.306  1259  1259 D EnterprisePartitionManager: event : 281 3 remove_enc_dir failed
,09-09 13:41:29.306  1259  1259 D SdpManagerService: start document   : 
09-09 13:41:29.306  1259  1259 D SdpManagerService: start element    : engine_list
09-09 13:41:29.316  1259  1259 D SdpManagerService: start characters : 
09-09 13:41:29.316  1259  1259 D SdpManagerService: start element    : engine
09-09 13:41:29.316  1259  1259 D SdpManagerService:  attribte alias: android_0
09-09 13:41:29.316  1259  1259 D SdpManagerService:  attribte id: 0
09-09 13:41:29.316  1259  1259 D SdpManagerService: end element      : engine
09-09 13:41:29.316  1259  1259 D SdpManagerService: start characters : 
09-09 13:41:29.316  1259  1259 D SdpManagerService: end element      : engine_list
09-09 13:41:29.316  1259  1259 D SdpManagerService: end document     : 
09-09 13:41:29.316  1259  1259 W System.err: mkdir failed: EEXIST (File exists) : /data/system/users/0
09-09 13:41:29.316  1259  1259 E SdpManagerService: cant make directory /data/system/users/0
09-09 13:41:29.316  1259  1259 D SdpManagerService: start document   : 
09-09 13:41:29.316  1259  1259 D SdpManagerService: start element    : user
09-09 13:41:29.316  1259  1259 D SdpManagerService: end element      : user
09-09 13:41:29.316  1259  1259 D SdpUtil : num:0 index-0
09-09 13:41:29.316  1259  1259 D SdpUtil : detecected userId : 0
09-09 13:41:29.316  1259  1259 D SdpManagerService: end document     : 
09-09 13:41:29.316  1259  1259 E SdpManagerService: Can't find engine info [android_0]
09-09 13:41:29.316  1259  1259 V EnterpriseBillingAsyncHandler: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-09 13:41:29.316  1259  3546 D SSRM:bb : MSG_TYPE_APP_REMOVED::
09-09 13:41:29.316  1259  1655 V EnterpriseBillingPolicyInternal: packageModification -  start - android.intent.action.PACKAGE_FULLY_REMOVED
09-09 13:41:29.316  1259  1655 V EnterpriseBillingPolicyInternal: uID is 10136
09-09 13:41:29.316  1259  1655 V EnterpriseBillingPolicyInternal: Removed Packageuid is0
09-09 13:41:29.316  1259  1655 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-09 13:41:29.316  1259  1259 D AccessibilityManagerService: checkUniversalSwitchState start:
09-09 13:41:29.316  1259  1655 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-09 13:41:29.316  1259  1655 V EnterpriseBillingPolicyInternal: packageModificationReceiver - onreceive - personal application - profile null
,09-09 13:41:29.326  5754  6350 E SQLiteLog: (10) unixWrite() File Descriptor : 20 gets errno : 30
,09-09 13:41:29.326  5754  6350 E DatabaseUtils: Writing exception to parcel
09-09 13:41:29.326  5754  6350 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
09-09 13:41:29.326  5754  6350 E DatabaseUtils: #################################################################
09-09 13:41:29.326  5754  6350 E DatabaseUtils: Error Code : 778 (SQLITE_IOERR_WRITE)
09-09 13:41:29.326  5754  6350 E DatabaseUtils: Caused By : Disk I/O error occurred during 'write' operation.
09-09 13:41:29.326  5754  6350 E DatabaseUtils: 	(disk I/O error (code 778))
09-09 13:41:29.326  5754  6350 E DatabaseUtils: #################################################################
09-09 13:41:29.326  5754  6350 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 13:41:29.326  5754  6350 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:866)
09-09 13:41:29.326  5754  6350 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 13:41:29.326  5754  6350 E DatabaseUtils: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 13:41:29.326  5754  6350 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
09-09 13:41:29.326  5754  6350 E DatabaseUtils: 	at com.samsung.android.sm.database.SmProvider.delete(SmProvider.java:826)
09-09 13:41:29.326  5754  6350 E DatabaseUtils: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:352)
09-09 13:41:29.326  5754  6350 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:206)
09-09 13:41:29.326  5754  6350 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:453)
,09-09 13:41:29.326  1259  1415 E MARsDBManager: Exception with contentResolver : disk I/O error (code 778)
09-09 13:41:29.326  1259  1415 E MARsDBManager: #################################################################
09-09 13:41:29.326  1259  1415 E MARsDBManager: Error Code : 778 (SQLITE_IOERR_WRITE)
09-09 13:41:29.326  1259  1415 E MARsDBManager: Caused By : Disk I/O error occurred during 'write' operation.
09-09 13:41:29.326  1259  1415 E MARsDBManager: 	(disk I/O error (code 778))
09-09 13:41:29.326  1259  1415 E MARsDBManager: #################################################################
09-09 13:41:29.326  1259  1415 E MARsDBManager: #################################################################
09-09 13:41:29.326  1259  1415 E MARsDBManager: Error Code : 778 (SQLITE_IOERR_WRITE)
09-09 13:41:29.326  1259  1415 E MARsDBManager: Caused By : Disk I/O error occurred during 'write' operation.
09-09 13:41:29.326  1259  1415 E MARsDBManager: 	(disk I/O error (code 778)
09-09 13:41:29.326  1259  1415 E MARsDBManager: #################################################################
09-09 13:41:29.326  1259  1415 E MARsDBManager: Error Code : 778 (SQLITE_IOERR_WRITE)
09-09 13:41:29.326  1259  1415 E MARsDBManager: Caused By : Disk I/O error occurred during 'write' operation.
09-09 13:41:29.326  1259  1415 E MARsDBManager: 	(disk I/O error (code 778))
09-09 13:41:29.326  1259  1415 E MARsDBManager: #################################################################)
09-09 13:41:29.326  1259  1415 E MARsDBManager: #################################################################
,09-09 13:41:29.346  1259  1378 D UsbSettingsManager: clearDefaults: com.test.thalitest,
09-09 13:41:29.346  1995  1995 E Launcher.Model: onPackageRemoved :com.test.thalitest
,09-09 13:41:29.346  1995  2125 E SQLiteLog: (10) unixWrite() File Descriptor : 20 gets errno : 30
,09-09 13:41:29.346  1995  2125 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-09 13:41:29.346  1995  2125 E AndroidRuntime: Process: com.sec.android.app.launcher, PID: 1995
09-09 13:41:29.346  1995  2125 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
09-09 13:41:29.346  1995  2125 E AndroidRuntime: #################################################################
09-09 13:41:29.346  1995  2125 E AndroidRuntime: Error Code : 778 (SQLITE_IOERR_WRITE)
09-09 13:41:29.346  1995  2125 E AndroidRuntime: Caused By : Disk I/O error occurred during 'write' operation.
09-09 13:41:29.346  1995  2125 E AndroidRuntime: 	(disk I/O error (code 778))
09-09 13:41:29.346  1995  2125 E AndroidRuntime: #################################################################
09-09 13:41:29.346  1995  2125 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-09 13:41:29.346  1995  2125 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:679)
09-09 13:41:29.346  1995  2125 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-09 13:41:29.346  1995  2125 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-09 13:41:29.346  1995  2125 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:527)
09-09 13:41:29.346  1995  2125 E AndroidRuntime: 	at com.android.launcher2.LauncherProvider.updateAppItems(LauncherProvider.java:539)
09-09 13:41:29.346  1995  2125 E AndroidRuntime: 	at com.android.launcher2.LauncherModel$6.run(LauncherModel.java:845)
09-09 13:41:29.346  1995  2125 E AndroidRuntime: 	at com.android.launcher2.LauncherModel.updateAppItems(LauncherModel.java:849)
09-09 13:41:29.346  1995  2125 E AndroidRuntime: 	at com.android.launcher2.MenuAppLoader.removePackage(MenuAppLoader.java:891)
09-09 13:41:29.346  1995  2125 E AndroidRuntime: 	at com.android.launcher2.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3788)
09-09 13:41:29.346  1995  2125 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:41:29.346  1995  2125 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:41:29.346  1995  2125 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
09-09 13:41:29.346  1995  2125 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
