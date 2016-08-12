#### Test 797510151684451_thali01_samsung-SM-G900F Logs


```
--------- beginning of main
08-12 18:36:09.836  3506  3506 D FactoryTest: User mode
08-12 18:36:09.836  3506  3506 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-12 18:36:09.836  3506  3506 D MTPRx   : still no open session command from host, so toast
--------- beginning of system
08-12 18:36:09.846   751  1949 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
08-12 18:36:09.866   751  1949 D ActivityManager: mDVFSHelper.acquire()
08-12 18:36:09.866   751  1949 D FocusedStackFrame: Set to : 0
08-12 18:36:09.866   751  1949 V WindowManager: addAppToken: AppWindowToken{4f57965 token=Token{7bd425c ActivityRecord{28948cf u0 com.samsung.android.MtpApplication/.USBConnection t167}}} to stack=1 task=167 at 0
08-12 18:36:09.876   751  1949 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
08-12 18:36:09.916   751  1949 D InputDispatcher: Focused application set to: xxxx
08-12 18:36:09.916   751  1949 D InputDispatcher: Focus left window: 1742
08-12 18:36:09.916   751   837 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
08-12 18:36:09.926   751   887 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:751 uid:1000
08-12 18:36:09.926   751   887 D PointerIcon: setMouseCustomIcon IconType is same.101
08-12 18:36:09.926   751   887 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:751 uid:1000
08-12 18:36:09.926   751   887 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-12 18:36:09.926   751  3443 D M       : limitCPUFreq:: freq = -1
08-12 18:36:09.926   751  3443 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 751  tag : SIOP_ARM_MAX@25
08-12 18:36:09.926   751  3443 D M       : limitGPUFreq:: freq = -1
08-12 18:36:09.936  3506  3506 E MTPRx   : started activity for popup
08-12 18:36:09.936  3506  3506 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
08-12 18:36:09.936  3506  3506 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
08-12 18:36:09.946   751  3443 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-12 18:36:09.956  3506  3506 D MTPUSBConnection: onCreate in USBConnection
08-12 18:36:09.956  3506  3506 V MTPUSBConnection: Registering broadcast receiver.
08-12 18:36:09.956  3506  3506 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
08-12 18:36:09.956   751  2413 D SecContentProvider2: query(), uri = 14 selection = getSealedState
08-12 18:36:10.026  3506  3506 D TAG     : dev.kiessupport is : TRUE
08-12 18:36:10.056  3506  3506 D SecWifiDisplayUtil: Metadata value : none
08-12 18:36:10.066  3506  3506 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{631a9bd V.E...... R.....I. 0,0-0,0}
08-12 18:36:10.066  3506  6393 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-12 18:36:10.076   751   766 D ISSUE_DEBUG: InputChannelName : cb2701d com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
08-12 18:36:10.076   751   839 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{cb2701d u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
08-12 18:36:10.076   751   766 D InputDispatcher: Focus entered window: 3506
08-12 18:36:10.076  1384  1384 D PhoneStatusBar: setSystemUiVisibility vis=40008000 mask=ffffffff oldVal=40008500 newVal=40008000 diff=500
08-12 18:36:10.076   751   887 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:751 uid:1000
08-12 18:36:10.076   751   887 D PointerIcon: setMouseCustomIcon IconType is same.101
08-12 18:36:10.076   751   887 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:751 uid:1000
08-12 18:36:10.076   751   887 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-12 18:36:10.086  3506  3506 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{7895375 I.E...... R.....I. 0,0-0,0}
08-12 18:36:10.086   751  1603 D ISSUE_DEBUG: InputChannelName : cd78463 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
08-12 18:36:10.086   751  1494 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-12 18:36:10.086   751  1494 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-12 18:36:10.086   751   751 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-12 18:36:10.096   751   751 I KnoxTimeoutHandler: Shared devices show user statefalse
08-12 18:36:10.096   751   751 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
08-12 18:36:10.136   293   293 I SurfaceFlinger: id=19 createSurf (145x145),1 flag=4, VSBConnecti
08-12 18:36:10.146  3506  6393 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-12 18:36:10.146  3506  6393 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-12 18:36:10.146  3506  6393 I Adreno-EGL: Build Date: 01/28/16 Thu
08-12 18:36:10.146  3506  6393 I Adreno-EGL: Local Branch: ss
08-12 18:36:10.146  3506  6393 I Adreno-EGL: Remote Branch: 
08-12 18:36:10.146  3506  6393 I Adreno-EGL: Local Patches: 
08-12 18:36:10.146  3506  6393 I Adreno-EGL: Reconstruct Branch: 
08-12 18:36:10.156  3506  6393 D libEGL  : eglInitialize EGLDisplay = 0x9edfe7c4
08-12 18:36:10.156  3506  6393 I OpenGLRenderer: Initialized EGL, version 1.4
08-12 18:36:10.236   293   293 I SurfaceFlinger: id=20 createSurf (193x193),1 flag=4, VSBConnecti
08-12 18:36:10.256  3506  3506 V ActivityThread: updateVisibility : ActivityRecord{4871598 token=android.os.BinderProxy@a0b0bb2 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
08-12 18:36:10.256  3506  3506 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
08-12 18:36:10.356   751  2390 V WindowStateAnimator: Finishing drawing window Window{cb2701d u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
08-12 18:36:10.366  3506  3506 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
08-12 18:36:10.366   751  1686 V WindowStateAnimator: Finishing drawing window Window{cd78463 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
08-12 18:36:10.366  3506  3506 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-12 18:36:10.366  3506  3506 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-12 18:36:10.376   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe86d364
08-12 18:36:10.376   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe86d364
08-12 18:36:10.376   751   887 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-12 18:36:10.376   751   751 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-12 18:36:10.376   751   751 I KnoxTimeoutHandler: SD activityfalse
08-12 18:36:10.376   751   887 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +464ms (total +510ms)
08-12 18:36:10.376   751   887 D ActivityManager: mDVFSHelper.release()
08-12 18:36:10.376   751   887 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{28948cf u0 com.samsung.android.MtpApplication/.USBConnection t167} time:108096
08-12 18:36:10.386   751  1771 V WindowStateAnimator: Finishing drawing window Window{cb2701d u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
08-12 18:36:10.386   751  1949 V WindowStateAnimator: Finishing drawing window Window{cd78463 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
08-12 18:36:10.386  3506  3506 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@a0b0bb2 time:108102
08-12 18:36:10.386   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe86d364
,08-12 18:36:10.926   751  3444 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
08-12 18:36:10.966  5385  5385 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
08-12 18:36:10.966  5385  5385 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
08-12 18:36:10.966  5385  5385 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
08-12 18:36:10.966  5385  5385 I art     : System.exit called, status: 0
08-12 18:36:10.966  5385  5385 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-12 18:36:11.006  5357  5357 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(47/onServiceDisconnected)] AASA: onServiceDisconnected
08-12 18:36:11.006   751  1948 I ActivityManager: Process com.samsung.aasaservice (pid 5385)(adj 0) has died(86,720)
08-12 18:36:11.006   751  1948 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
08-12 18:36:11.006   751  1948 I ActivityManager: isWidgetUsingPkg : com.samsung.aasaservice no widget is using.
08-12 18:36:11.006   751  1948 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
08-12 18:36:11.026  6410  6410 E Zygote  : v2
08-12 18:36:11.026  6410  6410 I libpersona: KNOX_SDCARD checking this for 10014
08-12 18:36:11.026  6410  6410 I libpersona: KNOX_SDCARD not a persona
08-12 18:36:11.026  6410  6410 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:36:11.026  6410  6410 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 18:36:11.026  6410  6410 E Zygote  : accessInfo : 0
08-12 18:36:11.026  6410  6410 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
08-12 18:36:11.036   751   837 I ActivityManager: Start proc 6410:com.google.android.partnersetup/u0a14 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
08-12 18:36:11.036   751  1323 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-12 18:36:11.056  6410  6410 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 18:36:11.056  6410  6410 D ActivityThread: Added TimaKeyStore provider
08-12 18:36:11.056   751  1416 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a8af119 6410:com.google.android.partnersetup/u0a14}
08-12 18:36:11.066   751  1323 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
08-12 18:36:11.066  6410  6410 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package null
08-12 18:36:11.076  6410  6410 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
08-12 18:36:11.096  1453  1453 D Recents : onTaskStackChanged
08-12 18:36:11.106   751  1494 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a8af119 6410:com.google.android.partnersetup/u0a14}
08-12 18:36:11.126   751  1494 I ActivityManager: Start proc 6425:com.samsung.groupcast/u0a15 for broadcast-3 com.samsung.groupcast/.receiver.SSPReceiver
08-12 18:36:11.126  6425  6425 E Zygote  : v2
08-12 18:36:11.126  6425  6425 I libpersona: KNOX_SDCARD checking this for 10015
08-12 18:36:11.126  6425  6425 I libpersona: KNOX_SDCARD not a persona
08-12 18:36:11.126  6425  6425 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:36:11.126  6425  6425 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 18:36:11.126  6425  6425 E Zygote  : accessInfo : 0
08-12 18:36:11.126  6425  6425 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.groupcast 
08-12 18:36:11.136   751  1949 I ActivityManager: Killing 5504:com.sec.android.app.camera/u0a153 (adj 15): DHA:empty #37
08-12 18:36:11.156   751  2413 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.camera, Auto Run ON
08-12 18:36:11.156  6425  6425 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 18:36:11.156  6425  6425 D ActivityThread: Added TimaKeyStore provider
08-12 18:36:11.166   751  1686 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d83fa8c 6425:com.samsung.groupcast/u0a15}
08-12 18:36:11.166  6425  6425 W ResourcesManager: getTopLevelResources: /system/priv-app/GroupPlay_27/GroupPlay_27.apk / 1.0 running in com.samsung.groupcast rsrc of package null
08-12 18:36:11.186  6425  6425 W System  : ClassLoader referenced unknown path: /system/priv-app/GroupPlay_27/lib/arm
08-12 18:36:11.206  6425  6425 D GroupCast_FileTools: [getDirectoryForImageResized : 295] cleaning!!
08-12 18:36:11.206  6425  6425 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
08-12 18:36:11.206  6425  6425 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-12 18:36:11.206  6425  6425 W System.err: 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:354)
08-12 18:36:11.206  6425  6425 W System.err: 	at com.samsung.groupcast.application.App.onCreate(App.java:161)
08-12 18:36:11.206  6425  6425 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-12 18:36:11.216  6425  6425 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-12 18:36:11.216  6425  6425 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-12 18:36:11.216  6425  6425 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-12 18:36:11.216  6425  6425 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 18:36:11.216  6425  6425 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-12 18:36:11.216  6425  6425 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-12 18:36:11.216  6425  6425 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 18:36:11.216  6425  6425 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-12 18:36:11.216  6425  6425 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-12 18:36:11.216   751  2390 I ActivityManager: Killing 5200:com.android.mms/u0a49 (adj 15): DHA:empty #37
08-12 18:36:11.216   751  2390 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8bb3eaa 1879:com.sec.android.app.shealth:remote/u0a34}
08-12 18:36:11.236   751  2413 I ActivityManager: Start proc 6438:com.samsung.android.sdk.samsunglink/u0a41 for broadcast-3 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
08-12 18:36:11.236  6438  6438 E Zygote  : v2
08-12 18:36:11.236  6438  6438 I libpersona: KNOX_SDCARD checking this for 10041
08-12 18:36:11.236  6438  6438 I libpersona: KNOX_SDCARD not a persona
08-12 18:36:11.236  6438  6438 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:36:11.236  6438  6438 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 18:36:11.236  6438  6438 E Zygote  : accessInfo : 0
08-12 18:36:11.236  6438  6438 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.sdk.samsunglink 
08-12 18:36:11.256   751  2336 D CountryDetector: No listener is left
08-12 18:36:11.256   751  2390 D ActivityManager: isAutoRunBlockedApp:: com.android.mms, Auto Run ON
08-12 18:36:11.266  6438  6438 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 18:36:11.266  6438  6438 D ActivityThread: Added TimaKeyStore provider
08-12 18:36:11.266   751  1686 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bd085d5 6438:com.samsung.android.sdk.samsunglink/u0a41}
08-12 18:36:11.276  6438  6438 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in com.samsung.android.sdk.samsunglink rsrc of package null
08-12 18:36:11.356  6438  6438 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-12 18:36:11.356  6438  6438 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-12 18:36:11.416  6438  6438 I SL_DEBUG: isLoggable:: isProductShip = 1
08-12 18:36:11.416  6438  6438 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
08-12 18:36:11.426   751  2413 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.analytics.AnalyticsAlarmReceiver newState = 0 callingPackage = 10041
08-12 18:36:11.426   751  1772 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.BootCompletedBroadcastReciever newState = 0 callingPackage = 10041
08-12 18:36:11.436   751  2336 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.AutoUploadMediaReceiver newState = 0 callingPackage = 10041
08-12 18:36:11.436   751  1686 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.spp.SPPReceiver newState = 0 callingPackage = 10041
08-12 18:36:11.436   751  1948 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.gcm.GCMReceiver newState = 0 callingPackage = 10041
08-12 18:36:11.446   751  1949 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.PCloudReceiver newState = 0 callingPackage = 10041
08-12 18:36:11.446   751  1771 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.RetryReceiver newState = 0 callingPackage = 10041
08-12 18:36:11.446   751  1494 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.util.ProcessorManagerAlarmReceiver newState = 0 callingPackage = 10041
08-12 18:36:11.446   751  1416 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.account.SamsungAccountReceiver newState = 0 callingPackage = 10041
08-12 18:36:11.456   751  1412 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.sync.CloudStorageSyncEnablerReceiver newState = 0 callingPackage = 10041
08-12 18:36:11.486  2320  2320 E audit   : type=1400 msg=audit(1471019771.486:284): avc:  denied  { execmod } for  pid=6400 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 18:36:11.486  2320  2320 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 18:36:11.486  2320  2320 E audit   : type=1300 msg=audit(1471019771.486:284): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b402b000 a1=51000 a2=5 a3=4 items=0 ppid=3619 ppcomm=adbd pid=6400 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 18:36:11.486  2320  2320 E audit   : type=1327 msg=audit(1471019771.486:284): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-12 18:36:11.486  2320  2320 E audit   : type=1320 msg=audit(1471019771.486:284): 
08-12 18:36:11.536  2320  2320 E audit   : type=1400 msg=audit(1471019771.536:285): avc:  denied  { execmod } for  pid=6400 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 18:36:11.536  2320  2320 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 18:36:11.536  2320  2320 E audit   : type=1300 msg=audit(1471019771.536:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3feb000 a1=51000 a2=5 a3=4 items=0 ppid=3619 ppcomm=adbd pid=6400 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 18:36:11.536  2320  2320 E audit   : type=1327 msg=audit(1471019771.536:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-12 18:36:11.536  2320  2320 E audit   : type=1320 msg=audit(1471019771.536:285): 
08-12 18:36:11.556  6438  6438 W System.err: java.lang.NumberFormatException: Invalid double: "4.0.67"
08-12 18:36:11.556  6438  6438 W System.err: 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
08-12 18:36:11.556  6438  6438 W System.err: 	at java.lang.StringToReal.initialParse(StringToReal.java:160)
08-12 18:36:11.556  6438  6438 W System.err: 	at java.lang.StringToReal.parseDouble(StringToReal.java:282)
08-12 18:36:11.556  6438  6438 W System.err: 	at java.lang.Double.parseDouble(Double.java:301)
08-12 18:36:11.556  6438  6438 W System.err: 	at com.mfluent.asp.ASPApplication.onCreate(SourceFile:375)
08-12 18:36:11.556  6438  6438 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-12 18:36:11.556  6438  6438 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-12 18:36:11.556  6438  6438 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-12 18:36:11.556  6438  6438 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-12 18:36:11.556  6438  6438 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 18:36:11.556  6438  6438 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-12 18:36:11.556  6438  6438 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-12 18:36:11.556  6438  6438 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 18:36:11.556  6438  6438 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-12 18:36:11.556  6438  6438 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-12 18:36:11.566   751  1416 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dc78110 1687:android.process.acore/u0a19}
08-12 18:36:11.566   751  1412 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{22ba88 5094:com.sec.android.gallery3d/u0a47}
08-12 18:36:11.576  5094  5094 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
08-12 18:36:11.586  2320  2320 E audit   : type=1400 msg=audit(1471019771.586:286): avc:  denied  { execmod } for  pid=6400 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 18:36:11.586  2320  2320 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 18:36:11.586  2320  2320 E audit   : type=1300 msg=audit(1471019771.586:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3feb000 a1=51000 a2=5 a3=4 items=0 ppid=3619 ppcomm=adbd pid=6400 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 18:36:11.586  6400  6400 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-12 18:36:11.586  2320  2320 E audit   : type=1327 msg=audit(1471019771.586:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-12 18:36:11.586  2320  2320 E audit   : type=1320 msg=audit(1471019771.586:286): 
08-12 18:36:11.586  6400  6400 D AndroidRuntime: CheckJNI is OFF
08-12 18:36:11.586  6400  6400 D AndroidRuntime: readGMSProperty: start
08-12 18:36:11.586  6400  6400 D AndroidRuntime: readGMSProperty: already setted!!
08-12 18:36:11.586  6400  6400 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-12 18:36:11.586  6400  6400 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-12 18:36:11.586  6400  6400 D AndroidRuntime: readGMSProperty: end
08-12 18:36:11.586  6400  6400 D AndroidRuntime: addProductProperty: start
08-12 18:36:11.596  6400  6400 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-12 18:36:11.596  6400  6400 W art     : af18e000-b20b4000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-12 18:36:11.596  6400  6400 W art     : b20b4000-b4323000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-12 18:36:11.596  6400  6400 W art     : b4323000-b4324000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-12 18:36:11.596  6400  6400 W art     : b4324000-b4772000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-12 18:36:11.596  6400  6400 W art     : b4772000-b4773000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b4773000-b477d000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-12 18:36:11.596  6400  6400 W art     : b477d000-b477e000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-12 18:36:11.596  6400  6400 W art     : b477e000-b4780000 rw-p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b4780000-b4880000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-12 18:36:11.596  6400  6400 W art     : b4890000-b48b9000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-12 18:36:11.596  6400  6400 W art     : b48b9000-b48bc000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-12 18:36:11.596  6400  6400 W art     : b48bc000-b48bd000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-12 18:36:11.596  6400  6400 W art     : b48bd000-b48be000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-12 18:36:11.596  6400  6400 W art     : b48be000-b48bf000 r--p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b48bf000-b48df000 r--s 00000000 00:0b 9219       /dev/__properties__
08-12 18:36:11.596  6400  6400 W art     : b48df000-b52f0000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-12 18:36:11.596  6400  6400 W art     : b52f0000-b52f1000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b52f1000-b533a000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-12 18:36:11.596  6400  6400 W art     : b533a000-b533b000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-12 18:36:11.596  6400  6400 W art     : b533b000-b5343000 rw-p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b5343000-b5344000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:36:11.596  6400  6400 W art     : b5344000-b5379000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-12 18:36:11.596  6400  6400 W art     : b5379000-b537a000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b537a000-b537b000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-12 18:36:11.596  6400  6400 W art     : b537b000-b537c000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-12 18:36:11.596  6400  6400 W art     : b537c000-b53d4000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-12 18:36:11.596  6400  6400 W art     : b53d4000-b53d5000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b53d5000-b53d6000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-12 18:36:11.596  6400  6400 W art     : b53d6000-b53d7000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-12 18:36:11.596  6400  6400 W art     : b53d8000-b53de000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 18:36:11.596  6400  6400 W art     : b53de000-b53df000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 18:36:11.596  6400  6400 W art     : b53df000-b53e0000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 18:36:11.596  6400  6400 W art     : b53e0000-b53e2000 rw-p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b53e3000-b53ed000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 18:36:11.596  6464  6464 I libpersona: KNOX_SDCARD checking this for 10050
08-12 18:36:11.596  6400  6400 W art     : b53ed000-b53f0000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 18:36:11.596  6464  6464 I libpersona: KNOX_SDCARD not a persona
08-12 18:36:11.596  6400  6400 W art     : b53f0000-b53f1000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 18:36:11.596  6400  6400 W art     : b53f2000-b5409000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 18:36:11.596  6400  6400 W art     : b5409000-b540a000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b540a000-b540b000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 18:36:11.596  6400  6400 W art     : b540b000-b540c000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 18:36:11.596  6400  6400 W art     : b540d000-b5417000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-12 18:36:11.596  6400  6400 W art     : b5417000-b5418000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-12 18:36:11.596  6400  6400 W art     : b5418000-b5419000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-12 18:36:11.596  6400  6400 W art     : b5419000-b541d000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 18:36:11.596  6400  6400 W art     : b541d000-b541e000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 18:36:11.596  6400  6400 W art     : b541e000-b541f000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 18:36:11.596  6400  6400 W art     : b541f000-b5435000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-12 18:36:11.596  6400  6400 W art     : b5435000-b5436000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-12 18:36:11.596  6400  6400 W art     : b5436000-b5437000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-12 18:36:11.596  6400  6400 W art     : b5437000-b5444000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-12 18:36:11.596  6400  6400 W art     : b5444000-b5445000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-12 18:36:11.596  6400  6400 W art     : b5445000-b5446000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-12 18:36:11.596  6400  6400 W art     : b5446000-b54a6000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-12 18:36:11.596  6400  6400 W art     : b54a6000-b54a9000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-12 18:36:11.596  6400  6400 W art     : b54a9000-b54ad000 rw-p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b54ad000-b550e000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-12 18:36:11.596  6400  6400 W art     : b550e000-b550f000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-12 18:36:11.596  6400  6400 W art     : b550f000-b555e000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-12 18:36:11.596  6400  6400 W art     : b555e000-b5560000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-12 18:36:11.596  6400  6400 W art     : b5560000-b5561000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-12 18:36:11.596  6400  6400 W art     : b5561000-b5562000 rw-p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b5562000-b5569000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 18:36:11.596  6400  6400 W art     : b5569000-b556a000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 18:36:11.596  6400  6400 W art     : b556a000-b556b000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 18:36:11.596  6400  6400 W art     : b556c000-b556f000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 18:36:11.596  6400  6400 W art     : b556f000-b5570000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 18:36:11.596  6400  6400 W art     : b5570000-b5571000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 18:36:11.596  6400  6400 W art     : b5572000-b5576000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-12 18:36:11.596  6400  6400 W art     : b5576000-b5577000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b5577000-b5578000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-12 18:36:11.596  6400  6400 W art     : b5578000-b5579000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
08-12 18:36:11.596  6400  6400 W art     : b557a000-b5597000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 18:36:11.596  6400  6400 W art     : b5597000-b5598000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 18:36:11.596  6400  6400 W art     : b5598000-b5599000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 18:36:11.596  6400  6400 W art     : b559a000-b559f000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 18:36:11.596  6400  6400 W art     : b559f000-b55a0000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 18:36:11.596  6400  6400 W art     : b55a0000-b55a1000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 18:36:11.596  6400  6400 W art     : b55a2000-b55d3000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 18:36:11.596  6400  6400 W art     : b55d3000-b55d6000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 18:36:11.596  6400  6400 W art     : b55d6000-b55d7000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 18:36:11.596  6400  6400 W art     : b55d8000-b5613000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-12 18:36:11.596  6400  6400 W art     : b5613000-b5614000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-12 18:36:11.596  6400  6400 W art     : b5614000-b5615000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-12 18:36:11.596  6400  6400 W art     : b5616000-b561d000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-12 18:36:11.596  6400  6400 W art     : b561d000-b561e000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b561e000-b561f000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-12 18:36:11.596  6400  6400 W art     : b561f000-b5620000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-12 18:36:11.596  6400  6400 W art     : b5620000-b5621000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:36:11.596  6400  6400 W art     : b5621000-b5638000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-12 18:36:11.596  6400  6400 W art     : b5638000-b5639000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b5639000-b563c000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-12 18:36:11.596  6400  6400 W art     : b563c000-b563d000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-12 18:36:11.596  6400  6400 W art     : b563d000-b565c000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-12 18:36:11.596  6400  6400 W art     : b565c000-b565d000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-12 18:36:11.596  6400  6400 W art     : b565d000-b565e000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-12 18:36:11.596  6400  6400 W art     : b565e000-b569c000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-12 18:36:11.596  6400  6400 W art     : b569c000-b569d000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b569d000-b569f000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-12 18:36:11.596  6400  6400 W art     : b569f000-b56a0000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-12 18:36:11.596  6400  6400 W art     : b56a1000-b56a8000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 18:36:11.596  6400  6400 W art     : b56a8000-b56a9000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 18:36:11.596  6400  6400 W art     : b56a9000-b56aa000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 18:36:11.596  6400  6400 W art     : b56ab000-b56ae000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 18:36:11.596  6400  6400 W art     : b56ae000-b56af000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 18:36:11.596  6400  6400 W art     : b56af000-b56b0000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 18:36:11.596  6400  6400 W art     : b56b0000-b56b6000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 18:36:11.596  6400  6400 W art     : b56b6000-b56b7000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b56b7000-b56b8000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 18:36:11.596  6400  6400 W art     : b56b8000-b56b9000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 18:36:11.596  6400  6400 W art     : b56b9000-b56c2000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-12 18:36:11.596  6400  6400 W art     : b56c2000-b56c3000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-12 18:36:11.596  6400  6400 W art     : b56c3000-b56c4000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-12 18:36:11.596  6400  6400 W art     : b56c4000-b5755000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 18:36:11.596  6400  6400 W art     : b5755000-b5756000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b5756000-b5761000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 18:36:11.596  6400  6400 W art     : b5761000-b5762000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 18:36:11.596  6400  6400 W art     : b5763000-b5775000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-12 18:36:11.596  6400  6400 W art     : b5775000-b5776000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-12 18:36:11.596  6400  6400 W art     : b5776000-b5777000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-12 18:36:11.596  6400  6400 W art     : b5778000-b577d000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-12 18:36:11.596  6400  6400 W art     : b577d000-b577e000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-12 18:36:11.616   751  2415 I ActivityManager: Start proc 6464:com.sec.android.app.myfiles/u0a50 for broadcast-3 com.sec.android.app.myfiles/.receiver.MyFilesReceiver
08-12 18:36:11.596  6400  6400 W art     : b577e000-b577f000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-12 18:36:11.596  6400  6400 W art     : b5780000-b57ed000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-12 18:36:11.596  6400  6400 W art     : b57ed000-b57ee000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b57ee000-b57f0000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-12 18:36:11.596  6400  6400 W art     : b57f0000-b57f1000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-12 18:36:11.596  6400  6400 W art     : b57f1000-b57f2000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:36:11.596  6400  6400 W art     : b57f2000-b57f9000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 18:36:11.596  6400  6400 W art     : b57f9000-b57fa000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 18:36:11.596  6400  6400 W art     : b57fa000-b57fb000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 18:36:11.596  6400  6400 W art     : b57fc000-b587c000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 18:36:11.596  6400  6400 W art     : b587c000-b587d000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b587d000-b587e000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 18:36:11.596  6400  6400 W art     : b587e000-b587f000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 18:36:11.596  6400  6400 W art     : b587f000-b5896000 rw-p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b5896000-b58cd000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-12 18:36:11.596  6400  6400 W art     : ib/libqc-opt.so
08-12 18:36:11.596  6400  6400 W art     : b58cd000-b58ce000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-12 18:36:11.596  6400  6400 W art     : b58ce000-b58cf000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-12 18:36:11.596  6400  6400 W art     : b58cf000-b58eb000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 18:36:11.596  6400  6400 W art     : b58eb000-b58ec000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 18:36:11.596  6400  6400 W art     : b58ec000-b58ed000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 18:36:11.596  6400  6400 W art     : b58ee000-b594f000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-12 18:36:11.596  6400  6400 W art     : b594f000-b5951000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-12 18:36:11.596  6400  6400 W art     : b5951000-b5952000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-12 18:36:11.596  6400  6400 W art     : b5953000-b597a000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-12 18:36:11.596  6400  6400 W art     : b597a000-b597b000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b597b000-b597c000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-12 18:36:11.596  6400  6400 W art     : b597c000-b597d000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-12 18:36:11.596  6400  6400 W art     : b597e000-b5986000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 18:36:11.596  6400  6400 W art     : b5986000-b5988000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 18:36:11.596  6400  6400 W art     : b5988000-b5989000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 18:36:11.596  6400  6400 W art     : b598a000-b598d000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-12 18:36:11.596  6400  6400 W art     : b598d000-b598e000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-12 18:36:11.596  6400  6400 W art     : b598e000-b598f000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-12 18:36:11.596  6400  6400 W art     : b598f000-b5993000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-12 18:36:11.596  6400  6400 W art     : b5993000-b5994000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b5994000-b5995000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-12 18:36:11.596  6400  6400 W art     : b5995000-b5996000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-12 18:36:11.596  6400  6400 W art     : b5996000-b59a6000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-12 18:36:11.596  6400  6400 W art     : b59a6000-b59a7000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-12 18:36:11.596  6400  6400 W art     : b59a7000-b59a8000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-12 18:36:11.596  6400  6400 W art     : b59a8000-b59ee000 rw-p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b59ee000-b59f7000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-12 18:36:11.596  6400  6400 W art     : b59f7000-b59f8000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-12 18:36:11.596  6400  6400 W art     : b59f8000-b59f9000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-12 18:36:11.596  6400  6400 W art     : b59fa000-b59ff000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-12 18:36:11.596  6400  6400 W art     : b59ff000-b5a00000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-12 18:36:11.596  6400  6400 W art     : b5a00000-b5a01000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-12 18:36:11.596  6400  6400 W art     : b5a01000-b5a04000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 18:36:11.596  6400  6400 W art     : b5a04000-b5a05000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b5a05000-b5a06000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 18:36:11.596  6400  6400 W art     : b5a06000-b5a07000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 18:36:11.596  6400  6400 W art     : b5a08000-b5a20000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 18:36:11.596  6400  6400 W art     : b5a20000-b5a21000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b5a21000-b5a22000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 18:36:11.596  6400  6400 W art     : b5a22000-b5a23000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 18:36:11.596  6400  6400 W art     : b5a23000-b5a24000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 18:36:11.596  6400  6400 W art     : b5a24000-b5bbe000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-12 18:36:11.596  6400  6400 W art     : b5bbe000-b5bbf000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b5bbf000-b5bcc000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-12 18:36:11.596  6400  6400 W art     : b5bcc000-b5bcd000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-12 18:36:11.596  6400  6400 W art     : b5bcd000-b5bd1000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-12 18:36:11.596  6400  6400 W art     : b5bd1000-b5bd2000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b5bd2000-b5bd3000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-12 18:36:11.596  6400  6400 W art     : b5bd3000-b5bd4000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-12 18:36:11.596  6400  6400 W art     : b5bd4000-b5be7000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-12 18:36:11.596  6400  6400 W art     : b5be7000-b5be8000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-12 18:36:11.596  6400  6400 W art     : b5be8000-b5be9000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-12 18:36:11.596  6400  6400 W art     : b5bea000-b5c35000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-12 18:36:11.596  6400  6400 W art     : b5c35000-b5c36000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-12 18:36:11.596  6400  6400 W art     : b5c36000-b5c37000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-12 18:36:11.596  6400  6400 W art     : b5c37000-b5c39000 rw-p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b5c3a000-b5c4b000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 18:36:11.596  6400  6400 W art     : b5c4b000-b5c4c000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b5c4c000-b5c4d000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 18:36:11.596  6400  6400 W art     : b5c4d000-b5c4e000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 18:36:11.596  6400  6400 W art     : b5c4e000-b5c4f000 r--p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b5c4f000-b5c59000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-12 18:36:11.596  6400  6400 W art     : b5c59000-b5c5b000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-12 18:36:11.596  6400  6400 W art     : b5c5b000-b5c5c000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-12 18:36:11.596  6400  6400 W art     : b5c5c000-b5c75000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-12 18:36:11.596  6400  6400 W art     : b5c75000-b5c76000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-12 18:36:11.596  6400  6400 W art     : b5c76000-b5c79000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-12 18:36:11.596  6400  6400 W art     : b5c79000-b5c7d000 rw-p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b5c7d000-b5cf1000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-12 18:36:11.596  6400  6400 W art     : b5cf1000-b5cf2000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b5cf2000-b5cf5000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-12 18:36:11.596  6400  6400 W art     : b5cf5000-b5cf6000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-12 18:36:11.596  6400  6400 W art     : b5cf6000-b5cf7000 r--p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b5cf7000-b5cfa000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-12 18:36:11.596  6400  6400 W art     : b5cfa000-b5cfb000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-12 18:36:11.596  6400  6400 W art     : b5cfb000-b5cfc000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-12 18:36:11.596  6400  6400 W art     : b5cfc000-b5cfd000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:36:11.596  6400  6400 W art     : b5cfd000-b5d02000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 18:36:11.596  6400  6400 W art     : b5d02000-b5d03000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 18:36:11.596  6400  6400 W art     : b5d03000-b5d04000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 18:36:11.596  6400  6400 W art     : b5d04000-b5d05000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:36:11.596  6400  6400 W art     : b5d05000-b5d08000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 18:36:11.596  6400  6400 W art     : b5d08000-b5d09000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 18:36:11.596  6400  6400 W art     : b5d09000-b5d0a000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 18:36:11.596  6400  6400 W art     : b5d0a000-b5d0b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:36:11.596  6400  6400 W art     : b5d0b000-b5d0f000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-12 18:36:11.596  6400  6400 W art     : b5d0f000-b5d10000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-12 18:36:11.596  6400  6400 W art     : b5d10000-b5d11000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-12 18:36:11.596  6400  6400 W art     : b5d11000-b5d12000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 18:36:11.596  6400  6400 W art     : b5d12000-b5d16000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 18:36:11.596  6400  6400 W art     : b5d16000-b5d17000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 18:36:11.596  6400  6400 W art     : b5d17000-b5d18000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 18:36:11.596  6400  6400 W art     : b5d18000-b5d19000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:36:11.596  6400  6400 W art     : b5d19000-b5d27000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-12 18:36:11.596  6400  6400 W art     : b5d27000-b5d28000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b5d28000-b5d29000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-12 18:36:11.596  6400  6400 W art     : b5d29000-b5d2a000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-12 18:36:11.596  6400  6400 W art     : b5d2a000-b5d34000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 18:36:11.596  6400  6400 W art     : b5d34000-b5d37000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 18:36:11.596  6400  6400 W art     : b5d37000-b5d38000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 18:36:11.596  6400  6400 W art     : b5d38000-b5d39000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:36:11.596  6400  6400 W art     : b5d39000-b5d43000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-12 18:36:11.596  6400  6400 W art     : b5d43000-b5d46000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-12 18:36:11.596  6400  6400 W art     : b5d46000-b5d47000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-12 18:36:11.596  6400  6400 W art     : b5d47000-b5d4b000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-12 18:36:11.596  6400  6400 W art     : b5d4b000-b5d4c000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-12 18:36:11.596  6400  6400 W art     : b5d4c000-b5d4d000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-12 18:36:11.596  6400  6400 W art     : b5d4d000-b5d4e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:36:11.596  6400  6400 W art     : b5d4e000-b5d5b000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-12 18:36:11.596  6400  6400 W art     : b5d5b000-b5d5d000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-12 18:36:11.596  6400  6400 W art     : b5d5d000-b5d5e000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-12 18:36:11.596  6400  6400 W art     : b5d5e000-b6170000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-12 18:36:11.596  6400  6400 W art     : b6170000-b6171000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b6171000-b617a000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-12 18:36:11.596  6400  6400 W art     : b617a000-b617e000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-12 18:36:11.596  6400  6400 W art     : b617e000-b617f000 rw-p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b617f000-b6186000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-12 18:36:11.596  6400  6400 W art     : b6186000-b6187000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-12 18:36:11.596  6400  6400 W art     : b6187000-b6188000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-12 18:36:11.596  6400  6400 W art     : b6188000-b6189000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:36:11.596  6400  6400 W art     : b6189000-b61a4000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-12 18:36:11.596  6400  6400 W art     : b61a4000-b61a5000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-12 18:36:11.596  6400  6400 W art     : b61a5000-b61a6000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-12 18:36:11.596  6400  6400 W art     : b61a6000-b61a7000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:36:11.596  6400  6400 W art     : b61a7000-b61f3000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 18:36:11.596  6400  6400 W art     : b61f3000-b61f4000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b61f4000-b61f5000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 18:36:11.596  6400  6400 W art     : b61f5000-b61f6000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 18:36:11.596  6400  6400 W art     : b61f6000-b61f7000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:36:11.596  6400  6400 W art     : b61f7000-b61fb000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-12 18:36:11.596  6400  6400 W art     : b61fb000-b61fc000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b61fc000-b61fd000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-12 18:36:11.596  6400  6400 W art     : b61fd000-b61fe000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-12 18:36:11.596  6400  6400 W art     : b61fe000-b6236000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-12 18:36:11.596  6400  6400 W art     : b6236000-b6237000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-12 18:36:11.596  6400  6400 W art     : b6237000-b6238000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-12 18:36:11.596  6400  6400 W art     : b6238000-b6239000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:36:11.596  6400  6400 W art     : b6239000-b62d7000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-12 18:36:11.596  6400  6400 W art     : b62d7000-b62d8000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b62d8000-b62f6000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-12 18:36:11.596  6400  6400 W art     : b62f6000-b62f7000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-12 18:36:11.596  6400  6400 W art     : b62f7000-b646a000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-12 18:36:11.596  6400  6400 W art     : b646a000-b6475000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-12 18:36:11.596  6400  6400 W art     : b6475000-b6476000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-12 18:36:11.596  6400  6400 W art     : b6476000-b658d000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-12 18:36:11.596  6400  6400 W art     : b658d000-b6598000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-12 18:36:11.596  6400  6400 W art     : b6598000-b6599000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-12 18:36:11.596  6400  6400 W art     : b6599000-b659d000 rw-p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b659d000-b65c1000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-12 18:36:11.596  6400  6400 W art     : b65c1000-b65c3000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-12 18:36:11.596  6400  6400 W art     : b65c3000-b65c4000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-12 18:36:11.596  6400  6400 W art     : b65c4000-b666a000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-12 18:36:11.596  6400  6400 W art     : b666a000-b6677000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-12 18:36:11.596  6400  6400 W art     : b6677000-b6678000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-12 18:36:11.596  6400  6400 W art     : b6678000-b6679000 rw-p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b6679000-b66cc000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-12 18:36:11.596  6400  6400 W art     : b66cc000-b66cd000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b66cd000-b66ce000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-12 18:36:11.596  6400  6400 W art     : b66ce000-b66cf000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-12 18:36:11.596  6400  6400 W art     : b66cf000-b66d4000 rw-p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b66d4000-b66e6000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-12 18:36:11.596  6400  6400 W art     : b66e6000-b66e7000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b66e7000-b66e8000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-12 18:36:11.596  6400  6400 W art     : b66e8000-b66e9000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-12 18:36:11.596  6400  6400 W art     : b66e9000-b66f0000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 18:36:11.596  6400  6400 W art     : b66f0000-b66f1000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 18:36:11.596  6400  6400 W art     : b66f1000-b66f2000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 18:36:11.596  6400  6400 W art     : b66f2000-b66f3000 rw-p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b66f3000-b66f6000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-12 18:36:11.596  6400  6400 W art     : b66f6000-b66f7000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-12 18:36:11.596  6400  6400 W art     : b66f7000-b66f8000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-12 18:36:11.596  6400  6400 W art     : b66f8000-b66fc000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-12 18:36:11.596  6400  6400 W art     : b66fc000-b66fd000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-12 18:36:11.596  6400  6400 W art     : b66fd000-b66fe000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-12 18:36:11.596  6400  6400 W art     : b66fe000-b670c000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-12 18:36:11.596  6400  6400 W art     : b670c000-b670d000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b670d000-b670e000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-12 18:36:11.596  6400  6400 W art     : b670e000-b670f000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-12 18:36:11.596  6400  6400 W art     : b670f000-b6718000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 18:36:11.596  6400  6400 W art     : b6718000-b6719000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 18:36:11.596  6400  6400 W art     : b6719000-b671a000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 18:36:11.596  6400  6400 W art     : b671a000-b6780000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-12 18:36:11.596  6400  6400 W art     : b6780000-b6781000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b6781000-b6783000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-12 18:36:11.596  6400  6400 W art     : b6783000-b678c000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-12 18:36:11.596  6400  6400 W art     : b678c000-b678f000 rw-p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b678f000-b6826000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-12 18:36:11.596  6400  6400 W art     : b6826000-b6828000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-12 18:36:11.596  6400  6400 W art     : b6828000-b6829000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-12 18:36:11.596  6400  6400 W art     : b6829000-b682a000 rw-p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b682a000-b6b4b000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-12 18:36:11.596  6400  6400 W art     : b6b4b000-b6b4c000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b6b4c000-b6b67000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-12 18:36:11.596  6400  6400 W art     : b6b67000-b6b6b000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-12 18:36:11.596  6400  6400 W art     : b6b6b000-b6b70000 rw-p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b6b70000-b6b78000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 18:36:11.596  6400  6400 W art     : b6b78000-b6b79000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 18:36:11.596  6400  6400 W art     : b6b79000-b6b7a000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 18:36:11.596  6400  6400 W art     : b6b7a000-b6ba8000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-12 18:36:11.596  6400  6400 W art     : b6ba8000-b6ba9000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b6ba9000-b6bb0000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-12 18:36:11.596  6400  6400 W art     : b6bb0000-b6bb1000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-12 18:36:11.596  6400  6400 W art     : b6bb1000-b6bf7000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-12 18:36:11.596  6400  6400 W art     : b6bf7000-b6bf8000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b6bf8000-b6bfb000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-12 18:36:11.596  6400  6400 W art     : b6bfb000-b6bfc000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-12 18:36:11.596  6464  6464 E Zygote  : v2
08-12 18:36:11.596  6400  6400 W art     : b6bfc000-b6c17000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-12 18:36:11.646   751  2413 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-12 18:36:11.596  6400  6400 W art     : b6c17000-b6c1b000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-12 18:36:11.596  6400  6400 W art     : b6c1b000-b6c1c000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-12 18:36:11.596  6400  6400 W art     : b6c1c000-b6c69000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-12 18:36:11.596  6400  6400 W art     : b6c69000-b6c6a000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b6c6a000-b6c76000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-12 18:36:11.596  6400  6400 W art     : b6c76000-b6c77000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-12 18:36:11.596  6400  6400 W art     : b6c77000-b6c84000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-12 18:36:11.596  6400  6400 W art     : b6c84000-b6c85000 ---p 00000000 00:00 0 
08-12 18:36:11.596  6400  6400 W art     : b6c85000-b6c86000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-12 18:36:11.596  6400  6400 W art     : b6c86000-b6c87000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-12 18:36:11.596  6400  6400 W art     : b6c87000-b6c8f000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-12 18:36:11.596  6400  6400 W art     : b6c8f000-b6c90000 ---p 00000000 00:00 0 
08-12 18:36:11.606  6400  6400 W art     : b6c90000-b6c91000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-12 18:36:11.606  6400  6400 W art     : b6c91000-b6c92000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-12 18:36:11.606  6400  6400 W art     : b6c92000-b6c99000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-12 18:36:11.606  6400  6400 W art     : b6c99000-b6c9a000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-12 18:36:11.606  6400  6400 W art     : b6c9a000-b6c9b000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-12 18:36:11.606  6400  6400 W art     : b6c9b000-b6caf000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-12 18:36:11.606  6400  6400 W art     : b6caf000-b6cb1000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-12 18:36:11.606  6400  6400 W art     : b6cb1000-b6cb2000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-12 18:36:11.606  6464  6464 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:36:11.606  6400  6400 W art     : b6cb2000-b6cda000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-12 18:36:11.606  6400  6400 W art     : b6cda000-b6cdc000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-12 18:36:11.606  6400  6400 W art     : b6cdc000-b6cdd000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-12 18:36:11.606  6464  6464 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 18:36:11.606  6400  6400 W art     : b6cdd000-b6ce0000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-12 18:36:11.606  6400  6400 W art     : b6ce0000-b6ce1000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-12 18:36:11.606  6400  6400 W art     : b6ce1000-b6ce2000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-12 18:36:11.606  6400  6400 W art     : b6ce2000-b6ceb000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-12 18:36:11.606  6400  6400 W art     : b6ceb000-b6cec000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-12 18:36:11.606  6400  6400 W art     : b6cec000-b6ced000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-12 18:36:11.606  6400  6400 W art     : b6ced000-b6d0d000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-12 18:36:11.606  6400  6400 W art     : b6d0d000-b6d0e000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-12 18:36:11.606  6400  6400 W art     : b6d0e000-b6d0f000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-12 18:36:11.606  6400  6400 W art     : b6d0f000-b6d82000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-12 18:36:11.606  6400  6400 W art     : b6d82000-b6d86000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-12 18:36:11.606  6400  6400 W art     : b6d86000-b6d89000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-12 18:36:11.606  6400  6400 W art     : b6d89000-b6d93000 rw-p 00000000 00:00 0 
08-12 18:36:11.606  6400  6400 W art     : b6d93000-b6e1b000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-12 18:36:11.606  6400  6400 W art     : b6e1b000-b6e1c000 ---p 00000000 00:00 0 
08-12 18:36:11.606  6400  6400 W art     : b6e1c000-b6e20000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-12 18:36:11.606  6400  6400 W art     : b6e20000-b6e21000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-12 18:36:11.606  6400  6400 W art     : b6e21000-b6e22000 rw-p 00000000 00:00 0 
08-12 18:36:11.606  6400  6400 W art     : b6e22000-b6e4b000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-12 18:36:11.606  6400  6400 W art     : b6e4b000-b6e4c000 ---p 00000000 00:00 0 
08-12 18:36:11.606  6400  6400 W art     : b6e4c000-b6e4f000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-12 18:36:11.606  6400  6400 W art     : b6e4f000-b6e50000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-12 18:36:11.606  6400  6400 W art     : b6e50000-b6f2a000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 18:36:11.606  6400  6400 W art     : b6f2a000-b6f31000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 18:36:11.606  6400  6400 W art     : b6f31000-b6f39000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 18:36:11.606  6400  6400 W art     : b6f39000-b6f3a000 rw-p 00000000 00:00 0 
08-12 18:36:11.606  6400  6400 W art     : b6f3a000-b6f3b000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 18:36:11.606  6400  6400 W art     : b6f3b000-b6f3c000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-12 18:36:11.606  6400  6400 W art     : b6f3c000-b6f3d000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:36:11.606  6400  6400 W art     : b6f3d000-b6f40000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:36:11.606  6400  6400 W art     : b6f40000-b6f65000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-12 18:36:11.606  6400  6400 W art     : b6f65000-b6f66000 ---p 00000000 00:00 0 
08-12 18:36:11.606  6400  6400 W art     : b6f66000-b6f6d000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-12 18:36:11.606  6400  6400 W art     : b6f6d000-b6f6e000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-12 18:36:11.606  6400  6400 W art     : b6f6e000-b6f,75000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-12 18:36:11.606  6400  6400 W art     : b6f75000-b6f76000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-12 18:36:11.606  6400  6400 W art     : b6f76000-b6f77000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-12 18:36:11.606  6400  6400 W art     : b6f77000-b6f78000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:36:11.606  6400  6400 W art     : b6f78000-b6f90000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-12 18:36:11.606  6400  6400 W art     : b6f90000-b6f91000 ---p 00000000 00:00 0 
08-12 18:36:11.606  6400  6400 W art     : b6f91000-b6f92000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-12 18:36:11.606  6400  6400 W art     : b6f92000-b6f93000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-12 18:36:11.606  6400  6400 W art     : b6f93000-b6fa1000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-12 18:36:11.606  6400  6400 W art     : b6fa1000-b6fa2000 ---p 00000000 00:00 0 
08-12 18:36:11.606  6400  6400 W art     : b6fa2000-b6fa3000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-12 18:36:11.606  6400  6400 W art     : b6fa3000-b6fa4000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-12 18:36:11.606  6400  6400 W art     : b6fa4000-b6fa5000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 18:36:11.606  6400  6400 W art     : b6fa5000-b6fa7000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:36:11.606  6400  6400 W art     : b6fa7000-b6fa8000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:36:11.606  6400  6400 W art     : b6fa8000-b6fa9000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 18:36:11.606  6400  6400 W art     : b6fa9000-b6faa000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-12 18:36:11.606  6400  6400 W art     : b6faa000-b6fab000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:36:11.606  6400  6400 W art     : b6fab000-b6fcb000 r--s 00000000 00:0b 9219       /dev/__properties__
08-12 18:36:11.606  6400  6400 W art     : b6fcb000-b6fcc000 r--p 00000000 00:00 0 
08-12 18:36:11.606  6400  6400 W art     : b6fcc000-b6fcd000 ---p 00000000 00:00 0 
08-12 18:36:11.606  6400  6400 W art     : b6fcd000-b6fcf000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-12 18:36:11.606  6400  6400 W art     : b6fcf000-b6fd0000 r-xp 00000000 00:00 0          [sigpage]
08-12 18:36:11.606  6400  6400 W art     : b6fd0000-b6feb000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-12 18:36:11.606  6400  6400 W art     : b6feb000-b6fec000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-12 18:36:11.606  6400  6400 W art     : b6fec000-b6fee000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-12 18:36:11.606  6464  6464 E Zygote  : accessInfo : 0
08-12 18:36:11.606  6400  6400 W art     : b6fee000-b6ff0000 rw-p 00000000 00:00 0 
08-12 18:36:11.606  6400  6400 W art     : b6ff0000-b6ff5000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-12 18:36:11.606  6400  6400 W art     : b6ff5000-b6ff6000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-12 18:36:11.606  6400  6400 W art     : b6ff6000-b6ff7000 rw-p 00000000 00:00 0 
08-12 18:36:11.606  6400  6400 W art     : be976000-be997000 rw-p 00000000 00:00 0          [stack]
08-12 18:36:11.606  6400  6400 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-12 18:36:11.606  6464  6464 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.myfiles 
08-12 18:36:11.646  6400  6400 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-12 18:36:11.676  6464  6464 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 18:36:11.676  6464  6464 D ActivityThread: Added TimaKeyStore provider
08-12 18:36:11.686   751  1416 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{87f8e45 6464:com.sec.android.app.myfiles/u0a50}
08-12 18:36:11.686   751  1686 I ActivityManager: Killing 5520:com.sec.android.GeoLookout/u0a112 (adj 15): DHA:empty #37
08-12 18:36:11.686  6400  6400 I Radio-JNI: register_android_hardware_Radio DONE
08-12 18:36:11.696  6464  6464 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.sec.android.app.myfiles rsrc of package null
08-12 18:36:11.696  6400  6400 E AffinityControl: AffinityControl: registerfunction enter
08-12 18:36:11.706   751  1603 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.GeoLookout, Auto Run ON
08-12 18:36:11.716  6464  6464 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMyFiles2014/lib/arm
08-12 18:36:11.716  6400  6400 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-12 18:36:11.726   751  2336 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-12 18:36:11.736   751  2336 D ActivityManager: mDVFSHelper.acquire()
08-12 18:36:11.736   751  2336 V WindowManager: addAppToken: AppWindowToken{d5f6aa8 token=Token{d6cf2cb ActivityRecord{a06c99a u0 com.test.thalitest/.MainActivity t168}}} to stack=1 task=168 at 0
08-12 18:36:11.746   751   887 D SecWifiDisplayUtil: Metadata value : none
08-12 18:36:11.746   751   887 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{f5ae6c0 V.E...... R.....ID 0,0-0,0}
08-12 18:36:11.746   751   887 D ISSUE_DEBUG: InputChannelName : 4743b3e Starting com.test.thalitest
08-12 18:36:11.756   751  2336 I ActivityManager: Start proc 6490:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-12 18:36:11.756   751  2336 D InputDispatcher: Focused application set to: xxxx
08-12 18:36:11.756  6490  6490 E Zygote  : v2
08-12 18:36:11.756  6490  6490 I libpersona: KNOX_SDCARD checking this for 10004
08-12 18:36:11.756  6490  6490 I libpersona: KNOX_SDCARD not a persona
08-12 18:36:11.756  6490  6490 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:36:11.756  6490  6490 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 18:36:11.756   751  2336 D InputDispatcher: Focus left window: 3506
08-12 18:36:11.756  6490  6490 E Zygote  : accessInfo : 0
08-12 18:36:11.756  6490  6490 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-12 18:36:11.756   751   839 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{6466612 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-12 18:36:11.756   751  1323 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-12 18:36:11.756  1384  1384 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
08-12 18:36:11.756  6400  6400 D AndroidRuntime: Shutting down VM
08-12 18:36:11.766   293   293 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, uhalitest
08-12 18:36:11.766  6464  6464 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-12 18:36:11.776  6490  6490 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 18:36:11.776  6490  6490 D ActivityThread: Added TimaKeyStore provider
08-12 18:36:11.786   751   887 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:751 uid:1000
08-12 18:36:11.786   751   887 D PointerIcon: setMouseCustomIcon IconType is same.101
08-12 18:36:11.786   751   887 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:751 uid:1000
08-12 18:36:11.786   751   887 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-12 18:36:11.786   751   887 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-12 18:36:11.786   751  2413 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d6a7766 2848:com.android.settings/1000}
08-12 18:36:11.786   334   334 E installd: system dir 0 : /system/app/
08-12 18:36:11.786   751  1949 V WindowOrientationListener: setCurrentAppOrientation :-1
08-12 18:36:11.786   334   334 E installd: system dir 1 : /system/priv-app/
08-12 18:36:11.786   751  1949 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-12 18:36:11.786   334   334 E installd: system dir 2 : /vendor/app/
08-12 18:36:11.786   334   334 E installd: system dir 3 : /oem/app/
08-12 18:36:11.796   751  1949 D ActivityManager:  Launching com.test.thalitest, updated priority
08-12 18:36:11.806   751   912 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-12 18:36:11.806   751   837 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-12 18:36:11.816  1742  1872 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-12 18:36:11.816  1742  1742 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-12 18:36:11.826   293   324 D libEGL  : eglTerminate EGLDisplay = 0xb69c164c
08-12 18:36:11.836   293  1297 D libEGL  : eglTerminate EGLDisplay = 0xb1fc964c
08-12 18:36:11.836   293  1297 D libEGL  : eglTerminate EGLDisplay = 0xb1fc964c
08-12 18:36:11.836   293   329 I SurfaceFlinger: id=19 Removed VSBConnecti (7/11)
08-12 18:36:11.836   293  1296 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/11)
08-12 18:36:11.836   751   887 V WindowStateAnimator: Finishing drawing window Window{4743b3e u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-12 18:36:11.836  3506  3506 V ActivityThread: updateVisibility : ActivityRecord{4871598 token=android.os.BinderProxy@a0b0bb2 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
08-12 18:36:11.846   293   329 I SurfaceFlinger: id=8 Removed Mauncher (4/10)
08-12 18:36:11.846   293  1297 I SurfaceFlinger: id=8 Removed Mauncher (-2/10)
08-12 18:36:11.846   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe86d3a4
08-12 18:36:11.846   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe86d3a4
08-12 18:36:11.846   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe86d364
08-12 18:36:11.846  2265  6166 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-12 18:36:11.846  1742  1742 V ActivityThread: updateVisibility : ActivityRecord{d6f9f22 token=android.os.BinderProxy@6aef634 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-12 18:36:11.846  1742  1742 D Launcher: onTrimMemory. Level: 20
08-12 18:36:11.866   293  1296 I SurfaceFlinger: id=20 Removed VSBConnecti (4/9)
08-12 18:36:11.866   293   329 I SurfaceFlinger: id=20 Removed VSBConnecti (-2/9)
08-12 18:36:11.876   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe86d3a4
08-12 18:36:11.956   751  1236 V AlarmManager: Expired Alarm result :4
,08-12 18:36:12.106   751  1949 I WindowManager: Screenshot max retries 4 of Token{d6cf2cb ActivityRecord{a06c99a u0 com.test.thalitest/.MainActivity t168}} appWin=Window{4743b3e u0 d0 Starting com.test.thalitest} drawState=4
,08-12 18:36:12.126   751   837 I ActivityManager: Start proc 6505:com.samsung.aasaservice/u0a210 for service com.samsung.aasaservice/.AASAService
,08-12 18:36:12.126  6505  6505 E Zygote  : v2
08-12 18:36:12.126  6505  6505 I libpersona: KNOX_SDCARD checking this for 10210
08-12 18:36:12.126  6505  6505 I libpersona: KNOX_SDCARD not a persona
,08-12 18:36:12.126  6505  6505 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:36:12.126  6505  6505 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 18:36:12.126  6505  6505 E Zygote  : accessInfo : 0
08-12 18:36:12.126  6505  6505 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
,08-12 18:36:12.136  6490  6490 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-12 18:36:12.136   751  2413 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d6a7766 2848:com.android.settings/1000}
,08-12 18:36:12.156  6517  6517 E Zygote  : v2
,08-12 18:36:12.156  6517  6517 I libpersona: KNOX_SDCARD checking this for 10169
08-12 18:36:12.156  6517  6517 I libpersona: KNOX_SDCARD not a persona
,08-12 18:36:12.156  6517  6517 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:36:12.156   751   837 I ActivityManager: Start proc 6517:com.samsung.android.provider.shootingmodeprovider/u0a169 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
,08-12 18:36:12.156  6517  6517 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 18:36:12.156  6517  6517 E Zygote  : accessInfo : 0
,08-12 18:36:12.156  6517  6517 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
,08-12 18:36:12.156   751  1323 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-12 18:36:12.156   751   839 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{4743b3e u0 d0 Starting com.test.thalitest}
,08-12 18:36:12.166  1384  1384 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
,08-12 18:36:12.176   751  3443 D SSRM:n  : SIOP:: AP = 450, PST = 451, CUR = 450, LCD = 0
,08-12 18:36:12.176  6490  6490 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-12 18:36:12.176   751  3443 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-12 18:36:12.176  6490  6490 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-12 18:36:12.186  6505  6505 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 18:36:12.186  6505  6505 D ActivityThread: Added TimaKeyStore provider
,08-12 18:36:12.196  6517  6517 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 18:36:12.196  6517  6517 D ActivityThread: Added TimaKeyStore provider
,08-12 18:36:12.196   751  2415 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a0424bb 6517:com.samsung.android.provider.shootingmodeprovider/u0a169}
,08-12 18:36:12.196  6490  6490 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-12 18:36:12.206  6505  6505 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
,08-12 18:36:12.206  6517  6517 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package null
,08-12 18:36:12.216  6505  6505 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
,08-12 18:36:12.226  6490  6490 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-12 18:36:12.226  6517  6517 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm
,08-12 18:36:12.226  6505  6505 D AASAservice: onCreate()
,08-12 18:36:12.226  6490  6490 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-12 18:36:12.226  5357  5357 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
08-12 18:36:12.226   751   766 I ActivityManager: Killing 5538:com.sec.android.app.popupuireceiver/1000 (adj 15): DHA:empty #37
,08-12 18:36:12.236   751  2390 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.popupuireceiver, Auto Run ON
,08-12 18:36:12.246  6490  6490 I cr_LibraryLoader: Time to load native libraries: 11 ms (timestamps 9949-9960)
08-12 18:36:12.246  6490  6490 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-12 18:36:12.246   751  1948 I ActivityManager: Killing 5108:com.samsung.dcm:DCMService/5004 (adj 15): DHA:empty #37
,08-12 18:36:12.256   751  1948 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fc85345 1724:com.android.phone/1001}
,08-12 18:36:12.256  6490  6490 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {bc711c4}
08-12 18:36:12.256  6490  6490 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-12 18:36:12.256  6490  6490 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 18:36:12.256   751  1948 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d78a65a 1826:com.google.android.googlequicksearchbox:search/u0a61}
,08-12 18:36:12.266  6490  6531 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-12 18:36:12.266  6490  6490 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-12 18:36:12.276   751  2390 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcm, Auto Run ON
,08-12 18:36:12.276   751  1412 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d78a65a 1826:com.google.android.googlequicksearchbox:search/u0a61}
,08-12 18:36:12.286   751  1412 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{63a7416 6322:com.samsung.android.sm.provider/1000}
,08-12 18:36:12.296  6490  6490 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-12 18:36:12.296  6490  6490 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-12 18:36:12.296  6490  6490 I Adreno-EGL: Build Date: 01/28/16 Thu
08-12 18:36:12.296  6490  6490 I Adreno-EGL: Local Branch: ss
08-12 18:36:12.296  6490  6490 I Adreno-EGL: Remote Branch: 
08-12 18:36:12.296  6490  6490 I Adreno-EGL: Local Patches: 
08-12 18:36:12.296  6490  6490 I Adreno-EGL: Reconstruct Branch: 
,08-12 18:36:12.306  6538  6538 E Zygote  : v2
08-12 18:36:12.306  6538  6538 I libpersona: KNOX_SDCARD checking this for 5012
08-12 18:36:12.306  6538  6538 I libpersona: KNOX_SDCARD not a persona
,08-12 18:36:12.306  6538  6538 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:36:12.306  6538  6538 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 18:36:12.306  6490  6490 D libEGL  : eglInitialize EGLDisplay = 0xbe8d5dac
,08-12 18:36:12.306  6538  6538 E Zygote  : accessInfo : 0
08-12 18:36:12.306  6538  6538 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.devicesecurity 
,08-12 18:36:12.306   751   766 I ActivityManager: Start proc 6538:com.samsung.android.sm.devicesecurity/5012 for broadcast-3 com.samsung.android.sm.devicesecurity/.PackageReceiver
,08-12 18:36:12.336  6538  6538 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 18:36:12.336  6538  6538 D ActivityThread: Added TimaKeyStore provider
,08-12 18:36:12.336   751  1948 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5465197 6538:com.samsung.android.sm.devicesecurity/5012}
,08-12 18:36:12.346   751  1494 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,08-12 18:36:12.346   751  1494 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,08-12 18:36:12.356  1826  6532 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-12 18:36:12.376  6538  6538 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_DeviceSecurity/SmartManager_v3_DeviceSecurity.apk / 1.0 running in com.samsung.android.sm.devicesecurity rsrc of package null
,08-12 18:36:12.396  6490  6490 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-12 18:36:12.396  6538  6538 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManager_v3_DeviceSecurity/lib/arm
,08-12 18:36:12.406  6490  6490 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-12 18:36:12.406  6490  6490 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-12 18:36:12.406  6490  6490 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-12 18:36:12.406  6490  6490 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-12 18:36:12.416  1826  6532 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
,08-12 18:36:12.426  6490  6490 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-12 18:36:12.426  1826  6532 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
,08-12 18:36:12.436  6490  6490 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-12 18:36:12.436   751  1603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6cf5d76 3198:com.android.contacts/u0a19}
,08-12 18:36:12.446  6566  6566 E Zygote  : v2
,08-12 18:36:12.446  6566  6566 I libpersona: KNOX_SDCARD checking this for 10049
08-12 18:36:12.456   751  1603 I ActivityManager: Start proc 6566:com.android.mms/u0a49 for broadcast-3 com.android.mms/.smishing.PackageInstallReceiver
08-12 18:36:12.456  6566  6566 I libpersona: KNOX_SDCARD not a persona
,08-12 18:36:12.456  6566  6566 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:36:12.456  6566  6566 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 18:36:12.456  6566  6566 E Zygote  : accessInfo : 0
,08-12 18:36:12.456  6566  6566 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.mms 
,08-12 18:36:12.456   751  1323 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-12 18:36:12.466   751  1323 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-12 18:36:12.486   751  1948 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10011
,08-12 18:36:12.486  6566  6566 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 18:36:12.486  6566  6566 D ActivityThread: Added TimaKeyStore provider
,08-12 18:36:12.496   751  1949 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fb19011 6566:com.android.mms/u0a49}
,08-12 18:36:12.516  6566  6566 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-12 18:36:12.536  6490  6490 D SecWifiDisplayUtil: Metadata value : none
,08-12 18:36:12.536  6490  6490 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{ec35f42 I.E...... R.....ID 0,0-0,0}
,08-12 18:36:12.546  6566  6566 W System  : ClassLoader referenced unknown path: imsmanager.jar
,08-12 18:36:12.546  6490  6582 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-12 18:36:12.546   751   767 D ISSUE_DEBUG: InputChannelName : 12fb302 com.test.thalitest/com.test.thalitest.MainActivity
,08-12 18:36:12.556   751  1948 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
,08-12 18:36:12.556   751  1948 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-12 18:36:12.556  6566  6566 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMms_Candy_M/lib/arm
08-12 18:36:12.556   751   751 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-12 18:36:12.556   751   751 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-12 18:36:12.566  4161  6579 W IcingInternalCorpora: getNumBytesRead when not calculated.
,08-12 18:36:12.586  6490  6490 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6490
,08-12 18:36:12.586   751  2336 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6490 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 18:36:12.586   751  1332 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-12 18:36:12.586   751  1332 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-12 18:36:12.596  6566  6566 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,08-12 18:36:12.596   751  1332 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-12 18:36:12.596   751  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-12 18:36:12.596   751  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,08-12 18:36:12.596   751  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-12 18:36:12.596   751  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-12 18:36:12.596   751  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-12 18:36:12.596   751  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,08-12 18:36:12.596   751  1332 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 18:36:12.596  6490  6490 D SecWifiDisplayUtil: Metadata value : none
,08-12 18:36:12.606  6490  6531 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-12 18:36:12.616   293   293 I SurfaceFlinger: id=22 createSurf (1x1),1 flag=404, NainActivit
,08-12 18:36:12.616  6566  6587 D Mms/ArtClassLoader: init before art second
,08-12 18:36:12.626   751  1603 D InputDispatcher: Focus entered window: 6490
,08-12 18:36:12.626  6566  6566 D Mms/TelephonyPermission: start operation mode monitor
08-12 18:36:12.626  6566  6566 D Mms/TelephonyPermission: User ID is null set current User Id
,08-12 18:36:12.626   751   887 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:751 uid:1000
08-12 18:36:12.626   751   887 D PointerIcon: setMouseCustomIcon IconType is same.101
08-12 18:36:12.626   751   887 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:751 uid:1000
08-12 18:36:12.626   751   887 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-12 18:36:12.626  6566  6586 D Mms/ArtClassLoader: init before art first
08-12 18:36:12.626  6490  6582 D libEGL  : eglInitialize EGLDisplay = 0x9ca3f7c4
08-12 18:36:12.626  6490  6582 I OpenGLRenderer: Initialized EGL, version 1.4
,08-12 18:36:12.636  6566  6588 D Mms/ArtClassLoader: init before art third
,08-12 18:36:12.636  6566  6566 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-12 18:36:12.646  6566  6566 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.mms rsrc of package null
,08-12 18:36:12.656  1826  6532 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 301 ms] updated apps [took 301 ms] 
,08-12 18:36:12.656  6566  6588 D Mms/ArtClassLoader: init [DONE] art
,08-12 18:36:12.666  6566  6566 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
,08-12 18:36:12.666  6566  6566 D Mms/TelephonyPermission: isDefault true
,08-12 18:36:12.666  6566  6566 D Mms/MmsApp: onCreate() com.android.mms
,08-12 18:36:12.686  6490  6490 V ActivityThread: updateVisibility : ActivityRecord{f0aa545 token=android.os.BinderProxy@aafd18d {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-12 18:36:12.686  6490  6490 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,08-12 18:36:12.696  6490  6490 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-12 18:36:12.696   751  1412 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-12 18:36:12.706  6490  6490 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-12 18:36:12.726   751  1686 V WindowStateAnimator: Finishing drawing window Window{12fb302 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-12 18:36:12.726  6490  6490 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-12 18:36:12.726  6490  6490 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@aafd18d time:110445
,08-12 18:36:12.736   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe86d364
,08-12 18:36:12.746   751   887 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-12 18:36:12.746   751   887 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +632ms (total +1s2ms)
08-12 18:36:12.746   751   751 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-12 18:36:12.746   751   887 D ActivityManager: mDVFSHelper.release()
08-12 18:36:12.746   751   887 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{a06c99a u0 com.test.thalitest/.MainActivity t168} time:110462
,08-12 18:36:12.746   751   751 I KnoxTimeoutHandler: SD activityfalse
08-12 18:36:12.746   751   887 D ViewRootImpl: #3 mView = null
,08-12 18:36:12.746   293   329 I SurfaceFlinger: id=21 Removed uhalitest (7/9)
,08-12 18:36:12.746   293  1297 I SurfaceFlinger: id=21 Removed uhalitest (-2/9)
,08-12 18:36:12.756   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe86d3a4
,08-12 18:36:12.766  6566  6566 D Mms/MessageUtils: getMessagingSimType() simSlotCount : 1
,08-12 18:36:12.766  6490  6593 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-12 18:36:12.766  6490  6593 D libEGL  : eglInitialize EGLDisplay = 0x9b4ea3ec
,08-12 18:36:12.766  6566  6566 D Mms/MmsApp: [start]    initCountryIso consume time = 177.485312
,08-12 18:36:12.786   751  1416 D CountryDetector: The first listener is added
,08-12 18:36:12.786  6566  6566 D Mms/MmsApp: [end]    initCountryIso consume time = 17.786667
08-12 18:36:12.786  6566  6566 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.099167
,08-12 18:36:12.806  6490  6490 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6490
,08-12 18:36:12.816  6566  6566 D Mms/MmsConfig: before partial update
,08-12 18:36:12.826  6566  6586 D Mms/ArtClassLoader: init [DONE] art
,08-12 18:36:12.846  6566  6566 D Mms/MmsConfig: Load Resize quality : 80
,08-12 18:36:12.856  6566  6566 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-12 18:36:12.856  6566  6566 D EasySignUpManager_1.0.5: isAuth is false
08-12 18:36:12.856  6566  6566 I EasySignUpManager_1.0.5: auth : false, join : 2
,08-12 18:36:12.856  6566  6566 D Mms/MmsConfig: getEasySignUpStatus - sIsAuthEasySignUp(isJoined(SERVICE_ID_RSHARE)) = false, TelephonyUtils.getSimState(0)= 1
,08-12 18:36:12.856  6566  6566 D EasySignUpManager_1.0.5: userSerialNumber = 0
,08-12 18:36:12.856  6566  6587 D Mms/ArtClassLoader: init [DONE] art
,08-12 18:36:12.866  6566  6566 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-12 18:36:12.866  6566  6566 D EasySignUpManager_1.0.5: serviceId : 1, features : -1
,08-12 18:36:12.866  6566  6566 D EasySignUpManager_1.0.5: isAuth is false
08-12 18:36:12.866  6566  6566 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-12 18:36:12.866  6566  6566 D EasySignUpManager_1.0.5: getServiceStatus : serviceId (1) is OFF
08-12 18:36:12.866  6566  6566 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 sIsAuthEasySignUp = false sIsFreeMessageServiceStatus = false
,08-12 18:36:12.866  1724  1937 D TP/MmsSmsProvider: query, match:2117, calling pid = 6566, accessRestricted = false
,08-12 18:36:12.876  1724  1937 D TP/MmsSmsProvider: query, match 2117:Elapsed time : 1.193 ms
,08-12 18:36:12.876  6566  6566 E CscParser: mps_code.dat does not exist
08-12 18:36:12.876  6566  6566 E CscParser: customer_path =/system/csc/customer.xml
08-12 18:36:12.876  6566  6566 E CscParser: fileName + /system/csc/customer.xml
,08-12 18:36:12.886  6566  6566 E CscParser: mps_code.dat does not exist
08-12 18:36:12.886  6566  6566 E CscParser: customer_path =/system/csc/customer.xml
08-12 18:36:12.886  6566  6566 E CscParser: fileName + /system/csc/customer.xml
,08-12 18:36:12.886  6490  6490 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 18:36:12.896  6566  6566 D CscParser: getInstance fileName =/system/csc/customer.xml
,08-12 18:36:12.896  6566  6566 D Mms/MmsConfig:  enable multiwindow = true
,08-12 18:36:12.896  6566  6566 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.RcsTransferContent
,08-12 18:36:12.896  6566  6566 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TmoRcsTransferContent
08-12 18:36:12.896  6566  6566 D Mms/MessageUtils: setComponentFreeMessage isChecked = false
,08-12 18:36:12.896  6566  6566 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TransferContent
08-12 18:36:12.896  6566  6566 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.ComposeMessageMms
,08-12 18:36:12.896  6566  6566 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-12 18:36:12.896  6566  6566 E Mms/MessageUtils: updateCountryIso : update country iso info 
,08-12 18:36:12.896  6566  6566 D Mms/MmsConfig: [end]    init() consume time = 113.363801
,08-12 18:36:12.906  6566  6566 D Mms/Contact: [start]    init() consume time = 8.233073
,08-12 18:36:12.926  1724  1932 D TP/MmsSmsProvider: query, match:13, calling pid = 6566, accessRestricted = false
,08-12 18:36:12.926  1724  1932 D TP/MmsSmsProvider: query, match 13:Elapsed time : 2.248 ms
,08-12 18:36:12.926  6566  6566 D Mms/Contact: [end]    init consume time = 17.295365
,08-12 18:36:12.926  6566  6604 D Mms/DraftCache: [start]    rebuildCache consume time = 4.088021
,08-12 18:36:12.936  6566  6566 D Mms:transaction: roaming -> false (slotId = 0)
08-12 18:36:12.936  6566  6566 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-12 18:36:12.936  6566  6566 D Mms:transaction: auto download without roaming -> true
08-12 18:36:12.936  6566  6566 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,08-12 18:36:12.936  6566  6566 D Mms:transaction: roaming -> false (slotId = 1)
08-12 18:36:12.936  6566  6566 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-12 18:36:12.936  6566  6566 D Mms:transaction: auto download without roaming -> true
08-12 18:36:12.936  6566  6566 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-12 18:36:12.936  6566  6566 D Mms:transaction: auto download during roaming secondary -> false
08-12 18:36:12.936  6566  6566 D Mms:transaction: mAutoDownload ------> true
,08-12 18:36:12.946  1724  1739 D TP/MmsSmsProvider: query, match:12, calling pid = 6566, accessRestricted = false
,08-12 18:36:12.946  1724  1739 D TP/MmsSmsProvider: query, match 12:Elapsed time : 1.293 ms
,08-12 18:36:12.946  6566  6604 D Mms/DraftCache: [end]    rebuildCache consume time = 19.999166
,08-12 18:36:12.956  6566  6566 D ComposerPerformance: 1471019772967 ms / [DONE] Composer constructor
,08-12 18:36:12.956  6566  6605 D Mms/Conversation: [start]    init() consume time = 7.08474
,08-12 18:36:12.956  6566  6566 D CII     : Log Level [5]
08-12 18:36:12.956  6566  6566 E CII     : IMSUtility: isIMSServiceEnabled. VoLTE CSC feature disabled.
,08-12 18:36:12.956  6566  6566 I Mms/ReservationManager: ReservationManager()
08-12 18:36:12.956  6566  6566 I Mms/ReservationManager: resetAfterConnected()
,08-12 18:36:12.956  1724  1932 D TP/MmsSmsProvider: delete, match:1, calling pid = 6566
08-12 18:36:12.956  1724  1932 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-12 18:36:12.956  1724  1932 V TP/MmsSmsProvider: deleteConversation delete_sys_msg: true finalSelection=thread_id = 9223372036854775807
,08-12 18:36:12.966  1724  1932 I TP/MmsSmsProvider: delete messages table selection : (thread_id = 9223372036854775807) AND (box_type = 3) null
,08-12 18:36:12.966  1724  1932 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-12 18:36:12.966  1724  1932 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,08-12 18:36:12.966  1724  1740 D TP/MmsSmsProvider: query, match:7, calling pid = 6566, accessRestricted = false
,08-12 18:36:12.966  1724  1740 D TP/MmsSmsProvider: query, match 7:Elapsed time : 1.799 ms
,08-12 18:36:12.976  6566  6566 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
08-12 18:36:12.976  1724  1932 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 118
,08-12 18:36:12.976  6566  6566 D Mms/MmsApp: [end]    onCreate() consume time = 19.708438
08-12 18:36:12.976  6566  6566 D Mms/MmsApp: [end]    onCreate() consume time = 0.081666
,08-12 18:36:12.986  1724  1932 V TP/MmsSmsDatabaseHelper: updateThread() end, affectedRows = 0
08-12 18:36:12.986  1724  1932 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0
08-12 18:36:12.986  1724  1932 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-12 18:36:12.986  1724  1932 D TP/MmsSmsProvider: delete, match 1:Elapsed time : 13.580 ms
08-12 18:36:12.986  1724  1932 D TP/MmsSmsProvider: need read changed broadcast:false
,08-12 18:36:12.986  6566  6605 D Mms/Conversation: [end]    init consume time = 5.139167
,08-12 18:36:12.986  6566  6605 D Mms/MessagingNotification: [start]    init() consume time = 5.111458
,08-12 18:36:12.986  6566  6566 D Mms:transaction: Service state changed: Bundle[mParcelledData.dataSize=1296]
,08-12 18:36:12.996  6566  6566 D Mms:transaction: roaming ------> false, mSimSlot = 0
,08-12 18:36:12.996  6566  6566 D Mms:transaction: roaming -> false (slotId = 0)
08-12 18:36:12.996  6566  6566 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-12 18:36:12.996  6566  6566 D Mms:transaction: auto download without roaming -> true
,08-12 18:36:12.996  6566  6566 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-12 18:36:12.996  6566  6566 D Mms:transaction: mAutoDownload ------> true
,08-12 18:36:12.996   751  1686 I ActivityManager: Start proc 6606:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
,08-12 18:36:12.996  6606  6606 E Zygote  : v2
08-12 18:36:12.996  6606  6606 I libpersona: KNOX_SDCARD checking this for 1000
08-12 18:36:12.996  6606  6606 I libpersona: KNOX_SDCARD not a persona
,08-12 18:36:13.006   751  1686 I ActivityManager: Killing 5141:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
,08-12 18:36:13.016  6606  6606 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:36:13.016  6606  6606 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 18:36:13.016  6606  6606 E Zygote  : accessInfo : 0
,08-12 18:36:13.036  6566  6605 D Mms/MessagingNotification: [end]    init consume time = 53.026875
,08-12 18:36:13.046  6606  6606 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 18:36:13.046  6606  6606 D ActivityThread: Added TimaKeyStore provider
,08-12 18:36:13.056  1724  1937 D TP/MmsSmsProvider: query, match:0, calling pid = 6566, accessRestricted = false
08-12 18:36:13.056  1724  1937 V TP/MmsSmsProvider: getSimpleConversations entered.
,08-12 18:36:13.056   751   767 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d0d26d6 6606:com.samsung.android.bbc.bbcagent/1000}
,08-12 18:36:13.056  1724  1937 D TP/MmsSmsProvider: query, match 0:Elapsed time : 4.831 ms
,08-12 18:36:13.076  6606  6606 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package null
,08-12 18:36:13.076  6080  6092 D BadgeProvider: query, [selection] : package=?
,08-12 18:36:13.076  6566  6619 D Mms/Synchronizer: [start]    doSync consume time = 34.110521
,08-12 18:36:13.086  6566  6605 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,08-12 18:36:13.086   751  2415 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
,08-12 18:36:13.096  1724  1932 D TP/MmsSmsProvider: update, match:300, calling pid = 6566
08-12 18:36:13.096  1724  1932 V TP/MmsSmsProvider: syncDBData start
,08-12 18:36:13.096  1724  1932 V TP/MmsSmsProvider: syncDBData sms end
,08-12 18:36:13.096  1724  1932 V TP/MmsSmsProvider: syncDBData mms end
,08-12 18:36:13.096  1724  1932 V TP/MmsSmsProvider: syncDBData end
,08-12 18:36:13.096  1724  1932 D TP/MmsSmsProvider: update, match 300:Elapsed time : 3.082 ms
,08-12 18:36:13.106  6566  6619 D Mms/Synchronizer: [end]    doSync consume time = 29.386459
,08-12 18:36:13.106  1724  1739 D TP/SmsProvider: query,matched:26, calling pid = 6566
08-12 18:36:13.106  6566  6618 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 0.432812
,08-12 18:36:13.106  1724  1739 D TP/SmsProvider: query, match 26:Elapsed time : 1.169 ms
,08-12 18:36:13.116  6490  6620 D jxcore_app_log: JniHelper::setJavaVM(0xb473c000), pthread_self() = -1695921872
,08-12 18:36:13.126  6490  6620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 18:36:13.126  6490  6620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 18:36:13.126  6490  6620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 18:36:13.126  6490  6620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 18:36:13.126  6490  6620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-12 18:36:13.126  6490  6620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c83f43 added. We now have 1 listener(s)
,08-12 18:36:13.126  6490  6620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-12 18:36:13.126  6490  6620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-12 18:36:13.126  6490  6620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 18:36:13.126  6490  6620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 18:36:13.126  1724  1740 D TP/MmsSmsProvider: query, match:6, calling pid = 6566, accessRestricted = false
,08-12 18:36:13.136  1724  1740 D TP/MmsSmsProvider: query, match 6:Elapsed time : 2.708 ms
,08-12 18:36:13.136  1724  1932 D TP/MmsSmsProvider: query, match:400, calling pid = 6566, accessRestricted = false
,08-12 18:36:13.136  6490  6620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 18:36:13.136  6490  6620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 18:36:13.136  6490  6620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 18:36:13.136  6490  6620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-12 18:36:13.136  6490  6620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 18:36:13.136  6490  6620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 18:36:13.136  6490  6620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 18:36:13.136  6490  6620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 18:36:13.136  6490  6620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 18:36:13.136  6490  6620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 18:36:13.136  6490  6620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 18:36:13.136  6490  6620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 18:36:13.136  6490  6620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 18:36:13.136  6490  6620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-12 18:36:13.136  6490  6620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac5163e added. We now have 1 listener(s)
,08-12 18:36:13.136  6490  6620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 18:36:13.146  6490  6620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-12 18:36:13.146  6490  6620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 18:36:13.146  6490  6620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 18:36:13.146  6490  6620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 18:36:13.146  6490  6620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-12 18:36:13.146  6566  6618 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 38.695886
,08-12 18:36:13.146   751  3444 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,08-12 18:36:13.146  6490  6620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 18:36:13.146  6490  6620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,08-12 18:36:13.156  6490  6620 D BluetoothAdapter: STATE_ON
,08-12 18:36:13.156  6490  6620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-12 18:36:13.156  6490  6620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 18:36:13.156  6490  6620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 18:36:13.156  6490  6620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 18:36:13.156  6490  6620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 18:36:13.156  6490  6620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 18:36:13.156  6490  6620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 18:36:13.156  6490  6620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 18:36:13.156  6490  6620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 18:36:13.156  6490  6620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 18:36:13.156  6490  6620 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-12 18:36:13.156  6490  6620 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-12 18:36:13.156  6490  6490 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 18:36:13.156  6606  6606 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm
,08-12 18:36:13.166  6490  6490 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 18:36:13.176   751  2336 I ActivityManager: Start proc 6622:com.wsomacp/u0a24 for content provider com.wsomacp/.db.XCPDBSqlProvider
,08-12 18:36:13.176  6622  6622 E Zygote  : v2
08-12 18:36:13.176  6622  6622 I libpersona: KNOX_SDCARD checking this for 10024
08-12 18:36:13.176  6622  6622 I libpersona: KNOX_SDCARD not a persona
08-12 18:36:13.176  6622  6622 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:36:13.176  6622  6622 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 18:36:13.176  6622  6622 E Zygote  : accessInfo : 0
08-12 18:36:13.176  6622  6622 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.wsomacp 
,08-12 18:36:13.196   751  3475 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 18:36:13.196  6490  6490 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 18:36:13.206  6622  6622 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 18:36:13.206  6622  6622 D ActivityThread: Added TimaKeyStore provider
,08-12 18:36:13.206   751  1416 I ActivityManager: Killing 5164:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,08-12 18:36:13.216   751   760 I art     : Background partial concurrent mark sweep GC freed 170995(10MB) AllocSpace objects, 12(2MB) LOS objects, 27% free, 42MB/58MB, paused 1.829ms total 166.532ms
,08-12 18:36:13.226  6622  6622 W ResourcesManager: getTopLevelResources: /system/priv-app/OmaCP/OmaCP.apk / 1.0 running in com.wsomacp rsrc of package null
,08-12 18:36:13.236   751  1494 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,08-12 18:36:13.256  6622  6622 W System  : ClassLoader referenced unknown path: /system/priv-app/OmaCP/lib/arm
,08-12 18:36:13.276  6634  6634 E Zygote  : v2
08-12 18:36:13.276  6634  6634 I libpersona: KNOX_SDCARD checking this for 10097
08-12 18:36:13.276  6634  6634 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:36:13.276  6634  6634 I libpersona: KNOX_SDCARD not a persona
08-12 18:36:13.276  6634  6634 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 18:36:13.276   751  2413 I ActivityManager: Start proc 6634:com.google.android.apps.docs/u0a97 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
08-12 18:36:13.276  6634  6634 E Zygote  : accessInfo : 0
08-12 18:36:13.276   751  2413 I ActivityManager: Killing 4646:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
08-12 18:36:13.276  6634  6634 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
,08-12 18:36:13.306  6634  6634 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 18:36:13.306  6634  6634 D ActivityThread: Added TimaKeyStore provider
,08-12 18:36:13.306   751  1948 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fd48729 6634:com.google.android.apps.docs/u0a97}
,08-12 18:36:13.316  6634  6634 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-12 18:36:13.336  6634  6634 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
,08-12 18:36:13.346  6622  6622 I OMACP   : [com.wsomacp.XCPApplication(51/onCreate)] CPApplication Start !
,08-12 18:36:13.356   751  1686 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,08-12 18:36:13.356  6566  6605 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-12 18:36:13.376  6622  6622 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,08-12 18:36:13.376  6622  6622 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,08-12 18:36:13.376  6622  6622 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,08-12 18:36:13.376  6622  6622 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,08-12 18:36:13.376  6622  6622 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,08-12 18:36:13.376  6622  6622 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,08-12 18:36:13.376  6622  6622 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,08-12 18:36:13.386  6622  6622 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,08-12 18:36:13.386  6622  6622 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,08-12 18:36:13.386  6622  6622 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,08-12 18:36:13.386  6622  6622 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,08-12 18:36:13.386  6622  6622 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,08-12 18:36:13.386  6622  6622 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-12 18:36:13.556  1453  1453 D Recents : onTaskStackChanged
,08-12 18:36:13.566  1453  1453 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-12 18:36:13.646  6634  6648 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
08-12 18:36:13.646  6634  6648 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-12 18:36:13.646  6634  6648 I GAv4    :   adb logcat -s GAv4
,08-12 18:36:13.676  6634  6648 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-12 18:36:13.676   751  2390 V AlarmManager:  remove PendingIntent] PendingIntent{b856ce5: PendingIntentRecord{d1b53ba com.google.android.apps.docs broadcastIntent}}
,08-12 18:36:13.676  4161  5019 I Icing   : Indexing 38360883C61536E4027A6B9191D49E9DF51837DC from com.google.android.googlequicksearchbox
,08-12 18:36:13.676  6634  6648 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-12 18:36:13.686  6634  6648 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-12 18:36:13.696  6634  6654 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-12 18:36:13.746  4161  5019 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-12 18:36:13.826  6634  6634 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/diskCache
,08-12 18:36:13.836  4161  5019 I Icing   : Indexing done 38360883C61536E4027A6B9191D49E9DF51837DC
,08-12 18:36:13.836  6634  6634 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,08-12 18:36:13.876  6634  6648 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
,08-12 18:36:13.876  6634  6648 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
08-12 18:36:13.876  6634  6648 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
,08-12 18:36:13.876  6634  6648 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,08-12 18:36:13.936  6660  6660 E Zygote  : v2
08-12 18:36:13.936  6660  6660 I libpersona: KNOX_SDCARD checking this for 10098
08-12 18:36:13.936  6660  6660 I libpersona: KNOX_SDCARD not a persona
08-12 18:36:13.936   751   766 I ActivityManager: Start proc 6660:com.sec.android.automotive.drivelink/u0a98 for broadcast-3 com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver
08-12 18:36:13.936  6660  6660 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:36:13.936  6660  6660 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 18:36:13.936  6660  6660 E Zygote  : accessInfo : 0
,08-12 18:36:13.936  6660  6660 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.automotive.drivelink 
08-12 18:36:13.936   751   766 I ActivityManager: Killing 5043:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
,08-12 18:36:13.966  6660  6660 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 18:36:13.966  6660  6660 D ActivityThread: Added TimaKeyStore provider
,08-12 18:36:13.976   751  1772 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{61af186 6660:com.sec.android.automotive.drivelink/u0a98}
,08-12 18:36:14.006   751  2390 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
,08-12 18:36:14.016  6660  6660 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-12 18:36:14.016  6490  6499 I art     : Background partial concurrent mark sweep GC freed 52679(5MB) AllocSpace objects, 10(1444KB) LOS objects, 44% free, 20MB/36MB, paused 6.311ms total 86.962ms
,08-12 18:36:14.036  6660  6660 W System  : ClassLoader referenced unknown path: /system/app/DriveLink/lib/arm
,08-12 18:36:14.066  6660  6660 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-12 18:36:14.076   751  1494 V AlarmManager:  remove PendingIntent] PendingIntent{2b3da47: PendingIntentRecord{cffc274 com.sec.android.automotive.drivelink broadcastIntent}}
,08-12 18:36:14.086  6660  6676 I GMPM    : App measurement is starting up
,08-12 18:36:14.086  2048  2048 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-12 18:36:14.086  2048  2048 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-12 18:36:14.086  6660  6660 E [CarMode]: [DLApplication]-onCreate: Applicatino Started!
,08-12 18:36:14.096  6660  6676 E GMPM    : getGoogleAppId failed with status: 10
,08-12 18:36:14.106  6660  6676 E GMPM    : Uploading is not possible. App measurement disabled
,08-12 18:36:14.106   751  2390 V AlarmManager:  remove PendingIntent] PendingIntent{b9091e0: PendingIntentRecord{cffc274 com.sec.android.automotive.drivelink broadcastIntent}}
,08-12 18:36:14.136  6660  6660 D SampleAppCoreManager: SampleAppCoreManager VACVersion '2.6.9.18467'
,08-12 18:36:14.146  6660  6660 I VlingoAndroidCore: AppName: SamsungCCKProject, Core: 2.6.9.18467, SDK: 2.0.2440, EDM:18467
,08-12 18:36:14.166  2048  2048 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-12 18:36:14.196  6683  6683 E Zygote  : v2
08-12 18:36:14.196  6683  6683 I libpersona: KNOX_SDCARD checking this for 10032
08-12 18:36:14.196  6683  6683 I libpersona: KNOX_SDCARD not a persona
,08-12 18:36:14.196  6683  6683 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:36:14.196  6683  6683 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 18:36:14.196  6683  6683 E Zygote  : accessInfo : 0
,08-12 18:36:14.196  6683  6683 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.vlingo.midas 
,08-12 18:36:14.196   751  1603 I ActivityManager: Start proc 6683:com.vlingo.midas/u0a32 for content provider com.vlingo.midas/.provider.VlingoConfigProvider
,08-12 18:36:14.196   751  1323 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-12 18:36:14.216  6683  6683 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 18:36:14.216  6683  6683 D ActivityThread: Added TimaKeyStore provider
,08-12 18:36:14.226   751  1323 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-12 18:36:14.236  6683  6683 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.vlingo.midas rsrc of package null
,08-12 18:36:14.246  6634  6649 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-12 18:36:14.256  6683  6683 W System  : ClassLoader referenced unknown path: /system/priv-app/S-Voice_Android_phone/lib/arm
,08-12 18:36:14.306  6490  6621 W jxcore-log: Initializing JXcore engine
08-12 18:36:14.306  6490  6621 W jxcore-log: JXcore engine is ready
,08-12 18:36:14.316  6634  6649 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-12 18:36:14.336  6660  6660 D [CarMode]: [DLAppUiUpdater]-test local  en_US
,08-12 18:36:14.336  6660  6660 D [CarMode]: [DLApplication]-GooglePlayServices SUCCESS.
,08-12 18:36:14.346  6660  6660 E [CarMode]: [DLApplication]-PREF_CAR_APP_RUNNING is set to false
08-12 18:36:14.346  6634  6649 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
08-12 18:36:14.346  6634  6649 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
08-12 18:36:14.346  6634  6649 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
08-12 18:36:14.346  2320  2320 E audit   : type=1400 msg=audit(1471019774.346:287): avc:  denied  { ioctl } for  pid=6621 comm="Thread-898" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-12 18:36:14.346  2320  2320 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 18:36:14.346  2320  2320 E audit   : type=1300 msg=audit(1471019774.346:287): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9ad973c8 items=0 ppid=353 ppcomm=main pid=6621 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-898" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-12 18:36:14.346  2320  2320 E audit   : type=1327 msg=audit(1471019774.346:287): proctitle="com.test.thalitest"
08-12 18:36:14.346  2320  2320 E audit   : type=1320 msg=audit(1471019774.346:287): 
08-12 18:36:14.356  2320  2320 E audit   : type=1400 msg=audit(1471019774.356:288): avc:  denied  { ioctl } for  pid=6621 comm="Thread-898" path="socket:[41439]" dev="sockfs" ino=41439 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-12 18:36:14.356  2320  2320 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 18:36:14.356  2320  2320 E audit   : type=1300 msg=audit(1471019774.356:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=39 a1=5451 a2=3 a3=9ad973c8 items=0 ppid=353 ppcomm=main pid=6621 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-898" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-12 18:36:14.356  2320  2320 E audit   : type=1327 msg=audit(1471019774.356:288): proctitle="com.test.thalitest"
08-12 18:36:14.356  2320  2320 E audit   : type=1320 msg=audit(1471019774.356:288): 
08-12 18:36:14.366  6490  6621 W jxcore-log: Starting JXcore engine
08-12 18:36:14.366  6660  6660 I UpdateManagerReceiver: Intent : android.intent.action.PACKAGE_ADDEDFri Aug 12 18:36:14 GMT+02:00 2016
08-12 18:36:14.366  6660  6660 D DialogFlow: initQueue()
,08-12 18:36:14.376  6697  6697 E Zygote  : v2
,08-12 18:36:14.376  6697  6697 I libpersona: KNOX_SDCARD checking this for 1000
08-12 18:36:14.376  6697  6697 I libpersona: KNOX_SDCARD not a persona
08-12 18:36:14.376  6697  6697 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:36:14.376  6697  6697 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 18:36:14.376  6697  6697 E Zygote  : accessInfo : 0
08-12 18:36:14.376   751  2336 I ActivityManager: Start proc 6697:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
08-12 18:36:14.386   751  2336 I ActivityManager: Killing 5723:com.sec.android.app.shealth/u0a34 (adj 15): DHA:empty #37
,08-12 18:36:14.386   751  2336 I ActivityManager: Killing 5619:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): DHA:empty #37
,08-12 18:36:14.406  6697  6697 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 18:36:14.406  6697  6697 D ActivityThread: Added TimaKeyStore provider
,08-12 18:36:14.416   751   766 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,08-12 18:36:14.416   751  1686 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,08-12 18:36:14.426   751  2413 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{832bcf8 6697:com.samsung.android.app.filterinstaller/1000}
,08-12 18:36:14.436  6634  6649 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-12 18:36:14.436  6697  6697 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package null
,08-12 18:36:14.446  6697  6697 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm
,08-12 18:36:14.456  6697  6697 E FilterPackageIntentReceiver: This package is not a effect filter
,08-12 18:36:14.456  6683  6683 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.41568', coreVersion = '2.6.12.18641', ro.csc.sales_code=XEO
,08-12 18:36:14.456  6490  6621 W jxcore-log: Platform android
08-12 18:36:14.456  6490  6621 W jxcore-log: 
08-12 18:36:14.456  6490  6621 W jxcore-log: Process ARCH arm
08-12 18:36:14.456  6490  6621 W jxcore-log: 
,08-12 18:36:14.466   751  1603 I ActivityManager: Start proc 6710:com.samsung.helphub/1000 for broadcast-3 com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver
,08-12 18:36:14.466   751  1603 I ActivityManager: Killing 4764:com.google.android.talk/u0a116 (adj 15): DHA:empty #37
,08-12 18:36:14.476  6710  6710 E Zygote  : v2
08-12 18:36:14.476  6710  6710 I libpersona: KNOX_SDCARD checking this for 1000
08-12 18:36:14.476  6710  6710 I libpersona: KNOX_SDCARD not a persona
,08-12 18:36:14.476  6710  6710 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:36:14.476  6710  6710 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 18:36:14.476  6710  6710 E Zygote  : accessInfo : 0
,08-12 18:36:14.486  6683  6683 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.12.18641, SDK: 2.0.2457, EDM:18641
,08-12 18:36:14.506  6710  6710 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 18:36:14.506  6710  6710 D ActivityThread: Added TimaKeyStore provider
,08-12 18:36:14.516   751  2336 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b52b0a4 6710:com.samsung.helphub/1000}
,08-12 18:36:14.526   751  2390 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,08-12 18:36:14.526  6710  6710 W ResourcesManager: getTopLevelResources: /system/app/InteractiveTutorial/InteractiveTutorial.apk / 1.0 running in com.samsung.helphub rsrc of package null
,08-12 18:36:14.536   751  1412 D PackageManager: setEnabledSetting : userId = 0 packageName = com.vlingo.midas cmp = com.vlingo.midas.settings.DrivingModeSettings newState = 2 callingPackage = 10032
,08-12 18:36:14.546  6710  6710 W System  : ClassLoader referenced unknown path: /system/app/InteractiveTutorial/lib/arm
,08-12 18:36:14.586  6725  6725 E Zygote  : v2
08-12 18:36:14.586  6725  6725 I libpersona: KNOX_SDCARD checking this for 1000
08-12 18:36:14.586  6725  6725 I libpersona: KNOX_SDCARD not a persona
,08-12 18:36:14.586  6725  6725 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:36:14.586  6725  6725 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 18:36:14.586   751  2336 I ActivityManager: Start proc 6725:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
08-12 18:36:14.586  6725  6725 E Zygote  : accessInfo : 0
,08-12 18:36:14.596   751  2336 I ActivityManager: Killing 5449:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): DHA:empty #37
,08-12 18:36:14.616  6683  6683 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,08-12 18:36:14.616  6683  6683 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,08-12 18:36:14.616   751  2415 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
,08-12 18:36:14.626  6683  6683 D DialogFlow: initQueue()
,08-12 18:36:14.636  6725  6725 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 18:36:14.636  6725  6725 D ActivityThread: Added TimaKeyStore provider
,08-12 18:36:14.646   751   766 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{484022f 6725:com.samsung.android.app.mirrorlink/1000}
,08-12 18:36:14.646  6725  6725 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package null
,08-12 18:36:14.666  6725  6725 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,08-12 18:36:14.706  6490  6621 I jxcore-log: JXcore Cordova bridge is ready!
08-12 18:36:14.706  6490  6621 I jxcore-log: 
,08-12 18:36:14.706  6490  6621 W jxcore-log: JXcore engine is started
,08-12 18:36:14.706  6490  6620 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-12 18:36:14.716  6490  6490 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 18:36:14.716  6725  6725 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
,08-12 18:36:14.716  6725  6725 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10004
,08-12 18:36:14.726   751  1686 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fa21edb 5631:com.google.android.apps.plus/u0a134}
,08-12 18:36:14.736   751  2413 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fa21edb 5631:com.google.android.apps.plus/u0a134}
,08-12 18:36:14.756   751  1412 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fa21edb 5631:com.google.android.apps.plus/u0a134}
,08-12 18:36:14.756   751  6302 I HarmonyEASService: Updating for all 1
,08-12 18:36:14.776   751  1365 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/168_task.xml.bak
,08-12 18:36:14.806   751  1416 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.GetContentActivityAlias newState = 2 callingPackage = 10134
,08-12 18:36:14.806   751  1686 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SendContentActivityAlias newState = 2 callingPackage = 10134
,08-12 18:36:14.806   751   767 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SetWallpaperActivityAlias newState = 2 callingPackage = 10134
,08-12 18:36:14.806   751  2413 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.VideoViewActivityAlias newState = 2 callingPackage = 10134
,08-12 18:36:14.806   751  1949 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias newState = 2 callingPackage = 10134
,08-12 18:36:14.816   751  1771 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestActivity newState = 2 callingPackage = 10134
,08-12 18:36:14.816   751  1494 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestService newState = 2 callingPackage = 10134
,08-12 18:36:14.816   751  2336 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.service.GooglePhotoDownsyncService newState = 2 callingPackage = 10134
,08-12 18:36:14.836  6739  6739 E Zygote  : v2
,08-12 18:36:14.836  6739  6739 I libpersona: KNOX_SDCARD checking this for 10165
08-12 18:36:14.836  6739  6739 I libpersona: KNOX_SDCARD not a persona
08-12 18:36:14.836  6739  6739 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:36:14.836  6739  6739 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 18:36:14.836   751  1686 I ActivityManager: Start proc 6739:com.sec.kidsplat.installer/u0a165 for broadcast-3 com.sec.kidsplat.installer/.KidsModeInstallReceiver
08-12 18:36:14.836  6739  6739 E Zygote  : accessInfo : 0
08-12 18:36:14.836  6739  6739 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.kidsplat.installer 
,08-12 18:36:14.846   751  1686 I ActivityManager: Killing 5817:com.samsung.android.app.FileShareClient/5005 (adj 15): DHA:empty #37
,08-12 18:36:14.866  6739  6739 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 18:36:14.866  6739  6739 D ActivityThread: Added TimaKeyStore provider
,08-12 18:36:14.876   751  2415 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ae7371a 6739:com.sec.kidsplat.installer/u0a165}
,08-12 18:36:14.876   751  1949 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareClient, Auto Run ON
,08-12 18:36:14.876  6739  6739 W ResourcesManager: getTopLevelResources: /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk / 1.0 running in com.sec.kidsplat.installer rsrc of package null
,08-12 18:36:14.886  6739  6739 W System  : ClassLoader referenced unknown path: /system/app/SecKidsModeInstaller/lib/arm
,08-12 18:36:14.896   751  1686 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ae7371a 6739:com.sec.kidsplat.installer/u0a165}
,08-12 18:36:14.896  6739  6739 D KidsPlatformStub: Package not found : com.sec.android.app.kidshome
,08-12 18:36:14.906  6751  6751 E Zygote  : v2
08-12 18:36:14.906  6751  6751 I libpersona: KNOX_SDCARD checking this for 10142
08-12 18:36:14.906  6751  6751 I libpersona: KNOX_SDCARD not a persona
,08-12 18:36:14.916   751  1494 I ActivityManager: Start proc 6751:com.sec.android.app.sbrowser/u0a142 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
,08-12 18:36:14.916   751  1494 I ActivityManager: Killing 5606:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #37
,08-12 18:36:14.916  6751  6751 E Zygote  : isSdpEnabledProcess - SDP enabled
08-12 18:36:14.916  6751  6751 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:36:14.916  6751  6751 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 18:36:14.916  6751  6751 E Zygote  : accessInfo : 64
08-12 18:36:14.916  6751  6751 E Zygote  : isSdpEnabledProcess - SDP enabled
08-12 18:36:14.916  6751  6751 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10142 / [uid]: 10142
,08-12 18:36:14.916  6751  6751 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
,08-12 18:36:14.926   751  2415 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
,08-12 18:36:14.936  6751  6751 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 18:36:14.936  6751  6751 D ActivityThread: Added TimaKeyStore provider
,08-12 18:36:14.946   751  2390 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f58924b 6751:com.sec.android.app.sbrowser/u0a142}
,08-12 18:36:14.946  6751  6751 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-12 18:36:14.966  6751  6751 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,08-12 18:36:15.016  6566  6566 I Mms/MmsApp:  start initViewCache mms
,08-12 18:36:15.036  6751  6751 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-12 18:36:15.036  6751  6751 D ManifestProvider: onCreate()
,08-12 18:36:15.066  6751  6751 I SBrowserUtils: getSystemProperty of sales_code : XEO
08-12 18:36:15.066  6751  6751 I SBrowserUtils: getSystemProperty of country_code : Poland
,08-12 18:36:15.066  6751  6751 I SBrowserUtils: getSystemProperty of country_code : Poland
08-12 18:36:15.066  6751  6751 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,08-12 18:36:15.076  6751  6751 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,08-12 18:36:15.076  6751  6751 D [MM]MHDataBaseProvider: onCreate()
,08-12 18:36:15.106  6751  6751 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@15cf2a9)
,08-12 18:36:15.126   751  1948 I ActivityManager: Killing 5339:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #37
,08-12 18:36:15.126   751  1948 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1ec8175 2048:com.google.android.gms.persistent/u0a11}
,08-12 18:36:15.136  4161  6767 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-12 18:36:15.136  4161  6766 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,08-12 18:36:15.146   751  1948 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{79883ff 4161:com.google.android.gms/u0a11}
,08-12 18:36:15.146  4161  6767 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-12 18:36:15.166  4161  4161 D AsyncTaskServiceImpl: Submit a task: nzm
,08-12 18:36:15.176  4161  6767 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-12 18:36:15.186  4161  6767 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-12 18:36:15.186   751  1412 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1ec8175 2048:com.google.android.gms.persistent/u0a11}
,08-12 18:36:15.186  4161  5039 D nzm     : Processing package: com.test.thalitest
,08-12 18:36:15.206   751  1948 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{79883ff 4161:com.google.android.gms/u0a11}
,08-12 18:36:15.216  4161  4161 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-12 18:36:15.216   751  1412 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,08-12 18:36:15.246  4161  5039 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
08-12 18:36:15.246  4161  5039 D nzm     : Found info for package com.test.thalitest in db.
,08-12 18:36:15.306   751  1772 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a9a8ea1 5672:com.android.vending/u0a29}
,08-12 18:36:15.316  6566  6566 D Mms/BubbleViewCache: fillCache bubble = 4
,08-12 18:36:15.366  5672  5672 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
,08-12 18:36:15.366   751  1412 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f76fd44 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4f4e3eb 6121:com.sec.android.app.samsungapps/u0a39}
,08-12 18:36:15.376  5672  5672 I Finsky  : [1] com.google.android.finsky.utils.bn.run(1302): Package state data is missing for com.test.thalitest
,08-12 18:36:15.376  2048  2048 D WearableService: callingUid 10011, callindPid: 2048
,08-12 18:36:15.386  5672  5672 E Finsky  : [1] com.google.android.finsky.wear.bo.a(837): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-12 18:36:15.386  5672  5672 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6394): Dropping command=send_installed_apps due to Gms not connected
,08-12 18:36:15.396  6773  6773 E Zygote  : v2
08-12 18:36:15.396  6773  6773 I libpersona: KNOX_SDCARD checking this for 10034
08-12 18:36:15.396  6773  6773 I libpersona: KNOX_SDCARD not a persona
08-12 18:36:15.396   751   751 I ActivityManager: Start proc 6773:com.sec.android.app.shealth/u0a34 for broadcast-3 com.sec.android.app.shealth/com.samsung.android.app.shealth.serviceframework.partner.PluginBroadcastReceiver
08-12 18:36:15.396  6773  6773 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:36:15.396  6773  6773 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 18:36:15.396  6773  6773 E Zygote  : accessInfo : 0
,08-12 18:36:15.396  6773  6773 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth 
,08-12 18:36:15.416   751   751 I BackgroundCompactionService: onStart. jobID=801
,08-12 18:36:15.416   751   751 I BackgroundCompactionService: onStart done. jobID=801
,08-12 18:36:15.426   751  6784 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
,08-12 18:36:15.436   751  6784 I BackgroundCompactionService: compact_memory command done
,08-12 18:36:15.456  6773  6773 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 18:36:15.456  6773  6773 D ActivityThread: Added TimaKeyStore provider
,08-12 18:36:15.466   751  1603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c75fb3 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b7e7970 6773:com.sec.android.app.shealth/u0a34}
,08-12 18:36:15.476  6773  6773 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,08-12 18:36:15.536  6773  6773 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,08-12 18:36:15.566  6773  6773 I MultiDex: VM with version 2.1.0 has multidex support
08-12 18:36:15.566  6773  6773 I MultiDex: install
08-12 18:36:15.566  6773  6773 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-12 18:36:15.566  6773  6773 I MultiDex: install
08-12 18:36:15.566  6773  6773 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-12 18:36:15.636   751  1416 I ActivityManager: Killing 5832:com.samsung.android.sm.policy/u0a203 (adj 15): DHA:empty #37
,08-12 18:36:15.636   751  1416 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c75fb3 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8bb3eaa 1879:com.sec.android.app.shealth:remote/u0a34}
,08-12 18:36:15.646  6773  6773 D HealthDataStore: Service for HealthDataStore is connected
,08-12 18:36:15.646  6773  6773 D HealthDataStore: HealthConnectionErrorResult code : 9
,08-12 18:36:15.646  6773  6773 D HealthConsole: Service for HealthDataConsole is connected
,08-12 18:36:15.656  6773  6773 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,08-12 18:36:15.656  6773  6773 E HealthDataStore: disconnectService: Context instance is invalid
,08-12 18:36:15.666  6683  6724 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-12 18:36:15.666  6683  6724 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-12 18:36:15.666   751  2336 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.policy, Auto Run ON
,08-12 18:36:15.676   751  1494 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c75fb3 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8bb3eaa 1879:com.sec.android.app.shealth:remote/u0a34}
,08-12 18:36:15.696   751  2415 V AlarmManager:  remove PendingIntent] PendingIntent{609446: PendingIntentRecord{8cb642f com.google.android.gms broadcastIntent}}
,08-12 18:36:15.696   751  1323 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
08-12 18:36:15.696   751  1323 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-12 18:36:15.716   751  2413 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a70a607 u0 com.google.android.gms.actions.HANDLE_PACKAGE_INSTALLED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1ec8175 2048:com.google.android.gms.persistent/u0a11}
,08-12 18:36:15.716  6683  6724 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-12 18:36:15.716  6683  6724 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-12 18:36:15.716  6683  6724 I System.out: INFO:Resource not found:/Common.properties Using default values
,08-12 18:36:15.736  6683  6724 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,08-12 18:36:15.736  6683  6724 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-12 18:36:15.896  4161  6771 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-12 18:36:16.356  4161  5026 I Icing   : Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,08-12 18:36:16.416  4161  5026 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-12 18:36:16.426  4161  5026 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-12 18:36:16.426  4161  5026 I Icing   : Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,08-12 18:36:17.356   751  1494 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 18:36:17.356   751  1494 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4338, temperature: 315, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-12 18:36:17.356   751  1494 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
08-12 18:36:17.356   751  1494 D BatteryService: stay LED for charging
,08-12 18:36:17.356   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 18:36:17.356   751   751 I MotionRecognitionService: Plugged
,08-12 18:36:17.356  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-12 18:36:17.356  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 18:36:17.356  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
08-12 18:36:17.356   751   751 D MotionRecognitionService:   cableConnection= 1
08-12 18:36:17.356   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-12 18:36:17.356   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-12 18:36:17.366  2304  2304 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 18:36:17.366  2304  2748 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 18:36:17.376  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 18:36:17.376  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-12 18:36:17.376  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 18:36:18.186   751  3443 D M       : limitCPUFreq:: freq = 1728000
,08-12 18:36:18.186   751  3443 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 751  pkgName : SIOP_ARM_MAX@25
,08-12 18:36:18.186   751  3443 D M       : limitGPUFreq:: freq = 389000000
,08-12 18:36:18.196   751  3443 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-12 18:36:21.786   751   912 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-12 18:36:21.816   751   912 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-12 18:36:21.816   751   912 D PackageManager: [MSG] MCS_UNBIND
,08-12 18:36:21.826   751  2413 I ActivityManager: Killing 5357:com.policydm/1000 (adj 15): DHA:empty #37
,08-12 18:36:21.856  6505  6505 D AASAservice: onDestroy()
,08-12 18:36:21.866   751  1412 D ActivityManager: isAutoRunBlockedApp:: com.policydm, Auto Run ON
,08-12 18:36:21.866  6505  6505 I art     : System.exit called, status: 80
,08-12 18:36:21.866  6505  6505 I AndroidRuntime: VM exiting with result code 80, cleanup skipped.
,08-12 18:36:21.886   751   766 I ActivityManager: Process com.samsung.aasaservice (pid 6505)(adj 0) has died(76,712)
,08-12 18:36:21.886   751   766 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
,08-12 18:36:21.936   353   353 I Zygote  : Process 6505 exited cleanly (80)
,08-12 18:36:22.216   751  3443 D SSRM:n  : SIOP:: AP = 460, PST = 450, CUR = 450, LCD = 0
,08-12 18:36:22.226   751  3443 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-12 18:36:23.256   751  1591 E Watchdog: !@Sync 3 [08-12 18:36:23.268]
,08-12 18:36:25.746   751  1323 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-12 18:36:25.746   751  1323 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-12 18:36:30.326   751  1236 V AlarmManager: Expired Alarm result :4
,08-12 18:36:30.346   751   837 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{679ba3 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1ec8175 2048:com.google.android.gms.persistent/u0a11}
,08-12 18:36:30.366   751  1494 V AlarmManager:  remove PendingIntent] PendingIntent{520fa59: PendingIntentRecord{d30ba3d com.google.android.gms broadcastIntent}}
,08-12 18:36:30.366  5672  5715 I Finsky  : [813] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,08-12 18:36:30.376   751  2390 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 18:36:30.386   751  2390 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4376, temperature: 316, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-12 18:36:30.386   751  2390 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
08-12 18:36:30.386   751  2390 D BatteryService: stay LED for charging
08-12 18:36:30.386   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 18:36:30.386   751   751 I MotionRecognitionService: Plugged
08-12 18:36:30.386   751   751 D MotionRecognitionService:   cableConnection= 1
08-12 18:36:30.386   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-12 18:36:30.386   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-12 18:36:30.386  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 18:36:30.386  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 18:36:30.386  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 18:36:30.386  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 18:36:30.406  2304  2304 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-12 18:36:30.406  2304  2748 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 18:36:30.406  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 18:36:30.406  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 18:36:30.516   751  1771 V AlarmManager:  remove PendingIntent] PendingIntent{34e4eff: PendingIntentRecord{d30ba3d com.google.android.gms broadcastIntent}}
,08-12 18:36:30.676  2048  2048 D WearableService: callingUid 10011, callindPid: 2048
,08-12 18:36:30.686  2048  2048 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-12 18:36:30.706   751   837 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2836fd0 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1ec8175 2048:com.google.android.gms.persistent/u0a11}
,08-12 18:36:30.736   751   766 V AlarmManager:  remove PendingIntent] PendingIntent{8e82bc9: PendingIntentRecord{d30ba3d com.google.android.gms broadcastIntent}}
,08-12 18:36:30.786  2048  6826 I CheckinUtil: Classify the device as Phone.
,08-12 18:36:30.786  2048  6826 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-12 18:36:30.836  2048  6826 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 18:36:30.836  2048  6826 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 18:36:30.836   314  1198 D EnterpriseController: netId is 0
08-12 18:36:30.836   314  1198 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-12 18:36:30.846   314  1194 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-12 18:36:30.846   314  1194 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-12 18:36:30.846   314  1194 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-12 18:36:30.876  5672  5715 I Finsky  : [813] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,08-12 18:36:30.876  5672  5672 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,08-12 18:36:30.886  2048  6826 I qtaguid : Tagging socket 45 with tag 1000040b00000000{268436491,0} uid -1, pid: 2048, getuid(): 10011
,08-12 18:36:30.916  2048  6826 I qtaguid : Tagging socket 49 with tag 1000040b00000000{268436491,0} uid -1, pid: 2048, getuid(): 10011
,08-12 18:36:31.086  2048  6826 I qtaguid : Untagging socket 45
,08-12 18:36:31.106  4161  6822 D ChimeraConfigService: Fetched value, gms:chimera:dogfoods = null
08-12 18:36:31.106  4161  6822 D ChimeraConfigService: Fetched value, gms:chimera:beta:module_sets = null
08-12 18:36:31.106  4161  6822 D ChimeraConfigService: Fetched value, gms:chimera:googlewide:module_sets = null
,08-12 18:36:31.116  4161  6822 D ChimeraConfigService: Fetched value, gms:chimera:prod:module_sets = null
,08-12 18:36:31.116  4161  6822 D ChimeraConfigService: Fetched value, gms:chimera:module_set = null
08-12 18:36:31.116  4161  6822 E ChimeraConfigService: gms:chimera:module_set is malformed, ignoring module set
,08-12 18:36:31.216   751  2336 V AlarmManager:  remove PendingIntent] PendingIntent{3ebb85: PendingIntentRecord{d30ba3d com.google.android.gms broadcastIntent}}
,08-12 18:36:31.266   751  2390 V AlarmManager:  remove PendingIntent] PendingIntent{5b68dda: PendingIntentRecord{d30ba3d com.google.android.gms broadcastIntent}}
,08-12 18:36:31.286   751   760 I art     : Background partial concurrent mark sweep GC freed 37117(2MB) AllocSpace objects, 12(240KB) LOS objects, 27% free, 42MB/58MB, paused 2.015ms total 161.564ms
,08-12 18:36:31.326  4161  6840 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-12 18:36:31.326  4161  6840 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-12 18:36:31.396   751  1771 V AlarmManager:  remove PendingIntent] PendingIntent{4b48b01: PendingIntentRecord{d30ba3d com.google.android.gms broadcastIntent}}
,08-12 18:36:31.506   751  1416 I ActivityManager: Start proc 6843:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,08-12 18:36:31.506  6843  6843 E Zygote  : v2
08-12 18:36:31.506  6843  6843 I libpersona: KNOX_SDCARD checking this for 10011
08-12 18:36:31.506  6843  6843 I libpersona: KNOX_SDCARD not a persona
,08-12 18:36:31.506  6843  6843 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:36:31.506  6843  6843 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 18:36:31.506  6843  6843 E Zygote  : accessInfo : 0
,08-12 18:36:31.506  6843  6843 W SELinux : SELinux: seapp_context_lookup: seinfo=gmscore, level=s0:c512,c768, pkgname=com.google.android.gms.unstable 
,08-12 18:36:31.526  6843  6843 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 18:36:31.526  6843  6843 D ActivityThread: Added TimaKeyStore provider
,08-12 18:36:31.546  6843  6843 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-12 18:36:31.576  6843  6843 I MultiDex: VM with version 2.1.0 has multidex support
,08-12 18:36:31.576  6843  6843 I MultiDex: install
08-12 18:36:31.576  6843  6843 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-12 18:36:31.606  6843  6843 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-12 18:36:31.626  6843  6843 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
08-12 18:36:31.626  6843  6843 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-12 18:36:31.626  6843  6843 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-12 18:36:31.666  6843  6843 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-12 18:36:31.676  6843  6843 D ChimeraCfgMgr: Reading stored module config
,08-12 18:36:31.776   331   955 I Drm     : android::Drm::Drm() is called from com.google.android.gms.unstable(pid:6843)
,08-12 18:36:31.796  6843  6857 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-12 18:36:31.836   331   957 D WVCdm   : Instantiating CDM.
,08-12 18:36:31.836   331   944 I Drm     : virtual status_t android::Drm::openSession(Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6843)
,08-12 18:36:31.836   331   944 I WVCdm   : CdmEngine::OpenSession
08-12 18:36:31.836   331   944 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,08-12 18:36:31.846   331   944 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-12 18:36:31.846   331   944 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
,08-12 18:36:31.846   331   944 D DrmWidevineDash: Service_Initialize: starts!
08-12 18:36:31.846   331   944 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,08-12 18:36:31.856   331   944 D QSEECOMAPI: : App is not loaded in QSEE
08-12 18:36:31.856   331   944 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
08-12 18:36:31.856   331   944 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-12 18:36:31.856   331   944 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-12 18:36:31.856   331   944 D QSEECOMAPI: : App is not loaded in QSEE
08-12 18:36:31.856   331   944 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
08-12 18:36:31.856   331   944 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-12 18:36:31.856   331   944 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-12 18:36:31.856   331   944 D QSEECOMAPI: : App is not loaded in QSEE
,08-12 18:36:31.876  6843  6854 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 18:36:31.876  6843  6854 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 18:36:31.876   314  1198 D EnterpriseController: netId is 0
08-12 18:36:31.876   314  1198 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-12 18:36:31.896   331   944 D QSEECOMAPI: : Loaded image: APP id = 3
,08-12 18:36:31.896   331   944 D DrmWidevineDash: Service_Initialize: ends! returns 0
,08-12 18:36:31.896   331   944 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaee94000
08-12 18:36:31.896   331   944 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaee94000
,08-12 18:36:31.906   331   944 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,08-12 18:36:31.906   331   944 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,08-12 18:36:31.906   331   944 D DrmWidevineDash: hlos api version =  10
08-12 18:36:31.906   331   944 D DrmWidevineDash: tz api version =  10
,08-12 18:36:31.906   331   944 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
08-12 18:36:31.916   331   944 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,08-12 18:36:31.916   331   944 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
08-12 18:36:31.916   331   944 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-12 18:36:31.916   331   944 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xaf1c0924
,08-12 18:36:31.916   331   944 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-12 18:36:31.926   331   944 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-12 18:36:31.926   331   944 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xae20e3b8, dataLength=8
,08-12 18:36:31.926   331   944 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-12 18:36:31.926   331   944 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xae83d400, wrapped_rsa_key_length=1280
,08-12 18:36:31.926   331   944 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,08-12 18:36:31.926   331   944 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-12 18:36:31.926   331   331 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-12 18:36:31.926   331   331 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
08-12 18:36:31.926   331   331 I WVCdm   : CdmEngine::GenerateKeyRequest
08-12 18:36:31.926   331   331 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xaf4d3440, idLength=0xbeeabcbc
,08-12 18:36:31.936   331   331 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
08-12 18:36:31.936   331   331 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,08-12 18:36:31.936   331   331 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
08-12 18:36:31.936   331   331 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
08-12 18:36:31.936   331   331 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
08-12 18:36:31.936   331   331 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,08-12 18:36:31.936   331   331 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 0
08-12 18:36:31.936   331   331 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,08-12 18:36:31.936   331   331 D DrmWidevineDash: hlos api version =  10
08-12 18:36:31.936   331   331 D DrmWidevineDash: tz api version =  10
08-12 18:36:31.936   331   331 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
08-12 18:36:31.936   331   331 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,08-12 18:36:31.936   331   331 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
08-12 18:36:31.936   331   331 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
08-12 18:36:31.936   331   331 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,08-12 18:36:31.946   331   331 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
,08-12 18:36:31.946   331   331 D WVCdm   : PrepareKeyRequest: nonce=2406990410
08-12 18:36:31.946   331   331 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1d83c00
,08-12 18:36:31.946   331   331 D DrmWidevineDash: message_length=1631, signature=0xad3cadc0, signature_length=3203054996
,08-12 18:36:32.036   331   331 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-12 18:36:32.036   331   957 I Drm     : virtual status_t android::Drm::closeSession(const Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6843)
,08-12 18:36:32.036   331   957 I WVCdm   : CdmEngine::CloseSession
08-12 18:36:32.036   331   957 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,08-12 18:36:32.036   331   957 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
,08-12 18:36:32.036   331   957 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,08-12 18:36:32.036   331   957 D DrmWidevineDash: Service_Uninitialize: starts!
08-12 18:36:32.036   331   957 D QSEECOMAPI: : QSEECom_dealloc_memory 
,08-12 18:36:32.036   331   957 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
,08-12 18:36:32.036   331   957 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,08-12 18:36:32.036   331   957 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,08-12 18:36:32.266   751  3443 D SSRM:n  : SIOP:: AP = 430, PST = 446, CUR = 450, LCD = 0
08-12 18:36:32.266   751  3443 D M       : limitCPUFreq:: freq = -1
08-12 18:36:32.266   751  3443 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 751  tag : SIOP_ARM_MAX@25
,08-12 18:36:32.266   751  3443 D M       : limitGPUFreq:: freq = -1
,08-12 18:36:32.266   751  3443 D M       : broadcastSiopLevelIntent:: currentSiopLevel = 1
,08-12 18:36:32.276  2794  2794 D ContentApp:  LEVEL : 1
,08-12 18:36:32.286  6876  6876 E Zygote  : v2
08-12 18:36:32.286   751   837 I ActivityManager: Start proc 6876:com.sec.android.app.videoplayer/u0a53 for broadcast-3 com.sec.android.app.videoplayer/.videowall.TranscodeReceiver
,08-12 18:36:32.286  6876  6876 I libpersona: KNOX_SDCARD checking this for 10053
08-12 18:36:32.286  6876  6876 I libpersona: KNOX_SDCARD not a persona
08-12 18:36:32.286   751  1323 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-12 18:36:32.286  6876  6876 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:36:32.286  6876  6876 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 18:36:32.286  6876  6876 E Zygote  : accessInfo : 0
,08-12 18:36:32.286  6876  6876 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.videoplayer 
,08-12 18:36:32.286   751  3443 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-12 18:36:32.346  6876  6876 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 18:36:32.346  6876  6876 D ActivityThread: Added TimaKeyStore provider
,08-12 18:36:32.356   751   766 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{86883fb u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bd8dc18 6876:com.sec.android.app.videoplayer/u0a53}
,08-12 18:36:32.366   751  1323 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-12 18:36:32.366  6876  6876 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,08-12 18:36:32.396  6876  6876 W System  : ClassLoader referenced unknown path: /system/priv-app/SecVideoPlayer/lib/arm
,08-12 18:36:32.416  6876  6876 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,08-12 18:36:32.436  6876  6876 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,08-12 18:36:32.446  6876  6876 D videowall-Global: core_num = 4
,08-12 18:36:32.456  6876  6876 D videowall-Global: density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
08-12 18:36:32.456  6876  6876 D videowall-Global: dsp : 1080, swkey : false, Cores : 4, Clock : 0
,08-12 18:36:32.466  6876  6876 D TranscodeReceiver:  SIOP_LEVEL: 1
,08-12 18:36:32.466   751  1948 I ActivityManager: Killing 5909:com.osp.app.signin/u0a44 (adj 15): DHA:empty #37
,08-12 18:36:32.476   751  2336 D ActivityManager: isAutoRunBlockedApp:: com.osp.app.signin, Auto Run ON
,08-12 18:36:32.626  6843  6854 I qtaguid : Tagging socket 21 with tag 1000180300000000{268441603,0} uid -1, pid: 6843, getuid(): 10011
,08-12 18:36:32.786  6843  6854 I qtaguid : Tagging socket 27 with tag 1000180300000000{268441603,0} uid -1, pid: 6843, getuid(): 10011
,08-12 18:36:32.906  6843  6854 I qtaguid : Untagging socket 21
,08-12 18:36:32.936  6843  6854 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-12 18:36:32.936  6843  6854 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-12 18:36:33.196   751  3475 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 18:36:33.376  6901  6901 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,08-12 18:36:33.466  6901  6901 I dex2oat : ----------------------------------------------------
08-12 18:36:33.466  6901  6901 I dex2oat : <SS>: S T A R T I N G . . .
08-12 18:36:33.466  6901  6901 E dex2oat : <SS>: oat location is not valid /data/user/0/com.google.android.gms/app_fb/f.dex
08-12 18:36:33.466  6901  6901 I dex2oat : dex2oat took 97.085ms (threads: 4) arena alloc=312KB java alloc=39KB native alloc=1550KB free=1521KB
,08-12 18:36:33.476  6843  6854 W System  : ClassLoader referenced unknown path: 
,08-12 18:36:33.476  6843  6854 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.gms/app_fb
,08-12 18:36:33.486  6843  6854 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-12 18:36:33.486  6843  6854 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-12 18:36:33.486  6843  6854 I Adreno-EGL: Build Date: 01/28/16 Thu
08-12 18:36:33.486  6843  6854 I Adreno-EGL: Local Branch: ss
08-12 18:36:33.486  6843  6854 I Adreno-EGL: Remote Branch: 
08-12 18:36:33.486  6843  6854 I Adreno-EGL: Local Patches: 
08-12 18:36:33.486  6843  6854 I Adreno-EGL: Reconstruct Branch: 
,08-12 18:36:33.486  6843  6854 D libEGL  : eglInitialize EGLDisplay = 0xb2ece264
,08-12 18:36:33.536  6843  6854 D libEGL  : eglTerminate EGLDisplay = 0xb2ece2bc
,08-12 18:36:33.606  6843  6854 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-12 18:36:33.606  6843  6854 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-12 18:36:33.606  6843  6854 I Adreno-EGL: Build Date: 01/28/16 Thu
08-12 18:36:33.606  6843  6854 I Adreno-EGL: Local Branch: ss
08-12 18:36:33.606  6843  6854 I Adreno-EGL: Remote Branch: 
08-12 18:36:33.606  6843  6854 I Adreno-EGL: Local Patches: 
08-12 18:36:33.606  6843  6854 I Adreno-EGL: Reconstruct Branch: 
,08-12 18:36:33.606  6843  6854 D libEGL  : eglInitialize EGLDisplay = 0xb2ece264
,08-12 18:36:33.686  6843  6854 D libEGL  : eglTerminate EGLDisplay = 0xb2ece2bc
,08-12 18:36:33.686  6843  6854 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-12 18:36:33.686  6843  6854 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-12 18:36:33.686  6843  6854 I Adreno-EGL: Build Date: 01/28/16 Thu
08-12 18:36:33.686  6843  6854 I Adreno-EGL: Local Branch: ss
08-12 18:36:33.686  6843  6854 I Adreno-EGL: Remote Branch: 
08-12 18:36:33.686  6843  6854 I Adreno-EGL: Local Patches: 
08-12 18:36:33.686  6843  6854 I Adreno-EGL: Reconstruct Branch: 
,08-12 18:36:33.686  6843  6854 D libEGL  : eglInitialize EGLDisplay = 0xb2ece264
,08-12 18:36:33.726  6843  6854 D libEGL  : eglTerminate EGLDisplay = 0xb2ece2bc
,08-12 18:36:33.746  2048  6842 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 18:36:33.746  2048  6842 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 18:36:33.746   314  1198 D EnterpriseController: netId is 0
08-12 18:36:33.746   314  1198 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-12 18:36:33.746  2048  6842 I qtaguid : Tagging socket 51 with tag 1000040100000000{268436481,0} uid 10011, pid: 2048, getuid(): 10011
,08-12 18:36:33.786  2048  6842 I qtaguid : Tagging socket 54 with tag 1000040100000000{268436481,0} uid 10011, pid: 2048, getuid(): 10011
,08-12 18:36:33.916   751   766 V AlarmManager:  remove PendingIntent] PendingIntent{f53671: PendingIntentRecord{d30ba3d com.google.android.gms broadcastIntent}}
,08-12 18:36:34.016   751  1416 V AlarmManager:  remove PendingIntent] PendingIntent{77957e2: PendingIntentRecord{d30ba3d com.google.android.gms broadcastIntent}}
,08-12 18:36:34.106  2048  2069 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@5996b84)
,08-12 18:36:34.266  6490  6621 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 18:36:34.266  6490  6621 I jxcore-log: 
,08-12 18:36:34.266  6490  6621 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 18:36:34.266  6490  6621 I jxcore-log: 
,08-12 18:36:34.276  6490  6621 D BluetoothAdapter: STATE_ON
,08-12 18:36:34.276  6490  6621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 18:36:34.276  6490  6621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 18:36:34.276  6490  6621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 18:36:34.276  6490  6621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 18:36:34.276  6490  6621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 18:36:34.276  6490  6621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 18:36:34.276  6490  6621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 18:36:34.276  6490  6621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 18:36:34.276  6490  6621 D BluetoothAdapter: STATE_ON
,08-12 18:36:34.276  6490  6621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 18:36:34.286  6490  6621 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 18:36:34.286  6490  6621 I jxcore-log: 
,08-12 18:36:34.286  6490  6621 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 18:36:34.286  6490  6621 I jxcore-log: 
,08-12 18:36:34.366  2048  2048 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=5880f20d-2558-43a3-abf5-86c451dcadaa
,08-12 18:36:34.376  2048  2048 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-12 18:36:34.376  2048  2048 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-12 18:36:34.496  2048  2213 W GCoreFlp: No location to return for getLastLocation()
,08-12 18:36:34.556  4161  6913 D UdcContextInitService: registered all accounts: true
,08-12 18:36:34.556  2048  2467 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-12 18:36:34.566  2048  2638 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-12 18:36:34.646   751  1416 V AlarmManager:  remove PendingIntent] PendingIntent{25df545: PendingIntentRecord{d30ba3d com.google.android.gms broadcastIntent}}
,08-12 18:36:34.686  6490  6621 I jxcore-log: Unit Test app is loaded
08-12 18:36:34.686  6490  6621 I jxcore-log: 
,08-12 18:36:34.686  6490  6621 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 18:36:34.686  6490  6621 I jxcore-log: 
,08-12 18:36:34.686  6490  6621 I jxcore-log: My device name is: samsung-SM-G900F
08-12 18:36:34.686  6490  6621 I jxcore-log: 
,08-12 18:36:34.686  6490  6490 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-12 18:36:34.686  6490  6621 I jxcore-log: WARN testUtils: myNameCallback not set!
08-12 18:36:34.686  6490  6621 I jxcore-log: 
,08-12 18:36:34.756  2048  2638 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-12 18:36:34.756  2048  2638 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-12 18:36:34.766  2048  6929 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 18:36:34.766  2048  6929 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 18:36:34.766   314  1198 D EnterpriseController: netId is 0
08-12 18:36:34.766   314  1198 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-12 18:36:34.776  2048  6929 I qtaguid : Tagging socket 62 with tag 1000310500000000{268448005,0} uid 10011, pid: 2048, getuid(): 10011
,08-12 18:36:34.826  2048  6929 I qtaguid : Tagging socket 64 with tag 1000310500000000{268448005,0} uid 10011, pid: 2048, getuid(): 10011
,08-12 18:36:34.866  2048  6935 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-12 18:36:34.876  2048  6926 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-12 18:36:34.886  2048  6935 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-12 18:36:34.886  2048  6926 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-12 18:36:34.896  2048  6935 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-12 18:36:34.896  2048  6926 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-12 18:36:34.896  2048  6926 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-12 18:36:34.906  2048  6926 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-12 18:36:34.976   751  1603 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 18:36:35.026  2048  6926 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 18:36:35.026  2048  6926 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 18:36:35.026   314  1198 D EnterpriseController: netId is 0
08-12 18:36:35.026   314  1198 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-12 18:36:35.026  2048  6926 I qtaguid : Tagging socket 68 with tag 11065c0800000000{285629448,0} uid -1, pid: 2048, getuid(): 10011
,08-12 18:36:35.056  2048  6926 I qtaguid : Tagging socket 71 with tag 11065c0800000000{285629448,0} uid -1, pid: 2048, getuid(): 10011
,08-12 18:36:35.116  2048  6929 I qtaguid : Untagging socket 62
,08-12 18:36:35.126  2048  2638 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-12 18:36:35.266   751  1603 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 18:36:35.296  2048  6926 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 18:36:35.296  2048  6926 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 18:36:35.296  2048  6926 I qtaguid : Tagging socket 68 with tag fffff1ef00000000{4294963695,0} uid -1, pid: 2048, getuid(): 10011
,08-12 18:36:35.426   751  1949 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 18:36:35.426  2048  6926 W Uploader: UNKNOWN no longer exists, so no auth token.
,08-12 18:36:35.436  2048  6926 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 18:36:35.436  2048  6926 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 18:36:35.436  2048  6926 I qtaguid : Tagging socket 68 with tag fffff65b00000000{4294964827,0} uid -1, pid: 2048, getuid(): 10011
,08-12 18:36:35.536   751  2415 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 18:36:35.546  2048  6926 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 18:36:35.546  2048  6926 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 18:36:35.546  2048  6926 I qtaguid : Tagging socket 68 with tag fffffb1f00000000{4294966047,0} uid -1, pid: 2048, getuid(): 10011
,08-12 18:36:35.646   751  1603 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 18:36:35.646  2048  6926 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 18:36:35.646  2048  6926 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 18:36:35.646  2048  6926 I qtaguid : Tagging socket 68 with tag 11065fff00000000{285630463,0} uid -1, pid: 2048, getuid(): 10011
,08-12 18:36:35.756   751  1412 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 18:36:35.756  2048  6926 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 18:36:35.756  2048  6926 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 18:36:35.756  2048  6926 I qtaguid : Tagging socket 68 with tag 11065c9100000000{285629585,0} uid -1, pid: 2048, getuid(): 10011
,08-12 18:36:35.936   751  1948 V AlarmManager:  remove PendingIntent] PendingIntent{fe12cf2: PendingIntentRecord{d30ba3d com.google.android.gms broadcastIntent}}
,08-12 18:36:36.876  2048  6928 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 18:36:36.876  2048  6928 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 18:36:36.876  2048  6928 I qtaguid : Tagging socket 62 with tag 1000310200000000{268448002,0} uid 10011, pid: 2048, getuid(): 10011
,08-12 18:36:37.076  6490  6621 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-12 18:36:37.076  6490  6621 I jxcore-log: 
,08-12 18:36:37.146  2048  6928 I qtaguid : Untagging socket 62
,08-12 18:36:37.156  2048  2638 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-12 18:36:37.686  6490  6621 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-12 18:36:37.686  6490  6621 I jxcore-log: 
,08-12 18:36:37.716  6490  6621 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-12 18:36:37.716  6490  6621 I jxcore-log: 
,08-12 18:36:38.736   751  1949 I ActivityManager: Killing 5940:com.google.android.apps.photos/u0a199 (adj 15): DHA:empty #37
,08-12 18:36:38.766   751  1771 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.photos, Auto Run ON
,08-12 18:36:39.096  6490  6621 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-12 18:36:39.096  6490  6621 I jxcore-log: 
,08-12 18:36:39.316  6490  6621 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-12 18:36:39.316  6490  6621 I jxcore-log: 
,08-12 18:36:39.326  6490  6621 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-12 18:36:39.326  6490  6621 I jxcore-log: 
,08-12 18:36:39.326  6490  6621 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-12 18:36:39.326  6490  6621 I jxcore-log: 
,08-12 18:36:39.346  6490  6621 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-12 18:36:39.346  6490  6621 I jxcore-log: 
,08-12 18:36:39.356  6490  6621 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-12 18:36:39.356  6490  6621 I jxcore-log: 
,08-12 18:36:40.026  6490  6621 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-12 18:36:40.026  6490  6621 I jxcore-log: 
,08-12 18:36:40.036  6490  6621 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-12 18:36:40.036  6490  6621 I jxcore-log: 
,08-12 18:36:40.046  6490  6621 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-12 18:36:40.046  6490  6621 I jxcore-log: 
,08-12 18:36:40.056  6490  6621 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-12 18:36:40.056  6490  6621 I jxcore-log: 
,08-12 18:36:40.106  6490  6621 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-12 18:36:40.106  6490  6621 I jxcore-log: 
,08-12 18:36:40.166  6490  6621 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-12 18:36:40.166  6490  6621 I jxcore-log: 
,08-12 18:36:40.166  6490  6621 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-12 18:36:40.166  6490  6621 I jxcore-log: 
,08-12 18:36:40.336  6490  6621 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-12 18:36:40.336  6490  6621 I jxcore-log: 
,08-12 18:36:40.366  6490  6621 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-12 18:36:40.366  6490  6621 I jxcore-log: 
,08-12 18:36:40.366  6490  6621 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-12 18:36:40.366  6490  6621 I jxcore-log: 
,08-12 18:36:40.366  6490  6621 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-12 18:36:40.366  6490  6621 I jxcore-log: 
,08-12 18:36:40.386  6490  6621 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-12 18:36:40.386  6490  6621 I jxcore-log: 
,08-12 18:36:40.456   751  2415 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 18:36:40.456   751  2415 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4360, temperature: 317, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 18:36:40.456   751  2415 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
08-12 18:36:40.456   751  2415 D BatteryService: stay LED for charging
08-12 18:36:40.456   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 18:36:40.456   751   751 I MotionRecognitionService: Plugged
,08-12 18:36:40.456   751   751 D MotionRecognitionService:   cableConnection= 1
08-12 18:36:40.456   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 18:36:40.456   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-12 18:36:40.456  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-12 18:36:40.456  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 18:36:40.456  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 18:36:40.466  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 18:36:40.466  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 18:36:40.466  2304  2304 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 18:36:40.466  2304  2748 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 18:36:40.476  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 18:36:40.506  6490  6621 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-12 18:36:40.506  6490  6621 I jxcore-log: 
,08-12 18:36:40.516  6490  6621 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-12 18:36:40.516  6490  6621 I jxcore-log: 
,08-12 18:36:40.546  6490  6621 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-12 18:36:40.546  6490  6621 I jxcore-log: 
,08-12 18:36:40.556  6490  6621 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-12 18:36:40.556  6490  6621 I jxcore-log: 
,08-12 18:36:40.576  6490  6621 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-12 18:36:40.576  6490  6621 I jxcore-log: 
,08-12 18:36:40.606  6490  6621 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-12 18:36:40.606  6490  6621 I jxcore-log: 
,08-12 18:36:40.616  6490  6621 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-12 18:36:40.616  6490  6621 I jxcore-log: 
,08-12 18:36:40.796  6490  6621 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-12 18:36:40.796  6490  6621 I jxcore-log: 
,08-12 18:36:40.806  6490  6621 D BluetoothAdapter: STATE_ON
,08-12 18:36:40.806  6490  6621 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-12 18:36:40.806  6490  6621 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-12 18:36:40.806  6490  6621 I jxcore-log: 
,08-12 18:36:42.346   751  3443 D SSRM:n  : SIOP:: AP = 430, PST = 440, CUR = 450, LCD = 0
,08-12 18:36:50.536   751  1416 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 18:36:50.536   751  1416 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4387, temperature: 318, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 18:36:50.536   751  1416 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-12 18:36:50.546   751  1416 D BatteryService: stay LED for charging
,08-12 18:36:50.546   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 18:36:50.556   751   751 I MotionRecognitionService: Plugged
,08-12 18:36:50.566   751   751 D MotionRecognitionService:   cableConnection= 1
,08-12 18:36:50.566   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 18:36:50.566   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-12 18:36:50.586  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 18:36:50.596  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 18:36:50.596  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 18:36:50.606  2304  2304 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 18:36:50.606  2304  2748 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 18:36:50.616  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 18:36:50.616  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 18:36:50.616  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 18:36:52.416   751  3443 D SSRM:n  : SIOP:: AP = 400, PST = 432, CUR = 450, LCD = 0
,08-12 18:36:53.196   751  3475 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 18:36:53.266   751  1591 E Watchdog: !@Sync 4 [08-12 18:36:53.274]
,08-12 18:36:54.296  1687  1760 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-12 18:36:59.986   751  1236 V AlarmManager: Expired Alarm result :8
,08-12 18:37:02.476   751  3443 D SSRM:n  : SIOP:: AP = 380, PST = 427, CUR = 450, LCD = 0
,08-12 18:37:02.486   751  3443 D M       : broadcastSiopLevelIntent:: currentSiopLevel = 0
,08-12 18:37:02.506  2794  2794 D ContentApp:  LEVEL : 0
,08-12 18:37:02.546   751   837 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{16519c0 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bd8dc18 6876:com.sec.android.app.videoplayer/u0a53}
,08-12 18:37:02.556   751  3443 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-12 18:37:02.576  6876  6876 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,08-12 18:37:02.576  6876  6876 D TranscodeReceiver:  SIOP_LEVEL: 0
,08-12 18:37:08.586   751  1236 V AlarmManager: Expired Alarm result :4
,08-12 18:37:08.656   751   766 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 18:37:08.656   751   766 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4386, temperature: 318, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 18:37:08.656   751   766 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
08-12 18:37:08.656   751   766 D BatteryService: stay LED for charging
,08-12 18:37:08.706  6966  6966 E Zygote  : v2
,08-12 18:37:08.706  6966  6966 I libpersona: KNOX_SDCARD checking this for 1000
,08-12 18:37:08.706  6966  6966 I libpersona: KNOX_SDCARD not a persona
,08-12 18:37:08.716  6966  6966 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-12 18:37:08.716  6966  6966 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 18:37:08.716  6966  6966 E Zygote  : accessInfo : 0
,08-12 18:37:08.716   751  1236 I ActivityManager: Start proc 6966:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,08-12 18:37:08.726  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-12 18:37:08.726  1384  1384 I PERF    : received broadcast android.intent.action.TIME_TICK
08-12 18:37:08.726  1384  1384 D KeyguardUpdateMonitor: handleTimeUpdate
,08-12 18:37:08.736   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 18:37:08.756  1384  1384 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-12 18:37:08.776  2304  2304 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 18:37:08.776  2304  2748 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 18:37:08.786   751   751 I MotionRecognitionService: Plugged
,08-12 18:37:08.786   751   751 D MotionRecognitionService:   cableConnection= 1
08-12 18:37:08.786   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-12 18:37:08.786   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-12 18:37:08.786  1384  1384 D SecKeyguardClockView: HomeTimezone(): 1
,08-12 18:37:08.796  1384  1384 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 18:37:08.796  1384  1384 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-12 18:37:08.796  1384  1384 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 18:37:08.796  1384  1384 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 18:37:08.796  1384  1384 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-12 18:37:08.796  1384  1384 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-12 18:37:08.796  1384  1384 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 18:37:08.796  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-12 18:37:08.796  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 18:37:08.796  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-12 18:37:08.796  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 18:37:08.796  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-12 18:37:08.796  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 18:37:08.816  6966  6966 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 18:37:08.816  6966  6966 D ActivityThread: Added TimaKeyStore provider
,08-12 18:37:08.836  6966  6966 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package null
,08-12 18:37:08.846  6966  6966 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm
,08-12 18:37:08.856  1384  1384 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 18:37:08.876   751  1771 I ActivityManager: Killing 5974:com.google.android.apps.magazines/u0a127 (adj 15): DHA:empty #37
,08-12 18:37:08.896   751  2390 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.magazines, Auto Run ON
,08-12 18:37:12.626   751  3443 D SSRM:n  : SIOP:: AP = 360, PST = 420, CUR = 450, LCD = 0
,08-12 18:37:13.206   751  3475 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 18:37:18.786   751  1771 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 18:37:18.796   751  1771 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 318, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 18:37:18.796   751  1771 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-12 18:37:18.796   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 18:37:18.806   751   751 I MotionRecognitionService: Plugged
,08-12 18:37:18.806   751   751 D MotionRecognitionService:   cableConnection= 1
,08-12 18:37:18.806   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 18:37:18.806   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-12 18:37:18.806  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 18:37:18.806  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 18:37:18.816  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 18:37:18.816  1384  1384 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 18:37:18.826  2304  2304 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 18:37:18.826  2304  2748 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 18:37:18.836   751  1771 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 42ms
,08-12 18:37:18.836   751  1771 D LightsService: [api] [SvcLED] setFlashing :: id = 5, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 751) 
,08-12 18:37:18.836   751  1771 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=5) set On
,08-12 18:37:18.836  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:37:18.846  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:37:18.846  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:37:18.846   751  1771 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,08-12 18:37:18.846   751  1771 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,08-12 18:37:18.856   751  1771 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,08-12 18:37:18.856   751  1771 D BatteryService: turn on LED for fully charged
,08-12 18:37:19.236   751  1219 E LightSensor: RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=0, cpl=3202560
,08-12 18:37:19.236   751   896 D LightsService: [SvcLED]  onSensorChanged::light value = 0
,08-12 18:37:19.236   751   896 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,08-12 18:37:19.246   751   896 D SensorManager: unregisterListener ::   
,08-12 18:37:19.256   751   896 D lights  : led_pattern : 5 +
,08-12 18:37:19.266   751   896 D lights  : led_pattern : 5 -
,08-12 18:37:19.276   751   896 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,08-12 18:37:19.276   751   896 V AlarmManager:  remove PendingIntent] PendingIntent{edc94e6: PendingIntentRecord{92daa27 android broadcastIntent}}
,08-12 18:37:19.306  4161  5065 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-12 18:37:22.686   751  3443 D SSRM:n  : SIOP:: AP = 350, PST = 412, CUR = 450, LCD = 0
,08-12 18:37:23.266   751  1591 E Watchdog: !@Sync 5 [08-12 18:37:23.281]
,08-12 18:37:23.436   751  3444 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,08-12 18:37:23.446   751   837 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1d272f0 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{63a7416 6322:com.samsung.android.sm.provider/1000}
,08-12 18:37:23.576   751  3444 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,08-12 18:37:23.586   751   837 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8319aee u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{63a7416 6322:com.samsung.android.sm.provider/1000}
,08-12 18:37:28.846   751  1771 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 18:37:28.846   751  1771 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 318, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 18:37:28.856   751  1771 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-12 18:37:28.856   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 18:37:28.866   751   751 I MotionRecognitionService: Plugged
,08-12 18:37:28.866   751   751 D MotionRecognitionService:   cableConnection= 1
,08-12 18:37:28.876   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 18:37:28.876   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-12 18:37:28.886   751  1771 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 35ms
,08-12 18:37:28.886   751  1771 D BatteryService: stay LED for fully charged
,08-12 18:37:28.906  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 18:37:28.906  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 18:37:28.906  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 18:37:28.916  2304  2304 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 18:37:28.916  2304  2748 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 18:37:28.926  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:37:28.926  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:37:28.926  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:37:32.746   751  3443 D SSRM:n  : SIOP:: AP = 340, PST = 404, CUR = 450, LCD = 0
,08-12 18:37:32.746   751  3443 D M       : broadcastSiopLevelIntent:: currentSiopLevel = -1
,08-12 18:37:32.766  2794  2794 D ContentApp:  LEVEL : -1
,08-12 18:37:32.806   751   837 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e03ce1c u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bd8dc18 6876:com.sec.android.app.videoplayer/u0a53}
,08-12 18:37:32.806  6876  6876 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,08-12 18:37:32.806  6876  6876 D TranscodeReceiver:  SIOP_LEVEL: -1
,08-12 18:37:33.206   751  3475 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 18:37:38.936   751  1772 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 18:37:38.946   751  1772 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 318, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 18:37:38.946   751  1772 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-12 18:37:38.946   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 18:37:38.956   751   751 I MotionRecognitionService: Plugged
,08-12 18:37:38.956   751   751 D MotionRecognitionService:   cableConnection= 1
,08-12 18:37:38.966   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 18:37:38.966   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-12 18:37:38.966   751  1772 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,08-12 18:37:38.976   751  1772 D BatteryService: stay LED for fully charged
,08-12 18:37:38.976  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 18:37:38.976  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 18:37:38.986  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 18:37:39.006  2304  2304 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 18:37:39.006  2304  2748 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 18:37:39.016  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:37:39.016  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:37:39.016  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:37:42.856   751  3443 D SSRM:n  : SIOP:: AP = 340, PST = 394, CUR = 450, LCD = 0
,08-12 18:37:49.026   751  2390 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 18:37:49.036   751  2390 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 318, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 18:37:49.036   751  2390 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-12 18:37:49.036   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 18:37:49.056   751   751 I MotionRecognitionService: Plugged
,08-12 18:37:49.056   751   751 D MotionRecognitionService:   cableConnection= 1
,08-12 18:37:49.056   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 18:37:49.056   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-12 18:37:49.056   751  2390 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,08-12 18:37:49.056  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 18:37:49.056  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 18:37:49.056  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 18:37:49.066   751  2390 D BatteryService: stay LED for fully charged
,08-12 18:37:49.076  2304  2304 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 18:37:49.076  2304  2748 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 18:37:49.086  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:37:49.086  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:37:49.086  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:37:50.936  2048  3314 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-12 18:37:52.916   751  3443 D SSRM:n  : SIOP:: AP = 330, PST = 382, CUR = 450, LCD = 0
,08-12 18:37:53.206   751  3475 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 18:37:53.276   751  1591 E Watchdog: !@Sync 6 [08-12 18:37:53.288]
,08-12 18:37:54.406  1687  1760 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-12 18:38:00.006   751  1236 V AlarmManager: Expired Alarm result :8
,08-12 18:38:00.086   751  2413 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 18:38:00.096   751  2413 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 317, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 18:38:00.096   751  2413 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-12 18:38:00.096   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 18:38:00.106   751   751 I MotionRecognitionService: Plugged
,08-12 18:38:00.106   751   751 D MotionRecognitionService:   cableConnection= 1
,08-12 18:38:00.116   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 18:38:00.116   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-12 18:38:00.126   751  2413 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,08-12 18:38:00.126   751  2413 D BatteryService: stay LED for fully charged
,08-12 18:38:00.126  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 18:38:00.126  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 18:38:00.136  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 18:38:00.156  2304  2304 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 18:38:00.156  2304  2748 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 18:38:00.166  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:38:00.166  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:38:00.166  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:38:02.976   751  3443 D SSRM:n  : SIOP:: AP = 330, PST = 369, CUR = 450, LCD = 0
,08-12 18:38:10.176   751  1494 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 18:38:10.176   751  1494 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 317, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 18:38:10.176   751  1494 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-12 18:38:10.186   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 18:38:10.196   751   751 I MotionRecognitionService: Plugged
,08-12 18:38:10.196   751   751 D MotionRecognitionService:   cableConnection= 1
,08-12 18:38:10.206   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-12 18:38:10.206   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-12 18:38:10.206   751  1494 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,08-12 18:38:10.206   751  1494 D BatteryService: stay LED for fully charged
08-12 18:38:10.206  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 18:38:10.206  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-12 18:38:10.206  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 18:38:10.226  2304  2304 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 18:38:10.226  2304  2748 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 18:38:10.236  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:38:10.236  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:38:10.236  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:38:13.036   751  3443 D SSRM:n  : SIOP:: AP = 330, PST = 359, CUR = 450, LCD = 0
,08-12 18:38:13.216   751  3475 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 18:38:20.266   751  1948 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 18:38:20.276   751  1948 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 316, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 18:38:20.276   751  1948 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-12 18:38:20.276   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 18:38:20.286   751   751 I MotionRecognitionService: Plugged
,08-12 18:38:20.296   751   751 D MotionRecognitionService:   cableConnection= 1
,08-12 18:38:20.296   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 18:38:20.296   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-12 18:38:20.306  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 18:38:20.306  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-12 18:38:20.306  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 18:38:20.306   751  1948 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 36ms
,08-12 18:38:20.306   751  1948 D BatteryService: stay LED for fully charged
,08-12 18:38:20.326  2304  2304 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 18:38:20.326  2304  2748 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 18:38:20.336  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:38:20.336  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:38:20.336  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:38:23.096   751  3443 D SSRM:n  : SIOP:: AP = 320, PST = 348, CUR = 450, LCD = 0
,08-12 18:38:23.286   751  1591 E Watchdog: !@Sync 7 [08-12 18:38:23.294]
,08-12 18:38:30.356   751  2413 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 18:38:30.356   751  2413 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 316, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 18:38:30.356   751  2413 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-12 18:38:30.366   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 18:38:30.376   751   751 I MotionRecognitionService: Plugged
,08-12 18:38:30.376   751   751 D MotionRecognitionService:   cableConnection= 1
,08-12 18:38:30.386   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 18:38:30.386   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-12 18:38:30.386   751  2413 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,08-12 18:38:30.396   751  2413 D BatteryService: stay LED for fully charged
,08-12 18:38:30.406  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 18:38:30.406  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-12 18:38:30.406  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 18:38:30.416  2304  2304 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 18:38:30.416  2304  2748 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 18:38:30.426  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:38:30.436  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-12 18:38:30.436  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:38:33.166   751  3443 D SSRM:n  : SIOP:: AP = 320, PST = 340, CUR = 450, LCD = 0
,08-12 18:38:33.216   751  3475 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 18:38:40.446   751  1494 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 18:38:40.446   751  1494 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 316, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 18:38:40.446   751  1494 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-12 18:38:40.456   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 18:38:40.466   751   751 I MotionRecognitionService: Plugged
,08-12 18:38:40.476   751   751 D MotionRecognitionService:   cableConnection= 1
,08-12 18:38:40.476   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 18:38:40.476   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-12 18:38:40.486   751  1494 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 37ms
,08-12 18:38:40.486   751  1494 D BatteryService: stay LED for fully charged
,08-12 18:38:40.506  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 18:38:40.506  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-12 18:38:40.506  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 18:38:40.516  2304  2304 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 18:38:40.516  2304  2748 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 18:38:40.526  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:38:40.526  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-12 18:38:40.526  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:38:43.226   751  3443 D SSRM:n  : SIOP:: AP = 320, PST = 334, CUR = 450, LCD = 0
,08-12 18:38:50.536   751  1948 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 18:38:50.536   751  1948 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 315, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 18:38:50.546   751  1948 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-12 18:38:50.546   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 18:38:50.556   751   751 I MotionRecognitionService: Plugged
,08-12 18:38:50.556   751   751 D MotionRecognitionService:   cableConnection= 1
,08-12 18:38:50.566   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 18:38:50.566   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-12 18:38:50.566   751  1948 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,08-12 18:38:50.576   751  1948 D BatteryService: stay LED for fully charged
,08-12 18:38:50.576  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 18:38:50.586  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 18:38:50.586  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 18:38:50.606  2304  2304 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 18:38:50.606  2304  2748 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 18:38:50.616  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:38:50.616  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:38:50.616  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:38:53.226   751  3475 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 18:38:53.286   751  3443 D SSRM:n  : SIOP:: AP = 320, PST = 330, CUR = 450, LCD = 0
,08-12 18:38:53.286   751  1591 E Watchdog: !@Sync 8 [08-12 18:38:53.298]
,08-12 18:38:54.416  1687  1760 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-12 18:38:54.596  1687  1760 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 170ms lastUpdatedAfter : 162045ms
,08-12 18:39:00.626   751  2413 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 18:39:03.346   751  3443 D SSRM:n  : SIOP:: AP = 320, PST = 327, CUR = 450, LCD = 0
,08-12 18:39:10.716   751  1948 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 18:39:10.726   751  1948 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 315, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 18:39:10.726   751  1948 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-12 18:39:10.726   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 18:39:10.736   751   751 I MotionRecognitionService: Plugged
,08-12 18:39:10.746   751   751 D MotionRecognitionService:   cableConnection= 1
,08-12 18:39:10.746   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 18:39:10.746   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-12 18:39:10.756   751  1948 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-12 18:39:10.756   751  1948 D BatteryService: stay LED for fully charged
,08-12 18:39:10.756  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 18:39:10.756  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-12 18:39:10.756  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 18:39:10.776  2304  2304 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 18:39:10.776  2304  2748 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 18:39:10.786  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:39:10.786  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-12 18:39:10.786  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:39:13.226   751  3475 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 18:39:13.406   751  3443 D SSRM:n  : SIOP:: AP = 320, PST = 325, CUR = 450, LCD = 0
,08-12 18:39:20.806   751  2413 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 18:39:20.806   751  2413 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 314, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 18:39:20.816   751  2413 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-12 18:39:20.816   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 18:39:20.826   751   751 I MotionRecognitionService: Plugged
,08-12 18:39:20.836   751   751 D MotionRecognitionService:   cableConnection= 1
,08-12 18:39:20.836   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 18:39:20.836   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-12 18:39:20.836   751  2413 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-12 18:39:20.846   751  2413 D BatteryService: stay LED for fully charged
,08-12 18:39:20.856  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 18:39:20.856  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-12 18:39:20.856  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 18:39:20.866  2304  2304 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 18:39:20.866  2304  2748 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 18:39:20.876  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:39:20.876  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:39:20.886  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:39:23.296   751  1591 E Watchdog: !@Sync 9 [08-12 18:39:23.304]
,08-12 18:39:23.466   751  3443 D SSRM:n  : SIOP:: AP = 320, PST = 323, CUR = 450, LCD = 0
,08-12 18:39:30.886   751  1686 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 18:39:30.886   751  1686 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 314, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-12 18:39:30.886   751  1686 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
08-12 18:39:30.886   751  1686 D BatteryService: stay LED for fully charged
,08-12 18:39:30.886   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 18:39:30.886   751   751 I MotionRecognitionService: Plugged
,08-12 18:39:30.886   751   751 D MotionRecognitionService:   cableConnection= 1
08-12 18:39:30.886   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-12 18:39:30.886   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-12 18:39:30.896  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 18:39:30.896  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-12 18:39:30.896  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 18:39:30.896  2304  2304 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 18:39:30.896  2304  2748 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 18:39:30.916  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:39:30.916  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-12 18:39:30.916  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:39:33.226   751  3475 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 18:39:33.526   751  3443 D SSRM:n  : SIOP:: AP = 320, PST = 322, CUR = 450, LCD = 0
,08-12 18:39:38.006   751  1230 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-12 18:39:38.016   751  1230 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-12 18:39:38.026   751  1229 D TimaService: TimaServiceHandler.handleMessage what =1
,08-12 18:39:38.036   751  1230 I TLC_TIMA_PKM_initialize: initializing...
,08-12 18:39:38.036   751  1230 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,08-12 18:39:38.036   751  1230 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,08-12 18:39:38.046   751  1230 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,08-12 18:39:38.046   751  1230 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,08-12 18:39:38.046   751  1230 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,08-12 18:39:38.046   751  1230 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,08-12 18:39:38.056   751  1230 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,08-12 18:39:38.056   751  1230 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,08-12 18:39:38.056   751  1230 D QSEECOMAPI: : App is not loaded in QSEE
,08-12 18:39:38.106   751  1230 D QSEECOMAPI: : Loaded image: APP id = 3
,08-12 18:39:38.116   751  1230 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,08-12 18:39:38.126   751  1230 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,08-12 18:39:40.976   751  2415 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 18:39:40.986   751  2415 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 313, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 18:39:40.986   751  2415 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-12 18:39:40.986   751  2415 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
,08-12 18:39:40.996   751  2415 D BatteryService: stay LED for fully charged
,08-12 18:39:40.996   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 18:39:41.006  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 18:39:41.006  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-12 18:39:41.006  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 18:39:41.016   751   751 I MotionRecognitionService: Plugged
,08-12 18:39:41.026  2304  2304 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 18:39:41.026  2304  2748 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 18:39:41.026   751   751 D MotionRecognitionService:   cableConnection= 1
08-12 18:39:41.026   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 18:39:41.026   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-12 18:39:41.026  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:39:41.036  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-12 18:39:41.036  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:39:41.466   751  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-12 18:39:41.466   751  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-12 18:39:41.476   751  1230 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-12 18:39:41.486   751  1230 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-12 18:39:43.586   751  3443 D SSRM:n  : SIOP:: AP = 320, PST = 321, CUR = 450, LCD = 0
,08-12 18:39:46.966   314  1194 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-12 18:39:46.966   314  1194 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-12 18:39:46.966   314  1194 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-12 18:39:51.056   751  1948 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 18:39:51.056   751  1948 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 313, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 18:39:51.066   751  1948 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-12 18:39:51.066   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 18:39:51.076   751   751 I MotionRecognitionService: Plugged
,08-12 18:39:51.076   751   751 D MotionRecognitionService:   cableConnection= 1
,08-12 18:39:51.086   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 18:39:51.086   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-12 18:39:51.096   751  1948 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 35ms
,08-12 18:39:51.096   751  1948 D BatteryService: stay LED for fully charged
,08-12 18:39:51.106  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 18:39:51.106  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-12 18:39:51.106  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 18:39:51.116  2304  2304 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 18:39:51.116  2304  2748 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 18:39:51.126  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:39:51.126  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-12 18:39:51.126  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 18:39:53.236   751  3475 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 18:39:53.296   751  1591 E Watchdog: !@Sync 10 [08-12 18:39:53.309]
,08-12 18:39:53.306   314  1194 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-12 18:39:53.306   314  1194 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-12 18:39:53.306   314  1194 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-12 18:39:53.646   751  3443 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450, LCD = 0
,08-12 18:39:54.606  1687  1760 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-12 18:40:01.146   751  1416 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 18:40:02.566  6490  6621 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-12 18:40:02.566  6490  6621 I jxcore-log: 
,08-12 18:40:03.706   751  3443 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450, LCD = 0
,08-12 18:40:03.756  2320  2320 E audit   : type=1400 msg=audit(1471020003.756:289): avc:  denied  { execmod } for  pid=7033 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 18:40:03.756  2320  2320 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 18:40:03.756  2320  2320 E audit   : type=1300 msg=audit(1471020003.756:289): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f8b000 a1=51000 a2=5 a3=4 items=0 ppid=3619 ppcomm=adbd pid=7033 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 18:40:03.756  2320  2320 E audit   : type=1327 msg=audit(1471020003.756:289): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-12 18:40:03.756  2320  2320 E audit   : type=1320 msg=audit(1471020003.756:289): 
,08-12 18:40:03.816  2320  2320 E audit   : type=1400 msg=audit(1471020003.816:290): avc:  denied  { execmod } for  pid=7033 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
,08-12 18:40:03.816  2320  2320 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-12 18:40:03.816  2320  2320 E audit   : type=1300 msg=audit(1471020003.816:290): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f4b000 a1=51000 a2=5 a3=4 items=0 ppid=3619 ppcomm=adbd pid=7033 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
,08-12 18:40:03.816  2320  2320 E audit   : type=1327 msg=audit(1471020003.816:290): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
,08-12 18:40:03.826  2320  2320 E audit   : type=1320 msg=audit(1471020003.816:290): 
,08-12 18:40:03.856  2320  2320 E audit   : type=1400 msg=audit(1471020003.856:291): avc:  denied  { execmod } for  pid=7033 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 18:40:03.856  7033  7033 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-12 18:40:03.856  2320  2320 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-12 18:40:03.866  2320  2320 E audit   : type=1300 msg=audit(1471020003.856:291): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f4b000 a1=51000 a2=5 a3=4 items=0 ppid=3619 ppcomm=adbd pid=7033 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
,08-12 18:40:03.866  7033  7033 D AndroidRuntime: CheckJNI is OFF
,08-12 18:40:03.866  7033  7033 D AndroidRuntime: readGMSProperty: start
08-12 18:40:03.866  2320  2320 E audit   : type=1327 msg=audit(1471020003.856:291): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-12 18:40:03.866  7033  7033 D AndroidRuntime: readGMSProperty: already setted!!
08-12 18:40:03.866  7033  7033 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-12 18:40:03.866  7033  7033 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-12 18:40:03.866  7033  7033 D AndroidRuntime: readGMSProperty: end
08-12 18:40:03.866  7033  7033 D AndroidRuntime: addProductProperty: start
,08-12 18:40:03.866  2320  2320 E audit   : type=1320 msg=audit(1471020003.856:291): ,
,08-12 18:40:03.876  7033  7033 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art,
08-12 18:40:03.876  7033  7033 W art     : aedb2000-b1cd8000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
,08-12 18:40:03.876  7033  7033 W art     : b1cd8000-b3f47000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-12 18:40:03.876  7033  7033 W art     : b3f47000-b3f48000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
,08-12 18:40:03.876  7033  7033 W art     : b3f48000-b3f49000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:40:03.876  7033  7033 W art     : b427b000-b42a4000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art,
08-12 18:40:03.876  7033  7033 W art     : b42a4000-b46f2000 r-xp 00000000 b3:17 332        /system/lib/libart.so
,08-12 18:40:03.876  7033  7033 W art     : b46f2000-b46f3000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b46f3000-b46fd000 r--p 0044e000 b3:17 332        /system/lib/libart.so
,08-12 18:40:03.876  7033  7033 W art     : b46fd000-b46fe000 rw-p 00458000 b3:17 332        /system/lib/libart.so,
,08-12 18:40:03.876  7033  7033 W art     : b46fe000-b4700000 rw-p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b4700000-b4800000 rw-p 00000000 00:00 0          [anon:libc_malloc]
,08-12 18:40:03.876  7033  7033 W art     : b481c000-b481f000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-12 18:40:03.876  7033  7033 W art     : b481f000-b4820000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
,08-12 18:40:03.876  7033  7033 W art     : b4820000-b4821000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-12 18:40:03.876  7033  7033 W art     : b4821000-b4822000 r--p 00000000 00:00 0 
,08-12 18:40:03.876  7033  7033 W art     : b4822000-b4842000 r--s 00000000 00:0b 9219       /dev/__properties__
08-12 18:40:03.876  7033  7033 W art     : b4842000-b5253000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-12 18:40:03.876  7033  7033 W art     : b5253000-b5254000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b5254000-b529d000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
,08-12 18:40:03.876  7033  7033 W art     : b529d000-b529e000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-12 18:40:03.876  7033  7033 W art     : b529e000-b52a6000 rw-p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b52a6000-b52a7000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:40:03.876  7033  7033 W art     : b52a7000-b52dc000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
,08-12 18:40:03.876  7033  7033 W art     : b52dc000-b52dd000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b52dd000-b52de000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-12 18:40:03.876  7033  7033 W art     : b52de000-b52df000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-12 18:40:03.876  7033  7033 W art     : b52df000-b5337000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
,08-12 18:40:03.876  7033  7033 W art     : b5337000-b5338000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b5338000-b5339000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-12 18:40:03.876  7033  7033 W art     : b5339000-b533a000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-12 18:40:03.876  7033  7033 W art     : b533b000-b5341000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
,08-12 18:40:03.876  7033  7033 W art     : b5341000-b5342000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 18:40:03.876  7033  7033 W art     : b5342000-b5343000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
,08-12 18:40:03.876  7033  7033 W art     : b5343000-b5345000 rw-p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b5346000-b5350000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 18:40:03.876  7033  7033 W art     : b5350000-b5353000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
,08-12 18:40:03.876  7033  7033 W art     : b5353000-b5354000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 18:40:03.876  7033  7033 W art     : b5355000-b536c000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 18:40:03.876  7033  7033 W art     : b536c000-b536d000 ---p 00000000 00:00 0 ,
08-12 18:40:03.876  7033  7033 W art     : b536d000-b536e000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 18:40:03.876  7033  7033 W art     : b536e000-b536f000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so,
08-12 18:40:03.876  7033  7033 W art     : b5370000-b537a000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-12 18:40:03.876  7033  7033 W art     : b537a000-b537b000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-12 18:40:03.876  7033  7033 W art     : b537b000-b537c000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
,08-12 18:40:03.876  7033  7033 W art     : b537c000-b5380000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 18:40:03.876  7033  7033 W art     : b5380000-b5381000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 18:40:03.876  7033  7033 W art     : b5381000-b5382000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 18:40:03.876  7033  7033 W art     : b5382000-b5398000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
,08-12 18:40:03.876  7033  7033 W art     : b5398000-b5399000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-12 18:40:03.876  7033  7033 W art     : b5399000-b539a000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-12 18:40:03.876  7033  7033 W art     : b539a000-b53a7000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-12 18:40:03.876  7033  7033 W art     : b53a7000-b53a8000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
,08-12 18:40:03.876  7033  7033 W art     : b53a8000-b53a9000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-12 18:40:03.876  7033  7033 W art     : b53a9000-b5409000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
,08-12 18:40:03.876  7033  7033 W art     : b5409000-b540c000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-12 18:40:03.876  7033  7033 W art     : b540c000-b5410000 rw-p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b5410000-b5471000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-12 18:40:03.876  7033  7033 W art     : b5471000-b5472000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-12 18:40:03.876  7033  7033 W art     : b5472000-b54c1000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-12 18:40:03.876  7033  7033 W art     : b54c1000-b54c3000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-12 18:40:03.876  7033  7033 W art     : b54c3000-b54c4000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
,08-12 18:40:03.876  7033  7033 W art     : b54c4000-b54c5000 rw-p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b54c5000-b54cc000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 18:40:03.876  7033  7033 W art     : b54cc000-b54cd000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 18:40:03.876  7033  7033 W art     : b54cd000-b54ce000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-12 18:40:03.876  7033  7033 W art     : avc_common.so,
08-12 18:40:03.876  7033  7033 W art     : b54cf000-b54d2000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 18:40:03.876  7033  7033 W art     : b54d2000-b54d3000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 18:40:03.876  7033  7033 W art     : b54d3000-b54d4000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-12 18:40:03.876  7033  7033 W art     : enc_common.so
,08-12 18:40:03.876  7033  7033 W art     : b54d5000-b54d9000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-12 18:40:03.876  7033  7033 W art     : b54d9000-b54da000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b54da000-b54db000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-12 18:40:03.876  7033  7033 W art     : b54db000-b54dc000 rw-p 00005000 b3:17 2510       /syste
,08-12 18:40:03.876  7033  7033 W art     : m/lib/libpowermanager.so
08-12 18:40:03.876  7033  7033 W art     : b54dd000-b54fa000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 18:40:03.876  7033  7033 W art     : b54fa000-b54fb000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 18:40:03.876  7033  7033 W art     : b54fb000-b54fc000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 18:40:03.876  7033  7033 W art     : b54fd000-b5502000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
,08-12 18:40:03.876  7033  7033 W art     : b5502000-b5503000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 18:40:03.876  7033  7033 W art     : b5503000-b5504000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 18:40:03.876  7033  7033 W art     : b5505000-b5536000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 18:40:03.876  7033  7033 W art     : b5536000-b5539000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
,08-12 18:40:03.876  7033  7033 W art     : b5539000-b553a000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 18:40:03.876  7033  7033 W art     : b553b000-b5576000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-12 18:40:03.876  7033  7033 W art     : b5576000-b5577000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-12 18:40:03.876  7033  7033 W art     : b5577000-b5578000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-12 18:40:03.876  7033  7033 W art     : b5579000-b5580000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
,08-12 18:40:03.876  7033  7033 W art     : b5580000-b5581000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b5581000-b5582000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-12 18:40:03.876  7033  7033 W art     : b5582000-b5583000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-12 18:40:03.876  7033  7033 W art     : b5583000-b5584000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-12 18:40:03.876  7033  7033 W art     : b5584000-b559b000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-12 18:40:03.876  7033  7033 W art     : b559b000-b559c000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b559c000-b559f000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-12 18:40:03.876  7033  7033 W art     : b559f000-b55a0000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-12 18:40:03.876  7033  7033 W art     : b55a0000-b55bf000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-12 18:40:03.876  7033  7033 W art     : b55bf000-b55c0000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-12 18:40:03.876  7033  7033 W art     : b55c0000-b55c1000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-12 18:40:03.876  7033  7033 W art     : b55c1000-b55ff000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-12 18:40:03.876  7033  7033 W art     : b55ff000-b5600000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b5600000-b5602000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-12 18:40:03.876  7033  7033 W art     : b5602000-b5603000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-12 18:40:03.876  7033  7033 W art     : b5604000-b560b000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 18:40:03.876  7033  7033 W art     : b560b000-b560c000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 18:40:03.876  7033  7033 W art     : b560c000-b560d000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 18:40:03.876  7033  7033 W art     : b560e000-b5611000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 18:40:03.876  7033  7033 W art     : b5611000-b5612000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 18:40:03.876  7033  7033 W art     : b5612000-b5613000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 18:40:03.876  7033  7033 W art     : b5613000-b5619000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 18:40:03.876  7033  7033 W art     : b5619000-b561a000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b561a000-b561b000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 18:40:03.876  7033  7033 W art     : b561b000-b561c000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 18:40:03.876  7033  7033 W art     : b561c000-b5625000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-12 18:40:03.876  7033  7033 W art     : b5625000-b5626000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-12 18:40:03.876  7033  7033 W art     : b5626000-b5627000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-12 18:40:03.876  7033  7033 W art     : b5627000-b56b8000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 18:40:03.876  7033  7033 W art     : b56b8000-b56b9000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b56b9000-b56c4000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 18:40:03.876  7033  7033 W art     : b56c4000-b56c5000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 18:40:03.876  7033  7033 W art     : b56c6000-b56d8000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-12 18:40:03.876  7033  7033 W art     : b56d8000-b56d9000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-12 18:40:03.876  7033  7033 W art     : b56d9000-b56da000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-12 18:40:03.876  7033  7033 W art     : b56db000-b56e0000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-12 18:40:03.876  7033  7033 W art     : b56e0000-b56e1000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-12 18:40:03.876  7033  7033 W art     : b56e1000-b56e2000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-12 18:40:03.876  7033  7033 W art     : b56e3000-b5750000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-12 18:40:03.876  7033  7033 W art     : b5750000-b5751000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b5751000-b5753000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-12 18:40:03.876  7033  7033 W art     : b5753000-b5754000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so,
08-12 18:40:03.876  7033  7033 W art     : b5754000-b5755000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:40:03.876  7033  7033 W art     : b5755000-b575c000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 18:40:03.876  7033  7033 W art     : b575c000-b575d000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 18:40:03.876  7033  7033 W art     : b575d000-b575e000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 18:40:03.876  7033  7033 W art     : b575f000-b57df000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 18:40:03.876  7033  7033 W art     : b57df000-b57e0000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b57e0000-b57e1000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
,08-12 18:40:03.876  7033  7033 W art     : b57e1000-b57e2000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 18:40:03.876  7033  7033 W art     : b57e2000-b57f9000 rw-p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b57f9000-b5830000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-12 18:40:03.876  7033  7033 W art     : ib/libqc-opt.so
08-12 18:40:03.876  7033  7033 W art     : b5830000-b5831000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-12 18:40:03.876  7033  7033 W art     : b5831000-b5832000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-12 18:40:03.876  7033  7033 W art     : b5832000-b584e000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so,
08-12 18:40:03.876  7033  7033 W art     : b584e000-b584f000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 18:40:03.876  7033  7033 W art     : b584f000-b5850000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 18:40:03.876  7033  7033 W art     : b5851000-b58b2000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-12 18:40:03.876  7033  7033 W art     : b58b2000-b58b4000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-12 18:40:03.876  7033  7033 W art     : b58b4000-b58b5000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
,08-12 18:40:03.876  7033  7033 W art     : b58b6000-b58dd000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-12 18:40:03.876  7033  7033 W art     : b58dd000-b58de000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b58de000-b58df000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-12 18:40:03.876  7033  7033 W art     : b58df000-b58e0000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
,08-12 18:40:03.876  7033  7033 W art     : b58e1000-b58e9000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 18:40:03.876  7033  7033 W art     : b58e9000-b58eb000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 18:40:03.876  7033  7033 W art     : b58eb000-b58ec000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 18:40:03.876  7033  7033 W art     : b58ed000-b58f0000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-12 18:40:03.876  7033  7033 W art     : b58f0000-b58f1000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
,08-12 18:40:03.876  7033  7033 W art     : b58f1000-b58f2000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-12 18:40:03.876  7033  7033 W art     : b58f2000-b58f6000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-12 18:40:03.876  7033  7033 W art     : b58f6000-b58f7000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b58f7000-b58f8000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-12 18:40:03.876  7033  7033 W art     : b58f8000-b58f9000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-12 18:40:03.876  7033  7033 W art     : b58f9000-b5909000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
,08-12 18:40:03.876  7033  7033 W art     : b5909000-b590a000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-12 18:40:03.876  7033  7033 W art     : b590a000-b590b000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-12 18:40:03.876  7033  7033 W art     : b590b000-b5951000 rw-p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b5951000-b595a000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-12 18:40:03.876  7033  7033 W art     : b595a000-b595b000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-12 18:40:03.876  7033  7033 W art     : b595b000-b595c000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
,08-12 18:40:03.876  7033  7033 W art     : b595d000-b5962000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-12 18:40:03.876  7033  7033 W art     : b5962000-b5963000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-12 18:40:03.876  7033  7033 W art     : b5963000-b5964000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-12 18:40:03.876  7033  7033 W art     : b5964000-b5967000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 18:40:03.876  7033  7033 W art     : b5967000-b5968000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b5968000-b5969000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
,08-12 18:40:03.876  7033  7033 W art     : b5969000-b596a000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 18:40:03.876  7033  7033 W art     : b596b000-b5983000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 18:40:03.876  7033  7033 W art     : b5983000-b5984000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b5984000-b5985000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 18:40:03.876  7033  7033 W art     : b5985000-b5986000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 18:40:03.876  7033  7033 W art     : b5987000-b5b21000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
,08-12 18:40:03.876  7033  7033 W art     : b5b21000-b5b22000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b5b22000-b5b2f000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-12 18:40:03.876  7033  7033 W art     : b5b2f000-b5b30000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-12 18:40:03.876  7033  7033 W art     : b5b30000-b5b34000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-12 18:40:03.876  7033  7033 W art     : b5b34000-b5b35000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b5b35000-b5b36000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
,08-12 18:40:03.876  7033  7033 W art     : b5b36000-b5b37000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-12 18:40:03.876  7033  7033 W art     : b5b37000-b5b4a000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-12 18:40:03.876  7033  7033 W art     : b5b4a000-b5b4b000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-12 18:40:03.876  7033  7033 W art     : b5b4b000-b5b4c000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-12 18:40:03.876  7033  7033 W art     : b5b4c000-b5b4d000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 18:40:03.876  7033  7033 W art     : b5b4d000-b5b98000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
,08-12 18:40:03.876  7033  7033 W art     : b5b98000-b5b99000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-12 18:40:03.876  7033  7033 W art     : b5b99000-b5b9a000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-12 18:40:03.876  7033  7033 W art     : b5b9a000-b5b9c000 rw-p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b5b9d000-b5bae000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 18:40:03.876  7033  7033 W art     : b5bae000-b5baf000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b5baf000-b5bb0000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 18:40:03.876  7033  7033 W art     : b5bb0000-b5bb1000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so,
08-12 18:40:03.876  7033  7033 W art     : b5bb2000-b5bbc000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-12 18:40:03.876  7033  7033 W art     : b5bbc000-b5bbe000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-12 18:40:03.876  7033  7033 W art     : b5bbe000-b5bbf000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-12 18:40:03.876  7033  7033 W art     : b5bbf000-b5bd8000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-12 18:40:03.876  7033  7033 W art     : b5bd8000-b5bd9000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-12 18:40:03.876  7033  7033 W art     : b5bd9000-b5bdc000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
,08-12 18:40:03.876  7033  7033 W art     : b5bdc000-b5be0000 rw-p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b5be0000-b5c54000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-12 18:40:03.876  7033  7033 W art     : b5c54000-b5c55000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b5c55000-b5c58000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-12 18:40:03.876  7033  7033 W art     : b5c58000-b5c59000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-12 18:40:03.876  7033  7033 W art     : b5c59000-b5c5a000 r--p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b5c5a000-b5c5d000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
,08-12 18:40:03.876  7033  7033 W art     : b5c5d000-b5c5e000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-12 18:40:03.876  7033  7033 W art     : b5c5e000-b5c5f000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-12 18:40:03.876  7033  7033 W art     : b5c5f000-b5c60000 r--p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b5c60000-b5c65000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 18:40:03.876  7033  7033 W art     : b5c65000-b5c66000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 18:40:03.876  7033  7033 W art     : b5c66000-b5c67000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
,08-12 18:40:03.876  7033  7033 W art     : b5c67000-b5c68000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:40:03.876  7033  7033 W art     : b5c68000-b5c6b000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 18:40:03.876  7033  7033 W art     : b5c6b000-b5c6c000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 18:40:03.876  7033  7033 W art     : b5c6c000-b5c6d000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 18:40:03.876  7033  7033 W art     : b5c6d000-b5c6e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:40:03.876  7033  7033 W art     : b5c6e000-b5c72000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-12 18:40:03.876  7033  7033 W art     : b5c72000-b5c73000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so,
08-12 18:40:03.876  7033  7033 W art     : b5c73000-b5c74000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-12 18:40:03.876  7033  7033 W art     : b5c74000-b5c75000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 18:40:03.876  7033  7033 W art     : b5c75000-b5c79000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 18:40:03.876  7033  7033 W art     : b5c79000-b5c7a000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 18:40:03.876  7033  7033 W art     : b5c7a000-b5c7b000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 18:40:03.876  7033  7033 W art     : b5c7b000-b5c7c000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-12 18:40:03.876  7033  7033 W art     : b5c7c000-b5c8a000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-12 18:40:03.876  7033  7033 W art     : b5c8a000-b5c8b000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b5c8b000-b5c8c000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-12 18:40:03.876  7033  7033 W art     : b5c8c000-b5c8d000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-12 18:40:03.876  7033  7033 W art     : b5c8d000-b5c97000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 18:40:03.876  7033  7033 W art     : b5c97000-b5c9a000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so,
08-12 18:40:03.876  7033  7033 W art     : b5c9a000-b5c9b000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 18:40:03.876  7033  7033 W art     : b5c9b000-b5c9c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:40:03.876  7033  7033 W art     : b5c9c000-b5ca6000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-12 18:40:03.876  7033  7033 W art     : b5ca6000-b5ca9000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-12 18:40:03.876  7033  7033 W art     : b5ca9000-b5caa000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-12 18:40:03.876  7033  7033 W art     : b5caa000-b5cae000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
,08-12 18:40:03.876  7033  7033 W art     : b5cae000-b5caf000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-12 18:40:03.876  7033  7033 W art     : b5caf000-b5cb0000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-12 18:40:03.876  7033  7033 W art     : b5cb0000-b5cb1000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:40:03.876  7033  7033 W art     : b5cb1000-b5cbe000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-12 18:40:03.876  7033  7033 W art     : b5cbe000-b5cc0000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-12 18:40:03.876  7033  7033 W art     : b5cc0000-b5cc1000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
,08-12 18:40:03.876  7033  7033 W art     : b5cc1000-b60d3000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-12 18:40:03.876  7033  7033 W art     : b60d3000-b60d4000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b60d4000-b60dd000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-12 18:40:03.876  7033  7033 W art     : b60dd000-b60e1000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-12 18:40:03.876  7033  7033 W art     : b60e1000-b60e2000 rw-p 00000000 00:00 0 ,
08-12 18:40:03.876  7033  7033 W art     : b60e2000-b60e9000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-12 18:40:03.876  7033  7033 W art     : b60e9000-b60ea000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-12 18:40:03.876  7033  7033 W art     : b60ea000-b60eb000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-12 18:40:03.876  7033  7033 W art     : b60eb000-b60ec000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:40:03.876  7033  7033 W art     : b60ec000-b6107000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
,08-12 18:40:03.876  7033  7033 W art     : b6107000-b6108000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-12 18:40:03.876  7033  7033 W art     : b6108000-b6109000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-12 18:40:03.876  7033  7033 W art     : b6109000-b610a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:40:03.876  7033  7033 W art     : b610a000-b6156000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 18:40:03.876  7033  7033 W art     : b6156000-b6157000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b6157000-b6158000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so,
08-12 18:40:03.876  7033  7033 W art     : b6158000-b6159000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 18:40:03.876  7033  7033 W art     : b6159000-b615a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:40:03.876  7033  7033 W art     : b615a000-b615e000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-12 18:40:03.876  7033  7033 W art     : b615e000-b615f000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b615f000-b6160000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
,08-12 18:40:03.876  7033  7033 W art     : b6160000-b6161000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-12 18:40:03.876  7033  7033 W art     : b6161000-b6199000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-12 18:40:03.876  7033  7033 W art     : b6199000-b619a000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-12 18:40:03.876  7033  7033 W art     : b619a000-b619b000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-12 18:40:03.876  7033  7033 W art     : b619b000-b619c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:40:03.876  7033  7033 W art     : b619c000-b623a000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
,08-12 18:40:03.876  7033  7033 W art     : b623a000-b623b000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b623b000-b6259000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-12 18:40:03.876  7033  7033 W art     : b6259000-b625a000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-12 18:40:03.876  7033  7033 W art     : b625a000-b63cd000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-12 18:40:03.876  7033  7033 W art     : b63cd000-b63d8000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-12 18:40:03.876  7033  7033 W art     : b63d8000-b63d9000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-12 18:40:03.876  7033  7033 W art     : b63d9000-b64f0000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
,08-12 18:40:03.876  7033  7033 W art     : b64f0000-b64fb000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-12 18:40:03.876  7033  7033 W art     : b64fb000-b64fc000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-12 18:40:03.876  7033  7033 W art     : b64fc000-b6500000 rw-p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b6500000-b6524000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-12 18:40:03.876  7033  7033 W art     : b6524000-b6526000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-12 18:40:03.876  7033  7033 W art     : b6526000-b6527000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-12 18:40:03.876  7033  7033 W art     : b6527000-b65cd000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so,
08-12 18:40:03.876  7033  7033 W art     : b65cd000-b65da000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-12 18:40:03.876  7033  7033 W art     : b65da000-b65db000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-12 18:40:03.876  7033  7033 W art     : b65db000-b65dc000 rw-p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b65dc000-b662f000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-12 18:40:03.876  7033  7033 W art     : b662f000-b6630000 ---p 00000000 00:00 0 ,
08-12 18:40:03.876  7033  7033 W art     : b6630000-b6631000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-12 18:40:03.876  7033  7033 W art     : b6631000-b6632000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-12 18:40:03.876  7033  7033 W art     : b6632000-b6637000 rw-p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b6637000-b6649000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
,08-12 18:40:03.876  7033  7033 W art     : b6649000-b664a000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b664a000-b664b000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
,08-12 18:40:03.876  7033  7033 W art     : b664b000-b664c000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-12 18:40:03.876  7033  7033 W art     : b664c000-b6653000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 18:40:03.876  7033  7033 W art     : b6653000-b6654000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
,08-12 18:40:03.876  7033  7033 W art     : b6654000-b6655000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 18:40:03.876  7033  7033 W art     : b6655000-b6656000 rw-p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b6656000-b6659000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-12 18:40:03.876  7033  7033 W art     : b6659000-b665a000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-12 18:40:03.876  7033  7033 W art     : b665a000-b665b000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
,08-12 18:40:03.876  7033  7033 W art     : b665b000-b665f000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-12 18:40:03.876  7033  7033 W art     : b665f000-b6660000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-12 18:40:03.876  7033  7033 W art     : b6660000-b6661000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-12 18:40:03.876  7033  7033 W art     : b6661000-b666f000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
,08-12 18:40:03.876  7033  7033 W art     : b666f000-b6670000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b6670000-b6671000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-12 18:40:03.876  7033  7033 W art     : b6671000-b6672000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-12 18:40:03.876  7033  7033 W art     : b6672000-b667b000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 18:40:03.876  7033  7033 W art     : b667b000-b667c000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so,
08-12 18:40:03.876  7033  7033 W art     : b667c000-b667d000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 18:40:03.876  7033  7033 W art     : b667d000-b66e3000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-12 18:40:03.876  7033  7033 W art     : b66e3000-b66e4000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b66e4000-b66e6000 r--p 00066000 b3:17 82         /system/lib/libEGL.so,
,08-12 18:40:03.876  7033  7033 W art     : b66e6000-b66ef000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-12 18:40:03.876  7033  7033 W art     : b66ef000-b66f2000 rw-p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b66f2000-b6789000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
,08-12 18:40:03.876  7033  7033 W art     : b6789000-b678b000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-12 18:40:03.876  7033  7033 W art     : b678b000-b678c000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-12 18:40:03.876  7033  7033 W art     : b678c000-b678d000 rw-p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b678d000-b6aae000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
,08-12 18:40:03.876  7033  7033 W art     : b6aae000-b6aaf000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b6aaf000-b6aca000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-12 18:40:03.876  7033  7033 W art     : b6aca000-b6ace000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-12 18:40:03.876  7033  7033 W art     : b6ace000-b6ad3000 rw-p 00000000 00:00 0 
,08-12 18:40:03.876  7033  7033 W art     : b6ad3000-b6adb000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 18:40:03.876  7033  7033 W art     : b6adb000-b6adc000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 18:40:03.876  7033  7033 W art     : b6adc000-b6add000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 18:40:03.876  7033  7033 W art     : b6add000-b6b0b000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
,08-12 18:40:03.876  7033  7033 W art     : b6b0b000-b6b0c000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b6b0c000-b6b13000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-12 18:40:03.876  7033  7033 W art     : b6b13000-b6b14000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-12 18:40:03.876  7033  7033 W art     : b6b14000-b6b5a000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-12 18:40:03.876  7033  7033 W art     : b6b5a000-b6b5b000 ---p 00000000 00:00 0 ,
08-12 18:40:03.876  7033  7033 W art     : b6b5b000-b6b5e000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-12 18:40:03.876  7033  7033 W art     : b6b5e000-b6b5f000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-12 18:40:03.876  7033  7033 W art     : b6b5f000-b6b7a000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-12 18:40:03.876  7033  7033 W art     : b6b7a000-b6b7e000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
,08-12 18:40:03.876  7033  7033 W art     : b6b7e000-b6b7f000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-12 18:40:03.876  7033  7033 W art     : b6b7f000-b6bcc000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-12 18:40:03.876  7033  7033 W art     : b6bcc000-b6bcd000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b6bcd000-b6bd9000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
,08-12 18:40:03.876  7033  7033 W art     : b6bd9000-b6bda000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-12 18:40:03.876  7033  7033 W art     : b6bda000-b6be7000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-12 18:40:03.876  7033  7033 W art     : b6be7000-b6be8000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b6be8000-b6be9000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-12 18:40:03.876  7033  7033 W art     : b6be9000-b6bea000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so,
08-12 18:40:03.876  7033  7033 W art     : b6bea000-b6bf2000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-12 18:40:03.876  7033  7033 W art     : b6bf2000-b6bf3000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b6bf3000-b6bf4000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-12 18:40:03.876  7033  7033 W art     : b6bf4000-b6bf5000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
,08-12 18:40:03.876  7033  7033 W art     : b6bf5000-b6bfc000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-12 18:40:03.876  7033  7033 W art     : b6bfc000-b6bfd000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-12 18:40:03.876  7033  7033 W art     : b6bfd000-b6bfe000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-12 18:40:03.876  7033  7033 W art     : b6bfe000-b6c12000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
,08-12 18:40:03.876  7033  7033 W art     : b6c12000-b6c14000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-12 18:40:03.876  7033  7033 W art     : b6c14000-b6c15000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-12 18:40:03.876  7033  7033 W art     : b6c15000-b6c3d000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-12 18:40:03.876  7033  7033 W art     : b6c3d000-b6c3f000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
,08-12 18:40:03.876  7033  7033 W art     : b6c3f000-b6c40000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-12 18:40:03.876  7033  7033 W art     : b6c40000-b6c43000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-12 18:40:03.876  7033  7033 W art     : b6c43000-b6c44000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-12 18:40:03.876  7033  7033 W art     : b6c44000-b6c45000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-12 18:40:03.876  7033  7033 W art     : b6c45000-b6c4e000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so,
08-12 18:40:03.876  7033  7033 W art     : b6c4e000-b6c4f000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-12 18:40:03.876  7033  7033 W art     : b6c4f000-b6c50000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-12 18:40:03.876  7033  7033 W art     : b6c50000-b6c70000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-12 18:40:03.876  7033  7033 W art     : b6c70000-b6c71000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
,08-12 18:40:03.876  7033  7033 W art     : b6c71000-b6c72000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-12 18:40:03.876  7033  7033 W art     : b6c72000-b6ce5000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-12 18:40:03.876  7033  7033 W art     : b6ce5000-b6ce9000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-12 18:40:03.876  7033  7033 W art     : b6ce9000-b6cec000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-12 18:40:03.876  7033  7033 W art     : b6cec000-b6cf6000 rw-p 00000000 00:00 0 ,
08-12 18:40:03.876  7033  7033 W art     : b6cf6000-b6d7e000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-12 18:40:03.876  7033  7033 W art     : b6d7e000-b6d7f000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b6d7f000-b6d83000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-12 18:40:03.876  7033  7033 W art     : b6d83000-b6d84000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
,08-12 18:40:03.876  7033  7033 W art     : b6d84000-b6d85000 rw-p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b6d85000-b6dae000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-12 18:40:03.876  7033  7033 W art     : b6dae000-b6daf000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b6daf000-b6db2000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so,
08-12 18:40:03.876  7033  7033 W art     : b6db2000-b6db3000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-12 18:40:03.876  7033  7033 W art     : b6db3000-b6e8d000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 18:40:03.876  7033  7033 W art     : b6e8d000-b6e94000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
,08-12 18:40:03.876  7033  7033 W art     : b6e94000-b6e9c000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 18:40:03.876  7033  7033 W art     : b6e9c000-b6e9d000 rw-p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b6e9d000-b6e9e000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 18:40:03.876  7033  7033 W art     : b6e9e000-b6e9f000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
,08-12 18:40:03.876  7033  7033 W art     : b6e9f000-b6ea0000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:40:03.876  7033  7033 W art     : b6ea0000-b6ea3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:40:03.876  7033  7033 W art     : b6ea3000-b6ec8000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-12 18:40:03.876  7033  7033 W art     : b6ec8000-b6ec9000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b6ec9000-b6ed0000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so,
08-12 18:40:03.876  7033  7033 W art     : b6ed0000-b6ed1000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-12 18:40:03.876  7033  7033 W art     : b6ed1000-b6ed8000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-12 18:40:03.876  7033  7033 W art     : b6ed8000-b6ed9000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-12 18:40:03.876  7033  7033 W art     : b6ed9000-b6eda000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
,08-12 18:40:03.876  7033  7033 W art     : b6eda000-b6edb000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:40:03.876  7033  7033 W art     : b6edb000-b6ef3000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-12 18:40:03.876  7033  7033 W art     : b6ef3000-b6ef4000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b6ef4000-b6ef5000 r--p 00018000 b3:17 918        /system/lib/libutils.so
,08-12 18:40:03.876  7033  7033 W art     : b6ef5000-b6ef6000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-12 18:40:03.876  7033  7033 W art     : b6ef6000-b6f04000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-12 18:40:03.876  7033  7033 W art     : b6f04000-b6f05000 ---p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b6f05000-b6f06000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-12 18:40:03.876  7033  7033 W art     : b6f06000-b6f07000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
,08-12 18:40:03.876  7033  7033 W art     : b6f07000-b6f08000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 18:40:03.876  7033  7033 W art     : b6f08000-b6f0a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:40:03.876  7033  7033 W art     : b6f0a000-b6f0b000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:40:03.876  7033  7033 W art     : b6f0b000-b6f0c000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 18:40:03.876  7033  7033 W art     : b6f0c000-b6f0d000 rw-p 00000000 00:00 0          [anon:linker_alloc_32],
08-12 18:40:03.876  7033  7033 W art     : b6f0d000-b6f0e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:40:03.876  7033  7033 W art     : b6f0e000-b6f2e000 r--s 00000000 00:0b 9219       /dev/__properties__
08-12 18:40:03.876  7033  7033 W art     : b6f2e000-b6f2f000 r--p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b6f2f000-b6f30000 ---p 00000000 00:00 0 
,08-12 18:40:03.876  7033  7033 W art     : b6f30000-b6f32000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-12 18:40:03.876  7033  7033 W art     : b6f32000-b6f33000 r-xp 00000000 00:00 0          [sigpage]
08-12 18:40:03.876  7033  7033 W art     : b6f33000-b6f4e000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-12 18:40:03.876  7033  7033 W art     : b6f4e000-b6f4f000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-12 18:40:03.876  7033  7033 W art     : b6f4f000-b6f51000 rw-p 0001b000 b3:17 2770       /system/bin/linker
,08-12 18:40:03.876  7033  7033 W art     : b6f51000-b6f53000 rw-p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : b6f53000-b6f58000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-12 18:40:03.876  7033  7033 W art     : b6f58000-b6f59000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-12 18:40:03.876  7033  7033 W art     : b6f59000-b6f5a000 rw-p 00000000 00:00 0 
08-12 18:40:03.876  7033  7033 W art     : bec0c000-bec2d000 rw-p 00000000 00:00 0          [stack]
,08-12 18:40:03.876  7033  7033 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-12 18:40:03.926  7033  7033 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-12 18:40:03.976  7033  7033 I Radio-JNI: register_android_hardware_Radio DONE,
,08-12 18:40:03.986  7033  7033 E AffinityControl: AffinityControl: registerfunction enter,
,08-12 18:40:03.996  7033  7033 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 18:40:04.006   751  1412 D PackageManager: START PACKAGE DELETE: observer{101939749}
08-12 18:40:04.006   751  1412 D PackageManager: pkg{<packageName>}
08-12 18:40:04.006   751  1412 D PackageManager: user{0}
08-12 18:40:04.006   751  1412 D PackageManager: caller{2000}
08-12 18:40:04.006   751  1412 D PackageManager: flags{2}
,08-12 18:40:04.016   751  1412 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-12 18:40:04.016   751  1412 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
,08-12 18:40:04.016   751  1412 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-12 18:40:04.016   751  1412 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-12 18:40:04.016   751  1412 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-12 18:40:04.016   751   912 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,08-12 18:40:04.016   751   912 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-12 18:40:04.016   751   912 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-12 18:40:04.016   751   912 D ApplicationPolicy: getApplicationUninstallationEnabled
,08-12 18:40:04.016   751   912 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-12 18:40:04.016   751   912 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-12 18:40:04.016   751   912 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-12 18:40:04.016   751   912 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
,08-12 18:40:04.016   751   837 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
,08-12 18:40:04.016   751   912 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-12 18:40:04.016   751   912 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-12 18:40:04.016   751   837 I ActivityManager: Killing 6490:com.test.thalitest/u0a4 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-12 18:40:04.026   751   837 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-12 18:40:04.026   751   837 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-12 18:40:04.036   751   837 D ActivityManager: mDVFSHelper.acquire()
,08-12 18:40:04.046   751   912 D AASAinstall: there is not AASApackages.xml file
,08-12 18:40:04.076   751  1686 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@32077fa)
,08-12 18:40:04.076   751  1332 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 18:40:04.076   751  1772 D GraphicsStats: Buffer count: 4
,08-12 18:40:04.086   751  1332 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 18:40:04.086   751  1332 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 18:40:04.086   751  2415 I WindowState: WIN DEATH: Window{12fb302 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 18:40:04.086   293   324 I SurfaceFlinger: id=22 Removed NainActivit (6/8)
,08-12 18:40:04.086   293  1296 I SurfaceFlinger: id=22 Removed NainActivit (-2/8)
,08-12 18:40:04.086   293  1297 I SurfaceFlinger: id=22 Removed NainActivit (-2/8)
,08-12 18:40:04.086   751  2415 D InputDispatcher: Focus left window: 6490
,08-12 18:40:04.096   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe86d3a4
,08-12 18:40:04.346   751   912 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-12 18:40:04.436   751   912 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-12 18:40:04.436   751   837 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-12 18:40:04.436   751   837 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-12 18:40:04.436   339   339 W keystore: ENTER clear_uid from uid 1000 for 10004
,08-12 18:40:04.436   751   912 I art     : Starting a blocking GC Explicit
,08-12 18:40:04.446   751   837 E ActivityManager: Failure starting process com.test.thalitest
08-12 18:40:04.446   751   837 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-12 18:40:04.446   751   837 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5273)
08-12 18:40:04.446   751   837 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5190)
08-12 18:40:04.446   751   837 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5028)
08-12 18:40:04.446   751   837 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:2639)
08-12 18:40:04.446   751   837 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:3481)
08-12 18:40:04.446   751   837 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:2595)
08-12 18:40:04.446   751   837 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:4999)
08-12 18:40:04.446   751   837 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:4960)
08-12 18:40:04.446   751   837 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:7375)
08-12 18:40:04.446   751   837 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:9142)
08-12 18:40:04.446   751   837 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:8765)
08-12 18:40:04.446   751   837 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:8920)
08-12 18:40:04.446   751   837 E ActivityManager: 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:461)
08-12 18:40:04.446   751   837 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:2597)
08-12 18:40:04.446   751   837 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 18:40:04.446   751   837 E ActivityManager: 	at android.os.Looper.loop(Looper.java:158)
08-12 18:40:04.446   751   837 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 18:40:04.446   751   837 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-12 18:40:04.456   751   837 I ActivityManager:   Force finishing activity ActivityRecord{a06c99a u0 com.test.thalitest/.MainActivity t168}
,08-12 18:40:04.476   751   837 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-12 18:40:04.476   751   887 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-12 18:40:04.476   751   837 D InputDispatcher: Focused application released
,08-12 18:40:04.486   751   887 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-12 18:40:04.486   751   887 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
08-12 18:40:04.486   751   887 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
08-12 18:40:04.486   751   887 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4342)
08-12 18:40:04.486   751   887 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13468)
08-12 18:40:04.486   751   887 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 18:40:04.486   751   887 D SecWifiDisplayUtil: Metadata value : none
08-12 18:40:04.486   751   887 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-12 18:40:04.486   751   887 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 18:40:04.486   751   887 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-12 18:40:04.486   751   887 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{5a20c52 V.E...... R.....ID 0,0-0,0}
,08-12 18:40:04.486   751   887 W WindowManager: Attempted to add application window with unknown token Token{d6cf2cb ActivityRecord{a06c99a u0 com.test.thalitest/.MainActivity t168 f}}.  Aborting.
,08-12 18:40:04.486   751   887 D ViewRootImpl: #3 mView = null
,08-12 18:40:04.486   751   887 W WindowManager: Token{d6cf2cb ActivityRecord{a06c99a u0 com.test.thalitest/.MainActivity t168 f}} already running, starting window not displayed. Unable to add window -- token Token{d6cf2cb ActivityRecord{a06c99a u0 com.test.thalitest/.MainActivity t168 f}} is not valid; is your activity running?
,08-12 18:40:04.486   293   293 I SurfaceFlinger: id=23 createSurf (1146x1876),1 flag=4, VSBConnecti
,08-12 18:40:04.486   751   766 V WindowOrientationListener: setCurrentAppOrientation :1
08-12 18:40:04.486   751   766 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
,08-12 18:40:04.486   751   887 W WindowManager: view not successfully added to wm, removing view
,08-12 18:40:04.496   751   887 W WindowManager: Exception when adding starting window
08-12 18:40:04.496   751   887 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{5a20c52 V.E...... R.....ID 0,0-0,0} not attached to window manager
08-12 18:40:04.496   751   887 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:451)
08-12 18:40:04.496   751   887 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:377)
08-12 18:40:04.496   751   887 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:122)
08-12 18:40:04.496   751   887 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4399)
08-12 18:40:04.496   751   887 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13468)
08-12 18:40:04.496   751   887 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 18:40:04.496   751   887 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
08-12 18:40:04.496   751   887 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 18:40:04.496   751   887 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-12 18:40:04.496   751   766 D InputDispatcher: Focus entered window: 3506
,08-12 18:40:04.496   751   887 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:751 uid:1000
,08-12 18:40:04.496   751   887 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-12 18:40:04.506   751   887 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:751 uid:1000
08-12 18:40:04.506   751   887 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-12 18:40:04.506   751   839 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{cb2701d u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,08-12 18:40:04.506  1384  1384 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,08-12 18:40:04.506  1742  1742 D Launcher: onRestart, Launcher: 111303122
,08-12 18:40:04.506  1742  1742 D Launcher: onStart, Launcher: 111303122
,08-12 18:40:04.506  1742  1742 D Launcher: setSystemUiTransparency.SettingNotFoundException : set as TRUE
,08-12 18:40:04.506  1742  1742 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-12 18:40:04.506  1742  1742 D Launcher.HomeView: onStart
,08-12 18:40:04.506   751  2415 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-12 18:40:04.506   751  2415 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-12 18:40:04.506   751   751 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-12 18:40:04.516   751   751 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-12 18:40:04.516   751   751 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
08-12 18:40:04.516   751  3443 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-12 18:40:04.516  1742  1742 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 Checking SurfaceTexture if it needs to be updated
,08-12 18:40:04.516  1742  1742 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 SurfaceTexture was set
,08-12 18:40:04.526  2265  2295 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = true on instance = 1
,08-12 18:40:04.526  1742  1742 V ActivityThread: updateVisibility : ActivityRecord{d6f9f22 token=android.os.BinderProxy@6aef634 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,08-12 18:40:04.526   751  2390 V WindowStateAnimator: Finishing drawing window Window{cb2701d u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-12 18:40:04.536   293   293 I SurfaceFlinger: id=24 createSurf (1080x1920),1 flag=4, Mauncher
,08-12 18:40:04.536   293   293 I SurfaceFlinger: id=25 createSurf (1194x288),1 flag=4, VSBConnecti
,08-12 18:40:04.536   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe86d364
,08-12 18:40:04.546   751   887 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-12 18:40:04.546   751   751 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-12 18:40:04.546   751   751 I KnoxTimeoutHandler: SD activityfalse
,08-12 18:40:04.546   751   887 D ActivityManager: mDVFSHelper.release()
08-12 18:40:04.546   751   887 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{28948cf u0 com.samsung.android.MtpApplication/.USBConnection t167} time:342263
,08-12 18:40:04.556  3506  3506 V ActivityThread: updateVisibility : ActivityRecord{4871598 token=android.os.BinderProxy@a0b0bb2 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-12 18:40:04.576   751  1686 V WindowStateAnimator: Finishing drawing window Window{cd78463 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-12 18:40:04.576  3506  3506 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@a0b0bb2 time:342296
,08-12 18:40:04.586   751   887 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-12 18:40:04.586   751   751 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-12 18:40:04.586   751   751 I KnoxTimeoutHandler: SD activityfalse
,08-12 18:40:04.586   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe86d364
,08-12 18:40:04.696   751   912 I art     : Explicit concurrent mark sweep GC freed 133023(8MB) AllocSpace objects, 118(2MB) LOS objects, 27% free, 42MB/58MB, paused 1.749ms total 254.863ms
,08-12 18:40:04.716   751  1771 V WindowStateAnimator: Finishing drawing window Window{6466612 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}: mDrawState=DRAW_PENDING
,08-12 18:40:04.716  1742  1742 D Launcher.HomeView: onStop
,08-12 18:40:04.726   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe86d364
,08-12 18:40:04.726   751   887 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-12 18:40:04.726   751   887 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{34ed334 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t165} time:342445
08-12 18:40:04.726   751   751 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-12 18:40:04.726   751   751 I KnoxTimeoutHandler: SD activityfalse
,08-12 18:40:04.736   751   912 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-12 18:40:04.736   751   912 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
08-12 18:40:04.736   751   912 D AASAinstall: there is not AASApackages.xml file
,08-12 18:40:04.736   751   912 D PackageManager: result of delete: 1{101939749}
,08-12 18:40:04.736  7033  7033 I art     : System.exit called, status: 0
08-12 18:40:04.736  7033  7033 I AndroidRuntime: VM exiting with result code 0.
,08-12 18:40:04.746   751   912 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-12 18:40:04.746   751   912 D PackageManager: userId{-1}
08-12 18:40:04.746   751   912 D PackageManager: andCode{true}
,08-12 18:40:04.746   751   912 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,08-12 18:40:04.776  6060  7063 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-12 18:40:04.776  6060  7063 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-12 18:40:04.776  6060  7063 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-12 18:40:04.796   751   837 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-12 18:40:04.796   751   837 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-12 18:40:04.796   751   837 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-12 18:40:04.806   751   751 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.806   751   751 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.806   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.816  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
08-12 18:40:04.816  1384  1384 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,08-12 18:40:04.816   751   887 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.816   751   825 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.816  1991  1991 E SamsungIME: mOCRHelper is null
,08-12 18:40:04.826  2048  2467 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-12 18:40:04.826   751   887 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.826   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.826   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.836   751  1299 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-12 18:40:04.846   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.846   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 18:40:04.846  1724  1724 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-12 18:40:04.846   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.846   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.846   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 18:40:04.846   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.846   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 18:40:04.846   751   751 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.856   751   825 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.856   751   837 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{53cd677 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{33566b1 4365:com.samsung.klmsagent/u0a18}
08-12 18:40:04.856   751   825 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.856   751   751 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.856   751   751 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.856  4365  4365 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Fri Aug 12 18:40:04 GMT+02:00 2016
,08-12 18:40:04.856   751   751 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.866   751   751 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.866  3198  3230 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-12 18:40:04.866  3198  3230 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-12 18:40:04.866   751   751 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-12 18:40:04.866   751   751 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.866  3198  3230 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-12 18:40:04.866  3198  3230 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-12 18:40:04.866   751  2390 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,08-12 18:40:04.876   751   751 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.876   751   751 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-12 18:40:04.876  4365  4365 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,08-12 18:40:04.876   751   751 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-12 18:40:04.876   751   751 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-12 18:40:04.876   751   751 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.876   751   751 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.876  4365  4365 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
,08-12 18:40:04.876  4365  4365 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-12 18:40:04.876   751   751 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.886   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.886  4365  4365 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-12 18:40:04.886  4365  7070 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 (has extras) }
08-12 18:40:04.886  4365  7070 D KLMS-2.6.032: : KLMSIntentService(): PACKAGE_REMOVED
,08-12 18:40:04.886   751   825 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.886  4365  7070 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().START
,08-12 18:40:04.886  4365  7070 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
08-12 18:40:04.886  4365  7070 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
08-12 18:40:04.886  4365  7070 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-12 18:40:04.886   751  1322 V NetworkStats: removeUidsLocked() for UIDs [10004]
08-12 18:40:04.886   751  1322 D NtpTrustedTime: currentTimeMillis() cache hit
08-12 18:40:04.886   751  1322 V NetworkStats: performPollLocked(flags=0x3)
,08-12 18:40:04.886   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.886   751  1323 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netpolicy.xml -> /data/system/netpolicy.xml.bak
08-12 18:40:04.886   751  1323 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-12 18:40:04.886   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.896   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.896   751  2336 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{53cd677 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a5e4167 751:system/1000}
08-12 18:40:04.896   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-12 18:40:04.896   751  1322 V NetworkStats: performPollLocked() took 7ms
08-12 18:40:04.896   751  1322 D NtpTrustedTime: currentTimeMillis() cache hit
,08-12 18:40:04.896   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-12 18:40:04.896   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.896   751   825 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.896   751   825 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.896   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.896   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.896   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 18:40:04.896   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.906   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.906   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 18:40:04.906   751   825 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.906  4365  7070 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-12 18:40:04.906   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.906   751  1323 D NtpTrustedTime: currentTimeMillis() cache hit
08-12 18:40:04.906   751  1323 D NtpTrustedTime: currentTimeMillis() cache hit
,08-12 18:40:04.906   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.906   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 18:40:04.906   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.906   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 18:40:04.906   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.906   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 18:40:04.906   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.906   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 18:40:04.906   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.906   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 18:40:04.906   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.906   751   825 W ResourcesManager: getTopLevelResources: /system/app/talkback/talkback.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.906  1718  7072 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-12 18:40:04.906  1718  7072 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-12 18:40:04.906  1718  7072 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-12 18:40:04.906  1718  7072 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-12 18:40:04.906  1718  7072 D RegisteredComponentCache: Collect Tech packages for Knox
08-12 18:40:04.916   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.916   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 18:40:04.916   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 18:40:04.916   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.916   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.916   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 18:40:04.916   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.916   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.916   751   751 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.916   751   751 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.916  4365  7070 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-12 18:40:04.926  4365  7070 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x727febe6 in tid 7070 (IntentService[K)
,08-12 18:40:04.926   751  1322 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x738d9000 in tid 1322 (NetworkStats)
,08-12 18:40:04.926   751   751 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
08-12 18:40:04.926   751   751 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
,08-12 18:40:04.926  2320  2320 E audit_log: File locking failed. error= Bad file descriptor
,08-12 18:40:04.926  2320  2320 E audit_log: File locking failed. error= Bad file descriptor
,08-12 18:40:04.936  4365  7070 F libc    : Unable to open connection to debuggerd: Connection refused
,08-12 18:40:04.936  2320  2320 E audit_log: File locking failed. error= Bad file descriptor
,08-12 18:40:04.996   353   353 I Zygote  : Process 4365 exited due to signal (7)
,08-12 18:40:04.996   334   334 E installd: eof
08-12 18:40:04.996   334   334 E installd: failed to read size
08-12 18:40:04.996   334   334 I installd: closing connection
,08-12 18:40:05.006   292   292 I ServiceManager: service 'connectivity' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'sb_service' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'servicediscovery' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'updatelock' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'notification' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'devicestoragemonitor' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'location' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'country_detector' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'sec_location' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'search' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'execute' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'dropbox' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'wallpaper' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'audio' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'DockObserver' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'midi' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'usb' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'serial' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'kiesusb' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'jobscheduler' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'backup' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'appwidget' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'voiceinteraction' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'SecExternalDisplayService' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'diskstats' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'com.samsung.ucs.ucsservice' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'mDNIe' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'AAS' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'MSCS' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'spengestureservice' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'quickconnect' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'samplingprofiler' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'commontime_management' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'dreams' died
08-12 18:40:05.006   331   955 W AudioFlinger: power manager service died !!!
08-12 18:40:05.006   292   292 I ServiceManager: service 'graphicsstats' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'print' died
08-12 18:40:05.006   331   955 W AudioFlinger: power manager service died !!!
08-12 18:40:05.006   292   292 I ServiceManager: service 'edmnativehelper' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'sec_analytics' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'telecom' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'alarm' died
08-12 18:40:05.006  2320  2320 E audit_log: File locking failed. error= Bad file descriptor
08-12 18:40:05.006   292   292 I ServiceManager: service 'context_aware' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'scontext' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'barbeam' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'multiwindow_facade' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'window' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'input' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'restrictions' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'bluetooth_manager' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'bluetooth_secure_mode_manager' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'rcp' died,
08-12 18:40:05.006   292   292 I ServiceManager: service 'user' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'procstats' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'meminfo' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'gfxinfo' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'dbinfo' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'cpuinfo' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'permission' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'processinfo' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'sensorservice' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'mdm.remotedesktop' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'battery' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'usagestats' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'webviewupdate' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'scheduling_policy' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'telephony.registry' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'persona' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'knox_ccm_policy' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'enterprise_license_policy' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'application_policy' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'wifi_policy' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'phone_restriction_policy' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'remoteinjection' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'knox_ucsm_policy' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'edm_proxy' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'display' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'persona_policy' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'activity' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'input_method' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'accessibility' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'cover' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'mount' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'uimode' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'lock_settings' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'deviceidle' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'device_policy' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'harmony_eas_service' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'sdp' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'sdp_log' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'dlp' died,
,08-12 18:40:05.006   292   292 I ServiceManager: service 'log_manager_service' died
08-12 18:40:05.006  1718  1718 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x7168ab05 in tid 1718 (com.android.nfc)
08-12 18:40:05.006   292   292 I ServiceManager: service 'launcherapps' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'voip' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'media_projection' died
,08-12 18:40:05.006   292   292 I ServiceManager: service 'lpnet' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'imms' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'mum_container_policy' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'enterprise_billing_policy' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'otp_service' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'enterprise_shared_device_policy' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'knox_timakeystore_policy' died
,08-12 18:40:05.006   292   292 I ServiceManager: service 'enterprise_policy' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'statusbar' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'clipboard' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'clipboardEx' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'network_management' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'media_session' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'media_router' died
,08-12 18:40:05.006   292   292 I ServiceManager: service 'ABTPersistenceService' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'textservices' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'network_score' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'netstats' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'netpolicy' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'wifip2p' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'wifi' died
,08-12 18:40:05.006   292   292 I ServiceManager: service 'wifihs20' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'wifiscanner' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'rttmanager' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'ethernet' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'package' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'trust' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'fingerprint' died
,08-12 18:40:05.006   292   292 I ServiceManager: service 'batterystats' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'appops' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'power' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'SEAMService' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'media.camera.proxy' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'account' died
,08-12 18:40:05.006   292   292 I ServiceManager: service 'content' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'DirEncryptService' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'LSManager' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'ReactiveService' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'DeviceRootKeyService' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'EngineeringModeService' died
,08-12 18:40:05.006   292   292 I ServiceManager: service 'SatsService' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'sedenial' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'vibrator' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'tw_toolbox' died
08-12 18:40:05.006  1718  1718 F libc    : Unable to open connection to debuggerd: Connection refused
08-12 18:40:05.006   292   292 I ServiceManager: service 'tima' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'iccc' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'cepproxyks' died
,08-12 18:40:05.006   292   292 I ServiceManager: service 'emailksproxy' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'CustomFrequencyManagerService' died
08-12 18:40:05.006   292   292 I ServiceManager: service 'consumer_ir' died
08-12 18:40:05.006   293  1297 D libEGL  : eglTerminate EGLDisplay = 0xb1fc96fc
08-12 18:40:05.006  1879  1890 W Sensors : sensorservice died [0xb3a3af80]
08-12 18:40:05.006   293  1297 D libEGL  : eglTerminate EGLDisplay = 0xb1fc96fc
08-12 18:40:05.006  1384  3502 W Sensors : sensorservice died [0xacef9d80]
,08-12 18:40:05.006   293  1297 I SurfaceFlinger: id=14 Removed EimLayer(Di (6/10)
08-12 18:40:05.006   293  1297 I SurfaceFlinger: id=2 Removed GocusedStac (7/9)
08-12 18:40:05.006   293  1297 I SurfaceFlinger: id=3 Removed EimLayer(Di (0/8)
08-12 18:40:05.006   293  1297 I SurfaceFlinger: id=4 Removed EimLayer(An (0/7)
08-12 18:40:05.006   293  1297 I SurfaceFlinger: id=15 Removed EimLayer(An (0/6)
08-12 18:40:05.006   293  1297 I SurfaceFlinger: id=2 Removed GocusedStac (-2/6)
08-12 18:40:05.006   293  1297 I SurfaceFlinger: id=3 Removed EimLayer(Di (-2/6)
,08-12 18:40:05.006   293  1297 I SurfaceFlinger: id=4 Removed EimLayer(An (-2/6)
08-12 18:40:05.006   293  1297 I SurfaceFlinger: id=18 Removed DolorFade (5/5)
08-12 18:40:05.006   293  1297 I SurfaceFlinger: id=18 Removed DolorFade (-2/5)
08-12 18:40:05.006   293  1297 I SurfaceFlinger: id=5 Removed TtatusBar (4/4)
08-12 18:40:05.006   293  1297 I SurfaceFlinger: id=5 Removed TtatusBar (-2/4)
08-12 18:40:05.006   293  1297 I SurfaceFlinger: id=7 Removed JmageWallpa (0/3)
08-12 18:40:05.006   293  1297 I SurfaceFlinger: id=7 Removed JmageWallpa (-2/3)
08-12 18:40:05.006   293  1297 I SurfaceFlinger: id=24 Removed Mauncher (0/2)
08-12 18:40:05.006   293  1297 I SurfaceFlinger: id=23 Removed VSBConnecti (1/1)
08-12 18:40:05.006   293  1297 I SurfaceFlinger: id=25 Removed VSBConnecti (0/0)
08-12 18:40:05.006   293  1297 I SurfaceFlinger: id=14 Removed EimLayer(Di (-2/0)
08-12 18:40:05.006   293  1297 I SurfaceFlinger: id=15 Removed EimLayer(An (-2/0)
08-12 18:40:05.006   293  1297 I SurfaceFlinger: id=23 Removed VSBConnecti (-2/0)
08-12 18:40:05.006   293  1297 I SurfaceFlinger: id=24 Removed Mauncher (-2/0)
08-12 18:40:05.006   293  1297 I SurfaceFlinger: id=25 Removed VSBConnecti (-2/0)
08-12 18:40:05.006  2848  2859 W Sensors : sensorservice died [0xad83dd00]
08-12 18:40:05.006  1742  1952 W Sensors : sensorservice died [0xacee33c0]
08-12 18:40:05.016  2372  2406 W Sensors : sensorservice died [0xad86de40]
08-12 18:40:05.016  2048  2072 W Sensors : sensorservice died [0xad263ec0]
08-12 18:40:05.016  1724  1724 I PhoneApp: VoIP Headset phone disconnected, cleaning local binding.
08-12 18:40:05.016  2048  2462 E WifiManager: Channel connection lost
08-12 18:40:05.016  1384  1642 E WifiManager: Channel connection lost
08-12 18:40:05.016   293   324 I SurfaceFlinger: restart the boot-animation @ binderDied
08-12 18:40:05.026   293   293 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6ae4000
08-12 18:40:05.026   293   293 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
08-12 18:40:05.026  2304  2304 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9eced894 in tid 2304 (droid.bluetooth)
08-12 18:40:05.026  2304  2304 F libc    : Unable to open connection to debuggerd: Connection refused
08-12 18:40:05.026  2320  2320 E audit_log: File locking failed. error= Bad file descriptor
08-12 18:40:05.026  1724  2181 E WifiManager: Channel connection lost
08-12 18:40:05.026  2848  3185 E WifiManager: Channel connection lost
,08-12 18:40:05.026  5846  5902 E WifiManager: Channel connection lost
,08-12 18:40:05.036  1826  1976 E WifiManager: Channel connection lost
,08-12 18:40:05.046  2848  2848 D BluetoothA2dp: Proxy object disconnected
08-12 18:40:05.046  2366  2366 D BluetoothA2dp: Proxy object disconnected
,08-12 18:40:05.046  2848  2848 D A2dpProfile: Bluetooth service disconnected
08-12 18:40:05.046  2848  2848 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-12 18:40:05.046  2848  2848 D PanProfile: Bluetooth service disconnected
08-12 18:40:05.046   292   292 I ServiceManager: service 'nfc' died
08-12 18:40:05.046   292   292 I ServiceManager: service 'nfccontroller' died
08-12 18:40:05.046   292   292 I ServiceManager: service 'secontroller' died
,08-12 18:40:05.046  2848  2848 D BluetoothMap: Proxy object disconnected
08-12 18:40:05.046  2848  2848 D MapProfile: Bluetooth service disconnected
,08-12 18:40:05.046  2848  2848 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9b90e2bd in tid 2848 (ndroid.settings)
,08-12 18:40:05.046  2848  2848 F libc    : Unable to open connection to debuggerd: Connection refused
,08-12 18:40:05.046  2320  2320 E audit_log: File locking failed. error= Bad file descriptor
,08-12 18:40:05.066   353   353 I Zygote  : Process 1718 exited due to signal (7)
,08-12 18:40:05.106   353   353 I Zygote  : Process 2848 exited due to signal (7)
,08-12 18:40:05.116   353   353 I Zygote  : Process 2304 exited due to signal (7)
,08-12 18:40:05.266   293   293 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
08-12 18:40:05.266   293   548 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,08-12 18:40:05.396   291   291 I lowmemorykiller: ActivityManager disconnected
08-12 18:40:05.396   291   291 I lowmemorykiller: Closing Activity Manager data connection
,08-12 18:40:05.516   293   293 I SurfaceFlinger: Disp[0] Orientation 0=>0
,08-12 18:40:05.516   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe86d3a4
,08-12 18:40:05.526   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe86d3a4
,08-12 18:40:05.526   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe86d38c
,08-12 18:40:05.526   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe86d38c
,08-12 18:40:05.536   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe86d38c
,08-12 18:40:05.536   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe86d38c
,08-12 18:40:05.536   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe86d38c
,08-12 18:40:05.546   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe86d38c
,08-12 18:40:05.556   293   548 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-12 18:40:05.556   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe86d38c

```
