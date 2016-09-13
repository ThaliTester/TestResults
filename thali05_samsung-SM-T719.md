#### Test 836273379690449_thali05_samsung-SM-T719 Logs


```
--------- beginning of system
09-13 14:17:26.231  1145  2078 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 14:17:26.231  1145  2078 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4390, temperature: 317, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 14:17:26.231  1145  2078 D BatteryService: online:4, current avg:167, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:175
09-13 14:17:26.231  1145  1145 D BatteryService: Sending ACTION_BATTERY_CHANGED.
--------- beginning of main
09-13 14:17:26.231  1693  1693 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 14:17:26.231  1693  1693 D PowerUI : priorPlugType = 2 mPlugType =  2
09-13 14:17:26.231  1693  1693 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 14:17:26.241  2605  2605 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 14:17:26.241  2605  3118 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-13 14:17:26.261  1693  1693 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 14:17:26.261  1693  1693 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 14:17:26.261  1693  1693 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 14:17:26.321  1145  3550 D SSRM:s  : SIOP:: AP = 350, PST = 383 (W:8), CP = 42, LCD = 0
09-13 14:17:26.321  1145  3550 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-13 14:17:26.591   726   726 I MSM-irqbalance: Decided to move IRQ327 from CPU0 to CPU3
09-13 14:17:26.671  5975  5975 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-13 14:17:26.671  5975  5975 D AndroidRuntime: CheckJNI is OFF
09-13 14:17:26.671  5975  5975 D AndroidRuntime: readGMSProperty: start
09-13 14:17:26.671  5975  5975 D AndroidRuntime: readGMSProperty: already setted!!
09-13 14:17:26.671  5975  5975 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-13 14:17:26.671  5975  5975 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-13 14:17:26.671  5975  5975 D AndroidRuntime: readGMSProperty: end
09-13 14:17:26.671  5975  5975 D AndroidRuntime: addProductProperty: start
09-13 14:17:26.701  5975  5975 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-13 14:17:26.741  5975  5975 I Radio-JNI: register_android_hardware_Radio DONE
09-13 14:17:26.741  5975  5975 E AffinityControl: AffinityControl: registerfunction enter
09-13 14:17:26.751  5975  5975 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-13 14:17:26.781  1145  1318 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
09-13 14:17:26.801  1145  1318 D GameManagerService: identifyGamePackage. com.test.thalitest
09-13 14:17:26.801  1145  1318 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-13 14:17:26.821  1145  1318 D ActivityManager: mDVFSHelper.acquire()
09-13 14:17:26.821   445   445 I SurfaceFlinger: id=13 createSurf (16x16),-1 flag=20004, EimLayer(Di
09-13 14:17:26.821   445   445 I SurfaceFlinger: id=14 createSurf (16x16),-1 flag=20004, EimLayer(An
09-13 14:17:26.831  1145  1145 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-13 14:17:26.831  1693  1693 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-13 14:17:26.831  1145  1318 D FocusedStackFrame: Set to : 0
09-13 14:17:26.831  1145  1145 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-13 14:17:26.831  1693  1693 D WallpaperService: MSG_WINDOW_RESIZED
09-13 14:17:26.831  1693  1693 D WallpaperService: updateSurface
09-13 14:17:26.831  1693  1693 V WallpaperService: Changes: creating=false format=false size=false
09-13 14:17:26.831  1693  1693 V WallpaperService: mWidth:2048 SurfaceWidth:2048 mHeight:2048 SurfaceHeigh:2048
09-13 14:17:26.831  1693  1693 D WallpaperService: relayout
09-13 14:17:26.831  1145  1318 V WindowManager: addAppToken: AppWindowToken{d0ed77eb3 token=Token{225f422 ActivityRecord{51e2ded u0 com.test.thalitest/.MainActivity t18}}} to stack=2 task=18 at 0
09-13 14:17:26.841  1693  1693 V WallpaperService: Wallpaper size has changed: (2048, 2048)
09-13 14:17:26.841  1145  1415 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{bca112b V.E...... R.....ID 0,0-0,0}
09-13 14:17:26.841  1145  1415 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-13 14:17:26.851  1145  1318 I ActivityManager: Start proc 5984:com.test.thalitest/u0a136 for activity com.test.thalitest/.MainActivity
09-13 14:17:26.851  5984  5984 E Zygote  : v2
09-13 14:17:26.851  5984  5984 I libpersona: KNOX_SDCARD checking this for 10136
09-13 14:17:26.851  1145  1318 D InputDispatcher: Focused application set to: xxxx
09-13 14:17:26.851  5984  5984 I libpersona: KNOX_SDCARD not a persona
09-13 14:17:26.861  5984  5984 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-13 14:17:26.861  5975  5975 D AndroidRuntime: Shutting down VM
09-13 14:17:26.861  1145  1620 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-13 14:17:26.861  5984  5984 E Zygote  : accessInfo : 0
09-13 14:17:26.861   445   445 I SurfaceFlinger: id=15 createSurf (1536x2048),1 flag=404, uhalitest
09-13 14:17:26.861  5984  5984 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-13 14:17:26.861  1145  1415 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 48 - 0, 0) vi=Rect(0, 48 - 0, 0) or=1
09-13 14:17:26.881  5984  5984 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 14:17:26.881  5984  5984 D ActivityThread: Added TimaKeyStore provider
09-13 14:17:26.891  1145  2016 D ActivityManager:  Launching com.test.thalitest, updated priority
09-13 14:17:26.891  1993  1993 V ActivityThread: updateVisibility : ActivityRecord{1435d24 token=android.os.BinderProxy@89403a3 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-13 14:17:26.891  1145  1145 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-13 14:17:26.891  1145  1380 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-13 14:17:26.901  1145  1415 V WindowStateAnimator: Finishing drawing window Window{b46ff21 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-13 14:17:26.921   445   473 I SurfaceFlinger: id=10 Removed MauncherAct (6/11)
09-13 14:17:26.921   445   475 I SurfaceFlinger: id=10 Removed MauncherAct (-2/11)
09-13 14:17:26.921  1993  1993 D Launcher: onTrimMemory. Level: 20
,09-13 14:17:27.201  1145  2016 I WindowManager: Screenshot max retries 4 of Token{225f422 ActivityRecord{51e2ded u0 com.test.thalitest/.MainActivity t18}} appWin=Window{b46ff21 u0 d0 Starting com.test.thalitest} drawState=4
09-13 14:17:27.201  1145  1620 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-13 14:17:27.211  1145  3550 D GameManagerService: identifyGamePackage. com.test.thalitest
09-13 14:17:27.221  1145  3550 D GameManagerService: identifyGamePackage. com.test.thalitest
09-13 14:17:27.251  1145  2664 W ActivityManager: Permission Denial: getCurrentUser() from pid=5984, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
09-13 14:17:27.261  5984  5984 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-13 14:17:27.261  5984  5984 D RelationGraph: garbageCollect()
09-13 14:17:27.281  1145  1953 W ActivityManager: Permission Denial: getCurrentUser() from pid=5984, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
09-13 14:17:27.291  5984  5984 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-13 14:17:27.321  5984  5984 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-13 14:17:27.341  5984  5984 I cr_LibraryLoader: Time to load native libraries: 9 ms (timestamps 9464-9473)
09-13 14:17:27.341  5984  5984 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-13 14:17:27.361  5984  5998 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-13 14:17:27.371  5984  5984 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {670ef81}
09-13 14:17:27.371  5984  5984 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-13 14:17:27.381  5984  5984 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 14:17:27.401  5984  5984 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-13 14:17:27.461  5984  5984 I Adreno  : QUALCOMM build                   : 971aff5, Ic07f1cdce3
09-13 14:17:27.461  5984  5984 I Adreno  : Build Date                       : 03/29/16
09-13 14:17:27.461  5984  5984 I Adreno  : OpenGL ES Shader Compiler Version: XE031.06.00.02
09-13 14:17:27.461  5984  5984 I Adreno  : Local Branch                     : 
09-13 14:17:27.461  5984  5984 I Adreno  : Remote Branch                    : refs/tags/AU_LINUX_ANDROID_LA.BR.1.3.3.C2.06.00.01.205.077
09-13 14:17:27.461  5984  5984 I Adreno  : Remote Branch                    : NONE
09-13 14:17:27.461  5984  5984 I Adreno  : Reconstruct Branch               : NOTHING
09-13 14:17:27.521  1145  1475 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10136
09-13 14:17:27.521  1145  1475 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:851 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29617 com.android.server.am.ActivityManagerService.registerReceiver:22639 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3995 
09-13 14:17:27.581  5984  5984 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
09-13 14:17:27.591  5984  5984 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
09-13 14:17:27.601  5984  5984 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
09-13 14:17:27.611  5984  5984 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
09-13 14:17:27.651  5984  5984 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-13 14:17:27.661  5984  5984 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{af40186 I.E...... R.....ID 0,0-0,0}
09-13 14:17:27.661  5984  6022 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-13 14:17:27.671  1145  1475 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-13 14:17:27.671  1145  1475 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-13 14:17:27.671  1145  1145 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-13 14:17:27.671  1145  1145 I KnoxTimeoutHandler: Shared devices show user statefalse
09-13 14:17:27.681  5984  5998 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
09-13 14:17:27.691  5984  5984 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10136, CallingPid : 5984
09-13 14:17:27.691  1145  2665 D ConnectivityService: listenForNetwork for Listen from uid/pid:10136/5984 for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 14:17:27.691  1145  1629 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
09-13 14:17:27.691  1145  1629 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,fe80::4678:3eff:feeb:95ef/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-13 14:17:27.691  1145  1629 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
09-13 14:17:27.691  1145  1629 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-13 14:17:27.691  1145  1629 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
09-13 14:17:27.691  1145  1629 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-13 14:17:27.691  1145  1629 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
09-13 14:17:27.691  1145  1629 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 14:17:27.701  5984  5984 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-13 14:17:27.711   445   445 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=404, NainActivit
09-13 14:17:27.721  5984  6022 I OpenGLRenderer: Initialized EGL, version 1.4
09-13 14:17:27.731  5984  5984 V ActivityThread: updateVisibility : ActivityRecord{4addc99 token=android.os.BinderProxy@48f777c {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-13 14:17:27.741  5984  5984 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 48 - 0, 0) vi=Rect(0, 48 - 0, 0) or=1
09-13 14:17:27.771  5984  6022 E libGLESv2: HWUI Protection: wrong call from hwui context F: ES3-glCreateProgramSEC
09-13 14:17:27.811  1145  2078 V WindowStateAnimator: Finishing drawing window Window{81d78a6 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
09-13 14:17:27.811  5984  5984 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@48f777c time:89945
09-13 14:17:27.811  1145  1415 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-13 14:17:27.811  1145  1145 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-13 14:17:27.811  1145  1415 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +611ms (total +975ms)
09-13 14:17:27.811  1145  1145 I KnoxTimeoutHandler: SD activityfalse
09-13 14:17:27.811  1145  1145 I KnoxTimeoutHandler: Fullscreen and mCurrent is not KNOX user. Hence hide keyguard
09-13 14:17:27.811  1145  1415 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{51e2ded u0 com.test.thalitest/.MainActivity t18} time:89949
09-13 14:17:27.811  1145  1415 D ActivityManager: mDVFSHelper.release()
09-13 14:17:27.811  1145  1415 D ViewRootImpl: #3 mView = null
09-13 14:17:27.821   445   473 I SurfaceFlinger: id=15 Removed uhalitest (6/11)
09-13 14:17:27.821   445   475 I SurfaceFlinger: id=15 Removed uhalitest (-2/11)
09-13 14:17:27.821  5984  6027 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 14:17:27.871  5984  5984 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5984
,09-13 14:17:28.071  5984  5984 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 14:17:28.191  5984  6033 D jxcore_app_log: JniHelper::setJavaVM(0xf4a7c000), pthread_self() = -616302288
09-13 14:17:28.201  5984  6033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 14:17:28.201  5984  6033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 14:17:28.201  5984  6033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 14:17:28.201  5984  6033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 14:17:28.201  5984  6033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-13 14:17:28.201  5984  6033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@85d836 added. We now have 1 listener(s)
09-13 14:17:28.201  5984  6033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:EB:95:EE
09-13 14:17:28.201  5984  6033 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-13 14:17:28.201  5984  6033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 14:17:28.201  5984  6033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 14:17:28.211  5984  6033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 14:17:28.211  5984  6033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 14:17:28.211  5984  6033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 14:17:28.211  5984  6033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:78:3E:EB:95:EE
09-13 14:17:28.211  5984  6033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 14:17:28.211  5984  6033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 14:17:28.211  5984  6033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 14:17:28.211  5984  6033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 14:17:28.211  5984  6033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 14:17:28.211  5984  6033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 14:17:28.211  5984  6033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 14:17:28.211  5984  6033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 14:17:28.211  5984  6033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 14:17:28.211  5984  6033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-13 14:17:28.211  5984  6033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cbae0d added. We now have 1 listener(s)
09-13 14:17:28.211  5984  6033 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 14:17:28.211  5984  6033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 14:17:28.211  5984  6033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-13 14:17:28.211  5984  6033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 14:17:28.211  5984  6033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 14:17:28.211  5984  6033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-13 14:17:28.211  5984  6033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:17:28.211  5984  6033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:EB:95:EE
,09-13 14:17:28.221  5984  6033 D BluetoothAdapter: STATE_ON
,09-13 14:17:28.221  5984  6033 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-13 14:17:28.221  5984  6033 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:17:28.221  5984  6033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:17:28.221  5984  6033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 14:17:28.221  5984  6033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:17:28.221  5984  6033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:17:28.221  5984  6033 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:17:28.221  5984  6033 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:17:28.221  5984  6033 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 14:17:28.221  5984  6033 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 14:17:28.221  5984  6033 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 14:17:28.221  5984  6033 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 14:17:28.231  5984  5984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:17:28.231  5984  5984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:17:28.241  5984  5984 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 14:17:28.671  1797  1797 D Recents : onTaskStackChanged
,09-13 14:17:28.691  5984  6034 W jxcore-log: Initializing JXcore engine
09-13 14:17:28.691  5984  6034 W jxcore-log: JXcore engine is ready
,09-13 14:17:28.721  2611  2611 E audit   : type=1400 msg=audit(1473769048.721:271): avc:  denied  { ioctl } for  pid=6034 comm="Thread-112" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5531 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-13 14:17:28.721  2611  2611 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-13 14:17:28.721  2611  2611 E audit   : type=1300 msg=audit(1473769048.721:271): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=7 a1=5451 a2=3 a3=db33a3c8 items=0 ppid=599 pid=6034 auid=4294967295 uid=10136 gid=10136 euid=10136 suid=10136 fsuid=10136 egid=10136 sgid=10136 fsgid=10136 ses=4294967295 tty=(none) comm="Thread-112" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-13 14:17:28.721  2611  2611 E audit   : type=1327 msg=audit(1473769048.721:271): proctitle="com.test.thalitest"
09-13 14:17:28.721  2611  2611 E audit   : type=1320 msg=audit(1473769048.721:271): 
09-13 14:17:28.721  2611  2611 E audit   : type=1400 msg=audit(1473769048.721:272): avc:  denied  { ioctl } for  pid=6034 comm="Thread-112" path="socket:[43363]" dev="sockfs" ino=43363 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-13 14:17:28.721  2611  2611 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-13 14:17:28.721  2611  2611 E audit   : type=1300 msg=audit(1473769048.721:272): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3c a1=5451 a2=3 a3=db33a3c8 items=0 ppid=599 pid=6034 auid=4294967295 uid=10136 gid=10136 euid=10136 suid=10136 fsuid=10136 egid=10136 sgid=10136 fsgid=10136 ses=4294967295 tty=(none) comm="Thread-112" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-13 14:17:28.721  2611  2611 E audit   : type=1327 msg=audit(1473769048.721:272): proctitle="com.test.thalitest"
09-13 14:17:28.721  2611  2611 E audit   : type=1320 msg=audit(1473769048.721:272): 
09-13 14:17:28.731  5984  6034 W jxcore-log: Starting JXcore engine
,09-13 14:17:28.781  5984  6034 W jxcore-log: Platform android
09-13 14:17:28.781  5984  6034 W jxcore-log: 
09-13 14:17:28.781  5984  6034 W jxcore-log: Process ARCH arm
09-13 14:17:28.781  5984  6034 W jxcore-log: 
,09-13 14:17:28.871  5984  6034 I jxcore-log: JXcore Cordova bridge is ready!
09-13 14:17:28.871  5984  6034 I jxcore-log: 
09-13 14:17:28.871  5984  6034 W jxcore-log: JXcore engine is started
,09-13 14:17:28.881  5984  6033 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-13 14:17:28.881  5984  5984 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 14:17:29.171  1145  3580 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 14:17:29.841  1145  1662 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/18_task.xml.bak
,09-13 14:17:30.221  1145  3550 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-13 14:17:34.171  1145  3580 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 14:17:34.471  5984  6034 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 14:17:34.471  5984  6034 I jxcore-log: 
,09-13 14:17:34.481  5984  6034 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 14:17:34.481  5984  6034 I jxcore-log: 
,09-13 14:17:34.491  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:34.491  5984  6034 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:17:34.491  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:17:34.491  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 14:17:34.491  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:17:34.491  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:17:34.491  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:17:34.491  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:17:34.491  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 14:17:34.491  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:34.501  5984  6034 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 14:17:34.501  5984  6034 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 14:17:34.501  5984  6034 I jxcore-log: 
,09-13 14:17:34.501  5984  6034 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 14:17:34.501  5984  6034 I jxcore-log: 
,09-13 14:17:34.811  5984  6034 I jxcore-log: Unit Test app is loaded
09-13 14:17:34.811  5984  6034 I jxcore-log: 
,09-13 14:17:34.811  5984  6034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:17:34.811  5984  6034 I jxcore-log: 
,09-13 14:17:34.811  5984  6034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 14:17:34.811  5984  6034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@702a444 added. We now have 2 listener(s)
09-13 14:17:34.811  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-13 14:17:34.811  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 14:17:34.811  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 14:17:34.811  5984  6034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 14:17:34.811  5984  6034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4d92d added. We now have 2 listener(s)
09-13 14:17:34.811  5984  6034 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 14:17:34.821  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 14:17:34.821  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:17:34.831  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:34.841  5984  6034 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:17:34.841  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:17:34.841  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 14:17:34.841  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:17:34.841  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:17:34.841  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:17:34.841  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:17:34.841  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 14:17:34.841  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:34.841  5984  6034 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 14:17:34.841  5984  6034 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 14:17:34.841  5984  6034 D ExecuteNativeTests: Running unit tests
09-13 14:17:34.841  5984  6034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 14:17:34.841  5984  6034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b83bf3 added. We now have 3 listener(s)
09-13 14:17:34.841  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-13 14:17:34.841  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 14:17:34.841  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 14:17:34.841  5984  6034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 14:17:34.841  5984  6034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ea7c0b0 added. We now have 3 listener(s)
09-13 14:17:34.841  5984  6034 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 14:17:34.851  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 14:17:34.851  5984  5984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:17:34.851  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:17:34.851  5984  5984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-13 14:17:34.851  5984  5984 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-13 14:17:34.861  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:34.861  5984  6034 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:17:34.861  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:17:34.861  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 14:17:34.861  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:17:34.861  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:17:34.861  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:17:34.861  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:17:34.861  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 14:17:34.871  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:34.871  5984  6034 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 14:17:34.871  5984  6034 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 14:17:34.881  5984  5984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-13 14:17:34.881  5984  5984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:17:35.801  3794  3794 D FactoryTest: User mode
,09-13 14:17:35.801  3794  3794 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
09-13 14:17:35.801  3794  3794 D MTPRx   : still no open session command from host, so toast
,09-13 14:17:35.811  1145  2382 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
,09-13 14:17:35.821  1145  2382 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
09-13 14:17:35.821  1145  2382 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.samsung.android.MtpApplication)
,09-13 14:17:35.831  1145  2382 D ActivityManager: mDVFSHelper.acquire()
,09-13 14:17:35.831  1145  2382 V WindowManager: addAppToken: AppWindowToken{d0d049673 token=Token{87d92e2 ActivityRecord{d2a0fad u0 com.samsung.android.MtpApplication/.USBConnection t19}}} to stack=2 task=19 at 0
,09-13 14:17:35.831  1145  2382 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,09-13 14:17:35.841  1145  1380 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
09-13 14:17:35.841  1145  1145 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
,09-13 14:17:35.851  1145  2382 D InputDispatcher: Focused application set to: xxxx
,09-13 14:17:35.851  3794  3794 E MTPRx   : started activity for popup
,09-13 14:17:35.861  3794  3794 D RelationGraph: garbageCollect()
09-13 14:17:35.861  3794  3794 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-13 14:17:35.871  1145  3550 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,09-13 14:17:35.881  3794  3794 D MTPUSBConnection: onCreate in USBConnection
09-13 14:17:35.881  3794  3794 V MTPUSBConnection: Registering broadcast receiver.
,09-13 14:17:35.881  3794  3794 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,09-13 14:17:35.881  1145  2664 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,09-13 14:17:35.921  3794  3794 D TAG     : dev.kiessupport is : TRUE
,09-13 14:17:35.961  3794  3794 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-13 14:17:35.961  3794  3794 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{942ae3e V.E...... R.....I. 0,0-0,0}
,09-13 14:17:35.961  3794  6036 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-13 14:17:35.971  3794  3794 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{84ee431 I.E...... R.....I. 0,0-0,0}
,09-13 14:17:35.981  1145  2004 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
09-13 14:17:35.981  1145  2004 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-13 14:17:35.981  1145  1145 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-13 14:17:35.981  1145  1145 I KnoxTimeoutHandler: Shared devices show user statefalse
09-13 14:17:35.981  1145  1145 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,09-13 14:17:36.001   445   445 I SurfaceFlinger: id=17 createSurf (97x97),1 flag=4, VSBConnecti
,09-13 14:17:36.011  3794  6036 I Adreno  : QUALCOMM build                   : 971aff5, Ic07f1cdce3
09-13 14:17:36.011  3794  6036 I Adreno  : Build Date                       : 03/29/16
09-13 14:17:36.011  3794  6036 I Adreno  : OpenGL ES Shader Compiler Version: XE031.06.00.02
09-13 14:17:36.011  3794  6036 I Adreno  : Local Branch                     : 
09-13 14:17:36.011  3794  6036 I Adreno  : Remote Branch                    : refs/tags/AU_LINUX_ANDROID_LA.BR.1.3.3.C2.06.00.01.205.077
09-13 14:17:36.011  3794  6036 I Adreno  : Remote Branch                    : NONE
09-13 14:17:36.011  3794  6036 I Adreno  : Reconstruct Branch               : NOTHING
,09-13 14:17:36.021  3794  6036 I OpenGLRenderer: Initialized EGL, version 1.4
,09-13 14:17:36.041   445   445 I SurfaceFlinger: id=18 createSurf (129x129),1 flag=4, VSBConnecti
,09-13 14:17:36.071  3794  3794 V ActivityThread: updateVisibility : ActivityRecord{24c7a84 token=android.os.BinderProxy@21d1c46 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,09-13 14:17:36.081  3794  6036 E libGLESv2: HWUI Protection: wrong call from hwui context F: ES3-glCreateProgramSEC
,09-13 14:17:36.091  3794  6036 E libGLESv2: HWUI Protection: wrong call from hwui context F: ES3-glCreateProgramSEC
,09-13 14:17:36.091  3794  6036 E libGLESv2: HWUI Protection: wrong call from hwui context F: ES3-glCreateProgramSEC
,09-13 14:17:36.101  1145  2016 V WindowStateAnimator: Finishing drawing window Window{80a60eb u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-13 14:17:36.101  1145  1317 V WindowStateAnimator: Finishing drawing window Window{92134e1 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-13 14:17:36.101  3794  3794 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-13 14:17:36.101  3794  3794 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,09-13 14:17:36.111  1145  1415 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-13 14:17:36.111  1145  1145 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-13 14:17:36.111  1145  2665 V WindowStateAnimator: Finishing drawing window Window{80a60eb u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,09-13 14:17:36.111  1145  1145 I KnoxTimeoutHandler: SD activityfalse
09-13 14:17:36.111  1145  2316 V WindowStateAnimator: Finishing drawing window Window{92134e1 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
09-13 14:17:36.111  3794  3794 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@21d1c46 time:98247
09-13 14:17:36.111  1145  1415 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +268ms (total +283ms)
,09-13 14:17:36.111  1145  1415 D ActivityManager: mDVFSHelper.release()
09-13 14:17:36.111  1145  1415 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{d2a0fad u0 com.samsung.android.MtpApplication/.USBConnection t19} time:98248
,09-13 14:17:36.281  1145  1720 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 14:17:36.281  1145  1720 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4371, temperature: 316, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 14:17:36.281  1145  1720 D BatteryService: online:4, current avg:162, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:144
09-13 14:17:36.281  1145  1145 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 14:17:36.281  1693  1693 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 14:17:36.281  1693  1693 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 14:17:36.281  1693  1693 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-13 14:17:36.291  2605  2605 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 14:17:36.291  2605  3118 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 14:17:36.311  1693  1693 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-13 14:17:36.311  1693  1693 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 14:17:36.311  1693  1693 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 14:17:36.351  1145  3550 D SSRM:s  : SIOP:: AP = 380, PST = 383 (W:9), CP = 46, LCD = 0
,09-13 14:17:36.351  1145  3550 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 14:17:36.891  1145  1423 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-13 14:17:36.911  1145  1423 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-13 14:17:36.981  1797  1797 D Recents : onTaskStackChanged
,09-13 14:17:36.991  1145  1475 D PackageManager: getComponentMetadataForIconTray : com.test.thalitest.MainActivity does not exist in mServices
09-13 14:17:36.991  1145  1475 D PackageManager: getComponentMetadataForIconTray : com.test.thalitest.MainActivity does not exist in mProviders
09-13 14:17:36.991  1145  1475 D PackageManager: getComponentMetadataForIconTray : com.test.thalitest.MainActivity does not exist in mReceivers
,09-13 14:17:37.001  1797  1797 I ApplicationPackageManager: load=com.test.thalitest, bg=96-96, dr=96-96
,09-13 14:17:37.001  1797  1797 I ApplicationPackageManager: scaled rate=0.98086953, size=96, alpha=2, hold=26, target=96
,09-13 14:17:39.181  1145  3580 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 14:17:41.621   726   726 I MSM-irqbalance: Decided to move IRQ200 from CPU0 to CPU3
,09-13 14:17:44.921  5984  6034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 14:17:44.921  5984  6034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebe099 added. We now have 4 listener(s)
,09-13 14:17:44.921  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-13 14:17:44.921  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 14:17:44.921  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 14:17:44.921  5984  6034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 14:17:44.921  5984  6034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2336f5e added. We now have 4 listener(s)
09-13 14:17:44.921  5984  6034 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 14:17:44.921  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 14:17:44.931  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:17:44.941  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:44.941  5984  6034 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:17:44.941  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:17:44.941  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 14:17:44.941  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:17:44.941  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:17:44.941  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:17:44.941  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:17:44.941  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 14:17:44.951  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:44.951  5984  6034 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 14:17:44.951  5984  6034 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 14:17:44.961  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:44.961  5984  5984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:17:44.961  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 14:17:44.961  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:17:44.961  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:17:44.961  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:17:44.961  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:17:44.961  5984  5984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:17:44.961  5984  6034 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-13 14:17:44.961  5984  6034 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 14:17:44.961  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 14:17:44.961  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:17:44.961  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:17:44.961  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:17:44.961  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:17:44.961  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:17:44.961  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 14:17:44.961  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:17:44.961  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 14:17:44.961  5984  6034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebe099 removed from the list
09-13 14:17:44.961  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:17:44.961  5984  6034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2336f5e removed from the list
09-13 14:17:44.961  5984  6034 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:17:44.961  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported,
09-13 14:17:44.971  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:17:44.971  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:44.971  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:44.971  5984  6034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebe099 not in the list,
09-13 14:17:44.971  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:17:44.971  5984  6034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2336f5e not in the list
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:17:44.971  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:44.971  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 14:17:44.971  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:17:44.971  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:44.971  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:44.971  5984  6034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebe099 not in the list
09-13 14:17:44.971  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:17:44.971  5984  6034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2336f5e not in the list
09-13 14:17:44.971  5984  6034 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:17:44.971  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:44.971  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:44.971  5984  6034 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-13 14:17:44.981  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:17:44.981  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:44.991  5984  6034 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:17:44.991  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:17:44.991  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 14:17:44.991  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:17:44.991  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:17:44.991  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:17:44.991  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:17:44.991  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 14:17:44.991  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:45.001  5984  6034 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 14:17:45.001  5984  6034 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 14:17:45.001  5984  6034 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-13 14:17:45.001  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-13 14:17:45.001  5984  6034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 14:17:45.001  5984  6034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 14:17:45.001  5984  6034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 14:17:45.001  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:17:45.001  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 14:17:45.001  5984  5984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:17:45.001  5984  6034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 14:17:45.001  5984  6034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 14:17:45.001  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 14:17:45.001  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 14:17:45.001  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:17:45.001  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 14:17:45.001  5984  5984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:17:45.001  5984  5984 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 14:17:45.011  5984  6041 D BluetoothSocket: bindListen(): myUserId = 0
09-13 14:17:45.011  5984  6041 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 14:17:45.011  5984  6034 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 14:17:45.011  5984  6034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 14:17:45.011  5984  6041 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-13 14:17:45.011  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:45.011  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:45.021  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:45.021  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 14:17:45.021  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:45.021  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:45.021  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 14:17:45.021  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 14:17:45.021  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:45.031  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 14:17:45.031  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-13 14:17:45.031  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 44 78 3E EB 95 EE
09-13 14:17:45.031  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:17:45.031  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:17:45.031  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 14:17:45.031  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:45.031  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:45.031  5984  6034 D BluetoothLeAdvertiser: start advertising
09-13 14:17:45.031  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:45.041  2605  2623 D BtGatt.GattService: registerClient() - UUID=3a1d5ae9-ffd0-4daf-b32a-5148636b613f
,09-13 14:17:45.091  2605  2758 D BtGatt.GattService: onClientRegistered() - UUID=3a1d5ae9-ffd0-4daf-b32a-5148636b613f, clientIf=6
,09-13 14:17:45.091  5984  5995 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
09-13 14:17:45.091  2605  2624 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-13 14:17:45.091  2605  2624 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:17:45.091  2605  2624 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:17:45.091  2605  2815 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-13 14:17:45.091  2605  2815 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
,09-13 14:17:45.091  2605  2799 D BtGatt.AdvertiseManager: message : 0
,09-13 14:17:45.091  2605  2799 D BtGatt.AdvertiseManager: number of adv instance running = 0
09-13 14:17:45.091  2605  2799 D BtGatt.AdvertiseManager: size of list is =0
,09-13 14:17:45.091  2605  2799 D BtGatt.AdvertiseManager: starting advertising
,09-13 14:17:45.101  2605  2799 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-13 14:17:45.101  3033  3036 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
,09-13 14:17:45.101  1145  2004 V AlarmManager:  remove PendingIntent] PendingIntent{ca661bf: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}},
09-13 14:17:45.101  2605  2815 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 20
09-13 14:17:45.101  3033  3036 I WCNSS_FILTER: do_write: IBS write: fd
,09-13 14:17:45.101  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 28 : bytes_written: 28
,09-13 14:17:45.101  3033  3033 I WCNSS_FILTER: do_write: IBS write: fc
,09-13 14:17:45.111  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 14:17:45.111  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
09-13 14:17:45.111  1145  1317 V AlarmManager:  remove PendingIntent] PendingIntent{d5a008c: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:45.111  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 14:17:45.111  2605  2815 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24562817
09-13 14:17:45.111  2605  2815 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-13 14:17:45.111  2605  2815 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,09-13 14:17:45.111  2605  2758 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
09-13 14:17:45.111  2605  2815 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-13 14:17:45.111  1145  2382 V AlarmManager:  remove PendingIntent] PendingIntent{3c513d5: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}},
09-13 14:17:45.111  2605  2799 D BtGatt.AdvertiseManager: starting multi advertising
09-13 14:17:45.111  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 38 : bytes_written: 38
,09-13 14:17:45.111  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8,
09-13 14:17:45.111  2605  2758 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
09-13 14:17:45.111  1145  1953 V AlarmManager:  remove PendingIntent] PendingIntent{2b287ea: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:45.111  2605  2799 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-13 14:17:45.111  2605  2799 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-13 14:17:45.111  2605  2799 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
09-13 14:17:45.111  2605  2799 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
09-13 14:17:45.111  5984  5994 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
09-13 14:17:45.111  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 14:17:45.111  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 14:17:45.111  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-13 14:17:45.121  1145  2664 V AlarmManager:  remove PendingIntent] PendingIntent{4695adb: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:45.121  5984  6034 I io.jxcore.node.ConnectionHelper: start: OK
09-13 14:17:45.121  5984  5984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 14:17:45.121  5984  5984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 14:17:45.121  5984  5984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 14:17:45.121  5984  5984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 14:17:45.121  5984  5984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 14:17:45.121  5984  5984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 14:17:45.121  1145  2016 V AlarmManager:  remove PendingIntent] PendingIntent{aec9978: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:45.121  5984  5984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 14:17:45.121  5984  5984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 14:17:45.211  1145  1589 V AlarmManager: Expired Alarm result :4
,09-13 14:17:45.211  1145  1380 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{12938b6 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2707753 1872:com.google.android.gms.persistent/u0a10}
,09-13 14:17:45.211  1145  2664 V AlarmManager:  remove PendingIntent] PendingIntent{98c9b7: PendingIntentRecord{2f36b47 com.google.android.gms broadcastIntent}}
,09-13 14:17:45.311  1145  2664 V AlarmManager:  remove PendingIntent] PendingIntent{face88d: PendingIntentRecord{2f36b47 com.google.android.gms broadcastIntent}}
,09-13 14:17:45.471  1872  6046 I VacuumService: Vacuum at: now=1473769065488 tag=VacuumService
,09-13 14:17:45.551  1145  1720 V AlarmManager:  remove PendingIntent] PendingIntent{3e51f90: PendingIntentRecord{2f36b47 com.google.android.gms broadcastIntent}}
,09-13 14:17:45.621  5984  6034 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 14:17:45.621  5984  6034 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-13 14:17:45.621  5984  6034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-13 14:17:45.621  5984  6034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 14:17:45.621  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 14:17:45.621  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 14:17:45.621  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 14:17:45.621  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
09-13 14:17:45.621  5984  6034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 14:17:45.621  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 14:17:45.621  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 14:17:45.621  5984  5984 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 14:17:45.621  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 14:17:45.621  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 14:17:45.621  5984  6041 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 14:17:45.621  5984  6041 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 14:17:45.621  5984  6041 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 14:17:45.621  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 14:17:45.621  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:45.631  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:45.631  5984  6034 D BluetoothLeScanner: could not find callback wrapper
09-13 14:17:45.631  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 14:17:45.631  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 14:17:45.631  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:45.631  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:45.631  5984  6034 D BluetoothLeAdvertiser: stop advertising
,09-13 14:17:45.631  2605  2623 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:17:45.631  2605  2623 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:17:45.631  2605  2815 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
09-13 14:17:45.631  2605  2815 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
09-13 14:17:45.631  2605  2815 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 14:17:45.631  2605  2815 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-13 14:17:45.631  2605  2815 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
09-13 14:17:45.631  2605  2799 D BtGatt.AdvertiseManager: message : 1
,09-13 14:17:45.641  2605  2799 D BtGatt.AdvertiseManager: stop advertise for client =  6
09-13 14:17:45.641  2605  2799 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
,09-13 14:17:45.641  2605  2799 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
09-13 14:17:45.641  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
,09-13 14:17:45.641  1145  1318 V AlarmManager:  remove PendingIntent] PendingIntent{18c8089: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:45.641  3033  3033 I WCNSS_FILTER: do_write: IBS write: fc
,09-13 14:17:45.641  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 14:17:45.641  3033  3036 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 14:17:45.641  2605  2758 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-13 14:17:45.641  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
09-13 14:17:45.641  2605  2758 D BtGatt.GattService: Client app is not null!
09-13 14:17:45.641  5984  5995 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
09-13 14:17:45.641  2605  2624 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 14:17:45.641  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 14:17:45.641  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 14:17:45.641  1145  2316 V AlarmManager:  remove PendingIntent] PendingIntent{af2a88e: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:45.641  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 14:17:45.641  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 14:17:45.641  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 14:17:45.641  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 14:17:45.641  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 14:17:45.641  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 14:17:45.651  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 14:17:45.651  1145  2382 V AlarmManager:  remove PendingIntent] PendingIntent{48138af: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:45.651  5984  5984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 14:17:45.651  5984  5984 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-13 14:17:45.651  5984  5984 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 14:17:45.651  5984  6034 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-13 14:17:45.651  5984  6034 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-13 14:17:45.651  5984  6034 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-13 14:17:45.651  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-13 14:17:45.651  5984  5984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:17:45.651  5984  5984 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 14:17:45.651  5984  5984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:17:45.651  5984  5984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 14:17:45.651  5984  6034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 14:17:45.651  5984  6034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 14:17:45.651  5984  6034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 14:17:45.651  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:17:45.651  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 14:17:45.651  5984  6034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 14:17:45.651  5984  6034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 14:17:45.651  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 14:17:45.651  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 14:17:45.651  5984  5984 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 14:17:45.651  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:17:45.651  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 14:17:45.651  5984  6048 D BluetoothSocket: bindListen(): myUserId = 0
09-13 14:17:45.651  5984  6048 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 14:17:45.651  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
09-13 14:17:45.651  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-13 14:17:45.661  1145  2004 V AlarmManager:  remove PendingIntent] PendingIntent{432b0cb: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:45.661  5984  6034 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 14:17:45.661  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 14:17:45.661  5984  6034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 14:17:45.661  5984  6048 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-13 14:17:45.661  1145  1832 E Watchdog: !@Sync 3 [09-13 14:17:45.671]
,09-13 14:17:45.661  1145  1953 V AlarmManager:  remove PendingIntent] PendingIntent{37550a8: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:45.661  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:45.661  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:45.661  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:45.661  1145  2004 V AlarmManager:  remove PendingIntent] PendingIntent{176b7c1: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:45.661  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 14:17:45.671  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:45.671  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:45.671  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 14:17:45.671  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 14:17:45.671  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:45.671  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 14:17:45.671  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:EB:95:EE",
09-13 14:17:45.671  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 44 78 3E EB 95 EE
09-13 14:17:45.671  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:17:45.671  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:17:45.671  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 14:17:45.671  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:45.671  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:45.671  5984  6034 D BluetoothLeAdvertiser: start advertising
,09-13 14:17:45.671  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:45.681  2605  3115 D BtGatt.GattService: registerClient() - UUID=d40dde41-b490-4ab5-82a2-a33320f02c21
,09-13 14:17:45.731  2605  2758 D BtGatt.GattService: onClientRegistered() - UUID=d40dde41-b490-4ab5-82a2-a33320f02c21, clientIf=6
09-13 14:17:45.731  5984  5995 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 14:17:45.731  2605  2624 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-13 14:17:45.731  2605  2624 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:17:45.731  2605  2624 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:17:45.731  2605  2815 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-13 14:17:45.731  2605  2815 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
,09-13 14:17:45.731  2605  2799 D BtGatt.AdvertiseManager: message : 0
,09-13 14:17:45.731  2605  2799 D BtGatt.AdvertiseManager: number of adv instance running = 0
09-13 14:17:45.731  2605  2799 D BtGatt.AdvertiseManager: size of list is =0
,09-13 14:17:45.731  2605  2799 D BtGatt.AdvertiseManager: starting advertising
,09-13 14:17:45.731  2605  2799 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-13 14:17:45.731  1145  1720 V AlarmManager:  remove PendingIntent] PendingIntent{bcf3b66: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:45.731  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 28 : bytes_written: 28
,09-13 14:17:45.731  3033  3033 I WCNSS_FILTER: do_write: IBS write: fc
,09-13 14:17:45.731  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 14:17:45.731  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
,09-13 14:17:45.731  2605  2758 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
09-13 14:17:45.731  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 14:17:45.731  1145  1317 V AlarmManager:  remove PendingIntent] PendingIntent{2398ea7: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:45.731  2605  2799 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 14:17:45.731  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 38 : bytes_written: 38
09-13 14:17:45.741  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-13 14:17:45.741  2605  2758 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
09-13 14:17:45.741  2605  2799 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-13 14:17:45.741  2605  2799 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-13 14:17:45.741  2605  2799 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
09-13 14:17:45.741  2605  2799 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
09-13 14:17:45.741  5984  5994 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
09-13 14:17:45.741  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 14:17:45.741  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 14:17:45.741  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 14:17:45.741  1145  1910 V AlarmManager:  remove PendingIntent] PendingIntent{822cf54: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:45.741  2605  2815 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 21
09-13 14:17:45.741  2605  2815 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24562817
09-13 14:17:45.741  2605  2815 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-13 14:17:45.741  2605  2815 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 14:17:45.741  2605  2815 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-13 14:17:45.741  5984  6034 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 14:17:45.741  5984  5984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 14:17:45.741  5984  5984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 14:17:45.741  5984  5984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 14:17:45.741  5984  5984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 14:17:45.741  5984  5984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 14:17:45.741  5984  5984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-13 14:17:45.741  1145  1953 V AlarmManager:  remove PendingIntent] PendingIntent{f60efd: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:45.741  5984  5984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 14:17:45.741  5984  5984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 14:17:45.751  1145  2078 V AlarmManager:  remove PendingIntent] PendingIntent{603a7f2: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:45.751  1145  2016 V AlarmManager:  remove PendingIntent] PendingIntent{3e66e43: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:46.251  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 14:17:46.251  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 14:17:46.251  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 14:17:46.251  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 14:17:46.251  5984  6048 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 14:17:46.251  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
,09-13 14:17:46.251  5984  6048 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 14:17:46.251  5984  6034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 14:17:46.251  5984  6048 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 14:17:46.251  5984  6034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebe099 not in the list
09-13 14:17:46.251  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:17:46.251  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 14:17:46.251  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 14:17:46.251  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 14:17:46.251  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 14:17:46.251  5984  5984 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 14:17:46.251  5984  5984 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 14:17:46.251  5984  5984 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-13 14:17:46.251  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:46.251  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:46.251  5984  6034 D BluetoothLeScanner: could not find callback wrapper
09-13 14:17:46.251  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 14:17:46.251  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 14:17:46.251  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:46.251  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:46.251  5984  6034 D BluetoothLeAdvertiser: stop advertising
,09-13 14:17:46.251  2605  3115 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 14:17:46.251  2605  3115 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 14:17:46.251  2605  2815 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
09-13 14:17:46.251  2605  2799 D BtGatt.AdvertiseManager: message : 1
09-13 14:17:46.251  2605  2815 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
,09-13 14:17:46.251  2605  2815 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 14:17:46.251  2605  2815 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-13 14:17:46.251  2605  2815 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
09-13 14:17:46.251  2605  2799 D BtGatt.AdvertiseManager: stop advertise for client =  6
09-13 14:17:46.251  2605  2799 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
09-13 14:17:46.251  2605  2799 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
09-13 14:17:46.251  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
09-13 14:17:46.261  3033  3033 I WCNSS_FILTER: do_write: IBS write: fc
09-13 14:17:46.261  1145  2316 V AlarmManager:  remove PendingIntent] PendingIntent{9878cc0: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:46.261  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-13 14:17:46.261  2605  2758 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-13 14:17:46.261  2605  2758 D BtGatt.GattService: Client app is not null!
09-13 14:17:46.261  3033  3036 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 14:17:46.261  5984  5995 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
09-13 14:17:46.261  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
09-13 14:17:46.261  2605  2624 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 14:17:46.261  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 14:17:46.261  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 14:17:46.261  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 14:17:46.261  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 14:17:46.261  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-13 14:17:46.261  1145  1318 V AlarmManager:  remove PendingIntent] PendingIntent{8199df9: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:46.261  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 14:17:46.261  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 14:17:46.261  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 14:17:46.271  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 14:17:46.271  5984  6034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2336f5e not in the list
09-13 14:17:46.271  5984  6034 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:17:46.271  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:17:46.271  5984  5984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:17:46.271  5984  5984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:17:46.271  5984  5984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 14:17:46.271  5984  6034 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-13 14:17:46.271  1145  2016 V AlarmManager:  remove PendingIntent] PendingIntent{8a0513e: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:46.271  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
09-13 14:17:46.271  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:17:46.271  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
,09-13 14:17:46.271  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-13 14:17:46.281  1145  1475 V AlarmManager:  remove PendingIntent] PendingIntent{ccc434a: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:46.281  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:46.281  5984  6034 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:17:46.281  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:17:46.281  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 14:17:46.281  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:17:46.281  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:17:46.281  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:17:46.281  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:17:46.281  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 14:17:46.281  1145  2382 V AlarmManager:  remove PendingIntent] PendingIntent{4b562bb: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:46.281  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:46.281  5984  6034 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 14:17:46.281  5984  6034 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 14:17:46.291  1145  2316 V AlarmManager:  remove PendingIntent] PendingIntent{cf233d8: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:46.281  5984  6034 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-13 14:17:46.281  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-13 14:17:46.281  5984  6034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 14:17:46.281  5984  6034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 14:17:46.281  5984  6034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 14:17:46.281  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:17:46.291  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 14:17:46.291  5984  6034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 14:17:46.291  5984  6034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 14:17:46.291  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 14:17:46.291  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 14:17:46.291  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:17:46.291  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 14:17:46.291  5984  5984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:17:46.291  5984  6051 D BluetoothSocket: bindListen(): myUserId = 0
,09-13 14:17:46.291  5984  6051 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 14:17:46.291  5984  6034 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 14:17:46.291  5984  6034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 14:17:46.291  5984  5984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:17:46.291  5984  5984 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 14:17:46.291  5984  6051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 14:17:46.301  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:46.301  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:46.301  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:46.301  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 14:17:46.301  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:46.301  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:46.301  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 14:17:46.301  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 14:17:46.301  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:46.301  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 14:17:46.301  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-13 14:17:46.301  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 44 78 3E EB 95 EE
09-13 14:17:46.301  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:17:46.301  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:17:46.301  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 14:17:46.301  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:46.311  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:46.311  5984  6034 D BluetoothLeAdvertiser: start advertising
,09-13 14:17:46.311  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:46.311  2605  3115 D BtGatt.GattService: registerClient() - UUID=3b2dbdb0-fd8f-46d9-b84e-a4447df393c5
,09-13 14:17:46.331  1145  2316 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 14:17:46.331  1145  2316 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4390, temperature: 316, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 14:17:46.331  1145  2316 D BatteryService: online:4, current avg:153, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:164
09-13 14:17:46.331  1145  1145 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 14:17:46.331  1693  1693 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 14:17:46.331  1693  1693 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 14:17:46.331  1693  1693 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-13 14:17:46.341  2605  2605 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 14:17:46.341  2605  3118 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 14:17:46.361  2605  2758 D BtGatt.GattService: onClientRegistered() - UUID=3b2dbdb0-fd8f-46d9-b84e-a4447df393c5, clientIf=6
,09-13 14:17:46.361  5984  5994 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
09-13 14:17:46.361  2605  2624 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-13 14:17:46.361  2605  2624 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:17:46.361  1693  1693 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 14:17:46.361  2605  2624 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:17:46.361  2605  2815 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-13 14:17:46.361  2605  2815 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
,09-13 14:17:46.361  2605  2799 D BtGatt.AdvertiseManager: message : 0
09-13 14:17:46.361  2605  2799 D BtGatt.AdvertiseManager: number of adv instance running = 0
09-13 14:17:46.361  2605  2799 D BtGatt.AdvertiseManager: size of list is =0
09-13 14:17:46.361  1693  1693 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 14:17:46.361  1693  1693 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 14:17:46.361  2605  2799 D BtGatt.AdvertiseManager: starting advertising
,09-13 14:17:46.361  2605  2799 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-13 14:17:46.371  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 28 : bytes_written: 28
09-13 14:17:46.371  1145  2316 V AlarmManager:  remove PendingIntent] PendingIntent{142b584: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:46.371  3033  3033 I WCNSS_FILTER: do_write: IBS write: fc
,09-13 14:17:46.371  2605  2815 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 22
09-13 14:17:46.371  2605  2815 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24562817
09-13 14:17:46.371  2605  2815 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-13 14:17:46.371  2605  2815 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 14:17:46.371  2605  2815 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-13 14:17:46.371  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 14:17:46.371  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
,09-13 14:17:46.371  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 14:17:46.371  2605  2758 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
09-13 14:17:46.371  1145  2016 V AlarmManager:  remove PendingIntent] PendingIntent{4cdb16d: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:46.371  2605  2799 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 14:17:46.371  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 38 : bytes_written: 38
,09-13 14:17:46.371  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-13 14:17:46.371  2605  2758 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
09-13 14:17:46.371  2605  2799 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-13 14:17:46.371  1145  1475 V AlarmManager:  remove PendingIntent] PendingIntent{ef1f1a2: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:46.371  2605  2799 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-13 14:17:46.371  2605  2799 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
09-13 14:17:46.371  2605  2799 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
09-13 14:17:46.371  5984  5995 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
09-13 14:17:46.371  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 14:17:46.371  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 14:17:46.381  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 14:17:46.381  1145  1317 V AlarmManager:  remove PendingIntent] PendingIntent{9ef6e33: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:46.381  5984  6034 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 14:17:46.381  5984  5984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 14:17:46.381  5984  5984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 14:17:46.381  5984  5984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 14:17:46.381  5984  5984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 14:17:46.381  5984  5984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-13 14:17:46.381  5984  5984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 14:17:46.381  1145  3550 D SSRM:s  : SIOP:: AP = 350, PST = 380 (W:10), CP = 42, LCD = 0
09-13 14:17:46.381  1145  3550 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-13 14:17:46.381  1145  1475 V AlarmManager:  remove PendingIntent] PendingIntent{cf7a5f0: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:46.381  5984  5984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 14:17:46.381  5984  5984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 14:17:46.391  1145  1910 V AlarmManager:  remove PendingIntent] PendingIntent{1a0f769: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:46.621   726   726 I MSM-irqbalance: Decided to move IRQ270 from CPU1 to CPU3
,09-13 14:17:46.881  5984  6034 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 14:17:46.881  5984  6034 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-13 14:17:46.881  5984  6034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-13 14:17:46.881  5984  6034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 14:17:46.881  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 14:17:46.881  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 14:17:46.881  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 14:17:46.881  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
09-13 14:17:46.881  5984  6034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 14:17:46.881  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 14:17:46.881  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 14:17:46.881  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 14:17:46.881  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 14:17:46.881  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 14:17:46.881  5984  6051 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 14:17:46.881  5984  6051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 14:17:46.881  5984  6051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 14:17:46.881  5984  5984 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 14:17:46.881  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:46.881  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:46.881  5984  6034 D BluetoothLeScanner: could not find callback wrapper
09-13 14:17:46.881  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 14:17:46.881  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 14:17:46.881  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:46.891  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:46.891  5984  6034 D BluetoothLeAdvertiser: stop advertising
,09-13 14:17:46.891  2605  3115 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:17:46.891  2605  3115 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:17:46.891  2605  2815 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
09-13 14:17:46.891  2605  2815 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
09-13 14:17:46.891  2605  2815 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 14:17:46.891  2605  2799 D BtGatt.AdvertiseManager: message : 1
09-13 14:17:46.891  2605  2815 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-13 14:17:46.891  2605  2815 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
09-13 14:17:46.891  2605  2799 D BtGatt.AdvertiseManager: stop advertise for client =  6
09-13 14:17:46.891  2605  2799 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
,09-13 14:17:46.891  2605  2799 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-13 14:17:46.891  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
09-13 14:17:46.901  1145  2382 V AlarmManager:  remove PendingIntent] PendingIntent{12185ee: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:46.901  3033  3033 I WCNSS_FILTER: do_write: IBS write: fc,
09-13 14:17:46.901  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 14:17:46.901  2605  2758 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-13 14:17:46.901  2605  2758 D BtGatt.GattService: Client app is not null!
09-13 14:17:46.901  3033  3036 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 14:17:46.901  5984  5994 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
09-13 14:17:46.901  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
09-13 14:17:46.901  2605  2624 D BtGatt.GattService: unregisterClient() - clientIf=6
09-13 14:17:46.901  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 14:17:46.901  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 14:17:46.901  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 14:17:46.901  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 14:17:46.901  1145  2016 V AlarmManager:  remove PendingIntent] PendingIntent{628ba8f: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:46.901  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-13 14:17:46.901  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 14:17:46.901  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 14:17:46.901  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 14:17:46.911  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 14:17:46.911  5984  5984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 14:17:46.911  5984  5984 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-13 14:17:46.911  5984  5984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 14:17:46.911  1145  2664 V AlarmManager:  remove PendingIntent] PendingIntent{1c9311c: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:46.911  5984  5984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:17:46.911  5984  5984 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 14:17:46.911  5984  5984 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-13 14:17:46.911  5984  5984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 14:17:46.911  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:17:46.911  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:46.911  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:17:46.911  5984  6034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebe099 not in the list
09-13 14:17:46.911  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:17:46.911  5984  6034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2336f5e not in the list
09-13 14:17:46.911  5984  6034 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:17:46.911  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:46.911  5984  6034 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-13 14:17:46.911  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:17:46.911  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:46.911  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:46.911  5984  6034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebe099 not in the list
09-13 14:17:46.911  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:17:46.911  5984  6034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2336f5e not in the list
09-13 14:17:46.911  1145  1953 V AlarmManager:  remove PendingIntent] PendingIntent{748a125: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:46.911  5984  6034 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:17:46.911  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:46.911  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:46.911  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-13 14:17:46.911  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 14:17:46.911  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:17:46.911  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:46.911  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:46.911  5984  6034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebe099 not in the list
,09-13 14:17:46.911  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:17:46.911  5984  6034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2336f5e not in the list
09-13 14:17:46.911  5984  6034 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:17:46.911  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:46.911  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:46.911  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
09-13 14:17:46.921  5984  6034 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-13 14:17:46.921  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:17:46.921  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:46.921  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:46.921  5984  6034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebe099 not in the list
09-13 14:17:46.921  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:17:46.921  5984  6034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2336f5e not in the list
09-13 14:17:46.921  5984  6034 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:17:46.921  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:46.921  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:46.921  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-13 14:17:46.921  5984  6034 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-13 14:17:46.921  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:17:46.921  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:46.921  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:46.921  5984  6034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebe099 not in the list
09-13 14:17:46.921  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:17:46.921  5984  6034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2336f5e not in the list
09-13 14:17:46.921  5984  6034 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:17:46.921  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:46.921  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:46.921  1145  2665 V AlarmManager:  remove PendingIntent] PendingIntent{2a412fa: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:46.921  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 14:17:46.921  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:17:46.921  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:17:46.921  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:17:46.921  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 14:17:46.921  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:17:46.921  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 14:17:46.921  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:17:46.921  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 14:17:46.921  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:17:46.921  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:17:46.921  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:17:46.921  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:17:46.921  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:46.921  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:46.921  5984  6034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebe099 not in the list
09-13 14:17:46.921  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:17:46.921  5984  6034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2336f5e not in the list
09-13 14:17:46.921  5984  6034 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:17:46.921  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:46.921  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:46.921  5984  6034 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-13 14:17:46.921  5984  6034 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 14:17:46.921  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-13 14:17:46.921  1145  2382 V AlarmManager:  remove PendingIntent] PendingIntent{50070ab: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:46.921  5984  6034 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 14:17:46.921  5984  6034 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 14:17:46.921  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 14:17:46.921  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 14:17:46.921  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 14:17:46.921  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 14:17:46.921  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 14:17:46.921  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 14:17:46.921  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 14:17:46.921  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-13 14:17:46.921  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 14:17:46.921  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 14:17:46.921  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 14:17:46.921  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 14:17:46.921  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 14:17:46.931  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 14:17:46.931  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 14:17:46.931  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 14:17:46.931  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-13 14:17:46.931  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 14:17:46.931  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 14:17:46.931  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 14:17:46.931  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 14:17:46.931  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 14:17:46.931  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 14:17:46.931  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 14:17:46.931  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 14:17:46.931  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 14:17:46.931  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 14:17:46.931  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 14:17:46.931  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 14:17:46.931  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 14:17:46.931  5984  6034 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 14:17:46.931  5984  6034 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 14:17:46.931  5984  6034 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 14:17:46.931  5984  6034 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 14:17:46.931  5984  6034 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-13 14:17:46.931  5984  6034 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 14:17:46.931  5984  6034 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 14:17:46.931  5984  6034 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 14:17:46.931  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-13 14:17:46.931  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-13 14:17:46.931  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-13 14:17:46.931  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-13 14:17:46.941  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 14:17:46.941  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 14:17:46.941  5984  6034 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 14:17:46.941  5984  6034 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 14:17:46.941  5984  6034 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-13 14:17:46.941  5984  6057 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 212)
,09-13 14:17:46.941  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:17:46.941  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:46.941  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:46.941  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-13 14:17:46.941  5984  6034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebe099 not in the list
09-13 14:17:46.941  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:17:46.941  5984  6034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2336f5e not in the list
09-13 14:17:46.941  5984  6034 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:17:46.941  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 14:17:46.941  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:46.941  5984  6058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 212
09-13 14:17:46.941  5984  6034 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-13 14:17:46.941  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:17:46.941  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:46.941  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:17:46.941  5984  6034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebe099 not in the list
09-13 14:17:46.941  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:17:46.941  5984  6034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2336f5e not in the list
09-13 14:17:46.941  5984  6034 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:17:46.941  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:46.941  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:17:46.941  5984  6034 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-13 14:17:46.941  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:17:46.941  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:46.941  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:46.941  5984  6034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebe099 not in the list
09-13 14:17:46.941  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:17:46.941  5984  6034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2336f5e not in the list,
09-13 14:17:46.941  5984  6034 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:17:46.941  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:46.941  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:46.941  5984  6034 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-13 14:17:46.941  5984  6034 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 14:17:46.941  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 14:17:46.941  5984  6034 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 14:17:46.941  5984  6034 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 14:17:46.941  5984  6034 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,09-13 14:17:46.941  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 14:17:46.941  5984  6034 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 14:17:46.941  5984  6034 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 14:17:46.941  5984  6034 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 14:17:46.941  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 14:17:46.941  5984  6034 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 14:17:46.941  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:17:46.941  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:46.941  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:17:46.941  5984  6034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebe099 not in the list
09-13 14:17:46.941  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:17:46.941  5984  6034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2336f5e not in the list
09-13 14:17:46.941  5984  6034 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:17:46.941  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:46.941  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:46.941  5984  6034 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-13 14:17:46.941  5984  6057 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-13 14:17:46.941  5984  6057 D BluetoothSocket: connect(): myUserId = 0
09-13 14:17:46.941  5984  6057 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 14:17:46.951  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:17:46.951  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:46.951  1145  2382 D SecContentProvider: insert(), uri = 2
,09-13 14:17:46.951  5984  6034 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:17:46.951  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:17:46.951  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 14:17:46.951  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:17:46.951  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:17:46.951  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:17:46.951  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:17:46.951  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 14:17:46.951  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 17 : bytes_written: 17
,09-13 14:17:46.951  2605  3072 W bt_btif : bta_dm_acl_change(), event : 2
09-13 14:17:46.961  3033  3033 I WCNSS_FILTER: do_write: IBS write: fc
09-13 14:17:46.961  1145  1720 V AlarmManager:  remove PendingIntent] PendingIntent{1536c87: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:46.961  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-13 14:17:46.961  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:46.961  5984  6034 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 14:17:46.961  5984  6034 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 14:17:46.961  1145  2382 V AlarmManager:  remove PendingIntent] PendingIntent{30087b4: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:46.961  5984  6034 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-13 14:17:46.961  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-13 14:17:46.961  5984  6034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 14:17:46.961  5984  6034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 14:17:46.961  5984  6034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 14:17:46.961  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:17:46.961  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 14:17:46.961  5984  6034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 14:17:46.961  5984  6034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 14:17:46.961  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 14:17:46.961  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 14:17:46.961  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:17:46.961  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 14:17:46.961  5984  6034 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 14:17:46.961  5984  6034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 14:17:46.961  5984  6059 D BluetoothSocket: bindListen(): myUserId = 0
09-13 14:17:46.961  5984  6059 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 14:17:46.961  5984  5984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:17:46.971  1145  1318 V AlarmManager:  remove PendingIntent] PendingIntent{2f86b20: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:46.971  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:46.971  5984  6059 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-13 14:17:46.971  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:46.971  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:46.971  5984  5984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:17:46.971  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 14:17:46.971  5984  5984 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 14:17:46.971  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:46.971  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:46.971  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 14:17:46.971  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 14:17:46.971  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:46.971  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 14:17:46.971  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-13 14:17:46.971  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 44 78 3E EB 95 EE
09-13 14:17:46.971  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:17:46.971  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:17:46.971  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 14:17:46.981  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:46.981  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:46.981  5984  6034 D BluetoothLeAdvertiser: start advertising
,09-13 14:17:46.981  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:46.981  2605  2623 D BtGatt.GattService: registerClient() - UUID=8cce677d-8c67-4411-867e-2846db4a21c4
,09-13 14:17:47.021  2605  2758 D BtGatt.GattService: onClientRegistered() - UUID=8cce677d-8c67-4411-867e-2846db4a21c4, clientIf=6
,09-13 14:17:47.021  5984  5995 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 14:17:47.031  2605  3157 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-13 14:17:47.031  2605  3157 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:17:47.031  2605  3157 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:17:47.031  2605  2799 D BtGatt.AdvertiseManager: message : 0
09-13 14:17:47.031  2605  2815 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-13 14:17:47.031  2605  2815 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
,09-13 14:17:47.031  2605  2799 D BtGatt.AdvertiseManager: number of adv instance running = 0
09-13 14:17:47.031  2605  2799 D BtGatt.AdvertiseManager: size of list is =0
,09-13 14:17:47.031  2605  2799 D BtGatt.AdvertiseManager: starting advertising
,09-13 14:17:47.031  2605  2799 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-13 14:17:47.041  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 28 : bytes_written: 28
09-13 14:17:47.041  1145  2078 V AlarmManager:  remove PendingIntent] PendingIntent{f298cd9: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:47.041  2605  2815 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 23
09-13 14:17:47.041  2605  2815 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24562817
09-13 14:17:47.041  2605  2815 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-13 14:17:47.041  2605  2815 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 14:17:47.041  2605  2815 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-13 14:17:47.041  3033  3033 I WCNSS_FILTER: do_write: IBS write: fc
,09-13 14:17:47.051  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-13 14:17:47.051  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
09-13 14:17:47.051  1145  1317 V AlarmManager:  remove PendingIntent] PendingIntent{671469e: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:47.051  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-13 14:17:47.051  2605  2758 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-13 14:17:47.051  2605  2799 D BtGatt.AdvertiseManager: starting multi advertising
09-13 14:17:47.051  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 38 : bytes_written: 38
09-13 14:17:47.051  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-13 14:17:47.051  2605  2758 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
09-13 14:17:47.051  1145  2382 V AlarmManager:  remove PendingIntent] PendingIntent{df3657f: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:47.051  2605  2799 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-13 14:17:47.051  2605  2799 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-13 14:17:47.051  2605  2799 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
09-13 14:17:47.051  2605  2799 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
09-13 14:17:47.051  5984  5994 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,09-13 14:17:47.051  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 14:17:47.051  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 14:17:47.061  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 14:17:47.061  1145  2078 V AlarmManager:  remove PendingIntent] PendingIntent{8c9194c: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:47.061  5984  6034 I io.jxcore.node.ConnectionHelper: start: OK
09-13 14:17:47.061  5984  5984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 14:17:47.061  5984  5984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 14:17:47.061  5984  5984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 14:17:47.061  5984  5984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 14:17:47.061  5984  5984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 14:17:47.061  5984  5984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 14:17:47.061  1145  1318 V AlarmManager:  remove PendingIntent] PendingIntent{1d1d95: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:47.061  5984  5984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 14:17:47.061  5984  5984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 14:17:47.071  1145  1720 V AlarmManager:  remove PendingIntent] PendingIntent{1a72eaa: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:47.571  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-13 14:17:47.571  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 14:17:47.571  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 14:17:47.571  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 14:17:47.571  5984  6059 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 14:17:47.571  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
09-13 14:17:47.571  5984  6059 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-13 14:17:47.571  5984  6034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 14:17:47.571  5984  6059 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 14:17:47.571  5984  6034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebe099 not in the list
09-13 14:17:47.571  5984  5984 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-13 14:17:47.571  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:17:47.571  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 14:17:47.571  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 14:17:47.571  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 14:17:47.571  5984  5984 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 14:17:47.571  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 14:17:47.571  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:47.571  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:47.571  5984  6034 D BluetoothLeScanner: could not find callback wrapper
09-13 14:17:47.571  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 14:17:47.571  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...,
09-13 14:17:47.571  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:47.571  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:47.571  5984  6034 D BluetoothLeAdvertiser: stop advertising
,09-13 14:17:47.571  2605  2623 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:17:47.571  2605  2623 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:17:47.571  2605  2799 D BtGatt.AdvertiseManager: message : 1
09-13 14:17:47.571  2605  2815 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
09-13 14:17:47.571  2605  2815 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
,09-13 14:17:47.571  2605  2815 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 14:17:47.571  2605  2815 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-13 14:17:47.571  2605  2815 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
09-13 14:17:47.571  2605  2799 D BtGatt.AdvertiseManager: stop advertise for client =  6
,09-13 14:17:47.571  2605  2799 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
09-13 14:17:47.571  2605  2799 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
09-13 14:17:47.581  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
,09-13 14:17:47.581  1145  2316 V AlarmManager:  remove PendingIntent] PendingIntent{5e2da9b: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:47.581  3033  3033 I WCNSS_FILTER: do_write: IBS write: fc
09-13 14:17:47.581  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 14:17:47.581  2605  2758 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-13 14:17:47.581  3033  3036 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 14:17:47.581  2605  2758 D BtGatt.GattService: Client app is not null!
09-13 14:17:47.581  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
09-13 14:17:47.581  5984  5995 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
09-13 14:17:47.581  2605  3157 D BtGatt.GattService: unregisterClient() - clientIf=6
09-13 14:17:47.581  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 14:17:47.581  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 14:17:47.581  1145  1953 V AlarmManager:  remove PendingIntent] PendingIntent{f147e38: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:47.581  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 14:17:47.581  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 14:17:47.581  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 14:17:47.581  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 14:17:47.581  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 14:17:47.581  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 14:17:47.581  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:17:47.581  1145  2004 V AlarmManager:  remove PendingIntent] PendingIntent{17efe11: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:47.591  5984  6034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2336f5e not in the list
09-13 14:17:47.591  5984  6034 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:17:47.591  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:17:47.591  5984  5984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:17:47.591  5984  5984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:17:47.591  5984  5984 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 14:17:47.591  5984  5984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 14:17:47.591  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:17:47.591  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:47.591  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:17:47.591  5984  6034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebe099 not in the list
09-13 14:17:47.591  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:17:47.591  5984  6034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2336f5e not in the list
09-13 14:17:47.591  5984  6034 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:17:47.591  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:47.591  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:17:47.591  5984  6034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 14:17:47.591  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:17:47.591  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 14:17:47.591  5984  6034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 14:17:47.591  5984  6034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 14:17:47.591  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 14:17:47.591  5984  5984 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 14:17:47.591  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 14:17:47.591  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:17:47.591  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 14:17:47.591  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 14:17:47.591  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 14:17:47.591  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:47.591  5984  6034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 14:17:47.591  5984  6034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebe099 not in the list
09-13 14:17:47.591  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 14:17:47.591  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 14:17:47.591  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 14:17:47.591  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 14:17:47.591  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:47.591  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:47.591  5984  5984 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 14:17:47.591  5984  6063 D BluetoothSocket: bindListen(): myUserId = 0
09-13 14:17:47.591  5984  6063 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 14:17:47.591  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 14:17:47.591  5984  5984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:17:47.591  5984  5984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:17:47.591  5984  5984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 14:17:47.601  5984  6034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2336f5e not in the list
09-13 14:17:47.601  5984  6034 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:17:47.601  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 14:17:47.601  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:47.601  5984  6034 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-13 14:17:47.601  5984  6034 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 14:17:47.601  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 14:17:47.601  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
09-13 14:17:47.601  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-13 14:17:47.601  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:17:47.601  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:17:47.601  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:17:47.601  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:17:47.601  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:47.601  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:17:47.601  5984  6034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebe099 not in the list
09-13 14:17:47.601  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:17:47.601  5984  6034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2336f5e not in the list
09-13 14:17:47.601  5984  6034 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:17:47.601  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:47.601  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:47.601  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 14:17:47.601  1145  2078 V AlarmManager:  remove PendingIntent] PendingIntent{6a18b76: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:47.601  5984  6063 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 14:17:47.601  5984  6063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 14:17:47.601  5984  6063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 14:17:47.601  5984  5984 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 14:17:47.601  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:17:47.601  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:47.601  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:47.601  5984  6034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebe099 not in the list
09-13 14:17:47.601  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:17:47.601  5984  6034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2336f5e not in the list
09-13 14:17:47.601  5984  6034 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:17:47.601  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:47.601  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:47.601  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:17:47.601  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:47.601  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:47.601  5984  6034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebe099 not in the list
09-13 14:17:47.601  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:17:47.601  5984  6034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2336f5e not in the list
09-13 14:17:47.601  5984  6034 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:17:47.601  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:47.601  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:17:47.611  5984  6034 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-13 14:17:47.611  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 14:17:47.611  1145  1910 V AlarmManager:  remove PendingIntent] PendingIntent{e8a8577: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:47.611  5984  6034 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-13 14:17:47.611  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 14:17:47.611  5984  6034 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 14:17:47.611  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 14:17:47.611  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 14:17:47.611  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-13 14:17:47.611  5984  6034 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-13 14:17:47.611  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 14:17:47.611  5984  6034 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-13 14:17:47.611  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 14:17:47.611  5984  6034 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-13 14:17:47.611  5984  6034 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-13 14:17:47.611  1145  1317 V AlarmManager:  remove PendingIntent] PendingIntent{6af45e4: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:47.611  5984  6034 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-13 14:17:47.611  5984  6034 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-13 14:17:47.611  5984  6034 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-13 14:17:47.611  5984  6034 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 14:17:47.611  5984  6034 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,09-13 14:17:47.611  5984  6034 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-13 14:17:47.621  5984  6064 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-13 14:17:47.621  5984  6064 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 14:17:48.101  5984  5984 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 14:17:48.121   553  1407 D EnterpriseController: netId is 0
09-13 14:17:48.121   553  1407 D Netd    : getNetworkForDns: using netid 502 for uid 10136
,09-13 14:17:48.131  5984  6064 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-13 14:17:48.131  5984  6066 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-13 14:17:48.131  5984  6066 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 14:17:48.131  5984  6064 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-13 14:17:48.131  5984  6064 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:17:48.131  5984  6066 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 14:17:48.131  5984  6066 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:17:48.131  5984  6064 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 14:17:48.131  5984  6064 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-13 14:17:48.131  5984  6066 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 14:17:48.131  5984  6069 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 266, name: IncomingSocketThread/Sender)
,09-13 14:17:48.141  5984  6070 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 265, name: OutgoingSocketThread/Sender)
,09-13 14:17:48.141  5984  6071 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 267, name: IncomingSocketThread/Receiver)
,09-13 14:17:48.141  5984  6071 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 267, thread name: IncomingSocketThread/Receiver)
09-13 14:17:48.141  5984  6071 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 14:17:48.141  5984  6071 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 267, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-13 14:17:48.141  5984  6072 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 268, name: OutgoingSocketThread/Receiver)
,09-13 14:17:48.141  5984  6072 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 268, thread name: OutgoingSocketThread/Receiver)
,09-13 14:17:48.141  5984  6072 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 14:17:48.141  5984  6072 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 268, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-13 14:17:48.601  3033  3083 I WCNSS_FILTER: do_write: IBS write: fe
09-13 14:17:48.601  3033  3083 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-13 14:17:48.621  5984  6034 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-13 14:17:48.621  5984  6034 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-13 14:17:48.631  5984  6034 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@21463dc Bundle[{}],
09-13 14:17:48.631  5984  6034 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 14:17:48.631  5984  6034 I io.jxcore.node.LifeCycleMonitor: stop: OK,
,09-13 14:17:48.631  5984  6034 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-13 14:17:48.631  5984  6034 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-13 14:17:48.631  5984  6034 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-13 14:17:48.631  5984  6034 D io.jxcore.node.LifeCycleMonitor: onActivityPaused,
,09-13 14:17:48.641  5984  6073 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775,
09-13 14:17:48.641  5984  6073 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 14:17:49.151  5984  6075 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-13 14:17:49.151  5984  6075 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 14:17:49.151  5984  6073 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-13 14:17:49.151  5984  6073 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 14:17:49.151  5984  6075 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:17:49.151  5984  6073 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 14:17:49.151  5984  6073 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:17:49.151  5984  6075 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes,
09-13 14:17:49.151  5984  6073 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-13 14:17:49.151  5984  6075 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-13 14:17:49.151  5984  6078 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 279, name: IncomingSocketThread/Sender)
,09-13 14:17:49.151  5984  6077 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 280, name: OutgoingSocketThread/Sender)
,09-13 14:17:49.151  5984  6079 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 281, name: OutgoingSocketThread/Receiver),
09-13 14:17:49.151  5984  6080 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 282, name: IncomingSocketThread/Receiver)
,09-13 14:17:49.151  5984  6079 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 281, thread name: OutgoingSocketThread/Receiver)
09-13 14:17:49.151  5984  6079 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 14:17:49.151  5984  6079 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 281, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-13 14:17:49.151  5984  6080 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 282, thread name: IncomingSocketThread/Receiver)
09-13 14:17:49.151  5984  6080 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 14:17:49.151  5984  6080 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 282, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-13 14:17:49.651  5984  6034 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 291),
09-13 14:17:49.651  5984  6034 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-13 14:17:49.651  5984  6034 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 292)
,09-13 14:17:49.651  5984  6034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
09-13 14:17:49.651  5984  6034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f96762f added. We now have 4 listener(s)
,09-13 14:17:49.661  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:EB:95:EE",
09-13 14:17:49.661  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 14:17:49.661  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 14:17:49.661  5984  6034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 14:17:49.661  5984  6034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cd43c added. We now have 4 listener(s)
09-13 14:17:49.661  5984  6034 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 14:17:49.661  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 14:17:49.661  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-13 14:17:49.671  5984  6034 D BluetoothAdapter: STATE_ON,
,09-13 14:17:49.671  5984  6034 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-13 14:17:49.671  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:17:49.671  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 14:17:49.671  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,09-13 14:17:49.671  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:17:49.671  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:17:49.671  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:17:49.671  5984  6034 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 14:17:49.671  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:49.681  5984  6034 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 14:17:49.681  5984  6034 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 14:17:49.681  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:49.681  5984  5984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:17:49.681  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:17:49.681  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:49.681  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:17:49.681  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 14:17:49.681  5984  6034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f96762f removed from the list
09-13 14:17:49.681  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:17:49.681  5984  6034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cd43c removed from the list
,09-13 14:17:49.691  5984  5984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:17:49.691  5984  6034 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:17:49.691  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:17:49.691  5984  6034 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-13 14:17:49.691  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
09-13 14:17:49.691  5984  6034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 14:17:49.691  5984  6034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 14:17:49.691  5984  6034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 14:17:49.691  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:17:49.691  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 14:17:49.691  5984  6034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 14:17:49.691  5984  6034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 14:17:49.691  5984  5984 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 14:17:49.691  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 14:17:49.691  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 14:17:49.691  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:17:49.691  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 14:17:49.691  5984  6081 D BluetoothSocket: bindListen(): myUserId = 0
09-13 14:17:49.691  5984  6081 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 14:17:49.701  5984  6034 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 14:17:49.701  5984  6034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 14:17:49.701  5984  6081 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 14:17:49.701  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:49.701  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:49.701  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:49.701  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 14:17:49.701  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:49.701  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:49.701  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 14:17:49.701  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 14:17:49.711  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:49.711  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 14:17:49.711  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-13 14:17:49.711  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 44 78 3E EB 95 EE
09-13 14:17:49.711  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:17:49.711  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:17:49.711  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 14:17:49.711  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:49.711  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:49.711  5984  6034 D BluetoothLeAdvertiser: start advertising
,09-13 14:17:49.711  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:49.711  2605  2624 D BtGatt.GattService: registerClient() - UUID=954511c1-1221-46dd-bc30-ada281185f73
,09-13 14:17:49.761  2605  2758 D BtGatt.GattService: onClientRegistered() - UUID=954511c1-1221-46dd-bc30-ada281185f73, clientIf=6
09-13 14:17:49.761  5984  5995 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 14:17:49.761  2605  2623 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2,
,09-13 14:17:49.761  2605  2623 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:17:49.761  2605  2623 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:17:49.761  2605  2799 D BtGatt.AdvertiseManager: message : 0
09-13 14:17:49.761  2605  2815 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-13 14:17:49.761  2605  2815 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
09-13 14:17:49.761  2605  2799 D BtGatt.AdvertiseManager: number of adv instance running = 0
09-13 14:17:49.761  2605  2799 D BtGatt.AdvertiseManager: size of list is =0
09-13 14:17:49.761  2605  2799 D BtGatt.AdvertiseManager: starting advertising
,09-13 14:17:49.761  2605  2799 D BtGatt.AdvertiseManager: isStandardAdv = false,
09-13 14:17:49.761  3033  3036 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
09-13 14:17:49.761  1145  1475 V AlarmManager:  remove PendingIntent] PendingIntent{7f6ac6f: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:49.771  2605  2815 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 24,
09-13 14:17:49.771  3033  3036 I WCNSS_FILTER: do_write: IBS write: fd
09-13 14:17:49.771  2605  2815 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24562817
09-13 14:17:49.771  2605  2815 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-13 14:17:49.771  2605  2815 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 14:17:49.771  2605  2815 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-13 14:17:49.771  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 28 : bytes_written: 28
09-13 14:17:49.771  3033  3033 I WCNSS_FILTER: do_write: IBS write: fc
09-13 14:17:49.771  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-13 14:17:49.771  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
09-13 14:17:49.771  1145  1910 V AlarmManager:  remove PendingIntent] PendingIntent{96b6d7c: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:49.771  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 14:17:49.771  2605  2758 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-13 14:17:49.771  2605  2799 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 14:17:49.771  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 38 : bytes_written: 38
09-13 14:17:49.771  1145  2004 V AlarmManager:  remove PendingIntent] PendingIntent{8019605: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:49.771  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 14:17:49.771  2605  2758 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
09-13 14:17:49.771  2605  2799 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-13 14:17:49.771  2605  2799 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-13 14:17:49.771  2605  2799 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
09-13 14:17:49.771  2605  2799 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
09-13 14:17:49.781  5984  5994 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
09-13 14:17:49.781  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 14:17:49.781  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 14:17:49.781  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-13 14:17:49.781  1145  1318 V AlarmManager:  remove PendingIntent] PendingIntent{140965a: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:49.781  5984  5984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 14:17:49.781  5984  5984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 14:17:49.781  5984  5984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 14:17:49.781  1145  2078 V AlarmManager:  remove PendingIntent] PendingIntent{9eba08b: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:49.781  5984  5984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 14:17:49.781  5984  5984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 14:17:49.781  5984  5984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 14:17:49.781  5984  5984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 14:17:49.781  5984  5984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 14:17:49.781  1145  1953 V AlarmManager:  remove PendingIntent] PendingIntent{abfe568: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:50.291  5984  5984 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 14:17:50.291  5984  5984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 14:17:50.291  5984  5984 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 14:17:50.771  3033  3083 I WCNSS_FILTER: do_write: IBS write: fe,
09-13 14:17:50.771  3033  3083 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-13 14:17:53.291  5984  6034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-13 14:17:53.291  5984  6034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 14:17:53.291  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 14:17:53.291  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 14:17:53.291  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 14:17:53.291  5984  6081 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 14:17:53.291  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:17:53.291  5984  6081 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-13 14:17:53.291  5984  6034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 14:17:53.291  5984  6081 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 14:17:53.291  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 14:17:53.291  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 14:17:53.291  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 14:17:53.291  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 14:17:53.291  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 14:17:53.291  5984  5984 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 14:17:53.291  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:53.291  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:53.291  5984  6034 D BluetoothLeScanner: could not find callback wrapper
09-13 14:17:53.291  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 14:17:53.291  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 14:17:53.291  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:53.291  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:53.291  5984  6034 D BluetoothLeAdvertiser: stop advertising
,09-13 14:17:53.291  2605  2624 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:17:53.291  2605  2624 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:17:53.291  2605  2815 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
09-13 14:17:53.291  2605  2815 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
09-13 14:17:53.291  2605  2815 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 14:17:53.291  2605  2815 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-13 14:17:53.291  2605  2815 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
09-13 14:17:53.291  2605  2799 D BtGatt.AdvertiseManager: message : 1
09-13 14:17:53.291  2605  2799 D BtGatt.AdvertiseManager: stop advertise for client =  6
09-13 14:17:53.301  1145  1318 V AlarmManager:  remove PendingIntent] PendingIntent{20a8d81: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:53.291  2605  2799 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
09-13 14:17:53.291  2605  2799 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
09-13 14:17:53.301  3033  3036 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
,09-13 14:17:53.301  3033  3036 I WCNSS_FILTER: do_write: IBS write: fd,
09-13 14:17:53.301  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
,09-13 14:17:53.301  3033  3033 I WCNSS_FILTER: do_write: IBS write: fc
,09-13 14:17:53.301  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 14:17:53.301  2605  2758 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-13 14:17:53.301  2605  2758 D BtGatt.GattService: Client app is not null!
09-13 14:17:53.301  1145  2382 V AlarmManager:  remove PendingIntent] PendingIntent{861be26: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:53.301  5984  5995 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,09-13 14:17:53.301  3033  3036 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 14:17:53.301  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
09-13 14:17:53.311  2605  2623 D BtGatt.GattService: unregisterClient() - clientIf=6
09-13 14:17:53.311  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 14:17:53.311  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 14:17:53.311  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 14:17:53.311  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 14:17:53.311  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 14:17:53.311  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 14:17:53.311  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 14:17:53.311  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 14:17:53.311  1145  1318 V AlarmManager:  remove PendingIntent] PendingIntent{f1ba67: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:53.311  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:17:53.311  5984  5984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 14:17:53.311  5984  5984 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 14:17:53.311  5984  5984 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 14:17:53.311  5984  5984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:17:53.311  5984  5984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:17:53.311  5984  5984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 14:17:53.311  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:17:53.311  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:53.311  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:53.311  5984  6034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f96762f not in the list
09-13 14:17:53.311  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:17:53.311  5984  6034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cd43c not in the list
09-13 14:17:53.311  5984  6034 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:17:53.311  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:53.311  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:53.311  5984  6034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 14:17:53.311  5984  6034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 14:17:53.311  5984  6034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 14:17:53.311  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 14:17:53.311  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:17:53.311  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 14:17:53.321  5984  6034 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 14:17:53.321  5984  6034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 14:17:53.321  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
09-13 14:17:53.321  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-13 14:17:53.321  1145  2664 V AlarmManager:  remove PendingIntent] PendingIntent{2559603: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:53.321  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-13 14:17:53.321  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:53.321  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:53.331  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:53.331  1145  2382 V AlarmManager:  remove PendingIntent] PendingIntent{b77f980: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:53.331  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 14:17:53.331  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:53.331  1145  1953 V AlarmManager:  remove PendingIntent] PendingIntent{91a6bb9: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:53.331  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:53.331  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 14:17:53.331  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 14:17:53.331  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:53.331  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:53.331  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-13 14:17:53.341  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:53.341  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:53.341  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-13 14:17:53.341  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 14:17:53.341  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-13 14:17:53.341  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 14:17:53.341  5984  6034 D BluetoothLeScanner: Start Scan
,09-13 14:17:53.341  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:53.341  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:53.341  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:53.351  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:53.351  2605  2624 D BtGatt.GattService: registerClient() - UUID=681f55f3-e527-4cc8-b72b-21f13cf2b1ef
,09-13 14:17:53.361  2605  3072 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40,
,09-13 14:17:53.361  2605  3072 E bt_btif_sock_rfcomm: SDP - Failed to look up a channel number to connect to
09-13 14:17:53.361  1145  2382 V AlarmManager:  remove PendingIntent] PendingIntent{7286bfe: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:53.361  2605  3072 W bt_btif : bta_dm_acl_change(), event : 2
09-13 14:17:53.361  2605  3072 W bt_btif : bta_dm_acl_change(), event : 5
09-13 14:17:53.361  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 14 : bytes_written: 14
09-13 14:17:53.361  2605  3154 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 7
09-13 14:17:53.361  5984  6057 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 212)
,09-13 14:17:53.361  1145  1953 V AlarmManager:  remove PendingIntent] PendingIntent{1918f5f: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:53.371  1145  2016 V AlarmManager:  remove PendingIntent] PendingIntent{7232dac: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:53.371  2605  2752 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@670ef81
09-13 14:17:53.371  2605  2758 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 1
,09-13 14:17:53.371  2605  2758 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-13 14:17:53.371  2605  2758 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 241
,09-13 14:17:53.371  1693  2103 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
,09-13 14:17:53.401  2605  2758 D BtGatt.GattService: onClientRegistered() - UUID=681f55f3-e527-4cc8-b72b-21f13cf2b1ef, clientIf=6
,09-13 14:17:53.401  5984  5994 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-13 14:17:53.401  2605  2623 D BtGatt.GattService: start scan with filters
,09-13 14:17:53.401  2605  2623 D BtGatt.GattService: getScanSettings
,09-13 14:17:53.401  2605  2623 D BtGatt.GattService: Is it foreground application = false
09-13 14:17:53.401  2605  2623 D BtGatt.GattService: not a background application
,09-13 14:17:53.401  2605  2623 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-13 14:17:53.401  2605  2623 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:17:53.401  2605  2623 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:17:53.401  2605  2815 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
09-13 14:17:53.401  2605  2815 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
,09-13 14:17:53.401  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-13 14:17:53.401  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 14:17:53.401  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 14:17:53.401  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-13 14:17:53.401  2605  2802 D BtGatt.ScanManager: handling starting scan
09-13 14:17:53.401  2605  2802 D BtGatt.ScanManager: isFilteringSupported
09-13 14:17:53.401  2605  2802 D BluetoothAdapter: enableStandAloneBleMode=
09-13 14:17:53.411  2605  2802 D BluetoothAdapter: STATE_ON
,09-13 14:17:53.411  2605  2802 D BluetoothAdapter: STATE_ON
,09-13 14:17:53.411  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 14:17:53.411  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 14:17:53.411  5984  5984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 14:17:53.411  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 14:17:53.411  2605  2802 D BluetoothAdapter: STATE_ON
,09-13 14:17:53.411  2605  2802 D BluetoothAdapter: STATE_ON
,09-13 14:17:53.411  2605  2802 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@670ef81
,09-13 14:17:53.411  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
09-13 14:17:53.411  1145  1318 V AlarmManager:  remove PendingIntent] PendingIntent{ed0a75: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:53.411  3033  3033 I WCNSS_FILTER: do_write: IBS write: fc
09-13 14:17:53.411  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 9 : bytes_written: 9
,09-13 14:17:53.411  2605  2758 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-13 14:17:53.411  2605  2758 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 14:17:53.411  2605  2802 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
09-13 14:17:53.411  2605  2802 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-13 14:17:53.411  2605  2815 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 46
09-13 14:17:53.411  2605  2815 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
09-13 14:17:53.411  2605  2802 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-13 14:17:53.411  2605  2802 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
,09-13 14:17:53.421  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 22 : bytes_written: 22
,09-13 14:17:53.421  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 10 : bytes_written: 10
09-13 14:17:53.421  1145  2004 V AlarmManager:  remove PendingIntent] PendingIntent{99b4a0a: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:53.421  2605  2758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-13 14:17:53.421  2605  2758 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 14:17:53.421  2605  2802 D BtGatt.ScanManager: Starting BLE batch scan
09-13 14:17:53.421  2605  2802 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-13 14:17:53.421  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-13 14:17:53.421  1145  1910 V AlarmManager:  remove PendingIntent] PendingIntent{569c27b: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:53.421  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 14:17:53.421  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 8 : bytes_written: 8
,09-13 14:17:53.421  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 14:17:53.421  2605  2758 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-13 14:17:53.421  2605  2758 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 14:17:53.421  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 16 : bytes_written: 16
09-13 14:17:53.421  2605  2815 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 618
,09-13 14:17:53.421  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 14:17:53.421  2605  2758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-13 14:17:53.421  2605  2758 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 14:17:53.431  1145  1953 V AlarmManager:  remove PendingIntent] PendingIntent{d6b7898: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:53.431  1145  1720 V AlarmManager:  remove PendingIntent] PendingIntent{310d8f1: PendingIntentRecord{2c80b57 com.android.bluetooth broadcastIntent}}
,09-13 14:17:53.431  1145  2078 V AlarmManager:  remove PendingIntent] PendingIntent{eeb8644: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:53.431  1145  1475 V AlarmManager:  remove PendingIntent] PendingIntent{9c9132d: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:53.431  2605  2815 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24562817
,09-13 14:17:53.431  2605  2815 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
09-13 14:17:53.431  2605  2815 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-13 14:17:53.431  2605  2815 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,09-13 14:17:53.431  2605  2815 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 2 => 2
09-13 14:17:53.431  2605  2815 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 2 => 2
,09-13 14:17:53.431  2605  2815 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-13 14:17:53.431  2605  2815 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 2 => 2
09-13 14:17:53.431  2605  2815 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 2 => 2
09-13 14:17:53.431  2605  2815 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-13 14:17:53.431  2605  2815 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-13 14:17:53.431  2605  2815 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 2 => 2
09-13 14:17:53.431  2605  2815 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 2 => 2
09-13 14:17:53.431  2605  2815 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24562817
,09-13 14:17:53.431  1145  2664 V AlarmManager:  remove PendingIntent] PendingIntent{431062: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:53.441  1145  1318 V AlarmManager:  remove PendingIntent] PendingIntent{95805f3: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:53.441  1145  2382 V AlarmManager:  remove PendingIntent] PendingIntent{93cc2b0: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:53.441  1145  2316 V AlarmManager:  remove PendingIntent] PendingIntent{650b529: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:53.871  2605  2752 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@670ef81
,09-13 14:17:53.881  1145  1380 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e45d0ae u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{79fdffa 2630:com.samsung.android.providers.context/u0a5}
,09-13 14:17:53.911  5984  5984 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-13 14:17:53.911  5984  5984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 14:17:53.911  5984  5984 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 14:17:54.431  3033  3083 I WCNSS_FILTER: do_write: IBS write: fe
09-13 14:17:54.431  3033  3083 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-13 14:17:54.431  1145  1589 V AlarmManager: Expired Alarm result :4
,09-13 14:17:54.431  2605  2605 D BtGatt.ScanManager: awakened up at time 116563
09-13 14:17:54.431  2605  2802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-13 14:17:54.431  3033  3036 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
09-13 14:17:54.431  3033  3036 I WCNSS_FILTER: do_write: IBS write: fd
09-13 14:17:54.431  1145  2665 V AlarmManager:  remove PendingIntent] PendingIntent{82359dc: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:54.431  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-13 14:17:54.431  3033  3033 I WCNSS_FILTER: do_write: IBS write: fc
,09-13 14:17:54.441  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 53 : bytes_written: 53
09-13 14:17:54.441  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-13 14:17:54.441  1145  2004 V AlarmManager:  remove PendingIntent] PendingIntent{8967ae5: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:54.441  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 52 : bytes_written: 52
09-13 14:17:54.441  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-13 14:17:54.441  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 50 : bytes_written: 50
09-13 14:17:54.441  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-13 14:17:54.441  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 78 : bytes_written: 78
09-13 14:17:54.441  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-13 14:17:54.441  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 53 : bytes_written: 53
09-13 14:17:54.441  1145  1910 V AlarmManager:  remove PendingIntent] PendingIntent{3a249ba: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:54.441  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-13 14:17:54.451  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 53 : bytes_written: 53
09-13 14:17:54.451  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-13 14:17:54.451  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 52 : bytes_written: 52
09-13 14:17:54.451  1145  1953 V AlarmManager:  remove PendingIntent] PendingIntent{e6c406b: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:54.451  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
09-13 14:17:54.451  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 10 : bytes_written: 10
09-13 14:17:54.451  1145  2016 V AlarmManager:  remove PendingIntent] PendingIntent{d7a37c8: PendingIntentRecord{2c80b57 com.android.bluetooth broadcastIntent}}
09-13 14:17:54.451  2605  2758 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=7
09-13 14:17:54.451  2605  2758 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 14:17:54.451  2605  2758 D BtGatt.GattService: current time is 116587604224
09-13 14:17:54.451  2605  2758 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -68, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 78, -20, -96, 83, -39, -56, 1, -128, -51, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 8, -20, -87, 80, 118, 39, 0, 85, -113, -37, 31, -33, 8, 0, -128, -83, 7, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 35, 97, 126, -92, 22, -56, 1, -128, -70, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -68, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -68, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 78, -20, -96, 83, -39, -56, 1, -128, -51, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 8, -20, -87, 80, 118, 39, 0]
09-13 14:17:54.451  2605  2758 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
09-13 14:17:54.451  2605  2758 D ScanRecord: parseFromBytes
09-13 14:17:54.451  2605  2758 D ScanRecord: first manudata for manu ID
09-13 14:17:54.461  2605  2758 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 8, -20, -87, 80, 118, 39]
09-13 14:17:54.461  2605  2758 D ScanRecord: parseFromBytes
09-13 14:17:54.461  2605  2758 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
09-13 14:17:54.461  2605  2758 D ScanRecord: parseFromBytes
09-13 14:17:54.461  2605  2758 D ScanRecord: first manudata for manu ID
09-13 14:17:54.461  2605  2758 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-13 14:17:54.461  2605  2758 D ScanRecord: parseFromBytes
09-13 14:17:54.461  2605  2758 D ScanRecord: first manudata for manu ID
09-13 14:17:54.461  2605  2758 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
09-13 14:17:54.461  2605  2758 D ScanRecord: parseFromBytes
09-13 14:17:54.461  2605  2758 D ScanRecord: first manudata for manu ID
09-13 14:17:54.461  2605  2758 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76,, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-13 14:17:54.461  2605  2758 D ScanRecord: parseFromBytes
09-13 14:17:54.461  2605  2758 D ScanRecord: first manudata for manu ID
09-13 14:17:54.461  2605  2758 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 8, -20, -87, 80, 118, 39]
09-13 14:17:54.461  2605  2758 D ScanRecord: parseFromBytes
09-13 14:17:54.461  5984  5995 D ScanRecord: parseFromBytes
09-13 14:17:54.461  5984  5995 D ScanRecord: first manudata for manu ID
09-13 14:17:54.461  5984  5995 D ScanRecord: parseFromBytes
09-13 14:17:54.461  5984  5995 D ScanRecord: first manudata for manu ID
09-13 14:17:54.461  1145  2382 V AlarmManager:  remove PendingIntent] PendingIntent{6b8e061: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:54.461  5984  5995 D ScanRecord: parseFromBytes
09-13 14:17:54.461  5984  5995 D ScanRecord: first manudata for manu ID
09-13 14:17:54.461  5984  5995 D ScanRecord: parseFromBytes
09-13 14:17:54.461  5984  5995 D ScanRecord: parseFromBytes
09-13 14:17:54.461  5984  5995 D ScanRecord: first manudata for manu ID
09-13 14:17:54.461  5984  5995 D ScanRecord: parseFromBytes
09-13 14:17:54.461  5984  5995 D ScanRecord: first manudata for manu ID
,09-13 14:17:54.461  5984  5995 D ScanRecord: parseFromBytes
,09-13 14:17:54.461  1145  2316 V AlarmManager:  remove PendingIntent] PendingIntent{d1b4786: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:54.471  1145  1317 V AlarmManager:  remove PendingIntent] PendingIntent{c0c7847: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:54.471  1145  2016 V AlarmManager:  remove PendingIntent] PendingIntent{bdf0874: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:54.471  5984  5984 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 08:EC:A9:50:76:27 5], added - the peer count is 1
,09-13 14:17:54.471  5984  5984 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 08:EC:A9:50:76:27 5] updated - the peer count is 1
09-13 14:17:54.471  5984  5984 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 08:EC:A9:50:76:27 5], Bluetooth address: 08:EC:A9:50:76:27, device name: '', device address: ''
,09-13 14:17:54.481  1145  1318 V AlarmManager:  remove PendingIntent] PendingIntent{42219d: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:54.481  1145  2004 V AlarmManager:  remove PendingIntent] PendingIntent{ed45612: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:54.491  1145  1910 V AlarmManager:  remove PendingIntent] PendingIntent{68e51e3: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:54.491  1145  1953 V AlarmManager:  remove PendingIntent] PendingIntent{1e37e0: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:54.491  1145  2665 V AlarmManager:  remove PendingIntent] PendingIntent{9243a99: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:54.501  1145  2078 V AlarmManager:  remove PendingIntent] PendingIntent{99dc15e: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:54.501  1145  1475 V AlarmManager:  remove PendingIntent] PendingIntent{5ca293f: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:54.501  1145  2664 V AlarmManager:  remove PendingIntent] PendingIntent{55ef20c: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:55.461  3033  3083 I WCNSS_FILTER: do_write: IBS write: fe
09-13 14:17:55.461  3033  3083 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-13 14:17:55.461  1145  1589 V AlarmManager: Expired Alarm result :4
,09-13 14:17:55.461  2605  2605 D BtGatt.ScanManager: awakened up at time 117590
09-13 14:17:55.461  2605  2802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-13 14:17:55.461  3033  3036 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
09-13 14:17:55.461  3033  3036 I WCNSS_FILTER: do_write: IBS write: fd
09-13 14:17:55.461  1145  2078 V AlarmManager:  remove PendingIntent] PendingIntent{900956a: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:55.461  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-13 14:17:55.461  3033  3033 I WCNSS_FILTER: do_write: IBS write: fc
,09-13 14:17:55.461  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 52 : bytes_written: 52
09-13 14:17:55.471  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-13 14:17:55.471  1145  1475 V AlarmManager:  remove PendingIntent] PendingIntent{cc21a5b: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:55.471  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 78 : bytes_written: 78
,09-13 14:17:55.471  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
09-13 14:17:55.471  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 69 : bytes_written: 69
09-13 14:17:55.471  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-13 14:17:55.471  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 10 : bytes_written: 10
,09-13 14:17:55.471  1145  2664 V AlarmManager:  remove PendingIntent] PendingIntent{f22f8: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:55.471  2605  2758 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=3
09-13 14:17:55.471  2605  2758 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 14:17:55.471  2605  2758 D BtGatt.GattService: current time is 117606975578
09-13 14:17:55.471  2605  2758 D BtGatt.GattService: Batch record : [78, -20, -96, 83, -39, -56, 1, -128, -51, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 8, -20, -87, 80, 118, 39, 0, -46, -4, -117, 6, 105, -37, 1, -128, -68, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 85, -113, -37, 31, -33, 8, 0, 4, -80, 17, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
09-13 14:17:55.471  2605  2758 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 8, -20, -87, 80, 118, 39]
09-13 14:17:55.471  2605  2758 D ScanRecord: parseFromBytes
09-13 14:17:55.471  2605  2758 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-13 14:17:55.471  2605  2758 D ScanRecord: parseFromBytes
09-13 14:17:55.471  2605  2758 D ScanRecord: first manudata for manu ID
09-13 14:17:55.471  2605  2758 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
09-13 14:17:55.471  1145  1953 V AlarmManager:  remove PendingIntent] PendingIntent{6e9a3d1: PendingIntentRecord{2c80b57 com.android.bluetooth broadcastIntent}}
09-13 14:17:55.471  2605  2758 D ScanRecord: parseFromBytes
09-13 14:17:55.471  2605  2758 D ScanRecord: first manudata for manu ID
09-13 14:17:55.471  5984  5994 D ScanRecord: parseFromBytes
09-13 14:17:55.471  5984  5994 D ScanRecord: parseFromBytes
09-13 14:17:55.471  5984  5994 D ScanRecord: first manudata for manu ID
,09-13 14:17:55.471  5984  5994 D ScanRecord: parseFromBytes
09-13 14:17:55.471  5984  5994 D ScanRecord: first manudata for manu ID
09-13 14:17:55.481  5984  5984 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 08:EC:A9:50:76:27 5] updated - the peer count is 1
,09-13 14:17:55.481  1145  2382 V AlarmManager:  remove PendingIntent] PendingIntent{60a9e36: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:55.481  1145  2004 V AlarmManager:  remove PendingIntent] PendingIntent{27e0137: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:55.491  1145  1910 V AlarmManager:  remove PendingIntent] PendingIntent{b8f76a4: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:55.491  1145  1953 V AlarmManager:  remove PendingIntent] PendingIntent{913ac0d: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:55.501  1145  2665 V AlarmManager:  remove PendingIntent] PendingIntent{ada67c2: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:56.381  1145  2078 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 14:17:56.381  1145  2078 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4390, temperature: 319, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-13 14:17:56.381  1145  2078 D BatteryService: online:4, current avg:159, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:160
09-13 14:17:56.381  1145  1145 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-13 14:17:56.391  1693  1693 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 14:17:56.391  1693  1693 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 14:17:56.391  1693  1693 D PowerUI : priorPlugType = 2 mPlugType =  2
09-13 14:17:56.391  1693  1693 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-13 14:17:56.391  2605  2605 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 14:17:56.391  2605  3118 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 14:17:56.411  1693  1693 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-13 14:17:56.411  1693  1693 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 14:17:56.411  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:17:56.411  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:56.411  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:17:56.411  5984  6034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f96762f not in the list
09-13 14:17:56.411  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:17:56.411  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 14:17:56.411  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 14:17:56.411  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 14:17:56.411  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 14:17:56.411  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 14:17:56.411  1145  3550 D SSRM:s  : SIOP:: AP = 340, PST = 376 (W:11), CP = 40, LCD = 0
09-13 14:17:56.411  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:56.411  1145  3550 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 14:17:56.411  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:56.411  5984  6034 D BluetoothLeScanner: Stop Scan
,09-13 14:17:56.421  2605  3115 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:17:56.421  2605  3115 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:17:56.421  2605  3115 D BtGatt.GattService: stopScan() - queue size =1
09-13 14:17:56.421  2605  2815 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
09-13 14:17:56.421  2605  2815 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
09-13 14:17:56.421  2605  2815 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-13 14:17:56.421  2605  2815 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 2 => 2
09-13 14:17:56.421  2605  2815 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 2 => 2
09-13 14:17:56.421  2605  2802 D BtGatt.ScanManager: filter size is 1
,09-13 14:17:56.421  2605  2815 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
09-13 14:17:56.421  2605  3157 D BtGatt.GattService: unregisterClient() - clientIf=6
09-13 14:17:56.421  2605  2815 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
09-13 14:17:56.421  2605  2802 D BtGatt.ScanManager: delete FilterIndex - 3
09-13 14:17:56.421  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 14:17:56.421  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 14:17:56.421  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 14:17:56.421  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
09-13 14:17:56.421  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 14:17:56.421  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 14:17:56.421  1145  2016 V AlarmManager:  remove PendingIntent] PendingIntent{ca779d3: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:56.421  3033  3033 I WCNSS_FILTER: do_write: IBS write: fc
,09-13 14:17:56.421  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 10 : bytes_written: 10
09-13 14:17:56.421  2605  2758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-13 14:17:56.421  2605  2758 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 14:17:56.421  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 14:17:56.421  2605  2802 D BtGatt.ScanManager: stopping BLe Batch
,09-13 14:17:56.421  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 16 : bytes_written: 16
09-13 14:17:56.421  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:56.431  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 14:17:56.431  1145  1317 V AlarmManager:  remove PendingIntent] PendingIntent{69f5910: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:56.431  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:56.431  5984  6034 D BluetoothLeAdvertiser: stop advertising
09-13 14:17:56.431  2605  2758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-13 14:17:56.431  5984  6034 D BluetoothLeAdvertiser: wrapper is null
09-13 14:17:56.431  2605  2758 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 14:17:56.431  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 14:17:56.431  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 14:17:56.431  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 14:17:56.431  2605  2802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-13 14:17:56.431  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
09-13 14:17:56.431  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:56.431  5984  6034 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,09-13 14:17:56.431  5984  6034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cd43c not in the list
09-13 14:17:56.431  5984  6034 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:17:56.431  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:17:56.431  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:17:56.431  5984  6034 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,09-13 14:17:56.431  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
09-13 14:17:56.431  5984  5984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:17:56.431  5984  5984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:17:56.431  1145  2316 V AlarmManager:  remove PendingIntent] PendingIntent{15bfc09: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:56.431  5984  6034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 14:17:56.431  5984  5984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 14:17:56.431  5984  6034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything,
09-13 14:17:56.431  5984  6034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 14:17:56.431  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-13 14:17:56.431  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 14:17:56.431  1145  1318 V AlarmManager:  remove PendingIntent] PendingIntent{2eb3e0e: PendingIntentRecord{2c80b57 com.android.bluetooth broadcastIntent}}
09-13 14:17:56.431  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 10 : bytes_written: 10
09-13 14:17:56.431  5984  6034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 14:17:56.441  1145  2664 V AlarmManager:  remove PendingIntent] PendingIntent{4212d1a: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:56.431  5984  6034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 14:17:56.431  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 14:17:56.431  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 14:17:56.431  2605  2758 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-13 14:17:56.431  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:17:56.431  2605  2758 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 14:17:56.431  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 14:17:56.431  5984  5984 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 14:17:56.431  5984  6086 D BluetoothSocket: bindListen(): myUserId = 0
09-13 14:17:56.431  5984  6086 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 14:17:56.441  1145  1317 V AlarmManager:  remove PendingIntent] PendingIntent{9fa504b: PendingIntentRecord{2c80b57 com.android.bluetooth broadcastIntent}}
09-13 14:17:56.441  5984  6034 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 14:17:56.441  5984  6034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 14:17:56.441  5984  6086 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 14:17:56.441  1145  1953 V AlarmManager:  remove PendingIntent] PendingIntent{90d3a28: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:56.441  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:56.441  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:56.441  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:56.441  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 14:17:56.441  1145  1475 V AlarmManager:  remove PendingIntent] PendingIntent{54a2341: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:56.441  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:56.451  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:56.451  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 14:17:56.451  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 14:17:56.451  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:56.451  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 14:17:56.451  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:EB:95:EE"
,09-13 14:17:56.451  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 44 78 3E EB 95 EE
09-13 14:17:56.451  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:17:56.451  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:17:56.451  5984  6034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 14:17:56.451  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:56.451  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:17:56.451  5984  6034 D BluetoothLeAdvertiser: start advertising
,09-13 14:17:56.451  5984  6034 D BluetoothAdapter: STATE_ON
,09-13 14:17:56.461  2605  3157 D BtGatt.GattService: registerClient() - UUID=0640412f-aec0-419b-850d-fab46063b610
,09-13 14:17:56.501  2605  2758 D BtGatt.GattService: onClientRegistered() - UUID=0640412f-aec0-419b-850d-fab46063b610, clientIf=6
09-13 14:17:56.501  5984  5994 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 14:17:56.501  2605  2623 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-13 14:17:56.501  2605  2623 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:17:56.501  2605  2623 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:17:56.501  2605  2799 D BtGatt.AdvertiseManager: message : 0
09-13 14:17:56.501  2605  2815 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-13 14:17:56.501  2605  2815 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
09-13 14:17:56.501  2605  2799 D BtGatt.AdvertiseManager: number of adv instance running = 0
09-13 14:17:56.501  2605  2799 D BtGatt.AdvertiseManager: size of list is =0
,09-13 14:17:56.501  2605  2799 D BtGatt.AdvertiseManager: starting advertising
,09-13 14:17:56.501  2605  2799 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-13 14:17:56.501  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 28 : bytes_written: 28
,09-13 14:17:56.511  3033  3033 I WCNSS_FILTER: do_write: IBS write: fc
,09-13 14:17:56.511  1145  1953 V AlarmManager:  remove PendingIntent] PendingIntent{c9500e6: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:56.511  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 14:17:56.511  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
09-13 14:17:56.511  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-13 14:17:56.511  2605  2758 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
09-13 14:17:56.511  2605  2815 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 25
09-13 14:17:56.511  2605  2815 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24562817
,09-13 14:17:56.511  2605  2815 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-13 14:17:56.511  2605  2815 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 14:17:56.511  2605  2815 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-13 14:17:56.511  2605  2799 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 14:17:56.511  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 38 : bytes_written: 38
09-13 14:17:56.511  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 14:17:56.511  2605  2758 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
09-13 14:17:56.511  2605  2799 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-13 14:17:56.511  1145  1318 V AlarmManager:  remove PendingIntent] PendingIntent{99ba627: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:17:56.511  2605  2799 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-13 14:17:56.511  2605  2799 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
09-13 14:17:56.511  2605  2799 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
09-13 14:17:56.511  5984  5995 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
09-13 14:17:56.511  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 14:17:56.511  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 14:17:56.521  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 14:17:56.521  5984  5984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 14:17:56.521  5984  5984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 14:17:56.521  5984  5984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 14:17:56.521  5984  5984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 14:17:56.521  5984  5984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 14:17:56.521  5984  5984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-13 14:17:56.521  1145  1317 V AlarmManager:  remove PendingIntent] PendingIntent{d0fd0d4: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:56.521  5984  5984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 14:17:56.521  5984  5984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 14:17:56.521  1145  2382 V AlarmManager:  remove PendingIntent] PendingIntent{954b27d: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:56.531  1145  2016 V AlarmManager:  remove PendingIntent] PendingIntent{1204572: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:56.531  1145  2004 V AlarmManager:  remove PendingIntent] PendingIntent{8127dc3: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:17:56.621   726   726 I MSM-irqbalance: Decided to move IRQ270 from CPU3 to CPU1,
,09-13 14:17:57.021  5984  5984 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true,
09-13 14:17:57.021  5984  5984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 14:17:57.021  5984  5984 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 14:17:57.521  3033  3083 I WCNSS_FILTER: do_write: IBS write: fe
,09-13 14:17:57.521  3033  3083 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-13 14:17:59.171  1145  3580 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 14:17:59.991  1145  1589 V AlarmManager: Expired Alarm result :8
,09-13 14:18:00.021  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:00.021  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 14:18:00.021  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 14:18:00.021  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 14:18:00.021  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:18:00.021  5984  6034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 14:18:00.021  5984  6034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f96762f not in the list
09-13 14:18:00.021  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:00.021  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 14:18:00.021  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 14:18:00.021  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 14:18:00.021  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 14:18:00.021  5984  5984 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 14:18:00.021  5984  6086 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 14:18:00.021  5984  6086 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 14:18:00.021  5984  6086 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 14:18:00.021  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:18:00.021  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:18:00.021  5984  6034 D BluetoothLeScanner: could not find callback wrapper
09-13 14:18:00.021  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 14:18:00.021  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 14:18:00.021  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:18:00.031  5984  6034 D BluetoothAdapter: STATE_ON
09-13 14:18:00.031  5984  6034 D BluetoothLeAdvertiser: stop advertising
,09-13 14:18:00.031  2605  3157 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:18:00.031  1145  2316 V AlarmManager:  remove PendingIntent] PendingIntent{a032640: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:18:00.031  2605  3157 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:18:00.031  2605  2799 D BtGatt.AdvertiseManager: message : 1
09-13 14:18:00.031  2605  2815 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
09-13 14:18:00.031  2605  2815 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
09-13 14:18:00.031  2605  2815 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 14:18:00.031  2605  2799 D BtGatt.AdvertiseManager: stop advertise for client =  6
09-13 14:18:00.031  2605  2799 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
09-13 14:18:00.031  2605  2799 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
09-13 14:18:00.031  3033  3036 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
,09-13 14:18:00.041  2605  2815 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 1
09-13 14:18:00.041  2605  2815 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
,09-13 14:18:00.051  3033  3036 I WCNSS_FILTER: do_write: IBS write: fd
,09-13 14:18:00.051  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
,09-13 14:18:00.061  3033  3033 I WCNSS_FILTER: do_write: IBS write: fc
09-13 14:18:00.061  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-13 14:18:00.061  2605  2758 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-13 14:18:00.061  2605  2758 D BtGatt.GattService: Client app is not null!
09-13 14:18:00.061  3033  3036 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-13 14:18:00.061  1145  1953 V AlarmManager:  remove PendingIntent] PendingIntent{e7ef979: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}},
09-13 14:18:00.061  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
09-13 14:18:00.061  5984  5994 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,09-13 14:18:00.061  2605  2623 D BtGatt.GattService: unregisterClient() - clientIf=6
09-13 14:18:00.061  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 14:18:00.061  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 14:18:00.061  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 14:18:00.061  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 14:18:00.061  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 14:18:00.061  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 14:18:00.061  5984  6034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 14:18:00.061  1145  2016 V AlarmManager:  remove PendingIntent] PendingIntent{8a946be: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
09-13 14:18:00.061  5984  6034 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 14:18:00.061  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:00.061  5984  5984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:18:00.061  5984  6034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cd43c not in the list
09-13 14:18:00.061  5984  6034 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:00.061  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:00.061  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:00.061  5984  5984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:18:00.061  5984  5984 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 14:18:00.061  5984  5984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 14:18:00.061  5984  6034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:00.061  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 14:18:00.061  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:00.061  5984  6034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f96762f not in the list
09-13 14:18:00.061  5984  6034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:00.061  5984  6034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cd43c not in the list
09-13 14:18:00.061  5984  6034 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:00.061  5984  6034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:00.061  5984  6034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:00.071  5984  6034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-13 14:18:00.071  5984  6034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 14:18:00.071  5984  6034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-13 14:18:00.071  5984  6034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 14:18:00.071  5984  6034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 14:18:00.071  5984  6034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 14:18:00.071  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
,09-13 14:18:00.071  3033  3036 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-13 14:18:00.071  1145  1720 V AlarmManager:  remove PendingIntent] PendingIntent{895331f: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:18:00.071  3033  3033 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-13 14:18:00.071  1145  2382 V AlarmManager:  remove PendingIntent] PendingIntent{614666c: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:18:00.081  5984  6089 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 312, name: My test thread name)
,09-13 14:18:00.081  1145  1910 V AlarmManager:  remove PendingIntent] PendingIntent{16cb435: PendingIntentRecord{d50ac1f com.android.bluetooth broadcastIntent}}
,09-13 14:18:00.571  5984  5984 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,09-13 14:18:01.081  3033  3083 I WCNSS_FILTER: do_write: IBS write: fe,
09-13 14:18:01.081  3033  3083 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-13 14:18:01.621   726   726 I MSM-irqbalance: Decided to move IRQ155 from CPU3 to CPU1
,09-13 14:18:02.081  5984  6034 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 312
09-13 14:18:02.081  5984  6034 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 312, name: My test thread name)
,09-13 14:18:02.081  5984  6090 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 313, name: My test thread name)
09-13 14:18:02.081  5984  6090 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 313, thread name: My test thread name)
09-13 14:18:02.081  5984  6090 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 313, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-13 14:18:02.081  5984  6034 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 14:18:02.081  5984  6091 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 317, name: My test thread name)
09-13 14:18:02.081  5984  6091 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 317, thread name: My test thread name): Test exception.
09-13 14:18:02.081  5984  6091 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 317, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-13 14:18:02.091  5984  6034 I jxcore-log: Total number of executed tests:  76
09-13 14:18:02.091  5984  6034 I jxcore-log: 
,09-13 14:18:02.091  5984  6034 I jxcore-log: Number of passed tests:  76
09-13 14:18:02.091  5984  6034 I jxcore-log: 
09-13 14:18:02.091  5984  6034 I jxcore-log: Number of failed tests:  0
09-13 14:18:02.091  5984  6034 I jxcore-log: 
,09-13 14:18:02.091  5984  6034 I jxcore-log: Number of ignored tests:  0
09-13 14:18:02.091  5984  6034 I jxcore-log: 
,09-13 14:18:02.091  5984  6034 I jxcore-log: Total duration:  17164
09-13 14:18:02.091  5984  6034 I jxcore-log: 
,09-13 14:18:02.091  5984  6034 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-13 14:18:02.091  5984  6034 I jxcore-log: 
,09-13 14:18:02.101  5984  6034 I jxcore-log: My device name is: samsung-SM-T719
09-13 14:18:02.101  5984  6034 I jxcore-log: 
09-13 14:18:02.101  5984  6034 I jxcore-log: WARN testUtils: myNameCallback not set!
09-13 14:18:02.101  5984  6034 I jxcore-log: 
09-13 14:18:02.101  5984  6034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:02.101  5984  6034 I jxcore-log: 
09-13 14:18:02.101  5984  6034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:02.101  5984  6034 I jxcore-log: 
09-13 14:18:02.101  5984  6034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:02.101  5984  6034 I jxcore-log: 
09-13 14:18:02.111  5984  6034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:02.111  5984  6034 I jxcore-log: 
,09-13 14:18:02.111  5984  6034 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 14:18:02.111  5984  6034 I jxcore-log: 
,09-13 14:18:02.111  5984  6034 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true},
09-13 14:18:02.111  5984  6034 I jxcore-log: 
09-13 14:18:02.111  5984  6034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
09-13 14:18:02.111  5984  6034 I jxcore-log: 
09-13 14:18:02.111  5984  6034 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 14:18:02.111  5984  6034 I jxcore-log: 
,09-13 14:18:02.121  5984  6034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:02.121  5984  6034 I jxcore-log: 
,09-13 14:18:02.121  5984  6034 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 14:18:02.121  5984  6034 I jxcore-log: 
,09-13 14:18:02.121  5984  6034 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 14:18:02.121  5984  6034 I jxcore-log: 
,09-13 14:18:02.121  5984  6034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:02.121  5984  6034 I jxcore-log: 
,09-13 14:18:02.121  5984  6034 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 14:18:02.121  5984  6034 I jxcore-log: 
,09-13 14:18:02.121  5984  6034 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-13 14:18:02.121  5984  6034 I jxcore-log: 
,09-13 14:18:02.121  5984  6034 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-13 14:18:02.121  5984  6034 I jxcore-log: 
,09-13 14:18:02.121  5984  6034 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 14:18:02.121  5984  6034 I jxcore-log: 
,09-13 14:18:02.121  5984  6034 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 14:18:02.121  5984  6034 I jxcore-log: 
,09-13 14:18:02.151  5984  6089 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 312, name: My test thread name), during the lifetime of the thread the total number of bytes read was 132 and the total number of bytes written 132,
,09-13 14:18:02.661  6092  6092 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-13 14:18:02.661  6092  6092 D AndroidRuntime: CheckJNI is OFF
,09-13 14:18:02.661  6092  6092 D AndroidRuntime: readGMSProperty: start
09-13 14:18:02.661  6092  6092 D AndroidRuntime: readGMSProperty: already setted!!
09-13 14:18:02.661  6092  6092 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-13 14:18:02.661  6092  6092 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-13 14:18:02.661  6092  6092 D AndroidRuntime: readGMSProperty: end
09-13 14:18:02.661  6092  6092 D AndroidRuntime: addProductProperty: start
,09-13 14:18:02.691  6092  6092 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-13 14:18:02.721  6092  6092 I Radio-JNI: register_android_hardware_Radio DONE
,09-13 14:18:02.731  6092  6092 E AffinityControl: AffinityControl: registerfunction enter
,09-13 14:18:02.741  6092  6092 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-13 14:18:02.751  1145  2665 D PackageManager: START PACKAGE DELETE: observer{3084490}
09-13 14:18:02.751  1145  2665 D PackageManager: pkg{<packageName>}
09-13 14:18:02.751  1145  2665 D PackageManager: user{0}
09-13 14:18:02.751  1145  2665 D PackageManager: caller{2000}
09-13 14:18:02.751  1145  2665 D PackageManager: flags{2}
09-13 14:18:02.751  1145  2665 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-13 14:18:02.751  1145  2665 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-13 14:18:02.751  1145  2665 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-13 14:18:02.751  1145  2665 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-13 14:18:02.751  1145  2665 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-13 14:18:02.761  1145  1423 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-13 14:18:02.761  1145  1423 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-13 14:18:02.761  1145  1423 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-13 14:18:02.761  1145  1423 D ApplicationPolicy: getApplicationUninstallationEnabled
09-13 14:18:02.761  1145  1423 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-13 14:18:02.761  1145  1423 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-13 14:18:02.761  1145  1423 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,09-13 14:18:02.761  1145  1423 D PackageManager: !@killApplicatoin: 10136, uninstall pkg
,09-13 14:18:02.761  1145  1423 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-13 14:18:02.761  1145  1380 I ActivityManager: Force stopping com.test.thalitest appid=10136 user=-1: uninstall pkg
09-13 14:18:02.761  1145  1423 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
09-13 14:18:02.761  1145  1380 I ActivityManager: Killing 5984:com.test.thalitest/u0a136 (adj 1): stop com.test.thalitest cause uninstall pkg
09-13 14:18:02.761  1145  1380 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5984 ,hash=58515270 ,name=com.test.thalitest
,09-13 14:18:02.761  1145  1380 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-13 14:18:02.781  1145  1423 D AASAinstall: there is not AASApackages.xml file
,09-13 14:18:02.781  6101  6101 E Zygote  : v2
09-13 14:18:02.781  6101  6101 I libpersona: KNOX_SDCARD checking this for 10136
09-13 14:18:02.781  6101  6101 I libpersona: KNOX_SDCARD not a persona
,09-13 14:18:02.781  1145  1380 I ActivityManager: Start proc 6101:com.test.thalitest/u0a136 for activity com.test.thalitest/.MainActivity
,09-13 14:18:02.781  6101  6101 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-13 14:18:02.781  1145  1380 I ActivityManager:   Force finishing activity ActivityRecord{51e2ded u0 com.test.thalitest/.MainActivity t18}
09-13 14:18:02.781  1145  1380 W VirtualScreenManagerService: moveTaskBackToDisplayIfNeeded(): top activity or app is null
09-13 14:18:02.791  6101  6101 E Zygote  : accessInfo : 0
09-13 14:18:02.791  6101  6101 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-13 14:18:02.791   445   473 I SurfaceFlinger: id=16 Removed NainActivit (6/12)
09-13 14:18:02.791   445   475 I SurfaceFlinger: id=16 Removed NainActivit (-2/12)
,09-13 14:18:02.811  6101  6101 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 14:18:02.811  6101  6101 D ActivityThread: Added TimaKeyStore provider
,09-13 14:18:02.901  1145  2665 D GraphicsStats: Buffer count: 5
09-13 14:18:02.901  1145  2664 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@b177d58)
09-13 14:18:02.901   445   473 E         : BitTube(): close sendFd (43)
09-13 14:18:02.901   445   473 E         : BitTube(): close sendFd (44)
,09-13 14:18:02.901  1145  1629 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-13 14:18:02.901  1145  1629 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 14:18:02.901  1145  1629 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-13 14:18:03.061  1145  1423 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,09-13 14:18:03.161  1145  1423 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-13 14:18:03.161   567   567 W keystore: ENTER clear_uid from uid 1000 for 10136
,09-13 14:18:03.161  1145  1423 I art     : Starting a blocking GC Explicit
,09-13 14:18:03.181  6101  6101 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
09-13 14:18:03.181  6101  6101 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
09-13 14:18:03.181  6101  6101 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
09-13 14:18:03.181  6101  6101 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
,09-13 14:18:03.191  6101  6101 D AndroidRuntime: Shutting down VM
,09-13 14:18:03.201  6101  6101 E AndroidRuntime: FATAL EXCEPTION: main
09-13 14:18:03.201  6101  6101 E AndroidRuntime: Process: com.test.thalitest, PID: 6101
09-13 14:18:03.201  6101  6101 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
09-13 14:18:03.201  6101  6101 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:676)
09-13 14:18:03.201  6101  6101 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6296)
09-13 14:18:03.201  6101  6101 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:223)
09-13 14:18:03.201  6101  6101 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1863)
09-13 14:18:03.201  6101  6101 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 14:18:03.201  6101  6101 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
09-13 14:18:03.201  6101  6101 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7231)
09-13 14:18:03.201  6101  6101 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 14:18:03.201  6101  6101 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
09-13 14:18:03.201  6101  6101 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
09-13 14:18:03.201  6101  6101 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
09-13 14:18:03.201  6101  6101 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:485)
09-13 14:18:03.201  6101  6101 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:661)
09-13 14:18:03.201  6101  6101 E AndroidRuntime: 	... 9 more
,09-13 14:18:03.201  6101  6101 I Process : Sending signal. PID: 6101 SIG: 9
,09-13 14:18:03.221  1145  1380 I ActivityManager: Start proc 6114:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
,09-13 14:18:03.221  6114  6114 E Zygote  : v2
09-13 14:18:03.221  6114  6114 I libpersona: KNOX_SDCARD checking this for 1000
09-13 14:18:03.221  6114  6114 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-13 14:18:03.221  6114  6114 I libpersona: KNOX_SDCARD not a persona
,09-13 14:18:03.221  6114  6114 E Zygote  : accessInfo : 0
,09-13 14:18:03.241  6114  6114 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 14:18:03.241  6114  6114 D ActivityThread: Added TimaKeyStore provider
,09-13 14:18:03.251  1145  2382 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3956f96 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b415eb1 6114:com.samsung.android.sm/1000}
,09-13 14:18:03.281  6114  6114 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1311 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.samsung.android.sm.common.SmartManagerReceiver.b:259 com.samsung.android.sm.common.SmartManagerReceiver.onReceive:107 
,09-13 14:18:03.301  1145  1910 I ActivityManager: Process com.test.thalitest (pid 6101)(adj 9) has died(143,1529)
09-13 14:18:03.301  1145  1910 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=6101 ,hash=23323195 ,name=com.test.thalitest
09-13 14:18:03.301  1145  1910 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
09-13 14:18:03.301  1145  1910 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.android.server.am.ActivityManagerService.updateOomAdjLocked:26615 com.android.server.am.ActivityManagerService.appDiedLocked:7605 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1888 android.os.BinderProxy.sendDeathNotice:558 
,09-13 14:18:03.401  1145  1423 I art     : Explicit concurrent mark sweep GC freed 243789(14MB) AllocSpace objects, 65(3MB) LOS objects, 33% free, 29MB/44MB, paused 2.802ms total 237.236ms
,09-13 14:18:03.421  1145  1423 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-13 14:18:03.421  1145  1423 D AASAuninstall: userId = 0, info.removedAppID = 10136, info.uid = 10136, packageName = com.test.thalitest
09-13 14:18:03.421  1145  1423 D AASAinstall: there is not AASApackages.xml file
09-13 14:18:03.421  1145  1423 D PackageManager: result of delete: 1{3084490}
,09-13 14:18:03.421  1145  1423 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-13 14:18:03.421  1145  1423 D PackageManager: userId{-1}
09-13 14:18:03.421  1145  1423 D PackageManager: andCode{true}
,09-13 14:18:03.421  6092  6092 I art     : System.exit called, status: 0
09-13 14:18:03.421  6092  6092 I AndroidRuntime: VM exiting with result code 0.
,09-13 14:18:03.431  1145  1423 I ActivityManager: Force stopping com.test.thalitest appid=10136 user=0: pkg removed
,09-13 14:18:03.461  5730  6128 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,09-13 14:18:03.461  5730  6128 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,09-13 14:18:03.471  5730  6128 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,09-13 14:18:03.481  1693  1693 D ShortcutManager: onReceive : android.intent.action.PACKAGE_REMOVED
09-13 14:18:03.481  1693  1693 D ShortcutManager: onReceive : Intent.EXTRA_REPLACING false,com.test.thalitest
,09-13 14:18:03.481  1693  1693 D CoverUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
,09-13 14:18:03.481  1145  1591 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 14:18:03.491  1872  2392 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-13 14:18:03.491  5005  5035 I SystemBroadcastReceiver: [#CMH#] Received broadcast 
,09-13 14:18:03.501  5005  5035 I ControllerEventHandler: [#CMH#] onPackageRemoved  null
09-13 14:18:03.501  5005  5035 I SystemBroadcastReceiver: [#CMH#] onReceive completed 
,09-13 14:18:03.511  1145  1619 V NetworkStats: removeUidsLocked() for UIDs [10136]
09-13 14:18:03.511  1145  1619 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 14:18:03.511  1145  1619 V NetworkStats: performPollLocked(flags=0x3)
,09-13 14:18:03.511  1948  1948 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-13 14:18:03.521  1145  1619 D NetworkStatsRecorder: entry.iface is null
09-13 14:18:03.521  1145  1619 D NetworkStatsRecorder: entry.iface is null
09-13 14:18:03.521  1145  1619 D NetworkStatsRecorder: entry.iface is null
09-13 14:18:03.521  1145  1619 D NetworkStatsRecorder: entry.iface is null
,09-13 14:18:03.521  1145  1380 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b5764d2 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{aff4775 3903:com.samsung.klmsagent/u0a16}
09-13 14:18:03.521  1797  1797 I Recents_MultiWindowAppListInfo: android.intent.action.PACKAGE_REMOVE
09-13 14:18:03.521  3903  3903 I KLMS-2.6.094: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } | timestamp: Tue Sep 13 14:18:03 GMT+02:00 2016
,09-13 14:18:03.531  1145  2665 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=2483, uid=10093 that is not exported from uid 10091
,09-13 14:18:03.531  1145  1371 D EnterpriseDeviceManagerService: Package has changed for user 0
,09-13 14:18:03.531  1145  1371 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,09-13 14:18:03.541  3903  3903 I KLMS-2.6.094: : KLMSAbstractReciever(): onReceive().END.
,09-13 14:18:03.541  3903  3903 I KLMS-2.6.094: : KLMSIntentService(): onCreate()
,09-13 14:18:03.541  3903  3903 I KLMS-2.6.094: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-13 14:18:03.541  1145  1720 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b5764d2 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d4c9954 1145:system/1000}
,09-13 14:18:03.541  1145  1619 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 14:18:03.541  1145  1619 V NetworkStats: performPollLocked() took 38ms
,09-13 14:18:03.551  1145  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 14:18:03.551  1145  1620 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 14:18:03.551  3903  3903 I KLMS-2.6.094: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-13 14:18:03.561  3903  6132 I KLMS-2.6.094: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-13 14:18:03.561  3903  6132 D KLMS-2.6.094: : KLMSIntentService(): PACKAGE_REMOVED
09-13 14:18:03.561  3903  6132 I KLMS-2.6.094: : Systemprocess(): listeningToPackageRemoved().START
09-13 14:18:03.561  3903  6132 I KLMS-2.6.094: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
09-13 14:18:03.561  3903  6132 I KLMS-2.6.094: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
09-13 14:18:03.561  3903  6132 I KLMS-2.6.094: : MDMBridge(): getAllLicenseInfoFromSDK()
,09-13 14:18:03.561  3903  6132 I KLMS-2.6.094: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-13 14:18:03.561  3903  6132 I KLMS-2.6.094: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-13 14:18:03.571  3903  6132 I KLMS-2.6.094: : MDMBridge(): getAllLicenseInfoFromSDK()
,09-13 14:18:03.571  3903  6132 D KLMS-2.6.094: : Systemprocess(): arrayLicenseInfo is null
,09-13 14:18:03.581  3903  6132 W FileUtils: Failed to chmod(/data/user/0/com.samsung.klmsagent/databases/klms.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,09-13 14:18:03.581  3903  6132 D KLMS-2.6.094: : DataSource(): Fetched Data from data base count : 0
09-13 14:18:03.581  1145  1145 V AlarmManager: Remove alarm for next reason : android.intent.action.PACKAGE_REMOVED : package: com.test.thalitest
,09-13 14:18:03.581  1145  1145 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-13 14:18:03.581  1145  1720 D SettingsProvider: isChangeAllowed() : name = klm_eula_shown
09-13 14:18:03.581  1145  1720 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-13 14:18:03.581  1145  1720 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
09-13 14:18:03.581  1145  1720 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-13 14:18:03.581  1145  1720 D SettingsProvider: selectionArgs: false
09-13 14:18:03.581  1145  1720 D SettingsProvider: selectionArgs: 10016
,09-13 14:18:03.581  1145  1145 D UniversalCredentialManagerService: inside mPkgReciever onReceive : android.intent.action.PACKAGE_REMOVED
09-13 14:18:03.581  1145  1145 D UniversalCredentialManagerService: ACTION_PACKAGE_REMOVED is called....
09-13 14:18:03.581  1145  1720 D SettingsProvider: ret = -1
09-13 14:18:03.581  1145  1145 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-13 14:18:03.581  1145  1145 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-13 14:18:03.581  1145  1145 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10136 container id = 0
,09-13 14:18:03.581  1145  1145 I OTPFW   : ProvisionData::getAllEntries Enter
,09-13 14:18:03.581  1145  1145 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-13 14:18:03.581  1145  1145 E SDAgentPackageStateReceiver: Not going to handle 'com.test.thalitest'!
,09-13 14:18:03.591  1145  1145 D UcmService: onReceive android.intent.action.PACKAGE_REMOVED
,09-13 14:18:03.591  1145  1145 D UcmService: Package update in userId-0 and uid-10136
,09-13 14:18:03.591  1145  1145 D GameManager.DatabaseHelper: removeGame(), packageName: com.test.thalitest, ret: 0
09-13 14:18:03.591  1145  1145 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-13 14:18:03.591  1145  1145 V EnterpriseBillingAsyncHandler: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-13 14:18:03.591  1145  1654 V EnterpriseBillingPolicyInternal: packageModification -  start - android.intent.action.PACKAGE_REMOVED
09-13 14:18:03.591  1145  1654 V EnterpriseBillingPolicyInternal: uID is 10136
09-13 14:18:03.591  1145  1654 V EnterpriseBillingPolicyInternal: Removed Packageuid is0
09-13 14:18:03.591  1145  1654 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-13 14:18:03.591  1145  1654 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-13 14:18:03.591  1145  1654 V EnterpriseBillingPolicyInternal: packageModificationReceiver - onreceive - personal application - profile null
,09-13 14:18:03.601  1145  1145 D SdpManagerService:  ActionReceiver::onReceive() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-13 14:18:03.601  1145  1145 D SdpManagerService: ACTION_PACKAGE_REMOVED Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } DATA= package:com.test.thalitest UID 1000 userId 0
09-13 14:18:03.601  1145  1145 D SdpManagerService: ACTION_PACKAGE_REMOVED packageName:: com.test.thalitest
,09-13 14:18:03.601  1145  1145 D EnterprisePartitionManager: SND -> {secure_fs remove_enc_dir}
,09-13 14:18:03.601   385   439 D epmd    : Partition obj created
09-13 14:18:03.601   385   439 D epmd    : Partition::dump============== 0
09-13 14:18:03.601   385   439 D epmd    : Partition::mType > INTERNAL-SDCARD mSrcPath > /data/knox/secure_fs/enc_user mMntPath > /data/enc_user
09-13 14:18:03.601   385   439 D epmd    : Partition::SDP > not supported
,09-13 14:18:03.601   385   439 E epmd    : removeEncPkgDir ERROR
09-13 14:18:03.601   385   439 D epmd    : deleting Partition object.
09-13 14:18:03.601   385   439 W FrameworkListener: Handler 'secure_fs' error (No such file or directory)
,09-13 14:18:03.601  1145  1425 D EnterprisePartitionManager: RCV <-
,09-13 14:18:03.601  1145  1145 D EnterprisePartitionManager: RMV <-
09-13 14:18:03.601  1145  1145 D EnterprisePartitionManager: event : 281 3 remove_enc_dir failed
09-13 14:18:03.601  1145  1145 D SdpManagerService: start document   : 
09-13 14:18:03.601  1145  1145 D SdpManagerService: start element    : engine_list
09-13 14:18:03.601  1145  1145 D SdpManagerService: start characters : 
09-13 14:18:03.601  1145  1145 D SdpManagerService: start element    : engine
09-13 14:18:03.601  1145  1145 D SdpManagerService:  attribte alias: android_0
09-13 14:18:03.601  1145  1145 D SdpManagerService:  attribte id: 0
09-13 14:18:03.601  1145  1145 D SdpManagerService: end element      : engine
09-13 14:18:03.601  1145  1145 D SdpManagerService: start characters : 
09-13 14:18:03.601  1145  1145 D SdpManagerService: end element      : engine_list
09-13 14:18:03.601  1145  1145 D SdpManagerService: end document     : 
09-13 14:18:03.601  1145  1145 W System.err: mkdir failed: EEXIST (File exists) : /data/system/users/0
09-13 14:18:03.601  1145  1145 E SdpManagerService: cant make directory /data/system/users/0
09-13 14:18:03.601  1145  1145 D SdpManagerService: start document   : 
09-13 14:18:03.601  1145  1145 D SdpManagerService: start element    : user
09-13 14:18:03.601  1145  3550 D SSRM:bb : MSG_TYPE_APP_REMOVED::
09-13 14:18:03.601  1145  1145 D SdpManagerService: end element      : user
09-13 14:18:03.601  1145  1145 D SdpUtil : num:0 index-0
09-13 14:18:03.601  1145  1145 D SdpUtil : detecected userId : 0
09-13 14:18:03.601  1145  1145 D SdpManagerService: end document     : 
09-13 14:18:03.601  1145  1145 E SdpManagerService: Can't find engine info [android_0]
09-13 14:18:03.601  1145  1145 V EnterpriseBillingAsyncHandler: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-13 14:18:03.601  1145  1654 V EnterpriseBillingPolicyInternal: packageModification -  start - android.intent.action.PACKAGE_FULLY_REMOVED
09-13 14:18:03.601  1145  1654 V EnterpriseBillingPolicyInternal: uID is 10136
09-13 14:18:03.601  1145  1654 V EnterpriseBillingPolicyInternal: Removed Packageuid is0
09-13 14:18:03.601  1145  1654 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-13 14:18:03.611  1145  1654 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-13 14:18:03.611  1145  1145 D AccessibilityManagerService: checkUniversalSwitchState start:
09-13 14:18:03.611  1145  1654 V EnterpriseBillingPolicyInternal: packageModificationReceiver - onreceive - personal application - profile null
09-13 14:18:03.611  1145  3550 D SSRM:bb : MSG_TYPE_UID_REMOVED::
,09-13 14:18:03.621  5786  5797 E SQLiteLog: (10) unixWrite() File Descriptor : 20 gets errno : 30
,09-13 14:18:03.621  5786  5797 E DatabaseUtils: Writing exception to parcel
09-13 14:18:03.621  5786  5797 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
09-13 14:18:03.621  5786  5797 E DatabaseUtils: #################################################################
09-13 14:18:03.621  5786  5797 E DatabaseUtils: Error Code : 778 (SQLITE_IOERR_WRITE)
09-13 14:18:03.621  5786  5797 E DatabaseUtils: Caused By : Disk I/O error occurred during 'write' operation.
09-13 14:18:03.621  5786  5797 E DatabaseUtils: 	(disk I/O error (code 778))
09-13 14:18:03.621  5786  5797 E DatabaseUtils: #################################################################
09-13 14:18:03.621  5786  5797 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 14:18:03.621  5786  5797 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:866)
09-13 14:18:03.621  5786  5797 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 14:18:03.621  5786  5797 E DatabaseUtils: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 14:18:03.621  5786  5797 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
09-13 14:18:03.621  5786  5797 E DatabaseUtils: 	at com.samsung.android.sm.database.SmProvider.delete(SmProvider.java:826)
09-13 14:18:03.621  5786  5797 E DatabaseUtils: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:352)
09-13 14:18:03.621  5786  5797 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:206)
09-13 14:18:03.621  5786  5797 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:453)
,09-13 14:18:03.621  1145  1413 E MARsDBManager: Exception with contentResolver : disk I/O error (code 778)
09-13 14:18:03.621  1145  1413 E MARsDBManager: #################################################################
09-13 14:18:03.621  1145  1413 E MARsDBManager: Error Code : 778 (SQLITE_IOERR_WRITE)
09-13 14:18:03.621  1145  1413 E MARsDBManager: Caused By : Disk I/O error occurred during 'write' operation.
09-13 14:18:03.621  1145  1413 E MARsDBManager: 	(disk I/O error (code 778))
09-13 14:18:03.621  1145  1413 E MARsDBManager: #################################################################
09-13 14:18:03.621  1145  1413 E MARsDBManager: #################################################################
09-13 14:18:03.621  1145  1413 E MARsDBManager: Error Code : 778 (SQLITE_IOERR_WRITE)
09-13 14:18:03.621  1145  1413 E MARsDBManager: Caused By : Disk I/O error occurred during 'write' operation.
09-13 14:18:03.621  1145  1413 E MARsDBManager: 	(disk I/O error (code 778)
09-13 14:18:03.621  1145  1413 E MARsDBManager: #################################################################
09-13 14:18:03.621  1145  1413 E MARsDBManager: Error Code : 778 (SQLITE_IOERR_WRITE)
09-13 14:18:03.621  1145  1413 E MARsDBManager: Caused By : Disk I/O error occurred during 'write' operation.
09-13 14:18:03.621  1145  1413 E MARsDBManager: 	(disk I/O error (code 778))
09-13 14:18:03.621  1145  1413 E MARsDBManager: #################################################################)
09-13 14:18:03.621  1145  1413 E MARsDBManager: #################################################################
,09-13 14:18:03.631  1145  1156 I art     : Background partial concurrent mark sweep GC freed 25976(1790KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 29MB/43MB, paused 6.373ms total 191.306ms

```
