#### Test 836273370459b7a_thali05_samsung-SM-T719 Logs


```
--------- beginning of system
,09-13 16:33:27.101  1158  3586 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
09-13 16:33:27.551  6033  6033 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-13 16:33:27.551  6033  6033 D AndroidRuntime: CheckJNI is OFF
09-13 16:33:27.551  6033  6033 D AndroidRuntime: readGMSProperty: start
09-13 16:33:27.551  6033  6033 D AndroidRuntime: readGMSProperty: already setted!!
09-13 16:33:27.551  6033  6033 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-13 16:33:27.551  6033  6033 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-13 16:33:27.551  6033  6033 D AndroidRuntime: readGMSProperty: end
09-13 16:33:27.551  6033  6033 D AndroidRuntime: addProductProperty: start
09-13 16:33:27.581  6033  6033 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-13 16:33:27.611  6033  6033 I Radio-JNI: register_android_hardware_Radio DONE
09-13 16:33:27.621  6033  6033 E AffinityControl: AffinityControl: registerfunction enter
09-13 16:33:27.631  6033  6033 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-13 16:33:27.661  1158  1719 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
09-13 16:33:27.681  1158  1719 D GameManagerService: identifyGamePackage. com.test.thalitest
09-13 16:33:27.681  1158  1719 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-13 16:33:27.691  1158  1719 D ActivityManager: mDVFSHelper.acquire()
09-13 16:33:27.691   445   445 I SurfaceFlinger: id=14 createSurf (16x16),-1 flag=20004, EimLayer(Di
09-13 16:33:27.691   445   445 I SurfaceFlinger: id=15 createSurf (16x16),-1 flag=20004, EimLayer(An
09-13 16:33:27.701  1699  1699 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-13 16:33:27.701  1158  1719 D FocusedStackFrame: Set to : 0
09-13 16:33:27.701  1158  1158 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-13 16:33:27.701  1699  1699 D WallpaperService: MSG_WINDOW_RESIZED
09-13 16:33:27.701  1699  1699 D WallpaperService: updateSurface
09-13 16:33:27.701  1699  1699 V WallpaperService: Changes: creating=false format=false size=false
09-13 16:33:27.701  1699  1699 V WallpaperService: mWidth:2048 SurfaceWidth:2048 mHeight:2048 SurfaceHeigh:2048
09-13 16:33:27.701  1699  1699 D WallpaperService: relayout
09-13 16:33:27.701  1158  1158 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-13 16:33:27.701  1699  1699 V WallpaperService: Wallpaper size has changed: (2048, 2048)
09-13 16:33:27.701  1158  1719 V WindowManager: addAppToken: AppWindowToken{d0916ad11 token=Token{2918938 ActivityRecord{251319b u0 com.test.thalitest/.MainActivity t18}}} to stack=2 task=18 at 0
09-13 16:33:27.711  1158  1414 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{78ed49 V.E...... R.....ID 0,0-0,0}
09-13 16:33:27.711  1158  1414 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-13 16:33:27.721  6042  6042 E Zygote  : v2
09-13 16:33:27.721  6042  6042 I libpersona: KNOX_SDCARD checking this for 10136
09-13 16:33:27.721  6042  6042 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:27.721  6042  6042 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-13 16:33:27.721  1158  1719 I ActivityManager: Start proc 6042:com.test.thalitest/u0a136 for activity com.test.thalitest/.MainActivity
09-13 16:33:27.721  6042  6042 E Zygote  : accessInfo : 0
09-13 16:33:27.721  6042  6042 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-13 16:33:27.721   445   445 I SurfaceFlinger: id=16 createSurf (1536x2048),1 flag=404, uhalitest
09-13 16:33:27.731  1158  1719 D InputDispatcher: Focused application set to: xxxx
09-13 16:33:27.731  1158  1414 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 48 - 0, 0) vi=Rect(0, 48 - 0, 0) or=1
09-13 16:33:27.731  6033  6033 D AndroidRuntime: Shutting down VM
09-13 16:33:27.731  1158  1620 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-13 16:33:27.741  6042  6042 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:33:27.741  6042  6042 D ActivityThread: Added TimaKeyStore provider
09-13 16:33:27.751  1158  1969 D ActivityManager:  Launching com.test.thalitest, updated priority
09-13 16:33:27.751  1977  1977 V ActivityThread: updateVisibility : ActivityRecord{e007037 token=android.os.BinderProxy@2e5cfdd {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-13 16:33:27.751  1158  1158 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-13 16:33:27.751  1158  1370 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-13 16:33:27.761  1158  1414 V WindowStateAnimator: Finishing drawing window Window{e65536f u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-13 16:33:27.781   445   464 I SurfaceFlinger: id=9 Removed MauncherAct (5/12)
09-13 16:33:27.791   445   468 I SurfaceFlinger: id=9 Removed MauncherAct (-2/12)
09-13 16:33:27.791  1977  1977 D Launcher: onTrimMemory. Level: 20
,09-13 16:33:28.061  1158  1969 I WindowManager: Screenshot max retries 4 of Token{2918938 ActivityRecord{251319b u0 com.test.thalitest/.MainActivity t18}} appWin=Window{e65536f u0 d0 Starting com.test.thalitest} drawState=4
,09-13 16:33:28.071  1158  1620 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,09-13 16:33:28.071  1158  3556 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-13 16:33:28.081  1158  3556 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-13 16:33:28.111  1158  2632 W ActivityManager: Permission Denial: getCurrentUser() from pid=6042, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
,09-13 16:33:28.111  6042  6042 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-13 16:33:28.111  6042  6042 D RelationGraph: garbageCollect()
,09-13 16:33:28.131  1158  2016 W ActivityManager: Permission Denial: getCurrentUser() from pid=6042, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
,09-13 16:33:28.141  6042  6042 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
,09-13 16:33:28.171  6042  6042 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-13 16:33:28.191  6042  6042 I cr_LibraryLoader: Time to load native libraries: 9 ms (timestamps 2226-2235)
,09-13 16:33:28.191  6042  6042 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
,09-13 16:33:28.221  6042  6056 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,09-13 16:33:28.221  6042  6042 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {13d0a2f}
,09-13 16:33:28.221  6042  6042 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
,09-13 16:33:28.231  6042  6042 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 16:33:28.251  6042  6042 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,09-13 16:33:28.321  6042  6042 I Adreno  : QUALCOMM build                   : 971aff5, Ic07f1cdce3
09-13 16:33:28.321  6042  6042 I Adreno  : Build Date                       : 03/29/16
09-13 16:33:28.321  6042  6042 I Adreno  : OpenGL ES Shader Compiler Version: XE031.06.00.02
09-13 16:33:28.321  6042  6042 I Adreno  : Local Branch                     : 
09-13 16:33:28.321  6042  6042 I Adreno  : Remote Branch                    : refs/tags/AU_LINUX_ANDROID_LA.BR.1.3.3.C2.06.00.01.205.077
09-13 16:33:28.321  6042  6042 I Adreno  : Remote Branch                    : NONE
09-13 16:33:28.321  6042  6042 I Adreno  : Reconstruct Branch               : NOTHING
,09-13 16:33:28.381  1158  2459 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10136
09-13 16:33:28.381  1158  2459 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:851 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29617 com.android.server.am.ActivityManagerService.registerReceiver:22639 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3995 
,09-13 16:33:28.441  6042  6042 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,09-13 16:33:28.451  6042  6042 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-13 16:33:28.451  6042  6042 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,09-13 16:33:28.471  6042  6042 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-13 16:33:28.511  6042  6042 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-13 16:33:28.521  6042  6042 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{36249c I.E...... R.....ID 0,0-0,0}
,09-13 16:33:28.521  6042  6080 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-13 16:33:28.531  1158  1269 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-13 16:33:28.531  1158  1269 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-13 16:33:28.531  1158  1158 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-13 16:33:28.531  1158  1158 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-13 16:33:28.531  6042  6056 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,09-13 16:33:28.551  6042  6042 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10136, CallingPid : 6042
,09-13 16:33:28.551  1158  2603 D ConnectivityService: listenForNetwork for Listen from uid/pid:10136/6042 for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:33:28.551  1158  1629 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
09-13 16:33:28.551  1158  1629 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,fe80::4678:3eff:feeb:95ef/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-13 16:33:28.551  1158  1629 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
09-13 16:33:28.551  1158  1629 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-13 16:33:28.551  1158  1629 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
09-13 16:33:28.551  1158  1629 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-13 16:33:28.551  1158  1629 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
09-13 16:33:28.551  1158  1629 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-13 16:33:28.561  6042  6042 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-13 16:33:28.571   445   445 I SurfaceFlinger: id=17 createSurf (1x1),1 flag=404, NainActivit
,09-13 16:33:28.591  6042  6080 I OpenGLRenderer: Initialized EGL, version 1.4
,09-13 16:33:28.611  6042  6042 V ActivityThread: updateVisibility : ActivityRecord{5e6ae07 token=android.os.BinderProxy@576d9c2 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-13 16:33:28.651  6042  6080 E libGLESv2: HWUI Protection: wrong call from hwui context F: ES3-glCreateProgramSEC
,09-13 16:33:28.681  1158  2603 V WindowStateAnimator: Finishing drawing window Window{dcbf4dc u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,09-13 16:33:28.691  6042  6042 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 48 - 0, 0) vi=Rect(0, 48 - 0, 0) or=1
,09-13 16:33:28.691  1158  1414 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-13 16:33:28.691  1158  1414 D ActivityManager: mDVFSHelper.release()
09-13 16:33:28.691  1158  1158 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-13 16:33:28.691  1158  1414 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +633ms (total +988ms)
09-13 16:33:28.691  1158  1414 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{251319b u0 com.test.thalitest/.MainActivity t18} time:92739
09-13 16:33:28.691  1158  1414 D ViewRootImpl: #3 mView = null
,09-13 16:33:28.691  1158  1158 I KnoxTimeoutHandler: SD activityfalse
09-13 16:33:28.701  1158  1158 I KnoxTimeoutHandler: Fullscreen and mCurrent is not KNOX user. Hence hide keyguard
09-13 16:33:28.701   445   464 I SurfaceFlinger: id=16 Removed uhalitest (6/12)
,09-13 16:33:28.701   445   468 I SurfaceFlinger: id=16 Removed uhalitest (-2/12)
,09-13 16:33:28.701  6042  6085 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 16:33:28.711  1158  2005 V WindowStateAnimator: Finishing drawing window Window{dcbf4dc u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,09-13 16:33:28.711  6042  6042 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@576d9c2 time:92754
,09-13 16:33:28.751  6042  6042 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6042
,09-13 16:33:28.971  6042  6042 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 16:33:29.101  6042  6091 D jxcore_app_log: JniHelper::setJavaVM(0xf4dbc000), pthread_self() = -626001616
,09-13 16:33:29.101  6042  6091 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 16:33:29.101  6042  6091 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 16:33:29.101  6042  6091 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 16:33:29.101  6042  6091 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 16:33:29.101  6042  6091 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-13 16:33:29.101  6042  6091 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c19eccc added. We now have 1 listener(s)
,09-13 16:33:29.111  6042  6091 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:EB:95:EE
09-13 16:33:29.111  6042  6091 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-13 16:33:29.111  6042  6091 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:33:29.111  6042  6091 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 16:33:29.111  6042  6091 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 16:33:29.111  6042  6091 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 16:33:29.111  6042  6091 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 16:33:29.111  6042  6091 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:78:3E:EB:95:EE
09-13 16:33:29.111  6042  6091 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 16:33:29.111  6042  6091 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 16:33:29.111  6042  6091 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 16:33:29.111  6042  6091 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 16:33:29.111  6042  6091 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 16:33:29.111  6042  6091 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 16:33:29.111  6042  6091 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 16:33:29.111  6042  6091 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 16:33:29.111  6042  6091 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 16:33:29.111  6042  6091 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-13 16:33:29.111  6042  6091 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eda641b added. We now have 1 listener(s)
09-13 16:33:29.111  6042  6091 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 16:33:29.111  6042  6091 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 16:33:29.111  6042  6091 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-13 16:33:29.111  6042  6091 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 16:33:29.111  6042  6091 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 16:33:29.111  6042  6091 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-13 16:33:29.111  6042  6091 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:33:29.111  6042  6091 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:EB:95:EE
,09-13 16:33:29.121  6042  6091 D BluetoothAdapter: STATE_ON
09-13 16:33:29.121  6042  6091 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-13 16:33:29.121  6042  6091 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:33:29.121  6042  6091 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:33:29.121  6042  6091 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:33:29.121  6042  6091 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:33:29.121  6042  6091 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:33:29.121  6042  6091 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:33:29.121  6042  6091 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:33:29.121  6042  6091 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:33:29.121  6042  6091 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 16:33:29.121  6042  6091 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:33:29.121  6042  6091 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 16:33:29.131  6042  6042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:33:29.131  6042  6042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:33:29.161  6042  6042 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 16:33:29.521  6042  6092 W jxcore-log: Initializing JXcore engine
09-13 16:33:29.521  6042  6092 W jxcore-log: JXcore engine is ready
,09-13 16:33:29.531  1798  1798 D Recents : onTaskStackChanged
,09-13 16:33:29.551  2616  2616 E audit   : type=1400 msg=audit(1473777209.551:271): avc:  denied  { ioctl } for  pid=6092 comm="Thread-112" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5531 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-13 16:33:29.551  2616  2616 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-13 16:33:29.551  2616  2616 E audit   : type=1300 msg=audit(1473777209.551:271): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=7 a1=5451 a2=3 a3=d8fde3c8 items=0 ppid=581 pid=6092 auid=4294967295 uid=10136 gid=10136 euid=10136 suid=10136 fsuid=10136 egid=10136 sgid=10136 fsgid=10136 ses=4294967295 tty=(none) comm="Thread-112" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-13 16:33:29.551  2616  2616 E audit   : type=1327 msg=audit(1473777209.551:271): proctitle="com.test.thalitest"
09-13 16:33:29.551  2616  2616 E audit   : type=1320 msg=audit(1473777209.551:271): 
09-13 16:33:29.551  2616  2616 E audit   : type=1400 msg=audit(1473777209.551:272): avc:  denied  { ioctl } for  pid=6092 comm="Thread-112" path="socket:[38883]" dev="sockfs" ino=38883 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-13 16:33:29.551  2616  2616 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-13 16:33:29.551  2616  2616 E audit   : type=1300 msg=audit(1473777209.551:272): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3c a1=5451 a2=3 a3=d8fde3c8 items=0 ppid=581 pid=6092 auid=4294967295 uid=10136 gid=10136 euid=10136 suid=10136 fsuid=10136 egid=10136 sgid=10136 fsgid=10136 ses=4294967295 tty=(none) comm="Thread-112" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-13 16:33:29.551  2616  2616 E audit   : type=1327 msg=audit(1473777209.551:272): proctitle="com.test.thalitest"
09-13 16:33:29.551  2616  2616 E audit   : type=1320 msg=audit(1473777209.551:272): 
,09-13 16:33:29.551  6042  6092 W jxcore-log: Starting JXcore engine
,09-13 16:33:29.611  6042  6092 W jxcore-log: Platform android
09-13 16:33:29.611  6042  6092 W jxcore-log: 
09-13 16:33:29.611  6042  6092 W jxcore-log: Process ARCH arm
09-13 16:33:29.611  6042  6092 W jxcore-log: 
,09-13 16:33:29.691  6042  6092 I jxcore-log: JXcore Cordova bridge is ready!
09-13 16:33:29.691  6042  6092 I jxcore-log: 
09-13 16:33:29.691  6042  6092 W jxcore-log: JXcore engine is started
,09-13 16:33:29.701  6042  6091 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-13 16:33:29.701  6042  6042 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 16:33:30.721  1158  1662 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/18_task.xml.bak
,09-13 16:33:31.091  1158  3556 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-13 16:33:32.101  1158  3586 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 16:33:33.561  3756  3756 D FactoryTest: User mode
,09-13 16:33:33.561  3756  3756 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
09-13 16:33:33.561  3756  3756 D MTPRx   : still no open session command from host, so toast
,09-13 16:33:33.571  1158  1269 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
09-13 16:33:33.571  1158  1269 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
09-13 16:33:33.571  1158  1269 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.samsung.android.MtpApplication)
,09-13 16:33:33.581  1158  1269 D ActivityManager: mDVFSHelper.acquire()
,09-13 16:33:33.581  1158  1269 V WindowManager: addAppToken: AppWindowToken{d09f0103f token=Token{69ee45e ActivityRecord{b80999 u0 com.samsung.android.MtpApplication/.USBConnection t19}}} to stack=2 task=19 at 0
,09-13 16:33:33.581  1158  1269 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,09-13 16:33:33.591  1158  1158 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
09-13 16:33:33.591  1158  1370 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,09-13 16:33:33.601  1158  1269 D InputDispatcher: Focused application set to: xxxx
,09-13 16:33:33.601  3756  3756 E MTPRx   : started activity for popup
,09-13 16:33:33.601  3756  3756 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-13 16:33:33.601  3756  3756 D RelationGraph: garbageCollect()
,09-13 16:33:33.611  1158  3556 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,09-13 16:33:33.621  3756  3756 D MTPUSBConnection: onCreate in USBConnection
09-13 16:33:33.621  3756  3756 V MTPUSBConnection: Registering broadcast receiver.
,09-13 16:33:33.621  3756  3756 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,09-13 16:33:33.621  1158  2592 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,09-13 16:33:33.661  3756  3756 D TAG     : dev.kiessupport is : TRUE
,09-13 16:33:33.681  3756  3756 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-13 16:33:33.691  3756  3756 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{49a2640 V.E...... R.....I. 0,0-0,0}
,09-13 16:33:33.691  3756  6094 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-13 16:33:33.701  3756  3756 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{b56e23b I.E...... R.....I. 0,0-0,0}
,09-13 16:33:33.701  1158  2657 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
09-13 16:33:33.701  1158  2657 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-13 16:33:33.701  1158  1158 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-13 16:33:33.711  1158  1158 I KnoxTimeoutHandler: Shared devices show user statefalse
09-13 16:33:33.711  1158  1158 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,09-13 16:33:33.731   445   445 I SurfaceFlinger: id=18 createSurf (97x97),1 flag=4, VSBConnecti
,09-13 16:33:33.741  3756  6094 I Adreno  : QUALCOMM build                   : 971aff5, Ic07f1cdce3
09-13 16:33:33.741  3756  6094 I Adreno  : Build Date                       : 03/29/16
09-13 16:33:33.741  3756  6094 I Adreno  : OpenGL ES Shader Compiler Version: XE031.06.00.02
09-13 16:33:33.741  3756  6094 I Adreno  : Local Branch                     : 
09-13 16:33:33.741  3756  6094 I Adreno  : Remote Branch                    : refs/tags/AU_LINUX_ANDROID_LA.BR.1.3.3.C2.06.00.01.205.077
09-13 16:33:33.741  3756  6094 I Adreno  : Remote Branch                    : NONE
09-13 16:33:33.741  3756  6094 I Adreno  : Reconstruct Branch               : NOTHING
,09-13 16:33:33.751  3756  6094 I OpenGLRenderer: Initialized EGL, version 1.4
,09-13 16:33:33.761   445   445 I SurfaceFlinger: id=19 createSurf (129x129),1 flag=4, VSBConnecti
,09-13 16:33:33.781  3756  3756 V ActivityThread: updateVisibility : ActivityRecord{646f96 token=android.os.BinderProxy@6fd4308 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,09-13 16:33:33.791  3756  6094 E libGLESv2: HWUI Protection: wrong call from hwui context F: ES3-glCreateProgramSEC
,09-13 16:33:33.801  3756  6094 E libGLESv2: HWUI Protection: wrong call from hwui context F: ES3-glCreateProgramSEC
,09-13 16:33:33.801  3756  6094 E libGLESv2: HWUI Protection: wrong call from hwui context F: ES3-glCreateProgramSEC
,09-13 16:33:33.811  1158  2459 V WindowStateAnimator: Finishing drawing window Window{a99c837 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-13 16:33:33.811  1158  2670 V WindowStateAnimator: Finishing drawing window Window{2e4b0d u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-13 16:33:33.811  3756  3756 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-13 16:33:33.811  3756  3756 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,09-13 16:33:33.821  1158  1414 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-13 16:33:33.821  1158  1158 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-13 16:33:33.821  1158  1414 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +223ms (total +236ms)
,09-13 16:33:33.821  1158  1158 I KnoxTimeoutHandler: SD activityfalse
09-13 16:33:33.821  1158  1414 D ActivityManager: mDVFSHelper.release()
09-13 16:33:33.821  1158  1414 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{b80999 u0 com.samsung.android.MtpApplication/.USBConnection t19} time:97862
,09-13 16:33:33.821  1158  1720 V WindowStateAnimator: Finishing drawing window Window{a99c837 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,09-13 16:33:33.821  1158  2632 V WindowStateAnimator: Finishing drawing window Window{2e4b0d u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,09-13 16:33:33.821  3756  3756 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@6fd4308 time:97865
,09-13 16:33:34.111  1158  3556 D SSRM:s  : SIOP:: AP = 360, PST = 378 (W:9), CP = 46, LCD = 0
,09-13 16:33:34.111  1158  3556 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 16:33:34.631  1158  2016 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 16:33:34.631  1158  2016 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4355, temperature: 314, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 16:33:34.631  1158  2016 D BatteryService: online:4, current avg:27, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-160
,09-13 16:33:34.631  1158  1158 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 16:33:34.641  1699  1699 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 16:33:34.641  1699  1699 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 16:33:34.641  1699  1699 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-13 16:33:34.641  2605  2605 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 16:33:34.641  2605  3148 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 16:33:34.641  1699  1699 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 16:33:34.641  1699  1699 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-13 16:33:34.661  1699  1699 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 16:33:34.711  1798  1798 D Recents : onTaskStackChanged
,09-13 16:33:34.721  1158  2016 D PackageManager: getComponentMetadataForIconTray : com.test.thalitest.MainActivity does not exist in mServices
09-13 16:33:34.721  1158  2016 D PackageManager: getComponentMetadataForIconTray : com.test.thalitest.MainActivity does not exist in mProviders
09-13 16:33:34.721  1158  2016 D PackageManager: getComponentMetadataForIconTray : com.test.thalitest.MainActivity does not exist in mReceivers
,09-13 16:33:34.721  1798  1798 I ApplicationPackageManager: load=com.test.thalitest, bg=96-96, dr=96-96
,09-13 16:33:34.721  1798  1798 I ApplicationPackageManager: scaled rate=0.98086953, size=96, alpha=2, hold=26, target=96
,09-13 16:33:35.291  6042  6092 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 16:33:35.291  6042  6092 I jxcore-log: 
,09-13 16:33:35.301  6042  6092 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 16:33:35.301  6042  6092 I jxcore-log: 
,09-13 16:33:35.301  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:35.311  6042  6092 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:33:35.311  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:33:35.311  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:33:35.311  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:33:35.311  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:33:35.311  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:33:35.311  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:33:35.311  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:33:35.311  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:35.321  6042  6092 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:33:35.321  6042  6092 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 16:33:35.321  6042  6092 I jxcore-log: 
,09-13 16:33:35.321  6042  6092 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 16:33:35.321  6042  6092 I jxcore-log: 
,09-13 16:33:35.651  6042  6092 I jxcore-log: Unit Test app is loaded
09-13 16:33:35.651  6042  6092 I jxcore-log: 
,09-13 16:33:35.651  6042  6092 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:33:35.651  6042  6092 I jxcore-log: 
,09-13 16:33:35.651  6042  6092 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 16:33:35.651  6042  6092 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d2936ca added. We now have 2 listener(s)
09-13 16:33:35.651  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-13 16:33:35.651  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:33:35.651  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 16:33:35.651  6042  6092 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 16:33:35.651  6042  6092 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37a103b added. We now have 2 listener(s)
09-13 16:33:35.651  6042  6092 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 16:33:35.651  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 16:33:35.661  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:33:35.671  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:35.671  6042  6092 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:33:35.671  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:33:35.671  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:33:35.671  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:33:35.671  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:33:35.671  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:33:35.671  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:33:35.671  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:33:35.681  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:35.681  6042  6092 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:33:35.681  6042  6092 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:33:35.681  6042  6092 D ExecuteNativeTests: Running unit tests
09-13 16:33:35.681  6042  6092 D BluetoothAdapter: enable()
,09-13 16:33:35.681  6042  6042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:33:35.681  6042  6042 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68),
,09-13 16:33:35.691  6042  6092 D BluetoothAdapter: enable(): BT is already enabled..!
09-13 16:33:35.691  1158  1370 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9018b09 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4927704 2639:com.samsung.android.providers.context/u0a5}
09-13 16:33:35.691  6042  6042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:33:35.691  6042  6092 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,09-13 16:33:35.691  1158  2632 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled,
09-13 16:33:35.691  1158  2632 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,09-13 16:33:35.701  1158  2632 D WifiService: System do NOT have com.sec.feature.sensorhub feature,
09-13 16:33:35.701  1158  2632 D WifiService: Wi-Fi on and Screen on , checkSensorStatus !!
09-13 16:33:35.701  1158  2632 W WifiService: Failed getting userId using ActivityManagerNative
09-13 16:33:35.701  1158  2632 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6042, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
09-13 16:33:35.701  1158  2632 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28130)
09-13 16:33:35.701  1158  2632 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2542)
09-13 16:33:35.701  1158  2632 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2530)
09-13 16:33:35.701  1158  2632 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
09-13 16:33:35.701  1158  2632 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
09-13 16:33:35.701  1158  2632 D WifiService: setWifiEnabled: true pid=6042, uid=10136
09-13 16:33:35.701  1158  1623 D WifiStateMachine: setFccChannel: channel = 0
,09-13 16:33:35.701  1158  2632 W ActivityManager: Permission Denial: getCurrentUser() from pid=6042, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
09-13 16:33:35.701  1158  1622 D WifiBigDataLog: getJsonFormat() - feature : ONOF
09-13 16:33:35.701  1158  2632 D SettingsProvider: isChangeAllowed() : name = wifi_on
09-13 16:33:35.701  1158  1623 D WifiController: [FCC]setFccChannel() is called !!!
,09-13 16:33:35.701  1158  1623 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
09-13 16:33:35.701  1158  1622 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.android.server.wifi.WifiStateMachine.insertLog:18843 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8707 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,09-13 16:33:35.701  1158  1622 D WifiBigDataLog: init : 
,09-13 16:33:35.701  6042  6092 I System.out: Running UT
,09-13 16:33:35.711  1158  1622 D WifiStateMachine: setFccChannelNative: channel = 0
09-13 16:33:35.711  1158  1622 D WifiNative-wlan0: callSECApiInt - ID [230]
09-13 16:33:35.711  1158  1370 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ffb210e u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4927704 2639:com.samsung.android.providers.context/u0a5}
,09-13 16:33:37.101  1158  3586 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 16:33:37.761  1158  1422 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,09-13 16:33:37.781  1158  1422 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak,
,09-13 16:33:43.651  1158  1834 E Watchdog: !@Sync 3 [09-13 16:33:43.652]
,09-13 16:33:44.091  1158  1589 V AlarmManager: Expired Alarm result :4
,09-13 16:33:44.091  1158  1370 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a9b113c u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{aad700d 1874:com.google.android.gms.persistent/u0a10}
,09-13 16:33:44.101  1158  2632 V AlarmManager:  remove PendingIntent] PendingIntent{3aecec5: PendingIntentRecord{b0e98d8 com.google.android.gms broadcastIntent}}
,09-13 16:33:44.141  1158  3556 D SSRM:s  : SIOP:: AP = 350, PST = 376 (W:10), CP = 42, LCD = 0
,09-13 16:33:44.141  1158  3556 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 16:33:44.201  1158  1268 V AlarmManager:  remove PendingIntent] PendingIntent{19b674b: PendingIntentRecord{b0e98d8 com.google.android.gms broadcastIntent}}
,09-13 16:33:44.381  1874  6100 I VacuumService: Vacuum at: now=1473777224387 tag=VacuumService
,09-13 16:33:44.451  1158  2016 V AlarmManager:  remove PendingIntent] PendingIntent{95e43e6: PendingIntentRecord{b0e98d8 com.google.android.gms broadcastIntent}}
,09-13 16:33:44.681  1158  2343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 16:33:44.681  1158  2343 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4390, temperature: 313, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 16:33:44.681  1158  2343 D BatteryService: online:4, current avg:3, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:160
09-13 16:33:44.681  1158  1158 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 16:33:44.691  1699  1699 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 16:33:44.691  1699  1699 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 16:33:44.691  1699  1699 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-13 16:33:44.691  2605  2605 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 16:33:44.691  2605  3148 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 16:33:44.711  1699  1699 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-13 16:33:44.711  1699  1699 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 16:33:44.711  1699  1699 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 16:33:45.761  6042  6092 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 16:33:45.761  6042  6092 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aaeb421 added. We now have 3 listener(s)
,09-13 16:33:45.761  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-13 16:33:45.761  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:33:45.761  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 16:33:45.761  6042  6092 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 16:33:45.761  6042  6092 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9caf046 added. We now have 3 listener(s)
09-13 16:33:45.761  6042  6092 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 16:33:45.771  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 16:33:45.771  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:33:45.781  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:45.781  6042  6092 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:33:45.781  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:33:45.781  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:33:45.781  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:33:45.781  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:33:45.781  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:33:45.781  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:33:45.781  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:33:45.791  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:45.791  6042  6092 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:33:45.791  6042  6092 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:33:45.791  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:45.801  6042  6042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:33:45.801  6042  6042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:33:45.801  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 16:33:45.801  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:33:45.801  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:33:45.801  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 16:33:45.801  6042  6092 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-13 16:33:45.801  6042  6092 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-13 16:33:45.801  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 16:33:45.801  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:33:45.801  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:33:45.801  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:33:45.801  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:45.801  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:45.801  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:33:45.801  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 16:33:45.801  6042  6092 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aaeb421 removed from the list
09-13 16:33:45.801  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:45.801  6042  6092 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9caf046 removed from the list
,09-13 16:33:45.801  6042  6092 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:45.801  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:33:45.801  6042  6092 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-13 16:33:45.811  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:45.811  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:45.811  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:45.811  6042  6092 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aaeb421 not in the list
09-13 16:33:45.811  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:45.811  6042  6092 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9caf046 not in the list
09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:45.811  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:45.811  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 16:33:45.811  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:45.811  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:45.811  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:45.811  6042  6092 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aaeb421 not in the list
,09-13 16:33:45.811  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:45.811  6042  6092 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9caf046 not in the list
09-13 16:33:45.811  6042  6092 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:45.811  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:45.811  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:45.811  6042  6092 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-13 16:33:45.811  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:33:45.821  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:45.831  6042  6092 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:33:45.831  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:33:45.831  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:33:45.831  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:33:45.831  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:33:45.831  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:33:45.831  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:33:45.831  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:33:45.831  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:45.831  6042  6092 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:33:45.831  6042  6092 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:33:45.831  6042  6092 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-13 16:33:45.831  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-13 16:33:45.831  6042  6092 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:33:45.831  6042  6092 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 16:33:45.831  6042  6092 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:33:45.831  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:33:45.841  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 16:33:45.841  6042  6092 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:33:45.841  6042  6092 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:33:45.841  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:33:45.841  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:33:45.841  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:33:45.841  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:33:45.841  6042  6042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:33:45.841  6042  6042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:33:45.841  6042  6042 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:33:45.841  6042  6101 D BluetoothSocket: bindListen(): myUserId = 0
09-13 16:33:45.841  6042  6101 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:33:45.841  6042  6092 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 16:33:45.841  6042  6092 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:33:45.851  6042  6101 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-13 16:33:45.851  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:45.851  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:45.851  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:45.861  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 16:33:45.861  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:45.861  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:45.861  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 16:33:45.861  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 16:33:45.871  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:45.871  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 16:33:45.871  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-13 16:33:45.871  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 44 78 3E EB 95 EE
09-13 16:33:45.871  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:33:45.871  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:33:45.871  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 16:33:45.871  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:45.871  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:45.871  6042  6092 D BluetoothLeAdvertiser: start advertising
09-13 16:33:45.871  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:45.881  2605  2626 D BtGatt.GattService: registerClient() - UUID=e00c5654-f444-4f24-8bde-50d2355ed195
,09-13 16:33:45.921  2605  2773 D BtGatt.GattService: onClientRegistered() - UUID=e00c5654-f444-4f24-8bde-50d2355ed195, clientIf=6
09-13 16:33:45.921  6042  6053 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 16:33:45.931  2605  3143 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
09-13 16:33:45.931  2605  3143 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:33:45.931  2605  3143 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:33:45.931  2605  2830 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-13 16:33:45.931  2605  2830 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
09-13 16:33:45.931  2605  2797 D BtGatt.AdvertiseManager: message : 0
09-13 16:33:45.941  2605  2797 D BtGatt.AdvertiseManager: number of adv instance running = 0
,09-13 16:33:45.941  2605  2797 D BtGatt.AdvertiseManager: size of list is =0
,09-13 16:33:45.941  2605  2797 D BtGatt.AdvertiseManager: starting advertising
,09-13 16:33:45.941  2605  2797 D BtGatt.AdvertiseManager: isStandardAdv = false,
,09-13 16:33:45.941  3053  3058 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
09-13 16:33:45.941  1158  2005 V AlarmManager:  remove PendingIntent] PendingIntent{863416c: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:45.951  2605  2830 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 32
,09-13 16:33:45.951  3053  3058 I WCNSS_FILTER: do_write: IBS write: fd
,09-13 16:33:45.961  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 28 : bytes_written: 28
09-13 16:33:45.961  3053  3053 I WCNSS_FILTER: do_write: IBS write: fc
09-13 16:33:45.961  2605  2830 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24562953
09-13 16:33:45.961  2605  2830 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-13 16:33:45.961  2605  2830 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,09-13 16:33:45.961  2605  2830 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-13 16:33:45.961  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 16:33:45.961  1158  2343 V AlarmManager:  remove PendingIntent] PendingIntent{5b9f335: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:45.961  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
,09-13 16:33:45.961  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-13 16:33:45.961  2605  2773 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
09-13 16:33:45.961  1158  2670 V AlarmManager:  remove PendingIntent] PendingIntent{844e3ca: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:45.961  2605  2797 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 16:33:45.961  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 38 : bytes_written: 38
09-13 16:33:45.971  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-13 16:33:45.971  2605  2773 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
09-13 16:33:45.971  2605  2797 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-13 16:33:45.971  2605  2797 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-13 16:33:45.971  2605  2797 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
09-13 16:33:45.971  1158  1269 V AlarmManager:  remove PendingIntent] PendingIntent{af8b93b: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:45.971  2605  2797 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
09-13 16:33:45.971  6042  6052 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
09-13 16:33:45.971  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 16:33:45.971  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:33:45.971  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:33:45.971  1158  2657 V AlarmManager:  remove PendingIntent] PendingIntent{2f90858: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}},
,09-13 16:33:45.971  6042  6092 I io.jxcore.node.ConnectionHelper: start: OK
09-13 16:33:45.971  6042  6042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:33:45.971  6042  6042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 16:33:45.971  6042  6042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 16:33:45.971  6042  6042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 16:33:45.971  6042  6042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 16:33:45.971  6042  6042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:33:45.971  1158  1721 V AlarmManager:  remove PendingIntent] PendingIntent{a38db1: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:45.981  6042  6042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 16:33:45.981  6042  6042 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:33:46.481  6042  6092 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 16:33:46.481  6042  6092 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-13 16:33:46.481  6042  6092 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-13 16:33:46.481  6042  6092 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-13 16:33:46.481  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:33:46.481  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:33:46.481  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 16:33:46.481  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 16:33:46.481  6042  6092 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:33:46.481  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 16:33:46.481  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:33:46.481  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 16:33:46.481  6042  6101 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 16:33:46.481  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:33:46.481  6042  6101 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:33:46.481  6042  6101 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 16:33:46.481  6042  6042 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-13 16:33:46.481  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 16:33:46.481  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:46.481  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:46.481  6042  6092 D BluetoothLeScanner: could not find callback wrapper
,09-13 16:33:46.481  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:33:46.481  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 16:33:46.481  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:46.481  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:46.481  6042  6092 D BluetoothLeAdvertiser: stop advertising
,09-13 16:33:46.491  2605  2626 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:33:46.491  2605  2626 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:33:46.491  2605  2797 D BtGatt.AdvertiseManager: message : 1
09-13 16:33:46.491  2605  2830 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
,09-13 16:33:46.491  2605  2830 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
09-13 16:33:46.491  2605  2830 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 16:33:46.491  2605  2797 D BtGatt.AdvertiseManager: stop advertise for client =  6
09-13 16:33:46.491  2605  2830 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-13 16:33:46.491  2605  2797 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
09-13 16:33:46.491  2605  2830 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
09-13 16:33:46.491  2605  2797 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-13 16:33:46.491  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
09-13 16:33:46.491  1158  1268 V AlarmManager:  remove PendingIntent] PendingIntent{2b57296: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:46.491  3053  3053 I WCNSS_FILTER: do_write: IBS write: fc
09-13 16:33:46.491  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-13 16:33:46.501  3053  3058 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 16:33:46.501  2605  2773 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-13 16:33:46.501  2605  2773 D BtGatt.GattService: Client app is not null!
,09-13 16:33:46.501  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
09-13 16:33:46.501  6042  6053 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
09-13 16:33:46.501  2605  3143 D BtGatt.GattService: unregisterClient() - clientIf=6
09-13 16:33:46.501  1158  1721 V AlarmManager:  remove PendingIntent] PendingIntent{62fae17: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:46.501  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 16:33:46.501  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 16:33:46.501  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 16:33:46.501  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 16:33:46.501  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 16:33:46.501  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:33:46.501  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 16:33:46.501  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:33:46.501  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:33:46.501  1158  2459 V AlarmManager:  remove PendingIntent] PendingIntent{6225204: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:46.511  6042  6042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 16:33:46.511  6042  6042 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-13 16:33:46.511  6042  6042 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:33:46.511  6042  6042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:33:46.511  6042  6042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:33:46.511  6042  6042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:33:46.511  6042  6042 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:33:46.511  6042  6092 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-13 16:33:46.511  6042  6092 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-13 16:33:46.511  6042  6092 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,09-13 16:33:46.511  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-13 16:33:46.511  6042  6092 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:33:46.511  6042  6092 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 16:33:46.511  6042  6092 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:33:46.511  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:33:46.511  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
09-13 16:33:46.511  1158  2632 V AlarmManager:  remove PendingIntent] PendingIntent{4b253ed: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:46.511  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-13 16:33:46.511  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 16:33:46.511  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 16:33:46.511  6042  6092 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:33:46.511  6042  6092 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:33:46.511  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:33:46.511  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:33:46.511  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:33:46.511  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:33:46.511  6042  6042 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 16:33:46.511  6042  6105 D BluetoothSocket: bindListen(): myUserId = 0
09-13 16:33:46.511  6042  6105 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:33:46.511  1158  1961 V AlarmManager:  remove PendingIntent] PendingIntent{bce2222: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:46.521  6042  6092 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 16:33:46.521  6042  6092 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:33:46.521  6042  6105 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-13 16:33:46.521  1158  2016 V AlarmManager:  remove PendingIntent] PendingIntent{ad03e6e: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:46.521  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:46.521  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:46.521  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:46.531  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:33:46.531  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:46.531  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:46.531  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 16:33:46.531  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:33:46.531  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:46.531  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 16:33:46.531  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:EB:95:EE"
,09-13 16:33:46.531  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 44 78 3E EB 95 EE
09-13 16:33:46.531  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:33:46.531  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:33:46.531  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 16:33:46.531  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:46.541  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:46.541  6042  6092 D BluetoothLeAdvertiser: start advertising
,09-13 16:33:46.541  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:46.541  2605  2626 D BtGatt.GattService: registerClient() - UUID=2ff6435e-f4dc-402d-9124-43557ac11788
,09-13 16:33:46.581  2605  2773 D BtGatt.GattService: onClientRegistered() - UUID=2ff6435e-f4dc-402d-9124-43557ac11788, clientIf=6,
09-13 16:33:46.581  6042  6052 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 16:33:46.581  2605  3165 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-13 16:33:46.591  2605  3165 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:33:46.591  2605  3165 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:33:46.591  2605  2830 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-13 16:33:46.591  2605  2797 D BtGatt.AdvertiseManager: message : 0
09-13 16:33:46.591  2605  2830 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
09-13 16:33:46.591  2605  2797 D BtGatt.AdvertiseManager: number of adv instance running = 0
09-13 16:33:46.591  2605  2797 D BtGatt.AdvertiseManager: size of list is =0
09-13 16:33:46.591  2605  2797 D BtGatt.AdvertiseManager: starting advertising
,09-13 16:33:46.591  2605  2797 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-13 16:33:46.591  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 28 : bytes_written: 28
09-13 16:33:46.591  3053  3053 I WCNSS_FILTER: do_write: IBS write: fc
09-13 16:33:46.591  1158  2459 V AlarmManager:  remove PendingIntent] PendingIntent{4c4490f: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:46.591  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 16:33:46.591  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
,09-13 16:33:46.591  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-13 16:33:46.591  2605  2773 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
09-13 16:33:46.601  2605  2830 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 33
09-13 16:33:46.601  2605  2830 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24562953
,09-13 16:33:46.601  2605  2830 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-13 16:33:46.601  2605  2830 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 16:33:46.601  1158  2592 V AlarmManager:  remove PendingIntent] PendingIntent{66fdd9c: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:46.601  2605  2830 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-13 16:33:46.601  2605  2797 D BtGatt.AdvertiseManager: starting multi advertising
09-13 16:33:46.601  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 38 : bytes_written: 38
,09-13 16:33:46.601  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 16:33:46.601  2605  2773 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-13 16:33:46.601  2605  2797 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-13 16:33:46.601  1158  1720 V AlarmManager:  remove PendingIntent] PendingIntent{5cf13a5: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:46.601  2605  2797 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-13 16:33:46.601  2605  2797 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
,09-13 16:33:46.601  2605  2797 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
09-13 16:33:46.601  6042  6053 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
09-13 16:33:46.601  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 16:33:46.601  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 16:33:46.601  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:33:46.601  6042  6092 I io.jxcore.node.ConnectionHelper: start: OK,
09-13 16:33:46.601  6042  6042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:33:46.601  1158  2016 V AlarmManager:  remove PendingIntent] PendingIntent{7c5d37a: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:46.601  6042  6042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 16:33:46.601  6042  6042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 16:33:46.601  6042  6042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 16:33:46.601  6042  6042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 16:33:46.601  6042  6042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:33:46.611  6042  6042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:33:46.611  6042  6042 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 16:33:46.611  1158  2657 V AlarmManager:  remove PendingIntent] PendingIntent{6672b: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:46.611  1158  2592 V AlarmManager:  remove PendingIntent] PendingIntent{c6b3788: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:47.111  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-13 16:33:47.111  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:33:47.111  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:33:47.111  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 16:33:47.111  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 16:33:47.111  6042  6092 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:33:47.111  6042  6092 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aaeb421 not in the list
09-13 16:33:47.111  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 16:33:47.111  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:33:47.111  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:33:47.111  6042  6105 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 16:33:47.111  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:33:47.111  6042  6105 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:33:47.111  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 16:33:47.111  6042  6105 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 16:33:47.111  6042  6042 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:33:47.111  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:47.111  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:47.111  6042  6092 D BluetoothLeScanner: could not find callback wrapper
09-13 16:33:47.111  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:33:47.111  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 16:33:47.111  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:47.111  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:47.111  6042  6092 D BluetoothLeAdvertiser: stop advertising
,09-13 16:33:47.111  2605  2626 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:33:47.121  2605  2626 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:33:47.121  2605  2797 D BtGatt.AdvertiseManager: message : 1
09-13 16:33:47.121  2605  2830 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
,09-13 16:33:47.121  2605  2830 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
09-13 16:33:47.121  2605  2830 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 16:33:47.121  2605  2830 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-13 16:33:47.121  2605  2830 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
09-13 16:33:47.121  2605  2797 D BtGatt.AdvertiseManager: stop advertise for client =  6
09-13 16:33:47.121  2605  2797 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
09-13 16:33:47.121  2605  2797 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-13 16:33:47.121  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
,09-13 16:33:47.121  1158  1269 V AlarmManager:  remove PendingIntent] PendingIntent{fc24521: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:47.121  3053  3053 I WCNSS_FILTER: do_write: IBS write: fc
,09-13 16:33:47.121  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 16:33:47.121  2605  2773 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-13 16:33:47.121  2605  2773 D BtGatt.GattService: Client app is not null!
09-13 16:33:47.121  6042  6052 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
09-13 16:33:47.121  3053  3058 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 16:33:47.121  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
09-13 16:33:47.121  2605  3165 D BtGatt.GattService: unregisterClient() - clientIf=6
09-13 16:33:47.121  1158  2592 V AlarmManager:  remove PendingIntent] PendingIntent{f4dad46: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:47.121  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 16:33:47.121  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 16:33:47.121  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 16:33:47.121  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 16:33:47.121  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 16:33:47.131  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:33:47.131  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 16:33:47.131  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:33:47.131  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:33:47.131  6042  6092 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9caf046 not in the list
,09-13 16:33:47.131  1158  1719 V AlarmManager:  remove PendingIntent] PendingIntent{9024b07: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:47.131  6042  6092 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:47.131  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.131  6042  6042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:33:47.131  6042  6042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:33:47.131  6042  6042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:33:47.131  6042  6042 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-13 16:33:47.131  6042  6042 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:33:47.131  6042  6092 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-13 16:33:47.131  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:33:47.141  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
09-13 16:33:47.141  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
,09-13 16:33:47.141  1158  2343 V AlarmManager:  remove PendingIntent] PendingIntent{6ee90a3: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:47.141  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-13 16:33:47.141  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:47.141  1158  2592 V AlarmManager:  remove PendingIntent] PendingIntent{4b76fa0: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:47.141  6042  6092 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:33:47.141  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:33:47.141  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:33:47.141  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:33:47.141  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:33:47.141  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:33:47.141  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:33:47.141  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:33:47.141  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:47.151  1158  2670 V AlarmManager:  remove PendingIntent] PendingIntent{bdd7759: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:47.151  6042  6092 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:33:47.151  6042  6092 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:33:47.151  6042  6092 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-13 16:33:47.151  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-13 16:33:47.151  6042  6092 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:33:47.151  6042  6092 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 16:33:47.151  6042  6092 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:33:47.151  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:33:47.151  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 16:33:47.151  6042  6092 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:33:47.151  6042  6092 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:33:47.151  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:33:47.151  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:33:47.151  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:33:47.151  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 16:33:47.151  6042  6108 D BluetoothSocket: bindListen(): myUserId = 0
,09-13 16:33:47.151  6042  6108 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 16:33:47.151  6042  6042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:33:47.151  6042  6092 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 16:33:47.151  6042  6092 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 16:33:47.161  6042  6108 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 16:33:47.161  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:47.161  6042  6042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:33:47.161  6042  6042 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:33:47.161  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:47.161  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:47.161  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:33:47.161  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:47.161  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:47.161  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 16:33:47.161  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:33:47.161  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:47.171  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 16:33:47.171  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:EB:95:EE"
,09-13 16:33:47.171  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 44 78 3E EB 95 EE
09-13 16:33:47.171  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:33:47.171  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:33:47.171  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 16:33:47.171  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:47.171  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:47.171  6042  6092 D BluetoothLeAdvertiser: start advertising
,09-13 16:33:47.171  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:47.171  2605  2634 D BtGatt.GattService: registerClient() - UUID=3fed7ae8-5d15-47bf-a22e-be49bcfbf6c2
,09-13 16:33:47.211  2605  2773 D BtGatt.GattService: onClientRegistered() - UUID=3fed7ae8-5d15-47bf-a22e-be49bcfbf6c2, clientIf=6
09-13 16:33:47.211  6042  6052 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 16:33:47.221  2605  3165 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-13 16:33:47.221  2605  3165 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:33:47.221  2605  3165 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:33:47.221  2605  2797 D BtGatt.AdvertiseManager: message : 0
09-13 16:33:47.221  2605  2797 D BtGatt.AdvertiseManager: number of adv instance running = 0
09-13 16:33:47.221  2605  2797 D BtGatt.AdvertiseManager: size of list is =0
09-13 16:33:47.221  2605  2830 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-13 16:33:47.221  2605  2830 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
09-13 16:33:47.221  2605  2797 D BtGatt.AdvertiseManager: starting advertising
,09-13 16:33:47.221  2605  2797 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-13 16:33:47.221  1158  1720 V AlarmManager:  remove PendingIntent] PendingIntent{8653015: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:47.231  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 28 : bytes_written: 28
,09-13 16:33:47.231  3053  3053 I WCNSS_FILTER: do_write: IBS write: fc
,09-13 16:33:47.231  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 16:33:47.231  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
,09-13 16:33:47.231  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 16:33:47.231  2605  2773 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-13 16:33:47.231  1158  1721 V AlarmManager:  remove PendingIntent] PendingIntent{cfa0f2a: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:47.231  2605  2797 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 16:33:47.231  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 38 : bytes_written: 38
09-13 16:33:47.231  2605  2830 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 34
09-13 16:33:47.231  2605  2830 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24562953
09-13 16:33:47.231  2605  2830 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-13 16:33:47.231  2605  2830 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 16:33:47.231  2605  2830 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
,09-13 16:33:47.231  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-13 16:33:47.231  2605  2773 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
09-13 16:33:47.231  2605  2797 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-13 16:33:47.231  2605  2797 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-13 16:33:47.231  1158  1268 V AlarmManager:  remove PendingIntent] PendingIntent{b93711b: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:47.231  2605  2797 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
09-13 16:33:47.231  2605  2797 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
09-13 16:33:47.231  6042  6053 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,09-13 16:33:47.231  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 16:33:47.231  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:33:47.241  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:33:47.241  6042  6092 I io.jxcore.node.ConnectionHelper: start: OK
09-13 16:33:47.241  1158  2343 V AlarmManager:  remove PendingIntent] PendingIntent{1f92b8: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:47.241  6042  6042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:33:47.241  6042  6042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 16:33:47.241  6042  6042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 16:33:47.241  6042  6042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 16:33:47.241  6042  6042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 16:33:47.241  6042  6042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:33:47.241  6042  6042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:33:47.241  6042  6042 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 16:33:47.241  1158  2459 V AlarmManager:  remove PendingIntent] PendingIntent{e75b891: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:47.251  1158  2016 V AlarmManager:  remove PendingIntent] PendingIntent{781f3f6: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:47.741  6042  6092 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 16:33:47.741  6042  6092 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 16:33:47.741  6042  6092 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-13 16:33:47.741  6042  6092 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 16:33:47.741  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:33:47.741  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:33:47.741  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 16:33:47.741  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 16:33:47.741  6042  6108 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 16:33:47.741  6042  6108 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:33:47.741  6042  6092 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:33:47.741  6042  6108 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true,
09-13 16:33:47.741  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 16:33:47.741  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:33:47.741  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:33:47.741  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 16:33:47.741  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 16:33:47.741  6042  6042 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:33:47.741  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:47.741  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:47.741  6042  6092 D BluetoothLeScanner: could not find callback wrapper
09-13 16:33:47.741  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 16:33:47.741  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 16:33:47.741  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:47.741  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:47.741  6042  6092 D BluetoothLeAdvertiser: stop advertising
,09-13 16:33:47.751  2605  3165 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 16:33:47.751  2605  3165 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:33:47.751  2605  2797 D BtGatt.AdvertiseManager: message : 1
09-13 16:33:47.751  2605  2830 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
09-13 16:33:47.751  2605  2830 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
09-13 16:33:47.751  2605  2830 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 16:33:47.751  2605  2830 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-13 16:33:47.751  2605  2830 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
09-13 16:33:47.751  2605  2797 D BtGatt.AdvertiseManager: stop advertise for client =  6
09-13 16:33:47.751  2605  2797 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
09-13 16:33:47.751  1158  1719 V AlarmManager:  remove PendingIntent] PendingIntent{ee03f7: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:47.751  2605  2797 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
09-13 16:33:47.751  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
,09-13 16:33:47.761  3053  3053 I WCNSS_FILTER: do_write: IBS write: fc
,09-13 16:33:47.761  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 16:33:47.761  2605  2773 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-13 16:33:47.761  2605  2773 D BtGatt.GattService: Client app is not null!
09-13 16:33:47.761  3053  3058 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0,
09-13 16:33:47.761  1158  2016 V AlarmManager:  remove PendingIntent] PendingIntent{2972264: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:47.761  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
09-13 16:33:47.761  6042  6052 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
09-13 16:33:47.761  2605  3143 D BtGatt.GattService: unregisterClient() - clientIf=6
09-13 16:33:47.761  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 16:33:47.761  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 16:33:47.761  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 16:33:47.761  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-13 16:33:47.761  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-13 16:33:47.761  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:33:47.761  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 16:33:47.761  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:33:47.761  1158  2592 V AlarmManager:  remove PendingIntent] PendingIntent{42c4ccd: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:47.761  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:33:47.761  6042  6042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 16:33:47.761  6042  6042 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-13 16:33:47.761  6042  6042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:33:47.771  6042  6042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:33:47.771  6042  6042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:33:47.771  6042  6042 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-13 16:33:47.771  6042  6042 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:33:47.771  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:47.771  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.771  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:33:47.771  6042  6092 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aaeb421 not in the list
09-13 16:33:47.771  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:47.771  6042  6092 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9caf046 not in the list
09-13 16:33:47.771  6042  6092 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:47.771  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:33:47.771  6042  6092 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-13 16:33:47.771  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:47.771  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.771  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.771  6042  6092 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aaeb421 not in the list
,09-13 16:33:47.771  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:47.771  6042  6092 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9caf046 not in the list
09-13 16:33:47.771  6042  6092 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:47.771  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.771  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.771  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
,09-13 16:33:47.771  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-13 16:33:47.771  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 16:33:47.771  1158  2657 V AlarmManager:  remove PendingIntent] PendingIntent{9d15982: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:47.771  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:47.771  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.771  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.771  6042  6092 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aaeb421 not in the list
09-13 16:33:47.771  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:47.771  6042  6092 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9caf046 not in the list
09-13 16:33:47.771  6042  6092 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 16:33:47.771  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.771  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.771  6042  6092 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-13 16:33:47.771  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:47.771  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.771  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.771  6042  6092 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aaeb421 not in the list
09-13 16:33:47.771  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:47.771  6042  6092 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9caf046 not in the list
09-13 16:33:47.771  6042  6092 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:47.771  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.771  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.771  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 16:33:47.771  6042  6092 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-13 16:33:47.771  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:47.771  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.771  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.771  6042  6092 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aaeb421 not in the list
09-13 16:33:47.771  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:47.771  6042  6092 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9caf046 not in the list
09-13 16:33:47.771  6042  6092 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:47.771  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.771  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.771  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 16:33:47.771  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:33:47.771  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:33:47.771  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 16:33:47.771  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsec,ureRfcommSocketPort: 1 -> -1
09-13 16:33:47.771  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:33:47.771  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 16:33:47.771  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:33:47.771  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:33:47.771  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:47.771  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.771  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.771  6042  6092 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aaeb421 not in the list
09-13 16:33:47.781  1158  2016 V AlarmManager:  remove PendingIntent] PendingIntent{3f4e893: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:47.771  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:47.771  6042  6092 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9caf046 not in the list
09-13 16:33:47.771  6042  6092 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:47.771  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.771  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.781  6042  6092 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:33:47.781  6042  6092 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-13 16:33:47.781  1158  2670 V AlarmManager:  remove PendingIntent] PendingIntent{2d600d0: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:47.781  6042  6092 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:33:47.781  6042  6092 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-13 16:33:47.781  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 16:33:47.781  6042  6092 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 16:33:47.781  6042  6092 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 16:33:47.781  6042  6092 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 16:33:47.781  6042  6092 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:33:47.781  6042  6092 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 16:33:47.781  6042  6092 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 16:33:47.781  6042  6092 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:33:47.781  6042  6092 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 16:33:47.781  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-13 16:33:47.791  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-13 16:33:47.791  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-13 16:33:47.791  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-13 16:33:47.791  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 16:33:47.791  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 16:33:47.791  6042  6092 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 16:33:47.791  6042  6092 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:33:47.791  6042  6092 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-13 16:33:47.791  6042  6112 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 213)
,09-13 16:33:47.791  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:47.791  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.791  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.791  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-13 16:33:47.791  6042  6092 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aaeb421 not in the list
09-13 16:33:47.791  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 16:33:47.791  6042  6092 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9caf046 not in the list
09-13 16:33:47.791  6042  6092 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:47.791  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.791  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.801  6042  6113 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 213
,09-13 16:33:47.801  6042  6092 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-13 16:33:47.801  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:47.801  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.801  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.801  6042  6092 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aaeb421 not in the list
09-13 16:33:47.801  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:47.801  6042  6092 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9caf046 not in the list
09-13 16:33:47.801  6042  6092 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:47.801  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.801  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:33:47.801  6042  6092 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,09-13 16:33:47.801  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:47.801  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.801  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.801  6042  6092 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aaeb421 not in the list
09-13 16:33:47.801  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:47.801  6042  6092 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9caf046 not in the list
,09-13 16:33:47.801  6042  6092 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:47.801  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.801  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.801  6042  6092 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-13 16:33:47.801  6042  6092 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 16:33:47.801  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 16:33:47.801  6042  6092 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 16:33:47.801  6042  6092 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 16:33:47.801  6042  6092 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 16:33:47.801  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 16:33:47.801  6042  6092 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 16:33:47.801  6042  6092 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 16:33:47.801  6042  6092 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 16:33:47.801  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 16:33:47.801  6042  6092 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 16:33:47.801  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:47.801  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.801  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.801  6042  6092 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aaeb421 not in the list
09-13 16:33:47.801  6042  6112 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-13 16:33:47.801  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:47.801  6042  6092 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9caf046 not in the list
09-13 16:33:47.801  6042  6092 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:47.801  6042  6112 D BluetoothSocket: connect(): myUserId = 0
09-13 16:33:47.801  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.801  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.801  6042  6112 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:33:47.801  6042  6092 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-13 16:33:47.811  6042  609,2 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:33:47.811  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:47.811  1158  1961 D SecContentProvider: insert(), uri = 2
,09-13 16:33:47.821  2605  3097 W bt_btif : bta_dm_acl_change(), event : 2
09-13 16:33:47.821  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 17 : bytes_written: 17
09-13 16:33:47.821  1158  2016 V AlarmManager:  remove PendingIntent] PendingIntent{5e259fc: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:47.821  3053  3053 I WCNSS_FILTER: do_write: IBS write: fc
,09-13 16:33:47.821  6042  6092 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:33:47.821  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:33:47.821  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:33:47.821  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:33:47.821  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:33:47.821  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:33:47.821  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:33:47.821  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:33:47.821  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,09-13 16:33:47.821  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:47.821  1158  2603 V AlarmManager:  remove PendingIntent] PendingIntent{db34885: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:47.821  6042  6092 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:33:47.821  6042  6092 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:33:47.821  6042  6092 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
,09-13 16:33:47.821  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-13 16:33:47.821  6042  6092 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:33:47.821  6042  6092 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 16:33:47.821  6042  6092 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:33:47.821  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:33:47.831  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 16:33:47.831  6042  6092 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:33:47.831  6042  6092 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 16:33:47.831  1158  1719 V AlarmManager:  remove PendingIntent] PendingIntent{14c96da: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:47.831  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:33:47.831  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:33:47.831  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:33:47.831  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
09-13 16:33:47.831  6042  6114 D BluetoothSocket: bindListen(): myUserId = 0
09-13 16:33:47.831  6042  6114 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:33:47.831  6042  6042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:33:47.831  6042  6114 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 16:33:47.831  6042  6092 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 16:33:47.831  6042  6092 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 16:33:47.841  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:47.841  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:47.841  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:47.841  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:33:47.841  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:47.841  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:47.841  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 16:33:47.841  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 16:33:47.841  6042  6042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:33:47.841  6042  6042 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 16:33:47.841  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:47.841  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 16:33:47.841  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-13 16:33:47.841  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 44 78 3E EB 95 EE
,09-13 16:33:47.841  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:33:47.841  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:33:47.841  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 16:33:47.851  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:47.851  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:47.851  6042  6092 D BluetoothLeAdvertiser: start advertising
,09-13 16:33:47.851  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:47.851  2605  3143 D BtGatt.GattService: registerClient() - UUID=ad651242-2548-488c-9aba-916ade5182de
,09-13 16:33:47.891  2605  2773 D BtGatt.GattService: onClientRegistered() - UUID=ad651242-2548-488c-9aba-916ade5182de, clientIf=6
,09-13 16:33:47.891  6042  6052 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 16:33:47.891  2605  2626 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-13 16:33:47.891  2605  2626 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:33:47.891  2605  2626 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 16:33:47.901  2605  2830 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-13 16:33:47.901  2605  2830 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
09-13 16:33:47.901  2605  2797 D BtGatt.AdvertiseManager: message : 0
09-13 16:33:47.901  2605  2797 D BtGatt.AdvertiseManager: number of adv instance running = 0
,09-13 16:33:47.901  2605  2797 D BtGatt.AdvertiseManager: size of list is =0
,09-13 16:33:47.901  2605  2797 D BtGatt.AdvertiseManager: starting advertising
,09-13 16:33:47.901  2605  2797 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-13 16:33:47.901  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 28 : bytes_written: 28
09-13 16:33:47.901  1158  1721 V AlarmManager:  remove PendingIntent] PendingIntent{6d46a6: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:47.901  2605  2830 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 35
09-13 16:33:47.901  2605  2830 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24562953
09-13 16:33:47.901  2605  2830 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-13 16:33:47.901  2605  2830 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 16:33:47.901  2605  2830 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-13 16:33:47.901  3053  3053 I WCNSS_FILTER: do_write: IBS write: fc
09-13 16:33:47.901  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-13 16:33:47.901  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
,09-13 16:33:47.911  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-13 16:33:47.911  2605  2773 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
09-13 16:33:47.911  1158  2632 V AlarmManager:  remove PendingIntent] PendingIntent{471d8e7: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:47.911  2605  2797 D BtGatt.AdvertiseManager: starting multi advertising
09-13 16:33:47.911  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 38 : bytes_written: 38
,09-13 16:33:47.911  2605  2773 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
09-13 16:33:47.911  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 16:33:47.911  2605  2797 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-13 16:33:47.911  2605  2797 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-13 16:33:47.911  2605  2797 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
09-13 16:33:47.911  1158  1720 V AlarmManager:  remove PendingIntent] PendingIntent{e39ec94: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:47.911  2605  2797 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
09-13 16:33:47.911  6042  6053 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
09-13 16:33:47.911  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 16:33:47.911  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:33:47.911  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:33:47.921  6042  6092 I io.jxcore.node.ConnectionHelper: start: OK
09-13 16:33:47.921  6042  6042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:33:47.921  1158  1721 V AlarmManager:  remove PendingIntent] PendingIntent{337033d: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:47.921  6042  6042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 16:33:47.921  6042  6042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 16:33:47.921  6042  6042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 16:33:47.921  6042  6042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 16:33:47.921  6042  6042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:33:47.921  6042  6042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:33:47.921  6042  6042 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 16:33:47.921  1158  2592 V AlarmManager:  remove PendingIntent] PendingIntent{f972732: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:47.931  1158  1969 V AlarmManager:  remove PendingIntent] PendingIntent{3f91c83: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:48.421  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:33:48.421  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:33:48.421  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:33:48.421  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 16:33:48.421  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 16:33:48.421  6042  6092 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:33:48.421  6042  6092 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aaeb421 not in the list
09-13 16:33:48.421  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:48.421  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:33:48.421  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:33:48.421  6042  6114 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 16:33:48.421  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:33:48.421  6042  6114 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:33:48.421  6042  6114 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 16:33:48.421  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 16:33:48.421  6042  6042 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:33:48.421  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:48.421  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:48.421  6042  6092 D BluetoothLeScanner: could not find callback wrapper
09-13 16:33:48.421  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:33:48.421  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 16:33:48.421  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:48.431  6042  6092 D BluetoothAdapter: STATE_ON,
09-13 16:33:48.431  6042  6092 D BluetoothLeAdvertiser: stop advertising
,09-13 16:33:48.431  2605  3143 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:33:48.431  2605  3143 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:33:48.431  2605  2830 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
,09-13 16:33:48.431  2605  2830 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
09-13 16:33:48.431  2605  2830 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 16:33:48.431  2605  2830 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-13 16:33:48.431  2605  2830 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
09-13 16:33:48.431  2605  2797 D BtGatt.AdvertiseManager: message : 1
09-13 16:33:48.431  2605  2797 D BtGatt.AdvertiseManager: stop advertise for client =  6
09-13 16:33:48.431  2605  2797 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
09-13 16:33:48.431  2605  2797 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-13 16:33:48.441  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
09-13 16:33:48.441  1158  1719 V AlarmManager:  remove PendingIntent] PendingIntent{8133e00: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:48.441  3053  3053 I WCNSS_FILTER: do_write: IBS write: fc
,09-13 16:33:48.441  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8,
09-13 16:33:48.441  2605  2773 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-13 16:33:48.441  1158  1720 V AlarmManager:  remove PendingIntent] PendingIntent{1159639: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:48.441  2605  2773 D BtGatt.GattService: Client app is not null!,
09-13 16:33:48.441  3053  3058 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 16:33:48.441  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
09-13 16:33:48.441  6042  6052 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,09-13 16:33:48.441  2605  2626 D BtGatt.GattService: unregisterClient() - clientIf=6
09-13 16:33:48.441  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 16:33:48.441  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 16:33:48.441  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 16:33:48.441  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 16:33:48.441  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-13 16:33:48.451  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:33:48.451  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 16:33:48.451  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:33:48.451  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:33:48.451  1158  2632 V AlarmManager:  remove PendingIntent] PendingIntent{30c847e: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:48.451  6042  6092 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9caf046 not in the list
09-13 16:33:48.451  6042  6092 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:48.451  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:48.451  6042  6042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:33:48.451  6042  6042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:33:48.451  6042  6042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:33:48.451  6042  6042 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 16:33:48.451  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:48.451  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:48.451  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:48.451  6042  6042 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:33:48.451  6042  6092 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aaeb421 not in the list
09-13 16:33:48.451  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:48.451  6042  6092 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9caf046 not in the list
09-13 16:33:48.451  6042  6092 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:48.451  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:48.451  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:48.451  6042  6092 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:33:48.451  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:33:48.451  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 16:33:48.451  6042  6092 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:33:48.451  6042  6092 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:33:48.451  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:33:48.451  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 16:33:48.461  6042  6042 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:33:48.461  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:48.461  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:33:48.461  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:33:48.461  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 16:33:48.461  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:48.461  6042  6092 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:33:48.461  6042  6118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:33:48.461  6042  6118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 16:33:48.461  6042  6092 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aaeb421 not in the list
09-13 16:33:48.461  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:48.461  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:33:48.461  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:33:48.461  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:33:48.461  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:48.461  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:33:48.461  6042  6042 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:33:48.461  6042  6042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:33:48.461  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
09-13 16:33:48.461  1158  1268 V AlarmManager:  remove PendingIntent] PendingIntent{426fddf: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:48.461  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-13 16:33:48.461  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:33:48.461  6042  6092 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9caf046 not in the list
09-13 16:33:48.461  6042  6092 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:48.461  6042  6042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:33:48.461  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:48.461  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:48.461  6042  6042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:33:48.461  6042  6042 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:33:48.461  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 16:33:48.461  6042  6092 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-13 16:33:48.461  6042  6092 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 16:33:48.461  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-13 16:33:48.461  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:33:48.461  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:33:48.461  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:48.461  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:48.461  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:48.461  6042  6092 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aaeb421 not in the list
09-13 16:33:48.461  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:48.461  6042  6092 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9caf046 not in the list
,09-13 16:33:48.461  6042  6092 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:48.461  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:48.461  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:33:48.461  1158  2603 V AlarmManager:  remove PendingIntent] PendingIntent{f6e3a2c: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:48.471  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:48.471  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:48.471  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:48.471  6042  6092 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aaeb421 not in the list
09-13 16:33:48.471  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:48.471  6042  6092 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9caf046 not in the list
09-13 16:33:48.471  6042  6092 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 16:33:48.471  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:48.471  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:48.471  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:48.471  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:48.471  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:48.471  6042  6092 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aaeb421 not in the list
09-13 16:33:48.471  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:48.471  6042  6092 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9caf046 not in the list
09-13 16:33:48.471  6042  6092 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:48.471  1158  2592 V AlarmManager:  remove PendingIntent] PendingIntent{1b05cf5: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:48.471  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:48.471  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:48.471  6042  6092 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-13 16:33:48.471  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 16:33:48.471  6042  6092 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-13 16:33:48.471  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 16:33:48.471  6042  6092 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 16:33:48.471  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-13 16:33:48.471  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 16:33:48.471  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-13 16:33:48.471  6042  6092 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-13 16:33:48.471  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 16:33:48.471  6042  6092 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-13 16:33:48.471  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-13 16:33:48.471  6042  6092 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-13 16:33:48.471  6042  6092 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-13 16:33:48.471  6042  6092 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-13 16:33:48.471  6042  6092 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-13 16:33:48.471  6042  6092 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,09-13 16:33:48.471  6042  6092 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 16:33:48.471  6042  6092 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-13 16:33:48.471  6042  6092 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-13 16:33:48.481  6042  6119 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-13 16:33:48.481  6042  6119 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 16:33:48.961  6042  6042 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 16:33:48.991   553  1407 D EnterpriseController: netId is 0
,09-13 16:33:48.991   553  1407 D Netd    : getNetworkForDns: using netid 502 for uid 10136
,09-13 16:33:49.001  6042  6119 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-13 16:33:49.001  6042  6121 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-13 16:33:49.001  6042  6121 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 16:33:49.001  6042  6119 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 16:33:49.001  6042  6121 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:33:49.001  6042  6119 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:33:49.001  6042  6121 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:33:49.001  6042  6119 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:33:49.001  6042  6124 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 267, name: OutgoingSocketThread/Sender)
09-13 16:33:49.001  6042  6121 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 16:33:49.001  6042  6119 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-13 16:33:49.001  6042  6125 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 266, name: IncomingSocketThread/Sender)
,09-13 16:33:49.001  6042  6127 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 269, name: OutgoingSocketThread/Receiver)
09-13 16:33:49.001  6042  6126 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 268, name: IncomingSocketThread/Receiver)
09-13 16:33:49.001  6042  6127 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 269, thread name: OutgoingSocketThread/Receiver)
09-13 16:33:49.001  6042  6127 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 16:33:49.001  6042  6127 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 269, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-13 16:33:49.001  6042  6126 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 268, thread name: IncomingSocketThread/Receiver)
09-13 16:33:49.001  6042  6126 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 16:33:49.001  6042  6126 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 268, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-13 16:33:49.461  3053  3107 I WCNSS_FILTER: do_write: IBS write: fe
09-13 16:33:49.461  3053  3107 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-13 16:33:49.491  6042  6092 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-13 16:33:49.491  6042  6092 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-13 16:33:49.491  6042  6092 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@4ee6122 Bundle[{}]
,09-13 16:33:49.491  6042  6092 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 16:33:49.491  6042  6092 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-13 16:33:49.491  6042  6092 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-13 16:33:49.491  6042  6092 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-13 16:33:49.491  6042  6092 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-13 16:33:49.491  6042  6092 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 16:33:49.501  6042  6128 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-13 16:33:49.501  6042  6128 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 16:33:49.711   716   716 I MSM-irqbalance: Decided to move IRQ200 from CPU0 to CPU1
,09-13 16:33:50.011  6042  6130 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-13 16:33:50.011  6042  6130 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 16:33:50.011  6042  6130 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:33:50.011  6042  6128 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-13 16:33:50.011  6042  6128 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 16:33:50.011  6042  6128 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:33:50.011  6042  6128 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:33:50.011  6042  6130 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:33:50.011  6042  6130 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 16:33:50.011  6042  6128 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-13 16:33:50.011  6042  6132 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 280, name: IncomingSocketThread/Sender)
,09-13 16:33:50.011  6042  6133 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 281, name: OutgoingSocketThread/Sender)
09-13 16:33:50.011  6042  6134 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 283, name: IncomingSocketThread/Receiver)
,09-13 16:33:50.011  6042  6134 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 283, thread name: IncomingSocketThread/Receiver)
09-13 16:33:50.011  6042  6135 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 282, name: OutgoingSocketThread/Receiver)
09-13 16:33:50.011  6042  6134 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 16:33:50.011  6042  6134 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 283, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-13 16:33:50.011  6042  6135 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 282, thread name: OutgoingSocketThread/Receiver)
09-13 16:33:50.011  6042  6135 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 16:33:50.011  6042  6135 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 282, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-13 16:33:50.511  6042  6092 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 292)
09-13 16:33:50.511  6042  6092 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-13 16:33:50.511  6042  6092 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 293)
09-13 16:33:50.511  6042  6092 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 16:33:50.511  6042  6092 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31d4af7 added. We now have 3 listener(s)
09-13 16:33:50.511  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-13 16:33:50.511  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 16:33:50.511  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 16:33:50.511  6042  6092 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 16:33:50.511  6042  6092 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a5d64 added. We now have 3 listener(s)
,09-13 16:33:50.511  6042  6092 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 16:33:50.521  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 16:33:50.521  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:33:50.531  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:50.531  6042  6092 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:33:50.531  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:33:50.531  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:33:50.531  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:33:50.531  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:33:50.531  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:33:50.531  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:33:50.531  6042  6092 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:33:50.531  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:50.531  6042  6092 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:33:50.531  6042  6092 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:33:50.541  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:50.541  6042  6042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:33:50.541  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:50.541  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:50.541  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:33:50.541  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 16:33:50.541  6042  6092 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31d4af7 removed from the list
09-13 16:33:50.541  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:50.541  6042  6092 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a5d64 removed from the list
,09-13 16:33:50.541  6042  6042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:33:50.541  6042  6092 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:50.541  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:33:50.541  6042  6092 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-13 16:33:50.541  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
09-13 16:33:50.541  6042  6092 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:33:50.541  6042  6092 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 16:33:50.541  6042  6092 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:33:50.541  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:33:50.541  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 16:33:50.541  6042  6092 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:33:50.541  6042  6092 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:33:50.541  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:33:50.541  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:33:50.541  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:33:50.541  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 16:33:50.551  6042  6042 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 16:33:50.551  6042  6136 D BluetoothSocket: bindListen(): myUserId = 0
,09-13 16:33:50.551  6042  6136 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 16:33:50.551  6042  6092 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 16:33:50.551  6042  6092 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:33:50.551  6042  6136 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 16:33:50.551  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:50.551  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:50.551  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:50.561  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:33:50.561  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:50.561  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:50.561  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 16:33:50.561  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:33:50.561  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:50.561  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 16:33:50.561  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-13 16:33:50.561  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 44 78 3E EB 95 EE
09-13 16:33:50.561  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:33:50.561  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:33:50.561  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 16:33:50.561  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:50.561  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:50.561  6042  6092 D BluetoothLeAdvertiser: start advertising
,09-13 16:33:50.561  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:50.571  2605  3165 D BtGatt.GattService: registerClient() - UUID=81674d8b-0a73-424d-a617-e3bdb7759568
,09-13 16:33:50.611  2605  2773 D BtGatt.GattService: onClientRegistered() - UUID=81674d8b-0a73-424d-a617-e3bdb7759568, clientIf=6
09-13 16:33:50.611  6042  6052 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6,
,09-13 16:33:50.611  2605  3143 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-13 16:33:50.611  2605  3143 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:33:50.611  2605  3143 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:33:50.611  2605  2830 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-13 16:33:50.611  2605  2830 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
,09-13 16:33:50.611  2605  2797 D BtGatt.AdvertiseManager: message : 0
,09-13 16:33:50.621  2605  2797 D BtGatt.AdvertiseManager: number of adv instance running = 0
09-13 16:33:50.621  2605  2797 D BtGatt.AdvertiseManager: size of list is =0
,09-13 16:33:50.621  2605  2797 D BtGatt.AdvertiseManager: starting advertising,
09-13 16:33:50.621  2605  2797 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-13 16:33:50.621  3053  3058 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
09-13 16:33:50.621  1158  1721 V AlarmManager:  remove PendingIntent] PendingIntent{afba2c4: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:50.621  3053  3058 I WCNSS_FILTER: do_write: IBS write: fd
09-13 16:33:50.621  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 28 : bytes_written: 28
09-13 16:33:50.621  3053  3053 I WCNSS_FILTER: do_write: IBS write: fc
,09-13 16:33:50.621  2605  2830 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 36
09-13 16:33:50.621  2605  2830 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24562953
09-13 16:33:50.621  2605  2830 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-13 16:33:50.621  2605  2830 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 16:33:50.621  2605  2830 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-13 16:33:50.631  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 16:33:50.631  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
09-13 16:33:50.631  1158  1269 V AlarmManager:  remove PendingIntent] PendingIntent{5435ad: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:50.631  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 16:33:50.631  2605  2773 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-13 16:33:50.631  1158  2343 V AlarmManager:  remove PendingIntent] PendingIntent{d03c0e2: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:50.631  2605  2797 D BtGatt.AdvertiseManager: starting multi advertising
09-13 16:33:50.631  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 38 : bytes_written: 38
,09-13 16:33:50.631  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 16:33:50.631  2605  2773 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-13 16:33:50.631  2605  2797 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-13 16:33:50.631  2605  2797 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-13 16:33:50.631  2605  2797 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
09-13 16:33:50.631  2605  2797 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
09-13 16:33:50.631  1158  1969 V AlarmManager:  remove PendingIntent] PendingIntent{2a2c73: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:50.631  6042  6053 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
09-13 16:33:50.631  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 16:33:50.631  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:33:50.641  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:33:50.641  1158  1269 V AlarmManager:  remove PendingIntent] PendingIntent{f722730: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:50.641  6042  6042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:33:50.641  6042  6042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 16:33:50.641  6042  6042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 16:33:50.641  6042  6042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 16:33:50.641  6042  6042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 16:33:50.641  6042  6042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:33:50.641  1158  2005 V AlarmManager:  remove PendingIntent] PendingIntent{aab7fa9: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:50.641  6042  6042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 16:33:50.641  6042  6042 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:33:51.141  6042  6042 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-13 16:33:51.141  6042  6042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 16:33:51.141  6042  6042 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 16:33:51.631  3053  3107 I WCNSS_FILTER: do_write: IBS write: fe
,09-13 16:33:51.631  3053  3107 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-13 16:33:54.141  6042  6092 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-13 16:33:54.141  6042  6092 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 16:33:54.141  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:33:54.141  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:33:54.141  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 16:33:54.141  6042  6136 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 16:33:54.141  6042  6136 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:33:54.141  6042  6136 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 16:33:54.141  6042  6042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:33:54.141  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:33:54.141  6042  6092 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 16:33:54.141  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 16:33:54.141  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:33:54.141  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:33:54.141  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:33:54.141  6042  6042 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:33:54.141  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 16:33:54.141  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:54.151  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:54.151  6042  6092 D BluetoothLeScanner: could not find callback wrapper
09-13 16:33:54.151  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:33:54.151  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 16:33:54.151  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:54.151  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:54.151  6042  6092 D BluetoothLeAdvertiser: stop advertising
09-13 16:33:54.151  2605  3165 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 16:33:54.151  2605  3165 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:33:54.161  2605  2797 D BtGatt.AdvertiseManager: message : 1
09-13 16:33:54.161  2605  2830 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
09-13 16:33:54.161  2605  2830 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
09-13 16:33:54.161  2605  2830 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 16:33:54.161  2605  2830 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-13 16:33:54.161  2605  2830 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
09-13 16:33:54.161  2605  2797 D BtGatt.AdvertiseManager: stop advertise for client =  6
09-13 16:33:54.161  2605  2797 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
,09-13 16:33:54.161  2605  2797 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
09-13 16:33:54.161  3053  3058 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
09-13 16:33:54.161  1158  2603 V AlarmManager:  remove PendingIntent] PendingIntent{1a1092e: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:54.171  3053  3058 I WCNSS_FILTER: do_write: IBS write: fd
,09-13 16:33:54.171  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
,09-13 16:33:54.171  3053  3053 I WCNSS_FILTER: do_write: IBS write: fc
,09-13 16:33:54.171  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-13 16:33:54.171  2605  2773 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-13 16:33:54.171  2605  2773 D BtGatt.GattService: Client app is not null!
09-13 16:33:54.171  6042  6052 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
09-13 16:33:54.171  3053  3058 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 16:33:54.171  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
09-13 16:33:54.171  2605  3143 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 16:33:54.171  1158  2343 V AlarmManager:  remove PendingIntent] PendingIntent{9f11ccf: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:54.171  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 16:33:54.171  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 16:33:54.171  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 16:33:54.171  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 16:33:54.171  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-13 16:33:54.181  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:33:54.181  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 16:33:54.181  1158  2657 V AlarmManager:  remove PendingIntent] PendingIntent{98a865c: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:54.181  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:33:54.181  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:33:54.181  6042  6042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 16:33:54.181  6042  6042 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-13 16:33:54.181  6042  6042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:33:54.181  6042  6042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:33:54.181  6042  6042 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:33:54.181  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:54.181  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:54.181  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:54.181  6042  6092 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31d4af7 not in the list
09-13 16:33:54.181  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:54.181  1158  3556 D SSRM:s  : SIOP:: AP = 340, PST = 372 (W:11), CP = 40, LCD = 0
09-13 16:33:54.181  6042  6092 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a5d64 not in the list
09-13 16:33:54.181  6042  6092 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:54.181  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:54.181  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:54.181  1158  3556 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-13 16:33:54.181  6042  6092 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:33:54.181  6042  6092 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:33:54.181  6042  6092 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 16:33:54.181  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 16:33:54.181  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:33:54.181  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 16:33:54.191  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
09-13 16:33:54.191  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12,
09-13 16:33:54.191  6042  6092 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 16:33:54.191  6042  6092 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 16:33:54.191  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 16:33:54.191  1158  1720 V AlarmManager:  remove PendingIntent] PendingIntent{f67ac48: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:54.191  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:54.191  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:54.191  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:54.191  1158  2016 V AlarmManager:  remove PendingIntent] PendingIntent{d527ae1: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:54.201  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:33:54.201  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:54.201  1158  1720 V AlarmManager:  remove PendingIntent] PendingIntent{8951006: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:54.201  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:54.201  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 16:33:54.201  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:33:54.201  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:54.201  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:54.211  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-13 16:33:54.211  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:54.211  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:54.211  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-13 16:33:54.211  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 16:33:54.211  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-13 16:33:54.211  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 16:33:54.211  6042  6092 D BluetoothLeScanner: Start Scan
,09-13 16:33:54.221  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:54.221  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:54.221  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 14 : bytes_written: 14
09-13 16:33:54.221  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:54.221  2605  3097 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
09-13 16:33:54.221  2605  3097 E bt_btif_sock_rfcomm: SDP - Failed to look up a channel number to connect to
09-13 16:33:54.221  2605  3097 W bt_btif : bta_dm_acl_change(), event : 2
09-13 16:33:54.221  2605  3097 W bt_btif : bta_dm_acl_change(), event : 5
09-13 16:33:54.221  2605  3162 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 7
,09-13 16:33:54.221  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:54.221  1158  2670 V AlarmManager:  remove PendingIntent] PendingIntent{cfdd6c7: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:54.221  6042  6112 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 213)
,09-13 16:33:54.221  2605  3165 D BtGatt.GattService: registerClient() - UUID=d397af3e-a7c8-4578-9f7f-79c3b329d81e
,09-13 16:33:54.231  1158  1961 V AlarmManager:  remove PendingIntent] PendingIntent{46f44f4: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:54.231  2605  2768 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13d0a2f
,09-13 16:33:54.231  2605  2773 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 1
09-13 16:33:54.231  1158  1719 V AlarmManager:  remove PendingIntent] PendingIntent{31ae41d: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:54.231  2605  2773 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-13 16:33:54.231  2605  2773 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 241
09-13 16:33:54.231  1699  2093 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
,09-13 16:33:54.271  2605  2773 D BtGatt.GattService: onClientRegistered() - UUID=d397af3e-a7c8-4578-9f7f-79c3b329d81e, clientIf=6
,09-13 16:33:54.271  6042  6053 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-13 16:33:54.271  2605  2634 D BtGatt.GattService: start scan with filters
09-13 16:33:54.271  2605  2634 D BtGatt.GattService: getScanSettings,
,09-13 16:33:54.281  2605  2634 D BtGatt.GattService: Is it foreground application = false
09-13 16:33:54.281  2605  2634 D BtGatt.GattService: not a background application
,09-13 16:33:54.281  2605  2634 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-13 16:33:54.281  2605  2634 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:33:54.281  2605  2634 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:33:54.281  2605  2830 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
09-13 16:33:54.281  2605  2830 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
,09-13 16:33:54.281  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
09-13 16:33:54.291  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 16:33:54.291  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 16:33:54.291  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-13 16:33:54.291  2605  2812 D BtGatt.ScanManager: handling starting scan
09-13 16:33:54.291  2605  2812 D BtGatt.ScanManager: isFilteringSupported
09-13 16:33:54.291  2605  2812 D BluetoothAdapter: enableStandAloneBleMode=
09-13 16:33:54.291  2605  2812 D BluetoothAdapter: STATE_ON
,09-13 16:33:54.291  2605  2812 D BluetoothAdapter: STATE_ON
,09-13 16:33:54.291  2605  2812 D BluetoothAdapter: STATE_ON
09-13 16:33:54.291  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 16:33:54.291  2605  2812 D BluetoothAdapter: STATE_ON
09-13 16:33:54.291  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:33:54.291  6042  6042 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 16:33:54.291  2605  2812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13d0a2f
09-13 16:33:54.291  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-13 16:33:54.291  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
09-13 16:33:54.291  3053  3053 I WCNSS_FILTER: do_write: IBS write: fc
,09-13 16:33:54.291  1158  2016 V AlarmManager:  remove PendingIntent] PendingIntent{f622692: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:54.291  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 9 : bytes_written: 9
09-13 16:33:54.291  2605  2773 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-13 16:33:54.291  2605  2773 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 16:33:54.291  2605  2812 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
09-13 16:33:54.291  2605  2812 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-13 16:33:54.291  2605  2812 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-13 16:33:54.291  2605  2812 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
09-13 16:33:54.301  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 22 : bytes_written: 22,
,09-13 16:33:54.301  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 10 : bytes_written: 10
,09-13 16:33:54.301  2605  2773 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-13 16:33:54.301  2605  2773 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 16:33:54.301  2605  2830 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 54
09-13 16:33:54.301  2605  2830 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
,09-13 16:33:54.301  2605  2812 D BtGatt.ScanManager: Starting BLE batch scan
09-13 16:33:54.301  2605  2812 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-13 16:33:54.301  1158  1268 V AlarmManager:  remove PendingIntent] PendingIntent{b771863: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:54.301  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-13 16:33:54.301  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 16:33:54.301  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 8 : bytes_written: 8
09-13 16:33:54.301  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-13 16:33:54.301  2605  2773 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-13 16:33:54.301  2605  2773 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 16:33:54.311  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 16 : bytes_written: 16
09-13 16:33:54.311  1158  2343 V AlarmManager:  remove PendingIntent] PendingIntent{ab5bc60: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:54.311  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 16:33:54.311  2605  2773 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-13 16:33:54.311  2605  2773 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 16:33:54.311  1158  2459 V AlarmManager:  remove PendingIntent] PendingIntent{106a519: PendingIntentRecord{7819de com.android.bluetooth broadcastIntent}}
,09-13 16:33:54.311  2605  2830 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 626
,09-13 16:33:54.311  1158  1969 V AlarmManager:  remove PendingIntent] PendingIntent{ab8d7bf: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:54.311  1158  1961 V AlarmManager:  remove PendingIntent] PendingIntent{f2a3e8c: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:54.321  1158  1719 V AlarmManager:  remove PendingIntent] PendingIntent{5379d5: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:54.321  1158  2592 V AlarmManager:  remove PendingIntent] PendingIntent{267f5ea: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:54.321  2605  2830 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24562953
,09-13 16:33:54.321  2605  2830 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
09-13 16:33:54.321  2605  2830 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-13 16:33:54.321  2605  2830 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-13 16:33:54.321  2605  2830 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 2 => 2
09-13 16:33:54.321  2605  2830 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 2 => 2
09-13 16:33:54.321  2605  2830 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-13 16:33:54.321  2605  2830 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 2 => 2
09-13 16:33:54.321  2605  2830 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 2 => 2
09-13 16:33:54.321  2605  2830 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-13 16:33:54.321  2605  2830 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-13 16:33:54.321  2605  2830 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 2 => 2
09-13 16:33:54.321  2605  2830 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 2 => 2
09-13 16:33:54.321  2605  2830 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24562953
,09-13 16:33:54.321  1158  1720 V AlarmManager:  remove PendingIntent] PendingIntent{2d30db: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:54.331  1158  2657 V AlarmManager:  remove PendingIntent] PendingIntent{c82b778: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:54.331  1158  2016 V AlarmManager:  remove PendingIntent] PendingIntent{65ede51: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:54.711   716   716 I MSM-irqbalance: Decided to move IRQ215 from CPU3 to CPU1
,09-13 16:33:54.731  2605  2768 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13d0a2f
,09-13 16:33:54.731  1158  1268 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 16:33:54.731  1158  1268 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4390, temperature: 315, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 16:33:54.731  1158  1268 D BatteryService: online:4, current avg:137, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:152
09-13 16:33:54.731  1158  1370 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1c786b6 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4927704 2639:com.samsung.android.providers.context/u0a5}
09-13 16:33:54.741  1158  1158 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 16:33:54.741  1699  1699 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 16:33:54.741  1699  1699 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 16:33:54.741  1699  1699 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-13 16:33:54.751  2605  2605 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 16:33:54.751  2605  3148 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 16:33:54.761  1699  1699 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 16:33:54.761  1699  1699 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 16:33:54.761  1699  1699 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 16:33:54.791  6042  6042 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-13 16:33:54.791  6042  6042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:33:54.791  6042  6042 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 16:33:55.311  3053  3107 I WCNSS_FILTER: do_write: IBS write: fe
09-13 16:33:55.311  3053  3107 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-13 16:33:55.311  1158  1589 V AlarmManager: Expired Alarm result :4
,09-13 16:33:55.311  2605  2605 D BtGatt.ScanManager: awakened up at time 119355
,09-13 16:33:55.311  2605  2812 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-13 16:33:55.311  3053  3058 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
09-13 16:33:55.311  3053  3058 I WCNSS_FILTER: do_write: IBS write: fd
,09-13 16:33:55.311  1158  1721 V AlarmManager:  remove PendingIntent] PendingIntent{e7d324: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:55.311  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-13 16:33:55.321  3053  3053 I WCNSS_FILTER: do_write: IBS write: fc
,09-13 16:33:55.321  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 78 : bytes_written: 78
09-13 16:33:55.321  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-13 16:33:55.321  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 78 : bytes_written: 78
09-13 16:33:55.321  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-13 16:33:55.321  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 78 : bytes_written: 78
09-13 16:33:55.321  1158  1269 V AlarmManager:  remove PendingIntent] PendingIntent{6e20e8d: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:55.321  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-13 16:33:55.321  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 78 : bytes_written: 78,
,09-13 16:33:55.321  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
09-13 16:33:55.321  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 78 : bytes_written: 78
09-13 16:33:55.321  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
09-13 16:33:55.331  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 10 : bytes_written: 10
09-13 16:33:55.331  2605  2773 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=5
09-13 16:33:55.331  2605  2773 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 16:33:55.331  2605  2773 D BtGatt.GattService: current time is 119371306723
,09-13 16:33:55.331  2605  2773 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -69, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -68, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -77, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -70, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -68, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-13 16:33:55.331  1158  2005 V AlarmManager:  remove PendingIntent] PendingIntent{cbd5842: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:55.331  2605  2773 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-13 16:33:55.331  1158  2603 V AlarmManager:  remove PendingIntent] PendingIntent{28ee053: PendingIntentRecord{7819de com.android.bluetooth broadcastIntent}}
,09-13 16:33:55.331  2605  2773 D ScanRecord: parseFromBytes
09-13 16:33:55.331  2605  2773 D ScanRecord: first manudata for manu ID
09-13 16:33:55.331  2605  2773 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-13 16:33:55.331  2605  2773 D ScanRecord: parseFromBytes
09-13 16:33:55.331  2605  2773 D ScanRecord: first manudata for manu ID
09-13 16:33:55.331  2605  2773 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-13 16:33:55.331  2605  2773 D ScanRecord: parseFromBytes
09-13 16:33:55.331  2605  2773 D ScanRecord: first manudata for manu ID
09-13 16:33:55.331  2605  2773 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-13 16:33:55.331  2605  2773 D ScanRecord: parseFromBytes
09-13 16:33:55.331  2605  2773 D ScanRecord: first manudata for manu ID
09-13 16:33:55.331  2605  2773 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-13 16:33:55.331  2605  2773 D ScanRecord: parseFromBytes
09-13 16:33:55.331  2605  2773 D ScanRecord: first manudata for manu ID
09-13 16:33:55.331  6042  6052 D ScanRecord: parseFromBytes
09-13 16:33:55.331  1158  2632 V AlarmManager:  remove PendingIntent] PendingIntent{260fd90: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:55.331  6042  6052 D ScanRecord: first manudata for manu ID
09-13 16:33:55.331  6042  6052 D ScanRecord: parseFromBytes
09-13 16:33:55.331  6042  6052 D ScanRecord: first manudata for manu ID
09-13 16:33:55.331  6042  6052 D ScanRecord: parseFromBytes
09-13 16:33:55.331  6042  6052 D ScanRecord: first manudata for manu ID
09-13 16:33:55.331  6042  6052 D ScanRecord: parseFromBytes
09-13 16:33:55.331  6042  6052 D ScanRecord: first manudata for manu ID
09-13 16:33:55.331  6042  6052 D ScanRecord: parseFromBytes
09-13 16:33:55.331  6042  6052 D ScanRecord: first manudata for manu ID
,09-13 16:33:55.341  1158  1720 V AlarmManager:  remove PendingIntent] PendingIntent{dee0689: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:55.341  1158  1969 V AlarmManager:  remove PendingIntent] PendingIntent{b4cb68e: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:55.341  1158  1961 V AlarmManager:  remove PendingIntent] PendingIntent{f1d2eaf: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:55.341  1158  2603 V AlarmManager:  remove PendingIntent] PendingIntent{e0062bc: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:55.351  1158  2343 V AlarmManager:  remove PendingIntent] PendingIntent{da78245: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:55.351  1158  2459 V AlarmManager:  remove PendingIntent] PendingIntent{61ad9a: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:55.361  1158  2657 V AlarmManager:  remove PendingIntent] PendingIntent{b9806cb: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:55.361  1158  2016 V AlarmManager:  remove PendingIntent] PendingIntent{dceeea8: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:56.331  3053  3107 I WCNSS_FILTER: do_write: IBS write: fe,
09-13 16:33:56.331  3053  3107 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-13 16:33:56.331  1158  1589 V AlarmManager: Expired Alarm result :4
,09-13 16:33:56.331  2605  2605 D BtGatt.ScanManager: awakened up at time 120374
,09-13 16:33:56.331  2605  2812 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-13 16:33:56.331  3053  3058 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
09-13 16:33:56.331  1158  1719 V AlarmManager:  remove PendingIntent] PendingIntent{f9d0966: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:56.331  3053  3058 I WCNSS_FILTER: do_write: IBS write: fd,
,09-13 16:33:56.341  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
09-13 16:33:56.341  3053  3053 I WCNSS_FILTER: do_write: IBS write: fc
09-13 16:33:56.341  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 53 : bytes_written: 53
09-13 16:33:56.341  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-13 16:33:56.341  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 53 : bytes_written: 53,
09-13 16:33:56.341  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
09-13 16:33:56.341  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 78 : bytes_written: 78
,09-13 16:33:56.341  1158  2670 V AlarmManager:  remove PendingIntent] PendingIntent{99e44a7: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:56.341  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-13 16:33:56.341  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 53 : bytes_written: 53
,09-13 16:33:56.341  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6,
09-13 16:33:56.341  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 52 : bytes_written: 52
,09-13 16:33:56.341  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-13 16:33:56.351  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 52 : bytes_written: 52
09-13 16:33:56.351  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-13 16:33:56.351  1158  1721 V AlarmManager:  remove PendingIntent] PendingIntent{1784d54: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:56.351  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 10 : bytes_written: 10
09-13 16:33:56.351  2605  2773 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=6
09-13 16:33:56.351  2605  2773 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 16:33:56.351  2605  2773 D BtGatt.GattService: current time is 120391915576
09-13 16:33:56.351  2605  2773 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -68, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -69, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -68, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -71, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 77, -3, -4, 78, -104, 86, 1, -128, -45, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111, 0, 77, -3, -4, 78, -104, 86, 1, -128, -45, 19, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111, 0]
09-13 16:33:56.351  1158  2657 V AlarmManager:  remove PendingIntent] PendingIntent{ac0b4fd: PendingIntentRecord{7819de com.android.bluetooth broadcastIntent}}
09-13 16:33:56.351  2605  2773 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-13 16:33:56.351  2605  2773 D ScanRecord: parseFromBytes
,09-13 16:33:56.351  2605  2773 D ScanRecord: first manudata for manu ID
09-13 16:33:56.351  2605  2773 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
09-13 16:33:56.351  2605  2773 D ScanRecord: parseFromBytes
09-13 16:33:56.351  2605  2773 D ScanRecord: first manudata for manu ID
09-13 16:33:56.351  2605  2773 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-13 16:33:56.351  2605  2773 D ScanRecord: parseFromBytes
09-13 16:33:56.351  2605  2773 D ScanRecord: first manudata for manu ID
09-13 16:33:56.351  2605  2773 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
09-13 16:33:56.351  2605  2773 D ScanRecord: parseFromBytes
09-13 16:33:56.351  2605  2773 D ScanRecord: first manudata for manu ID
09-13 16:33:56.351  2605  2773 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111]
09-13 16:33:56.351  2605  2773 D ScanRecord: parseFromBytes
09-13 16:33:56.351  2605  2773 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111]
09-13 16:33:56.351  2605  2773 D ScanRecord: parseFromBytes
,09-13 16:33:56.351  6042  6053 D ScanRecord: parseFromBytes
09-13 16:33:56.351  6042  6053 D ScanRecord: first manudata for manu ID
09-13 16:33:56.351  6042  6053 D ScanRecord: parseFromBytes
09-13 16:33:56.351  6042  6053 D ScanRecord: first manudata for manu ID
09-13 16:33:56.351  6042  6053 D ScanRecord: parseFromBytes
09-13 16:33:56.351  6042  6053 D ScanRecord: first manudata for manu ID
09-13 16:33:56.351  6042  6053 D ScanRecord: parseFromBytes
09-13 16:33:56.351  6042  6053 D ScanRecord: parseFromBytes
09-13 16:33:56.351  6042  6053 D ScanRecord: first manudata for manu ID
09-13 16:33:56.351  6042  6053 D ScanRecord: parseFromBytes
,09-13 16:33:56.351  6042  6042 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> A8:81:95:E9:5F:6F 5], added - the peer count is 1
,09-13 16:33:56.351  1158  1268 V AlarmManager:  remove PendingIntent] PendingIntent{3e055f2: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:56.351  6042  6042 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> A8:81:95:E9:5F:6F 6] updated - the peer count is 1
09-13 16:33:56.351  6042  6042 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 5], Bluetooth address: A8:81:95:E9:5F:6F, device name: '', device address: ''
,09-13 16:33:56.351  6042  6042 I io.jxcore.node.ConnectionHelper: onPeerUpdated: [<no peer name> A8:81:95:E9:5F:6F 6], device name: '', device address: ''
,09-13 16:33:56.361  1158  2603 V AlarmManager:  remove PendingIntent] PendingIntent{be08443: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:56.361  1158  2459 V AlarmManager:  remove PendingIntent] PendingIntent{5b6eac0: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:56.361  1158  1969 V AlarmManager:  remove PendingIntent] PendingIntent{ae8a3f9: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:56.371  1158  2005 V AlarmManager:  remove PendingIntent] PendingIntent{299df3e: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:56.371  1158  2016 V AlarmManager:  remove PendingIntent] PendingIntent{57d219f: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:56.371  1158  2343 V AlarmManager:  remove PendingIntent] PendingIntent{67ff2ec: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:56.381  1158  2670 V AlarmManager:  remove PendingIntent] PendingIntent{f0686b5: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:56.381  1158  1721 V AlarmManager:  remove PendingIntent] PendingIntent{7d0b14a: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:56.381  1158  2592 V AlarmManager:  remove PendingIntent] PendingIntent{31c38bb: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:56.381  1158  2657 V AlarmManager:  remove PendingIntent] PendingIntent{7ef51d8: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}},
,09-13 16:33:57.101  1158  3586 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 16:33:57.301  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-13 16:33:57.301  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:57.301  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:33:57.301  6042  6092 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31d4af7 not in the list
09-13 16:33:57.301  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:57.301  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:33:57.301  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 16:33:57.301  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:33:57.301  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
09-13 16:33:57.301  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-13 16:33:57.301  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:57.301  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:57.301  6042  6092 D BluetoothLeScanner: Stop Scan
,09-13 16:33:57.301  2605  2634 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest,
09-13 16:33:57.301  2605  2634 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:33:57.301  2605  2634 D BtGatt.GattService: stopScan() - queue size =1
09-13 16:33:57.301  2605  2830 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
,09-13 16:33:57.301  2605  2830 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
,09-13 16:33:57.301  2605  2830 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,09-13 16:33:57.301  2605  2830 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 2 => 2
09-13 16:33:57.311  1158  1269 V AlarmManager:  remove PendingIntent] PendingIntent{e5d931: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:57.301  2605  2830 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 2 => 2
09-13 16:33:57.301  2605  3143 D BtGatt.GattService: unregisterClient() - clientIf=6
09-13 16:33:57.301  2605  2830 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
,09-13 16:33:57.301  2605  2830 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
,09-13 16:33:57.301  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:33:57.301  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 16:33:57.301  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 16:33:57.301  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 16:33:57.301  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 16:33:57.311  2605  2812 D BtGatt.ScanManager: filter size is 1
09-13 16:33:57.311  2605  2812 D BtGatt.ScanManager: delete FilterIndex - 3
09-13 16:33:57.311  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
09-13 16:33:57.311  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:33:57.311  3053  3053 I WCNSS_FILTER: do_write: IBS write: fc
09-13 16:33:57.311  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 10 : bytes_written: 10
09-13 16:33:57.311  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:57.311  2605  2773 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-13 16:33:57.311  2605  2773 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 16:33:57.311  1158  2603 V AlarmManager:  remove PendingIntent] PendingIntent{6f09816: PendingIntentRecord{7819de com.android.bluetooth broadcastIntent}}
09-13 16:33:57.311  2605  2812 D BtGatt.ScanManager: stopping BLe Batch,
09-13 16:33:57.311  1158  2459 V AlarmManager:  remove PendingIntent] PendingIntent{9cba597: PendingIntentRecord{7819de com.android.bluetooth broadcastIntent}}
09-13 16:33:57.311  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:57.311  1158  2670 V AlarmManager:  remove PendingIntent] PendingIntent{1f3b384: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:57.311  6042  6092 D BluetoothLeAdvertiser: stop advertising
09-13 16:33:57.311  6042  6092 D BluetoothLeAdvertiser: wrapper is null
09-13 16:33:57.311  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 16:33:57.311  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 16:33:57.311  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:33:57.311  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 16 : bytes_written: 16
09-13 16:33:57.311  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 16:33:57.311  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:57.311  6042  6092 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
09-13 16:33:57.311  2605  2773 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-13 16:33:57.311  2605  2773 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 16:33:57.311  2605  2812 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-13 16:33:57.311  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-13 16:33:57.321  1158  1961 V AlarmManager:  remove PendingIntent] PendingIntent{aba83f0: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:57.311  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 10 : bytes_written: 10
09-13 16:33:57.311  2605  2773 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-13 16:33:57.311  2605  2773 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 16:33:57.311  6042  6042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:33:57.311  6042  6092 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a5d64 not in the list
09-13 16:33:57.311  6042  6092 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:57.311  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:57.311  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:57.311  6042  6042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:33:57.321  6042  6042 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:33:57.321  6042  6092 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
09-13 16:33:57.321  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
09-13 16:33:57.321  6042  6092 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:33:57.321  6042  6092 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 16:33:57.321  6042  6092 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 16:33:57.321  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:33:57.321  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 16:33:57.321  6042  6092 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:33:57.321  6042  6092 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:33:57.321  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:33:57.321  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:33:57.321  6042  6042 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:33:57.321  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:33:57.321  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:33:57.321  6042  6141 D BluetoothSocket: bindListen(): myUserId = 0
09-13 16:33:57.321  6042  6141 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:33:57.321  6042  6092 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 16:33:57.321  6042  6092 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:33:57.331  6042  6141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-13 16:33:57.331  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:57.331  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:57.331  1158  2657 V AlarmManager:  remove PendingIntent] PendingIntent{13d7d69: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:57.331  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:57.331  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:33:57.331  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:57.331  1158  1269 V AlarmManager:  remove PendingIntent] PendingIntent{b9a93ee: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:57.331  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:57.331  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 16:33:57.331  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:33:57.341  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:57.341  1158  2657 V AlarmManager:  remove PendingIntent] PendingIntent{1f7b08f: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:57.341  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 16:33:57.341  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-13 16:33:57.341  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 44 78 3E EB 95 EE
09-13 16:33:57.341  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:33:57.341  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:33:57.341  6042  6092 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 16:33:57.341  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:57.341  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:33:57.341  6042  6092 D BluetoothLeAdvertiser: start advertising
,09-13 16:33:57.341  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:33:57.341  2605  3143 D BtGatt.GattService: registerClient() - UUID=05b47d4e-9ce1-4856-8a87-4702f8368780
,09-13 16:33:57.391  2605  2773 D BtGatt.GattService: onClientRegistered() - UUID=05b47d4e-9ce1-4856-8a87-4702f8368780, clientIf=6
09-13 16:33:57.391  6042  6053 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 16:33:57.391  2605  3165 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-13 16:33:57.391  2605  3165 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:33:57.391  2605  3165 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:33:57.391  2605  2797 D BtGatt.AdvertiseManager: message : 0
09-13 16:33:57.391  2605  2830 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-13 16:33:57.391  2605  2830 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
,09-13 16:33:57.391  2605  2797 D BtGatt.AdvertiseManager: number of adv instance running = 0
,09-13 16:33:57.391  2605  2797 D BtGatt.AdvertiseManager: size of list is =0
,09-13 16:33:57.401  2605  2797 D BtGatt.AdvertiseManager: starting advertising
,09-13 16:33:57.401  2605  2797 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-13 16:33:57.401  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 28 : bytes_written: 28
09-13 16:33:57.401  3053  3053 I WCNSS_FILTER: do_write: IBS write: fc
09-13 16:33:57.401  1158  1721 V AlarmManager:  remove PendingIntent] PendingIntent{bdbef1c: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:57.401  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 16:33:57.401  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
09-13 16:33:57.401  2605  2830 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 37
09-13 16:33:57.401  2605  2830 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24562953
09-13 16:33:57.401  2605  2830 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-13 16:33:57.401  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-13 16:33:57.401  2605  2830 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 16:33:57.401  2605  2830 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-13 16:33:57.401  2605  2773 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-13 16:33:57.411  2605  2797 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 16:33:57.411  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 38 : bytes_written: 38
09-13 16:33:57.411  1158  2459 V AlarmManager:  remove PendingIntent] PendingIntent{b278725: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:57.411  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-13 16:33:57.411  2605  2773 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
09-13 16:33:57.411  2605  2797 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-13 16:33:57.411  2605  2797 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-13 16:33:57.411  2605  2797 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
09-13 16:33:57.411  2605  2797 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
09-13 16:33:57.411  6042  6052 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,09-13 16:33:57.411  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 16:33:57.411  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:33:57.411  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:33:57.411  6042  6042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:33:57.411  1158  1719 V AlarmManager:  remove PendingIntent] PendingIntent{6a000fa: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:33:57.411  6042  6042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 16:33:57.411  6042  6042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-13 16:33:57.411  6042  6042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 16:33:57.411  6042  6042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 16:33:57.411  6042  6042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-13 16:33:57.421  6042  6042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 16:33:57.421  6042  6042 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 16:33:57.421  1158  1721 V AlarmManager:  remove PendingIntent] PendingIntent{dc8c6ab: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:57.421  1158  1961 V AlarmManager:  remove PendingIntent] PendingIntent{e46e108: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:57.421  1158  2592 V AlarmManager:  remove PendingIntent] PendingIntent{ee70a1: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:33:57.921  6042  6042 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 16:33:57.921  6042  6042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 16:33:57.921  6042  6042 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 16:33:58.411  3053  3107 I WCNSS_FILTER: do_write: IBS write: fe,
09-13 16:33:58.411  3053  3107 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-13 16:33:59.991  1158  1589 V AlarmManager: Expired Alarm result :8
,09-13 16:34:00.911  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:00.911  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:34:00.911  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:34:00.911  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 16:34:00.921  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:34:00.921  6042  6141 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 16:34:00.921  6042  6141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:34:00.921  6042  6141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 16:34:00.921  6042  6042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:34:00.921  6042  6092 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:34:00.921  6042  6092 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31d4af7 not in the list
09-13 16:34:00.921  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:00.921  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:34:00.921  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:34:00.921  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:34:00.921  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 16:34:00.921  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:34:00.921  6042  6042 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-13 16:34:00.921  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:34:00.921  6042  6092 D BluetoothLeScanner: could not find callback wrapper
09-13 16:34:00.921  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:34:00.921  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 16:34:00.921  6042  6092 D BluetoothAdapter: STATE_ON
,09-13 16:34:00.921  6042  6092 D BluetoothAdapter: STATE_ON
09-13 16:34:00.921  6042  6092 D BluetoothLeAdvertiser: stop advertising
09-13 16:34:00.931  2605  3143 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:34:00.931  2605  3143 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:34:00.931  2605  2797 D BtGatt.AdvertiseManager: message : 1
09-13 16:34:00.931  2605  2830 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
09-13 16:34:00.931  2605  2830 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
09-13 16:34:00.931  2605  2830 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 16:34:00.931  2605  2797 D BtGatt.AdvertiseManager: stop advertise for client =  6
09-13 16:34:00.931  2605  2797 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
,09-13 16:34:00.931  2605  2797 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-13 16:34:00.931  3053  3058 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
09-13 16:34:00.931  1158  1720 V AlarmManager:  remove PendingIntent] PendingIntent{95d32c6: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:34:00.951  3053  3058 I WCNSS_FILTER: do_write: IBS write: fd
09-13 16:34:00.951  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
,09-13 16:34:00.951  3053  3053 I WCNSS_FILTER: do_write: IBS write: fc
,09-13 16:34:00.951  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 16:34:00.951  2605  2773 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-13 16:34:00.951  2605  2773 D BtGatt.GattService: Client app is not null!
09-13 16:34:00.951  1158  2657 V AlarmManager:  remove PendingIntent] PendingIntent{d4b2287: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:34:00.951  2605  2830 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 2
09-13 16:34:00.951  2605  2830 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
09-13 16:34:00.951  3053  3058 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 16:34:00.951  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
09-13 16:34:00.951  6042  6053 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
09-13 16:34:00.951  2605  3165 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 16:34:00.951  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 16:34:00.951  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 16:34:00.951  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 16:34:00.951  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 16:34:00.951  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 16:34:00.961  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:34:00.961  6042  6092 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 16:34:00.961  6042  6092 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:34:00.961  1158  1969 V AlarmManager:  remove PendingIntent] PendingIntent{8ed05b4: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
09-13 16:34:00.961  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:00.961  6042  6092 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a5d64 not in the list
09-13 16:34:00.961  6042  6042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:00.961  6042  6092 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:00.961  6042  6042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:00.961  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:00.961  6042  6042 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:34:00.961  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:00.961  6042  6092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:00.961  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:00.961  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:00.961  6042  6092 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31d4af7 not in the list
09-13 16:34:00.961  6042  6092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:00.961  6042  6092 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a5d64 not in the list
09-13 16:34:00.961  6042  6092 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:00.961  6042  6092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:00.961  6042  6092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:00.961  6042  6092 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-13 16:34:00.961  6042  6092 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 16:34:00.961  6042  6092 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-13 16:34:00.961  6042  6092 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:34:00.961  6042  6092 V io.jxcore.,node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 16:34:00.961  6042  6092 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 16:34:00.971  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
,09-13 16:34:00.971  3053  3058 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-13 16:34:00.971  1158  2459 V AlarmManager:  remove PendingIntent] PendingIntent{1e075dd: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:34:00.971  6042  6144 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 313, name: My test thread name)
09-13 16:34:00.971  3053  3053 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-13 16:34:00.971  1158  2016 V AlarmManager:  remove PendingIntent] PendingIntent{669b552: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:34:00.971  1158  1719 V AlarmManager:  remove PendingIntent] PendingIntent{fad6023: PendingIntentRecord{a7e2666 com.android.bluetooth broadcastIntent}}
,09-13 16:34:01.461  6042  6042 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 16:34:01.971  3053  3107 I WCNSS_FILTER: do_write: IBS write: fe
09-13 16:34:01.971  3053  3107 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-13 16:34:02.971  6042  6092 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 313
09-13 16:34:02.971  6042  6092 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 313, name: My test thread name)
,09-13 16:34:02.971  6042  6145 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 314, name: My test thread name)
09-13 16:34:02.971  6042  6145 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 314, thread name: My test thread name)
09-13 16:34:02.971  6042  6145 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 314, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-13 16:34:02.971  6042  6092 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:34:02.981  6042  6146 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 318, name: My test thread name)
09-13 16:34:02.981  6042  6146 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 318, thread name: My test thread name): Test exception.
09-13 16:34:02.981  6042  6146 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 318, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-13 16:34:02.981  6042  6092 I jxcore-log: Total number of executed tests:  76
09-13 16:34:02.981  6042  6092 I jxcore-log: 
,09-13 16:34:02.981  6042  6092 I jxcore-log: Number of passed tests:  76
09-13 16:34:02.981  6042  6092 I jxcore-log: 
,09-13 16:34:02.981  6042  6092 I jxcore-log: Number of failed tests:  0
09-13 16:34:02.981  6042  6092 I jxcore-log: 
,09-13 16:34:02.981  6042  6092 I jxcore-log: Number of ignored tests:  0
09-13 16:34:02.981  6042  6092 I jxcore-log: 
,09-13 16:34:02.981  6042  6092 I jxcore-log: Total duration:  17220
09-13 16:34:02.981  6042  6092 I jxcore-log: 
,09-13 16:34:02.991  6042  6092 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-13 16:34:02.991  6042  6092 I jxcore-log: 
,09-13 16:34:02.991  6042  6092 I jxcore-log: My device name is: samsung-SM-T719
09-13 16:34:02.991  6042  6092 I jxcore-log: 
09-13 16:34:02.991  6042  6092 I jxcore-log: WARN testUtils: myNameCallback not set!
09-13 16:34:02.991  6042  6092 I jxcore-log: 
09-13 16:34:03.001  6042  6092 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:03.001  6042  6092 I jxcore-log: 
09-13 16:34:03.001  6042  6092 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:03.001  6042  6092 I jxcore-log: 
09-13 16:34:03.001  6042  6092 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:03.001  6042  6092 I jxcore-log: 
09-13 16:34:03.001  6042  6092 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 16:34:03.001  6042  6092 I jxcore-log: 
,09-13 16:34:03.011  6042  6092 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 16:34:03.011  6042  6092 I jxcore-log: 
,09-13 16:34:03.011  6042  6092 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:03.011  6042  6092 I jxcore-log: 
,09-13 16:34:03.011  6042  6092 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 16:34:03.011  6042  6092 I jxcore-log: 
,09-13 16:34:03.011  6042  6092 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:03.011  6042  6092 I jxcore-log: 
,09-13 16:34:03.011  6042  6092 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 16:34:03.011  6042  6092 I jxcore-log: 
,09-13 16:34:03.011  6042  6092 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 16:34:03.011  6042  6092 I jxcore-log: 
,09-13 16:34:03.021  6042  6092 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:03.021  6042  6092 I jxcore-log: 
,09-13 16:34:03.021  6042  6092 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true},
09-13 16:34:03.021  6042  6092 I jxcore-log: 
09-13 16:34:03.021  6042  6092 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-13 16:34:03.021  6042  6092 I jxcore-log: 
,09-13 16:34:03.021  6042  6092 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-13 16:34:03.021  6042  6092 I jxcore-log: 
,09-13 16:34:03.021  6042  6092 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-13 16:34:03.021  6042  6092 I jxcore-log: 
,09-13 16:34:03.021  6042  6092 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true},
09-13 16:34:03.021  6042  6092 I jxcore-log: 
,09-13 16:34:03.021  6042  6092 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 16:34:03.021  6042  6092 I jxcore-log: 
,09-13 16:34:03.071  6042  6144 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 313, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,09-13 16:34:03.531  6147  6147 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-13 16:34:03.541  6147  6147 D AndroidRuntime: CheckJNI is OFF
,09-13 16:34:03.541  6147  6147 D AndroidRuntime: readGMSProperty: start
09-13 16:34:03.541  6147  6147 D AndroidRuntime: readGMSProperty: already setted!!
09-13 16:34:03.541  6147  6147 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-13 16:34:03.541  6147  6147 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-13 16:34:03.541  6147  6147 D AndroidRuntime: readGMSProperty: end
09-13 16:34:03.541  6147  6147 D AndroidRuntime: addProductProperty: start
,09-13 16:34:03.571  6147  6147 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-13 16:34:03.601  6147  6147 I Radio-JNI: register_android_hardware_Radio DONE
,09-13 16:34:03.611  6147  6147 E AffinityControl: AffinityControl: registerfunction enter
,09-13 16:34:03.621  6147  6147 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-13 16:34:03.631  1158  1961 D PackageManager: START PACKAGE DELETE: observer{237947168}
09-13 16:34:03.631  1158  1961 D PackageManager: pkg{<packageName>}
09-13 16:34:03.631  1158  1961 D PackageManager: user{0}
09-13 16:34:03.631  1158  1961 D PackageManager: caller{2000}
09-13 16:34:03.631  1158  1961 D PackageManager: flags{2}
09-13 16:34:03.631  1158  1961 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-13 16:34:03.631  1158  1961 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-13 16:34:03.631  1158  1961 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-13 16:34:03.631  1158  1961 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-13 16:34:03.631  1158  1961 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-13 16:34:03.631  1158  1422 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-13 16:34:03.631  1158  1422 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-13 16:34:03.631  1158  1422 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-13 16:34:03.631  1158  1422 D ApplicationPolicy: getApplicationUninstallationEnabled
09-13 16:34:03.631  1158  1422 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-13 16:34:03.631  1158  1422 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-13 16:34:03.631  1158  1422 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,09-13 16:34:03.641  1158  1422 D PackageManager: !@killApplicatoin: 10136, uninstall pkg
09-13 16:34:03.641  1158  1422 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-13 16:34:03.641  1158  1370 I ActivityManager: Force stopping com.test.thalitest appid=10136 user=-1: uninstall pkg
09-13 16:34:03.641  1158  1422 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
09-13 16:34:03.641  1158  1370 I ActivityManager: Killing 6042:com.test.thalitest/u0a136 (adj 1): stop com.test.thalitest cause uninstall pkg
09-13 16:34:03.641  1158  1370 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=6042 ,hash=124422268 ,name=com.test.thalitest
09-13 16:34:03.641  1158  1370 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-13 16:34:03.661  1158  1370 I ActivityManager: Start proc 6156:com.test.thalitest/u0a136 for activity com.test.thalitest/.MainActivity
,09-13 16:34:03.661  6156  6156 E Zygote  : v2
09-13 16:34:03.661  6156  6156 I libpersona: KNOX_SDCARD checking this for 10136
09-13 16:34:03.661  6156  6156 I libpersona: KNOX_SDCARD not a persona
,09-13 16:34:03.661  1158  1370 I ActivityManager:   Force finishing activity ActivityRecord{251319b u0 com.test.thalitest/.MainActivity t18}
09-13 16:34:03.661  1158  1370 W VirtualScreenManagerService: moveTaskBackToDisplayIfNeeded(): top activity or app is null
,09-13 16:34:03.661  6156  6156 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-13 16:34:03.661   445  2290 I SurfaceFlinger: id=17 Removed NainActivit (6/13)
,09-13 16:34:03.661  1158  1422 D AASAinstall: there is not AASApackages.xml file
09-13 16:34:03.661   445   464 I SurfaceFlinger: id=17 Removed NainActivit (-2/13)
,09-13 16:34:03.671  6156  6156 E Zygote  : accessInfo : 0
,09-13 16:34:03.671  6156  6156 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
,09-13 16:34:03.691  6156  6156 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:34:03.691  6156  6156 D ActivityThread: Added TimaKeyStore provider
,09-13 16:34:03.861  1158  1363 E libprocessgroup: failed to kill 1 processes for processgroup 6042
,09-13 16:34:03.871  1158  1269 D GraphicsStats: Buffer count: 5
09-13 16:34:03.871  1158  1969 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@49d49e)
09-13 16:34:03.871   445   468 E         : BitTube(): close sendFd (55)
09-13 16:34:03.871   445   468 E         : BitTube(): close sendFd (56)
,09-13 16:34:03.871  1158  1629 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:34:03.871  1158  1629 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:34:03.871  1158  1629 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-13 16:34:03.951  1158  1422 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,09-13 16:34:04.021  1158  1422 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-13 16:34:04.031   567   567 W keystore: ENTER clear_uid from uid 1000 for 10136
,09-13 16:34:04.031  1158  1422 I art     : Starting a blocking GC Explicit
,09-13 16:34:04.041  6156  6156 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
09-13 16:34:04.041  6156  6156 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
09-13 16:34:04.041  6156  6156 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
09-13 16:34:04.041  6156  6156 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
,09-13 16:34:04.061  6156  6156 D AndroidRuntime: Shutting down VM
,09-13 16:34:04.061  6156  6156 E AndroidRuntime: FATAL EXCEPTION: main
09-13 16:34:04.061  6156  6156 E AndroidRuntime: Process: com.test.thalitest, PID: 6156
09-13 16:34:04.061  6156  6156 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
09-13 16:34:04.061  6156  6156 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:676)
09-13 16:34:04.061  6156  6156 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6296)
09-13 16:34:04.061  6156  6156 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:223)
09-13 16:34:04.061  6156  6156 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1863)
09-13 16:34:04.061  6156  6156 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:34:04.061  6156  6156 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
09-13 16:34:04.061  6156  6156 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7231)
09-13 16:34:04.061  6156  6156 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 16:34:04.061  6156  6156 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
09-13 16:34:04.061  6156  6156 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
09-13 16:34:04.061  6156  6156 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
09-13 16:34:04.061  6156  6156 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:485)
09-13 16:34:04.061  6156  6156 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:661)
09-13 16:34:04.061  6156  6156 E AndroidRuntime: 	... 9 more
,09-13 16:34:04.061  6156  6156 I Process : Sending signal. PID: 6156 SIG: 9
,09-13 16:34:04.081  6169  6169 E Zygote  : v2
,09-13 16:34:04.081  6169  6169 I libpersona: KNOX_SDCARD checking this for 1000
09-13 16:34:04.081  1158  1370 I ActivityManager: Start proc 6169:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
,09-13 16:34:04.081  6169  6169 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-13 16:34:04.081  6169  6169 I libpersona: KNOX_SDCARD not a persona
,09-13 16:34:04.081  6169  6169 E Zygote  : accessInfo : 0
,09-13 16:34:04.111  6169  6169 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:34:04.111  6169  6169 D ActivityThread: Added TimaKeyStore provider
,09-13 16:34:04.111  1158  2603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{407574c u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e6bdb7f 6169:com.samsung.android.sm/1000}
,09-13 16:34:04.141  6169  6169 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1311 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.samsung.android.sm.common.SmartManagerReceiver.b:259 com.samsung.android.sm.common.SmartManagerReceiver.onReceive:107 
,09-13 16:34:04.161  1158  1268 I ActivityManager: Killing 5423:com.sec.android.soagent/1000 (adj 15): DHA:empty #31
,09-13 16:34:04.211  1158  3556 D SSRM:s  : SIOP:: AP = 330, PST = 369 (W:12), CP = 41, LCD = 0
,09-13 16:34:04.211  1158  3556 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 16:34:04.221  1158  1969 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.soagent, Auto Run ON
09-13 16:34:04.221  1158  1969 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5423 ,hash=47749457 ,name=com.sec.android.soagent
,09-13 16:34:04.231  1158  2459 I ActivityManager: Process com.test.thalitest (pid 6156)(adj 9) has died(147,1503)
09-13 16:34:04.231  1158  2459 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-13 16:34:04.231  1158  2459 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=6156 ,hash=166957785 ,name=com.test.thalitest
,09-13 16:34:04.231  1158  2459 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.android.server.am.ActivityManagerService.updateOomAdjLocked:26615 com.android.server.am.ActivityManagerService.appDiedLocked:7605 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1888 android.os.BinderProxy.sendDeathNotice:558 
,09-13 16:34:04.271  1158  1422 I art     : Explicit concurrent mark sweep GC freed 243584(14MB) AllocSpace objects, 70(3MB) LOS objects, 33% free, 29MB/44MB, paused 2.925ms total 239.067ms
,09-13 16:34:04.291  1158  1422 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-13 16:34:04.291  1158  1422 D AASAuninstall: userId = 0, info.removedAppID = 10136, info.uid = 10136, packageName = com.test.thalitest
09-13 16:34:04.291  1158  1422 D AASAinstall: there is not AASApackages.xml file
09-13 16:34:04.291  1158  1422 D PackageManager: result of delete: 1{237947168}
,09-13 16:34:04.291  1158  1422 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-13 16:34:04.291  1158  1422 D PackageManager: userId{-1}
09-13 16:34:04.291  1158  1422 D PackageManager: andCode{true}
,09-13 16:34:04.291  6147  6147 I art     : System.exit called, status: 0
09-13 16:34:04.291  6147  6147 I AndroidRuntime: VM exiting with result code 0.
,09-13 16:34:04.301  1158  1422 I ActivityManager: Force stopping com.test.thalitest appid=10136 user=0: pkg removed
,09-13 16:34:04.331  5776  6183 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,09-13 16:34:04.331  5776  6183 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,09-13 16:34:04.341  5776  6183 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,09-13 16:34:04.361  1699  1699 D ShortcutManager: onReceive : android.intent.action.PACKAGE_REMOVED
09-13 16:34:04.361  1699  1699 D ShortcutManager: onReceive : Intent.EXTRA_REPLACING false,com.test.thalitest
,09-13 16:34:04.361  1699  1699 D CoverUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
,09-13 16:34:04.361  1874  2395 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-13 16:34:04.361  5028  5045 I SystemBroadcastReceiver: [#CMH#] Received broadcast 
,09-13 16:34:04.361  5028  5045 I ControllerEventHandler: [#CMH#] onPackageRemoved  null
09-13 16:34:04.361  5028  5045 I SystemBroadcastReceiver: [#CMH#] onReceive completed 
,09-13 16:34:04.371  1158  1591 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 16:34:04.381  1158  1619 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 16:34:04.381  1158  1619 V NetworkStats: removeUidsLocked() for UIDs [10136]
09-13 16:34:04.381  1158  1619 V NetworkStats: performPollLocked(flags=0x3)
,09-13 16:34:04.391  1943  1943 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-13 16:34:04.401  1158  1370 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7ca8444 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b312e56 3896:com.samsung.klmsagent/u0a16}
,09-13 16:34:04.401  1798  1798 I Recents_MultiWindowAppListInfo: android.intent.action.PACKAGE_REMOVE
09-13 16:34:04.401  3896  3896 I KLMS-2.6.094: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } | timestamp: Tue Sep 13 16:34:04 GMT+02:00 2016
,09-13 16:34:04.411  1158  2670 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=2488, uid=10093 that is not exported from uid 10091
,09-13 16:34:04.411  3896  3896 I KLMS-2.6.094: : KLMSAbstractReciever(): onReceive().END.
,09-13 16:34:04.411  1158  1619 V NetworkStats: performPollLocked() took 29ms
09-13 16:34:04.411  1158  1619 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 16:34:04.411  1158  2343 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7ca8444 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3587de6 1158:system/1000}
,09-13 16:34:04.421  1158  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 16:34:04.421  1158  1620 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 16:34:04.421  3896  3896 I KLMS-2.6.094: : KLMSIntentService(): onCreate()
,09-13 16:34:04.421  3896  3896 I KLMS-2.6.094: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-13 16:34:04.421  3896  3896 I KLMS-2.6.094: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-13 16:34:04.421  3896  6187 I KLMS-2.6.094: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-13 16:34:04.421  3896  6187 D KLMS-2.6.094: : KLMSIntentService(): PACKAGE_REMOVED
09-13 16:34:04.421  3896  6187 I KLMS-2.6.094: : Systemprocess(): listeningToPackageRemoved().START
09-13 16:34:04.421  3896  6187 I KLMS-2.6.094: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
09-13 16:34:04.421  3896  6187 I KLMS-2.6.094: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
09-13 16:34:04.421  3896  6187 I KLMS-2.6.094: : MDMBridge(): getAllLicenseInfoFromSDK()
,09-13 16:34:04.431  3896  6187 I KLMS-2.6.094: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-13 16:34:04.431  1158  1363 D EnterpriseDeviceManagerService: Package has changed for user 0
09-13 16:34:04.431  1158  1363 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,09-13 16:34:04.431  3896  6187 I KLMS-2.6.094: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-13 16:34:04.431  1158  1158 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
09-13 16:34:04.431  1158  1158 V AlarmManager: Remove alarm for next reason : android.intent.action.PACKAGE_REMOVED : package: com.test.thalitest
,09-13 16:34:04.431  1158  1158 D UniversalCredentialManagerService: inside mPkgReciever onReceive : android.intent.action.PACKAGE_REMOVED
09-13 16:34:04.431  1158  1158 D UniversalCredentialManagerService: ACTION_PACKAGE_REMOVED is called....
09-13 16:34:04.431  1158  1158 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-13 16:34:04.441  1158  1158 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-13 16:34:04.441  1158  1158 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10136 container id = 0
,09-13 16:34:04.441  1158  1158 I OTPFW   : ProvisionData::getAllEntries Enter
,09-13 16:34:04.441  1158  1158 E OTPFW   : ProvisionData::getAllEntries Table is empty
09-13 16:34:04.441  1158  1158 E SDAgentPackageStateReceiver: Not going to handle 'com.test.thalitest'!
,09-13 16:34:04.441  1158  1158 D UcmService: onReceive android.intent.action.PACKAGE_REMOVED
09-13 16:34:04.441  1158  1158 D UcmService: Package update in userId-0 and uid-10136
,09-13 16:34:04.441  3896  6187 I KLMS-2.6.094: : MDMBridge(): getAllLicenseInfoFromSDK()
09-13 16:34:04.441  3896  6187 D KLMS-2.6.094: : Systemprocess(): arrayLicenseInfo is null
,09-13 16:34:04.441  1158  1158 D GameManager.DatabaseHelper: removeGame(), packageName: com.test.thalitest, ret: 0
,09-13 16:34:04.441  1158  1158 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-13 16:34:04.451  1158  1158 V EnterpriseBillingAsyncHandler: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,09-13 16:34:04.451  1158  1654 V EnterpriseBillingPolicyInternal: packageModification -  start - android.intent.action.PACKAGE_REMOVED
09-13 16:34:04.451  1158  1654 V EnterpriseBillingPolicyInternal: uID is 10136
09-13 16:34:04.451  1158  1654 V EnterpriseBillingPolicyInternal: Removed Packageuid is0
09-13 16:34:04.451  1158  1654 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-13 16:34:04.451  1158  1654 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-13 16:34:04.451  1158  1654 V EnterpriseBillingPolicyInternal: packageModificationReceiver - onreceive - personal application - profile null
,09-13 16:34:04.451  3896  6187 D KLMS-2.6.094: : DataSource(): Fetched Data from data base count : 0
,09-13 16:34:04.451  1158  1158 D SdpManagerService:  ActionReceiver::onReceive() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-13 16:34:04.451  1158  2005 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
09-13 16:34:04.451  1158  2005 D SettingsProvider: isChangeAllowed() : name = klm_eula_shown
09-13 16:34:04.451  1158  1158 D SdpManagerService: ACTION_PACKAGE_REMOVED Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } DATA= package:com.test.thalitest UID 1000 userId 0
09-13 16:34:04.451  1158  2005 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-13 16:34:04.451  1158  1158 D SdpManagerService: ACTION_PACKAGE_REMOVED packageName:: com.test.thalitest
09-13 16:34:04.451  1158  2005 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-13 16:34:04.451  1158  1158 D EnterprisePartitionManager: SND -> {secure_fs remove_enc_dir}
09-13 16:34:04.451  1158  2005 D SettingsProvider: selectionArgs: false
09-13 16:34:04.451  1158  2005 D SettingsProvider: selectionArgs: 10016
,09-13 16:34:04.451  1158  2005 D SettingsProvider: ret = -1
09-13 16:34:04.451   383   438 D epmd    : Partition obj created
09-13 16:34:04.451   383   438 D epmd    : Partition::dump============== 0
09-13 16:34:04.451   383   438 D epmd    : Partition::mType > INTERNAL-SDCARD mSrcPath > /data/knox/secure_fs/enc_user mMntPath > /data/enc_user
09-13 16:34:04.451   383   438 D epmd    : Partition::SDP > not supported
09-13 16:34:04.451   383   438 E epmd    : removeEncPkgDir ERROR
09-13 16:34:04.451   383   438 D epmd    : deleting Partition object.
09-13 16:34:04.451   383   438 W FrameworkListener: Handler 'secure_fs' error (No such file or directory)
09-13 16:34:04.451  1158  1424 D EnterprisePartitionManager: RCV <-
09-13 16:34:04.451  1158  1158 D EnterprisePartitionManager: RMV <-
09-13 16:34:04.451  1158  1158 D EnterprisePartitionManager: event : 281 3 remove_enc_dir failed
,09-13 16:34:04.461  1158  1158 D SdpManagerService: start document   : 
09-13 16:34:04.461  1158  1158 D SdpManagerService: start element    : engine_list
09-13 16:34:04.461  1158  1158 D SdpManagerService: start characters : 
09-13 16:34:04.461  1158  1158 D SdpManagerService: start element    : engine
09-13 16:34:04.461  1158  1158 D SdpManagerService:  attribte alias: android_0
09-13 16:34:04.461  1158  1158 D SdpManagerService:  attribte id: 0
09-13 16:34:04.461  1158  1158 D SdpManagerService: end element      : engine
09-13 16:34:04.461  1158  1158 D SdpManagerService: start characters : 
09-13 16:34:04.461  1158  1158 D SdpManagerService: end element      : engine_list
09-13 16:34:04.461  1158  1158 D SdpManagerService: end document     : 
,09-13 16:34:04.461  1158  1158 W System.err: mkdir failed: EEXIST (File exists) : /data/system/users/0
09-13 16:34:04.461  1158  1158 E SdpManagerService: cant make directory /data/system/users/0
09-13 16:34:04.461  1158  1158 D SdpManagerService: start document   : 
09-13 16:34:04.461  1158  1158 D SdpManagerService: start element    : user
09-13 16:34:04.461  1158  1158 D SdpManagerService: end element      : user
09-13 16:34:04.461  1158  1158 D SdpUtil : num:0 index-0
,09-13 16:34:04.461  1158  1158 D SdpUtil : detecected userId : 0
09-13 16:34:04.461  1158  1158 D SdpManagerService: end document     : 
09-13 16:34:04.461  1158  3556 D SSRM:bb : MSG_TYPE_APP_REMOVED::
09-13 16:34:04.461  1158  1158 E SdpManagerService: Can't find engine info [android_0]
09-13 16:34:04.461  1158  1158 V EnterpriseBillingAsyncHandler: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-13 16:34:04.461  1158  1654 V EnterpriseBillingPolicyInternal: packageModification -  start - android.intent.action.PACKAGE_FULLY_REMOVED
09-13 16:34:04.461  1158  1654 V EnterpriseBillingPolicyInternal: uID is 10136
09-13 16:34:04.461  1158  1654 V EnterpriseBillingPolicyInternal: Removed Packageuid is0
09-13 16:34:04.461  1158  1654 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-13 16:34:04.461  1158  1654 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-13 16:34:04.461  1158  1654 V EnterpriseBillingPolicyInternal: packageModificationReceiver - onreceive - personal application - profile null
,09-13 16:34:04.461  1158  3556 D SSRM:bb : MSG_TYPE_UID_REMOVED::
,09-13 16:34:04.471  1158  1158 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7ca8444 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{aad700d 1874:com.google.android.gms.persistent/u0a10}
,09-13 16:34:04.471  1158  1158 D AccessibilityManagerService: checkUniversalSwitchState start:
,09-13 16:34:04.471  1158  1412 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer
09-13 16:34:04.471  1158  1412 V MARsDBManager: getManagedPackagesFromDB!
,09-13 16:34:04.481  1158  2343 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7ca8444 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{629ccf2 2231:com.google.android.gms/u0a10}
,09-13 16:34:04.481  1158  2592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7ca8444 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{629ccf2 2231:com.google.android.gms/u0a10}
,09-13 16:34:04.491  1158  2670 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7ca8444 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{aad700d 1874:com.google.android.gms.persistent/u0a10}
,09-13 16:34:04.491  2231  6189 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-13 16:34:04.491  2231  6189 D AccountUtils: Clearing selected account for com.test.thalitest
,09-13 16:34:04.491  1874  1874 D GCM-PT  : Populating db of packages that use GCM
,09-13 16:34:04.511  1158  1169 I art     : Background partial concurrent mark sweep GC freed 26259(1839KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 4.057ms total 201.904ms
,09-13 16:34:04.511  2231  6189 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-13 16:34:04.511  1874  1874 W SQLiteLog: (28) failed to open "/data/user/0/com.google.android.gms/databases/gcm_registrar.db-journal" with flag (131138) and mode_t (1b0) due to error (30)
09-13 16:34:04.511  1874  1874 E SQLiteLog: (10) unixWrite() File Descriptor : 60 gets errno : 9
09-13 16:34:04.511  1874  1874 E SQLiteLog: (778) statement aborts at 16: [INSERT INTO packages(uid,package_name) VALUES (?,?)] 
,09-13 16:34:04.521  1874  1874 E SQLiteDatabase: Error inserting uid=0 package_name=com.google.android.gms
09-13 16:34:04.521  1874  1874 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
09-13 16:34:04.521  1874  1874 E SQLiteDatabase: #################################################################
09-13 16:34:04.521  1874  1874 E SQLiteDatabase: Error Code : 778 (SQLITE_IOERR_WRITE)
09-13 16:34:04.521  1874  1874 E SQLiteDatabase: Caused By : Disk I/O error occurred during 'write' operation.
09-13 16:34:04.521  1874  1874 E SQLiteDatabase: 	(disk I/O error (code 778))
09-13 16:34:04.521  1874  1874 E SQLiteDatabase: #################################################################
09-13 16:34:04.521  1874  1874 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
09-13 16:34:04.521  1874  1874 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:915)
09-13 16:34:04.521  1874  1874 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
09-13 16:34:04.521  1874  1874 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
09-13 16:34:04.521  1874  1874 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
09-13 16:34:04.521  1874  1874 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
09-13 16:34:04.521  1874  1874 E SQLiteDatabase: 	at com.google.android.gms.gcm.GcmPackageTracker.c(:com.google.android.gms:292)
09-13 16:34:04.521  1874  1874 E SQLiteDatabase: 	at com.google.android.gms.gcm.GcmPackageTracker.a(:com.google.android.gms:219)
09-13 16:34:04.521  1874  1874 E SQLiteDatabase: 	at com.google.android.gms.gcm.GcmPackageTracker.a(:com.google.android.gms:124)
09-13 16:34:04.521  1874  1874 E SQLiteDatabase: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(:com.google.android.gms:332)
09-13 16:34:04.521  1874  1874 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3637)
09-13 16:34:04.521  1874  1874 E SQLiteDatabase: 	at android.app.ActivityThread.access$2000(ActivityThread.java:223)
09-13 16:34:04.521  1874  1874 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1879)
09-13 16:34:04.521  1874  1874 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:34:04.521  1874  1874 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:158)
09-13 16:34:04.521  1874  1874 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:7231)
09-13 16:34:04.521  1874  1874 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 16:34:04.521  1874  1874 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
09-13 16:34:04.521  1874  1874 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
09-13 16:34:04.521  1874  1874 W GCM-PT  : Unable to add package to the database
,09-13 16:34:04.531  1158  2632 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7ca8444 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{aad700d 1874:com.google.android.gms.persistent/u0a10}
,09-13 16:34:04.531  1874  1874 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
09-13 16:34:04.531  1874  1874 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
09-13 16:34:04.531  1874  2237 W System.err: mkdir failed: EEXIST (File exists) : /data/user/0/com.google.android.gms/shared_prefs
09-13 16:34:04.531  1874  2237 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.gms/shared_prefs/nlp-prefs.xml
,09-13 16:34:04.541  2231  6189 W SQLiteLog: (28) failed to open "/data/user/0/com.google.android.gms/databases/phenotype.db" with flag (131138) and mode_t (0) due to error (30)
,09-13 16:34:04.541  2231  6189 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-13 16:34:04.541  2231  6189 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 16:34:04.541  2231  6189 E SQLiteDatabase: #################################################################
09-13 16:34:04.541  2231  6189 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
09-13 16:34:04.541  2231  6189 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
09-13 16:34:04.541  2231  6189 E SQLiteDatabase: #################################################################
09-13 16:34:04.541  2231  6189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 16:34:04.541  2231  6189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
09-13 16:34:04.541  2231  6189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
09-13 16:34:04.541  2231  6189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 16:34:04.541  2231  6189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 16:34:04.541  2231  6189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 16:34:04.541  2231  6189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 16:34:04.541  2231  6189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 16:34:04.541  2231  6189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 16:34:04.541  2231  6189 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:639)
09-13 16:34:04.541  2231  6189 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
09-13 16:34:04.541  2231  6189 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
09-13 16:34:04.541  2231  6189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 16:34:04.541  2231  6189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 16:34:04.541  2231  6189 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastIntentOperation.onHandleIntent(:com.google.android.gms:51)
09-13 16:34:04.541  2231  6189 E SQLiteDatabase: 	at com.google.android.chimera.IntentOperation.onHandleIntent(:com.google.android.gms:76)
09-13 16:34:04.541  2231  6189 E SQLiteDatabase: 	at com.google.android.chimera.container.l.run(:com.google.android.gms:801)
09-13 16:34:04.541  2231  6189 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 16:34:04.541  2231  6189 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 16:34:04.541  2231  6189 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-13 16:34:04.541  2231  6189 E PhenotypeInitializer: Could not unregister android package com.test.thalitest
09-13 16:34:04.541  2231  6189 E PhenotypeInitializer: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 16:34:04.541  2231  6189 E PhenotypeInitializer: #################################################################
09-13 16:34:04.541  2231  6189 E PhenotypeInitializer: Error Code : 0 (SQLITE_OK)
09-13 16:34:04.541  2231  6189 E PhenotypeInitializer: Caused By : not an error (code 0): Could not open the database in read/write mode.
09-13 16:34:04.541  2231  6189 E PhenotypeInitializer: ############################################,#####################
09-13 16:34:04.541  2231  6189 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 16:34:04.541  2231  6189 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
09-13 16:34:04.541  2231  6189 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
09-13 16:34:04.541  2231  6189 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 16:34:04.541  2231  6189 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 16:34:04.541  2231  6189 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 16:34:04.541  2231  6189 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 16:34:04.541  2231  6189 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 16:34:04.541  2231  6189 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 16:34:04.541  2231  6189 E PhenotypeInitializer: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:639)
09-13 16:34:04.541  2231  6189 E PhenotypeInitializer: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
09-13 16:34:04.541  2231  6189 E PhenotypeInitializer: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
09-13 16:34:04.541  2231  6189 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 16:34:04.541  2231  6189 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 16:34:04.541  2231  6189 E PhenotypeInitializer: 	at com.google.android.gms.app.service.PackageBroadcastIntentOperation.onHandleIntent(:com.google.android.gms:51)
09-13 16:34:04.541  2231  6189 E PhenotypeInitializer: 	at com.google.android.chimera.IntentOperation.onHandleIntent(:com.google.android.gms:76)
09-13 16:34:04.541  2231  6189 E PhenotypeInitializer: 	at com.google.android.chimera.container.l.run(:com.google.android.gms:801)
09-13 16:34:04.541  2231  6189 E PhenotypeInitializer: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 16:34:04.541  2231  6189 E PhenotypeInitializer: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 16:34:04.541  2231  6189 E PhenotypeInitializer: 	at java.lang.Thread.run(Thread.java:818)
,09-13 16:34:04.541  1158  1268 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7ca8444 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4af2cec 5671:com.android.vending/u0a19}

```
