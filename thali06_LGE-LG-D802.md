#### Test 61703351a2a4153_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
D/Finsky  ( 3711): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
W/Settings( 3711): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 3711): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/dalvikvm( 3711): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 3711): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 3711): VFY: replacing opcode 0x6e at 0x011e
I/dalvikvm( 3711): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 3711): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 3711): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 3711): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 3711): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
D/dalvikvm( 3711): VFY: replacing opcode 0x6e at 0x029a
I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3030): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3030): created cursor android.database.sqlite.SQLiteCursor@42891878 on behalf of 3711
I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
I/dalvikvm( 3711): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 3711): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
D/dalvikvm( 3711): VFY: replacing opcode 0x6e at 0x001a
W/GLSActivity( 1536): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1536): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1536): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1536): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1536): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1536): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1536): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1536): 	at dalvik.system.NativeStart.run(Native Method)
I/dalvikvm( 3711): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 3711): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
D/dalvikvm( 3711): VFY: replacing opcode 0x6e at 0x0049
I/IcingCorporaProvider( 2620): UpdateCorporaTask done [took 387 ms] updated apps [took 387 ms] 
E/PlayEventLogger( 3711): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3711): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3711): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3711): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3711): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3711): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3711): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3711): 	at dalvik.system.NativeStart.run(Native Method)
--------- beginning of /dev/log/system
D/NotificationService(  950): updateLightListLocked :r=NotificationRecord(0x42d0e430: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  950): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
D/Finsky  ( 3711): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3711): [1] 2.run: Finished loading 1 libraries.
D/Finsky  ( 3711): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/Finsky  ( 3711): [1] RestoreService.handleStartupIntent: Redelivery of startup intent - dropping it
D/Finsky  ( 3711): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/PackageBroadcastService( 1943): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/ActivityManager(  950): Killing 3338:com.lge.appwidget.lgsearch/u0a97 (adj 15): empty #17
I/ActivityManager(  950): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=3757 uid=10009 gids={50009, 3003}
I/ActivityManager(  950): Delaying start of: ServiceRecord{43593c28 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{43280588 stackId=1, 1 tasks}
I/PackageBroadcastService( 1943): Null package name or gms related package.  Ignoreing.
D/ActivityManager(  950): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bc48f0 u0 com.android.settings/.UsbSettings t2}
I/Icing   ( 1943): updateResources: need to parse f{com.google.android.gms}
D/HyLog   ( 3757): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3757): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 3757): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/AppUp4:Utils( 3630): [getPackageName] uri : package:com.example.hello
D/AppUp4  ( 3630): [PreloadListManagerHelper] action android.intent.action.PACKAGE_ADDED
D/AppUp4  ( 3630): AppUp4:PreloadListManagerHelper isLGApp : com.example.hello
D/[BNRAppListMgrReceiver]( 3388): android.intent.action.PACKAGE_ADDED : com.example.hello
W/System  ( 3711): Ignoring header User-Agent because its value was null.
E/DataScheduler( 3711): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =0
D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
I/ActivityManager(  950): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=3774 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
I/ActivityManager(  950): Killing 3209:com.android.mms/u0a35 (adj 15): empty #17
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/CountryDetector(  950): No listener is left
I/LocationManagerService(  950): remove 42b10590
D/LocationManagerService(  950): provider request: passive ProviderRequest[ON interval=0]
E/BatteryObserver( 1155): usb Uevent not necessary.
D/HyLog   ( 3774): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3774): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 3774): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{43280588 stackId=1, 1 tasks}
D/ActivityManager(  950): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bc48f0 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 291 plugged : true isCharging : false
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  950): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  950): battery changed pluggedType: 2
I/LGEmail ( 3774): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
D/LGEmail ( 3774): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
W/BaseRuntimeLoader( 3774): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3774): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3774): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3774): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/PackageChangeReceiver( 3774): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
I/ActivityManager(  950): Killing 3372:com.lge.clock/u0a10 (adj 15): empty #17
I/IcingCorporaProvider( 2620): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/ActivityManager(  950): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3792 uid=10073 gids={50073, 3003, 1028, 1015}
I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{43280588 stackId=1, 1 tasks}
D/ActivityManager(  950): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bc48f0 u0 com.android.settings/.UsbSettings t2}
D/HyLog   ( 3792): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3792): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 3792): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/IcingCorporaProvider( 2620): UpdateCorporaTask done [took 191 ms] updated apps [took 191 ms] 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm(  950): GC_EXPLICIT freed 2036K, 12% free 27249K/30840K, paused 4ms+13ms, total 165ms
D/Finsky  ( 3711): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/dalvikvm( 3711): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3711): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 3711): VFY: replacing opcode 0x62 at 0x0037
I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/Finsky  ( 3711): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/dalvikvm( 1536): GC_EXPLICIT freed 801K, 29% free 17807K/24832K, paused 2ms+4ms, total 29ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
W/GAV2    ( 3792): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 291 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  950): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/EulaProviderUpdateObserver( 2917): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 2917): uri : package:com.example.hello
I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
W/Finsky  ( 3711): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/ChimeraCfgMgr( 1943): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1943): Loading module APK com.google.android.play.games
D/PackageBroadcastService( 1943): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
I/dalvikvm( 3711): Total arena pages for JIT: 11
I/dalvikvm( 3711): Total arena pages for JIT: 12
I/dalvikvm( 3711): Total arena pages for JIT: 13
I/dalvikvm( 3711): Total arena pages for JIT: 14
,I/ConfigFetchService( 1943): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1943): launchTask
W/dalvikvm( 1943): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/ChimeraCfgMgr( 1943): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1943): Module APK com.google.android.play.games already loaded
V/ConfigFetchTask( 1943): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1Vol4euwL-BVJydD0FVNMKuxbBNjNXX2rZkHPI-h78o4HjnefyGNSfeLYfjOoz8-A-w6gkejZbeoheKFAo-UkDyLqxTZs_h1pzp875nxsccsilmcreENMnGLc3ugbADnJ9tTzuXJH0mx6DaXt8e5RPck3MHBufLS_X2rTyIHutEGk1ivul5_QiocnFkbth4XFUH_XOg
D/ChimeraCfgMgr( 1943): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1943): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1943): Failed to find package metadata for com.example.hello
D/Vision  ( 1943): No vision deps
I/GoogleURLConnFactory( 1943): Using platform SSLCertificateSocketFactory
W/BaseAppContext( 1943): Using Auth Proxy for data requests.
W/BaseAppContext( 1943): Using Auth Proxy for data requests.
I/PeopleContactsSync( 1943): CP2 sync disabled
I/dalvikvm( 1943): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1943): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1943): VFY: replacing opcode 0x6e at 0x000e
I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
E/DataScheduler( 1943): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =0
D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/BaseAppContext( 1943): Using Auth Proxy for data requests.
W/ConfigFetchTask( 1943): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 1943): fetch service done; releasing wakelock
I/ConfigFetchService( 1943): stopping self
W/Finsky  ( 3711): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 3711): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
W/BaseAppContext( 1943): Using Auth Proxy for data requests.
D/Finsky  ( 3711): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
W/BaseAppContext( 1943): Using Auth Proxy for data requests.
D/Finsky  ( 3711): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
W/BaseAppContext( 1943): Using Auth Proxy for data requests.
I/Icing   ( 1943): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/DeviceConnectionService( 1425): client connected with version: 7571000
W/GAV2    ( 3792): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  950): Killing 3419:com.lge.sizechangable.photoalbum/u0a95 (adj 15): empty #17
I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{43280588 stackId=1, 1 tasks}
D/ActivityManager(  950): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bc48f0 u0 com.android.settings/.UsbSettings t2}
D/Icing   ( 1943): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1943): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
I/ActivityManager(  950): Killing 3458:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{43280588 stackId=1, 1 tasks}
D/ActivityManager(  950): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bc48f0 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm( 1943): GC_CONCURRENT freed 1574K, 27% free 18345K/24832K, paused 3ms+2ms, total 26ms
I/ActivityManager(  950): Start proc com.lge.appbox.client:AppBoxCommonService for service com.lge.appbox.client/com.lge.appbox.service.AppBoxCommonService: pid=3850 uid=10011 gids={50011, 3003, 1028, 1015, 2001}
D/HyLog   ( 3850): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3850): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 3850): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/AppUp4:AppBoxApplication( 3850): AppBoxApplication onCreate()
D/AppUp4:AbstractIntentService( 3850): onCreate
D/AppUp4  ( 3850): config : false
D/AppUp4:AbstractEnvInfo( 3850): Config no : EnvRealInfo
D/AppUp4:AutoProfileManager( 3850): db mvno version : 9
E/AppUp4:AutoProfileManager( 3850): what happen...? prepareValid DB... can't do anything...
W/BaseRuntimeLoader( 3850): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3850): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3850): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3850): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/AppUp4  ( 3850): config : false
D/AppUp4:AbstractServerEnvInfo( 3850): Config no : EnvRealInfo
D/AppUp4:AppBoxCommonService( 3850): onCreate()
D/AppUp4:AppBoxCommonService( 3850): onHandleIntent begin.
D/AppUp4:AppBoxCommonService( 3850): Factory mode : 0
I/AppUp4:NetworkUtils( 3850): Active NetworkInfo : null
D/AppUp4:AppBoxCommonService( 3850): Skip invalid intent of hidden update popup .
D/AppUp4:AppBoxCommonService( 3850): onDestroy()
I/ActivityManager(  950): Start proc com.android.mms for service com.android.mms/.transaction.SmsReceiverService: pid=3864 uid=10035 gids={50035, 3003, 1028, 1015, 1023, 4002, 3002}
I/ActivityManager(  950): Killing 3441:com.android.providers.calendar/u0a16 (adj 15): empty #17
I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{43280588 stackId=1, 1 tasks}
D/HyLog   ( 3864): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3864): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 3864): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  950): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bc48f0 u0 com.android.settings/.UsbSettings t2}
I/ConversationSkinProvider( 3864): skin provider oncreate
D/AndroidRuntime( 3842): 
D/AndroidRuntime( 3842): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3842): CheckJNI is OFF
E/[MMS]   ( 3864): MmsSettings: [LGE] MmsSettings.initializeMmsSettings()
D/dalvikvm( 3842): Trying to load lib libjavacore.so 0x0
W/BaseRuntimeLoader( 3864): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3864): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3864): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3864): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/dalvikvm( 3842): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3842): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3842): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3842): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/[MMS]   ( 3864): MmsSettings: [LGE]loadXMLSettings() ++++++++++ >> Load default:false
I/[MMS]   ( 3864): MmsSettings: [LGE]loadXMLSettings() SIM(current) information
I/[MMS]   ( 3864): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 3864): MmsSettings: [LGE]loadXMLSettings() [Build] Country:EU, Operator:OPEN
D/[MMS]   ( 3864): MmsSettings: loadxmlstring=open_eu_mms_config
D/[MMS]   ( 3864): MmsSettings: Matching Xml Data file name = 2131034168
D/ChimeraCfgMgr( 1943): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1943): Module APK com.google.android.play.games already loaded
D/dalvikvm( 3842): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
D/[MMS]   ( 3864): MmsSettings: [LGE]parseDTMF() file doesn't exist
D/[MMS]   ( 3864): MmsSettings: [LGE]setDefaultDTMFVolume() set default DTMF value
E/[MMS]   ( 3864): MmsSettings: [LGE]loadXMLSettings(): Check current items.
D/[MMS]   ( 3864): MmsSettings: [LGE]---------------------------------------->
D/[MMS]   ( 3864): MmsSettings: [LGE]   sms_dr = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   cb_on = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   sms_concat = [5]
D/[MMS]   ( 3864): MmsSettings: [LGE]   sms_char = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   mms_dr_r = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   mms_dr_a = [1]
D/[MMS]   ( 3864): MmsSettings: [LGE]   mms_rr_r = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   mms_rr_a = [1]
D/[MMS]   ( 3864): MmsSettings: [LGE]   auto_retr = [1]
D/[MMS]   ( 3864): MmsSettings: [LGE]   auto_retr_r = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   mms_priority = [1]
D/[MMS]   ( 3864): MmsSettings: [LGE]   mms_validity = [6]
D/[MMS]   ( 3864): MmsSettings: [LGE]   mms_creation = [2]
D/[MMS]   ( 3864): MmsSettings: [LGE]   mms_size = [300]
D/[MMS]   ( 3864): MmsSettings: [LGE]   slide_dur = [5]
D/[MMS]   ( 3864): MmsSettings: [LGE]   recv_adv = [1]
D/[MMS]   ( 3864): MmsSettings: [LGE]   push_on = [1]
D/[MMS]   ( 3864): MmsSettings: [LGE]   del_old = [1]
D/[MMS]   ( 3864): MmsSettings: [LGE]   sms_limit = [500]
D/[MMS]   ( 3864): MmsSettings: [LGE]   mms_limit = [50]
D/[MMS]   ( 3864): MmsSettings: [LGE]   max_editor_num = [2000]
D/[MMS]   ( 3864): MmsSettings: [LGE]   mms_slide_num = [10]
D/[MMS]   ( 3864): MmsSettings: [LGE]   mms_recipient_num = [20]
D/[MMS]   ( 3864): MmsSettings: [LGE]   attachement_storage = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   send_msg_enter_key = [1]
D/[MMS]   ( 3864): MmsSettings: [LGE]   spam_setting = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   anonymous_spam_setting = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   mms_recipient_length = [64]
D/[MMS]   ( 3864): MmsSettings: [LGE]   sms_recipient_length = [20]
D/[MMS]   ( 3864): MmsSettings: [LGE]   recv_adv_invisible = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   mms_creation_invisible = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   mms_dr_r_invisible = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   mms_dr_a_invisible = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   mms_rr_r_invisible = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   mms_rr_a_invisible = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   auto_retr_r_invisible = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   mms_validity_invisible = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   mms_priority_invisible = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   sms_char_invisible = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   sms_dr_invisible = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   sms_validity_invisible = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   discard_visible = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   mms_pending_in_wifi_use = [1]
D/[MMS]   ( 3864): MmsSettings: [LGE]   attach_location = [1]
D/[MMS]   ( 3864): MmsSettings: [LGE]   custom_extract_ui = [1]
D/[MMS]   ( 3864): MmsSettings: [LGE]   msg_list_data_seperator = [1]
D/[MMS]   ( 3864): MmsSettings: [LGE]   animation_effect = [1]
D/[MMS]   ( 3864): MmsSettings: [LGE]   inline_msg_item = [1]
D/[MMS]   ( 3864): MmsSettings: [LGE]   display_as_slide_layout = [1]
D/[MMS]   ( 3864): MmsSettings: [LGE]   one_bubble = [1]
D/[MMS]   ( 3864): MmsSettings: [LGE]   hide_sync_header_update = [1]
D/[MMS]   ( 3864): MmsSettings: [LGE]   recipient_cc_bcc = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   ciq_on = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   mms_enabled_when_data_disabled = [1]
D/[MMS]   ( 3864): MmsSettings: [LGE]   two_finger_flick = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   kr_skt_feature_set = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   kr_kt_feature_set = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   kr_lgu_feature_set = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   docomo_message_setting = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   docomo_sim_card_set = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   docomo_nexti_phonebook_set = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   docomo_function_validity_period = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   docomo_led_button_blink = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   docomo_dtmf_setting = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   china_feature_set = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   media_resolution_restrict_off = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   attachment_save_in_slidesheow = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   mms_max_video_resolution = [320x240]
D/[MMS]   ( 3864): MmsSettings: [LGE]   email_over_sms = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   email_over_sms_gateway_num = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   addr_len_check = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   message_poster = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   sticky_note = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   wificalling_feature_set = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   online_album = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   online_album_dest_num = [000]
D/[MMS]   ( 3864): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   voice_mail = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   smsc_readonly = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   latin_america_fdn_check = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   sms_sent_time_mode = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   fdn_gprs_check = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   reply_to_virtual_smsc = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   save_to_draft = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   mms_signature = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   mms_callback = [0]
D/[MMS]   ( 3864): MmsSettings: [LGE]   message_counters_key = [0]
E/[MMS]   ( 3864): MmsSettings: [LGE]loadXMLSettings(): Check prefMmsConfig.
I/[MMS]   ( 3864): MmsSettings: [LGE]loadXMLSettings() Phone(saved) information
I/[MMS]   ( 3864): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 3864): MmsSettings: [LGE]loadXMLSettings(): SIM is NOT changed!!!
E/[MMS]   ( 3864): MmsSettings: [LGE]loadXMLSettings(): SIM is not ready!!!
D/MmsConfig( 3864): [LGE] setForceSmsGsmAlphabet_SystemProperties.set: 0
I/[MMS]   ( 3864): MmsConfig: [LGE]getUaString=LG-D802 LG-Android-MMS-V4.0/1.2
I/LGDrmService( 3864): _DRM_ServiceGet() : Bind lgdrm service
E/Diag_Lib(  275): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  275): qmi_init:  Created client handle b7009c68
E/Diag_Lib(  275): qmi_client [275] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  275): qmi_client [275] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  275): Sending signal ...... to read cmd data 
E/Diag_Lib(  275): qmi error code.........:0
E/Diag_Lib(  275): qmi sys error code.........:0
D/DRM_Adap(  275): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
E/Diag_Lib(  275): Setting the api flag to : 1
E/Diag_Lib(  275): qmi_client [275] 7: sending 47 bytes on fd = 16
E/Diag_Lib(  275): qmi_client [275] 7: Received 93 bytes on fd = 16
E/Diag_Lib(  275):  API Flag .............. 1 
E/Diag_Lib(  275):  Message ID ............... 37 
E/Diag_Lib(  275): qmi_service_release called, user_handle=20200
E/Diag_Lib(  275): qmi_free_srvc_data : ENTRY
E/Diag_Lib(  275): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib(  275): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib(  275): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib(  275): qmi_service_delete_client_txns : ENTRY - client_id: [2]
E/Diag_Lib(  275): qmi_service_delete_client_txns : EXIT
E/Diag_Lib(  275): qmi_free_srvc_data : ENTRY
E/Diag_Lib(  275): qmi_client [275] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  275): qmi_client [275] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  275): Sending signal ...... to read cmd data 
E/Diag_Lib(  275): qmi error code.........:0
E/Diag_Lib(  275): qmi sys error code.........:0
D/DRM_Adap(  275): drmLibGetIMEI: success getting IMEI
D/LGDRM   (  275): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
E/Diag_Lib(  275): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  275): qmi_init:  Created client handle b7009c80
E/Diag_Lib(  275): qmi_client [275] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  275): qmi_client [275] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  275): Sending signal ...... to read cmd data 
E/Diag_Lib(  275): qmi error code.........:0
E/Diag_Lib(  275): qmi sys error code.........:0
D/DRM_Adap(  275): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
E/Diag_Lib(  275): Setting the api flag to : 1
E/Diag_Lib(  275): qmi_client [275] 7: sending 47 bytes on fd = 16
E/Diag_Lib(  275): qmi_client [275] 7: Received 93 bytes on fd = 16
E/Diag_Lib(  275):  API Flag .............. 1 
E/Diag_Lib(  275):  Message ID ............... 37 
E/Diag_Lib(  275): qmi_service_release called, user_handle=20200
E/Diag_Lib(  275): qmi_free_srvc_data : ENTRY
E/Diag_Lib(  275): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib(  275): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib(  275): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib(  275): qmi_service_delete_client_txns : ENTRY - client_id: [2]
E/Diag_Lib(  275): qmi_service_delete_client_txns : EXIT
E/Diag_Lib(  275): qmi_free_srvc_data : ENTRY
E/Diag_Lib(  275): qmi_client [275] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  275): qmi_client [275] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  275): Sending signal ...... to read cmd data 
E/Diag_Lib(  275): qmi error code.........:0
E/Diag_Lib(  275): qmi sys error code.........:0
D/DRM_Adap(  275): drmLibGetIMEI: success getting IMEI
D/LGDRM   (  275): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
I/DrmWrapper( 3864): isDrmV1 =true
V/DrmWrapper( 3864): isDrmV2 =false
V/MmsConfig( 3864): [isMmsEnabledWhenDataDisabled]value=1
V/MmsConfigStaticVar( 3864): [setMmsEnabledWhenDataDisabled]enabled=true
V/MmsConfigStaticVar( 3864): [setMmsEnabledWhenDataRoamingDisabled]enabled=false
D/CmasFeatures( 3864): [init]CMAS features are initialized for US country. Returning.
V/Contact ( 3864): Contact init()_Create new insatnce
I/MessagingNotification( 3864): registerLEDObserver
I/MessagingNotification( 3864): registerLEDObserver REGISTER
V/TelephonyAutoProfiling(  950): [getValue] FEATURE key : vzw_roaming_state, value : null
D/CountryDetector(  950): The first listener is added
V/MmsConfig( 3864): [getMPDNSupport]is_KrDevice:false is_Mpdn:false is_Roaming:false networkOperator:
D/LocationManagerService(  950): getProviders()=[passive, gps]
D/LocationManagerService(  950): request 4317f1a0 passive Request[POWER_NONE passive fastest=0] from android(1000)
I/LOG_TAG ( 3864): registerContactDBChangeObserver
D/LocationManagerService(  950): provider request: passive ProviderRequest[ON interval=0]
E/ActivityThread( 3864): Failed to find provider info for com.lge.ims.provider.uc
V/SmsReceiverService( 3864): onStart: #1 mResultCode: -1 = Activity.RESULT_OK
V/LGRssiData( 3864): [loadRssi] File not exist 
V/LGRssiData( 3864): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 3864): [loadFeatureFromXml] *** start feature loading from xml
V/TelephonyAutoProfiling( 3864): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 3864): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 3864): [getValue] FEATURE key : vzw_roaming_state, value : null
D/SmsReceiverService( 3864): [LGE] ACTION_SERVICE_STATE_CHANGED received
V/TelephonyAutoProfiling( 3864): [getValue] FEATURE key : vzw_roaming_state, value : null
E/memtrack( 3842): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3842): failed to load memtrack module: -2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 3842): Calling main entry com.android.commands.am.Am
I/ActivityManager(  950): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3842
I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{43280588 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (106 us)
V/ActivityManager(  950): Moving to PAUSING: ActivityRecord{42bc48f0 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm(  950): GC_FOR_ALLOC freed 626K, 12% free 27237K/30840K, paused 65ms, total 65ms
I/dalvikvm-heap(  950): Grow heap (frag case) to 29.594MB for 856096-byte allocation
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm(  950): GC_FOR_ALLOC freed 64K, 12% free 28010K/31680K, paused 65ms, total 65ms
I/dalvikvm-heap(  950): Grow heap (frag case) to 30.349MB for 856096-byte allocation
D/AndroidRuntime( 3842): Shutting down VM
D/dalvikvm( 3842): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
D/UsbSettingsControl( 2536): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2536): [AUTORUN] onPause() : mActiveCurrentFunction = boot
I/SlideAside( 3515): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/ActivityManager(  950): resumeTopActivityLocked: Pausing null
V/ActivityManager(  950): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  950): setFocusedStack: mFocusedStack=ActivityStack{43280588 stackId=1, 2 tasks}
D/ActivityManager(  950): allPausedActivitiesComplete: r=ActivityRecord{42bc48f0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
I/ActivityManager(  950): startService SlideAside
W/ContextImpl(  950): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
V/ActivityManager(  950): Moving to PAUSED: ActivityRecord{42bc48f0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{43280588 stackId=1, 2 tasks}
D/ActivityManager(  950): resumeTopActivityLocked: Restarting ActivityRecord{43298230 u0 com.example.hello/.MainActivity t3}
I/ActivityManager(  950): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3911 uid=10312 gids={50312, 3003, 3001, 3002}
V/ActivityManager(  950): Moving to RESUMED: ActivityRecord{43298230 u0 com.example.hello/.MainActivity t3} (starting new instance)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm(  268): GC_EXPLICIT freed 43K, 34% free 16472K/24832K, paused 1ms+3ms, total 31ms
E/BatteryObserver( 1155): usb Uevent not necessary.
D/HyLog   ( 3911): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3911): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 3911): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 17ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/SlideAside( 3515): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 16ms
D/SlideAside( 3515): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.example.hello (filtered)
V/WebViewChromium( 3911): Binding Chromium to the background looper Looper (main, tid 1) {4281eb70}
I/chromium( 3911): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 3911): Initializing chromium process, renderers=0
I/Adreno-EGL( 3911): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 3911): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 3911): Build Date: 01/20/14 Mon
I/Adreno-EGL( 3911): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 3911): Remote Branch: 
I/Adreno-EGL( 3911): Local Patches: 
I/Adreno-EGL( 3911): Reconstruct Branch: 
W/chromium( 3911): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/dalvikvm( 3911): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3911): VFY: unable to resolve virtual method 172: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3911): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3911): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3911): VFY: unable to resolve virtual method 167: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3911): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3911): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3911): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3911): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3911): VFY: unable to resolve virtual method 225: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3911): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3911): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3911): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3911): VFY: unable to resolve virtual method 183: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3911): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3911): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3911): VFY: unable to resolve virtual method 188: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3911): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3911): CordovaWebView is running on device made by: LGE
D/dalvikvm( 3911): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 3911): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 3911): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3911): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 3911): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/OpenGLRenderer( 3911): Enabling debug mode 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/AwContents( 3911): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  950): IME STATUS OFF
,W/AwContents( 3911): nativeOnDraw failed; clearing to background color.
I/ActivityManager( 3911): Timeline: Activity_idle id: android.os.BinderProxy@42820338 time:39825
I/ActivityManager(  950): Displayed com.example.hello/.MainActivity: +486ms
,I/chromium( 3911): [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 3911): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 3911): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3911): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x428244e8
,D/dalvikvm( 3911): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x428244e8
,D/jxcore_app_log( 3911): JniHelper::setJavaVM(0x416e1838), pthread_self() = 1634027832
,I/ActivityManager(  950): Timeline: Activity_windows_visible id: ActivityRecord{43298230 u0 com.example.hello/.MainActivity t3} time:40101
,D/UsbSettings( 2536): [AUTORUN] onStop()
D/ActivityManager(  950): no-history finish of ActivityRecord{42bc48f0 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  950): Finishing activity token=Token{43267730 ActivityRecord{42bc48f0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  950): Moving to FINISHING: ActivityRecord{42bc48f0 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  950): resumeTopActivityLocked: Top activity resumed ActivityRecord{43298230 u0 com.example.hello/.MainActivity t3}
V/ActivityManager(  950): Moving to STOPPING: ActivityRecord{42bc48f0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
,I/chromium( 3911): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
V/ActivityManager(  950): Moving to STOPPED: ActivityRecord{42bc48f0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/jxcore-log( 3911): Initializing JXcore engine
W/jxcore-log( 3911): JXcore engine is ready
,I/chromium( 3911): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,W/jxcore-log( 3911): Starting JXcore engine
,W/jxcore-log( 3911): Platform android
W/jxcore-log( 3911): 
,W/jxcore-log( 3911): Process ARCH arm
W/jxcore-log( 3911): 
,I/jxcore-log( 3911): JXcore Cordova bridge is ready!
I/jxcore-log( 3911): 
,W/jxcore-log( 3911): JXcore engine is started
,E/jxcore  ( 3911): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js
E/jxcore  ( 3911): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  950): battery changed pluggedType: 2
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  950): Waited long enough for: ServiceRecord{430ec590 u0 com.lge.slideaside/.MainService}
,I/ActivityManager(  950): Killing 3404:com.android.calendar/u0a15 (adj 15): empty #17
,I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{43280588 stackId=1, 2 tasks}
,D/ActivityManager(  950): resumeTopActivityLocked: Top activity resumed ActivityRecord{43298230 u0 com.example.hello/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 3792): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  950): Killing 3351:com.google.android.music:main/u0a107 (adj 15): empty #17
,F/ActivityManager(  950): Service ServiceRecord{43197398 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{42bfa198 3351:com.google.android.music:main/u0a107} not same as in map: null
,F/ActivityManager(  950): Service ServiceRecord{43189628 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{42bfa198 3351:com.google.android.music:main/u0a107} not same as in map: null
,I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{43280588 stackId=1, 2 tasks}
,D/ActivityManager(  950): resumeTopActivityLocked: Top activity resumed ActivityRecord{43298230 u0 com.example.hello/.MainActivity t3}
,I/ConfigService( 1536): onDestroy
,I/CheckinService( 1943): Done disabling old GoogleServicesFramework version
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.415909 Y: -0.300339 Z: 9.798874 
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.415909 .y:-0.300339 .z:9.798874
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.418472 Y: -0.295181 Z: 9.790131 
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.418472 .y:-0.295181 .z:9.790131
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  950): battery changed pluggedType: 2
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 291 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1155): GC_CONCURRENT freed 1282K, 6% free 25440K/26900K, paused 4ms+2ms, total 46ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  950): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 291 plugged : true isCharging : false
,D/WifiController(  950): battery changed pluggedType: 2
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  950): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  950): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 291 plugged : true isCharging : false
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  950): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  950): Waited long enough for: ServiceRecord{43153c60 u0 com.android.mms/.transaction.SmsReceiverService}
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  950): handleInetConditionChange: no active default network - ignore
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 3711): [339] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3711): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 291 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  950): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  950): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/WifiController(  950): battery changed pluggedType: 2
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 291 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  950): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.414001 Y: -0.279144 Z: 9.834000 
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.414001 .y:-0.279144 .z:9.834000
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.414703 Y: -0.279449 Z: 9.788498 
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.414703 .y:-0.279449 .z:9.788498
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/WeatherService( 1848): 2 : TimeTick Intent has been received, Time(hour:min:sec) 13:23:0
,D/WeatherService( 1848): 2 : TimeTick Intent And Screen On
,D/WeatherService( 1848): 2 : SDK version : 19
,D/WeatherQuickCover( 1848): 2 : quick cover state : opened : 0
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1457094180032, nextTick: 60001, mDrawingTime: 0
,D/Weather.Utils( 1848): 2 : Utils getTopActivity com.lge.launcher2 / false
,D/Weather.Utils( 1848): 2 : Utils getTopActivity com.lge.easyhome / false
D/WeatherService( 1848): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1848): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1848): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 13:23:0
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1457094180056, nextTick: 59977, mDrawingTime: 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.398193 Y: -0.270386 Z: 9.818192 
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.398193 .y:-0.270386 .z:9.818192
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.404007 Y: -0.292664 Z: 9.812134 
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.404007 .y:-0.292664 .z:9.812134
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  950): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 289 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  950): battery changed pluggedType: 2
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,W/ContextImpl( 2608): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1212 android.content.ContextWrapper.sendBroadcast:365 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  950): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 289 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.416107 Y: -0.300232 Z: 9.811462 
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.416107 .y:-0.300232 .z:9.811462
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.393219 Y: -0.291275 Z: 9.810822 
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.393219 .y:-0.291275 .z:9.810822
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,I/rmt_storage(  417): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb70df178
I/rmt_storage(  417): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  417): wakelock acquired: 1, error no: 42
,I/rmt_storage(  417): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1223823640)
,I/rmt_storage(  417): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
,I/rmt_storage(  417): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  417): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1223823640) wakelock released: 1, error no: 0
I/rmt_storage(  417): 
I/rmt_storage(  417): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb70df178
,E/Diag_Lib(  727): [IMS_FATAL]| 2912 | 741 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.405426 Y: -0.268097 Z: 9.847778 
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.405426 .y:-0.268097 .z:9.847778
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.390030 Y: -0.274628 Z: 9.823303 
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.390030 .y:-0.274628 .z:9.823303
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.437378 Y: -0.276077 Z: 9.854767 
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.437378 .y:-0.276077 .z:9.854767
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.422806 Y: -0.272552 Z: 9.872040 
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.422806 .y:-0.272552 .z:9.872040
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  950): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.396027 Y: -0.278961 Z: 9.822937 
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.396027 .y:-0.278961 .z:9.822937
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.395370 Y: -0.261627 Z: 9.837173 
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.395370 .y:-0.261627 .z:9.837173
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1457094240050, nextTick: 59982, mDrawingTime: 0
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1457094240058, nextTick: 59974, mDrawingTime: 0
,I/PowerManagerService(  950): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  950): [updateScreenState] screen on = false
,D/KnockOnPowerController(  950): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  950): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  950): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  950): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  950): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  950): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
,I/qcom_sensors_hal(  950): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  950): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 7956 usec
D/KnockOnPowerController(  950): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  950): hal_acquire_resources
,I/qcom_sensors_hal(  950): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  950): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  950): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  950): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
,D/qcom_sensors_hal(  950): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  950): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  950): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  950): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.401428 Y: -0.262512 Z: 9.832550 
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.401428 .y:-0.262512 .z:9.832550
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.395157 Y: -0.266907 Z: 9.849304 
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.395157 .y:-0.266907 .z:9.849304
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,I/Sensors (  354): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,V/qcom_sensors_hal(  950): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  950): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  950): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  950): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  950): proximitySensorChanged  positive = true
I/KnockOnPowerController(  950): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.403793 Y: -0.268448 Z: 9.812851 
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.403793 .y:-0.268448 .z:9.812851
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1,
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.408249 Y: -0.263626 Z: 9.807617 
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.408249 .y:-0.263626 .z:9.807617
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.406113 Y: -0.265823 Z: 9.835098 
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.406113 .y:-0.265823 .z:9.835098
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.413086 Y: -0.265686 Z: 9.821716 
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.413086 .y:-0.265686 .z:9.821716
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  950): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@43159958)
,D/KeyguardViewMediator( 1141): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1141): notifyScreenOnLocked
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/KeyguardViewMediator( 1141): handleNotifyScreenOn
,D/KeyguardViewManager( 1141): onScreenTurnedOn()
V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.403183 Y: -0.266861 Z: 9.818497 
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.403183 .y:-0.266861 .z:9.818497
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  950): **** SHOWN CALLED ****
,I/WindowManager(  950): No lock screen! windowToken=null
D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb7488450
D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
,D/WifiStateMachine(  950): handleScreenStateChanged: true
,D/WifiServiceExtension(  950): sendKtScanInterval  mRtspPlay : false
D/WifiStateMachine(  950): handleMessage: E msg.what=131154
D/WifiStateMachine(  950): processMsg: InitialState
,D/WifiStateMachine(  950): processMsg: DefaultState
D/WifiStateMachine(  950): handleMessage: X
D/WifiStateMachine(  950): handleMessage: E msg.what=131127
,D/WifiStateMachine(  950): processMsg: InitialState
D/WifiStateMachine(  950): processMsg: DefaultState
D/WifiStateMachine(  950): handleMessage: X
,D/WifiStateMachine(  950): handleMessage: E msg.what=131158
D/WifiStateMachine(  950): processMsg: InitialState
D/WifiStateMachine(  950): processMsg: DefaultState
D/WifiStateMachine(  950): setSuspendOptimizations: 4 false
,D/WifiStateMachine(  950): mSuspendOptNeedsDisabled 4
,D/WifiStateMachine(  950): handleMessage: X
,D/WifiOffDelayIfNotUsed(  950): stopMonitoring
,E/AudioSystem(  950): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 950
V/SRS_Proc(  270): ParamSet string: screen_state=on
,D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
,V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1155): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{4313a9a0 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1155): enqueuing start. mLedList.size()=2
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1155): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1848): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 13:24:5
,E/SlideAside( 3515): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,I/SlideAside( 3515): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1848): 2 : This is isUpdating : false
D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1848): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 13:24:5
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/WeatherService( 1848): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1848): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1848): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1155): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1155): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1155): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1155): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1155): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1155): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1155): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 207, B = 207
,D/qdlights( 1155): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 201, B = 201
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  950): Excessive delay in blankDisplay() while turning screen off: 411ms
D/qdlights( 1155): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1155): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 189, B = 189
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1155): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1155): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 177, B = 177
,D/qdlights( 1155): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1155): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 165, B = 165
,D/dalvikvm( 1141): GC_FOR_ALLOC freed 7210K, 13% free 68341K/78080K, paused 49ms, total 52ms
,D/qdlights( 1155): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 159, B = 159
,D/qdlights( 1155): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1155): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 147, B = 147
,D/qdlights( 1155): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 141, B = 141
,D/qdlights( 1155): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 135, B = 135
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
,D/qdlights( 1155): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 129, B = 129
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1457094245787, nextTick: 54245, mDrawingTime: 0
,D/qdlights( 1155): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 123, B = 123
,D/qdlights( 1155): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 117, B = 117
,D/qdlights( 1155): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 111, B = 111
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1457094245823, nextTick: 54210, mDrawingTime: 0
,D/qdlights( 1155): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 105, B = 105
V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.409058 Y: -0.265427 Z: 9.832870 
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.409058 .y:-0.265427 .z:9.832870
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
,D/qdlights( 1155): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 99, B = 99
,D/WeatherService( 1848): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:24:5
,D/WeatherService( 1848): 2 : ACTION screen on
,D/WeatherService( 1848): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1848): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:24:5
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/qdlights( 1155): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 93, B = 93
,V/TelephonyAutoProfiling(  950): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  405): Reading a NULL string not supported here.
E/Parcel  (  405): Reading a NULL string not supported here.
E/Parcel  (  405): Reading a NULL string not supported here.
,E/Parcel  (  405): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/GsmSST  ( 1450): Emergency Service
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1450): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_RAD_TEST, value : null
D/qdlights( 1155): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 87, B = 87
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_gfit, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1450): [PhoneIntfMgr] sigLevel = 5
,V/PhoneApp( 1450): Action intent recieved:android.intent.action.SCREEN_ON
D/qdlights( 1155): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 81, B = 81
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  950): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  950): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  950): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  950): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,D/KeyguardViewMediator( 1141): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1141): notifyScreenOffLocked
,V/ActivityManager(  950): Moving to PAUSING: ActivityRecord{43298230 u0 com.example.hello/.MainActivity t3}
D/qdlights( 1155): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 75, B = 75
D/qcom_sensors_hal(  950): hal_acquire_resources
D/qcom_sensors_hal(  950): hal_acquire_resources: Deactivating sensor handle=0
,D/qcom_sensors_hal(  950): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=1000
V/ActivityManager(  950): Moving to PAUSED: ActivityRecord{43298230 u0 com.example.hello/.MainActivity t3} (pause complete)
V/ActivityManager(  950): Moving to STOPPING: ActivityRecord{43298230 u0 com.example.hello/.MainActivity t3} (stop requested)
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  950): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  950): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  950): hal_smgr_report_delete: Rcvd success response from request
D/qdlights( 1155): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 69, B = 69
,D/KeyguardViewMediator( 1141): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,I/LGImmersionVibrator(  950): Vibrator off
,D/UsbSettings( 2536): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/ActivityManager(  950): Moving to DESTROYING: ActivityRecord{42bc48f0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  950): Moving to STOPPED: ActivityRecord{43298230 u0 com.example.hello/.MainActivity t3} (stop complete)
D/WifiStateMachine(  950): handleScreenStateChanged: false
D/WifiStateMachine(  950): handleMessage: E msg.what=131154
D/WifiStateMachine(  950): processMsg: InitialState
D/WifiStateMachine(  950): processMsg: DefaultState
D/WifiStateMachine(  950): handleMessage: X
D/WifiStateMachine(  950): handleMessage: E msg.what=131158
D/WifiStateMachine(  950): processMsg: InitialState
D/WifiStateMachine(  950): processMsg: DefaultState
D/WifiStateMachine(  950): setSuspendOptimizations: 4 true
D/WifiStateMachine(  950): mSuspendOptNeedsDisabled 0
D/WifiStateMachine(  950): handleMessage: X
D/qdlights( 1155): set_light_notifications: 2,ff003f3f,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 63, B = 63
V/UsbSettings( 2536): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2536): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2536): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
,E/AudioSystem(  950): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 950
V/SRS_Proc(  270): ParamSet string: screen_state=off
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
D/KeyguardViewMediator( 1141): handleNotifyScreenOff
D/WifiController(  950): CMD_SCREEN_OFF 
,D/WifiController(  950): shouldWifiStayAwake TRUE
,D/KeyguardViewManager( 1141): onScreenTurnedOff()
D/qdlights( 1155): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 57, B = 57
,E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/VolumeVibrator( 1155): clear
D/qdlights( 1155): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 51, B = 51
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/ActivityManager(  950): Moving to DESTROYED: ActivityRecord{42bc48f0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{43280588 stackId=1, 1 tasks}
,D/ActivityManager(  950): resumeTopActivityLocked: Going to sleep and all paused
I/[LGHome]EVENT( 1488): [Launcher.java:1567:onReceive()]Screen Off
D/qdlights( 1155): set_light_notifications: 2,ff002d2d,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 45, B = 45
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
E/Parcel  (  405): Reading a NULL string not supported here.
E/Parcel  (  405): Reading a NULL string not supported here.
E/Parcel  (  405): Reading a NULL string not supported here.
,E/Parcel  (  405): Reading a NULL string not supported here.
D/qdlights( 1155): set_light_notifications: 2,ff002727,10,0,2
D/WeatherService( 1848): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:24:5
D/qdlights( 1155): [Current] = 255, R = 0, G = 39, B = 39
,D/WeatherService( 1848): 2 : ACTION screen off
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
V/TelephonyAutoProfiling(  950): [getValue] FEATURE key : trf_based_vzw, value : null
,D/WeatherService( 1848): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:24:5
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1450): [PhoneIntfMgr] sigLevel = 5
D/qdlights( 1155): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 33, B = 33
D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
D/GsmSST  ( 1450): Emergency Service
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1450): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_assisted_dialing, value : null
D/NfcService( 1475): NFC-C OFF
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1450): Action intent recieved:android.intent.action.SCREEN_OFF
,D/qdlights( 1155): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 27, B = 27
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1463): [TangibleIO] LCD is off. Remove tangible if exist.
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/qdlights( 1155): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1155): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1155): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  354): sns_pwr.c(320):releasing wakelock
,E/ThermalEngine(  285): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1141): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/PhoneApp( 1450): getIsInUseVoLTE : false
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/PhoneApp( 1450): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1141): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/KeyguardViewMediator( 1141): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1141): doKeyguard is called, but is not locked.
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  950): handleInetConditionChange: no active default network - ignore
W/SocketClient(  264): write error (Broken pipe)
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1457094258829804475; DSPS: 5126610; Offset: 1457094102378083284
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1457094278830699051; DSPS: 5782000; Offset: 1457094102378062333
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1457094298832187742; DSPS: 6437408; Offset: 1457094102378086180
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1457094300057, nextTick: 59973, mDrawingTime: 1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1457094300059, nextTick: 59973, mDrawingTime: 0
,TIME-OUT KILL (timeout was 150000ms)
```
