#### Test 82642184cbac892_thali05_samsung-SM-T719 Logs


```
--------- beginning of system
08-30 02:45:36.110  1158  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,--------- beginning of main
08-30 02:45:37.180  5943  5943 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 02:45:37.180  5943  5943 D AndroidRuntime: CheckJNI is OFF
08-30 02:45:37.180  5943  5943 D AndroidRuntime: readGMSProperty: start
08-30 02:45:37.180  5943  5943 D AndroidRuntime: readGMSProperty: already setted!!
08-30 02:45:37.180  5943  5943 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 02:45:37.180  5943  5943 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 02:45:37.180  5943  5943 D AndroidRuntime: readGMSProperty: end
08-30 02:45:37.180  5943  5943 D AndroidRuntime: addProductProperty: start
08-30 02:45:37.210  5943  5943 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 02:45:37.250  5943  5943 I Radio-JNI: register_android_hardware_Radio DONE
08-30 02:45:37.260  5943  5943 E AffinityControl: AffinityControl: registerfunction enter
08-30 02:45:37.280  5943  5943 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 02:45:37.320  1158  1200 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
08-30 02:45:37.340  1158  1200 D GameManagerService: identifyGamePackage. com.test.thalitest
08-30 02:45:37.340  1158  1200 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
08-30 02:45:37.360  1158  1200 D ActivityManager: mDVFSHelper.acquire()
08-30 02:45:37.360   444   444 I SurfaceFlinger: id=14 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-30 02:45:37.360   444   444 I SurfaceFlinger: id=15 createSurf (16x16),-1 flag=20004, EimLayer(An
08-30 02:45:37.360  1158  1158 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-30 02:45:37.360  1158  1158 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-30 02:45:37.370  1702  1702 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-30 02:45:37.370  1702  1702 D WallpaperService: MSG_WINDOW_RESIZED
08-30 02:45:37.370  1158  1200 D FocusedStackFrame: Set to : 0
08-30 02:45:37.370  1702  1702 D WallpaperService: updateSurface
08-30 02:45:37.370  1702  1702 V WallpaperService: Changes: creating=false format=false size=false
08-30 02:45:37.370  1702  1702 V WallpaperService: mWidth:2048 SurfaceWidth:2048 mHeight:2048 SurfaceHeigh:2048
08-30 02:45:37.370  1702  1702 D WallpaperService: relayout
08-30 02:45:37.370  1158  1200 V WindowManager: addAppToken: AppWindowToken{d04b3bd75 token=Token{5d8ccac ActivityRecord{f2e4a5f u0 com.test.thalitest/.MainActivity t18}}} to stack=2 task=18 at 0
08-30 02:45:37.370  1702  1702 V WallpaperService: Wallpaper size has changed: (2048, 2048)
08-30 02:45:37.380  1158  1394 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{353262d V.E...... R.....ID 0,0-0,0}
08-30 02:45:37.380  1158  1394 D SecWifiDisplayUtil: Metadata value : SecSettings2
08-30 02:45:37.390  5952  5952 E Zygote  : v2
08-30 02:45:37.390  5952  5952 I libpersona: KNOX_SDCARD checking this for 10136
08-30 02:45:37.390  5952  5952 I libpersona: KNOX_SDCARD not a persona
08-30 02:45:37.390  5952  5952 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-30 02:45:37.390   444   444 I SurfaceFlinger: id=16 createSurf (1536x2048),1 flag=404, uhalitest
08-30 02:45:37.390  1158  1200 I ActivityManager: Start proc 5952:com.test.thalitest/u0a136 for activity com.test.thalitest/.MainActivity
08-30 02:45:37.390  5952  5952 E Zygote  : accessInfo : 0
08-30 02:45:37.390  5952  5952 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-30 02:45:37.390  1158  1200 D InputDispatcher: Focused application set to: xxxx
08-30 02:45:37.400  1158  1394 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 48 - 0, 0) vi=Rect(0, 48 - 0, 0) or=1
08-30 02:45:37.400  5943  5943 D AndroidRuntime: Shutting down VM
08-30 02:45:37.400  1158  1619 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-30 02:45:37.420  5952  5952 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 02:45:37.420  5952  5952 D ActivityThread: Added TimaKeyStore provider
08-30 02:45:37.420  1158  2287 D ActivityManager:  Launching com.test.thalitest, updated priority
08-30 02:45:37.430  1158  1158 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
08-30 02:45:37.430  1158  1358 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-30 02:45:37.440  1158  1394 V WindowStateAnimator: Finishing drawing window Window{867d0f3 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-30 02:45:37.460   444   470 I SurfaceFlinger: id=9 Removed MauncherAct (5/12)
08-30 02:45:37.460   444  1994 I SurfaceFlinger: id=9 Removed MauncherAct (-2/12)
08-30 02:45:37.470  1986  1986 V ActivityThread: updateVisibility : ActivityRecord{9bc936b token=android.os.BinderProxy@d9ee16 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
08-30 02:45:37.470  1986  1986 D Launcher: onTrimMemory. Level: 20
,08-30 02:45:37.750  1158  2287 I WindowManager: Screenshot max retries 4 of Token{5d8ccac ActivityRecord{f2e4a5f u0 com.test.thalitest/.MainActivity t18}} appWin=Window{867d0f3 u0 d0 Starting com.test.thalitest} drawState=4
,08-30 02:45:37.750  1158  1619 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-30 02:45:37.770  1158  3553 D GameManagerService: identifyGamePackage. com.test.thalitest
,08-30 02:45:37.770  1158  3553 D GameManagerService: identifyGamePackage. com.test.thalitest
,08-30 02:45:37.790  1158  2287 W ActivityManager: Permission Denial: getCurrentUser() from pid=5952, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
,08-30 02:45:37.800  5952  5952 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-30 02:45:37.800  5952  5952 D RelationGraph: garbageCollect()
,08-30 02:45:37.820  1158  1722 W ActivityManager: Permission Denial: getCurrentUser() from pid=5952, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
,08-30 02:45:37.820  5952  5952 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
,08-30 02:45:37.850  5952  5952 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-30 02:45:37.870  5952  5952 I cr_LibraryLoader: Time to load native libraries: 10 ms (timestamps 3029-3039)
,08-30 02:45:37.880  5952  5952 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
,08-30 02:45:37.900  5952  5966 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-30 02:45:37.900  5952  5952 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6862a7}
,08-30 02:45:37.900  5952  5952 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
,08-30 02:45:37.910  5952  5952 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 02:45:37.930  5952  5952 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-30 02:45:38.000  5952  5952 I Adreno  : QUALCOMM build                   : 971aff5, Ic07f1cdce3
08-30 02:45:38.000  5952  5952 I Adreno  : Build Date                       : 03/29/16
08-30 02:45:38.000  5952  5952 I Adreno  : OpenGL ES Shader Compiler Version: XE031.06.00.02
08-30 02:45:38.000  5952  5952 I Adreno  : Local Branch                     : 
08-30 02:45:38.000  5952  5952 I Adreno  : Remote Branch                    : refs/tags/AU_LINUX_ANDROID_LA.BR.1.3.3.C2.06.00.01.205.077
08-30 02:45:38.000  5952  5952 I Adreno  : Remote Branch                    : NONE
08-30 02:45:38.000  5952  5952 I Adreno  : Reconstruct Branch               : NOTHING
,08-30 02:45:38.060  1158  1722 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10136
,08-30 02:45:38.060  1158  1722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:851 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29617 com.android.server.am.ActivityManagerService.registerReceiver:22639 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3995 
,08-30 02:45:38.120  5952  5952 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-30 02:45:38.130  5952  5952 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 02:45:38.140  5952  5952 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-30 02:45:38.150  5952  5952 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-30 02:45:38.190  5952  5952 D SecWifiDisplayUtil: Metadata value : SecSettings2
,08-30 02:45:38.200  5952  5952 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{afacbb4 I.E...... R.....ID 0,0-0,0}
,08-30 02:45:38.200  5952  5990 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 02:45:38.210  1158  2164 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-30 02:45:38.210  1158  2164 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-30 02:45:38.210  1158  1158 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-30 02:45:38.210  1158  1158 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-30 02:45:38.220  5952  5966 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-30 02:45:38.230  5952  5952 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10136, CallingPid : 5952
,08-30 02:45:38.230  1158  1200 D ConnectivityService: listenForNetwork for Listen from uid/pid:10136/5952 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 02:45:38.230  1158  1628 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
08-30 02:45:38.230  1158  1628 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,fe80::4678:3eff:feeb:95ef/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-30 02:45:38.230  1158  1628 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-30 02:45:38.230  1158  1628 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-30 02:45:38.230  1158  1628 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-30 02:45:38.230  1158  1628 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-30 02:45:38.230  1158  1628 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-30 02:45:38.230  1158  1628 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,08-30 02:45:38.230  1158  1628 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 02:45:38.240  5952  5952 D SecWifiDisplayUtil: Metadata value : SecSettings2
,08-30 02:45:38.250   444   444 I SurfaceFlinger: id=17 createSurf (1x1),1 flag=404, NainActivit
,08-30 02:45:38.270  5952  5990 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 02:45:38.280  5952  5952 V ActivityThread: updateVisibility : ActivityRecord{de2b97f token=android.os.BinderProxy@7b8239a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-30 02:45:38.290  5952  5952 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 48 - 0, 0) vi=Rect(0, 48 - 0, 0) or=1
,08-30 02:45:38.320  5952  5990 E libGLESv2: HWUI Protection: wrong call from hwui context F: ES3-glCreateProgramSEC
,08-30 02:45:38.350  1158  1979 V WindowStateAnimator: Finishing drawing window Window{2964810 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-30 02:45:38.360  5952  5952 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@7b8239a time:93522
,08-30 02:45:38.360  1158  1394 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-30 02:45:38.360  1158  1158 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-30 02:45:38.360  1158  1394 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +615ms (total +991ms)
,08-30 02:45:38.360  1158  1158 I KnoxTimeoutHandler: SD activityfalse
08-30 02:45:38.360  1158  1158 I KnoxTimeoutHandler: Fullscreen and mCurrent is not KNOX user. Hence hide keyguard
08-30 02:45:38.360  1158  1394 D ActivityManager: mDVFSHelper.release()
08-30 02:45:38.360  1158  1394 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{f2e4a5f u0 com.test.thalitest/.MainActivity t18} time:93528
08-30 02:45:38.360  1158  1394 D ViewRootImpl: #3 mView = null
08-30 02:45:38.360   444  2797 I SurfaceFlinger: id=16 Removed uhalitest (6/12)
08-30 02:45:38.360   444   473 I SurfaceFlinger: id=16 Removed uhalitest (-2/12)
,08-30 02:45:38.370  5952  5995 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 02:45:38.420  5952  5952 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5952
,08-30 02:45:38.620  5952  5952 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 02:45:38.750  5952  6001 D jxcore_app_log: JniHelper::setJavaVM(0xf497c000), pthread_self() = -633079504
,08-30 02:45:38.750  5952  6001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 02:45:38.750  5952  6001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 02:45:38.750  5952  6001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 02:45:38.750  5952  6001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 02:45:38.750  5952  6001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 02:45:38.750  5952  6001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c289e4 added. We now have 1 listener(s)
,08-30 02:45:38.760  5952  6001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:EB:95:EE
08-30 02:45:38.760  5952  6001 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:EB:95:EE"
,08-30 02:45:38.760  5952  6001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 02:45:38.760  5952  6001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 02:45:38.760  5952  6001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 02:45:38.760  5952  6001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 02:45:38.760  5952  6001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 02:45:38.760  5952  6001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:78:3E:EB:95:EE
08-30 02:45:38.760  5952  6001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 02:45:38.760  5952  6001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 02:45:38.760  5952  6001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 02:45:38.760  5952  6001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 02:45:38.760  5952  6001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 02:45:38.760  5952  6001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 02:45:38.760  5952  6001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 02:45:38.760  5952  6001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 02:45:38.760  5952  6001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 02:45:38.760  5952  6001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 02:45:38.760  5952  6001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1271613 added. We now have 1 listener(s)
08-30 02:45:38.760  5952  6001 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 02:45:38.770  5952  6001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 02:45:38.770  5952  6001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 02:45:38.770  5952  6001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 02:45:38.770  5952  6001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 02:45:38.770  5952  6001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 02:45:38.770  5952  6001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 02:45:38.770  5952  6001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:EB:95:EE
,08-30 02:45:38.780  5952  6001 D BluetoothAdapter: STATE_ON
,08-30 02:45:38.780  5952  6001 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-30 02:45:38.780  5952  6001 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 02:45:38.780  5952  6001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 02:45:38.780  5952  6001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 02:45:38.780  5952  6001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 02:45:38.780  5952  6001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 02:45:38.780  5952  6001 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 02:45:38.780  5952  6001 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 02:45:38.780  5952  6001 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 02:45:38.780  5952  6001 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 02:45:38.780  5952  6001 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 02:45:38.780  5952  6001 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 02:45:38.780  5952  5952 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 02:45:38.790  5952  5952 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 02:45:38.800  5952  5952 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 02:45:39.210  1795  1795 D Recents : onTaskStackChanged
,08-30 02:45:39.850  5952  6002 W jxcore-log: Initializing JXcore engine
08-30 02:45:39.850  5952  6002 W jxcore-log: JXcore engine is ready
,08-30 02:45:39.890  2525  2525 E audit   : type=1400 msg=audit(1472517939.890:273): avc:  denied  { ioctl } for  pid=6002 comm="Thread-108" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5369 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 02:45:39.890  2525  2525 E audit   :  SEPF_SECMOBILE_6.0.1_0013
08-30 02:45:39.890  2525  2525 E audit   : type=1300 msg=audit(1472517939.890:273): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=7 a1=5451 a2=3 a3=d851e3c8 items=0 ppid=590 pid=6002 auid=4294967295 uid=10136 gid=10136 euid=10136 suid=10136 fsuid=10136 egid=10136 sgid=10136 fsgid=10136 ses=4294967295 tty=(none) comm="Thread-108" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-30 02:45:39.890  2525  2525 E audit   : type=1327 msg=audit(1472517939.890:273): proctitle="com.test.thalitest"
08-30 02:45:39.890  2525  2525 E audit   : type=1320 msg=audit(1472517939.890:273): 
08-30 02:45:39.890  2525  2525 E audit   : type=1400 msg=audit(1472517939.890:274): avc:  denied  { ioctl } for  pid=6002 comm="Thread-108" path="socket:[45487]" dev="sockfs" ino=45487 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-30 02:45:39.890  2525  2525 E audit   :  SEPF_SECMOBILE_6.0.1_0013
08-30 02:45:39.890  2525  2525 E audit   : type=1300 msg=audit(1472517939.890:274): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3c a1=5451 a2=3 a3=d851e3c8 items=0 ppid=590 pid=6002 auid=4294967295 uid=10136 gid=10136 euid=10136 suid=10136 fsuid=10136 egid=10136 sgid=10136 fsgid=10136 ses=4294967295 tty=(none) comm="Thread-108" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-30 02:45:39.890  2525  2525 E audit   : type=1327 msg=audit(1472517939.890:274): proctitle="com.test.thalitest"
08-30 02:45:39.890  2525  2525 E audit   : type=1320 msg=audit(1472517939.890:274): 
,08-30 02:45:39.890  5952  6002 W jxcore-log: Starting JXcore engine
,08-30 02:45:39.950  5952  6002 W jxcore-log: Platform android
08-30 02:45:39.950  5952  6002 W jxcore-log: 
08-30 02:45:39.950  5952  6002 W jxcore-log: Process ARCH arm
08-30 02:45:39.950  5952  6002 W jxcore-log: 
,08-30 02:45:40.040  5952  6002 I jxcore-log: JXcore Cordova bridge is ready!
08-30 02:45:40.040  5952  6002 I jxcore-log: 
08-30 02:45:40.040  5952  6002 W jxcore-log: JXcore engine is started
,08-30 02:45:40.050  5952  6001 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 02:45:40.050  5952  5952 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 02:45:40.380  1158  1661 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/18_task.xml.bak
,08-30 02:45:40.780  1158  3553 D GameManagerService: identifyGamePackage. com.test.thalitest
,08-30 02:45:41.100  1158  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 02:45:42.080  1158  3553 D SSRM:s  : SIOP:: AP = 340, PST = 365 (W:9), CP = 43, LCD = 0
,08-30 02:45:42.090  1158  3553 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-30 02:45:42.600  3588  3588 D FactoryTest: User mode
,08-30 02:45:42.600  3588  3588 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-30 02:45:42.600  3588  3588 D MTPRx   : still no open session command from host, so toast
,08-30 02:45:42.610  1158  1722 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
,08-30 02:45:42.620  1158  1722 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,08-30 02:45:42.620  1158  1722 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.samsung.android.MtpApplication)
,08-30 02:45:42.620  1158  1722 D ActivityManager: mDVFSHelper.acquire()
,08-30 02:45:42.630  1158  1722 V WindowManager: addAppToken: AppWindowToken{d0d4c88c3 token=Token{c1f9c72 ActivityRecord{3ef057d u0 com.samsung.android.MtpApplication/.USBConnection t19}}} to stack=2 task=19 at 0
,08-30 02:45:42.630  1158  1722 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,08-30 02:45:42.630  1158  1358 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
08-30 02:45:42.630  1158  1158 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
,08-30 02:45:42.650  1158  1722 D InputDispatcher: Focused application set to: xxxx
,08-30 02:45:42.650  3588  3588 E MTPRx   : started activity for popup
,08-30 02:45:42.650  3588  3588 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-30 02:45:42.650  3588  3588 D RelationGraph: garbageCollect()
,08-30 02:45:42.660  1158  3553 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,08-30 02:45:42.670  3588  3588 D MTPUSBConnection: onCreate in USBConnection
08-30 02:45:42.670  3588  3588 V MTPUSBConnection: Registering broadcast receiver.
,08-30 02:45:42.670  3588  3588 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,08-30 02:45:42.670  1158  1989 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,08-30 02:45:42.710  3588  3588 D TAG     : dev.kiessupport is : TRUE
,08-30 02:45:42.730  3588  3588 D SecWifiDisplayUtil: Metadata value : SecSettings2
,08-30 02:45:42.730  3588  3588 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{813a00d V.E...... R.....I. 0,0-0,0}
,08-30 02:45:42.730  3588  6004 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 02:45:42.740  3588  3588 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{5a4ba3c I.E...... R.....I. 0,0-0,0}
,08-30 02:45:42.740  1158  1200 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-30 02:45:42.740  1158  1200 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-30 02:45:42.740  1158  1158 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-30 02:45:42.750  1158  1158 I KnoxTimeoutHandler: Shared devices show user statefalse
08-30 02:45:42.750  1158  1158 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-30 02:45:42.760   444   444 I SurfaceFlinger: id=18 createSurf (97x97),1 flag=4, VSBConnecti
,08-30 02:45:42.770  3588  6004 I Adreno  : QUALCOMM build                   : 971aff5, Ic07f1cdce3
08-30 02:45:42.770  3588  6004 I Adreno  : Build Date                       : 03/29/16
08-30 02:45:42.770  3588  6004 I Adreno  : OpenGL ES Shader Compiler Version: XE031.06.00.02
08-30 02:45:42.770  3588  6004 I Adreno  : Local Branch                     : 
08-30 02:45:42.770  3588  6004 I Adreno  : Remote Branch                    : refs/tags/AU_LINUX_ANDROID_LA.BR.1.3.3.C2.06.00.01.205.077
08-30 02:45:42.770  3588  6004 I Adreno  : Remote Branch                    : NONE
08-30 02:45:42.770  3588  6004 I Adreno  : Reconstruct Branch               : NOTHING
,08-30 02:45:42.780  3588  6004 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 02:45:42.800   444   444 I SurfaceFlinger: id=19 createSurf (129x129),1 flag=4, VSBConnecti
,08-30 02:45:42.820  3588  3588 V ActivityThread: updateVisibility : ActivityRecord{c8be44b token=android.os.BinderProxy@3494b5 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-30 02:45:42.840  3588  6004 E libGLESv2: HWUI Protection: wrong call from hwui context F: ES3-glCreateProgramSEC
,08-30 02:45:42.850  3588  6004 E libGLESv2: HWUI Protection: wrong call from hwui context F: ES3-glCreateProgramSEC
,08-30 02:45:42.850  3588  6004 E libGLESv2: HWUI Protection: wrong call from hwui context F: ES3-glCreateProgramSEC
,08-30 02:45:42.860  1158  1979 V WindowStateAnimator: Finishing drawing window Window{c744d3b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-30 02:45:42.860  1158  1989 V WindowStateAnimator: Finishing drawing window Window{b5b41b1 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-30 02:45:42.860  3588  3588 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-30 02:45:42.860  3588  3588 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,08-30 02:45:42.870  1158  1394 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-30 02:45:42.870  1158  1394 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +226ms (total +242ms)
08-30 02:45:42.870  1158  1394 D ActivityManager: mDVFSHelper.release()
08-30 02:45:42.870  1158  1158 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-30 02:45:42.870  1158  1394 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3ef057d u0 com.samsung.android.MtpApplication/.USBConnection t19} time:98034
,08-30 02:45:42.870  1158  2237 V WindowStateAnimator: Finishing drawing window Window{c744d3b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
08-30 02:45:42.870  1158  1158 I KnoxTimeoutHandler: SD activityfalse
,08-30 02:45:42.870  1158  2165 V WindowStateAnimator: Finishing drawing window Window{b5b41b1 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
08-30 02:45:42.870  3588  3588 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3494b5 time:98038
,08-30 02:45:43.590  1158  1979 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-30 02:45:43.590  1158  1979 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4359, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
08-30 02:45:43.590  1158  1979 D BatteryService: online:4, current avg:37, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-144
08-30 02:45:43.590  1158  1158 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 02:45:43.600  1702  1702 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-30 02:45:43.600  1702  1702 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 02:45:43.600  1702  1702 D PowerUI : priorPlugType = 2 mPlugType =  2
,08-30 02:45:43.600  2514  2514 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-30 02:45:43.600  2514  3103 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-30 02:45:43.620  1702  1702 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,08-30 02:45:43.620  1702  1702 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
08-30 02:45:43.620  1702  1702 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-30 02:45:43.740  1795  1795 D Recents : onTaskStackChanged
,08-30 02:45:43.760  1158  1722 D PackageManager: getComponentMetadataForIconTray : com.test.thalitest.MainActivity does not exist in mServices
08-30 02:45:43.760  1158  1722 D PackageManager: getComponentMetadataForIconTray : com.test.thalitest.MainActivity does not exist in mProviders
08-30 02:45:43.760  1158  1722 D PackageManager: getComponentMetadataForIconTray : com.test.thalitest.MainActivity does not exist in mReceivers
,08-30 02:45:43.760  1795  1795 I ApplicationPackageManager: load=com.test.thalitest, bg=96-96, dr=96-96
,08-30 02:45:43.760  1795  1795 I ApplicationPackageManager: scaled rate=0.98086953, size=96, alpha=2, hold=26, target=96
,08-30 02:45:46.100  1158  3569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 02:45:47.420  1158  1421 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-30 02:45:47.440  1158  1421 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-30 02:45:48.230  5952  6002 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 02:45:48.230  5952  6002 I jxcore-log: 
,08-30 02:45:48.230  5952  6002 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 02:45:48.230  5952  6002 I jxcore-log: 
,08-30 02:45:48.240  5952  6002 D BluetoothAdapter: STATE_ON
,08-30 02:45:48.250  5952  6002 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 02:45:48.250  5952  6002 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 02:45:48.250  5952  6002 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 02:45:48.250  5952  6002 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 02:45:48.250  5952  6002 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 02:45:48.250  5952  6002 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 02:45:48.250  5952  6002 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 02:45:48.250  5952  6002 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 02:45:48.250  5952  6002 D BluetoothAdapter: STATE_ON
,08-30 02:45:48.250  5952  6002 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 02:45:48.250  5952  6002 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 02:45:48.250  5952  6002 I jxcore-log: 
,08-30 02:45:48.260  5952  6002 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 02:45:48.260  5952  6002 I jxcore-log: 
,08-30 02:45:48.470  5952  6002 I jxcore-log: Running unit tests
08-30 02:45:48.470  5952  6002 I jxcore-log: 
,08-30 02:45:48.480  5952  6002 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-30 02:45:48.480  5952  6002 I jxcore-log: Failed to execute UT.
08-30 02:45:48.480  5952  6002 I jxcore-log: 
,08-30 02:45:48.480  5952  6002 I jxcore-log: Unit Test app is loaded
08-30 02:45:48.480  5952  6002 I jxcore-log: 
,08-30 02:45:48.480  5952  6002 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 02:45:48.480  5952  6002 I jxcore-log: 
,08-30 02:45:48.480  5952  6002 I jxcore-log: My device name is: samsung-SM-T719
08-30 02:45:48.480  5952  6002 I jxcore-log: 
08-30 02:45:48.480  5952  6002 I jxcore-log: WARN testUtils: myNameCallback not set!
08-30 02:45:48.480  5952  6002 I jxcore-log: 
,08-30 02:45:48.490  5952  5952 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 02:45:49.910  5952  6002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-30 02:45:49.910  5952  6002 I jxcore-log: 
,08-30 02:45:50.160  5952  6002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 02:45:50.160  5952  6002 I jxcore-log: 
,08-30 02:45:50.180  5952  6002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-30 02:45:50.180  5952  6002 I jxcore-log: 
,08-30 02:45:51.030  5952  6002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-30 02:45:51.030  5952  6002 I jxcore-log: 
,08-30 02:45:51.160  5952  6002 I jxcore-log: ERROR runTests: 
08-30 02:45:51.160  5952  6002 I jxcore-log: 
,08-30 02:45:51.160  5952  6002 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 02:45:51.160  5952  6002 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-30 02:45:51.160  5952  6002 I jxcore-log: WARN testUtils: logCallback not set!
08-30 02:45:51.160  5952  6002 I jxcore-log: 
,08-30 02:45:51.160  5952  6002 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 02:45:51.160  5952  6002 I jxcore-log:     _functionName: 'loadFile',
08-30 02:45:51.160  5952  6002 I jxcore-log:     _lineNumber: '26',
08-30 02:45:51.160  5952  6002 I jxcore-log:     _columnNumber: '11',
08-30 02:45:51.160  5952  6002 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-30 02:45:51.160  5952  6002 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 02:45:51.160  5952  6002 I jxcore-log:     _functionName: '',
08-30 02:45:51.160  5952  6002 I jxcore-log:     _lineNumber: '38',
08-30 02:45:51.160  5952  6002 I jxcore-log:     _columnNumber: '7',
08-30 02:45:51.160  5952  6002 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-30 02:45:51.160  5952  6002 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 02:45:51.160  5952  6002 I jxcore-log:     _functionName: '',
08-30 02:45:51.160  5952  6002 I jxcore-log:     _lineNumber: '35',
08-30 02:45:51.160  5952  6002 I jxcore-log:     _columnNumber: '3',
08-30 02:45:51.160  5952  6002 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 02:45:51.160  5952  6002 I jxcore-log:   { _fileName: 'module.js',
08-30 02:45:51.160  5952  6002 I jxcore-log:     _functionName: '$w.prototype._compile',
08-30 02:45:51.160  5952  6002 I jxcore-log:     _lineNumber: '621',
08-30 02:45:51.160  5952  6002 I jxcore-log:     _columnNumber: '8',
08-30 02:45:51.160  5952  6002 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-30 02:45:51.160  5952  6002 I jxcore-log:   { _fileName: 'module.js',
08-30 02:45:51.160  5952  6002 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-30 02:45:51.160  5952  6002 I jxcore-log:     _lineNumber: '651',
08-30 02:45:51.160  5952  6002 I jxcore-log:     _columnNumber: '1',
08-30 02:45:51.160  5952  6002 I jxcore-log:    
08-30 02:45:51.160  5952  6002 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 02:45:51.160  5952  6002 I jxcore-log: 
08-30 02:45:51.160  5952  6002 E jxcore-log: Error: 
08-30 02:45:51.160  5952  6002 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 02:45:51.160  5952  6002 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-30 02:45:51.160  5952  6002 E jxcore-log: 
,08-30 02:45:51.630  6007  6007 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-30 02:45:51.650  6007  6007 D AndroidRuntime: CheckJNI is OFF
,08-30 02:45:51.650  6007  6007 D AndroidRuntime: readGMSProperty: start
08-30 02:45:51.650  6007  6007 D AndroidRuntime: readGMSProperty: already setted!!
08-30 02:45:51.650  6007  6007 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 02:45:51.650  6007  6007 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 02:45:51.650  6007  6007 D AndroidRuntime: readGMSProperty: end
08-30 02:45:51.650  6007  6007 D AndroidRuntime: addProductProperty: start
,08-30 02:45:51.690  6007  6007 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-30 02:45:51.730  6007  6007 I Radio-JNI: register_android_hardware_Radio DONE
,08-30 02:45:51.730  6007  6007 E AffinityControl: AffinityControl: registerfunction enter
,08-30 02:45:51.750  6007  6007 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 02:45:51.780  1158  2287 D PackageManager: START PACKAGE DELETE: observer{63248022}
08-30 02:45:51.780  1158  2287 D PackageManager: pkg{<packageName>}
08-30 02:45:51.780  1158  2287 D PackageManager: user{0}
08-30 02:45:51.780  1158  2287 D PackageManager: caller{2000}
08-30 02:45:51.780  1158  2287 D PackageManager: flags{2}
08-30 02:45:51.780  1158  2287 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-30 02:45:51.780  1158  2287 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-30 02:45:51.780  1158  2287 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-30 02:45:51.780  1158  2287 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-30 02:45:51.780  1158  2287 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-30 02:45:51.780  1158  1421 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-30 02:45:51.780  1158  1421 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-30 02:45:51.780  1158  1421 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-30 02:45:51.780  1158  1421 D ApplicationPolicy: getApplicationUninstallationEnabled
08-30 02:45:51.780  1158  1421 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-30 02:45:51.780  1158  1421 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-30 02:45:51.780  1158  1421 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-30 02:45:51.780  1158  1421 D PackageManager: !@killApplicatoin: 10136, uninstall pkg
08-30 02:45:51.780  1158  1421 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-30 02:45:51.780  1158  1421 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-30 02:45:51.790  1158  1358 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5952 ,hash=80753072 ,name=com.test.thalitest
08-30 02:45:51.790  1158  1358 I ActivityManager: Force stopping com.test.thalitest appid=10136 user=-1: uninstall pkg
08-30 02:45:51.790  1158  1358 I ActivityManager: Killing 5952:com.test.thalitest/u0a136 (adj 1): stop com.test.thalitest cause uninstall pkg
08-30 02:45:51.790  1158  1358 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-30 02:45:51.810  1158  1421 D AASAinstall: there is not AASApackages.xml file
,08-30 02:45:51.810  6016  6016 E Zygote  : v2
08-30 02:45:51.810  6016  6016 I libpersona: KNOX_SDCARD checking this for 10136
08-30 02:45:51.810  6016  6016 I libpersona: KNOX_SDCARD not a persona
,08-30 02:45:51.810  6016  6016 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-30 02:45:51.810  1158  1358 I ActivityManager: Start proc 6016:com.test.thalitest/u0a136 for activity com.test.thalitest/.MainActivity
,08-30 02:45:51.810  6016  6016 E Zygote  : accessInfo : 0
08-30 02:45:51.810  6016  6016 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-30 02:45:51.810  1158  1358 I ActivityManager:   Force finishing activity ActivityRecord{f2e4a5f u0 com.test.thalitest/.MainActivity t18}
08-30 02:45:51.810  1158  1358 W VirtualScreenManagerService: moveTaskBackToDisplayIfNeeded(): top activity or app is null
,08-30 02:45:51.820   444  2797 I SurfaceFlinger: id=17 Removed NainActivit (6/13)
,08-30 02:45:51.820   444  2797 I SurfaceFlinger: id=17 Removed NainActivit (-2/13)
,08-30 02:45:51.840  6016  6016 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 02:45:51.840  6016  6016 D ActivityThread: Added TimaKeyStore provider
,08-30 02:45:51.950   444   473 E         : BitTube(): close sendFd (41)
08-30 02:45:51.950   444   473 E         : BitTube(): close sendFd (46)
08-30 02:45:51.950  1158  2165 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@6349604)
08-30 02:45:51.950  1158  1628 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 02:45:51.950  1158  2446 D GraphicsStats: Buffer count: 5
,08-30 02:45:51.950  1158  1628 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 02:45:51.950  1158  1628 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 02:45:52.090  1158  1421 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-30 02:45:52.120  1158  3553 D SSRM:s  : SIOP:: AP = 380, PST = 367 (W:10), CP = 48, LCD = 0
,08-30 02:45:52.130  1158  3553 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-30 02:45:52.170  1158  1421 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-30 02:45:52.170   567   567 W keystore: ENTER clear_uid from uid 1000 for 10136
,08-30 02:45:52.170  1158  1421 I art     : Starting a blocking GC Explicit
,08-30 02:45:52.210  6016  6016 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
08-30 02:45:52.210  6016  6016 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
,08-30 02:45:52.210  6016  6016 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
08-30 02:45:52.210  6016  6016 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
,08-30 02:45:52.220  6016  6016 D AndroidRuntime: Shutting down VM
,08-30 02:45:52.220  6016  6016 E AndroidRuntime: FATAL EXCEPTION: main
08-30 02:45:52.220  6016  6016 E AndroidRuntime: Process: com.test.thalitest, PID: 6016
08-30 02:45:52.220  6016  6016 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-30 02:45:52.220  6016  6016 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:676)
08-30 02:45:52.220  6016  6016 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6296)
08-30 02:45:52.220  6016  6016 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:223)
08-30 02:45:52.220  6016  6016 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1863)
08-30 02:45:52.220  6016  6016 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:45:52.220  6016  6016 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
08-30 02:45:52.220  6016  6016 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7231)
08-30 02:45:52.220  6016  6016 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 02:45:52.220  6016  6016 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-30 02:45:52.220  6016  6016 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-30 02:45:52.220  6016  6016 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-30 02:45:52.220  6016  6016 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:485)
08-30 02:45:52.220  6016  6016 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:661)
08-30 02:45:52.220  6016  6016 E AndroidRuntime: 	... 9 more
,08-30 02:45:52.230  6016  6016 I Process : Sending signal. PID: 6016 SIG: 9
,08-30 02:45:52.240  6031  6031 E Zygote  : v2
08-30 02:45:52.240  1158  1358 I ActivityManager: Start proc 6031:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
08-30 02:45:52.240  6031  6031 I libpersona: KNOX_SDCARD checking this for 1000
08-30 02:45:52.240  6031  6031 I libpersona: KNOX_SDCARD not a persona
,08-30 02:45:52.240  6031  6031 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-30 02:45:52.240  1158  1979 I ActivityManager: Process com.test.thalitest (pid 6016)(adj 9) has died(164,1494)
08-30 02:45:52.250  1158  1979 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
08-30 02:45:52.250  6031  6031 E Zygote  : accessInfo : 0
08-30 02:45:52.250  1158  1979 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=6016 ,hash=97550871 ,name=com.test.thalitest
,08-30 02:45:52.250  1158  1979 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.android.server.am.ActivityManagerService.updateOomAdjLocked:26615 com.android.server.am.ActivityManagerService.appDiedLocked:7605 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1888 android.os.BinderProxy.sendDeathNotice:558 
,08-30 02:45:52.270  6031  6031 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 02:45:52.270  6031  6031 D ActivityThread: Added TimaKeyStore provider
,08-30 02:45:52.270  1158  2237 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8340622 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{53147ed 6031:com.samsung.android.sm/1000}
,08-30 02:45:52.310  6031  6031 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1311 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.samsung.android.sm.common.SmartManagerReceiver.b:259 com.samsung.android.sm.common.SmartManagerReceiver.onReceive:107 
,08-30 02:45:52.420  1158  1587 V AlarmManager: Expired Alarm result :4
,08-30 02:45:52.420  1158  1358 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6e775e9 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e7e1861 1870:com.google.android.gms.persistent/u0a10}
,08-30 02:45:52.430  1158  1616 V AlarmManager:  remove PendingIntent] PendingIntent{1b0626e: PendingIntentRecord{88a06ac com.google.android.gms broadcastIntent}}
,08-30 02:45:52.430  1158  1421 I art     : Explicit concurrent mark sweep GC freed 234089(13MB) AllocSpace objects, 54(2MB) LOS objects, 33% free, 29MB/43MB, paused 3.074ms total 256.654ms
,08-30 02:45:52.430  1158  1830 E Watchdog: !@Sync 3 [08-30 02:45:52.450]
,08-30 02:45:52.450  1158  1421 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-30 02:45:52.450  1158  1421 D AASAuninstall: userId = 0, info.removedAppID = 10136, info.uid = 10136, packageName = com.test.thalitest
08-30 02:45:52.450  1158  1421 D AASAinstall: there is not AASApackages.xml file
08-30 02:45:52.450  1158  1421 D PackageManager: result of delete: 1{63248022}
,08-30 02:45:52.460  1158  1421 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-30 02:45:52.460  1158  1421 D PackageManager: userId{-1}
08-30 02:45:52.460  1158  1421 D PackageManager: andCode{true}
,08-30 02:45:52.460  6007  6007 I art     : System.exit called, status: 0
08-30 02:45:52.460  6007  6007 I AndroidRuntime: VM exiting with result code 0.
,08-30 02:45:52.470  1158  1421 I ActivityManager: Force stopping com.test.thalitest appid=10136 user=0: pkg removed
,08-30 02:45:52.490  5687  6045 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-30 02:45:52.490  5687  6045 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-30 02:45:52.490  5687  6045 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-30 02:45:52.510  1702  1702 D ShortcutManager: onReceive : android.intent.action.PACKAGE_REMOVED
08-30 02:45:52.510  1702  1702 D ShortcutManager: onReceive : Intent.EXTRA_REPLACING false,com.test.thalitest
,08-30 02:45:52.510  1702  1702 D CoverUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
,08-30 02:45:52.520  1158  1589 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 02:45:52.520  5055  5097 I SystemBroadcastReceiver: [#CMH#] Received broadcast 
08-30 02:45:52.520  5055  5097 I ControllerEventHandler: [#CMH#] onPackageRemoved  null
08-30 02:45:52.520  5055  5097 I SystemBroadcastReceiver: [#CMH#] onReceive completed 
,08-30 02:45:52.530  1158  1618 V NetworkStats: removeUidsLocked() for UIDs [10136]
08-30 02:45:52.530  1158  1618 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 02:45:52.530  1158  1618 V NetworkStats: performPollLocked(flags=0x3)
,08-30 02:45:52.530  1158  1618 V NetworkStats: performPollLocked() took 4ms
08-30 02:45:52.530  1158  1618 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 02:45:52.540  1158  1358 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b0431e u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bfc8254 3904:com.samsung.klmsagent/u0a16}
08-30 02:45:52.540  1931  1931 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-30 02:45:52.540  3904  3904 I KLMS-2.6.094: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } | timestamp: Tue Aug 30 02:45:52 GMT+02:00 2016
,08-30 02:45:52.550  1158  1619 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 02:45:52.550  1158  1619 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 02:45:52.550  1158  1200 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=2489, uid=10093 that is not exported from uid 10091
,08-30 02:45:52.560  1795  1795 I Recents_MultiWindowAppListInfo: android.intent.action.PACKAGE_REMOVE
,08-30 02:45:52.560  1158  1351 D EnterpriseDeviceManagerService: Package has changed for user 0
08-30 02:45:52.560  1158  1351 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-30 02:45:52.560  3904  3904 I KLMS-2.6.094: : KLMSAbstractReciever(): onReceive().END.
,08-30 02:45:52.570  3904  3904 I KLMS-2.6.094: : KLMSIntentService(): onCreate()
,08-30 02:45:52.570  3904  3904 I KLMS-2.6.094: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-30 02:45:52.570  1158  2237 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b0431e u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c495c55 1158:system/1000}
,08-30 02:45:52.570  3904  3904 I KLMS-2.6.094: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-30 02:45:52.570  3904  6050 I KLMS-2.6.094: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,08-30 02:45:52.570  3904  6050 D KLMS-2.6.094: : KLMSIntentService(): PACKAGE_REMOVED
08-30 02:45:52.570  3904  6050 I KLMS-2.6.094: : Systemprocess(): listeningToPackageRemoved().START
08-30 02:45:52.570  3904  6050 I KLMS-2.6.094: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
08-30 02:45:52.570  3904  6050 I KLMS-2.6.094: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
08-30 02:45:52.570  3904  6050 I KLMS-2.6.094: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-30 02:45:52.580  3904  6050 I KLMS-2.6.094: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-30 02:45:52.580  3904  6050 I KLMS-2.6.094: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-30 02:45:52.580  3904  6050 I KLMS-2.6.094: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-30 02:45:52.580  3904  6050 D KLMS-2.6.094: : Systemprocess(): arrayLicenseInfo is null
,08-30 02:45:52.590  3904  6050 D KLMS-2.6.094: : DataSource(): Fetched Data from data base count : 0
,08-30 02:45:52.600  1158  2237 D SettingsProvider: isChangeAllowed() : name = klm_eula_shown
08-30 02:45:52.600  1158  2237 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 02:45:52.600  1158  2237 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-30 02:45:52.600  1158  2237 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 02:45:52.600  1158  2237 D SettingsProvider: selectionArgs: false
08-30 02:45:52.600  1158  2237 D SettingsProvider: selectionArgs: 10016
,08-30 02:45:52.600  1158  2237 D SettingsProvider: ret = -1
,08-30 02:45:52.600  1870  2392 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 02:45:52.610  1158  2165 V AlarmManager:  remove PendingIntent] PendingIntent{d52d3b7: PendingIntentRecord{88a06ac com.google.android.gms broadcastIntent}}
,08-30 02:45:52.610  1158  1158 V AlarmManager: Remove alarm for next reason : android.intent.action.PACKAGE_REMOVED : package: com.test.thalitest
,08-30 02:45:52.620  1158  1158 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-30 02:45:52.620  1158  1158 D UniversalCredentialManagerService: inside mPkgReciever onReceive : android.intent.action.PACKAGE_REMOVED
08-30 02:45:52.620  1158  1158 D UniversalCredentialManagerService: ACTION_PACKAGE_REMOVED is called....
08-30 02:45:52.620  1158  1158 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-30 02:45:52.620  1158  1158 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-30 02:45:52.620  1158  1158 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10136 container id = 0
,08-30 02:45:52.620  1158  1158 I OTPFW   : ProvisionData::getAllEntries Enter
,08-30 02:45:52.620  1158  1158 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-30 02:45:52.620  1158  1158 E SDAgentPackageStateReceiver: Not going to handle 'com.test.thalitest'!
,08-30 02:45:52.620  1158  1158 D UcmService: onReceive android.intent.action.PACKAGE_REMOVED
08-30 02:45:52.620  1158  1158 D UcmService: Package update in userId-0 and uid-10136
,08-30 02:45:52.630  1158  1158 D GameManager.DatabaseHelper: removeGame(), packageName: com.test.thalitest, ret: 0
08-30 02:45:52.630  1158  1158 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-30 02:45:52.630  1158  1158 V EnterpriseBillingAsyncHandler: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-30 02:45:52.630  1158  1653 V EnterpriseBillingPolicyInternal: packageModification -  start - android.intent.action.PACKAGE_REMOVED
08-30 02:45:52.630  1158  1653 V EnterpriseBillingPolicyInternal: uID is 10136
08-30 02:45:52.630  1158  1653 V EnterpriseBillingPolicyInternal: Removed Packageuid is0
08-30 02:45:52.630  1158  1653 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-30 02:45:52.630  1158  1653 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-30 02:45:52.630  1158  1653 V EnterpriseBillingPolicyInternal: packageModificationReceiver - onreceive - personal application - profile null
08-30 02:45:52.630  1158  1158 D SdpManagerService:  ActionReceiver::onReceive() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,08-30 02:45:52.630  1158  1158 D SdpManagerService: ACTION_PACKAGE_REMOVED Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } DATA= package:com.test.thalitest UID 1000 userId 0
08-30 02:45:52.630  1158  1158 D SdpManagerService: ACTION_PACKAGE_REMOVED packageName:: com.test.thalitest
08-30 02:45:52.630  1158  1158 D EnterprisePartitionManager: SND -> {secure_fs remove_enc_dir}
,08-30 02:45:52.630   384   437 D epmd    : Partition obj created
08-30 02:45:52.630   384   437 D epmd    : Partition::dump============== 0
08-30 02:45:52.630   384   437 D epmd    : Partition::mType > INTERNAL-SDCARD mSrcPath > /data/knox/secure_fs/enc_user mMntPath > /data/enc_user
08-30 02:45:52.630   384   437 D epmd    : Partition::SDP > not supported
08-30 02:45:52.630  1870  1870 W SQLiteLog: (28) failed to open "/data/user/0/com.google.android.gms/databases/ns.db" with flag (131138) and mode_t (0) due to error (30)
,08-30 02:45:52.630   384   437 E epmd    : removeEncPkgDir ERROR
08-30 02:45:52.630  1158  1423 D EnterprisePartitionManager: RCV <-
08-30 02:45:52.630   384   437 D epmd    : deleting Partition object.
08-30 02:45:52.630  1158  1158 D EnterprisePartitionManager: RMV <-
08-30 02:45:52.630   384   437 W FrameworkListener: Handler 'secure_fs' error (No such file or directory)
08-30 02:45:52.630  1158  1158 D EnterprisePartitionManager: event : 281 3 remove_enc_dir failed
,08-30 02:45:52.630  1158  1158 D SdpManagerService: start document   : 
,08-30 02:45:52.630  1158  1158 D SdpManagerService: start element    : engine_list
08-30 02:45:52.630  1158  1158 D SdpManagerService: start characters : 
08-30 02:45:52.630  1158  1158 D SdpManagerService: start element    : engine
08-30 02:45:52.640  1158  1158 D SdpManagerService:  attribte alias: android_0
08-30 02:45:52.640  1158  1158 D SdpManagerService:  attribte id: 0
08-30 02:45:52.640  1158  1158 D SdpManagerService: end element      : engine
08-30 02:45:52.640  1158  1158 D SdpManagerService: start characters : 
08-30 02:45:52.640  1158  1158 D SdpManagerService: end element      : engine_list
08-30 02:45:52.640  1158  1158 D SdpManagerService: end document     : 
,08-30 02:45:52.640  1158  1158 W System.err: mkdir failed: EEXIST (File exists) : /data/system/users/0
08-30 02:45:52.640  1158  1158 E SdpManagerService: cant make directory /data/system/users/0
08-30 02:45:52.640  1870  1870 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/ns.db'.
08-30 02:45:52.640  1870  1870 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:45:52.640  1870  1870 E SQLiteDatabase: #################################################################
08-30 02:45:52.640  1870  1870 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
08-30 02:45:52.640  1870  1870 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-30 02:45:52.640  1870  1870 E SQLiteDatabase: #################################################################
08-30 02:45:52.640  1870  1870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:45:52.640  1870  1870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-30 02:45:52.640  1870  1870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-30 02:45:52.640  1870  1870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-30 02:45:52.640  1870  1870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-30 02:45:52.640  1870  1870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-30 02:45:52.640  1870  1870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-30 02:45:52.640  1870  1870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-30 02:45:52.640  1870  1870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-30 02:45:52.640  1870  1870 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:639)
08-30 02:45:52.640  1870  1870 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-30 02:45:52.640  1870  1870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:45:52.640  1870  1870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:45:52.640  1870  1870 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.k.b(:com.google.android.gms:244)
08-30 02:45:52.640  1870  1870 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.h.a(:com.google.android.gms:51)
08-30 02:45:52.640  1870  1870 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.i.handleMessage(:com.google.android.gms:172)
08-30 02:45:52.640  1870  1870 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:45:52.640  1870  1870 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:158)
08-30 02:45:52.640  1870  1870 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:7231)
08-30 02:45:52.640  1870  1870 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 02:45:52.640  1870  1870 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-30 02:45:52.640  1870  1870 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-30 02:45:52.640  1158  1158 D SdpManagerService: start document   : 
08-30 02:45:52.640  1158  1158 D SdpManagerService: start element    : user
08-30 02:45:52.640  1158  1158 D SdpManagerService: end element      : user
08-30 02:45:52.640  1158  1158 D SdpUtil : num:0 index-0
08-30 02:45:52.640  1158  1158 D SdpUtil : detecected userId : 0
08-30 02:45:52.640  1158  1158 D SdpManagerService: end document     : ,
08-30 02:45:52.640  1158  1158 E SdpManagerService: Can't find engine info [android_0]
08-30 02:45:52.640  1870  1870 D AndroidRuntime: Shutting down VM
08-30 02:45:52.640  1158  3553 D SSRM:bb : MSG_TYPE_APP_REMOVED::
08-30 02:45:52.640  1158  1158 V EnterpriseBillingAsyncHandler: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-30 02:45:52.640  1158  1158 D AccessibilityManagerService: checkUniversalSwitchState start:
08-30 02:45:52.640  1158  1653 V EnterpriseBillingPolicyInternal: packageModification -  start - android.intent.action.PACKAGE_FULLY_REMOVED
08-30 02:45:52.640  1158  3553 D SSRM:bb : MSG_TYPE_UID_REMOVED::
08-30 02:45:52.640  1158  1653 V EnterpriseBillingPolicyInternal: uID is 10136
08-30 02:45:52.640  1158  1653 V EnterpriseBillingPolicyInternal: Removed Packageuid is0
08-30 02:45:52.640  1158  1653 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-30 02:45:52.640  1158  1653 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-30 02:45:52.640  1158  1653 V EnterpriseBillingPolicyInternal: packageModificationReceiver - onreceive - personal application - profile null
08-30 02:45:52.640  5737  5751 E SQLiteLog: (10) unixWrite() File Descriptor : 20 gets errno : 30
08-30 02:45:52.650  5737  5751 E DatabaseUtils: Writing exception to parcel
08-30 02:45:52.650  5737  5751 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
08-30 02:45:52.650  5737  5751 E DatabaseUtils: #################################################################
08-30 02:45:52.650  5737  5751 E DatabaseUtils: Error Code : 778 (SQLITE_IOERR_WRITE)
08-30 02:45:52.650  5737  5751 E DatabaseUtils: Caused By : Disk I/O error occurred during 'write' operation.
08-30 02:45:52.650  5737  5751 E DatabaseUtils: 	(disk I/O error (code 778))
08-30 02:45:52.650  5737  5751 E DatabaseUtils: #################################################################
08-30 02:45:52.650  5737  5751 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 02:45:52.650  5737  5751 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:866)
08-30 02:45:52.650  5737  5751 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 02:45:52.650  5737  5751 E DatabaseUtils: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 02:45:52.650  5737  5751 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
08-30 02:45:52.650  5737  5751 E DatabaseUtils: 	at com.samsung.android.sm.database.SmProvider.delete(SmProvider.java:826)
08-30 02:45:52.650  5737  5751 E DatabaseUtils: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:352)
08-30 02:45:52.650  5737  5751 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:206)
08-30 02:45:52.650  5737  5751 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:453)
08-30 02:45:52.650  1158  1391 E MARsDBManager: Exception with contentResolver : disk I/O error (code 778)
08-30 02:45:52.650  1158  1391 E MARsDBManager: #################################################################
08-30 02:45:52.650  1158  1391 E MARsDBManager: Error Code : 778 (SQLITE_IOERR_WRITE)
08-30 02:45:52.650  1158  1391 E MARsDBManager: Caused By : Disk I/O error occurred during 'write' operation.
08-30 02:45:52.650  1158  1391 E MARsDBManager: 	(disk I/O error (code 778))
08-30 02:45:52.650  1158  1391 E MARsDBManager: #################################################################
08-30 02:45:52.650  1158  1391 E MARsDBManager: #################################################################
08-30 02:45:52.650  1158  1391 E MARsDBManager: Error Code : 778 (SQLITE_IOERR_WRITE)
08-30 02:45:52.650  1158  1391 E MARsDBManager: Caused By : Disk I/O error occurred during 'write' operation.
08-30 02:45:52.650  1158  1391 E MARsDBManager: 	(disk I/O error (code 778)
08-30 02:45:52.650  1158  1391 E MARsDBManager: #################################################################
08-30 02:45:52.650  1158  1391 E MARsDBManager: Error Code : 778 (SQLITE_IOERR_WRITE)
08-30 02:45:52.650  1158  1391 E MARsDBManager: Caused By : Disk I/O error occurred during 'write' operation.
08-30 02:45:52.650  1158  1391 E MARsDBManager: 	(disk I/O error (code 778))
08-30 02:45:52.650  1158  1391 E MARsDBManager: #################################################################)
08-30 02:45:52.650  1158  1391 E MARsDBManager: #################################################################
08-30 02:45:52.650  1870  1870 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-qcF
08-30 02:45:52.650  1870  1870 I GCore-Chimera-Crash: GCore-Chimera-Crash
08-30 02:45:52.650  1870  1870 E AndroidRuntime: FATAL EXCEPTION: main
08-30 02:45:52.650  1870  1870 E AndroidRuntime: Process: com.google.android.gms.persistent, PID: 1870
08-30 02:45:52.650  1870  1870 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:45:52.650  1870  1870 E AndroidRuntime: #################################################################
08-30 02:45:52.650  1870  1870 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
08-30 02:45:52.650  1870  1870 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-30 02:45:52.650  1870  1870 E AndroidRuntime: #################################################################
08-30 02:45:52.650  1870  1870 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:45:52.650  1870  1870 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-30 02:45:52.650  1870  1870 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-30 02:45:52.650  1870  1870 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-30 02:45:52.650  1870  1870 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-30 02:45:52.650  1870  1870 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-30 02:45:52.650  1870  1870 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-30 02:45:52.650  1870  1870 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-30 02:45:52.650  1870  1870 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-30 02:45:52.650  1870  1870 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:639)
08-30 02:45:52.650  1870  1870 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-30 02:45:52.650  1870  1870 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:45:52.650  1870  1870 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:45:52.650  1870  1870 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.k.b(:com.google.android.gms:244)
08-30 02:45:52.650  1870  1870 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.h.a(:com.google.android.gms:51)
08-30 02:45:52.650  1870  1870 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.i.handleMessage(:com.google.android.gms:172)
08-30 02:45:52.650  1870  1870 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:45:52.650  1870  1870 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
08-30 02:45:52.650  1870  1870 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7231)
08-30 02:45:52.650  1870  1870 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 02:45:52.650  1870  1870 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-30 02:45:52.650  1870  1870 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-30 02:45:52.670  1158  1351 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-30 02:45:52.670  1986  1986 E Launcher.Model: onPackageRemoved :com.test.thalitest
,08-30 02:45:52.670  1986  2123 E SQLiteLog: (10) unixWrite() File Descriptor : 20 gets errno : 30
08-30 02:45:52.680  1986  2123 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-30 02:45:52.680  1986  2123 E AndroidRuntime: Process: com.sec.android.app.launcher, PID: 1986
08-30 02:45:52.680  1986  2123 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
08-30 02:45:52.680  1986  2123 E AndroidRuntime: #################################################################
08-30 02:45:52.680  1986  2123 E AndroidRuntime: Error Code : 778 (SQLITE_IOERR_WRITE)
08-30 02:45:52.680  1986  2123 E AndroidRuntime: Caused By : Disk I/O error occurred during 'write' operation.
08-30 02:45:52.680  1986  2123 E AndroidRuntime: 	(disk I/O error (code 778))
08-30 02:45:52.680  1986  2123 E AndroidRuntime: #################################################################
08-30 02:45:52.680  1986  2123 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-30 02:45:52.680  1986  2123 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:679)
08-30 02:45:52.680  1986  2123 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
08-30 02:45:52.680  1986  2123 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
08-30 02:45:52.680  1986  2123 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:527)
08-30 02:45:52.680  1986  2123 E AndroidRuntime: 	at com.android.launcher2.LauncherProvider.updateAppItems(LauncherProvider.java:539)
08-30 02:45:52.680  1986  2123 E AndroidRuntime: 	at com.android.launcher2.LauncherModel$6.run(LauncherModel.java:845)
08-30 02:45:52.680  1986  2123 E AndroidRuntime: 	at com.android.launcher2.LauncherModel.updateAppItems(LauncherModel.java:849)
08-30 02:45:52.680  1986  2123 E AndroidRuntime: 	at com.android.launcher2.MenuAppLoader.removePackage(MenuAppLoader.java:891)
08-30 02:45:52.680  1986  2123 E AndroidRuntime: 	at com.android.launcher2.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3788)
08-30 02:45:52.680  1986  2123 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 02:45:52.680  1986  2123 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 02:45:52.680  1986  2123 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
08-30 02:45:52.680  1986  2123 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
