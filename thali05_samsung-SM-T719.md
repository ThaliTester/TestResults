#### Test 83084099807e426_thali05_samsung-SM-T719 Logs


```
--------- beginning of system
08-31 16:50:26.789  1159  3439 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 16:50:26.919  1159  3409 D SSRM:s  : SIOP:: AP = 340, PST = 368 (W:7), CP = 40, LCD = 0
08-31 16:50:26.919  1159  3409 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
--------- beginning of main
08-31 16:50:27.229  5627  5627 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-31 16:50:27.229  5627  5627 D AndroidRuntime: CheckJNI is OFF
08-31 16:50:27.229  5627  5627 D AndroidRuntime: readGMSProperty: start
08-31 16:50:27.229  5627  5627 D AndroidRuntime: readGMSProperty: already setted!!
08-31 16:50:27.229  5627  5627 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-31 16:50:27.229  5627  5627 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-31 16:50:27.229  5627  5627 D AndroidRuntime: readGMSProperty: end
08-31 16:50:27.229  5627  5627 D AndroidRuntime: addProductProperty: start
08-31 16:50:27.259  5627  5627 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-31 16:50:27.299  5627  5627 I Radio-JNI: register_android_hardware_Radio DONE
08-31 16:50:27.309  5627  5627 E AffinityControl: AffinityControl: registerfunction enter
08-31 16:50:27.319  5627  5627 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-31 16:50:27.359  1159  1950 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
08-31 16:50:27.369  1159  1950 D GameManagerService: identifyGamePackage. com.test.thalitest
08-31 16:50:27.369  1159  1950 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
08-31 16:50:27.389  1159  1950 D ActivityManager: mDVFSHelper.acquire()
08-31 16:50:27.389   447   447 I SurfaceFlinger: id=12 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-31 16:50:27.399   447   447 I SurfaceFlinger: id=13 createSurf (16x16),-1 flag=20004, EimLayer(An
08-31 16:50:27.399  1159  1159 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-31 16:50:27.399  1159  1950 D FocusedStackFrame: Set to : 0
08-31 16:50:27.399  1159  1159 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-31 16:50:27.399  1159  1950 V WindowManager: addAppToken: AppWindowToken{d091298b2 token=Token{79b4abd ActivityRecord{2eca214 u0 com.test.thalitest/.MainActivity t18}}} to stack=2 task=18 at 0
08-31 16:50:27.399  1705  1705 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-31 16:50:27.399  1705  1705 D WallpaperService: MSG_WINDOW_RESIZED
08-31 16:50:27.399  1705  1705 D WallpaperService: updateSurface
08-31 16:50:27.399  1705  1705 V WallpaperService: Changes: creating=false format=false size=false
08-31 16:50:27.399  1705  1705 V WallpaperService: mWidth:2048 SurfaceWidth:2048 mHeight:2048 SurfaceHeigh:2048
08-31 16:50:27.399  1705  1705 D WallpaperService: relayout
08-31 16:50:27.409  1705  1705 V WallpaperService: Wallpaper size has changed: (2048, 2048)
08-31 16:50:27.409  1159  1403 D SecWifiDisplayUtil: Metadata value : SecSettings2
08-31 16:50:27.409  1159  1403 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{b308c0a V.E...... R.....ID 0,0-0,0}
08-31 16:50:27.419  1159  1950 I ActivityManager: Start proc 5636:com.test.thalitest/u0a136 for activity com.test.thalitest/.MainActivity
08-31 16:50:27.419  5636  5636 E Zygote  : v2
08-31 16:50:27.419  5636  5636 I libpersona: KNOX_SDCARD checking this for 10136
08-31 16:50:27.419  1159  1950 D InputDispatcher: Focused application set to: xxxx
08-31 16:50:27.419  5636  5636 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:27.419  5636  5636 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:27.419  1159  1622 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-31 16:50:27.419  5627  5627 D AndroidRuntime: Shutting down VM
08-31 16:50:27.419  5636  5636 E Zygote  : accessInfo : 0
08-31 16:50:27.419  5636  5636 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-31 16:50:27.419   447   447 I SurfaceFlinger: id=14 createSurf (1536x2048),1 flag=404, uhalitest
08-31 16:50:27.429  1159  1403 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 48 - 0, 0) vi=Rect(0, 48 - 0, 0) or=1
08-31 16:50:27.439  5636  5636 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:27.439  5636  5636 D ActivityThread: Added TimaKeyStore provider
08-31 16:50:27.449  1159  1200 D ActivityManager:  Launching com.test.thalitest, updated priority
08-31 16:50:27.449  1980  1980 V ActivityThread: updateVisibility : ActivityRecord{c4fa2c9 token=android.os.BinderProxy@fb0d955 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
08-31 16:50:27.459  1159  1159 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
08-31 16:50:27.469  1159  1403 V WindowStateAnimator: Finishing drawing window Window{1578a98 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-31 16:50:27.479   447  1658 I SurfaceFlinger: id=9 Removed MauncherAct (5/11)
08-31 16:50:27.479   447   476 I SurfaceFlinger: id=9 Removed MauncherAct (-2/11)
08-31 16:50:27.479  1980  1980 D Launcher: onTrimMemory. Level: 20
,08-31 16:50:27.769  1159  1200 I WindowManager: Screenshot max retries 4 of Token{79b4abd ActivityRecord{2eca214 u0 com.test.thalitest/.MainActivity t18}} appWin=Window{1578a98 u0 d0 Starting com.test.thalitest} drawState=4
08-31 16:50:27.769  1159  1366 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
,08-31 16:50:27.769  1159  1622 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-31 16:50:27.779  1159  3409 D GameManagerService: identifyGamePackage. com.test.thalitest
,08-31 16:50:27.789  1159  3409 D GameManagerService: identifyGamePackage. com.test.thalitest
,08-31 16:50:27.809  1159  1200 W ActivityManager: Permission Denial: getCurrentUser() from pid=5636, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
,08-31 16:50:27.829  5636  5636 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-31 16:50:27.829  5636  5636 D RelationGraph: garbageCollect()
,08-31 16:50:27.849  1159  1202 W ActivityManager: Permission Denial: getCurrentUser() from pid=5636, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
,08-31 16:50:27.859  5636  5636 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
,08-31 16:50:27.889  5636  5636 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-31 16:50:27.919  5636  5636 I cr_LibraryLoader: Time to load native libraries: 11 ms (timestamps 6909-6920)
,08-31 16:50:27.919  5636  5636 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
,08-31 16:50:27.939  5636  5650 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-31 16:50:27.949  5636  5636 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7a2026b}
,08-31 16:50:27.949  5636  5636 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
,08-31 16:50:27.959  5636  5636 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 16:50:27.979  5636  5636 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-31 16:50:28.019  5636  5652 W chromium: [WARNING:dns_config_service_posix.cc(306)] Failed to read DnsConfig.
,08-31 16:50:28.049  5636  5636 I Adreno  : QUALCOMM build                   : 971aff5, Ic07f1cdce3
08-31 16:50:28.049  5636  5636 I Adreno  : Build Date                       : 03/29/16
08-31 16:50:28.049  5636  5636 I Adreno  : OpenGL ES Shader Compiler Version: XE031.06.00.02
08-31 16:50:28.049  5636  5636 I Adreno  : Local Branch                     : 
08-31 16:50:28.049  5636  5636 I Adreno  : Remote Branch                    : refs/tags/AU_LINUX_ANDROID_LA.BR.1.3.3.C2.06.00.01.205.077
08-31 16:50:28.049  5636  5636 I Adreno  : Remote Branch                    : NONE
08-31 16:50:28.049  5636  5636 I Adreno  : Reconstruct Branch               : NOTHING
,08-31 16:50:28.109  1159  2313 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10136
08-31 16:50:28.109  1159  2313 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:851 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29617 com.android.server.am.ActivityManagerService.registerReceiver:22639 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3995 
,08-31 16:50:28.189  5636  5636 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-31 16:50:28.199  5636  5636 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-31 16:50:28.199  5636  5636 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-31 16:50:28.219  5636  5636 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-31 16:50:28.259  5636  5636 D SecWifiDisplayUtil: Metadata value : SecSettings2
,08-31 16:50:28.259  5636  5636 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{5e1d428 I.E...... R.....ID 0,0-0,0}
,08-31 16:50:28.259  5636  5674 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-31 16:50:28.269  1159  1366 W ActivityManager: Activity pause timeout for ActivityRecord{2eca214 u0 com.test.thalitest/.MainActivity t18}
,08-31 16:50:28.269  1159  1988 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-31 16:50:28.269  1159  1988 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-31 16:50:28.269  1159  1159 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-31 16:50:28.269  1159  1159 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-31 16:50:28.279  5636  5650 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-31 16:50:28.279  3613  3613 D FactoryTest: User mode
,08-31 16:50:28.279  3613  3613 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-31 16:50:28.279  3613  3613 D MTPRx   : still no open session command from host, so toast
,08-31 16:50:28.289  1159  1950 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
,08-31 16:50:28.289  1159  1950 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
08-31 16:50:28.289  1159  1950 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.samsung.android.MtpApplication)
,08-31 16:50:28.299  1159  1950 D ActivityManager: mDVFSHelper.acquire()
08-31 16:50:28.299  1159  1950 V WindowManager: addAppToken: AppWindowToken{d084ed3d3 token=Token{d7ee9c2 ActivityRecord{950f60d u0 com.samsung.android.MtpApplication/.USBConnection t19}}} to stack=2 task=19 at 0
08-31 16:50:28.299  1159  1950 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,08-31 16:50:28.309  1159  1159 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
08-31 16:50:28.309  1159  1366 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-31 16:50:28.319  1159  1950 D InputDispatcher: Focused application set to: xxxx
,08-31 16:50:28.319  3613  3613 E MTPRx   : started activity for popup
,08-31 16:50:28.319  5636  5636 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10136, CallingPid : 5636
,08-31 16:50:28.319  1159  1976 D ConnectivityService: listenForNetwork for Listen from uid/pid:10136/5636 for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:50:28.319  3613  3613 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-31 16:50:28.319  3613  3613 D RelationGraph: garbageCollect()
08-31 16:50:28.319  1159  3409 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,08-31 16:50:28.329  5636  5636 D SecWifiDisplayUtil: Metadata value : SecSettings2
,08-31 16:50:28.339  3613  3613 D MTPUSBConnection: onCreate in USBConnection
08-31 16:50:28.339  3613  3613 V MTPUSBConnection: Registering broadcast receiver.
,08-31 16:50:28.339   447   447 I SurfaceFlinger: id=15 createSurf (1536x2048),1 flag=404, NainActivit
,08-31 16:50:28.339  3613  3613 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,08-31 16:50:28.349  1159  1724 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,08-31 16:50:28.349  5636  5674 I OpenGLRenderer: Initialized EGL, version 1.4
,08-31 16:50:28.359  5636  5636 V ActivityThread: updateVisibility : ActivityRecord{d4d647d token=android.os.BinderProxy@50cbaae {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-31 16:50:28.359  5636  5636 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 48 - 0, 0) vi=Rect(0, 48 - 0, 0) or=1
,08-31 16:50:28.389  3613  3613 D TAG     : dev.kiessupport is : TRUE
,08-31 16:50:28.399  5636  5674 E libGLESv2: HWUI Protection: wrong call from hwui context F: ES3-glCreateProgramSEC
,08-31 16:50:28.409  5636  5680 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-31 16:50:28.409  3613  3613 D SecWifiDisplayUtil: Metadata value : SecSettings2
,08-31 16:50:28.419  3613  3613 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{88f5c18 V.E...... R.....I. 0,0-0,0}
,08-31 16:50:28.419  3613  5683 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-31 16:50:28.429  3613  3613 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{d4df773 I.E...... R.....I. 0,0-0,0}
,08-31 16:50:28.429  1159  1202 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-31 16:50:28.429  1159  1202 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-31 16:50:28.429  1159  1159 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-31 16:50:28.429  1159  1159 I KnoxTimeoutHandler: Shared devices show user statefalse
08-31 16:50:28.429  1159  1159 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-31 16:50:28.439  1159  1724 V WindowStateAnimator: Finishing drawing window Window{1064dd1 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
08-31 16:50:28.439  5636  5636 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@50cbaae time:97447
,08-31 16:50:28.449   447   447 I SurfaceFlinger: id=16 createSurf (97x97),1 flag=4, VSBConnecti
,08-31 16:50:28.469  5636  5636 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5636
08-31 16:50:28.469  1159  1403 D ActivityManager: mDVFSHelper.release()
08-31 16:50:28.469  1159  1403 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-31 16:50:28.469  1159  1159 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-31 16:50:28.469  1159  1403 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +699ms (total +1s63ms)
08-31 16:50:28.469  1159  1159 I KnoxTimeoutHandler: SD activityfalse
08-31 16:50:28.469  1159  1159 I KnoxTimeoutHandler: Fullscreen and mCurrent is not KNOX user. Hence hide keyguard
08-31 16:50:28.469  1159  1403 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2eca214 u0 com.test.thalitest/.MainActivity t18} time:97472
08-31 16:50:28.469  3613  5683 I Adreno  : QUALCOMM build                   : 971aff5, Ic07f1cdce3
08-31 16:50:28.469  3613  5683 I Adreno  : Build Date                       : 03/29/16
08-31 16:50:28.469  3613  5683 I Adreno  : OpenGL ES Shader Compiler Version: XE031.06.00.02
08-31 16:50:28.469  3613  5683 I Adreno  : Local Branch                     : 
08-31 16:50:28.469  3613  5683 I Adreno  : Remote Branch                    : refs/tags/AU_LINUX_ANDROID_LA.BR.1.3.3.C2.06.00.01.205.077
08-31 16:50:28.469  3613  5683 I Adreno  : Remote Branch                    : NONE
08-31 16:50:28.469  3613  5683 I Adreno  : Reconstruct Branch               : NOTHING
08-31 16:50:28.469  1159  1403 D ViewRootImpl: #3 mView = null
08-31 16:50:28.469   447   468 I SurfaceFlinger: id=14 Removed uhalitest (6/12)
,08-31 16:50:28.469   447  1658 I SurfaceFlinger: id=14 Removed uhalitest (-2/12)
,08-31 16:50:28.469  3613  5683 I OpenGLRenderer: Initialized EGL, version 1.4
,08-31 16:50:28.489   447   447 I SurfaceFlinger: id=17 createSurf (129x129),1 flag=4, VSBConnecti
,08-31 16:50:28.499  3613  3613 V ActivityThread: updateVisibility : ActivityRecord{403902e token=android.os.BinderProxy@23711e0 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-31 16:50:28.519  3613  5683 E libGLESv2: HWUI Protection: wrong call from hwui context F: ES3-glCreateProgramSEC
,08-31 16:50:28.519  3613  5683 E libGLESv2: HWUI Protection: wrong call from hwui context F: ES3-glCreateProgramSEC
,08-31 16:50:28.519  3613  5683 E libGLESv2: HWUI Protection: wrong call from hwui context F: ES3-glCreateProgramSEC
,08-31 16:50:28.529  1159  1976 V WindowStateAnimator: Finishing drawing window Window{c71e2e6 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-31 16:50:28.529  1159  1200 V WindowStateAnimator: Finishing drawing window Window{29c82d4 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-31 16:50:28.529  3613  3613 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-31 16:50:28.529  3613  3613 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,08-31 16:50:28.539  1159  1403 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-31 16:50:28.539  1159  1159 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-31 16:50:28.539  1159  1403 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +229ms
08-31 16:50:28.539  1159  1403 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{950f60d u0 com.samsung.android.MtpApplication/.USBConnection t19} time:97544
,08-31 16:50:28.539  1159  1159 I KnoxTimeoutHandler: SD activityfalse
,08-31 16:50:28.539  1159  1724 V WindowStateAnimator: Finishing drawing window Window{c71e2e6 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,08-31 16:50:28.539  1159  1978 V WindowStateAnimator: Finishing drawing window Window{29c82d4 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
08-31 16:50:28.539  3613  3613 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@23711e0 time:97547
,08-31 16:50:28.649  5636  5636 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 16:50:28.769  5636  5689 D jxcore_app_log: JniHelper::setJavaVM(0xf50bc000), pthread_self() = -606078672
,08-31 16:50:28.779  5636  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 16:50:28.779  5636  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 16:50:28.779  5636  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 16:50:28.779  5636  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 16:50:28.779  5636  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-31 16:50:28.779  5636  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a3e1aca added. We now have 1 listener(s)
,08-31 16:50:28.779  5636  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:EB:95:EE
08-31 16:50:28.779  5636  5689 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:EB:95:EE"
,08-31 16:50:28.779  5636  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 16:50:28.779  5636  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 16:50:28.789  5636  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 16:50:28.789  5636  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 16:50:28.789  5636  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 16:50:28.789  5636  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:78:3E:EB:95:EE
08-31 16:50:28.789  5636  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 16:50:28.789  5636  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 16:50:28.789  5636  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 16:50:28.789  5636  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 16:50:28.789  5636  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 16:50:28.789  5636  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 16:50:28.789  5636  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 16:50:28.789  5636  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 16:50:28.789  5636  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 16:50:28.789  5636  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-31 16:50:28.789  5636  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@53b70b1 added. We now have 1 listener(s)
08-31 16:50:28.789  5636  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 16:50:28.789  5636  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 16:50:28.789  5636  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-31 16:50:28.789  5636  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 16:50:28.789  5636  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 16:50:28.789  5636  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-31 16:50:28.789  5636  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 16:50:28.789  5636  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:EB:95:EE
,08-31 16:50:28.799  5636  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 16:50:28.799  5636  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 16:50:28.799  5636  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:50:28.799  5636  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 16:50:28.799  5636  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 16:50:28.799  5636  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 16:50:28.799  5636  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:50:28.799  5636  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:50:28.799  5636  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 16:50:28.799  5636  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 16:50:28.799  5636  5689 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 16:50:28.799  5636  5689 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 16:50:28.819  5636  5636 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 16:50:29.359  5636  5690 W jxcore-log: Initializing JXcore engine
08-31 16:50:29.359  5636  5690 W jxcore-log: JXcore engine is ready
,08-31 16:50:29.389  2530  2530 E audit   : type=1400 msg=audit(1472655029.389:265): avc:  denied  { ioctl } for  pid=5690 comm="Thread-96" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5369 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-31 16:50:29.389  2530  2530 E audit   :  SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:29.389  2530  2530 E audit   : type=1300 msg=audit(1472655029.389:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=7 a1=5451 a2=3 a3=d9f033c8 items=0 ppid=594 pid=5690 auid=4294967295 uid=10136 gid=10136 euid=10136 suid=10136 fsuid=10136 egid=10136 sgid=10136 fsgid=10136 ses=4294967295 tty=(none) comm="Thread-96" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-31 16:50:29.389  2530  2530 E audit   : type=1327 msg=audit(1472655029.389:265): proctitle="com.test.thalitest"
08-31 16:50:29.389  2530  2530 E audit   : type=1320 msg=audit(1472655029.389:265): 
08-31 16:50:29.389  2530  2530 E audit   : type=1400 msg=audit(1472655029.389:266): avc:  denied  { ioctl } for  pid=5690 comm="Thread-96" path="socket:[39534]" dev="sockfs" ino=39534 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-31 16:50:29.389  2530  2530 E audit   :  SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:29.389  2530  2530 E audit   : type=1300 msg=audit(1472655029.389:266): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3c a1=5451 a2=3 a3=d9f033c8 items=0 ppid=594 pid=5690 auid=4294967295 uid=10136 gid=10136 euid=10136 suid=10136 fsuid=10136 egid=10136 sgid=10136 fsgid=10136 ses=4294967295 tty=(none) comm="Thread-96" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-31 16:50:29.389  2530  2530 E audit   : type=1327 msg=audit(1472655029.389:266): proctitle="com.test.thalitest"
08-31 16:50:29.389  2530  2530 E audit   : type=1320 msg=audit(1472655029.389:266): 
,08-31 16:50:29.399  5636  5690 W jxcore-log: Starting JXcore engine
,08-31 16:50:29.429  1796  1796 D Recents : onTaskStackChanged
,08-31 16:50:29.449  5636  5690 W jxcore-log: Platform android
08-31 16:50:29.449  5636  5690 W jxcore-log: 
08-31 16:50:29.449  5636  5690 W jxcore-log: Process ARCH arm
08-31 16:50:29.449  5636  5690 W jxcore-log: 
,08-31 16:50:29.469  1159  2558 D PackageManager: getComponentMetadataForIconTray : com.test.thalitest.MainActivity does not exist in mServices
08-31 16:50:29.469  1159  2558 D PackageManager: getComponentMetadataForIconTray : com.test.thalitest.MainActivity does not exist in mProviders
08-31 16:50:29.469  1159  2558 D PackageManager: getComponentMetadataForIconTray : com.test.thalitest.MainActivity does not exist in mReceivers
,08-31 16:50:29.469  1796  1796 I ApplicationPackageManager: load=com.test.thalitest, bg=96-96, dr=96-96
,08-31 16:50:29.469  1796  1796 I ApplicationPackageManager: scaled rate=0.98086953, size=96, alpha=2, hold=26, target=96
,08-31 16:50:29.539  5636  5690 I jxcore-log: JXcore Cordova bridge is ready!
08-31 16:50:29.539  5636  5690 I jxcore-log: 
08-31 16:50:29.539  5636  5690 W jxcore-log: JXcore engine is started
,08-31 16:50:29.539  5636  5689 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-31 16:50:29.549  5636  5636 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 16:50:29.619  1159  1202 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-31 16:50:29.619  1159  1202 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4378, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
08-31 16:50:29.619  1159  1202 D BatteryService: online:4, current avg:148, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:140
,08-31 16:50:29.619  1159  1159 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 16:50:29.619  1705  1705 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-31 16:50:29.619  1705  1705 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 16:50:29.619  1705  1705 D PowerUI : priorPlugType = 2 mPlugType =  2
,08-31 16:50:29.629  1705  1705 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
08-31 16:50:29.629  1705  1705 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
08-31 16:50:29.629  1705  1705 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-31 16:50:29.749   717   717 I MSM-irqbalance: Decided to move IRQ200 from CPU2 to CPU3
,08-31 16:50:30.419  1159  1664 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/18_task.xml.bak
,08-31 16:50:31.789  1159  3439 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 16:50:36.619  1159  1591 V AlarmManager: Expired Alarm result :4
,08-31 16:50:36.619  1159  1366 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{645586c u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ad7afc9 1878:com.google.android.gms.persistent/u0a10}
,08-31 16:50:36.629  1159  1724 V AlarmManager:  remove PendingIntent] PendingIntent{bffbe35: PendingIntentRecord{f74e757 com.google.android.gms broadcastIntent}}
,08-31 16:50:36.949  1159  3409 D SSRM:s  : SIOP:: AP = 360, PST = 367 (W:8), CP = 46, LCD = 0
,08-31 16:50:36.949  1159  3409 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:50:37.449  1159  1426 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-31 16:50:37.459  1159  1426 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-31 16:50:37.849  5636  5690 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 16:50:37.849  5636  5690 I jxcore-log: 
,08-31 16:50:37.849  5636  5690 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 16:50:37.849  5636  5690 I jxcore-log: 
,08-31 16:50:37.859  5636  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 16:50:37.859  5636  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 16:50:37.859  5636  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:50:37.859  5636  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 16:50:37.859  5636  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 16:50:37.859  5636  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 16:50:37.859  5636  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:50:37.859  5636  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:50:37.859  5636  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 16:50:37.859  5636  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 16:50:37.859  5636  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 16:50:37.859  5636  5690 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 16:50:37.859  5636  5690 I jxcore-log: 
,08-31 16:50:37.859  5636  5690 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 16:50:37.859  5636  5690 I jxcore-log: 
,08-31 16:50:38.069  5636  5690 I jxcore-log: Running unit tests
08-31 16:50:38.069  5636  5690 I jxcore-log: 
08-31 16:50:38.069  5636  5690 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-31 16:50:38.069  5636  5690 I jxcore-log: Failed to execute UT.
08-31 16:50:38.069  5636  5690 I jxcore-log: 
,08-31 16:50:38.069  5636  5690 I jxcore-log: Unit Test app is loaded
08-31 16:50:38.069  5636  5690 I jxcore-log: 
,08-31 16:50:38.079  5636  5690 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 16:50:38.079  5636  5690 I jxcore-log: 
,08-31 16:50:38.079  5636  5690 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,08-31 16:50:38.089  1159  1950 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled,
,08-31 16:50:38.089  1159  1950 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed,
,08-31 16:50:38.089  5636  5636 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-31 16:50:38.089  1159  1950 D WifiService: System do NOT have com.sec.feature.sensorhub feature
08-31 16:50:38.089  1159  1624 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,08-31 16:50:38.089  1159  1950 D WifiService: Wi-Fi on and Screen on , checkSensorStatus !!
08-31 16:50:38.089  1159  1950 D WifiService: setWifiEnabled: true pid=5636, uid=10136
08-31 16:50:38.089  1159  1950 W ActivityManager: Permission Denial: getCurrentUser() from pid=5636, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
08-31 16:50:38.099  1159  1950 W WifiService: Failed getting userId using ActivityManagerNative
08-31 16:50:38.099  1159  1950 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5636, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
08-31 16:50:38.099  1159  1950 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28130)
08-31 16:50:38.099  1159  1950 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2542)
08-31 16:50:38.099  1159  1950 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2530)
08-31 16:50:38.099  1159  1950 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
08-31 16:50:38.099  1159  1950 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
08-31 16:50:38.099  1159  1950 D SettingsProvider: isChangeAllowed() : name = wifi_on
08-31 16:50:38.099  1159  1624 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.android.server.wifi.WifiStateMachine.insertLog:18843 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8707 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,08-31 16:50:38.099  1159  1624 D WifiBigDataLog: init : 
08-31 16:50:38.099  1159  1625 D WifiStateMachine: setFccChannel: channel = 0
08-31 16:50:38.099  1159  1625 D WifiController: [FCC]setFccChannel() is called !!!
08-31 16:50:38.099  1159  1625 D SecContentProvider: insert(), uri = 2
08-31 16:50:38.099  1159  1625 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
08-31 16:50:38.099  1159  1976 I WifiService: disconnect: pid=5636, uid=10136
,08-31 16:50:38.099  1159  1366 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cfb08b1 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{efa98fc 2545:com.samsung.android.providers.context/u0a5}
,08-31 16:50:38.099  1159  2133 E OsAgent :  Wifi Scan Always Available: 0
08-31 16:50:38.099  1159  2133 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
08-31 16:50:38.099  1159  2133 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: IS_WIFI_HARDWARE_ON: true
08-31 16:50:38.099  1159  2133 E OsAgent :  Wifi Scan Always Available: 0
08-31 16:50:38.099  1159  2133 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
08-31 16:50:38.099  1159  2133 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: IS_WIFI_HARDWARE_ON: true
08-31 16:50:38.099  1159  2133 E OsAgent :  Wifi Scan Always Available: 0
08-31 16:50:38.099  1159  2133 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
08-31 16:50:38.099  1159  2133 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: IS_WIFI_HARDWARE_ON: true
08-31 16:50:38.099  1159  1624 E WifiHW  : ##################### set firmware type 0 #####################
08-31 16:50:38.109  5636  5690 D BluetoothAdapter: enable()
08-31 16:50:38.109  1159  2146 E LocSvc_libulp: I/int ulp_msg_process_phone_setting_update(const UlpPhoneContextSettings*), context type: 0x4
08-31 16:50:38.109  1159  2146 E LocSvc_libulp:   gps enabled: 0
08-31 16:50:38.109  1159  2146 E LocSvc_libulp:  network position available 0
08-31 16:50:38.109  1159  2146 E LocSvc_libulp:  wifi setting enabled 1
08-31 16:50:38.109  1159  2146 E LocSvc_libulp:  battery charging 0, agps enabled 0, enh_location_services_enabled 0is_pip_user_setting_enabled 0
08-31 16:50:38.109  1159  2146 E LocSvc_libulp: I/int ulp_msg_process_system_update(UlpSystemEvent): systemEvent:4 
08-31 16:50:38.109  1159  2146 E LocSvc_libulp: E/int ulp_brain_select_providers(), return when ulp_started = 0, phone context_type = 0x37
08-31 16:50:38.109  1159  2146 E LocSvc_libulp: ,
08-31 16:50:38.109  1159  2146 E LocSvc_libulp: I/int ulp_msg_process_start_req(), at ulp state = 0
,08-31 16:50:38.109  1159  2139 E LocSvc_LBSApiV02: E/virtual int lbs_core::LBSApiV02::wifiEnabledStatusInject(int):677]: Error : st = 2, ind.status = 1554863040
08-31 16:50:38.109  1159  2146 E LocSvc_libulp: I/int ulp_msg_process_phone_setting_update(const UlpPhoneContextSettings*), context type: 0x37
08-31 16:50:38.109  1159  2146 E LocSvc_libulp:   gps enabled: 0
08-31 16:50:38.109  1159  2146 E LocSvc_libulp:  network position available 0
08-31 16:50:38.109  1159  2146 E LocSvc_libulp:  wifi setting enabled 1
08-31 16:50:38.109  1159  2146 E LocSvc_libulp:  battery charging 0, agps enabled 1, enh_location_services_enabled 0is_pip_user_setting_enabled 0
08-31 16:50:38.109  1159  2146 E LocSvc_libulp: I/int ulp_msg_process_system_update(UlpSystemEvent): systemEvent:4 
,08-31 16:50:38.109  1159  1727 W ActivityManager: Permission Denial: getCurrentUser() from pid=5636, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
08-31 16:50:38.109  1159  1727 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-31 16:50:38.109  1159  1727 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5636, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
08-31 16:50:38.109  1159  1727 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28130)
08-31 16:50:38.109  1159  1727 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2879)
08-31 16:50:38.109  1159  1727 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2869)
08-31 16:50:38.109  1159  1727 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1244)
08-31 16:50:38.109  1159  1727 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:262)
08-31 16:50:38.109  1159  1727 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
08-31 16:50:38.109  1159  1727 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 16:50:38.109  1159  1727 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,08-31 16:50:38.109  1159  1727 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,08-31 16:50:38.119  5636  5690 I jxcore-log: My device name is: samsung-SM-T719
08-31 16:50:38.119  5636  5690 I jxcore-log: 
,08-31 16:50:38.119  5636  5690 I jxcore-log: WARN testUtils: myNameCallback not set!
08-31 16:50:38.119  5636  5690 I jxcore-log: 
,08-31 16:50:38.129  5693  5693 E Zygote  : v2
08-31 16:50:38.129  5693  5693 I libpersona: KNOX_SDCARD checking this for 1002
08-31 16:50:38.129  5693  5693 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:38.129  1159  1402 I ActivityManager: Start proc 5693:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-31 16:50:38.129  5693  5693 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-31 16:50:38.139  5693  5693 E Zygote  : accessInfo : 0
,08-31 16:50:38.159  5693  5693 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:38.159  5693  5693 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:38.209  5693  5693 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-31 16:50:38.219   449   449 I rmt_storage: rmt_storage_connect_cb: clnt_h=0xa conn_h=0x7f9cf7a010
08-31 16:50:38.219   449   449 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0xa: req_h=0xa msg_id=3: R/W request received
08-31 16:50:38.219   449   449 I rmt_storage: wakelock acquired: 1, error no: 42
,08-31 16:50:38.219   449   897 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0xa Unblock worker thread (th_id: 548089103424)
,08-31 16:50:38.239  5693  5693 D BtSettings.ProfileConfig: Adding GattService
08-31 16:50:38.239  5693  5693 D BtSettings.ProfileConfig: Adding HeadsetService
08-31 16:50:38.239  5693  5693 D BtSettings.ProfileConfig: Adding A2dpService
,08-31 16:50:38.239  5693  5693 D BtSettings.ProfileConfig: Adding HidService
08-31 16:50:38.239  5693  5693 D BtSettings.ProfileConfig: Adding HealthService
,08-31 16:50:38.239  5693  5693 D BtSettings.ProfileConfig: Adding PanService
08-31 16:50:38.239  5693  5693 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-31 16:50:38.239  5693  5693 D BtSettings.ProfileConfig: Adding SapService
08-31 16:50:38.239  5693  5693 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-31 16:50:38.239  5693  5693 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-31 16:50:38.239  5693  5693 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-31 16:50:38.249  1159  2558 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-31 16:50:38.249  1159  2558 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.gatt.GattService
08-31 16:50:38.249  1159  2558 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:50:38.249  1159  2558 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:50:38.249  1159  2558 D SettingsProvider: selectionArgs: false
08-31 16:50:38.249  1159  2558 D SettingsProvider: selectionArgs: 1002
,08-31 16:50:38.249  1159  2558 D SettingsProvider: ret = -1
08-31 16:50:38.249  1159  1724 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-31 16:50:38.249  1159  1724 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-31 16:50:38.249  1159  1724 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:50:38.249  1159  1724 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:50:38.249  1159  1724 D SettingsProvider: selectionArgs: false
08-31 16:50:38.249  1159  1724 D SettingsProvider: selectionArgs: 1002
08-31 16:50:38.249  1159  1724 D SettingsProvider: ret = -1
,08-31 16:50:38.249  1159  1978 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-31 16:50:38.249  1159  1978 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-31 16:50:38.249  1159  1978 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:50:38.249  1159  1978 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:50:38.249  1159  1978 D SettingsProvider: selectionArgs: false
08-31 16:50:38.249  1159  1978 D SettingsProvider: selectionArgs: 1002
,08-31 16:50:38.249  1159  1978 D SettingsProvider: ret = -1
,08-31 16:50:38.249  1159  1200 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-31 16:50:38.249  1159  1200 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hid.HidService
08-31 16:50:38.249  1159  1200 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:50:38.249  1159  1200 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:50:38.249  1159  1200 D SettingsProvider: selectionArgs: false
08-31 16:50:38.249  1159  1200 D SettingsProvider: selectionArgs: 1002
,08-31 16:50:38.249  1159  1200 D SettingsProvider: ret = -1
08-31 16:50:38.249  1159  1727 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-31 16:50:38.249  1159  1727 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:50:38.249  1159  1727 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:50:38.249  1159  1727 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-31 16:50:38.249  1159  1727 D SettingsProvider: selectionArgs: false
08-31 16:50:38.249  1159  1727 D SettingsProvider: selectionArgs: 1002
,08-31 16:50:38.249  1159  1727 D SettingsProvider: ret = -1
,08-31 16:50:38.249  1159  2313 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,08-31 16:50:38.249  1159  2313 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.pan.PanService
08-31 16:50:38.249  1159  2313 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:50:38.249  1159  2313 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:50:38.249  1159  2313 D SettingsProvider: selectionArgs: false
,08-31 16:50:38.249  1159  2313 D SettingsProvider: selectionArgs: 1002
08-31 16:50:38.259  1159  2313 D SettingsProvider: ret = -1
08-31 16:50:38.259  1159  2367 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-31 16:50:38.259  1159  2367 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,08-31 16:50:38.259  1159  2367 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:50:38.259   449   897 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0xa: req_h=0xa msg_id=3: Bytes written = 1572864
08-31 16:50:38.259  1159  2367 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:50:38.259   449   897 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0xa: req_h=0xa msg_id=3: Send response: res=0 err=0
08-31 16:50:38.259  1159  2367 D SettingsProvider: selectionArgs: false
08-31 16:50:38.259   449   897 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0xa About to block rmt_storage client thread (th_id: 548089103424) wakelock released: 1, error no: 0
08-31 16:50:38.259   449   897 I rmt_storage: 
,08-31 16:50:38.259  1159  2367 D SettingsProvider: selectionArgs: 1002
08-31 16:50:38.259  1159  2367 D SettingsProvider: ret = -1
,08-31 16:50:38.259  1159  1988 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed,
08-31 16:50:38.259  1159  1988 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.sap.SapService
08-31 16:50:38.259   449   449 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0xa conn_h=0x7f9cf7a010
08-31 16:50:38.259  1159  1988 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:50:38.259  1159  1950 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-31 16:50:38.259  1159  1988 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-31 16:50:38.259  1159  1202 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-31 16:50:38.259  1159  1988 D SettingsProvider: selectionArgs: false
08-31 16:50:38.259  1159  1988 D SettingsProvider: selectionArgs: 1002
08-31 16:50:38.259  1159  1988 D SettingsProvider: ret = -1
08-31 16:50:38.259  1159  1950 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-31 16:50:38.259  1159  1950 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:50:38.259  1159  1950 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:50:38.259  1159  1950 D SettingsProvider: selectionArgs: false
,08-31 16:50:38.259  1159  1950 D SettingsProvider: selectionArgs: 1002
08-31 16:50:38.259  1159  1950 D SettingsProvider: ret = -1
08-31 16:50:38.259  1159  1202 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-31 16:50:38.259  1159  1202 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:50:38.259  1159  1202 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:50:38.259  1159  1202 D SettingsProvider: selectionArgs: false
08-31 16:50:38.259  1159  1202 D SettingsProvider: selectionArgs: 1002
,08-31 16:50:38.259  1159  1202 D SettingsProvider: ret = -1
,08-31 16:50:38.299  5693  5693 D BluetoothAdapterState: make() - Creating AdapterState
,08-31 16:50:38.299  5693  5706 I BluetoothAdapterState: Entering OffState
,08-31 16:50:38.299  5693  5693 I bt_bluedroid: init
,08-31 16:50:38.309  5693  5707 E bt_core_counter: counter_init unable to open counter port
08-31 16:50:38.309  5693  5707 E bt_core_module: module_init failed to initialize "counter_module"
,08-31 16:50:38.309  5693  5707 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-31 16:50:38.309  5693  5707 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 16:50:38.309  5693  5707 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-31 16:50:38.309  5693  5707 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-31 16:50:38.309  5693  5693 I bt_bluedroid: get_profile_interface socket
,08-31 16:50:38.309  5693  5693 W bt_btif : btif_get_adapter_property 2
08-31 16:50:38.309  5693  5693 W bt_btif : btif_get_adapter_property 1
,08-31 16:50:38.319  5693  5693 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-31 16:50:38.319  5693  5710 D BluetoothAdapterProperties: Address is:44:78:3E:EB:95:EE
08-31 16:50:38.319  5693  5710 E BluetoothServiceJni: populateRssiValuesNative
08-31 16:50:38.319  5693  5710 I bt_bluedroid: getModelRssiValues
08-31 16:50:38.319  5693  5710 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-31 16:50:38.319  5693  5710 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-31 16:50:38.319  5693  5693 D BluetoothAdapterService: makeHashMapAvPerformance: Loading from conf
,08-31 16:50:38.319  5693  5710 D BluetoothAdapterProperties: Name is: Galaxy Tab S2
,08-31 16:50:38.319  1159  1159 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
,08-31 16:50:38.319  5693  5693 I bt_bluedroid: get_profile_interface sdp
,08-31 16:50:38.329  5693  5703 I bt_bluedroid: config_hci_snoop_log
,08-31 16:50:38.329  1159  1402 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 7 receivers.
,08-31 16:50:38.329  5693  5706 D BluetoothAdapterState: Current state: OFF, message: BLE_TURN_ON
,08-31 16:50:38.329  5693  5706 D BluetoothAdapterProperties: Setting state to 14
08-31 16:50:38.329  5693  5706 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-31 16:50:38.329  5693  5706 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 16:50:38.329  5693  5706 D BluetoothAdapterService: updateAdapterState state is 14
,08-31 16:50:38.329  5693  5706 D BluetoothAdapterService: Autoconnection is available 
08-31 16:50:38.329  5693  5706 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 14
,08-31 16:50:38.329  1159  1402 D BluetoothManagerService: Ble Turning On/Off, G state: 1, S state: 1
,08-31 16:50:38.339  5693  5706 D BluetoothSecureManager: getInstant: null
08-31 16:50:38.339  5693  5706 D BluetoothSecureManager: calling getMethod for getService,
08-31 16:50:38.339  5693  5706 D BluetoothSecureManager: calling getService
08-31 16:50:38.339  5693  5706 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@e3e4274
,08-31 16:50:38.339  1159  1727 D BluetoothSecureManagerService: isSecureModeEnabled
08-31 16:50:38.339  1159  1727 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-31 16:50:38.339  5693  5706 D BtConfig.SecureMode: isSecureModeOn:false
08-31 16:50:38.339  5693  5706 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-31 16:50:38.339  5693  5706 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-31 16:50:38.339  5693  5706 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-31 16:50:38.339  5693  5706 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-31 16:50:38.339  5693  5706 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-31 16:50:38.339  5693  5706 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-31 16:50:38.339  5693  5706 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 16:50:38.339  5693  5706 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-31 16:50:38.339  5693  5706 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-31 16:50:38.339  5693  5706 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-31 16:50:38.339  5693  5706 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-31 16:50:38.339  5693  5706 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-31 16:50:38.339  5693  5706 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-31 16:50:38.339  5693  5706 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-31 16:50:38.339  5693  5706 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
08-31 16:50:38.339  5693  5706 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.sap.SapService
08-31 16:50:38.339  5693  5706 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 16:50:38.339  5693  5706 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 16:50:38.339  5693  5706 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 16:50:38.349  5693  5706 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,08-31 16:50:38.349  5693  5706 D BluetoothBondStateMachine: make
,08-31 16:50:38.349  5693  5706 I BluetoothAdapterState: Entering PendingCommandState,
08-31 16:50:38.349  5693  5693 I BtGatt.JNI: classInitNative(L992): classInitNative: Success!
,08-31 16:50:38.359  5693  5693 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 16:50:38.359  5693  5693 D BtGatt.GattService: Received start request. Starting profile...
08-31 16:50:38.359  5693  5693 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7a2026b
08-31 16:50:38.359  5693  5693 D BtGatt.GattService: start()
08-31 16:50:38.359  5693  5693 I bt_bluedroid: get_profile_interface gatt
,08-31 16:50:38.359  5693  5693 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7a2026b
,08-31 16:50:38.359  5693  5693 D BtGatt.AdvertiseManager: advertise manager created
08-31 16:50:38.359  5693  5693 D BtGatt.AdvertiseManager: start
,08-31 16:50:38.359  5693  5693 D BtGatt.ScanManager: start
,08-31 16:50:38.359  5693  5693 D BtGatt.GattService: [GSIM LOG]: loadLogPref
,08-31 16:50:38.379  5693  5693 D BtGatt.GattService: [GSIM LOG]: loadLogPref END
,08-31 16:50:38.389  5693  5693 D BtGatt.GattService: setGattService(): set to: null
,08-31 16:50:38.389  5693  5693 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Message sending
08-31 16:50:38.389  5693  5693 E BtGatt.GattService: notifyProfileServiceStateChanged
,08-31 16:50:38.389  5693  5693 E BluetoothAdapterService: handleMessage() - Message: 1
08-31 16:50:38.389  5693  5693 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Before synchronized
,08-31 16:50:38.389  5693  5693 V BluetoothAdapterState: isTurningOff()=false
08-31 16:50:38.389  5693  5693 V BluetoothAdapterState: isTurningOn()=false
08-31 16:50:38.389  5693  5693 V BluetoothAdapterState: isBleTurningOn()=true
08-31 16:50:38.389  5693  5693 V BluetoothAdapterState: isBleTurningOff()=false
08-31 16:50:38.389  5693  5706 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STARTED
,08-31 16:50:38.389  5693  5706 I bt_bluedroid: enable
08-31 16:50:38.389  5693  5707 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-31 16:50:38.389  5693  5707 I bt_hci  : start_up
,08-31 16:50:38.399  5693  5707 I bt_vendor: alloc value 0xf3cfb789
08-31 16:50:38.399  5693  5707 I bt_vendor: bt-vendor : init
08-31 16:50:38.399  5693  5707 I bt_vendor: bt-vendor : get_bt_soc_type
08-31 16:50:38.399  5693  5707 I bt_vendor: qcom.bluetooth.soc set to rome
08-31 16:50:38.399  5693  5707 I bt_vendor: bt-vendor : Initializing UART transport layer
08-31 16:50:38.399  5693  5707 I bt_vendor: init: Local BD Address : ee:95:eb:3e:78:44
08-31 16:50:38.399  5693  5707 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-31 16:50:38.399  5693  5707 I bt_vendor: bt_powerup: 0
,08-31 16:50:38.399  5693  5707 E bt_vendor: Write 0 to rfkill
,08-31 16:50:38.399  5693  5707 E bt_vendor: Stopping HCI filter as part of CTRL:OFF
,08-31 16:50:38.399  5693  5707 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-31 16:50:38.399  5693  5707 I bt_vendor: bt_powerup: 1
,08-31 16:50:38.409  5693  5707 E bt_vendor: Write 1 to rfkill
,08-31 16:50:38.529  5693  5707 D bt_hci  : start_up starting async portion,
08-31 16:50:38.529  5693  5725 I bt_hci  : event_finish_startup
08-31 16:50:38.529  5693  5725 I bt_hci_h4: hal_open
08-31 16:50:38.529  5693  5725 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-31 16:50:38.529  5693  5725 I bt_vendor: bt-vendor : is_soc_initialized
08-31 16:50:38.529  5693  5725 I bt_vendor: wc_transport.soc_initialized set to 0
08-31 16:50:38.529  5693  5725 I bt_vendor: userial vendor open: opening /dev/ttyHS0
,08-31 16:50:38.529  5693  5725 I bt_vendor: device fd = 61 open
08-31 16:50:38.529  5693  5725 D bt_vendor: userial clock on
08-31 16:50:38.529  5693  5725 I bt_vendor: Wipower not enabled
,08-31 16:50:38.529  5693  5725 I bt_vendor:  rome_soc_init 
08-31 16:50:38.529  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_VER_REQ_CMD
08-31 16:50:38.529  5693  5725 D bt_vendor: HCI-CMD -1:	0x1 ,	0x0 	0xfc 	0x1 	0x19
08-31 16:50:38.529  5693  5725 I bt_vendor: read_vs_hci_event: Wait for HCI-Vendor Specfic Event from SOC
,08-31 16:50:38.569  5693  5725 I bt_vendor: get_vs_hci_event: Received HCI-Vendor Specific event,
08-31 16:50:38.569  5693  5725 I bt_vendor: get_vs_hci_event: Parameter Length: 0xe
08-31 16:50:38.569  5693  5725 I bt_vendor: get_vs_hci_event: Command response: 0x0
08-31 16:50:38.569  5693  5725 I bt_vendor: get_vs_hci_event: Response type   : 0x2
08-31 16:50:38.569  5693  5725 I bt_vendor: get_vs_hci_event: Command Request Response
08-31 16:50:38.569  5693  5725 I bt_vendor: 	 Current Product ID		: 0x00000008
08-31 16:50:38.569  5693  5725 I bt_vendor: 	 Current Patch Version		: 0x0111
08-31 16:50:38.569  5693  5725 I bt_vendor: 	 Current ROM Build Version	: 0x0302
,08-31 16:50:38.569  5693  5725 I bt_vendor: 	 Current SOC Version		: 0x00000044
08-31 16:50:38.569  5693  5725 I bt_vendor: hci_send_vs_cmd: Received HCI-Vendor Specific Event from SOC
08-31 16:50:38.569  5693  5725 I bt_vendor: read_hci_event: Wait for Command Compete Event from SOC
08-31 16:50:38.569  5693  5725 I bt_vendor: rome_soc_init: Rome Version (0x03020044)
08-31 16:50:38.569  5693  5725 I bt_vendor: ## userial_vendor_ioctl: UART Flow Off 
,08-31 16:50:38.589  5693  5725 I bt_vendor: ## userial_vendor_ioctl: UART Flow On ,
08-31 16:50:38.589  5693  5725 I bt_vendor: read_vs_hci_event: Wait for HCI-Vendor Specfic Event from SOC
,08-31 16:50:38.589  5693  5725 I bt_vendor: get_vs_hci_event: Received HCI-Vendor Specific event,
08-31 16:50:38.589  5693  5725 I bt_vendor: get_vs_hci_event: Parameter Length: 0x2
08-31 16:50:38.589  5693  5725 I bt_vendor: get_vs_hci_event: Command response: 0x92
08-31 16:50:38.589  5693  5725 I bt_vendor: get_vs_hci_event: Response type   : 0x1
08-31 16:50:38.589  5693  5725 I bt_vendor: rome_set_baudrate_req: Received HCI-Vendor Specific Event from SOC
08-31 16:50:38.589  5693  5725 I bt_vendor: read_hci_event: Wait for Command Compete Event from SOC
,08-31 16:50:38.589  5693  5725 I bt_vendor: rome_soc_init: Baud rate changed successfully 
08-31 16:50:38.589  5693  5725 I bt_vendor: File Open (/system/etc/firmware/btfw32.tlv)
,08-31 16:50:38.589  5693  5725 I bt_vendor: ====================================================
08-31 16:50:38.589  5693  5725 I bt_vendor: TLV Type			 : 0x1
08-31 16:50:38.589  5693  5725 I bt_vendor: Length			 : 65736 bytes
08-31 16:50:38.589  5693  5725 I bt_vendor: Total Length			 : 65480 bytes
08-31 16:50:38.589  5693  5725 I bt_vendor: Patch Data Length			 : 65456 bytes
08-31 16:50:38.589  5693  5725 I bt_vendor: Signing Format Version	 : 0x1
08-31 16:50:38.589  5693  5725 I bt_vendor: Signature Algorithm		 : 0x2
08-31 16:50:38.589  5693  5725 I bt_vendor: Event Handling			 : 0x3
08-31 16:50:38.589  5693  5725 I bt_vendor: Reserved			 : 0x0
08-31 16:50:38.589  5693  5725 I bt_vendor: Product ID			 : 0x0008
08-31 16:50:38.589  5693  5725 I bt_vendor: Rom Build Version		 : 0x0302,
08-31 16:50:38.589  5693  5725 I bt_vendor: Patch Version		 : 0x0192
08-31 16:50:38.589  5693  5725 I bt_vendor: Reserved			 : 0x8000
08-31 16:50:38.589  5693  5725 I bt_vendor: Patch Entry Address		 : 0x19b08
08-31 16:50:38.589  5693  5725 I bt_vendor: ====================================================
,08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_req: TLV size: 65740, Total Seg num: 270, remain size: 130,
08-31 16:50:38.599  5693  5725 I bt_vendor: Event handling type: ROME_SKIP_EVT_VSE_CC
08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.0, size:243
08-31 16:50:38.599  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.599  5693  5725 D bt_vendor: HCI-CMD 0:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 0
08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.1, size:243
08-31 16:50:38.599  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.599  5693  5725 D bt_vendor: HCI-CMD 1:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 1
08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.2, size:243
08-31 16:50:38.599  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.599  5693  5725 D bt_vendor: HCI-CMD 2:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 2
08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.3, size:243
08-31 16:50:38.599  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD,
08-31 16:50:38.599  5693  5725 D bt_vendor: HCI-CMD 3:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 3
08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.4, size:243,
08-31 16:50:38.599  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.599  5693  5725 D bt_vendor: HCI-CMD 4:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 4
08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.5, size:243
08-31 16:50:38.599  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.599  5693  5725 D bt_vendor: HCI-CMD 5:	0x1 	0x0 	0xfc 	0xf5 ,	0x1e 	0xf3
08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 5
08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.6, size:243
08-31 16:50:38.599  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
,08-31 16:50:38.599  5693  5725 D bt_vendor: HCI-CMD 6:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 6
08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.7, size:243,
08-31 16:50:38.599  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.599  5693  5725 D bt_vendor: HCI-CMD 7:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 7
08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.8, size:243
08-31 16:50:38.599  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.599  5693  5725 D bt_vendor: HCI-CMD 8:	0x1 	0x0 	0xfc 	,0xf5 	0x1e 	0xf3
08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 8
08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.9, size:243
08-31 16:50:38.599  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
,08-31 16:50:38.599  5693  5725 D bt_vendor: HCI-CMD 9:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 9
,08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.10, size:243
08-31 16:50:38.599  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.599  5693  5725 D bt_vendor: HCI-CMD 10:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 10
08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.11, size:243
08-31 16:50:38.599  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.599  5693  5725 D bt_vendor: HCI-CMD 11:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	,0xf3
08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 11
08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.12, size:243
08-31 16:50:38.599  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.599  5693  5725 D bt_vendor: HCI-CMD 12:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 12
,08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.13, size:243
08-31 16:50:38.599  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.599  5693  5725 D bt_vendor: HCI-CMD 13:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 13
08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.14, size:243
08-31 16:50:38.599  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.599  5693  5725 D bt_vendor: HCI-CMD 14:	,0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 14
08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.15, size:243
08-31 16:50:38.599  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.599  5693  5725 D bt_vendor: HCI-CMD 15:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 15
,08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.16, size:243
08-31 16:50:38.599  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.599  5693  5725 D bt_vendor: HCI-CMD 16:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 16
08-31 16:50:38.599  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.17, size:243
08-31 16:50:38.599  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.599  5693  5725 D bt_vendor: HCI-CMD 17:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 17
,08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.18, size:243
08-31 16:50:38.609  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.609  5693  5725 D bt_vendor: HCI-CMD 18:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 18
08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.19, size:243
08-31 16:50:38.609  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.609  5693  5725 D bt_vendor: HCI-CMD 19:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 19
08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.20, size:243
,08-31 16:50:38.609  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.609  5693  5725 D bt_vendor: HCI-CMD 20:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 20
08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.21, size:243
08-31 16:50:38.609  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.609  5693  5725 D bt_vendor: HCI-CMD 21:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 21
08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.22, size:243
08-31 16:50:38.609  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.609  5693  5725 D bt_vendor: HCI-CMD 22:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 22
08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.23, size:243
08-31 16:50:38.609  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
,08-31 16:50:38.609  5693  5725 D bt_vendor: HCI-CMD 23:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 23
08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.24, size:243
08-31 16:50:38.609  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.609  5693  5725 D bt_vendor: HCI-CMD 24:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 24
08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.25, size:243
08-31 16:50:38.609  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.609  5693  5725 D bt_vendor: HCI-CMD 25:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 25
08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.26, size:243
08-31 16:50:38.609  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.609  5693  5725 D bt_vendor: HCI-CMD 26:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 26
08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.27, size:243
08-31 16:50:38.609  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.609  5693  5725 D bt_vendor: HCI-CMD 27:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 27
08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.28, size:243
08-31 16:50:38.609  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.609  5693  5725 D bt_vendor: HCI-CMD 28:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 28
08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.29, size:243
08-31 16:50:38.609  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.609  5693  5725 D bt_vendor: HCI-CMD 29:	,0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 29
08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.30, size:243
08-31 16:50:38.609  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.609  5693  5725 D bt_vendor: HCI-CMD 30:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 30
08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.31, size:243
08-31 16:50:38.609  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
,08-31 16:50:38.609  5693  5725 D bt_vendor: HCI-CMD 31:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 31
08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.32, size:243
08-31 16:50:38.609  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.609  5693  5725 D bt_vendor: HCI-CMD 32:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 32
,08-31 16:50:38.609  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.33, size:243
08-31 16:50:38.609  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.609  5693  5725 D bt_vendor: HCI-CMD 33:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 33
,08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.34, size:243
08-31 16:50:38.619  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.619  5693  5725 D bt_vendor: HCI-CMD 34:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 34
08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.35, size:243
08-31 16:50:38.619  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.619  5693  5725 D bt_vendor: HCI-CMD 35:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 35
08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.36, size:243
08-31 16:50:38.619  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.619  5693  5725 D bt_vendor: HCI-CMD 36:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 36
08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.37, size:243
08-31 16:50:38.619  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.619  5693  5725 D bt_vendor: HCI-CMD 37:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 37
08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.38, size:243
08-31 16:50:38.619  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.619  5693  5725 D bt_vendor: HCI-CMD 38:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 38
08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.39, size:243
08-31 16:50:38.619  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.619  5693  5725 D bt_vendor: HCI-CMD 39:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 39
08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.40, size:243
08-31 16:50:38.619  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.619  5693  5725 D bt_vendor: HCI-CMD 40:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 40
08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.41, size:243
08-31 16:50:38.619  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
,08-31 16:50:38.619  5693  5725 D bt_vendor: HCI-CMD 41:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 41
08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.42, size:243
08-31 16:50:38.619  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.619  5693  5725 D bt_vendor: HCI-CMD 42:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 42
08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.43, size:243
08-31 16:50:38.619  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.619  5693  5725 D bt_vendor: HCI-CMD 43:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 43
08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.44, size:243
08-31 16:50:38.619  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.619  5693  5725 D bt_vendor: HCI-CMD 44:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 44
08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.45, size:243
08-31 16:50:38.619  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.619  5693  5725 D bt_vendor: HCI-CMD 45:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 45
08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.46, size:243
08-31 16:50:38.619  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.619  5693  5725 D bt_vendor: HCI-CMD 46:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 46
08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.47, size:243
08-31 16:50:38.619  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.619  5693  5725 D bt_vendor: HCI-CMD 47:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 47
08-31 16:50:38.619  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.48, size:243
08-31 16:50:38.629  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.629  5693  5725 D bt_vendor: HCI-CMD 48:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.629  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 48
08-31 16:50:38.629  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.49, size:243
08-31 16:50:38.629  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.629  5693  5725 D bt_vendor: HCI-CMD 49:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.629  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 49
08-31 16:50:38.629  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.50, size:243
08-31 16:50:38.629  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.629  5693  5725 D bt_vendor: HCI-CMD 50:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 50
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.51, size:243
08-31 16:50:38.639  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.639  5693  5725 D bt_vendor: HCI-CMD 51:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 51
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.52, size:243
08-31 16:50:38.639  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.639  5693  5725 D bt_vendor: HCI-CMD 52:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 52
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.53, size:243
08-31 16:50:38.639  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.639  5693  5725 D bt_vendor: HCI-CMD 53:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 53
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.54, size:243
08-31 16:50:38.639  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.639  5693  5725 D bt_vendor: HCI-CMD 54:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 54
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.55, size:243
08-31 16:50:38.639  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.639  5693  5725 D bt_vendor: HCI-CMD 55:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 55
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.56, size:243
08-31 16:50:38.639  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.639  5693  5725 D bt_vendor: HCI-CMD 56:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 56
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.57, size:243
08-31 16:50:38.639  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.639  5693  5725 D bt_vendor: HCI-CMD 57:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 57
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.58, size:243
08-31 16:50:38.639  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.639  5693  5725 D bt_vendor: HCI-CMD 58:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 58
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.59, size:243
08-31 16:50:38.639  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.639  5693  5725 D bt_vendor: HCI-CMD 59:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 59
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.60, size:243
08-31 16:50:38.639  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.639  5693  5725 D bt_vendor: HCI-CMD 60:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 60
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.61, size:243
08-31 16:50:38.639  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.639  5693  5725 D bt_vendor: HCI-CMD 61:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 61
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.62, size:243
08-31 16:50:38.639  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.639  5693  5725 D bt_vendor: HCI-CMD 62:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 62
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.63, size:243
08-31 16:50:38.639  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.639  5693  5725 D bt_vendor: HCI-CMD 63:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 63
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.64, size:243
08-31 16:50:38.639  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.639  5693  5725 D bt_vendor: HCI-CMD 64:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 64
08-31 16:50:38.639  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.65, size:243
08-31 16:50:38.639  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.639  5693  5725 D bt_vendor: HCI-CMD 65:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 65
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.66, size:243
08-31 16:50:38.649  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.649  5693  5725 D bt_vendor: HCI-CMD 66:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 66
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.67, size:243
08-31 16:50:38.649  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.649  5693  5725 D bt_vendor: HCI-CMD 67:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 67
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.68, size:243
08-31 16:50:38.649  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.649  5693  5725 D bt_vendor: HCI-CMD 68:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 68
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.69, size:243
08-31 16:50:38.649  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.649  5693  5725 D bt_vendor: HCI-CMD 69:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 69
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.70, size:243
08-31 16:50:38.649  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.649  5693  5725 D bt_vendor: HCI-CMD 70:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 70
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.71, size:243
08-31 16:50:38.649  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.649  5693  5725 D bt_vendor: HCI-CMD 71:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 71
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.72, size:243
08-31 16:50:38.649  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.649  5693  5725 D bt_vendor: HCI-CMD 72:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 72
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.73, size:243
08-31 16:50:38.649  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.649  5693  5725 D bt_vendor: HCI-CMD 73:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 73
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.74, size:243
08-31 16:50:38.649  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.649  5693  5725 D bt_vendor: HCI-CMD 74:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 74
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.75, size:243
08-31 16:50:38.649  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.649  5693  5725 D bt_vendor: HCI-CMD 75:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 75
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.76, size:243
08-31 16:50:38.649  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.649  5693  5725 D bt_vendor: HCI-CMD 76:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 76
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.77, size:243
08-31 16:50:38.649  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.649  5693  5725 D bt_vendor: HCI-CMD 77:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 77
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.78, size:243
08-31 16:50:38.649  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.649  5693  5725 D bt_vendor: HCI-CMD 78:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 78
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.79, size:243
08-31 16:50:38.649  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.649  5693  5725 D bt_vendor: HCI-CMD 79:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 79
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.80, size:243
08-31 16:50:38.649  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.649  5693  5725 D bt_vendor: HCI-CMD 80:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 80
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.81, size:243
08-31 16:50:38.649  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.649  5693  5725 D bt_vendor: HCI-CMD 81:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 81
08-31 16:50:38.649  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.82, size:243
08-31 16:50:38.649  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.649  5693  5725 D bt_vendor: HCI-CMD 82:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 82
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.83, size:243
08-31 16:50:38.669  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.669  5693  5725 D bt_vendor: HCI-CMD 83:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 83
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.84, size:243
08-31 16:50:38.669  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.669  5693  5725 D bt_vendor: HCI-CMD 84:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 84
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.85, size:243
08-31 16:50:38.669  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.669  5693  5725 D bt_vendor: HCI-CMD 85:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 85
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.86, size:243
08-31 16:50:38.669  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.669  5693  5725 D bt_vendor: HCI-CMD 86:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 86
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.87, size:243
08-31 16:50:38.669  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.669  5693  5725 D bt_vendor: HCI-CMD 87:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 87
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.88, size:243
08-31 16:50:38.669  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.669  5693  5725 D bt_vendor: HCI-CMD 88:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 88
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.89, size:243
08-31 16:50:38.669  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.669  5693  5725 D bt_vendor: HCI-CMD 89:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 89
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.90, size:243
08-31 16:50:38.669  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.669  5693  5725 D bt_vendor: HCI-CMD 90:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 90
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.91, size:243
08-31 16:50:38.669  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.669  5693  5725 D bt_vendor: HCI-CMD 91:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 91
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.92, size:243
08-31 16:50:38.669  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.669  5693  5725 D bt_vendor: HCI-CMD 92:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 92
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.93, size:243
08-31 16:50:38.669  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.669  5693  5725 D bt_vendor: HCI-CMD 93:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 93
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.94, size:243
08-31 16:50:38.669  1159  1839 E Watchdog: !@Sync 3 [08-31 16:50:38.682]
08-31 16:50:38.669  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.669  5693  5725 D bt_vendor: HCI-CMD 94:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 94
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.95, size:243
08-31 16:50:38.669  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.669  5693  5725 D bt_vendor: HCI-CMD 95:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 95
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.96, size:243
08-31 16:50:38.669  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.669  5693  5725 D bt_vendor: HCI-CMD 96:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 96
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.97, size:243
08-31 16:50:38.669  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.669  5693  5725 D bt_vendor: HCI-CMD 97:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 97
08-31 16:50:38.669  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.98, size:243
08-31 16:50:38.669  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.669  5693  5725 D bt_vendor: HCI-CMD 98:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 98
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.99, size:243
08-31 16:50:38.679  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.679  5693  5725 D bt_vendor: HCI-CMD 99:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 99
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.100, size:243
08-31 16:50:38.679  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.679  5693  5725 D bt_vendor: HCI-CMD 100:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 100
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.101, size:243
08-31 16:50:38.679  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.679  5693  5725 D bt_vendor: HCI-CMD 101:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 101
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.102, size:243
08-31 16:50:38.679  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.679  5693  5725 D bt_vendor: HCI-CMD 102:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 102
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.103, size:243
08-31 16:50:38.679  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.679  5693  5725 D bt_vendor: HCI-CMD 103:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 103
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.104, size:243
08-31 16:50:38.679  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.679  5693  5725 D bt_vendor: HCI-CMD 104:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 104
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.105, size:243
08-31 16:50:38.679  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.679  5693  5725 D bt_vendor: HCI-CMD 105:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 105
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.106, size:243
08-31 16:50:38.679  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.679  5693  5725 D bt_vendor: HCI-CMD 106:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 106
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.107, size:243
08-31 16:50:38.679  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.679  5693  5725 D bt_vendor: HCI-CMD 107:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 107
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.108, size:243
08-31 16:50:38.679  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.679  5693  5725 D bt_vendor: HCI-CMD 108:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 108
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.109, size:243
08-31 16:50:38.679  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.679  5693  5725 D bt_vendor: HCI-CMD 109:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 109
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.110, size:243
08-31 16:50:38.679  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.679  5693  5725 D bt_vendor: HCI-CMD 110:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 110
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.111, size:243
08-31 16:50:38.679  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.679  5693  5725 D bt_vendor: HCI-CMD 111:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 111
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.112, size:243
08-31 16:50:38.679  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.679  5693  5725 D bt_vendor: HCI-CMD 112:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 112
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.113, size:243
08-31 16:50:38.679  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.679  5693  5725 D bt_vendor: HCI-CMD 113:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 113
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.114, size:243
08-31 16:50:38.679  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.679  5693  5725 D bt_vendor: HCI-CMD 114:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 114
08-31 16:50:38.679  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.115, size:243
08-31 16:50:38.679  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.679  5693  5725 D bt_vendor: HCI-CMD 115:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 115
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.116, size:243
08-31 16:50:38.689  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.689  5693  5725 D bt_vendor: HCI-CMD 116:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 116
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.117, size:243
08-31 16:50:38.689  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.689  5693  5725 D bt_vendor: HCI-CMD 117:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 117
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.118, size:243
08-31 16:50:38.689  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.689  5693  5725 D bt_vendor: HCI-CMD 118:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 118
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.119, size:243
08-31 16:50:38.689  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.689  5693  5725 D bt_vendor: HCI-CMD 119:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 119
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.120, size:243
08-31 16:50:38.689  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.689  5693  5725 D bt_vendor: HCI-CMD 120:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 120
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.121, size:243
08-31 16:50:38.689  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.689  5693  5725 D bt_vendor: HCI-CMD 121:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 121
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.122, size:243
08-31 16:50:38.689  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.689  5693  5725 D bt_vendor: HCI-CMD 122:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 122
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.123, size:243
08-31 16:50:38.689  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.689  5693  5725 D bt_vendor: HCI-CMD 123:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 123
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.124, size:243
08-31 16:50:38.689  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.689  5693  5725 D bt_vendor: HCI-CMD 124:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 124
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.125, size:243
08-31 16:50:38.689  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.689  5693  5725 D bt_vendor: HCI-CMD 125:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 125
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.126, size:243
08-31 16:50:38.689  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.689  5693  5725 D bt_vendor: HCI-CMD 126:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 126
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.127, size:243
08-31 16:50:38.689  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.689  5693  5725 D bt_vendor: HCI-CMD 127:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 127
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.128, size:243
08-31 16:50:38.689  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.689  5693  5725 D bt_vendor: HCI-CMD 128:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 128
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.129, size:243
08-31 16:50:38.689  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.689  5693  5725 D bt_vendor: HCI-CMD 129:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 129
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.130, size:243
08-31 16:50:38.689  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.689  5693  5725 D bt_vendor: HCI-CMD 130:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 130
08-31 16:50:38.689  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.131, size:243
08-31 16:50:38.689  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.689  5693  5725 D bt_vendor: HCI-CMD 131:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 131
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.132, size:243
08-31 16:50:38.709  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.709  5693  5725 D bt_vendor: HCI-CMD 132:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 132
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.133, size:243
08-31 16:50:38.709  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.709  5693  5725 D bt_vendor: HCI-CMD 133:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 133
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.134, size:243
08-31 16:50:38.709  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.709  5693  5725 D bt_vendor: HCI-CMD 134:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 134
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.135, size:243
08-31 16:50:38.709  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.709  5693  5725 D bt_vendor: HCI-CMD 135:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 135
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.136, size:243
08-31 16:50:38.709  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.709  5693  5725 D bt_vendor: HCI-CMD 136:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 136
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.137, size:243
08-31 16:50:38.709  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.709  5693  5725 D bt_vendor: HCI-CMD 137:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 137
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.138, size:243
08-31 16:50:38.709  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.709  5693  5725 D bt_vendor: HCI-CMD 138:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 138
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.139, size:243
08-31 16:50:38.709  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.709  5693  5725 D bt_vendor: HCI-CMD 139:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 139
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.140, size:243
08-31 16:50:38.709  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.709  5693  5725 D bt_vendor: HCI-CMD 140:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 140
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.141, size:243
08-31 16:50:38.709  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.709  5693  5725 D bt_vendor: HCI-CMD 141:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 141
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.142, size:243
08-31 16:50:38.709  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.709  5693  5725 D bt_vendor: HCI-CMD 142:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 142
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.143, size:243
08-31 16:50:38.709  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.709  5693  5725 D bt_vendor: HCI-CMD 143:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 143
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.144, size:243
08-31 16:50:38.709  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.709  5693  5725 D bt_vendor: HCI-CMD 144:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 144
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.145, size:243
08-31 16:50:38.709  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.709  5693  5725 D bt_vendor: HCI-CMD 145:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 145
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.146, size:243
08-31 16:50:38.709  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.709  5693  5725 D bt_vendor: HCI-CMD 146:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 146
08-31 16:50:38.709  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.147, size:243
08-31 16:50:38.709  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.709  5693  5725 D bt_vendor: HCI-CMD 147:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 147
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.148, size:243
08-31 16:50:38.719  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.719  5693  5725 D bt_vendor: HCI-CMD 148:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 148
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.149, size:243
08-31 16:50:38.719  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.719  5693  5725 D bt_vendor: HCI-CMD 149:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 149
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.150, size:243
08-31 16:50:38.719  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.719  5693  5725 D bt_vendor: HCI-CMD 150:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 150
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.151, size:243
08-31 16:50:38.719  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.719  5693  5725 D bt_vendor: HCI-CMD 151:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 151
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.152, size:243
08-31 16:50:38.719  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.719  5693  5725 D bt_vendor: HCI-CMD 152:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 152
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.153, size:243
08-31 16:50:38.719  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.719  5693  5725 D bt_vendor: HCI-CMD 153:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 153
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.154, size:243
08-31 16:50:38.719  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.719  5693  5725 D bt_vendor: HCI-CMD 154:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 154
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.155, size:243
08-31 16:50:38.719  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.719  5693  5725 D bt_vendor: HCI-CMD 155:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 155
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.156, size:243
08-31 16:50:38.719  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.719  5693  5725 D bt_vendor: HCI-CMD 156:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 156
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.157, size:243
08-31 16:50:38.719  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.719  5693  5725 D bt_vendor: HCI-CMD 157:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 157
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.158, size:243
08-31 16:50:38.719  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.719  5693  5725 D bt_vendor: HCI-CMD 158:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 158
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.159, size:243
08-31 16:50:38.719  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.719  5693  5725 D bt_vendor: HCI-CMD 159:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 159
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.160, size:243
08-31 16:50:38.719  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.719  5693  5725 D bt_vendor: HCI-CMD 160:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 160
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.161, size:243
08-31 16:50:38.719  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.719  5693  5725 D bt_vendor: HCI-CMD 161:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 161
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.162, size:243
08-31 16:50:38.719  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.719  5693  5725 D bt_vendor: HCI-CMD 162:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 162
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.163, size:243
08-31 16:50:38.719  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.719  5693  5725 D bt_vendor: HCI-CMD 163:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 163
08-31 16:50:38.719  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.164, size:243
08-31 16:50:38.719  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.719  5693  5725 D bt_vendor: HCI-CMD 164:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.729  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 164
08-31 16:50:38.729  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.165, size:243
08-31 16:50:38.729  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.729  5693  5725 D bt_vendor: HCI-CMD 165:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.729  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 165
08-31 16:50:38.729  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.166, size:243
08-31 16:50:38.729  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.729  5693  5725 D bt_vendor: HCI-CMD 166:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.729  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 166
08-31 16:50:38.729  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.167, size:243
08-31 16:50:38.729  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.729  5693  5725 D bt_vendor: HCI-CMD 167:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.729  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 167
08-31 16:50:38.729  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.168, size:243
08-31 16:50:38.729  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.729  5693  5725 D bt_vendor: HCI-CMD 168:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.729  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 168
08-31 16:50:38.729  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.169, size:243
08-31 16:50:38.739  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.739  5693  5725 D bt_vendor: HCI-CMD 169:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.739  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 169
08-31 16:50:38.739  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.170, size:243
08-31 16:50:38.739  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.739  5693  5725 D bt_vendor: HCI-CMD 170:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.739  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 170
08-31 16:50:38.739  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.171, size:243
08-31 16:50:38.739  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.739  5693  5725 D bt_vendor: HCI-CMD 171:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.739  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 171
08-31 16:50:38.739  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.172, size:243
08-31 16:50:38.739  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.739  5693  5725 D bt_vendor: HCI-CMD 172:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.739  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 172
08-31 16:50:38.739  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.173, size:243
,08-31 16:50:38.739  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.739  5693  5725 D bt_vendor: HCI-CMD 173:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.739  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 173
08-31 16:50:38.739  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.174, size:243
08-31 16:50:38.739  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.739  5693  5725 D bt_vendor: HCI-CMD 174:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.739  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 174
08-31 16:50:38.739  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.175, size:243
08-31 16:50:38.739  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.739  5693  5725 D bt_vendor: HCI-CMD 175:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.739  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 175
,08-31 16:50:38.739  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.176, size:243
08-31 16:50:38.739  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.739  5693  5725 D bt_vendor: HCI-CMD 176:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.739  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 176
08-31 16:50:38.739  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.177, size:243
08-31 16:50:38.739  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
,08-31 16:50:38.739  5693  5725 D bt_vendor: HCI-CMD 177:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.739  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 177
08-31 16:50:38.739  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.178, size:243
08-31 16:50:38.739  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.739  5693  5725 D bt_vendor: HCI-CMD 178:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.739  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 178
08-31 16:50:38.739  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.179, size:243
08-31 16:50:38.739  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.739  5693  5725 D bt_vendor: HCI-CMD 179:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.739  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 179
08-31 16:50:38.739  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.180, size:243
,08-31 16:50:38.739  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.739  5693  5725 D bt_vendor: HCI-CMD 180:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 180
,08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.181, size:243
08-31 16:50:38.749  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.749  5693  5725 D bt_vendor: HCI-CMD 181:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 181
08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.182, size:243
08-31 16:50:38.749  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.749  5693  5725 D bt_vendor: HCI-CMD 182:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 182
08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.183, size:243
08-31 16:50:38.749  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.749  5693  5725 D bt_vendor: HCI-CMD 183:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 183
08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.184, size:243
,08-31 16:50:38.749  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.749  5693  5725 D bt_vendor: HCI-CMD 184:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 184
08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.185, size:243
08-31 16:50:38.749  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.749  5693  5725 D bt_vendor: HCI-CMD 185:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 185
08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.186, size:243
08-31 16:50:38.749  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.749  5693  5725 D bt_vendor: HCI-CMD 186:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 186
,08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.187, size:243
08-31 16:50:38.749  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.749  5693  5725 D bt_vendor: HCI-CMD 187:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 187
08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.188, size:243
,08-31 16:50:38.749  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.749  5693  5725 D bt_vendor: HCI-CMD 188:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 188
08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.189, size:243
,08-31 16:50:38.749  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.749  5693  5725 D bt_vendor: HCI-CMD 189:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 189
08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.190, size:243
,08-31 16:50:38.749  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.749  5693  5725 D bt_vendor: HCI-CMD 190:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 190
,08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.191, size:243
08-31 16:50:38.749  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.749  5693  5725 D bt_vendor: HCI-CMD 191:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 191
,08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.192, size:243
08-31 16:50:38.749  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.749  5693  5725 D bt_vendor: HCI-CMD 192:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 192
,08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.193, size:243
08-31 16:50:38.749  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.749  5693  5725 D bt_vendor: HCI-CMD 193:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 193
,08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.194, size:243
08-31 16:50:38.749  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.749  5693  5725 D bt_vendor: HCI-CMD 194:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 194
08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.195, size:243
,08-31 16:50:38.749  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.749  5693  5725 D bt_vendor: HCI-CMD 195:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 195
08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.196, size:243
,08-31 16:50:38.749  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.749  5693  5725 D bt_vendor: HCI-CMD 196:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 196
08-31 16:50:38.749  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.197, size:243
,08-31 16:50:38.749  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.749  5693  5725 D bt_vendor: HCI-CMD 197:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 197
,08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.198, size:243
08-31 16:50:38.759  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.759  5693  5725 D bt_vendor: HCI-CMD 198:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 198
08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.199, size:243
08-31 16:50:38.759  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
,08-31 16:50:38.759  5693  5725 D bt_vendor: HCI-CMD 199:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 199
08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.200, size:243
08-31 16:50:38.759  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.759  5693  5725 D bt_vendor: HCI-CMD 200:	0x1 	0x0 	,0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 200
08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.201, size:243
08-31 16:50:38.759  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.759  5693  5725 D bt_vendor: HCI-CMD 201:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 201
08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.202, size:243
08-31 16:50:38.759  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.759  5693  5725 D bt_vendor: HCI-CMD 202:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 202
08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.203, size:243
08-31 16:50:38.759  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
,08-31 16:50:38.759  5693  5725 D bt_vendor: HCI-CMD 203:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 203
08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.204, size:243
08-31 16:50:38.759  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.759  5693  5725 D bt_vendor: HCI-CMD 204:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 204
08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.205, size:243
08-31 16:50:38.759  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.759  5693  5725 D bt_vendor: HCI-CMD 205:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 205
,08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.206, size:243
08-31 16:50:38.759  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.759  5693  5725 D bt_vendor: HCI-CMD 206:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 206
08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.207, size:243
,08-31 16:50:38.759  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.759  5693  5725 D bt_vendor: HCI-CMD 207:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 207
08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.208, size:243
08-31 16:50:38.759  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
,08-31 16:50:38.759  5693  5725 D bt_vendor: HCI-CMD 208:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 208
08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.209, size:243
08-31 16:50:38.759  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.759  5693  5725 D bt_vendor: HCI-CMD 209:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 209
08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.210, size:243
08-31 16:50:38.759  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.759  5693  5725 D bt_vendor: HCI-CMD 210:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 210
,08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.211, size:243
08-31 16:50:38.759  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.759  5693  5725 D bt_vendor: HCI-CMD 211:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 211
08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.212, size:243
,08-31 16:50:38.759  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.759  5693  5725 D bt_vendor: HCI-CMD 212:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 212
08-31 16:50:38.759  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.213, size:243
08-31 16:50:38.759  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
,08-31 16:50:38.759  5693  5725 D bt_vendor: HCI-CMD 213:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 213
08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.214, size:243
08-31 16:50:38.779  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.779  5693  5725 D bt_vendor: HCI-CMD 214:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 214
08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.215, size:243
08-31 16:50:38.779  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD,
08-31 16:50:38.779  5693  5725 D bt_vendor: HCI-CMD 215:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 215
08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.216, size:243
08-31 16:50:38.779  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.779  5693  5725 D bt_vendor: HCI-CMD 216:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 216
08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.217, size:243
08-31 16:50:38.779  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.779  5693  5725 D bt_vendor: HCI-CMD 217:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 217
08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.218, size:243
,08-31 16:50:38.779  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.779  5693  5725 D bt_vendor: HCI-CMD 218:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 218
08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.219, size:243
08-31 16:50:38.779  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
,08-31 16:50:38.779  5693  5725 D bt_vendor: HCI-CMD 219:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 219
08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.220, size:243
08-31 16:50:38.779  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.779  5693  5725 D bt_vendor: HCI-CMD 220:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 220
08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.221, size:243
08-31 16:50:38.779  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.779  5693  5725 D bt_vendor: HCI-CMD 221:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 221
,08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.222, size:243
08-31 16:50:38.779  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.779  5693  5725 D bt_vendor: HCI-CMD 222:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 222
08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.223, size:243
,08-31 16:50:38.779  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.779  5693  5725 D bt_vendor: HCI-CMD 223:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 223
08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.224, size:243
,08-31 16:50:38.779  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.779  5693  5725 D bt_vendor: HCI-CMD 224:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 224
08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.225, size:243
,08-31 16:50:38.779  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.779  5693  5725 D bt_vendor: HCI-CMD 225:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 225
08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.226, size:243
,08-31 16:50:38.779  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.779  5693  5725 D bt_vendor: HCI-CMD 226:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 226
08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.227, size:243
08-31 16:50:38.779  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.779  5693  5725 D bt_vendor: HCI-CMD 227:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 227
08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.228, size:243
08-31 16:50:38.779  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.779  5693  5725 D bt_vendor: HCI-CMD 228:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 228
08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.229, size:243
08-31 16:50:38.779  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.779  5693  5725 D bt_vendor: HCI-CMD 229:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 229
08-31 16:50:38.779  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.230, size:243
08-31 16:50:38.779  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.779  5693  5725 D bt_vendor: HCI-CMD 230:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 230
,08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.231, size:243
08-31 16:50:38.789  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.789  5693  5725 D bt_vendor: HCI-CMD 231:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 231
08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.232, size:243
08-31 16:50:38.789  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.789  5693  5725 D bt_vendor: HCI-CMD 232:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 232
08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.233, size:243
08-31 16:50:38.789  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.789  5693  5725 D bt_vendor: HCI-CMD 233:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 233
08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.234, size:243
,08-31 16:50:38.789  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.789  5693  5725 D bt_vendor: HCI-CMD 234:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 234
08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.235, size:243
08-31 16:50:38.789  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
,08-31 16:50:38.789  5693  5725 D bt_vendor: HCI-CMD 235:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 235
08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.236, size:243
08-31 16:50:38.789  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
,08-31 16:50:38.789  5693  5725 D bt_vendor: HCI-CMD 236:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 236
08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.237, size:243
08-31 16:50:38.789  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.789  5693  5725 D bt_vendor: HCI-CMD 237:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 237
08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.238, size:243
08-31 16:50:38.789  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.789  5693  5725 D bt_vendor: HCI-CMD 238:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 238
,08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.239, size:243
08-31 16:50:38.789  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.789  5693  5725 D bt_vendor: HCI-CMD 239:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 239
08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.240, size:243
08-31 16:50:38.789  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.789  5693  5725 D bt_vendor: HCI-CMD 240:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 240
08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.241, size:243
08-31 16:50:38.789  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.789  5693  5725 D bt_vendor: HCI-CMD 241:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 241
08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.242, size:243
,08-31 16:50:38.789  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.789  5693  5725 D bt_vendor: HCI-CMD 242:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 242
08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.243, size:243
08-31 16:50:38.789  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
,08-31 16:50:38.789  5693  5725 D bt_vendor: HCI-CMD 243:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 243
08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.244, size:243
08-31 16:50:38.789  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.789  5693  5725 D bt_vendor: HCI-CMD 244:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 244
08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.245, size:243
08-31 16:50:38.789  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.789  5693  5725 D bt_vendor: HCI-CMD 245:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 245
,08-31 16:50:38.789  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.246, size:243
08-31 16:50:38.789  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.789  5693  5725 D bt_vendor: HCI-CMD 246:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.799  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 246
08-31 16:50:38.799  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.247, size:243
08-31 16:50:38.799  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.799  5693  5725 D bt_vendor: HCI-CMD 247:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.799  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 247
08-31 16:50:38.799  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.248, size:243
,08-31 16:50:38.799  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.799  5693  5725 D bt_vendor: HCI-CMD 248:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.799  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 248
08-31 16:50:38.799  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.249, size:243
08-31 16:50:38.799  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
,08-31 16:50:38.799  5693  5725 D bt_vendor: HCI-CMD 249:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.799  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 249
08-31 16:50:38.799  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.250, size:243
,08-31 16:50:38.799  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.799  5693  5725 D bt_vendor: HCI-CMD 250:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.799  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 250
08-31 16:50:38.799  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.251, size:243
08-31 16:50:38.799  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
,08-31 16:50:38.799  5693  5725 D bt_vendor: HCI-CMD 251:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.799  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 251
08-31 16:50:38.799  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.252, size:243
08-31 16:50:38.799  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.799  5693  5725 D bt_vendor: HCI-CMD 252:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.799  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 252
08-31 16:50:38.799  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.253, size:243
08-31 16:50:38.799  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.799  5693  5725 D bt_vendor: HCI-CMD 253:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.799  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 253
08-31 16:50:38.799  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.254, size:243
08-31 16:50:38.799  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.799  5693  5725 D bt_vendor: HCI-CMD 254:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.799  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 254
08-31 16:50:38.799  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.255, size:243
08-31 16:50:38.799  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.809  5693  5725 D bt_vendor: HCI-CMD 255:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.809  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 255
08-31 16:50:38.809  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.256, size:243
08-31 16:50:38.809  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.809  5693  5725 D bt_vendor: HCI-CMD 256:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.809  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 256
08-31 16:50:38.809  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.257, size:243
08-31 16:50:38.809  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.809  5693  5725 D bt_vendor: HCI-CMD 257:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.809  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 257
08-31 16:50:38.809  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.258, size:243
08-31 16:50:38.809  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.809  5693  5725 D bt_vendor: HCI-CMD 258:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.809  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 258
08-31 16:50:38.809  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.259, size:243
08-31 16:50:38.809  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.809  5693  5725 D bt_vendor: HCI-CMD 259:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.809  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 259
08-31 16:50:38.809  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.260, size:243
08-31 16:50:38.809  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.809  5693  5725 D bt_vendor: HCI-CMD 260:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.809  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 260
08-31 16:50:38.809  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.261, size:243
08-31 16:50:38.809  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.809  5693  5725 D bt_vendor: HCI-CMD 261:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.809  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 261
08-31 16:50:38.809  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.262, size:243
08-31 16:50:38.809  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.809  5693  5725 D bt_vendor: HCI-CMD 262:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.809  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 262
08-31 16:50:38.809  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.263, size:243
08-31 16:50:38.809  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.809  5693  5725 D bt_vendor: HCI-CMD 263:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.819  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 263
,08-31 16:50:38.819  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.264, size:243
08-31 16:50:38.819  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.819  5693  5725 D bt_vendor: HCI-CMD 264:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.819  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 264
,08-31 16:50:38.819  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.265, size:243
08-31 16:50:38.819  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.819  5693  5725 D bt_vendor: HCI-CMD 265:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.819  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 265
08-31 16:50:38.819  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.266, size:243
,08-31 16:50:38.819  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.819  5693  5725 D bt_vendor: HCI-CMD 266:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.819  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 266
08-31 16:50:38.819  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.267, size:243
08-31 16:50:38.819  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
,08-31 16:50:38.819  5693  5725 D bt_vendor: HCI-CMD 267:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.819  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 267
08-31 16:50:38.819  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.268, size:243
08-31 16:50:38.819  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.819  5693  5725 D bt_vendor: HCI-CMD 268:	0x1 	0x0 	,0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.819  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 268
08-31 16:50:38.819  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.269, size:243
08-31 16:50:38.819  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.819  5693  5725 D bt_vendor: HCI-CMD 269:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
,08-31 16:50:38.819  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 269
08-31 16:50:38.819  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.270, size:130
08-31 16:50:38.819  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.819  5693  5725 D bt_vendor: HCI-CMD 270:	0x1 	0x0 	0xfc 	0x84 	0x1e 	0x82
08-31 16:50:38.819  5693  5725 I bt_vendor: read_vs_hci_event: Wait for HCI-Vendor Specfic Event from SOC
,08-31 16:50:38.959  5693  5725 I bt_vendor: get_vs_hci_event: Received HCI-Vendor Specific event
08-31 16:50:38.959  5693  5725 I bt_vendor: get_vs_hci_event: Parameter Length: 0x3
08-31 16:50:38.959  5693  5725 I bt_vendor: get_vs_hci_event: Command response: 0x0
,08-31 16:50:38.959  5693  5725 I bt_vendor: get_vs_hci_event: Response type   : 0x4
08-31 16:50:38.959  5693  5725 I bt_vendor: get_vs_hci_event: Command Request Response
08-31 16:50:38.959  5693  5725 I bt_vendor: get_vs_hci_event: Download Packet successfully!
08-31 16:50:38.959  5693  5725 I bt_vendor: hci_send_vs_cmd: Received HCI-Vendor Specific Event from SOC
08-31 16:50:38.959  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 270
08-31 16:50:38.959  5693  5725 I bt_vendor: File Open (/system/etc/firmware/btnv32.bin)
08-31 16:50:38.959  5693  5725 I bt_vendor: ====================================================
08-31 16:50:38.959  5693  5725 I bt_vendor: TLV Type			 : 0x2
08-31 16:50:38.959  5693  5725 I bt_vendor: Length			 : 2006 bytes
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG ID			 : 2
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Length			 : 6
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Pointer			 : 0
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
08-31 16:50:38.959  5693  5725 I bt_vendor: BD Address: ee:95:eb:3e:78:44
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Data			 : ee 95 eb 3e 78 44 
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG ID			 : 6
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Length			 : 8
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Pointer			 : 0
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Data			 : ff fe 8f fe d8 3f 5b 8f 
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG ID			 : 17
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Length			 : 8
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Pointer			 : 0
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Data			 : 82 01 0e 08 04 0a 28 00 
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG ID			 : 27
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Length			 : 1
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Pointer			 : 0
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Data			, : 01 
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG ID			 : 28
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Length			 : 20
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Pointer			 : 0
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
,08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Data			 : 00 10 00 00 2c 01 02 08 14 f4 00 00 33 f4 00 00 00 00 00 00 
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG ID			 : 32
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Length			 : 2
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Pointer			 : 0
,08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Data			 : 09 32 
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG ID			 : 35
,08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Length			 : 55
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Pointer			 : 0
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Data			 : 40 41 42 43 44 45 46 47 58 59 0e 0e 16 16 16 1e 26 5f 36 7e 0e 0e 16 16 16 1e 26 5f 36 7e 08 12 10 1c 2e 38 4d 52 58 70 08 12 10 1c 2e 38 4d 52 58 70 1b 1a 01 05 dd ,
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG ID			 : 36
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Length			 : 12
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Pointer			 : 0
,08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Data			 : ff 03 08 09 09 09 00 00 09 07 01 00 
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG ID			 : 37
,08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Length			 : 22
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Pointer			 : 0
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
,08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Data			 : 00 00 02 01 01 03 03 03 00 03 03 03 00 00 04 00 34 1b 02 05 00 00 
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG ID			 : 38
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Length			 : 13
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Pointer			 : 0
,08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Data			 : 06 01 68 09 70 00 00 1f 00 00 00 00 05 
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG ID			 : 39
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Length			 : 4
,08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Pointer			 : 0
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Data			 : 13 08 00 00 
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG ID			 : 40
,08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Length			 : 18
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Pointer			 : 0
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Data			 : 32 05 07 0d e2 11 43 13 c0 0c 40 10 e0 12 8d 04 3d 08 
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG ID			 : 41
,08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Length			 : 176
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Pointer			 : 0
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Data			 : 2b 00 00 00 f6 02 00 00 76 00 0e 00 29 02 1e 00 61 00 0a 00 7d 00 50 00 91 00 06 00 92 00 03 00 a6 01 50 00 aa 01 22 00 ab 01 0f 00 ac 01 00 00 84 00 1f 00 b3 01 03 00 b4 01 14 00 b5 01 07 00 c5 01 0d 00 c6 01 10 00 ca 01 2b 00 cb 01 5f 00 cc 01 48 00 6c 00 00 00 d0 01 6a 00 48 00 33 00 71 03 03 00 4b 02 2f 00 49 00 6d 00 4a 00 a5 00 66 00 3b 00 02 02 01 00 05 01 1a 00 47 00 44 00 45 02 0f 00 83 00 39 00 85 00 3a 00 47 02 09 00 56 02 09 00 33 02 04 00 2e 00 12 00 e0 01 08 00 72 00 0b 00 2b 02 2a 00 00 00 00 00 00 00 00 00 
,08-31 16:50:38.959  5693  5725 I bt_vendor: TAG ID			 : 42
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Length			 : 60
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Pointer			 : 0
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Data			 : 60 e3 16 00 c7 c3 00 00 c0 e1 e4 00 a1 18 00 00 00 01 1f 01 42 01 69 01 95 01 c7 01 fe 01 3d 02 83 02 d1 02 29 03 00 0a 10 00 1f 00 3f 00 7f 00 fd 00 f9 01 f1 03 de 07 00 00 9a 01 
,08-31 16:50:38.959  5693  5725 I bt_vendor: TAG ID			 : 44
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Length			 : 41
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Pointer			 : 0
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Data			 : 6f 0a 00 00 00 00 00 28 ff 10 02 0a 03 0a 0a 03 0a 28 a0 62 03 64 01 01 0a 00 00 00 00 00 00 a0 ff 10 0a 03 0a 0a 03 0a 03 
,08-31 16:50:38.959  5693  5725 I bt_vendor: TAG ID			 : 46
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Length			 : 2
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Pointer			 : 0
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
,08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Data			 : 6c 00 
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG ID			 : 57
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Length			 : 44
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Pointer			 : 0
,08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Data			 : 03 00 3c 00 14 00 00 00 00 00 00 00 00 00 00 00 0a 0a 02 4f 01 08 01 10 03 05 01 01 00 01 01 01 b2 03 06 00 20 03 03 01 0a 06 10 b8 
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG ID			 : 60
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Length			 : 69
,08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Pointer			 : 0
08-31 16:50:38.959  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Data			 : 80 fa 02 32 80 fa 02 32 c0 a3 00 19 d1 1c f9 00 bb 95 fb 00 81 fb 3a 00 f5 56 2f 00 7d 05 00 00 66 06 00 00 0e 00 00 00 c9 1a ef 00 ec a5 f4 00 d2 75 5b 00 3a 63 4b 00 c8 0a 00 00 33 03 00 00 09 00 00 00 00 
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG ID			 : 64
,08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Length			 : 78
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Pointer			 : 0
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Data			 : 00 04 08 0a 0c 0e 10 10 12 14 16 1e 20 22 24 28 2e 32 34 38 3a 3c 3e 40 44 46 48 4a 4c 4e 50 5a 60 66 6e 70 72 74 76 78 7a e6 00 00 5e 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 04 00 01 41 00 20 03 38 00 d0 07 d0 07 88 13 
,08-31 16:50:38.969  5693  5725 I bt_vendor: TAG ID			 : 65
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Length			 : 11
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Pointer			 : 0
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
,08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Data			 : 01 04 02 04 04 08 04 04 02 00 02 
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG ID			 : 71
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Length			 : 9
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Pointer			 : 0
,08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Data			 : 04 04 0c 04 7f 00 05 08 10 
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG ID			 : 78
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Length			 : 2
,08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Pointer			 : 0
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Data			 : 08 08 
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG ID			 : 82
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Length			 : 16
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Pointer			 : 0
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Data			 : 25 0f 00 80 00 00 00 00 00 00 00 00 00 00 00 00 
,08-31 16:50:38.969  5693  5725 I bt_vendor: TAG ID			 : 84
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Length			 : 212
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Pointer			 : 0
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Data			 : 02 13 14 23 25 26 27 38 38 00 2b 2b 2b 2b 2b 2b 29 29 29 29 29 29 2d 2d 2d 2d 2d 2d 28 28 28 28 28 28 2f 2f 2f 2f 2f 2f 18 18 17 18 16 00 1b 1b 1b 1c 1c 1b 19 11 1b 1b 1b 1d 15 14 12 11 1b 1b 15 16 15 14 12 10 14 14 14 15 13 11 10 0f 04 04 04 03 03 05 07 0e 05 05 05 03 0a 0f 11 13 05 05 0a 0d 0e 0f 11 12 0f 10 0f 0f 11 13 12 13 00 00 3e 7b 7b 73 71 50 50 50 00 40 60 60 30 08 02 0f 00 01 00 00 00 00 00 00 08 16 16 08 08 00 00 00 37 5f 48 29 38 42 22 18 01 04 03 04 03 00 86 01 95 01 af 01 ca 01 e5 01 02 02 16 02 35 02 56 02 81 02 a5 02 cb 02 f2 02 25 03 51 03 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-31 16:50:38.969  5693  5725 I bt_vendor: TAG ID			 : 85
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Length			 : 248
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Pointer			 : 0
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
,08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Data			 : ff ff 3b 00 44 32 8f 01 b6 01 ea 01 21 02 53 02 93 02 e3 02 2f 03 00 00 a2 03 ce 04 fa 05 26 07 0a 01 55 02 f4 0c 01 00 f4 01 00 00 5f 80 06 00 2a 1e de 00 00 00 00 00 0c 0c 0c 04 04 04 04 0c 0c 04 04 04 04 00 02 02 02 02 01 00 00 02 02 02 01 00 00 00 1f 1f 14 10 10 10 03 1f 14 10 10 10 03 00 0f 0f 0f 0f 0f 0f 0f 0f 0f 0f 0f 0f 0f 0f 0c 0c 0c 06 06 06 00 0c 0c 06 06 06 00 00 02 02 02 02 01 00 00 02 02 02 01 00 00 00 1f 1a 0e 08 08 08 00 1a 0e 08 08 08 00 00 0f 0f 0f 0f 0f 0f 0f 0f 0f 0f 0f 0f 0f 0f 0c 0c 0c 0c 06 06 06 0c 0c 0c 06 06 06 00 02 02 02 02 02 01 00 02 02 02 02 01 00 00 1f 1f 1a 0e 08 08 08 1f 1a 0e 08 08 08 00 0f 0f 0f 0f 0f 0f 0f 0f 0f 0f 0f 0f 0f 0f 00 06 14 05 47 cf 77 ac 7c ac 7c ac 7c ac 7c c4 80 00 00 00 1e 04 04 00 
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG ID			 : 86
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Length			 : 24
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Pointer			 : 0
,08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Data			 : 03 25 0a 07 08 32 7e 86 8e 96 9e a6 ae b6 be 7e 86 8e 96 9e a6 ae b6 be 
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG ID			 : 90
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Length			 : 8
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Pointer			 : 0
,08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Data			 : ff 00 00 00 00 00 00 00 
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG ID			 : 91
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Length			 : 180
,08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Pointer			 : 0
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Data			 : 01 01 00 03 03 00 03 04 00 03 07 00 03 0a 00 03 0c 00 06 0c 00 0a 0e 00 0b 0d 00 0e 0f 00 c3 68 c3 68 c3 68 c3 68 c3 68 c3 68 c3 68 c3 68 c3 68 c2 68 c2 68 c2 68 c3 68 c3 68 c3 68 c4 69 c4 69 c4 69 c4 69 c4 69 c4 69 c4 69 c4 69 c4 69 c3 69 c3 69 c3 69 c4 69 c4 69 c4 69 c5 69 c5 69 c5 69 c5 69 c5 69 c5 69 c5 69 c5 69 c5 69 c4 69 c4 69 c4 69 c5 69 c5 69 c5 69 c7 7d c7 7d c7 7d c7 7d c7 7d c7 7d c7 7d c7 7d c7 7d c6 7d c6 7d c6 7d c6 7d c6 7d c6 7d d8 7f d8 7f d8 7f d8 7f d8 7f d8 7f d8 7f d8 7f d8 7f d7 7f d7 7f d7 7f d8 7f d8 7f d8 7f 
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG ID			 : 93
,08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Length			 : 160
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Pointer			 : 0
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Data			 : 44 44 44 44 44 44 44 44 44 44 44 44 54 45 44 54 54 45 44 54 54 45 45 44 44 45 45 44 54 45 54 55 55 55 55 55 55 55 55 55 55 55 55 55 55 55 55 55 65 55 55 65 65 56 55 55 55 55 55 55 65 56 55 66 66 66 66 66 66 66 66 66 66 66 66 66 66 66 66 66 77 77 77 77 77 77 77 77 77 77 77 77 67 77 77 67 77 77 87 78 77 77 87 78 77 77 87 78 77 87 77 77 88 88 98 89 88 88 98 89 88 88 88 88 88 88 88 78 99 99 a9 9a 99 99 a9 9a 99 99 99 99 99 99 99 88 9a aa ba 9b aa aa ba ab aa aa aa aa 9a aa aa 99 
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG ID			 : 95
,08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Length			 : 94
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Pointer			 : 0
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Data			 : 00 0b 01 0d 00 00 00 02 00 02 02 00 00 10 33 73 33 33 07 00 02 00 01 23 d7 03 ec 01 da 00 66 06 33 13 fe 04 00 00 36 00 21 00 00 10 00 28 00 00 10 01 14 64 0a 00 72 01 2b 2b 44 4a 47 45 45 45 43 44 58 57 55 54 5a 59 25 40 28 28 39 3d 39 3a 3a 3a 38 39 44 44 43 42 45 45 24 36 19 48 
,08-31 16:50:38.969  5693  5725 I bt_vendor: TAG ID			 : 144
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Length			 : 1
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Pointer			 : 0
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Data			 : 00 
,08-31 16:50:38.969  5693  5725 I bt_vendor: TAG ID			 : 150
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Length			 : 18
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Pointer			 : 0
08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Extended Flag		 : 0
,08-31 16:50:38.969  5693  5725 I bt_vendor: TAG Data			 : 32 05 07 0d c5 10 26 13 80 0c 60 10 87 13 30 0e 00 0e 
08-31 16:50:38.969  5693  5725 I bt_vendor: ====================================================
08-31 16:50:38.969  5693  5725 I bt_vendor: rome_tlv_dnld_req: TLV size: 2010, Total Seg num: 8, remain size: 66
08-31 16:50:38.969  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.0, size:243
08-31 16:50:38.969  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.969  5693  5725 D bt_vendor: HCI-CMD 0:	0x1 	0x0 	0xfc 	0xf5 ,	0x1e 	0xf3
08-31 16:50:38.969  5693  5725 I bt_vendor: read_vs_hci_event: Wait for HCI-Vendor Specfic Event from SOC
08-31 16:50:38.969  5693  5725 I bt_vendor: get_vs_hci_event: Received HCI-Vendor Specific event
08-31 16:50:38.969  5693  5725 I bt_vendor: get_vs_hci_event: Parameter Length: 0x3
08-31 16:50:38.969  5693  5725 I bt_vendor: get_vs_hci_event: Command response: 0x0
08-31 16:50:38.969  5693  5725 I bt_vendor: get_vs_hci_event: Response type   : 0x4
08-31 16:50:38.969  5693  5725 I bt_vendor: get_vs_hci_event: Command Request Response
,08-31 16:50:38.969  5693  5725 I bt_vendor: get_vs_hci_event: Download Packet successfully!
08-31 16:50:38.969  5693  5725 I bt_vendor: hci_send_vs_cmd: Received HCI-Vendor Specific Event from SOC
08-31 16:50:38.969  5693  5725 I bt_vendor: read_hci_event: Wait for Command Compete Event from SOC
08-31 16:50:38.969  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 0
08-31 16:50:38.969  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.1, size:243
08-31 16:50:38.969  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.969  5693  5725 D bt_vendor: HCI-CMD 1:	0x1 	0x0 	0xfc 	0xf5 	,0x1e 	0xf3
08-31 16:50:38.969  5693  5725 I bt_vendor: read_vs_hci_event: Wait for HCI-Vendor Specfic Event from SOC
08-31 16:50:38.969  5693  5725 I bt_vendor: get_vs_hci_event: Received HCI-Vendor Specific event
08-31 16:50:38.969  5693  5725 I bt_vendor: get_vs_hci_event: Parameter Length: 0x3
08-31 16:50:38.969  5693  5725 I bt_vendor: get_vs_hci_event: Command response: 0x0
08-31 16:50:38.969  5693  5725 I bt_vendor: get_vs_hci_event: Response type   : 0x4
08-31 16:50:38.969  5693  5725 I bt_vendor: get_vs_hci_event: Command Request Response
,08-31 16:50:38.969  5693  5725 I bt_vendor: get_vs_hci_event: Download Packet successfully!
08-31 16:50:38.969  5693  5725 I bt_vendor: hci_send_vs_cmd: Received HCI-Vendor Specific Event from SOC
08-31 16:50:38.969  5693  5725 I bt_vendor: read_hci_event: Wait for Command Compete Event from SOC
08-31 16:50:38.969  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 1
08-31 16:50:38.969  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.2, size:243
08-31 16:50:38.969  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
,08-31 16:50:38.969  5693  5725 D bt_vendor: HCI-CMD 2:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.969  5693  5725 I bt_vendor: read_vs_hci_event: Wait for HCI-Vendor Specfic Event from SOC
08-31 16:50:38.969  5693  5725 I bt_vendor: get_vs_hci_event: Received HCI-Vendor Specific event
08-31 16:50:38.969  5693  5725 I bt_vendor: get_vs_hci_event: Parameter Length: 0x3
08-31 16:50:38.969  5693  5725 I bt_vendor: get_vs_hci_event: Command response: 0x0
,08-31 16:50:38.969  5693  5725 I bt_vendor: get_vs_hci_event: Response type   : 0x4
08-31 16:50:38.969  5693  5725 I bt_vendor: get_vs_hci_event: Command Request Response
08-31 16:50:38.969  5693  5725 I bt_vendor: get_vs_hci_event: Download Packet successfully!
08-31 16:50:38.969  5693  5725 I bt_vendor: hci_send_vs_cmd: Received HCI-Vendor Specific Event from SOC
08-31 16:50:38.969  5693  5725 I bt_vendor: read_hci_event: Wait for Command Compete Event from SOC
08-31 16:50:38.969  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 2
08-31 16:50:38.969  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.3, size:243
,08-31 16:50:38.969  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.969  5693  5725 D bt_vendor: HCI-CMD 3:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.969  5693  5725 I bt_vendor: read_vs_hci_event: Wait for HCI-Vendor Specfic Event from SOC
08-31 16:50:38.969  5693  5725 I bt_vendor: get_vs_hci_event: Received HCI-Vendor Specific event
08-31 16:50:38.969  5693  5725 I bt_vendor: get_vs_hci_event: Parameter Length: 0x3
,08-31 16:50:38.969  5693  5725 I bt_vendor: get_vs_hci_event: Command response: 0x0
08-31 16:50:38.969  5693  5725 I bt_vendor: get_vs_hci_event: Response type   : 0x4
08-31 16:50:38.969  5693  5725 I bt_vendor: get_vs_hci_event: Command Request Response
08-31 16:50:38.969  5693  5725 I bt_vendor: get_vs_hci_event: Download Packet successfully!
08-31 16:50:38.969  5693  5725 I bt_vendor: hci_send_vs_cmd: Received HCI-Vendor Specific Event from SOC
08-31 16:50:38.969  5693  5725 I bt_vendor: read_hci_event: Wait for Command Compete Event from SOC
08-31 16:50:38.969  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 3
,08-31 16:50:38.969  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.4, size:243
08-31 16:50:38.969  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.979  5693  5725 D bt_vendor: HCI-CMD 4:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.979  5693  5725 I bt_vendor: read_vs_hci_event: Wait for HCI-Vendor Specfic Event from SOC
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Received HCI-Vendor Specific event
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Parameter Length: 0x3
,08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Command response: 0x0
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Response type   : 0x4
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Command Request Response
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Download Packet successfully!
08-31 16:50:38.979  5693  5725 I bt_vendor: hci_send_vs_cmd: Received HCI-Vendor Specific Event from SOC
08-31 16:50:38.979  5693  5725 I bt_vendor: read_hci_event: Wait for Command Compete Event from SOC
08-31 16:50:38.979  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 4
,08-31 16:50:38.979  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.5, size:243
08-31 16:50:38.979  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.979  5693  5725 D bt_vendor: HCI-CMD 5:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.979  5693  5725 I bt_vendor: read_vs_hci_event: Wait for HCI-Vendor Specfic Event from SOC
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Received HCI-Vendor Specific event
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Parameter Length: 0x3
,08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Command response: 0x0
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Response type   : 0x4
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Command Request Response
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Download Packet successfully!
08-31 16:50:38.979  5693  5725 I bt_vendor: hci_send_vs_cmd: Received HCI-Vendor Specific Event from SOC
08-31 16:50:38.979  5693  5725 I bt_vendor: read_hci_event: Wait for Command Compete Event from SOC
08-31 16:50:38.979  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 5
,08-31 16:50:38.979  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.6, size:243
08-31 16:50:38.979  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.979  5693  5725 D bt_vendor: HCI-CMD 6:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.979  5693  5725 I bt_vendor: read_vs_hci_event: Wait for HCI-Vendor Specfic Event from SOC
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Received HCI-Vendor Specific event
,08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Parameter Length: 0x3
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Command response: 0x0
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Response type   : 0x4
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Command Request Response
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Download Packet successfully!
08-31 16:50:38.979  5693  5725 I bt_vendor: hci_send_vs_cmd: Received HCI-Vendor Specific Event from SOC
08-31 16:50:38.979  5693  5725 I bt_vendor: read_hci_event: Wait for Command Compete Event from SOC
08-31 16:50:38.979  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 6
,08-31 16:50:38.979  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.7, size:243
08-31 16:50:38.979  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.979  5693  5725 D bt_vendor: HCI-CMD 7:	0x1 	0x0 	0xfc 	0xf5 	0x1e 	0xf3
08-31 16:50:38.979  5693  5725 I bt_vendor: read_vs_hci_event: Wait for HCI-Vendor Specfic Event from SOC
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Received HCI-Vendor Specific event
,08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Parameter Length: 0x3
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Command response: 0x0
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Response type   : 0x4
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Command Request Response
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Download Packet successfully!
08-31 16:50:38.979  5693  5725 I bt_vendor: hci_send_vs_cmd: Received HCI-Vendor Specific Event from SOC
08-31 16:50:38.979  5693  5725 I bt_vendor: read_hci_event: Wait for Command Compete Event from SOC
,08-31 16:50:38.979  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 7
08-31 16:50:38.979  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Downloading TLV Patch segment no.8, size:66
08-31 16:50:38.979  5693  5725 D bt_vendor: frame_hci_cmd_pkt: Sending EDL_PATCH_TLV_REQ_CMD
08-31 16:50:38.979  5693  5725 D bt_vendor: HCI-CMD 8:	0x1 	0x0 	0xfc 	0x44 	0x1e 	0x42
08-31 16:50:38.979  5693  5725 I bt_vendor: read_vs_hci_event: Wait for HCI-Vendor Specfic Event from SOC
,08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Received HCI-Vendor Specific event
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Parameter Length: 0x3
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Command response: 0x0
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Response type   : 0x4
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Command Request Response
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Download Packet successfully!
08-31 16:50:38.979  5693  5725 I bt_vendor: hci_send_vs_cmd: Received HCI-Vendor Specific Event from SOC
08-31 16:50:38.979  5693  5725 I bt_vendor: read_hci_event: Wait for Command Compete Event from SOC
,08-31 16:50:38.979  5693  5725 I bt_vendor: rome_tlv_dnld_segment: Successfully downloaded patch segment: 8
08-31 16:50:38.979  5693  5725 I bt_vendor: rome_soc_init: Download TLV file successfully 
08-31 16:50:38.979  5693  5725 I bt_vendor: enable_controller_log: 0
08-31 16:50:38.979  5693  5725 I bt_vendor: read_vs_hci_event: Wait for HCI-Vendor Specfic Event from SOC
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Received HCI-Vendor Specific event
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Parameter Length: 0x1
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Command response: 0x0
,08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Response type   : 0x0
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Command Request Response
08-31 16:50:38.979  5693  5725 I bt_vendor: get_vs_hci_event: Download Packet successfully!
08-31 16:50:38.979  5693  5725 I bt_vendor: hci_send_vs_cmd: Received HCI-Vendor Specific Event from SOC
08-31 16:50:38.979  5693  5725 I bt_vendor: rome_hci_reset: HCI RESET 
08-31 16:50:38.979  5693  5725 I bt_vendor: read_hci_event: Wait for Command Compete Event from SOC
08-31 16:50:38.979  5693  5725 I bt_vendor: HCI Reset is done
,08-31 16:50:39.119  5737  5737 I WCNSS_FILTER: Init diag for BT log packets
,08-31 16:50:39.119  5737  5737 D WCNSS_FILTER: wcnss_ibs_init
08-31 16:50:39.119  5737  5737 D WCNSS_FILTER: wcnss_ibs_init: tty_fd = 13
,08-31 16:50:39.279  5693  5725 E bt_vendor: connect_to_local_socket: ACCEPT 
,08-31 16:50:39.279  5693  5725 E bt_vendor: connect_to_local_socket: Connection succeeded
,08-31 16:50:39.279  5693  5725 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-31 16:50:39.279  5693  5725 I bt_vendor: firmware callback
08-31 16:50:39.279  5693  5725 I bt_hci  : firmware_config_callback
,08-31 16:50:39.279  5693  5743 I bt_btu_task: Bluetooth chip preload is complete
,08-31 16:50:39.289  5693  5743 I         : BTE_InitTraceLevels -- TRC_HCI
08-31 16:50:39.289  5693  5743 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 16:50:39.289  5693  5743 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 16:50:39.289  5693  5743 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 16:50:39.289  5693  5743 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 16:50:39.289  5693  5743 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 16:50:39.289  5693  5743 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 16:50:39.289  5693  5743 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 16:50:39.289  5693  5743 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 16:50:39.289  5693  5743 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 16:50:39.289  5693  5743 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 16:50:39.289  5693  5743 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 16:50:39.289  5693  5743 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 16:50:39.289  5693  5743 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 16:50:39.289  5693  5743 I         : BTE_InitTraceLevels -- TRC_BTIF
08-31 16:50:39.289  5693  5743 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-31 16:50:39.289  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.289  5737  5738 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
,08-31 16:50:39.289  5737  5738 I WCNSS_FILTER: do_write: IBS write: fd
,08-31 16:50:39.289  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,08-31 16:50:39.349  5737  5737 I WCNSS_FILTER: do_write: IBS write: fc
,08-31 16:50:39.349  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.349  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.349  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,08-31 16:50:39.349  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 14 : bytes_written: 14
,08-31 16:50:39.349  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 11 : bytes_written: 11
,08-31 16:50:39.349  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.349  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.349  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,08-31 16:50:39.349  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
,08-31 16:50:39.349  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.349  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,08-31 16:50:39.349  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 13 : bytes_written: 13
08-31 16:50:39.349  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.349  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,08-31 16:50:39.349  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 71 : bytes_written: 71
,08-31 16:50:39.359  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
,08-31 16:50:39.359  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 17 : bytes_written: 17
08-31 16:50:39.359  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
,08-31 16:50:39.359  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.359  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,08-31 16:50:39.359  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.359  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
,08-31 16:50:39.359  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 17 : bytes_written: 17
,08-31 16:50:39.359  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
,08-31 16:50:39.359  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 17 : bytes_written: 17
08-31 16:50:39.359  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
,08-31 16:50:39.359  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.359  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.359  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,08-31 16:50:39.359  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
08-31 16:50:39.359  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.359  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,08-31 16:50:39.359  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 10 : bytes_written: 10
08-31 16:50:39.359  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.359  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,08-31 16:50:39.359  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
,08-31 16:50:39.359  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.359  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
08-31 16:50:39.369  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
,08-31 16:50:39.369  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.369  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
08-31 16:50:39.369  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,08-31 16:50:39.369  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.369  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,08-31 16:50:39.369  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 11 : bytes_written: 11
,08-31 16:50:39.369  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
08-31 16:50:39.369  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,08-31 16:50:39.369  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
,08-31 16:50:39.369  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.369  5693  5743 W bt_l2cap: l2c_link_processs_ble_num_bufs 16
08-31 16:50:39.369  5693  5743 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c4e659
08-31 16:50:39.369  5693  5743 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c4e659 
08-31 16:50:39.369  5693  5743 E bt_btm  : btm_ble_set_search_if search_if=4
,08-31 16:50:39.379  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.379  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,08-31 16:50:39.379  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.379  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,08-31 16:50:39.379  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.379  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
,08-31 16:50:39.379  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.379  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
,08-31 16:50:39.379  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.379  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
08-31 16:50:39.379  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.379  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
08-31 16:50:39.379  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.379  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,08-31 16:50:39.389  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.389  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
08-31 16:50:39.389  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,08-31 16:50:39.389  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.389  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,08-31 16:50:39.389  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 21 : bytes_written: 21
08-31 16:50:39.389  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.389  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
08-31 16:50:39.389  5693  5710 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 16 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mVersSupported = 95 mTotNumOfTrackableAdv = 32 mIsExtendedScanSupported = true mIsDebugLogSupported = false mAobleSupported = 0
,08-31 16:50:39.389  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 255 : bytes_written: 255
,08-31 16:50:39.399  5693  5710 E bt_btif : bta_dm_sm_execute e
08-31 16:50:39.399  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 252 : bytes_written: 252
,08-31 16:50:39.399  5693  5710 D bt_hci  : do_postload posting postload work item
,08-31 16:50:39.399  5693  5725 I bt_hci  : event_postload
08-31 16:50:39.399  5693  5725 I bt_vendor: sco_config_cb
08-31 16:50:39.399  5693  5710 E bt_btif_sock: btif_sock_init: !vhci_init
08-31 16:50:39.399  5693  5725 I bt_hci  : sco_config_callback postload finished.
08-31 16:50:39.399  5693  5710 E bt_btif : ## init_cmd_fd assert ts[h].cmd_fdr == -1 && ts[h].cmd_fdw == -1 failed at line:289 ##
08-31 16:50:39.399  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.399  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
,08-31 16:50:39.399  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.399  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.399  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
08-31 16:50:39.399  5693  5710 D bt_bte_conf: Device ID record 1 : primary
08-31 16:50:39.399  5693  5710 D bt_bte_conf:   vendorId            = 0075
,08-31 16:50:39.399  5693  5710 D bt_bte_conf:   vendorIdSource      = 0001
08-31 16:50:39.399  5693  5710 D bt_bte_conf:   product             = 0100
08-31 16:50:39.399  5693  5710 D bt_bte_conf:   version             = 0200
08-31 16:50:39.399  5693  5710 D bt_bte_conf:   clientExecutableURL = 
08-31 16:50:39.399  5693  5710 D bt_bte_conf:   serviceDescription  = 
08-31 16:50:39.399  5693  5710 D bt_bte_conf:   documentationURL    = 
08-31 16:50:39.399  5693  5710 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-31 16:50:39.399  5693  5707 D bt_stack_manager: event_start_up_stack finished
08-31 16:50:39.399  5693  5710 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  14 , val : 29
,08-31 16:50:39.399  5693  5710 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  15 , val : 8
08-31 16:50:39.399  5693  5710 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  16 , val : 602
08-31 16:50:39.399  5693  5710 D BluetoothDataManager: UpdateLocalInfo for String is called!!! type : 17, val : 
08-31 16:50:39.399  5693  5710 D BluetoothDataManager: firmwareVersion from Property : Rome Ver. 0x192
08-31 16:50:39.399  5693  5710 E BluetoothAdapterState: stateChangeCallback : 1
08-31 16:50:39.399  5693  5706 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: ENABLED_READY
08-31 16:50:39.409  5693  5706 D BluetoothAdapterProperties: Setting state to 15
08-31 16:50:39.409  5693  5706 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-31 16:50:39.409  5693  5706 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 16:50:39.409  5693  5706 D BluetoothAdapterService: updateAdapterState state is 15
08-31 16:50:39.409  5693  5706 D BluetoothAdapterService: Autoconnection is available 
08-31 16:50:39.409  5693  5706 D BluetoothAdapterService: updateAdapterState prevState = 14newState = 15
08-31 16:50:39.409  5693  5706 I BluetoothAdapterState: Entering BleOnState
,08-31 16:50:39.409  1159  1402 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 16:50:39.419  1159  1402 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,08-31 16:50:39.419  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
,08-31 16:50:39.419  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.419  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,08-31 16:50:39.429  5693  5706 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_ON
,08-31 16:50:39.429  5693  5706 D BluetoothAdapterProperties: Setting state to 11
08-31 16:50:39.429  5693  5706 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-31 16:50:39.429  5693  5706 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 16:50:39.429  5693  5706 D BluetoothAdapterService: updateAdapterState state is 11
,08-31 16:50:39.429  1159  1402 D BluetoothManagerService: Turning On/Off, G state: 2, S state: 2, mBLE count: 0, s BLE count: 0
,08-31 16:50:39.429  5693  5706 D BluetoothAdapterService: Autoconnection is available 
08-31 16:50:39.429  5693  5706 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 11
08-31 16:50:39.429  5693  5706 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 16:50:39.429  1159  1159 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 16:50:39.429  5693  5706 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-31 16:50:39.429  1159  1159 I InputMethodManagerService: [BT Setting State] State =11
,08-31 16:50:39.429  5693  5706 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 16:50:39.429  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
,08-31 16:50:39.429  2030  2030 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,08-31 16:50:39.429  1159  1159 D BluetoothPhoneService: Bluetooth Adapter state : 11
08-31 16:50:39.429  1705  2083 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,08-31 16:50:39.429  1705  2083 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-31 16:50:39.429  1159  1159 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
08-31 16:50:39.429  1159  1159 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:50:39.429  1159  1159 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,08-31 16:50:39.439  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.439  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
08-31 16:50:39.439  5636  5636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 16:50:39.439  1159  1366 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eefe2a u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{796a31c 5498:com.android.settings/1000}
,08-31 16:50:39.439  5693  5706 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 16:50:39.449  1705  2113 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = true, connected = false, connecting = false, mController.getLastDeviceName() = null
08-31 16:50:39.449  1159  2558 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eefe2a u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{efa98fc 2545:com.samsung.android.providers.context/u0a5}
08-31 16:50:39.449  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
08-31 16:50:39.449  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.449  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,08-31 16:50:39.449  1705  1705 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 148
08-31 16:50:39.449  5693  5693 D HeadsetService: Received start request. Starting profile...
08-31 16:50:39.449  5693  5693 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7a2026b
08-31 16:50:39.449  5693  5706 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 16:50:39.449  5693  5693 D HeadsetProvider: make
08-31 16:50:39.449  5693  5693 D HeadsetProvider: HeadsetProvider
08-31 16:50:39.449  5693  5693 I HeadsetProvider: clearAllHeadsetSettings(0)
,08-31 16:50:39.459  1159  2558 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eefe2a u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ad7afc9 1878:com.google.android.gms.persistent/u0a10}
,08-31 16:50:39.459  1878  1878 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,08-31 16:50:39.459  5693  5706 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-31 16:50:39.459  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
08-31 16:50:39.459  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.459  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,08-31 16:50:39.469  5693  5706 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-31 16:50:39.469  1159  1988 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eefe2a u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{796a31c 5498:com.android.settings/1000}
,08-31 16:50:39.469  5498  5498 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:50:39.469  5498  5498 D BluetoothStatusReceiver: AdapterStateChanged :: state = 11
,08-31 16:50:39.469  5693  5706 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 16:50:39.469  5498  5498 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
,08-31 16:50:39.479  5693  5706 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
08-31 16:50:39.479  5693  5693 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-31 16:50:39.479  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
08-31 16:50:39.479  5498  5498 D LocalBluetoothManager: LocalBluetoothManager :: constructor
08-31 16:50:39.479  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.479  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,08-31 16:50:39.479  5498  5498 D BluetoothEventManager: BluetoothEventManager Constructor :: 
08-31 16:50:39.479  5693  5706 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 16:50:39.479  5693  5706 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 16:50:39.479  5693  5706 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 16:50:39.479  5693  5706 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-31 16:50:39.479  5693  5706 I BluetoothAdapterState: Entering PendingCommandState
,08-31 16:50:39.479  5693  5693 D HeadsetStateMachine: make
,08-31 16:50:39.479  5693  5693 E HeadsetStateMachine: # of Max HF connection is 2
,08-31 16:50:39.489  1159  1402 D Tethering: enter TetherInterfaceSM  and send tetherstatechangebroadcast
08-31 16:50:39.489  1159  1371 E EthernetNetworkFactory: maybeTrackInterface : not matched eth0/usb0 iface is wlan0
08-31 16:50:39.489  1159  1402 D Tethering: NAP Supported and not Wifi Model
,08-31 16:50:39.489  5498  5498 D LocalBluetoothProfileManager: LocalBluetoothProfileManager :: uuid is null
08-31 16:50:39.489  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
08-31 16:50:39.489  5498  5498 D LocalBluetoothProfileManager: PANU : true
08-31 16:50:39.489  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.489  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,08-31 16:50:39.499  1159  1402 E Tethering: No numeric data
,08-31 16:50:39.499   747  1447 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1088
08-31 16:50:39.499   747  1447 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
08-31 16:50:39.499   747  1443 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
08-31 16:50:39.499   747  1443 I QC-NETMGR-LIB: Processing RTM_NEWLINK
08-31 16:50:39.499   747  1443 I QC-NETMGR-LIB: Metainfo:  Index=13 Family=0 Type=0x1 Change=[0xffffffff]UP BROADCAST DEBUG LOOPBACK POINTOPOINT NOTRAILERS RUNNING NOARP PROMISC ALLMULTI MASTER SLAVE MULTICAST PORTSEL AUTOMEDIA DYNAMIC LOWER_UP DORMANT  Flags=[0x1002]BROADCAST MULTICAST 
08-31 16:50:39.499   747  1443 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
08-31 16:50:39.499   555  1417 D Netd    : Iface wlan0 link down
08-31 16:50:39.499   747  1443 I QC-NETMGR-LIB: Received RTM_NEWLINK
08-31 16:50:39.499   747  1443 E QC-NETMGR-LIB: unrecognized ifindex 13, disable link
,08-31 16:50:39.499  5693  5693 I bt_bluedroid: get_profile_interface handsfree
08-31 16:50:39.499  1159  1371 E EthernetNetworkFactory: maybeTrackInterface : not matched eth0/usb0 iface is p2p0
,08-31 16:50:39.499   747  1447 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1088
08-31 16:50:39.509   747  1447 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
08-31 16:50:39.509   555  1417 D Netd    : Iface p2p0 link down
,08-31 16:50:39.509   747  1443 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
08-31 16:50:39.509   747  1443 I QC-NETMGR-LIB: Processing RTM_NEWLINK
08-31 16:50:39.509   747  1443 I QC-NETMGR-LIB: Metainfo:  Index=14 Family=0 Type=0x1 Change=[0xffffffff]UP BROADCAST DEBUG LOOPBACK POINTOPOINT NOTRAILERS RUNNING NOARP PROMISC ALLMULTI MASTER SLAVE MULTICAST PORTSEL AUTOMEDIA DYNAMIC LOWER_UP DORMANT  Flags=[0x1002]BROADCAST MULTICAST 
08-31 16:50:39.509   747  1443 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
08-31 16:50:39.509   747  1443 I QC-NETMGR-LIB: Received RTM_NEWLINK
08-31 16:50:39.509   747  1443 E QC-NETMGR-LIB: unrecognized ifindex 14, disable link
,08-31 16:50:39.509  1159  1402 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 16:50:39.509  1159  1402 D Tethering: InitialState.processMessage what=4
,08-31 16:50:39.509  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
08-31 16:50:39.509  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.509  1159  1621 V NetworkStats: performPollLocked(flags=0x1)
08-31 16:50:39.509  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
08-31 16:50:39.509  1159  1621 V NetworkStats: performPollLocked() took 3ms
08-31 16:50:39.509  1159  1402 D Tethering: NAP Supported and not Wifi Model
08-31 16:50:39.509  1159  1621 D NtpTrustedTime: forceRefresh: no connectivity
08-31 16:50:39.509  1705  1705 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 16:50:39.509  1705  1705 D HotspotTile: updateTetherState():false, false
08-31 16:50:39.509  1159  1402 E Tethering: No numeric data
,08-31 16:50:39.519  1159  1622 D NtpTrustedTime: forceRefresh: no connectivity
,08-31 16:50:39.519   555  1424 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-31 16:50:39.519   555  1424 D SoftapController: Softap fwReload - Ok
08-31 16:50:39.519  1159  1402 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 16:50:39.519  5498  5498 D BluetoothSap: Create BluetoothSap proxy object
,08-31 16:50:39.519  1159  1621 D NtpTrustedTime: forceRefresh: no connectivity
08-31 16:50:39.519  1705  1705 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 16:50:39.519  1705  1705 D HotspotTile: updateTetherState():false, false,
08-31 16:50:39.519   555  1424 D CommandListener: Setting iface cfg
08-31 16:50:39.519   555  1424 D CommandListener: Trying to bring down wlan0,
08-31 16:50:39.519   555  1424 D CommandListener: Clearing all IP addresses on wlan0
08-31 16:50:39.519  1159  1621 V NetworkStats: performPollLocked(flags=0x1)
,08-31 16:50:39.519  5498  5498 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-31 16:50:39.519  5498  5498 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
08-31 16:50:39.519  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
,08-31 16:50:39.519  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.519  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,08-31 16:50:39.519  5693  5693 I DualScoManager: Instantiating Dual Sco Manager
08-31 16:50:39.519  5693  5693 I DualScoManager: Set HeadsetServiceHelper
,08-31 16:50:39.519  5693  5693 D BluetoothAtMessage: createCMTIContentObservers,
08-31 16:50:39.529  1159  1624 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
08-31 16:50:39.529  1159  1621 V NetworkStats: performPollLocked() took 6ms
,08-31 16:50:39.529  5752  5752 E Zygote  : v2
08-31 16:50:39.529  5752  5752 I libpersona: KNOX_SDCARD checking this for 5010
08-31 16:50:39.529  5752  5752 I libpersona: KNOX_SDCARD not a persona
,08-31 16:50:39.529  1159  1200 I ActivityManager: Start proc 5752:com.samsung.android.intelligenceservice2/5010 for broadcast-3 com.samsung.android.intelligenceservice2/com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor$BtConnectionReceiver
,08-31 16:50:39.539  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
08-31 16:50:39.539  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.539  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,08-31 16:50:39.539  5752  5752 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:39.539  1159  1622 D NtpTrustedTime: forceRefresh: no connectivity
,08-31 16:50:39.539  5752  5752 E Zygote  : accessInfo : 0
,08-31 16:50:39.539  5752  5752 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.intelligenceservice2 
,08-31 16:50:39.539  5693  5693 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@f67f03c
,08-31 16:50:39.549  5693  5693 D HeadsetProvider: setHeadsetDB - Can't find 300 for 44:78:3E:EB:95:XX
,08-31 16:50:39.549  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
08-31 16:50:39.549  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.549  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,08-31 16:50:39.559  5693  5693 I HeadsetProvider: setHeadsetDB - 44:78:3E:EB:95:XX, 300, 0, true
08-31 16:50:39.559  5752  5752 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:39.559  5752  5752 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:39.559  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
08-31 16:50:39.559  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.559  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,08-31 16:50:39.569  5693  5693 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@d39124b
08-31 16:50:39.569  5693  5693 D HeadsetProvider: setHeadsetDB - Can't find 400 for 44:78:3E:EB:95:XX
,08-31 16:50:39.569  1159  1988 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eefe2a u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{860dbfb 5752:com.samsung.android.intelligenceservice2/5010}
,08-31 16:50:39.569  5693  5693 I HeadsetProvider: setHeadsetDB - 44:78:3E:EB:95:XX, 400, 1, true
,08-31 16:50:39.569  5693  5750 D HeadsetStateMachine: Enter Disconnected: -2, size: 0/0
,08-31 16:50:39.569  5693  5693 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Message sending
08-31 16:50:39.569  5693  5693 E HeadsetService: notifyProfileServiceStateChanged
,08-31 16:50:39.579  1159  1159 D BluetoothA2dp: Proxy object connected
08-31 16:50:39.579  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
08-31 16:50:39.579  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.579  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
08-31 16:50:39.579  2545  2545 D BluetoothA2dp: Proxy object connected
,08-31 16:50:39.579  5693  5693 D A2dpService: Received start request. Starting profile...
08-31 16:50:39.579  5693  5693 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7a2026b
,08-31 16:50:39.579  5693  5693 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-31 16:50:39.579  5693  5750 D HeadsetStateMachine: Clear mHeadsetBrsf
08-31 16:50:39.579  5693  5750 D HeadsetStateMachine: map size, before remove : 0
08-31 16:50:39.579  5693  5693 I bt_bluedroid: get_profile_interface avrcp
08-31 16:50:39.579  5693  5750 D HeadsetStateMachine: map size, after remove: 0
,08-31 16:50:39.579  5752  5752 W System  : ClassLoader referenced unknown path: /system/priv-app/intelligenceservice2/lib/arm64
,08-31 16:50:39.579  5693  5693 I Avrcp   : No of Audio players :: 1
08-31 16:50:39.579  5693  5693 I Avrcp   : App Package name is GM
,08-31 16:50:39.589  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
08-31 16:50:39.589  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.589  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,08-31 16:50:39.589  5752  5752 D UserAnalysis.Provider: PlaceProvider onCreate()
,08-31 16:50:39.599  5693  5693 V Avrcp   : MediaPlayerInfo: mPlayerId=1
,08-31 16:50:39.599  5693  5693 I Avrcp   : No of Video players :: 2
08-31 16:50:39.599  5693  5693 I Avrcp   : Video App Package name is others
,08-31 16:50:39.599  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
08-31 16:50:39.599  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.599  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,08-31 16:50:39.619  5752  5752 D UserAnalysis.Secu: Key for secure DB is newly created
,08-31 16:50:39.629  5752  5752 D UserAnalysis.SDBH: SecurePlaceDbHelper() 
08-31 16:50:39.629  5752  5752 D UserAnalysis: Create SecureDbHelper
08-31 16:50:39.629  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
08-31 16:50:39.629  5737  5738 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
08-31 16:50:39.629  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
,08-31 16:50:39.629  1159  1624 D wifi    : Can not initialize the vendor function pointer table
08-31 16:50:39.629  1159  1624 E WifiNative-HAL: Could not start hal
08-31 16:50:39.629  1159  1624 E WifiStateMachine: Failed to start HAL
,08-31 16:50:39.629  1159  1624 E WifiHW  : supplicant_name : p2p_supplicant
,08-31 16:50:39.639  1159  2558 W ActivityManager: Permission Denial: getCurrentUser() from pid=5752, uid=5010 requires android.permission.INTERACT_ACROSS_USERS
,08-31 16:50:39.639  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
08-31 16:50:39.639  5752  5752 D UserAnalysis.App: onCreate()
08-31 16:50:39.639  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
,08-31 16:50:39.639  5752  5752 D UserAnalysis.App: no applications having user consent for prediction
,08-31 16:50:39.639  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.639  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 10 : bytes_written: 10
08-31 16:50:39.649  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.649  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
,08-31 16:50:39.649  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,08-31 16:50:39.649  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
,08-31 16:50:39.649  1159  1202 I ActivityManager: Killing 5098:com.samsung.android.app.assistantmenu/1000 (adj 15): DHA:empty #31
,08-31 16:50:39.649  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
08-31 16:50:39.649  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
,08-31 16:50:39.649  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
08-31 16:50:39.649  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
,08-31 16:50:39.649  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
08-31 16:50:39.649  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
08-31 16:50:39.649  1159  1202 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eefe2a u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d5ab7b3 5693:com.android.bluetooth/1002}
08-31 16:50:39.649  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
08-31 16:50:39.649  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
,08-31 16:50:39.659  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,08-31 16:50:39.659  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
08-31 16:50:39.659  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
08-31 16:50:39.659  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
,08-31 16:50:39.659  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
08-31 16:50:39.659  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
08-31 16:50:39.659  5693  5693 V Avrcp   : MediaPlayerInfo: mPlayerId=2
08-31 16:50:39.659  5693  5693 I Avrcp   : Video App Package name is VP
,08-31 16:50:39.659  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
08-31 16:50:39.659  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
,08-31 16:50:39.659  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
08-31 16:50:39.659  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
,08-31 16:50:39.659  5693  5693 V Avrcp   : MediaPlayerInfo: mPlayerId=3
08-31 16:50:39.659  5693  5693 I Avrcp   : Add tempPlayer
08-31 16:50:39.659  5693  5693 V Avrcp   : MediaPlayerInfo: mPlayerId=4
08-31 16:50:39.659  5693  5693 V Avrcp   : no_of_players : 4
08-31 16:50:39.659  5693  5693 I Avrcp   : Total no of players: 4
08-31 16:50:39.659  5693  5693 V Avrcp   : Samsung player is the 1st player
08-31 16:50:39.659  5693  5693 D Avrcp   : Compose Browsing Service Candidate
08-31 16:50:39.659  5693  5693 D Avrcp   : ResolveInfo info ResolveInfo{b940ad4 com.google.android.music/.browse.MediaBrowserService m=0x108000}
08-31 16:50:39.659  5693  5693 D Avrcp   : Initialize Media Controller
,08-31 16:50:39.659  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
08-31 16:50:39.659  1159  1978 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-31 16:50:39.659  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
08-31 16:50:39.659  1159  1978 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4312, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
08-31 16:50:39.659  1159  1978 D BatteryService: online:4, current avg:-178, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-671
08-31 16:50:39.659  1159  1159 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-31 16:50:39.659  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
08-31 16:50:39.659  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
,08-31 16:50:39.669  5752  5752 V PlaceDetection v1.0.29 : [PlaceDetection::stopService] Service stopped.
08-31 16:50:39.669  5693  5693 D Avrcp   : Get the Context Package Name: com.android.bluetooth
08-31 16:50:39.669  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
08-31 16:50:39.669  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,08-31 16:50:39.669  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
08-31 16:50:39.669  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
,08-31 16:50:39.669  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,08-31 16:50:39.669  5693  5693 E Avrcp   : getActiveSessions
08-31 16:50:39.669  5693  5693 D Avrcp   : pick active media Controller
08-31 16:50:39.669  5693  5693 D Avrcp   : Get the active Media Controller 
08-31 16:50:39.669  5693  5693 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-31 16:50:39.669  1705  1705 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-31 16:50:39.669  1705  1705 D PowerUI : priorPlugType = 2 mPlugType =  2
08-31 16:50:39.669  1705  1705 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 16:50:39.669  5693  5693 D A2dpStateMachine: make
08-31 16:50:39.669  5752  5752 V PlaceDetection v1.0.29 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-31 16:50:39.669  5693  5693 I bt_bluedroid: get_profile_interface a2dp
08-31 16:50:39.669  5693  5693 E bt_btif : warning : media task started media_task_refcnt 1 
08-31 16:50:39.669  5693  5693 E bt_btif : warning : no command pending, ignore ack
,08-31 16:50:39.679  5636  5690 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-31 16:50:39.679  5636  5690 I jxcore-log: 
,08-31 16:50:39.679  5693  5767 D A2dpStateMachine: Enter Disconnected: -2
,08-31 16:50:39.679  5693  5693 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Message sending
08-31 16:50:39.679  5693  5693 E A2dpService: notifyProfileServiceStateChanged
08-31 16:50:39.679  5693  5693 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 16:50:39.679  1159  2367 V AlarmManager:  remove PendingIntent] PendingIntent{1ea5aa9: PendingIntentRecord{1e482e com.samsung.android.intelligenceservice2 broadcastIntent}}
,08-31 16:50:39.679  5693  5693 D HidService: Received start request. Starting profile...
08-31 16:50:39.679  5693  5693 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7a2026b
08-31 16:50:39.679  5693  5693 I bt_bluedroid: get_profile_interface hidhost
08-31 16:50:39.679  5693  5693 D HidService: setHidService(): set to: null
08-31 16:50:39.679  5693  5693 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Message sending
08-31 16:50:39.679  5693  5693 E HidService: notifyProfileServiceStateChanged
08-31 16:50:39.679  5693  5693 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-31 16:50:39.679  5693  5693 D HealthService: Received start request. Starting profile...
08-31 16:50:39.679  5693  5693 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7a2026b
,08-31 16:50:39.679  5693  5693 I bt_bluedroid: get_profile_interface health
08-31 16:50:39.679  5693  5693 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Message sending
08-31 16:50:39.679  5693  5693 E HealthService: notifyProfileServiceStateChanged
,08-31 16:50:39.679  5693  5693 I BluetoothPanServiceJni: classInitNative(L113): succeeds
,08-31 16:50:39.689  1159  1159 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 16:50:39.689  5498  5498 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 16:50:39.689  5693  5693 D PanService: Received start request. Starting profile...
08-31 16:50:39.689  5693  5693 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7a2026b
08-31 16:50:39.689  5498  5498 D PanProfile: Bluetooth service connected
08-31 16:50:39.689  5693  5693 D BluetoothPanServiceJni: initializeNative(L118): pan
08-31 16:50:39.689  5693  5693 I bt_bluedroid: get_profile_interface pan
,08-31 16:50:39.689  5693  5693 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Message sending
08-31 16:50:39.689  5693  5693 E PanService: notifyProfileServiceStateChanged
,08-31 16:50:39.689  5693  5693 D BluetoothMapService: Received start request. Starting profile...
08-31 16:50:39.689  5693  5693 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7a2026b
,08-31 16:50:39.689  5693  5693 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Message sending
08-31 16:50:39.689  5693  5693 E BluetoothMapService: notifyProfileServiceStateChanged
08-31 16:50:39.689  1705  1705 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
08-31 16:50:39.689  1705  1705 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
08-31 16:50:39.689  1705  1705 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 16:50:39.689  1705  1705 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-31 16:50:39.689  1705  1705 D PanProfile: Bluetooth service connected
,08-31 16:50:39.689  5693  5693 V SapService: SapBinder()
,08-31 16:50:39.699  5498  5498 D BluetoothSap: Proxy object connected
,08-31 16:50:39.699  5693  5693 D SapService: Received start request. Starting profile...
08-31 16:50:39.699  5498  5498 D SapProfile: Bluetooth service connected
08-31 16:50:39.699  5693  5693 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7a2026b
08-31 16:50:39.699  1705  1705 D BluetoothSap: Proxy object connected
08-31 16:50:39.699  5693  5693 V SapService: start()
08-31 16:50:39.699  1705  1705 D SapProfile: Bluetooth service connected
,08-31 16:50:39.699  5693  5693 V SapService: SAP UUID disabled
08-31 16:50:39.699  5693  5693 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Message sending
08-31 16:50:39.699  5693  5693 E SapService: notifyProfileServiceStateChanged
,08-31 16:50:39.699  5765  5765 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-31 16:50:39.699  5765  5765 I wpa_supplicant: Successfully initialized wpa_supplicant
08-31 16:50:39.699  5765  5765 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x20000), vendorssid_list()
,08-31 16:50:39.699  5765  5765 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-31 16:50:39.699  5693  5693 D HeadsetStateMachine: Try to query the phonestate on bind
,08-31 16:50:39.699  1159  1727 I BluetoothPhoneService: queryPhoneState
08-31 16:50:39.699  1159  1727 I BluetoothPhoneService: updateHeadsetWithCallState : true
,08-31 16:50:39.699  5693  5693 D HeadsetStateMachine: Proxy object connected
,08-31 16:50:39.709  5693  5693 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-31 16:50:39.709  5693  5693 D HeadsetPhoneState: sendDeviceDataStateChanged
08-31 16:50:39.709  5693  5750 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-31 16:50:39.709  5693  5750 E HeadsetStateMachine: Unknown message: 11
08-31 16:50:39.709  5693  5693 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-31 16:50:39.709  5693  5693 E BluetoothAdapterService: handleMessage() - Message: 1
08-31 16:50:39.709  5693  5750 D HeadsetStateMachine: Disconnected process message: 19, size: 0
08-31 16:50:39.709  5693  5750 E HeadsetStateMachine: Unknown message: 19
08-31 16:50:39.709  5693  5693 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Before synchronized
,08-31 16:50:39.709  5693  5693 V BluetoothAdapterState: isTurningOff()=false
08-31 16:50:39.709  5693  5693 V BluetoothAdapterState: isTurningOn()=true
08-31 16:50:39.709  5693  5693 V BluetoothAdapterState: isBleTurningOn()=false
08-31 16:50:39.709  5693  5693 V BluetoothAdapterState: isBleTurningOff()=false
08-31 16:50:39.709  5693  5693 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 16:50:39.709  5693  5750 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-31 16:50:39.709  5693  5750 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 16:50:39.709  5693  5750 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-31 16:50:39.709  5693  5750 E HeadsetStateMachine: Unknown message: 11
08-31 16:50:39.709  5693  5693 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 16:50:39.709  5693  5693 E BluetoothAdapterService: handleMessage() - Message: 1
08-31 16:50:39.709  5693  5693 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Before synchronized
08-31 16:50:39.709  5693  5750 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-31 16:50:39.709  5693  5693 V BluetoothAdapterState: isTurningOff()=false
08-31 16:50:39.709  5693  5693 V BluetoothAdapterState: isTurningOn()=true
08-31 16:50:39.709  5693  5693 V BluetoothAdapterState: isBleTurningOn()=false
08-31 16:50:39.709  5693  5693 V BluetoothAdapterState: isBleTurningOff()=false
08-31 16:50:39.709  5693  5693 E BluetoothAdapterService: handleMessage() - Message: 1
08-31 16:50:39.709  5693  5693 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Before synchronized
08-31 16:50:39.709  5693  5693 V BluetoothAdapterState: isTurningOff()=false
08-31 16:50:39.709  5693  5693 V BluetoothAdapterState: isTurningOn()=true
08-31 16:50:39.709  5693  5693 V BluetoothAdapterState: isBleTurningOn()=false
08-31 16:50:39.709  5693  5693 V BluetoothAdapterState: isBleTurningOff()=false
08-31 16:50:39.709  5693  5693 D BluetoothAdapterService: HID Host service started
,08-31 16:50:39.719  5773  5773 E Zygote  : v2
08-31 16:50:39.719  5773  5773 I libpersona: KNOX_SDCARD checking this for 10089
08-31 16:50:39.719  5773  5773 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:39.719  5773  5773 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:39.719  5773  5773 E Zygote  : accessInfo : 0
08-31 16:50:39.719  1159  2313 I ActivityManager: Start proc 5773:com.google.android.apps.maps/u0a89 for broadcast-3 com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
08-31 16:50:39.719  5773  5773 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.maps 
,08-31 16:50:39.719  1705  2083 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
08-31 16:50:39.719  5693  5693 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 16:50:39.719  5498  5498 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
08-31 16:50:39.719  5693  5693 E BluetoothAdapterService: handleMessage() - Message: 1
08-31 16:50:39.719  5693  5693 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Before synchronized
,08-31 16:50:39.719  5693  5693 V BluetoothAdapterState: isTurningOff()=false
08-31 16:50:39.719  5693  5693 V BluetoothAdapterState: isTurningOn()=true
08-31 16:50:39.719  5693  5693 V BluetoothAdapterState: isBleTurningOn()=false
08-31 16:50:39.719  5693  5693 V BluetoothAdapterState: isBleTurningOff()=false
08-31 16:50:39.719  5693  5693 E BluetoothAdapterService: handleMessage() - Message: 1
08-31 16:50:39.719  5693  5693 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Before synchronized
,08-31 16:50:39.719  5693  5693 V BluetoothAdapterState: isTurningOff()=false
08-31 16:50:39.719  5693  5693 V BluetoothAdapterState: isTurningOn()=true
08-31 16:50:39.719  5693  5693 V BluetoothAdapterState: isBleTurningOn()=false
08-31 16:50:39.719  5693  5693 V BluetoothAdapterState: isBleTurningOff()=false
08-31 16:50:39.719  5693  5693 E BluetoothAdapterService: handleMessage() - Message: 1
08-31 16:50:39.719  5693  5693 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Before synchronized
08-31 16:50:39.719  5693  5693 V BluetoothAdapterState: isTurningOff()=false
08-31 16:50:39.719  5693  5693 V BluetoothAdapterState: isTurningOn()=true
08-31 16:50:39.719  5693  5693 V BluetoothAdapterState: isBleTurningOn()=false
08-31 16:50:39.719  5693  5693 V BluetoothAdapterState: isBleTurningOff()=false
08-31 16:50:39.719  5693  5693 E BluetoothAdapterService: handleMessage() - Message: 1
08-31 16:50:39.719  5693  5693 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Before synchronized
,08-31 16:50:39.719  5693  5693 V BluetoothAdapterState: isTurningOff()=false
08-31 16:50:39.719  5693  5693 V BluetoothAdapterState: isTurningOn()=true
08-31 16:50:39.719  5693  5693 V BluetoothAdapterState: isBleTurningOn()=false
08-31 16:50:39.719  5693  5693 V BluetoothAdapterState: isBleTurningOff()=false
08-31 16:50:39.719  5693  5693 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 16:50:39.719  5693  5693 D HeadsetPhoneState: sendDeviceDataStateChanged
08-31 16:50:39.719  5693  5706 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STARTED
08-31 16:50:39.719  5693  5750 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-31 16:50:39.719  5693  5750 E HeadsetStateMachine: Unknown message: 11
08-31 16:50:39.719  5693  5693 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-31 16:50:39.719  5693  5750 D HeadsetStateMachine: Disconnected process message: 19, size: 0
08-31 16:50:39.719  5693  5750 E HeadsetStateMachine: Unknown message: 19
,08-31 16:50:39.729  5498  5498 D BluetoothMap: Create BluetoothMap proxy object
08-31 16:50:39.729  5693  5706 E BluetoothServiceJni: enableBrEdrNative:
08-31 16:50:39.729  5693  5706 I bt_bluedroid: enable_bredr
,08-31 16:50:39.729  1705  2083 D BluetoothMap: Create BluetoothMap proxy object
,08-31 16:50:39.729  5693  5710 I bt_bta_hh: BTA_HhEnable sec_mask:0x24 p_cback:0xf3c23ca9
08-31 16:50:39.729  5693  5710 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x100048
08-31 16:50:39.729  5693  5710 D BluetoothAdapterProperties: Address is:44:78:3E:EB:95:EE
08-31 16:50:39.729  5693  5710 E BluetoothServiceJni: populateRssiValuesNative
08-31 16:50:39.729  5693  5710 I bt_bluedroid: getModelRssiValues
08-31 16:50:39.729  5693  5710 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-31 16:50:39.729  5693  5710 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
08-31 16:50:39.729  5693  5743 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
08-31 16:50:39.729  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
08-31 16:50:39.729  5737  5737 I WCNSS_FILTER: do_write: IBS write: fc
,08-31 16:50:39.729  1159  1950 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5098 ,hash=71919545 ,name=com.samsung.android.app.assistantmenu
08-31 16:50:39.729  1159  1950 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.assistantmenu, Auto Run ON
08-31 16:50:39.739  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,08-31 16:50:39.739  5765  5765 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-31 16:50:39.739  1159  1624 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-31 16:50:39.739   460   460 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 5765
08-31 16:50:39.739   460   460 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-31 16:50:39.739  5765  5765 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-31 16:50:39.739  5765  5765 I wpa_supplicant: ssSupport state is = 1
08-31 16:50:39.739  5765  5765 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-31 16:50:39.739  5765  5765 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-31 16:50:39.739   460   460 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 5765
08-31 16:50:39.739   460   460 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
08-31 16:50:39.739  5693  5743 D CODEC_IF_MOD: codec_open: codec_open
08-31 16:50:39.739  5693  5743 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
08-31 16:50:39.739  5693  5743 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
08-31 16:50:39.739  5693  5743 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
08-31 16:50:39.739  5693  5743 D CODEC_IF: codec_if_open: codec module opened (v0.1
08-31 16:50:39.739  5693  5743 D CODEC_IF: codec_if_close: codec_if_close hdl -283193340
08-31 16:50:39.739  5693  5743 D CODEC_IF_MOD: codec_close: codec_close
08-31 16:50:39.739  5693  5743 D CODEC_IF_MOD: codec_close: freed apt-x encoder
08-31 16:50:39.739  5693  5743 D         : Codec ==> check 44.1kHz mode : check_sshd_encoder_available:356
08-31 16:50:39.739  5693  5743 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
,08-31 16:50:39.749   717   717 I MSM-irqbalance: Discovered a new IRQ: 139
,08-31 16:50:39.749   717   717 I MSM-irqbalance: Decided to move IRQ270 from CPU1 to CPU3
,08-31 16:50:39.749  1159  1159 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
08-31 16:50:39.749  1159  1159 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
08-31 16:50:39.749  1159  1629 I WifiHs20Service: Message received 5011
08-31 16:50:39.749  5693  5743 D CODEC_IF_SSHD: codec_open: codec_open
08-31 16:50:39.749  5693  5743 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 44100
08-31 16:50:39.749  5693  5743 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
08-31 16:50:39.749  5693  5743 D CODEC_IF: codec_if_open: codec module opened (v0.1
08-31 16:50:39.749  5693  5743 D CODEC_IF: codec_if_close: codec_if_close hdl -388469376
08-31 16:50:39.749  5693  5743 D CODEC_IF_SSHD: codec_close: codec_close
08-31 16:50:39.749  5693  5743 D         : Codec ==> check 44.1kHz mode : check_sshd_encoder_available:356
08-31 16:50:39.749  5693  5743 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
08-31 16:50:39.749  5693  5743 D CODEC_IF_SSHD: codec_open: codec_open
08-31 16:50:39.749  5693  5743 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 44100
08-31 16:50:39.749  5693  5743 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
08-31 16:50:39.749  5693  5743 D CODEC_IF: codec_if_open: codec module opened (v0.1
08-31 16:50:39.749  5693  5743 D CODEC_IF: codec_if_close: codec_if_close hdl -388469376
08-31 16:50:39.749  5693  5743 D CODEC_IF_SSHD: codec_close: codec_close
08-31 16:50:39.749  5693  5743 D         : Codec ==> copy capability info [bta_av_co_audio_init:646]
,08-31 16:50:39.749  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
,08-31 16:50:39.749  5773  5773 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:39.749  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.749  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
08-31 16:50:39.749  1159  1632 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
08-31 16:50:39.749  5773  5773 D ActivityThread: Added TimaKeyStore provider
08-31 16:50:39.759  1943  1960 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
08-31 16:50:39.759  1705  1705 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 16:50:39.759  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.759  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
08-31 16:50:39.759  5765  5765 I SecureStorage: [INFO]: SPID(0x00000004)ss_id will be loaded by secure_storage_daemon: /system/bin/wpa_supplicant
08-31 16:50:39.759  1943  1960 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
08-31 16:50:39.759  1705  1705 D HotspotTile: onReceive : 2, 0
08-31 16:50:39.759  1159  1632 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,08-31 16:50:39.759  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.759  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
,08-31 16:50:39.759  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,08-31 16:50:39.759  5693  5710 D BluetoothAdapterProperties: Name is: Galaxy Tab S2
,08-31 16:50:39.759  1705  1705 D BluetoothMap: Proxy object connected
08-31 16:50:39.759  1705  1705 D MapProfile: Bluetooth service connected
08-31 16:50:39.759  1705  1705 D BluetoothMap: getConnectedDevices()
08-31 16:50:39.759  5636  5636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 16:50:39.759  1705  1705 D BluetoothMap: Bluetooth is Not enabled
,08-31 16:50:39.769  1159  1200 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eefe2a u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{81cb9eb 5773:com.google.android.apps.maps/u0a89}
,08-31 16:50:39.769  5693  5710 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 16:50:39.769  1159  1159 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
08-31 16:50:39.769  5693  5710 D BluetoothAdapterProperties: Scan Mode:20
08-31 16:50:39.769  5693  5710 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 16:50:39.769  5693  5710 E bt_btif : btif_handle_bluetooth_enable_evt
08-31 16:50:39.769  5498  5498 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
08-31 16:50:39.769  5693  5710 E bt_btif : ANT+ socket does not initialize.
,08-31 16:50:39.769  5693  5710 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-31 16:50:39.769  1705  2083 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
,08-31 16:50:39.769  5693  5710 D IOP_DB_BT: db_open: db_open : handle 4089184272l, read 18559 bytes onto local cache
08-31 16:50:39.769  5693  5710 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
08-31 16:50:39.769  5693  5710 D IOP_DB_BT: db_query: result 1
08-31 16:50:39.769  5693  5710 I         : iop_db_open: iop_db_open status 0
08-31 16:50:39.769  5693  5710 E BluetoothAdapterState: stateChangeCallback : 17
08-31 16:50:39.769  5693  5706 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STARTED
08-31 16:50:39.769  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 8 : bytes_written: 8
08-31 16:50:39.769  5693  5710 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 16:50:39.779  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.779  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 8 : bytes_written: 8
08-31 16:50:39.779  5636  5636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 16:50:39.779  5693  5706 D BluetoothAdapterProperties: ScanMode =  20
08-31 16:50:39.779  5693  5706 D BluetoothAdapterProperties: State =  11
,08-31 16:50:39.779  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.779  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
,08-31 16:50:39.779  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.779  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
08-31 16:50:39.779  1159  1202 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
08-31 16:50:39.779  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.779  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 8 : bytes_written: 8
08-31 16:50:39.779  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,08-31 16:50:39.779  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
,08-31 16:50:39.779  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.779  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
,08-31 16:50:39.779  1159  1950 D SecContentProvider: insert(), uri = 2
,08-31 16:50:39.779  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,08-31 16:50:39.779  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
08-31 16:50:39.779  5693  5710 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 16:50:39.779  5693  5710 D BluetoothAdapterProperties: Scan Mode:21
08-31 16:50:39.779  5693  5710 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 16:50:39.779  5693  5706 D BluetoothAdapterProperties: Setting state to 12
08-31 16:50:39.779  5693  5706 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-31 16:50:39.789  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.789  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
,08-31 16:50:39.789  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,08-31 16:50:39.789  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
,08-31 16:50:39.789  5636  5636 D BluetoothAdapter: STATE_ON
08-31 16:50:39.789  1705  2083 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
08-31 16:50:39.789  1705  1705 D BluetoothInputDevice: Proxy object connected
08-31 16:50:39.789  5498  5498 D BluetoothMap: Proxy object connected
08-31 16:50:39.789  1705  1705 D HidProfile: Bluetooth service connected
08-31 16:50:39.789  5498  5498 D MapProfile: Bluetooth service connected
08-31 16:50:39.789  5498  5498 D BluetoothMap: getConnectedDevices()
08-31 16:50:39.789  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.789  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
,08-31 16:50:39.789  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.789  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
08-31 16:50:39.789  5636  5636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-31 16:50:39.789  5773  5773 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
08-31 16:50:39.789  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.789  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 8 : bytes_written: 8
,08-31 16:50:39.799  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.799  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
08-31 16:50:39.799  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:39.799  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
,08-31 16:50:39.799  5498  5498 D BluetoothInputDevice: Proxy object connected
08-31 16:50:39.799  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,08-31 16:50:39.799  5636  5636 D BluetoothAdapter: STATE_ON
,08-31 16:50:39.799  5636  5636 D BluetoothAdapter: STATE_ON
,08-31 16:50:39.799  5498  5498 D HidProfile: Bluetooth service connected
08-31 16:50:39.799  5636  5636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-31 16:50:39.799  5693  5706 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 16:50:39.799  5693  5706 D BluetoothAdapterService: updateAdapterState state is 12
,08-31 16:50:39.799  5636  5636 D BluetoothAdapter: STATE_ON
,08-31 16:50:39.809  5693  5706 V BluetoothAdapterService: start opp service
,08-31 16:50:39.809  5636  5636 D BluetoothAdapter: STATE_ON
,08-31 16:50:39.809  5636  5636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-31 16:50:39.809  5693  5706 D BluetoothAdapterService: Autoconnection is available 
08-31 16:50:39.809  5693  5706 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-31 16:50:39.809  5693  5706 D BluetoothAdapterService: starting service from this receiver
08-31 16:50:39.809  2545  2557 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:50:39.809  2545  2557 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:50:39.809  5693  5706 D BluetoothAdapterService: BT on, init HID DEV count : 0
08-31 16:50:39.809  5693  5706 I BluetoothAdapterState: Entering OnState
08-31 16:50:39.819  5498  5509 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:50:39.819  5498  5509 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:50:39.819  1159  1402 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 16:50:39.819  5498  5508 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 16:50:39.819  1943  1960 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:50:39.819  1943  1960 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 16:50:39.819  1705  1718 D BluetoothPan: onBluetoothStateChange on: true
08-31 16:50:39.819  1159  1402 D BluetoothPan: onBluetoothStateChange on: true
08-31 16:50:39.819  1705  1705 D BluetoothPbap: Proxy object connected
08-31 16:50:39.819  5498  5498 D BluetoothPbap: Proxy object connected
,08-31 16:50:39.819  5636  5636 D BluetoothAdapter: STATE_ON
08-31 16:50:39.829  1159  1159 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 16:50:39.819  5498  5498 D PbapServerProfile: Bluetooth service connected
08-31 16:50:39.829  1159  1159 I InputMethodManagerService: [BT Setting State] State =12
08-31 16:50:39.819  1705  1705 D PbapServerProfile: Bluetooth service connected
08-31 16:50:39.829  1159  1159 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-31 16:50:39.819  5498  5508 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 16:50:39.819  5693  5693 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-31 16:50:39.819  1878  1900 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:50:39.819  1878  1900 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 16:50:39.819  5498  5509 D BluetoothPan: onBluetoothStateChange on: true
08-31 16:50:39.819  5636  5636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 16:50:39.819  5636  5636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:50:39.819  5636  5636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 16:50:39.819  5636  5636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 16:50:39.819  5636  5636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 16:50:39.819  5636  5636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:50:39.819  5636  5636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:50:39.819  5636  5636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 16:50:39.819  5498  5508 D BluetoothSap: onBluetoothStateChange: up=true
08-31 16:50:39.819  1705  1722 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 16:50:39.819  5693  5703 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:50:39.819  5693  5703 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 16:50:39.819  5636  5636 D BluetoothAdapter: STATE_ON
08-31 16:50:39.829  5636  5647 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:50:39.829  5636  5647 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 16:50:39.829  2545  2557 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 16:50:39.829  5498  5509 D BluetoothMap: onBluetoothStateChange: up=true
08-31 16:50:39.829  5636  5636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 16:50:39.829  1705  2173 D BluetoothMap: onBluetoothStateChange: up=true
08-31 16:50:39.829  1159  1402 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:50:39.829  1159  1402 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 16:50:39.829  1705  1718 D BluetoothSap: onBluetoothStateChange: up=true
08-31 16:50:39.829  1705  1722 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:50:39.829  1705  1722 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 16:50:39.829  1705  2173 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 16:50:39.829  2030  2030 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:50:39.829  1705  2083 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:50:39.829  1705  2083 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
08-31 16:50:39.829  1159  1159 D BluetoothPhoneService: Bluetooth Adapter state : 12
08-31 16:50:39.829  1159  1159 I BluetoothPhoneService: queryPhoneState
08-31 16:50:39.829  1159  1159 I BluetoothPhoneService: updateHeadsetWithCallState : true
,08-31 16:50:39.839  1159  1159 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
08-31 16:50:39.839  1159  1159 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:50:39.839  1159  1159 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
08-31 16:50:39.839  5498  5498 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:50:39.839  5498  5498 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-31 16:50:39.839  1159  1950 W ActivityManager: Permission Denial: getCurrentUser() from pid=5773, uid=10089 requires android.permission.INTERACT_ACROSS_USERS
,08-31 16:50:39.839  5636  5636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 16:50:39.839  1705  2083 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-31 16:50:39.839  5498  5498 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-31 16:50:39.849  5693  5693 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
08-31 16:50:39.849  5693  5693 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
08-31 16:50:39.849  5693  5693 V BtOppService: isOwner == true
,08-31 16:50:39.849  1705  2083 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-31 16:50:39.849  5498  5498 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 16:50:39.849  1705  2083 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-31 16:50:39.849  1705  1705 D BluetoothA2dp: Proxy object connected
08-31 16:50:39.849  1705  1705 D A2dpProfile: Bluetooth service connected
08-31 16:50:39.849  5498  5498 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-31 16:50:39.859  5693  5704 D A2dpStateMachine: getConnectedDevices : size=0
,08-31 16:50:39.859  1705  2083 E BluetoothHeadset: BTStateChangeCB is registed
,08-31 16:50:39.859  5498  5498 E BluetoothHeadset: BTStateChangeCB is registed
,08-31 16:50:39.859  1705  2083 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
08-31 16:50:39.859  5498  5498 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
08-31 16:50:39.859  5498  5498 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
08-31 16:50:39.859  5498  5498 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
08-31 16:50:39.859  5498  5498 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
08-31 16:50:39.859  1705  2083 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
08-31 16:50:39.859  1705  2083 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
,08-31 16:50:39.859  1705  2083 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
,08-31 16:50:39.869  1705  2113 D BluetoothTile: handleUpdateState :  supported = true, enabled = true, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
,08-31 16:50:39.869  1159  2367 D StatusBarManagerService: setIcon slot=bluetooth index=18 icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0204c1) visible user=0 )
08-31 16:50:39.869  5498  5498 D BluetoothA2dp: Proxy object connected
,08-31 16:50:39.869  5498  5498 D A2dpProfile: Bluetooth service connected
08-31 16:50:39.869  1159  1202 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-31 16:50:39.879  5693  5749 D A2dpStateMachine: getConnectedDevices : size=0
08-31 16:50:39.879  5693  5693 I BluetoothPbapService: Handler(): got msg=1
,08-31 16:50:39.879  1159  1727 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-31 16:50:39.879  5693  5791 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-31 16:50:39.889  5693  5791 D BluetoothSocket: bindListen(): myUserId = 0
08-31 16:50:39.889  5693  5791 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 16:50:39.899  5792  5792 E Zygote  : v2
08-31 16:50:39.899  5792  5792 I libpersona: KNOX_SDCARD checking this for 10034
08-31 16:50:39.899  5792  5792 E Zygote  : isSdpEnabledProcess - SDP enabled
08-31 16:50:39.899  5792  5792 I libpersona: KNOX_SDCARD not a persona
,08-31 16:50:39.899  5792  5792 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:39.899  1159  1976 I ActivityManager: Start proc 5792:com.samsung.android.email.provider/u0a34 for content provider com.samsung.android.email.provider/.provider.database.EmailProvider
08-31 16:50:39.899  5792  5792 E Zygote  : accessInfo : 64
08-31 16:50:39.899  5792  5792 E Zygote  : isSdpEnabledProcess - SDP enabled
08-31 16:50:39.899  5792  5792 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10034 / [uid]: 10034
,08-31 16:50:39.899  5792  5792 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider 
,08-31 16:50:39.899  5693  5791 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-31 16:50:39.899  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
08-31 16:50:39.899  5737  5737 I WCNSS_FILTER: do_write: IBS write: fc
08-31 16:50:39.909  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,08-31 16:50:39.929  5792  5792 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:39.929  5792  5792 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:39.929  1159  1159 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@408838f
08-31 16:50:39.929  1159  1159 D BluetoothHeadset: registerMessageListener
,08-31 16:50:39.929  5693  5704 D A2dpStateMachine: getConnectedDevices : size=0
,08-31 16:50:39.929  5693  5788 D HeadsetService: registerMessageListener
08-31 16:50:39.929  5693  5788 D HeadsetService: registerMessageListener
08-31 16:50:39.929  1159  1159 I Telecom : BluetoothManager : register MessageListener
08-31 16:50:39.929  1159  1159 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
08-31 16:50:39.929  5693  5750 D HeadsetStateMachine: Disconnected process message: 70, size: 0
08-31 16:50:39.929  5693  5750 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@6ba8688
,08-31 16:50:39.949  5773  5806 W System.err: mkdir failed: EEXIST (File exists) : /storage/emulated/0/Android/data/com.google.android.apps.maps/testdata
,08-31 16:50:39.949  5773  5806 W System.err: mkdir failed: EEXIST (File exists) : /data/user/0/com.google.android.apps.maps/app_/testdata
,08-31 16:50:39.959  5773  5806 W System.err: mkdir failed: EEXIST (File exists) : /storage/emulated/0/Android/data/com.google.android.apps.maps/cache
,08-31 16:50:39.959  1705  1705 D HeadsetProfile: Bluetooth service connected
,08-31 16:50:39.959  5498  5498 D HeadsetProfile: Bluetooth service connected
,08-31 16:50:39.989  5636  5690 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-31 16:50:39.989  5636  5690 I jxcore-log: 
,08-31 16:50:40.009  5636  5690 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-31 16:50:40.009  5636  5690 I jxcore-log: 
,08-31 16:50:40.019  5792  5792 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_M/lib/arm64
,08-31 16:50:40.039  1159  1724 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 16:50:40.039  1159  1978 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 16:50:40.069  1159  1724 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 16:50:40.099  1159  1727 I ActivityManager: Killing 4802:com.samsung.android.sm/1000 (adj 15): DHA:empty #31
08-31 16:50:40.109  1159  1200 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-31 16:50:40.099  1159  1727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e792ffa u-1 android.net.conn.TETHER_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{37f90f5 1159:system/1000}
08-31 16:50:40.109  1159  1366 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b93c9ab u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{81082f1 5636:com.test.thalitest/u0a136}
08-31 16:50:40.119  1159  2558 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.119  1159  2558 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.119  1159  2558 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.119  1159  2558 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.119  1159  2558 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.119  1159  2558 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.119  1159  2558 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.119  1159  2558 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.119  1159  2558 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.119  1159  2558 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.119  1159  2558 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.119  1159  2558 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.119  1159  2558 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.119  115,9  2558 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.119  1159  2558 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:50:40.119  1159  1202 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa12808 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{796a31c 5498:com.android.settings/1000}
,08-31 16:50:40.119   460   460 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,08-31 16:50:40.129  5765  5765 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed
,08-31 16:50:40.129  5693  5693 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2) for masId0
,08-31 16:50:40.139  5830  5830 E Zygote  : v2
08-31 16:50:40.139  1159  1366 I ActivityManager: Start proc 5830:com.samsung.android.securitylogagent/1000 for broadcast-5 com.samsung.android.securitylogagent/.receivers.NetworkReceiver
08-31 16:50:40.139  5830  5830 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:50:40.139  5830  5830 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:40.139  5498  5498 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1311 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 16:50:40.139  5830  5830 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-31 16:50:40.139  5693  5829 D BluetoothSocket: bindListen(): myUserId = 0
08-31 16:50:40.139  5693  5829 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 16:50:40.139  5830  5830 E Zygote  : accessInfo : 0
,08-31 16:50:40.139  5773  5804 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-31 16:50:40.139  1159  1950 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa12808 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{efa98fc 2545:com.samsung.android.providers.context/u0a5}
,08-31 16:50:40.149  5693  5829 I BtOppRfcommListener: Accept thread started.
,08-31 16:50:40.149  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
08-31 16:50:40.149  5765  5765 I wpa_supplicant: Loading default cred
,08-31 16:50:40.149  5765  5765 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-31 16:50:40.149  5737  5737 I WCNSS_FILTER: do_write: IBS write: fc
08-31 16:50:40.149  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,08-31 16:50:40.149  1159  1950 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa12808 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ad7afc9 1878:com.google.android.gms.persistent/u0a10}
,08-31 16:50:40.149  1878  1878 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,08-31 16:50:40.149  5693  5693 D BluetoothSocket: bindListen(): myUserId = 0
08-31 16:50:40.149  5693  5693 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 16:50:40.159  5765  5765 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
08-31 16:50:40.159   460   460 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 5765
08-31 16:50:40.159   460   460 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-31 16:50:40.159  5765  5765 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-31 16:50:40.159  5765  5765 I wpa_supplicant: ssSupport state is = 1
,08-31 16:50:40.159  5765  5765 W wpa_supplicant: Loading system cred
08-31 16:50:40.169  5765  5765 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-31 16:50:40.169  5830  5830 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:40.169  5830  5830 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:40.169  1159  1200 I ActivityManager: Start proc 5847:com.sec.android.provider.badge/u0a1 for content provider com.sec.android.provider.badge/.BadgeProvider
,08-31 16:50:40.169  5847  5847 E Zygote  : v2
08-31 16:50:40.169  5847  5847 I libpersona: KNOX_SDCARD checking this for 10001
08-31 16:50:40.169  5847  5847 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:40.169  5847  5847 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-31 16:50:40.169  5847  5847 E Zygote  : accessInfo : 0
08-31 16:50:40.169  5847  5847 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.provider.badge 
08-31 16:50:40.169  1159  1988 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa12808 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{796a31c 5498:com.android.settings/1000}
,08-31 16:50:40.179  5498  5498 D DockEventReceiver: finishStartingService: stopping service
,08-31 16:50:40.179  5498  5498 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:50:40.179  5498  5498 D BluetoothStatusReceiver: AdapterStateChanged :: state = 12
,08-31 16:50:40.179  1159  1724 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b93c9ab u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f00aba1 5830:com.samsung.android.securitylogagent/1000}
,08-31 16:50:40.189  1159  1988 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa12808 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{860dbfb 5752:com.samsung.android.intelligenceservice2/5010}
,08-31 16:50:40.189  5765  5765 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
08-31 16:50:40.189   460   460 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 5765
08-31 16:50:40.189   460   460 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-31 16:50:40.189  5765  5765 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
,08-31 16:50:40.189  5765  5765 I wpa_supplicant: ssSupport state is = 1
08-31 16:50:40.189  5765  5765 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 16:50:40.189  5765  5765 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 16:50:40.189  5765  5765 I wpa_supplicant: [getIMSI]: sim_num 0
,08-31 16:50:40.189  5693  5693 D BluetoothSocket: bindListen(): myUserId = 0
08-31 16:50:40.189  5693  5693 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 16:50:40.189  1159  1988 I ActivityManager: Killing 5216:com.samsung.ipservice/5004 (adj 15): DHA:empty #31
,08-31 16:50:40.189  5765  5765 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 16:50:40.199  1159  1988 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa12808 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d5ab7b3 5693:com.android.bluetooth/1002}
,08-31 16:50:40.199   747  1447 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
08-31 16:50:40.199   747  1447 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
08-31 16:50:40.199   747  1443 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
08-31 16:50:40.199   747  1443 I QC-NETMGR-LIB: Processing RTM_NEWLINK
08-31 16:50:40.199   747  1443 I QC-NETMGR-LIB: Metainfo:  Index=13 Family=0 Type=0x1 Change=[0x1]UP  Flags=[0x1003]UP BROADCAST MULTICAST 
08-31 16:50:40.199   747  1443 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
08-31 16:50:40.199   555  1417 D Netd    : Iface wlan0 link down
08-31 16:50:40.199   747  1443 I QC-NETMGR-LIB: Received RTM_NEWLINK
08-31 16:50:40.199   747  1443 E QC-NETMGR-LIB: unrecognized ifindex 13, disable link
,08-31 16:50:40.199  5693  5693 D ObexServerSockets: Succeed to create listening sockets 
08-31 16:50:40.199  5693  5693 D ObexServerSockets: startAccept()
,08-31 16:50:40.199  5693  5693 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-31 16:50:40.199  5693  5693 D BluetoothSdpJni: SDP Create record success - handle: 0
08-31 16:50:40.199  5693  5693 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7a2026b
08-31 16:50:40.199  5693  5693 D BtConfig.SecureMode: isSecureModeOn:false
08-31 16:50:40.199  5737  5738 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
,08-31 16:50:40.199  5693  5860 D ObexServerSockets: Accepting socket connection for masId0
08-31 16:50:40.199  5847  5847 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:40.199  5847  5847 D ActivityThread: Added TimaKeyStore provider
08-31 16:50:40.199  5737  5737 I WCNSS_FILTER: do_write: IBS write: fc
08-31 16:50:40.199  5737  5737 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
08-31 16:50:40.209  1159  2558 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa12808 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{81cb9eb 5773:com.google.android.apps.maps/u0a89}
,08-31 16:50:40.209  5693  5861 D ObexServerSockets: Accepting socket connection for masId0
,08-31 16:50:40.219  1159  1988 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm, Auto Run ON
08-31 16:50:40.219  1159  1988 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=4802 ,hash=54630717 ,name=com.samsung.android.sm
,08-31 16:50:40.219  1159  1724 I ActivityManager: Killing 4840:com.samsung.dcmservice/5004 (adj 15): DHA:empty #31
,08-31 16:50:40.229  5847  5847 W System  : ClassLoader referenced unknown path: /system/priv-app/BadgeProvider_M/lib/arm64
,08-31 16:50:40.229  5847  5847 D BadgeProvider: onCreate
08-31 16:50:40.229  5847  5847 D BadgeProvider: DatabaseHelper
,08-31 16:50:40.229  4816  4816 I ServiceManager: [#CMH#] Disconnected to Service  com.samsung.dcmservice.DCMService
08-31 16:50:40.229  1159  2313 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcmservice, Auto Run ON
08-31 16:50:40.229  1159  2313 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=4840 ,hash=127054049 ,name=com.samsung.dcmservice
08-31 16:50:40.229  1159  2313 W ActivityManager: Scheduling restart of crashed service com.samsung.dcmservice/.DCMService in 1000ms
,08-31 16:50:40.239  5830  5830 W System  : ClassLoader referenced unknown path: /system/app/SecurityLogAgent/lib/arm64
,08-31 16:50:40.239  5847  5858 D BaseReflect: null getOwnClass TEST
,08-31 16:50:40.239  5847  5858 D MethodReflector: android.content.ContentResolver getClass TEST
08-31 16:50:40.239  5847  5858 D BaseReflect: class android.content.ContentResolver isSupportClass TEST
08-31 16:50:40.239  5847  5858 D BaseReflect: class android.content.ContentResolver getOwnClass TEST
,08-31 16:50:40.249  5847  5858 D MethodReflector: notifyChange is called
,08-31 16:50:40.249  1980  1980 D Launcher.Model: reloadBadges entered.
08-31 16:50:40.249  5847  5858 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
08-31 16:50:40.249  5847  5858 D BadgeProvider: sendNotify, [notify] : null
08-31 16:50:40.249  1980  1980 D Launcher.Model: reloadBadges entered.
,08-31 16:50:40.249  5847  5858 D BadgeProvider: update, getCallingPackage() : com.samsung.android.email.provider
08-31 16:50:40.249  5847  5858 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
08-31 16:50:40.249  5847  5858 D BadgeProvider: update, [uri.query] : null
08-31 16:50:40.249  5847  5858 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-31 16:50:40.249  5847  5858 D BadgeProvider: update, [UpdateCount] : 1
,08-31 16:50:40.249  5847  5858 D BadgeProvider: query, [selection] : null
,08-31 16:50:40.259  1980  2137 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
08-31 16:50:40.259  1980  2137 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
08-31 16:50:40.259  1980  2137 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
08-31 16:50:40.259  1980  2137 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
,08-31 16:50:40.259  1159  1724 I ActivityManager: Killing 5227:com.samsung.faceservice/5004 (adj 15): DHA:empty #31
,08-31 16:50:40.269  4816  4816 I ServiceManager: [#CMH#] Disconnected to Service  com.samsung.ipservice.IPService
08-31 16:50:40.269  1159  2313 D ActivityManager: isAutoRunBlockedApp:: com.samsung.ipservice, Auto Run ON
08-31 16:50:40.269  5847  5858 D BadgeProvider: query, [selection] : null
08-31 16:50:40.269  1159  2313 W ActivityManager: Scheduling restart of crashed service com.samsung.ipservice/.IPService in 10967ms
08-31 16:50:40.269  1159  2313 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5216 ,hash=252310905 ,name=com.samsung.ipservice
,08-31 16:50:40.269  1980  2137 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
08-31 16:50:40.269  1980  2137 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
08-31 16:50:40.269  1980  2137 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
08-31 16:50:40.269  1980  2137 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
,08-31 16:50:40.349  4816  4816 I ServiceManager: [#CMH#] Disconnected to Service  com.samsung.faceservice.FaceService
08-31 16:50:40.349  1159  1727 D ActivityManager: isAutoRunBlockedApp:: com.samsung.faceservice, Auto Run ON
08-31 16:50:40.349  1159  1727 W ActivityManager: Scheduling restart of crashed service com.samsung.faceservice/.FaceService in 20886ms
08-31 16:50:40.349  1159  1727 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5227 ,hash=90739308 ,name=com.samsung.faceservice
,08-31 16:50:40.449  5765  5765 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
,08-31 16:50:40.449  5765  5765 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-31 16:50:40.489  5765  5765 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,08-31 16:50:40.489   460   460 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 5765
,08-31 16:50:40.489   460   460 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-31 16:50:40.489  5765  5765 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-31 16:50:40.489  5765  5765 I wpa_supplicant: ssSupport state is = 1
,08-31 16:50:40.489  5765  5765 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 16:50:40.499   747  1447 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
08-31 16:50:40.499   555  1417 D Netd    : Iface p2p0 link down
08-31 16:50:40.499   747  1447 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
08-31 16:50:40.499   555  1417 D Netd    : Iface p2p0 link down
08-31 16:50:40.499   747  1447 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
08-31 16:50:40.499   747  1447 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
08-31 16:50:40.499   747  1443 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
08-31 16:50:40.499   747  1443 I QC-NETMGR-LIB: Processing RTM_NEWLINK
08-31 16:50:40.499   747  1443 I QC-NETMGR-LIB: Metainfo:  Index=14 Family=0 Type=0x1 Change=[0x1]UP  Flags=[0x1043]UP BROADCAST RUNNING MULTICAST 
08-31 16:50:40.499   747  1443 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
08-31 16:50:40.499   747  1443 I QC-NETMGR-LIB: Received RTM_NEWLINK
08-31 16:50:40.499   747  1443 E QC-NETMGR-LIB: unrecognized ifindex 14, disable link
08-31 16:50:40.499   747  1443 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
08-31 16:50:40.499   747  1443 I QC-NETMGR-LIB: Processing RTM_NEWLINK
08-31 16:50:40.499   747  1443 I QC-NETMGR-LIB: Metainfo:  Index=14 Family=0 Type=0x1 Change=[0x0] Flags=[0x1003]UP BROADCAST MULTICAST 
08-31 16:50:40.499   747  1443 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
08-31 16:50:40.499   747  1443 I QC-NETMGR-LIB: Received RTM_NEWLINK
08-31 16:50:40.499   747  1443 E QC-NETMGR-LIB: unrecognized ifindex 14, disable link
08-31 16:50:40.499   747  1447 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
08-31 16:50:40.499   747  1447 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
08-31 16:50:40.499   747  1443 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
,08-31 16:50:40.499   747  1443 I QC-NETMGR-LIB: Processing RTM_NEWLINK
08-31 16:50:40.499   747  1443 I QC-NETMGR-LIB: Metainfo:  Index=14 Family=0 Type=0x1 Change=[0x0] Flags=[0x1003]UP BROADCAST MULTICAST 
08-31 16:50:40.499   747  1443 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
08-31 16:50:40.499   747  1443 I QC-NETMGR-LIB: Received RTM_NEWLINK
08-31 16:50:40.499   747  1443 E QC-NETMGR-LIB: unrecognized ifindex 14, disable link
08-31 16:50:40.499   555  1417 D Netd    : Iface p2p0 link down
,08-31 16:50:40.669  5765  5765 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,08-31 16:50:40.679  1159  1624 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-31 16:50:40.679  1159  1624 E WifiStateMachine: Deffering msg in Supplicant Starting State131085
,08-31 16:50:40.679  1159  1624 D WifiNative-wlan0: callSECApiBoolean - ID [301]
,08-31 16:50:40.679  5765  5765 I wpa_supplicant: HOTSPOT20_ENABLE called ON
08-31 16:50:40.679  5765  5765 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 16:50:40.689  5765  5765 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-31 16:50:40.699  5765  5765 I wpa_supplicant: wlan0: Skip scan - bUseNetwork false
,08-31 16:50:40.699  1159  1624 D WifiNative-wlan0: callSECApiInt - ID [210]
,08-31 16:50:40.699  1159  1159 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
08-31 16:50:40.699  1159  1159 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
08-31 16:50:40.699  1159  1629 I WifiHs20Service: Message received 5011
08-31 16:50:40.699  1159  1626 D HS20StateMachine: WIFI_STATE_ENABLED
08-31 16:50:40.699  1159  1626 D HS20StateMachine: reloadCredentialsToSupplicant
08-31 16:50:40.699  1159  1626 D HotspotDBHandler: getCredentialIds
08-31 16:50:40.699  1159  1624 D WifiConfigStore: Loading config and enabling all networks 
08-31 16:50:40.709  1705  2083 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
08-31 16:50:40.709  1705  1705 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-31 16:50:40.709  1705  1705 D HotspotTile: onReceive : 3, 0
08-31 16:50:40.709  1159  1632 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
08-31 16:50:40.709  1705  2113 D QSTile.WifiTile: handleUpdateState  cb.changed 5 wifiEnabled : ON 
08-31 16:50:40.709  1943  2324 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
08-31 16:50:40.709  1943  2324 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
08-31 16:50:40.709  1159  1632 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,08-31 16:50:40.709  5636  5636 D BluetoothAdapter: STATE_ON
,08-31 16:50:40.719  1159  1366 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{39eee4c u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f00aba1 5830:com.samsung.android.securitylogagent/1000}
08-31 16:50:40.719  5636  5636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 16:50:40.719  5636  5636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:50:40.719  5636  5636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 16:50:40.719  5636  5636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 16:50:40.719  5636  5636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 16:50:40.719  5636  5636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:50:40.719  5636  5636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:50:40.719  5636  5636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 16:50:40.719  5636  5636 D BluetoothAdapter: STATE_ON
,08-31 16:50:40.719  5636  5636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 16:50:40.729  1159  1624 I WifiConfigStore: "NG700" is a verified password AP: true
,08-31 16:50:40.729  1159  1624 E WifiConfigStore: Not a HS20
,08-31 16:50:40.729  5867  5867 E Zygote  : v2
08-31 16:50:40.729  5867  5867 I libpersona: KNOX_SDCARD checking this for 10085
08-31 16:50:40.729  5867  5867 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:40.729  5867  5867 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:40.729  1159  1626 I ActivityManager: Start proc 5867:com.samsung.hs20provider/u0a85 for content provider com.samsung.hs20provider/.Hs20Provider
,08-31 16:50:40.729  1159  1624 D WifiConfigStore: loaded 0 passpoint configs
08-31 16:50:40.729  1159  1624 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-31 16:50:40.729  5867  5867 E Zygote  : accessInfo : 0
08-31 16:50:40.729  1705  1705 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 148
08-31 16:50:40.729  5867  5867 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
,08-31 16:50:40.739  1159  1624 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-31 16:50:40.739  1159  1624 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
08-31 16:50:40.739  1159  1624 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-31 16:50:40.739  1159  1624 D WifiConfigStore: setNetworkPriorityDefault: networkId = 0, priority = 1
08-31 16:50:40.739  1159  1159 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
08-31 16:50:40.739  1159  1159 D WifiHs20Service: reason: 2
08-31 16:50:40.739  1159  1629 I WifiHs20Service: Message received 5014
08-31 16:50:40.739  1159  1624 D WifiNative-wlan0: callSECApiInt - ID [65]
08-31 16:50:40.739  1159  1629 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
08-31 16:50:40.739  1159  1629 E WifiHs20Service: The changed config is NULL
,08-31 16:50:40.739  1159  1624 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-31 16:50:40.739  5765  5765 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-31 16:50:40.739  5765  5765 I wpa_supplicant: resume autoscan
08-31 16:50:40.739  1159  1200 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{39eee4c u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{81082f1 5636:com.test.thalitest/u0a136}
08-31 16:50:40.739  5765  5765 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
08-31 16:50:40.739  5765  5765 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
08-31 16:50:40.739  5765  5765 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-31 16:50:40.739  5765  5765 I wpa_supplicant: reset timer : RESET_TIMER 0
08-31 16:50:40.739  5765  5765 I wpa_supplicant: P2P: Current p2p state = IDLE
08-31 16:50:40.739  5765  5765 I wpa_supplicant: First Scan Start
08-31 16:50:40.739  5765  5765 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-31 16:50:40.739  1159  2367 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.739  1159  2367 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.739  1159  2367 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.739  1159  2367 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.739  1159  2367 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.739  1159  2367 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.739  1159  2367 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.739  1159  2367 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.739  1159  2367 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.739  1159  2367 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.739  1159  2367 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.739  1159  2367 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.739  1159  2367 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.739  1159  2367 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.739  1159  2367 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTE,D, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.749  1159  1624 D WifiNative-wlan0: Setting external_sim to 1
08-31 16:50:40.749  1159  1624 D WifiStateMachine: [setCountryCode()] Airplane mode return !!!
08-31 16:50:40.749  1159  1624 D WifiStateMachine: Setting OUI to DA-A1-19
,08-31 16:50:40.749  5765  5765 I wpa_supplicant: bt_status is set be DISCONNECTED
,08-31 16:50:40.749  1159  1624 E WifiNative-wlan0: do suspend true
,08-31 16:50:40.749  1159  1623 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-31 16:50:40.749  1159  1624 D WifiNative-HAL: Failing getSupportedFeatureset because HAL isn't started
08-31 16:50:40.759  1159  1649 E WifiScanningService: could not start HAL
,08-31 16:50:40.759  1159  1624 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-31 16:50:40.759  1159  1624 D WifiStateMachine: [FCC]Airplane on, setFccChannel(0)!!!
08-31 16:50:40.759  1159  1624 D WifiStateMachine: setFccChannelNative: channel = 0
08-31 16:50:40.759  1159  1624 D WifiNative-wlan0: callSECApiInt - ID [230]
,08-31 16:50:40.759  1159  1159 D RttService: SCAN_AVAILABLE : 3
08-31 16:50:40.759  1159  1650 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 16:50:40.759   555  1424 D CommandListener: Setting iface cfg
08-31 16:50:40.759   555  1424 D CommandListener: Trying to bring up p2p0
08-31 16:50:40.759  1159  1623 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-31 16:50:40.759  1159  1623 D SecContentProvider: insert(), uri = 2
,08-31 16:50:40.759  1159  1623 D WifiP2pService: P2pEnablingState
08-31 16:50:40.759  1159  1623 D WifiP2pService: P2pEnablingState{ what=147457 }
08-31 16:50:40.759  1159  1623 D WifiP2pService: P2p socket connection successful
08-31 16:50:40.759  1159  1623 D WifiP2pService: P2pEnabledState
08-31 16:50:40.759  1159  1623 D SecContentProvider: insert(), uri = 2
,08-31 16:50:40.759  5867  5867 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:40.759  5867  5867 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:40.769  1159  1624 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
08-31 16:50:40.769  1159  1159 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-31 16:50:40.769  1159  1403 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
08-31 16:50:40.769  1159  1403 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-31 16:50:40.769  1159  1403 D WifiDisplayController: disconnect
08-31 16:50:40.769  1159  1403 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 16:50:40.769  1159  1623 D WifiP2pService: sending p2p connection changed broadcast: IDLE
,08-31 16:50:40.769  1705  1705 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-31 16:50:40.769  1705  1705 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-31 16:50:40.769  1159  1623 D WifiP2pService: create mNetworkAgent
,08-31 16:50:40.769  1159  1623 D P2pNetworkAgent: NetworkAgent: Registering NetworkAgent
,08-31 16:50:40.769  1159  1624 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
08-31 16:50:40.769  1705  1705 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-31 16:50:40.769  1159  1200 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 16:50:40.769  1705  1705 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-31 16:50:40.779  1159  2133 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
08-31 16:50:40.779  1159  2133 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 3, Mac address valid: false, AP MAC address: [00:00:00:00:00:00], Wifi-Ap SSID Valid: false, SSID: 
,08-31 16:50:40.779  1159  2133 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
08-31 16:50:40.779  1159  2133 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 3, Mac address valid: false, AP MAC address: [00:00:00:00:00:00], Wifi-Ap SSID Valid: false, SSID: 
,08-31 16:50:40.779  1159  1623 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-31 16:50:40.779  1159  1631 E ConnectivityService: updateNetworkInfo()
08-31 16:50:40.779  1159  1631 D ConnectivityService: Got NetworkAgent Messenger
,08-31 16:50:40.779  1159  1631 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:50:40.779  1159  1631 D ConnectivityService: NetworkAgent connected
08-31 16:50:40.779  1159  1631 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } for legacy network type 13
08-31 16:50:40.779  5765  5765 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 512
,08-31 16:50:40.779  5765  5765 I wpa_supplicant: P2P: Set Samsung Discovery name = ,
,08-31 16:50:40.779  1159  1403 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:40.779  1705  1705 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-31 16:50:40.789  1159  1366 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{eaa150 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7813774 5343:com.samsung.android.app.FileShareServer/5005}
08-31 16:50:40.789  5343  5343 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 16:50:40.789  1943  1966 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
08-31 16:50:40.789  5343  5343 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,08-31 16:50:40.789  5343  5343 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,08-31 16:50:40.789  5867  5867 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm64
,08-31 16:50:40.799  1159  2367 W ActivityManager: Permission Denial: getCurrentUser() from pid=5867, uid=10085 requires android.permission.INTERACT_ACROSS_USERS
,08-31 16:50:40.809  5881  5881 E Zygote  : v2
08-31 16:50:40.809  5881  5881 I libpersona: KNOX_SDCARD checking this for 5005
08-31 16:50:40.809  5881  5881 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:40.809  1159  1366 I ActivityManager: Start proc 5881:com.samsung.android.app.FileShareClient/5005 for broadcast-5 com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver
,08-31 16:50:40.809  5881  5881 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:40.809  5867  5877 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
08-31 16:50:40.809  5867  5877 D HotspotProvider: CREDENTIAL
,08-31 16:50:40.809  5867  5877 D HotspotProvider: No prepend tags
08-31 16:50:40.809  5881  5881 E Zygote  : accessInfo : 0
08-31 16:50:40.809  1159  1623 E WifiP2pService: Failed to set my phone number info into probe response
08-31 16:50:40.809  5881  5881 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareClient 
,08-31 16:50:40.819  1159  1623 D WifiNative-p2p0: p2pGetDeviceAddress
,08-31 16:50:40.819  1159  1623 D WifiNative-p2p0: p2pGetDeviceAddress returning 46:78:3e:eb:95:ef
,08-31 16:50:40.819  1159  1623 D WifiP2pService: DeviceAddress: 46:95:ef
08-31 16:50:40.819  1159  1403 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Tablet] Galaxy Tab S2
08-31 16:50:40.819  1159  1403 D WifiDisplayController:  deviceAddress: 46:78:3e:eb:95:ef
08-31 16:50:40.819  1159  1403 D WifiDisplayController:  primary type: 1-0050F204-9
08-31 16:50:40.819  1159  1403 D WifiDisplayController:  secondary type: null
08-31 16:50:40.819  1159  1403 D WifiDisplayController:  wps: 0
08-31 16:50:40.819  1159  1403 D WifiDisplayController:  grpcapab: 0
08-31 16:50:40.819  1159  1403 D WifiDisplayController:  devcapab: 0
08-31 16:50:40.819  1159  1403 D WifiDisplayController:  status: 3
08-31 16:50:40.819  1159  1403 D WifiDisplayController:  wfdInfo: null
08-31 16:50:40.819  1159  1403 D WifiDisplayController:  groupownerAddress: null
08-31 16:50:40.819  1159  1403 D WifiDisplayController:  GOdeviceName: null
08-31 16:50:40.819  1159  1403 D WifiDisplayController:  interfaceAddress: 
08-31 16:50:40.819  1159  1403 D WifiDisplayController:  SConnectInfo : null
08-31 16:50:40.819  1159  1403 D WifiDisplayController:  contactInfoHash : null
08-31 16:50:40.819  1159  1403 D WifiDisplayController:  ssDevInfo : 0
08-31 16:50:40.819  1159  1403 D WifiDisplayController:  iconIdx : 0
,08-31 16:50:40.819  1159  1626 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
08-31 16:50:40.819  1159  1626 D HS20StateMachine: enter : DiscoveringState
08-31 16:50:40.819  1159  1159 I ActivityManager: Killing 4816:com.samsung.cmh:CMH/5004 (adj 15): DHA:empty #31
,08-31 16:50:40.829  1159  1623 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-31 16:50:40.839  1159  1623 D WifiP2pService: InactiveState
08-31 16:50:40.839  1159  1623 D P2pNetworkAgent: NetworkAgent: NetworkAgent fully connected
08-31 16:50:40.839  1159  1631 E ConnectivityService: updateNetworkInfo()
08-31 16:50:40.839  1159  1631 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = UNKNOWN
,08-31 16:50:40.839  1159  1623 D WifiP2pService: InactiveState{ what=143376 }
08-31 16:50:40.839  1159  1623 D WifiP2pService: P2pEnabledState{ what=143376 }
08-31 16:50:40.839  1159  1623 E WifiP2pService: Airplane mode : skipped SET_COUNTRY_CODE
,08-31 16:50:40.839  5881  5881 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:40.839  5881  5881 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:40.839  1159  1976 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{eaa150 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f6ef56f 5881:com.samsung.android.app.FileShareClient/5005}
,08-31 16:50:40.859  5881  5881 W System  : ClassLoader referenced unknown path: /system/app/AllshareFileShareClient/lib/arm64
,08-31 16:50:40.859  5881  5881 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 16:50:40.869  5881  5881 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-31 16:50:40.889  5881  5881 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 16:50:40.889  1159  2313 I ActivityManager: Killing 5020:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #31
,08-31 16:50:40.889  5636  5690 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-31 16:50:40.889  5636  5690 I jxcore-log: 
,08-31 16:50:40.909  1159  1724 D ActivityManager: isAutoRunBlockedApp:: com.samsung.cmh, Auto Run ON
,08-31 16:50:40.909  1159  1724 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=4816 ,hash=250780440 ,name=com.samsung.cmh:CMH
08-31 16:50:40.909  4863  4863 I StoryService: [StoryService] On destroy() 
08-31 16:50:40.909  4863  4863 I ServiceController: [StoryService] shutdown() 
,08-31 16:50:40.939  1159  1950 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5020 ,hash=43606391 ,name=com.sec.android.diagmonagent
08-31 16:50:40.939  1159  1950 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,08-31 16:50:41.029  5636  5690 I jxcore-log: ERROR runTests: 
08-31 16:50:41.029  5636  5690 I jxcore-log: 
,08-31 16:50:41.029  5636  5690 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-31 16:50:41.029  5636  5690 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-31 16:50:41.029  5636  5690 I jxcore-log: WARN testUtils: logCallback not set!
08-31 16:50:41.029  5636  5690 I jxcore-log: 
,08-31 16:50:41.029  5636  5690 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 16:50:41.029  5636  5690 I jxcore-log:     _functionName: 'loadFile',
08-31 16:50:41.029  5636  5690 I jxcore-log:     _lineNumber: '26',
08-31 16:50:41.029  5636  5690 I jxcore-log:     _columnNumber: '11',
08-31 16:50:41.029  5636  5690 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-31 16:50:41.029  5636  5690 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 16:50:41.029  5636  5690 I jxcore-log:     _functionName: '',
08-31 16:50:41.029  5636  5690 I jxcore-log:     _lineNumber: '38',
08-31 16:50:41.029  5636  5690 I jxcore-log:     _columnNumber: '7',
08-31 16:50:41.029  5636  5690 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-31 16:50:41.029  5636  5690 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 16:50:41.029  5636  5690 I jxcore-log:     _functionName: '',
08-31 16:50:41.029  5636  5690 I jxcore-log:     _lineNumber: '35',
08-31 16:50:41.029  5636  5690 I jxcore-log:     _columnNumber: '3',
08-31 16:50:41.029  5636  5690 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-31 16:50:41.029  5636  5690 I jxcore-log:   { _fileName: 'module.js',
08-31 16:50:41.029  5636  5690 I jxcore-log:     _functionName: '$w.prototype._compile',
08-31 16:50:41.029  5636  5690 I jxcore-log:     _lineNumber: '621',
08-31 16:50:41.029  5636  5690 I jxcore-log:     _columnNumber: '8',
08-31 16:50:41.029  5636  5690 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-31 16:50:41.029  5636  5690 I jxcore-log:   { _fileName: 'module.js',
08-31 16:50:41.029  5636  5690 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-31 16:50:41.029  5636  5690 I jxcore-log:     _lineNumber: '651',
08-31 16:50:41.029  5636  5690 I jxcore-log:     _columnNumber: '1',
08-31 16:50:41.029  5636  5690 I jxcore-log:    
08-31 16:50:41.029  5636  5690 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-31 16:50:41.029  5636  5690 I jxcore-log: 
08-31 16:50:41.029  5636  5690 E jxcore-log: Error: 
08-31 16:50:41.029  5636  5690 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-31 16:50:41.029  5636  5690 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-31 16:50:41.029  5636  5690 E jxcore-log: 
,08-31 16:50:41.029  5636  5690 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 16:50:41.029  5636  5690 I jxcore-log: 
08-31 16:50:41.039  5636  5690 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 16:50:41.039  5636  5690 I jxcore-log: 
,08-31 16:50:41.199  5737  5746 I WCNSS_FILTER: do_write: IBS write: fe
08-31 16:50:41.199  5737  5746 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,08-31 16:50:41.549  5893  5893 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-31 16:50:41.559  5893  5893 D AndroidRuntime: CheckJNI is OFF
,08-31 16:50:41.559  5893  5893 D AndroidRuntime: readGMSProperty: start
08-31 16:50:41.559  5893  5893 D AndroidRuntime: readGMSProperty: already setted!!
08-31 16:50:41.559  5893  5893 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-31 16:50:41.559  5893  5893 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-31 16:50:41.559  5893  5893 D AndroidRuntime: readGMSProperty: end
08-31 16:50:41.559  5893  5893 D AndroidRuntime: addProductProperty: start
,08-31 16:50:41.589  5893  5893 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-31 16:50:41.619  5893  5893 I Radio-JNI: register_android_hardware_Radio DONE
,08-31 16:50:41.619  5893  5893 E AffinityControl: AffinityControl: registerfunction enter
,08-31 16:50:41.639  5893  5893 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 16:50:41.649  1159  1976 D PackageManager: START PACKAGE DELETE: observer{65045116}
08-31 16:50:41.649  1159  1976 D PackageManager: pkg{<packageName>}
08-31 16:50:41.649  1159  1976 D PackageManager: user{0}
08-31 16:50:41.649  1159  1976 D PackageManager: caller{2000}
08-31 16:50:41.649  1159  1976 D PackageManager: flags{2}
08-31 16:50:41.649  1159  1976 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-31 16:50:41.649  1159  1976 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-31 16:50:41.649  1159  1976 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-31 16:50:41.649  1159  1976 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-31 16:50:41.649  1159  1976 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-31 16:50:41.649  1159  1426 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-31 16:50:41.659  1159  1426 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-31 16:50:41.659  1159  1426 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-31 16:50:41.659  1159  1426 D ApplicationPolicy: getApplicationUninstallationEnabled
08-31 16:50:41.659  1159  1426 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-31 16:50:41.659  1159  1426 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-31 16:50:41.659  1159  1426 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-31 16:50:41.659  1159  1426 D PackageManager: !@killApplicatoin: 10136, uninstall pkg
08-31 16:50:41.659  1159  1426 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-31 16:50:41.659  1159  1366 I ActivityManager: Force stopping com.test.thalitest appid=10136 user=-1: uninstall pkg
08-31 16:50:41.659  1159  1426 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-31 16:50:41.659  1159  1366 I ActivityManager: Killing 5636:com.test.thalitest/u0a136 (adj 1): stop com.test.thalitest cause uninstall pkg
08-31 16:50:41.659  1159  1366 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5636 ,hash=135299825 ,name=com.test.thalitest
,08-31 16:50:41.659  1159  1366 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-31 16:50:41.669  1159  1426 D AASAinstall: there is not AASApackages.xml file
,08-31 16:50:41.679  5903  5903 E Zygote  : v2
08-31 16:50:41.679  5903  5903 I libpersona: KNOX_SDCARD checking this for 10136
08-31 16:50:41.679  5903  5903 I libpersona: KNOX_SDCARD not a persona
,08-31 16:50:41.679  5903  5903 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-31 16:50:41.679  5903  5903 E Zygote  : accessInfo : 0
,08-31 16:50:41.679  5903  5903 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
,08-31 16:50:41.689  1159  1366 I ActivityManager: Start proc 5903:com.test.thalitest/u0a136 for activity com.test.thalitest/.MainActivity
,08-31 16:50:41.689  1159  1366 W VirtualScreenManagerService: moveTaskBackToDisplayIfNeeded(): top activity or app is null
08-31 16:50:41.689  1159  1366 I ActivityManager:   Force finishing activity ActivityRecord{2eca214 u0 com.test.thalitest/.MainActivity t18}
,08-31 16:50:41.689  1159  1366 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 56)
08-31 16:50:41.689   447   476 I SurfaceFlinger: id=15 Removed NainActivit (6/12)
,08-31 16:50:41.689   447   468 I SurfaceFlinger: id=15 Removed NainActivit (-2/12)
,08-31 16:50:41.709  5903  5903 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:41.709  5903  5903 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:41.819  5765  5765 I wpa_supplicant: nl80211: Received scan results (29 BSSes)
08-31 16:50:41.819  5765  5765 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
08-31 16:50:41.819  5765  5765 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
08-31 16:50:41.819  5765  5765 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-31 16:50:41.819  5765  5765 I wpa_supplicant:    allow  - level is under -85dBm [-47] or selected nid [-1] [0]
08-31 16:50:41.819  5765  5765 I wpa_supplicant:  selected from pick network BSS F4.99.3E ssid='NG700' et= 090,gp=03,cu=987654321,sc=987654321
08-31 16:50:41.819  5765  5765 I wpa_supplicant:    allow  - level is under -85dBm [-47] or selected nid [-1] [0]
08-31 16:50:41.819  5765  5765 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
08-31 16:50:41.819  1159  5864 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-31 16:50:41.829  1159  1978 D GraphicsStats: Buffer count: 5
08-31 16:50:41.829  1159  1976 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@3e8335a)
08-31 16:50:41.829   447   468 E         : BitTube(): close sendFd (40)
08-31 16:50:41.829  1159  1631 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:50:41.829   447   468 E         : BitTube(): close sendFd (41)
,08-31 16:50:41.829  1159  1631 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:50:41.829  1159  1631 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:50:41.899   747  1447 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 320
08-31 16:50:41.899   747  1447 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
08-31 16:50:41.899  5765  5765 E wpa_supplicant: Cmd 35605 not handled
08-31 16:50:41.899   747  1447 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 188
08-31 16:50:41.899   747  1447 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
08-31 16:50:41.899   747  1447 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 72
08-31 16:50:41.899   747  1447 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
08-31 16:50:41.899   747  1447 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
08-31 16:50:41.899   555  1417 D Netd    : Iface wlan0 link down
08-31 16:50:41.899   747  1447 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
08-31 16:50:41.899   747  1443 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
08-31 16:50:41.899   747  1443 I QC-NETMGR-LIB: Processing RTM_NEWLINK
08-31 16:50:41.899   747  1443 I QC-NETMGR-LIB: Metainfo:  Index=13 Family=0 Type=0x1 Change=[0x0] Flags=[0x1003]UP BROADCAST MULTICAST 
08-31 16:50:41.899   747  1443 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
08-31 16:50:41.899   747  1443 I QC-NETMGR-LIB: Received RTM_NEWLINK
08-31 16:50:41.899   747  1443 E QC-NETMGR-LIB: unrecognized ifindex 13, disable link
08-31 16:50:41.899   747  1443 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
08-31 16:50:41.899   747  1443 I QC-NETMGR-LIB: Processing RTM_NEWLINK
08-31 16:50:41.899   555  1417 D Netd    : Iface wlan0 link down
08-31 16:50:41.899   747  1443 I QC-NETMGR-LIB: Metainfo:  Index=13 Family=0 Type=0x1 Change=[0x0] Flags=[0x1003]UP BROADCAST MULTICAST 
08-31 16:50:41.899   747  1443 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
08-31 16:50:41.899   747  1443 I QC-NETMGR-LIB: Received RTM_NEWLINK
08-31 16:50:41.899   747  1443 E QC-NETMGR-LIB: unrecognized ifindex 13, disable link
08-31 16:50:41.899   555  1417 D Netd    : Iface wlan0 link down
08-31 16:50:41.899   747  1443 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
08-31 16:50:41.899   747  1443 I QC-NETMGR-LIB: Processing RTM_NEWLINK
08-31 16:50:41.899   747  1443 I QC-NETMGR-LIB: Metainfo:  Index=13 Family=0 Type=0x1 Change=[0x0] Flags=[0x1003]UP BROADCAST MULTICAST 
08-31 16:50:41.899   555  1417 D Netd    : Iface wlan0 link up
08-31 16:50:41.899   747  1443 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
08-31 16:50:41.899   747  1443 I QC-NETMGR-LIB: Received RTM_NEWLINK
08-31 16:50:41.899   747  1443 E QC-NETMGR-LIB: unrecognized ifindex 13, disable link
08-31 16:50:41.899   747  1443 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
08-31 16:50:41.899   747  1443 I QC-NETMGR-LIB: Processing RTM_NEWLINK
08-31 16:50:41.899   747  1443 I QC-NETMGR-LIB: Metainfo:  Index=13 Family=0 Type=0x1 Change=[0x0] Flags=[0x11003]UP BROADCAST MULTICAST LOWER_UP 
08-31 16:50:41.899   747  1443 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
08-31 16:50:41.899   747  1443 I QC-NETMGR-LIB: Received RTM_NEWLINK
08-31 16:50:41.899   747  1443 E QC-NETMGR-LIB: unrecognized ifindex 13, disable link
,08-31 16:50:41.899  1159  1402 D Tethering: enter TetherInterfaceSM  and send tetherstatechangebroadcast
,08-31 16:50:41.899  5765  5765 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-31 16:50:41.939  5765  5765 I wpa_supplicant: wlan0: WPA: RX message 1 of 4-Way Handshake from F4.99.3E (ver=2)
,08-31 16:50:41.939  5765  5765 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 2/4
,08-31 16:50:41.949  1159  1426 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-31 16:50:41.949  5765  5765 I wpa_supplicant: wlan0: WPA: RX message 3 of 4-Way Handshake from F4.99.3E (ver=2)
08-31 16:50:41.949  5765  5765 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 4/4
,08-31 16:50:41.949  5765  5765 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 16:50:41.949  5765  5765 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-31 16:50:41.949   747  1447 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
08-31 16:50:41.949   747  1447 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
08-31 16:50:41.949   555  1417 D Netd    : Iface wlan0 link up
,08-31 16:50:41.949   747  1443 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
08-31 16:50:41.949   747  1443 I QC-NETMGR-LIB: Processing RTM_NEWLINK
08-31 16:50:41.949  5765  5765 I wpa_supplicant: Blacklist: Clear (temp) 
08-31 16:50:41.949   747  1443 I QC-NETMGR-LIB: Metainfo:  Index=13 Family=0 Type=0x1 Change=[0x0] Flags=[0x11043]UP BROADCAST RUNNING MULTICAST LOWER_UP 
08-31 16:50:41.949   747  1443 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
08-31 16:50:41.949   747  1443 I QC-NETMGR-LIB: Received RTM_NEWLINK
08-31 16:50:41.949   747  1443 E QC-NETMGR-LIB: unrecognized ifindex 13, disable link
,08-31 16:50:42.019  1159  1426 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-31 16:50:42.019  1159  1402 D Tethering: NAP Supported and not Wifi Model
,08-31 16:50:42.029   568   568 W keystore: ENTER clear_uid from uid 1000 for 10136
08-31 16:50:42.029  1159  1402 E Tethering: No numeric data
08-31 16:50:42.029  1159  1988 I ActivityManager: Killing 4987:com.wssyncmldm/1000 (adj 15): DHA:empty #31
,08-31 16:50:42.029  1159  1402 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-31 16:50:42.029  1159  1426 I art     : Starting a blocking GC Explicit
,08-31 16:50:42.039  1159  1621 D NtpTrustedTime: forceRefresh: no connectivity
,08-31 16:50:42.039  1159  1621 V NetworkStats: performPollLocked(flags=0x1)
,08-31 16:50:42.039  1159  1621 V NetworkStats: performPollLocked() took 2ms
,08-31 16:50:42.039  1705  1705 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 16:50:42.039  1705  1705 D HotspotTile: updateTetherState():false, false
,08-31 16:50:42.039  1159  1366 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a7e91bd u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{358d09d 1705:com.android.systemui/u0a46}
,08-31 16:50:42.039  1159  1622 D NtpTrustedTime: forceRefresh: no connectivity
,08-31 16:50:42.049  1159  1724 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d79d3b2 u-1 android.net.conn.TETHER_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{37f90f5 1159:system/1000}
,08-31 16:50:42.049  1159  1624 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-31 16:50:42.059  5903  5903 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
08-31 16:50:42.059  5903  5903 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
,08-31 16:50:42.059  5903  5903 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
08-31 16:50:42.059  5903  5903 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
,08-31 16:50:42.059  1159  1624 V AlarmManager:  remove PendingIntent] PendingIntent{90b8f03: PendingIntentRecord{3878cb9 android broadcastIntent}}
,08-31 16:50:42.059  1159  1624 D WifiNetworkAgent: NetworkAgent: Registering NetworkAgent
,08-31 16:50:42.059  1159  1159 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
08-31 16:50:42.059  1159  1624 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-31 16:50:42.059  1159  1159 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-31 16:50:42.059  1159  1631 D ConnectivityService: Got NetworkAgent Messenger
08-31 16:50:42.059  1159  1631 E ConnectivityService: updateNetworkInfo()
08-31 16:50:42.059  1159  1631 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:50:42.059  1159  1631 D ConnectivityService: NetworkAgent connected
08-31 16:50:42.069  1159  1159 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,08-31 16:50:42.069  1159  1629 I WifiHs20Service: Message received 5007
08-31 16:50:42.069   555  1424 D CommandListener: Setting iface cfg
,08-31 16:50:42.069  1705  2083 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
08-31 16:50:42.069  1943  1943 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,08-31 16:50:42.069  5903  5903 D AndroidRuntime: Shutting down VM
,08-31 16:50:42.069  1159  1624 D WifiStateMachine: Start Dhcp Watchdog 1
08-31 16:50:42.069  1159  1366 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1dc642d u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6724a55 5359:com.enhance.gameservice/u0a79}
,08-31 16:50:42.079  5903  5903 E AndroidRuntime: FATAL EXCEPTION: main
08-31 16:50:42.079  5903  5903 E AndroidRuntime: Process: com.test.thalitest, PID: 5903
08-31 16:50:42.079  5903  5903 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-31 16:50:42.079  5903  5903 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:676)
08-31 16:50:42.079  5903  5903 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6296)
08-31 16:50:42.079  5903  5903 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:223)
08-31 16:50:42.079  5903  5903 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1863)
08-31 16:50:42.079  5903  5903 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:50:42.079  5903  5903 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
08-31 16:50:42.079  5903  5903 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7231)
08-31 16:50:42.079  5903  5903 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:50:42.079  5903  5903 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-31 16:50:42.079  5903  5903 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-31 16:50:42.079  5903  5903 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-31 16:50:42.079  5903  5903 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:485)
08-31 16:50:42.079  5903  5903 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:661)
08-31 16:50:42.079  5903  5903 E AndroidRuntime: 	... 9 more
,08-31 16:50:42.079  1159  1624 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,08-31 16:50:42.079  1159  1624 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,08-31 16:50:42.079  1159  2133 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
08-31 16:50:42.079  1159  2133 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 5, Mac address valid: false, AP MAC address: [00:00:00:00:00:00], Wifi-Ap SSID Valid: false, SSID: 
,08-31 16:50:42.089  5903  5903 I Process : Sending signal. PID: 5903 SIG: 9
,08-31 16:50:42.089  1159  1624 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,08-31 16:50:42.099  5918  5918 E Zygote  : v2
08-31 16:50:42.099  5918  5918 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:50:42.099  5918  5918 I libpersona: KNOX_SDCARD not a persona
,08-31 16:50:42.099  5918  5918 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-31 16:50:42.099  5918  5918 E Zygote  : accessInfo : 0
08-31 16:50:42.099  1159  1366 I ActivityManager: Start proc 5918:com.sec.android.diagmonagent/1000 for broadcast-5 com.sec.android.diagmonagent/.DiagMonConnectivityChangeReciever
,08-31 16:50:42.099  1159  1624 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,08-31 16:50:42.099  1159  2133 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
08-31 16:50:42.099  1159  2133 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 7, Mac address valid: false, AP MAC address: [00:00:00:00:00:00], Wifi-Ap SSID Valid: false, SSID: 
,08-31 16:50:42.119  1159  1366 I ActivityManager: Start proc 5931:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
,08-31 16:50:42.119  1159  1624 D WifiNetworkAgent: NetworkAgent: NetworkAgent fully connected
08-31 16:50:42.129  1159  2133 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
08-31 16:50:42.129  1159  2133 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 8, Mac address valid: false, AP MAC address: [00:00:00:00:00:00], Wifi-Ap SSID Valid: false, SSID: 
,08-31 16:50:42.129  1159  1631 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,08-31 16:50:42.129  1159  1976 D ActivityManager: isAutoRunBlockedApp:: com.wssyncmldm, Auto Run ON
08-31 16:50:42.129  1159  1976 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=4987 ,hash=223752390 ,name=com.wssyncmldm
,08-31 16:50:42.129  1159  1631 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]
,08-31 16:50:42.129  1159  1631 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,08-31 16:50:42.129  5918  5918 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:42.129  5918  5918 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:42.139  1705  2083 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,08-31 16:50:42.139  5931  5931 E Zygote  : v2
08-31 16:50:42.139  5931  5931 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:50:42.139  5931  5931 I libpersona: KNOX_SDCARD not a persona
,08-31 16:50:42.139  5931  5931 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-31 16:50:42.139  5931  5931 E Zygote  : accessInfo : 0
,08-31 16:50:42.139  1159  1624 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,08-31 16:50:42.139  1159  1950 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1dc642d u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d421cc8 5918:com.sec.android.diagmonagent/1000}
,08-31 16:50:42.139  1159  2133 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
08-31 16:50:42.139  1159  1624 E WifiNative-wlan0: do suspend false
08-31 16:50:42.139  1159  2133 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 9, Mac address valid: true, AP MAC address: [f4:f2:6d:22:99:3e], Wifi-Ap SSID Valid: true, SSID: NG700
,08-31 16:50:42.149  1159  1623 D WifiP2pService: InactiveState{ what=143375 }
,08-31 16:50:42.149  1159  1623 D WifiP2pService: P2pEnabledState{ what=143375 }
08-31 16:50:42.149  1159  2153 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 131 QMI_LOC_NOTIFY_WIFI_ATTACHMENT_STATUS_REQ_V02
,08-31 16:50:42.159  5918  5918 W System  : ClassLoader referenced unknown path: /system/priv-app/DiagMonAgent/lib/arm64
,08-31 16:50:42.169  5941  5941 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-31 16:50:42.169  5941  5941 I dhcpcd  : version 5.5.6 starting
,08-31 16:50:42.179  5918  5918 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
08-31 16:50:42.179  1159  1200 I ActivityManager: Process com.test.thalitest (pid 5903)(adj 9) has died(169,1536)
08-31 16:50:42.179  5941  5941 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
08-31 16:50:42.179  1159  1200 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
08-31 16:50:42.179  1159  1200 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5903 ,hash=104957701 ,name=com.test.thalitest
,08-31 16:50:42.179  5931  5931 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:42.179  1159  1200 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.android.server.am.ActivityManagerService.updateOomAdjLocked:26615 com.android.server.am.ActivityManagerService.appDiedLocked:7605 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1888 android.os.BinderProxy.sendDeathNotice:558 
08-31 16:50:42.179  5931  5931 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:42.189  1159  1727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fda3486 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{49b6161 5931:com.samsung.android.sm/1000}
,08-31 16:50:42.209  5931  5931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1311 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.samsung.android.sm.common.SmartManagerReceiver.b:259 com.samsung.android.sm.common.SmartManagerReceiver.onReceive:107 
,08-31 16:50:42.249  5918  5918 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-31 16:50:42.259  5918  5918 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(72/onCreate)] DiagMon DM Application Start !
08-31 16:50:42.259  1159  1426 I art     : Explicit concurrent mark sweep GC freed 259361(15MB) AllocSpace objects, 51(2MB) LOS objects, 33% free, 29MB/43MB, paused 2.769ms total 224.949ms
,08-31 16:50:42.259  5918  5918 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,08-31 16:50:42.259  5918  5918 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
08-31 16:50:42.259  5918  5918 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
08-31 16:50:42.259  5918  5918 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-31 16:50:42.269  1159  2558 I ActivityManager: Start proc 5951:com.sec.app.RilErrorNotifier/1000 for broadcast-5 com.sec.app.RilErrorNotifier/.PhoneErrorReceiver
,08-31 16:50:42.269  1159  2558 I ActivityManager: Killing 4421:com.android.providers.calendar/u0a32 (adj 15): DHA:empty #31
08-31 16:50:42.269  5951  5951 E Zygote  : v2
08-31 16:50:42.269  5951  5951 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:50:42.269  5951  5951 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:42.269  5951  5951 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-31 16:50:42.269  5941  5941 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,08-31 16:50:42.269  5941  5941 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-31 16:50:42.269  5951  5951 E Zygote  : accessInfo : 0
08-31 16:50:42.269  5941  5941 I dhcpcd  : bssid match
,08-31 16:50:42.279  5941  5941 I dhcpcd  : wlan0: rebinding lease of 192.168.1.106
,08-31 16:50:42.279  1159  1426 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-31 16:50:42.279  1159  1426 D AASAuninstall: userId = 0, info.removedAppID = 10136, info.uid = 10136, packageName = com.test.thalitest
08-31 16:50:42.279  1159  1426 D AASAinstall: there is not AASApackages.xml file
08-31 16:50:42.279  1159  1426 D PackageManager: result of delete: 1{65045116}
,08-31 16:50:42.279  1159  1426 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-31 16:50:42.279  1159  1426 D PackageManager: userId{-1}
08-31 16:50:42.279  1159  1426 D PackageManager: andCode{true}
,08-31 16:50:42.289  5893  5893 I art     : System.exit called, status: 0
08-31 16:50:42.289  5893  5893 I AndroidRuntime: VM exiting with result code 0.
,08-31 16:50:42.289  1159  1426 I ActivityManager: Force stopping com.test.thalitest appid=10136 user=0: pkg removed
,08-31 16:50:42.299  1159  1426 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 124)
,08-31 16:50:42.319  5394  5964 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-31 16:50:42.319  5394  5964 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-31 16:50:42.329  5394  5964 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-31 16:50:42.329  5951  5951 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:42.329  5951  5951 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:42.349  1705  1705 D ShortcutManager: onReceive : android.intent.action.PACKAGE_REMOVED
08-31 16:50:42.349  1705  1705 D ShortcutManager: onReceive : Intent.EXTRA_REPLACING false,com.test.thalitest
,08-31 16:50:42.349  1705  1705 D CoverUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
,08-31 16:50:42.349  1159  1593 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 16:50:42.349  1878  2433 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-31 16:50:42.359  1159  1366 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dd840c5 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1ac0a09 3738:com.samsung.klmsagent/u0a16}
,08-31 16:50:42.369  3738  3738 I KLMS-2.6.094: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } | timestamp: Wed Aug 31 16:50:42 GMT+02:00 2016
,08-31 16:50:42.369  1159  1950 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1dc642d u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3151312 5951:com.sec.app.RilErrorNotifier/1000}
08-31 16:50:42.369  1796  1796 I Recents_MultiWindowAppListInfo: android.intent.action.PACKAGE_REMOVE
,08-31 16:50:42.369  3738  3738 I KLMS-2.6.094: : KLMSAbstractReciever(): onReceive().END.
,08-31 16:50:42.369  3738  3738 I KLMS-2.6.094: : KLMSIntentService(): onCreate()
08-31 16:50:42.369  1159  1202 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
08-31 16:50:42.369  1159  1202 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=4421 ,hash=141357687 ,name=com.android.providers.calendar
,08-31 16:50:42.379  1943  1943 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-31 16:50:42.379  1159  1978 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=2497, uid=10093 that is not exported from uid 10091
08-31 16:50:42.379  3738  3738 I KLMS-2.6.094: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-31 16:50:42.379  5941  5941 I dhcpcd  : wlan0: acknowledged 192.168.1.106 from 192.168.1.1
,08-31 16:50:42.379  3738  3738 I KLMS-2.6.094: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-31 16:50:42.379  3738  5967 I KLMS-2.6.094: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
08-31 16:50:42.379  3738  5967 D KLMS-2.6.094: : KLMSIntentService(): PACKAGE_REMOVED
08-31 16:50:42.379  3738  5967 I KLMS-2.6.094: : Systemprocess(): listeningToPackageRemoved().START
08-31 16:50:42.379  3738  5967 I KLMS-2.6.094: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
08-31 16:50:42.379  3738  5967 I KLMS-2.6.094: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
08-31 16:50:42.379  3738  5967 I KLMS-2.6.094: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-31 16:50:42.379  3738  5967 I KLMS-2.6.094: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-31 16:50:42.389  3738  5967 I KLMS-2.6.094: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-31 16:50:42.389  5951  5951 W System  : ClassLoader referenced unknown path: /system/priv-app/PhoneErrService/lib/arm64
,08-31 16:50:42.389  3738  5967 I KLMS-2.6.094: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-31 16:50:42.389  1159  2313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dd840c5 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{37f90f5 1159:system/1000}
,08-31 16:50:42.389  3738  5967 D KLMS-2.6.094: : Systemprocess(): arrayLicenseInfo is null
,08-31 16:50:42.399  5951  5951 I PhoneErrorReceiver: onReceive
08-31 16:50:42.399  5951  5951 I MIPErrReceiver: isWiFiConnected
,08-31 16:50:42.399  3738  5967 D KLMS-2.6.094: : DataSource(): Fetched Data from data base count : 0
,08-31 16:50:42.399  1159  1727 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:50:42.399  1159  1621 V NetworkStats: removeUidsLocked() for UIDs [10136]
08-31 16:50:42.399  1159  1621 V NetworkStats: performPollLocked(flags=0x3)
,08-31 16:50:42.409  1159  1621 V NetworkStats: performPollLocked() took 5ms
,08-31 16:50:42.409  1159  2367 D SettingsProvider: isChangeAllowed() : name = klm_eula_shown
08-31 16:50:42.409  1159  2367 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-31 16:50:42.409  1159  2367 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:50:42.409  1159  2367 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:50:42.409  1159  2367 D SettingsProvider: selectionArgs: false
08-31 16:50:42.409  1159  2367 D SettingsProvider: selectionArgs: 10016
,08-31 16:50:42.409  1159  2367 D SettingsProvider: ret = -1
,08-31 16:50:42.419  1159  1358 D EnterpriseDeviceManagerService: Package has changed for user 0
08-31 16:50:42.419  1159  1358 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-31 16:50:42.419  1159  1159 V AlarmManager: Remove alarm for next reason : android.intent.action.PACKAGE_REMOVED : package: com.test.thalitest
,08-31 16:50:42.419  1159  1159 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-31 16:50:42.419  1159  1978 I ActivityManager: Start proc 5970:com.sec.knox.switcher/1000 for broadcast-5 com.sec.knox.switcher/.knoxusage.KnoxUsageReceiver
,08-31 16:50:42.419  1159  1159 D UniversalCredentialManagerService: inside mPkgReciever onReceive : android.intent.action.PACKAGE_REMOVED
08-31 16:50:42.419  1159  1159 D UniversalCredentialManagerService: ACTION_PACKAGE_REMOVED is called....
08-31 16:50:42.419  1159  1159 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-31 16:50:42.419  1159  1159 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-31 16:50:42.419  1159  1159 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10136 container id = 0
08-31 16:50:42.419  1159  1978 I ActivityManager: Killing 5248:com.android.calendar/u0a106 (adj 15): DHA:empty #31
08-31 16:50:42.419  5970  5970 E Zygote  : v2
08-31 16:50:42.419  5970  5970 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:50:42.419  1159  1159 I OTPFW   : ProvisionData::getAllEntries Enter
08-31 16:50:42.419  5970  5970 I libpersona: KNOX_SDCARD not a persona
,08-31 16:50:42.429  1159  1159 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-31 16:50:42.429  1159  1159 E SDAgentPackageStateReceiver: Not going to handle 'com.test.thalitest'!
08-31 16:50:42.429  5970  5970 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-31 16:50:42.429  1159  1622 D NtpTrustedTime: forceRefresh: no connectivity
,08-31 16:50:42.429  5970  5970 E Zygote  : accessInfo : 0
,08-31 16:50:42.429  1159  1159 D UcmService: onReceive android.intent.action.PACKAGE_REMOVED
,08-31 16:50:42.429  1159  1159 D UcmService: Package update in userId-0 and uid-10136
,08-31 16:50:42.429  1159  1159 D GameManager.DatabaseHelper: removeGame(), packageName: com.test.thalitest, ret: 0
,08-31 16:50:42.429  1159  1159 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-31 16:50:42.429  1159  1159 V EnterpriseBillingAsyncHandler: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,08-31 16:50:42.429  1159  1655 V EnterpriseBillingPolicyInternal: packageModification -  start - android.intent.action.PACKAGE_REMOVED
08-31 16:50:42.429  1159  1655 V EnterpriseBillingPolicyInternal: uID is 10136
08-31 16:50:42.429  1159  1655 V EnterpriseBillingPolicyInternal: Removed Packageuid is0
08-31 16:50:42.429  1159  1655 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-31 16:50:42.439  1159  1655 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-31 16:50:42.439  1159  1655 V EnterpriseBillingPolicyInternal: packageModificationReceiver - onreceive - personal application - profile null
08-31 16:50:42.439  1159  1159 D SdpManagerService:  ActionReceiver::onReceive() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,08-31 16:50:42.439  1159  1159 D SdpManagerService: ACTION_PACKAGE_REMOVED Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } DATA= package:com.test.thalitest UID 1000 userId 0
08-31 16:50:42.439  1159  1159 D SdpManagerService: ACTION_PACKAGE_REMOVED packageName:: com.test.thalitest
08-31 16:50:42.439  1159  1159 D EnterprisePartitionManager: SND -> {secure_fs remove_enc_dir}
,08-31 16:50:42.439  5941  5941 I dhcpcd  : wlan0: leased 192.168.1.106 for 172800 seconds
08-31 16:50:42.439   384   440 D epmd    : Partition obj created
08-31 16:50:42.439  1159  1428 D EnterprisePartitionManager: RCV <-
08-31 16:50:42.439   384   440 D epmd    : Partition::dump============== 0
08-31 16:50:42.439  1159  1159 D EnterprisePartitionManager: RMV <-
08-31 16:50:42.439   384   440 D epmd    : Partition::mType > INTERNAL-SDCARD mSrcPath > /data/knox/secure_fs/enc_user mMntPath > /data/enc_user
08-31 16:50:42.439  1159  1159 D EnterprisePartitionManager: event : 281 3 remove_enc_dir failed
08-31 16:50:42.439   384   440 D epmd    : Partition::SDP > not supported
08-31 16:50:42.439  1159  1159 D SdpManagerService: start document   : 
08-31 16:50:42.439   384   440 E epmd    : removeEncPkgDir ERROR
08-31 16:50:42.439  1159  1159 D SdpManagerService: start element    : engine_list
08-31 16:50:42.439   384   440 D epmd    : deleting Partition object.
08-31 16:50:42.439  1159  1159 D SdpManagerService: start characters : 
08-31 16:50:42.439   384   440 W FrameworkListener: Handler 'secure_fs' error (No such file or directory)
08-31 16:50:42.439  1159  1159 D SdpManagerService: start element    : engine
08-31 16:50:42.439  1159  1159 D SdpManagerService:  attribte alias: android_0
08-31 16:50:42.439  1159  1159 D SdpManagerService:  attribte id: 0
08-31 16:50:42.439  1159  1159 D SdpManagerService: end element      : engine
08-31 16:50:42.439  1159  1159 D SdpManagerService: start characters : 
08-31 16:50:42.439  1159  1159 D SdpManagerService: end element      : engine_list
08-31 16:50:42.439  1159  1159 D SdpManagerService: end document     : 
08-31 16:50:42.439  1159  1159 W System.err: mkdir failed: EEXIST (File exists) : /data/system/users/0
08-31 16:50:42.439  1159  1159 E SdpManagerService: cant make directory /data/system/users/0
08-31 16:50:42.439  5941  5941 I dhcpcd  : list file open Error `/data/misc/dhcp/dhcpcd-wlan0.lease_list': Read-only file system
08-31 16:50:42.439  5941  5941 E dhcpcd  : wlan0: open: Read-only file system
08-31 16:50:42.439  5941  5941 E dhcpcd  : write_lease: Read-only file system
08-31 16:50:42.439  1159  1159 D SdpManagerService: start document   : 
08-31 16:50:42.439  1159  1159 D SdpManagerService: start element    : user
08-31 16:50:42.439  1159  1159 D SdpManagerService: end element      : user
08-31 16:50:42.439  1159  1159 D SdpUtil : num:0 index-0
08-31 16:50:42.439  1159  1159 D SdpUtil : detecected userId : 0
08-31 16:50:42.439  1159  1159 D SdpManagerService: end document     : 
08-31 16:50:42.439  1159  1159 E SdpManagerService: Can't find engine info [android_0]
08-31 16:50:42.439  1159  1159 V EnterpriseBillingAsyncHandler: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-31 16:50:42.439  1159  1655 V EnterpriseBillingPolicyInternal: packageModification -  start - android.intent.action.PACKAGE_FULLY_REMOVED
08-31 16:50:42.439   747  1447 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 80
08-31 16:50:42.439  1159  1655 V EnterpriseBillingPolicyInternal: uID is 10136
08-31 16:50:42.439  1159  1655 V EnterpriseBillingPolicyInternal: Removed Packageuid is0
08-31 16:50:42.439  1159  1655 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-31 16:50:42.439   747  1447 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
08-31 16:50:42.439   747  1443 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
08-31 16:50:42.439   747  1443 I QC-NETMGR-LIB: Processing RTM_NEWADDR
08-31 16:50:42.439   747  1443 I QC-NETMGR-LIB: Metainfo:  Family=2 PrefixLen=24 Scope=0x0 Index=13 Flags=[0x80]PERMANENT 
08-31 16:50:42.439   747  1443 I QC-NETMGR-LIB: Attribute: PrefixIPv4 addr [192.168.1.106]
08-31 16:50:42.439   747  1443 I QC-NETMGR-LIB: Attribute: LocalIPv4 addr [192.168.1.106]
08-31 16:50:42.439   747  1443 I QC-NETMGR-LIB: Attribute: BroadcastIPv4 addr [192.168.1.255]
08-31 16:50:42.439   747  1443 I QC-NETMGR-LIB: Attribute: Label ,name wlan0
08-31 16:50:42.439   747  1443 I QC-NETMGR-LIB: Attribute: Address Cache Info - prefered=-1 valid=-1 cstamp=0x2b89 tstamp=0x2b89
08-31 16:50:42.439   747  1443 I QC-NETMGR-LIB: Rcvd Netlink msg type [20]
08-31 16:50:42.439   747  1443 E QC-NETMGR-LIB: unrecognized ifindex 13
,08-31 16:50:42.449  1159  1655 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-31 16:50:42.449  1159  1655 V EnterpriseBillingPolicyInternal: packageModificationReceiver - onreceive - personal application - profile null
08-31 16:50:42.449  1159  3409 D SSRM:bb : MSG_TYPE_APP_REMOVED::
08-31 16:50:42.449  1159  1631 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,08-31 16:50:42.449  5440  5450 E SQLiteLog: (10) unixWrite() File Descriptor : 20 gets errno : 30
,08-31 16:50:42.449  1159  1159 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dd840c5 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ad7afc9 1878:com.google.android.gms.persistent/u0a10}
,08-31 16:50:42.449  1159  1159 D AccessibilityManagerService: checkUniversalSwitchState start:
,08-31 16:50:42.459  1159  3409 D SSRM:bb : MSG_TYPE_UID_REMOVED::
,08-31 16:50:42.459  5970  5970 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:42.459  5970  5970 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:42.459  1159  1724 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dd840c5 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{18de5e5 2267:com.google.android.gms/u0a10}
,08-31 16:50:42.469  5440  5450 E DatabaseUtils: Writing exception to parcel
08-31 16:50:42.469  5440  5450 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
08-31 16:50:42.469  5440  5450 E DatabaseUtils: #################################################################
08-31 16:50:42.469  5440  5450 E DatabaseUtils: Error Code : 778 (SQLITE_IOERR_WRITE)
08-31 16:50:42.469  5440  5450 E DatabaseUtils: Caused By : Disk I/O error occurred during 'write' operation.
08-31 16:50:42.469  5440  5450 E DatabaseUtils: 	(disk I/O error (code 778))
08-31 16:50:42.469  5440  5450 E DatabaseUtils: #################################################################
08-31 16:50:42.469  5440  5450 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 16:50:42.469  5440  5450 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:866)
08-31 16:50:42.469  5440  5450 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 16:50:42.469  5440  5450 E DatabaseUtils: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 16:50:42.469  5440  5450 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
08-31 16:50:42.469  5440  5450 E DatabaseUtils: 	at com.samsung.android.sm.database.SmProvider.delete(SmProvider.java:826)
08-31 16:50:42.469  5440  5450 E DatabaseUtils: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:352)
08-31 16:50:42.469  5440  5450 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:206)
08-31 16:50:42.469  5440  5450 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:453)
,08-31 16:50:42.469  1159  1200 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1dc642d u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d7dca91 5970:com.sec.knox.switcher/1000}
,08-31 16:50:42.469  2267  5985 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-31 16:50:42.469  2267  5985 D AccountUtils: Clearing selected account for com.test.thalitest
,08-31 16:50:42.469  1159  1724 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dd840c5 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{18de5e5 2267:com.google.android.gms/u0a10}
,08-31 16:50:42.469  1159  1401 E MARsDBManager: Exception with contentResolver : disk I/O error (code 778)
08-31 16:50:42.469  1159  1401 E MARsDBManager: #################################################################
08-31 16:50:42.469  1159  1401 E MARsDBManager: Error Code : 778 (SQLITE_IOERR_WRITE)
08-31 16:50:42.469  1159  1401 E MARsDBManager: Caused By : Disk I/O error occurred during 'write' operation.
08-31 16:50:42.469  1159  1401 E MARsDBManager: 	(disk I/O error (code 778))
08-31 16:50:42.469  1159  1401 E MARsDBManager: #################################################################
08-31 16:50:42.469  1159  1401 E MARsDBManager: #################################################################
08-31 16:50:42.469  1159  1401 E MARsDBManager: Error Code : 778 (SQLITE_IOERR_WRITE)
08-31 16:50:42.469  1159  1401 E MARsDBManager: Caused By : Disk I/O error occurred during 'write' operation.
08-31 16:50:42.469  1159  1401 E MARsDBManager: 	(disk I/O error (code 778)
08-31 16:50:42.469  1159  1401 E MARsDBManager: #################################################################
08-31 16:50:42.469  1159  1401 E MARsDBManager: Error Code : 778 (SQLITE_IOERR_WRITE)
08-31 16:50:42.469  1159  1401 E MARsDBManager: Caused By : Disk I/O error occurred during 'write' operation.
08-31 16:50:42.469  1159  1401 E MARsDBManager: 	(disk I/O error (code 778))
08-31 16:50:42.469  1159  1401 E MARsDBManager: #################################################################)
08-31 16:50:42.469  1159  1401 E MARsDBManager: #################################################################
,08-31 16:50:42.479  1159  1978 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dd840c5 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ad7afc9 1878:com.google.android.gms.persistent/u0a10}
,08-31 16:50:42.489  2267  5985 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-31 16:50:42.489  1878  1878 D GCM-PT  : Populating db of packages that use GCM
,08-31 16:50:42.499  5970  5970 W System  : ClassLoader referenced unknown path: /system/app/KnoxSwitcher/lib/arm64
,08-31 16:50:42.509  2267  5985 W SQLiteLog: (28) failed to open "/data/user/0/com.google.android.gms/databases/phenotype.db" with flag (131138) and mode_t (0) due to error (30)
,08-31 16:50:42.509  5970  5970 D KnoxUsageDB: getInstance - KnoxUsageDBHelper
08-31 16:50:42.509  5970  5970 D KnoxUsageDB: null == mDbHelperInstance - KnoxUsageDBHelper
,08-31 16:50:42.509  2267  5985 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
08-31 16:50:42.509  2267  5985 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 16:50:42.509  2267  5985 E SQLiteDatabase: #################################################################
08-31 16:50:42.509  2267  5985 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
08-31 16:50:42.509  2267  5985 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-31 16:50:42.509  2267  5985 E SQLiteDatabase: #################################################################
08-31 16:50:42.509  2267  5985 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 16:50:42.509  2267  5985 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-31 16:50:42.509  2267  5985 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-31 16:50:42.509  2267  5985 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 16:50:42.509  2267  5985 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 16:50:42.509  2267  5985 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 16:50:42.509  2267  5985 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 16:50:42.509  2267  5985 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 16:50:42.509  2267  5985 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 16:50:42.509  2267  5985 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:639)
08-31 16:50:42.509  2267  5985 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-31 16:50:42.509  2267  5985 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-31 16:50:42.509  2267  5985 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 16:50:42.509  2267  5985 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 16:50:42.509  2267  5985 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastIntentOperation.onHandleIntent(:com.google.android.gms:51)
08-31 16:50:42.509  2267  5985 E SQLiteDatabase: 	at com.google.android.chimera.IntentOperation.onHandleIntent(:com.google.android.gms:76)
08-31 16:50:42.509  2267  5985 E SQLiteDatabase: 	at com.google.android.chimera.container.l.run(:com.google.android.gms:801)
08-31 16:50:42.509  2267  5985 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 16:50:42.509  2267  5985 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 16:50:42.509  2267  5985 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-31 16:50:42.509  2267  5985 E PhenotypeInitializer: Could not unregister android package com.test.thalitest
08-31 16:50:42.509  2267  5985 E PhenotypeInitializer: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 16:50:42.509  2267  5985 E PhenotypeInitializer: #################################################################
08-31 16:50:42.509  2267  5985 E PhenotypeInitializer: Error Code : 0 (SQLITE_OK)
08-31 16:50:42.509  2267  5985 E PhenotypeInitializer: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-31 16:50:42.509  2267  5985 E PhenotypeInitializer: #################################################################
08-31 16:50:42.509  2267  5985 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 16:50:42.509  2267  5985 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-31 16:50:42.509  2267  5985 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-31 16:50:42.509  2267  5985 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 16:50:42.509  2267  5985 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 16:50:42.509  2267  5985 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 16:50:42.509  2267  5985 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 16:50:42.509  2267  5985 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 16:50:42.509  2267  5985 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 16:50:42.509  2267  5985 E PhenotypeInitializer: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:639)
08-31 16:50:42.509  2267  5985 E PhenotypeInitializer: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-31 16:50:42.509  2267  5985 E PhenotypeInitializer: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-31 16:50:42.509  2267  5985 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 16:50:42.509  2267  5985 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 16:50:42.509  2267  5985 E PhenotypeInitializer: 	at com.google.android.gms.app.service.PackageBroadcastIntentOperation.onHandleIntent(:com.google.android.gms:51)
08-31 16:50:42.509  2267  5985 E PhenotypeInitializer: 	at com.google.android.chimera.IntentOperation.onHandleIntent(:com.google.android.gms:76)
08-31 16:50:42.509  2267  5985 E PhenotypeInitializer: 	at com.google.android.chimera.container.l.run(:com.google.android.gms:801)
08-31 16:50:42.509  2267  5985 E PhenotypeInitializer: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 16:50:42.509  2267  5985 E PhenotypeInitializer: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 16:50:42.509  2267  5985 E PhenotypeInitializer: 	at java.lang.Thread.run(Thread.java:818)
,08-31 16:50:42.519  1159  1202 D ActivityManager: isAutoRunBlockedApp:: com.android.calendar, Auto Run ON
08-31 16:50:42.519  1159  1202 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5248 ,hash=6424831 ,name=com.android.calendar
08-31 16:50:42.519  5970  5970 I usagelog: received in receiver
08-31 16:50:42.519  5970  5970 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0

```
