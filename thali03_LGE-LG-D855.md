#### Test 5753124374916c2_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
I/MusicWidget( 2759): mDelayedStopHandler : unbind
,I/MusicBrowser( 2181): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2181): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2181): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2181): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2181): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2181): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2181): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2181): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1036):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1b7161facom.lge.music.MediaPlaybackService$5@3c7d13ab
D/MusicBrowser( 2181): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2181): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2181): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2181): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2181): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@1c6c2e31
I/MusicBrowser( 2181): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2181): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2181): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2181): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2181): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2181): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2181): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2181): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2181): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2181): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2181): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2181): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2181): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2181): reset
V/MediaPlayer[Native]( 2181): setListener
V/MediaPlayer[Native]( 2181): disconnect
V/MediaPlayer[Native]( 2181): destructor
V/AudioFlinger(  316): releasing 13 from 2181 for -1
V/AudioFlinger(  316):  decremented refcount to 0
V/AudioFlinger(  316): purging stale effects
V/MediaPlayer[Native]( 2181): disconnect
D/MusicBrowser( 2181): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
I/SmartShareClient( 2181): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2181): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2181): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2181): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2181): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2181): [SmartShareManagerClient] unregisterListener: 1048685064
W/SmartShareClient( 2181): [SmartShareManagerClient] unregisterListener invalid listener: 1048685064
I/SmartShareClient( 2181): [SmartShareManagerClient] terminate service: 2181/MediaPlaybackService/680353439
E/HomeCloudIF( 2181): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2181): [SmartShareManagerClient] unbindService context:android.app.Application@293405a1
E/BooksSync( 6846): Soft error: 
E/BooksSync( 6846): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6846): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4722532658879914067&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6846): Headers:
E/BooksSync( 6846): accept-encoding: [gzip]
E/BooksSync( 6846): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6846): gdata-version: 2
E/BooksSync( 6846): 
E/BooksSync( 6846): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6846): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6846): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6846): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6846): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6846): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6846): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6846): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6846): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6846): {
E/BooksSync( 6846):  "error": {
E/BooksSync( 6846):   "errors": [
E/BooksSync( 6846):    {
E/BooksSync( 6846):     "domain": "global",
E/BooksSync( 6846):     "reason": "required",
E/BooksSync( 6846):     "message": "Login Required",
E/BooksSync( 6846):     "locationType": "header",
E/BooksSync( 6846):     "location": "Authorization"
E/BooksSync( 6846):    }
E/BooksSync( 6846):   ],
E/BooksSync( 6846):   "code": 401,
E/BooksSync( 6846):   "message": "Login Required"
E/BooksSync( 6846):  }
E/BooksSync( 6846): }
E/BooksSync( 6846): 
E/BooksSync( 6846): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6846): 	... 8 more
V/CloudHub( 2181): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2181): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2181): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2181): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
--------- beginning of system
I/ActivityManager( 1036): Killing 6409:com.android.defcontainer/u0a4 (adj 15): empty #17
E/BooksSync( 6846): Sync error
E/BooksSync( 6846): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6846): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4722532658879914067&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6846): Headers:
E/BooksSync( 6846): accept-encoding: [gzip]
E/BooksSync( 6846): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6846): gdata-version: 2
E/BooksSync( 6846): 
E/BooksSync( 6846): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6846): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6846): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6846): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6846): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6846): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6846): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6846): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6846): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6846): {
E/BooksSync( 6846):  "error": {
E/BooksSync( 6846):   "errors": [
E/BooksSync( 6846):    {
E/BooksSync( 6846):     "domain": "global",
E/BooksSync( 6846):     "reason": "required",
E/BooksSync( 6846):     "message": "Login Required",
E/BooksSync( 6846):     "locationType": "header",
E/BooksSync( 6846):     "location": "Authorization"
E/BooksSync( 6846):    }
E/BooksSync( 6846):   ],
E/BooksSync( 6846):   "code": 401,
E/BooksSync( 6846):   "message": "Login Required"
E/BooksSync( 6846):  }
E/BooksSync( 6846): }
E/BooksSync( 6846): 
E/BooksSync( 6846): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6846): 	... 8 more
I/BooksSync( 6846): Finished books sync
I/CloudHub( 2181): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29976
W/libprocessgroup( 1036): failed to open /acct/uid_10004/pid_6409/cgroup.procs: No such file or directory
D/AndroidRuntime( 6899): 
D/AndroidRuntime( 6899): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6899): CheckJNI is OFF
D/SyncManager( 1036): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 79558, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/ActivityManager( 1036): Killing 6563:com.google.android.partnersetup/u0a8 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_10008/pid_6563/cgroup.procs: No such file or directory
D/AndroidRuntime( 6899): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1036): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1937): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1036): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1036): setTaskToReturnTo : TaskRecord{18b0253 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1036): setTaskToReturnTo : TaskRecord{18b0253 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1036): AppWindowTokenEx init.. 
E/GBMv2   (  335): DFP En is all cleared set to be enabled
I/ActivityManager( 1036): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6933 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6899): Shutting down VM
D/DSDPConnection( 1849): Display #0 changed.
V/ActivityManager( 1036): Display changed displayId=0
D/SplitWindowPolicy( 1937): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1937): topRunningActivity=ActivityInfo{2daed32f co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1937): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1937): topRunningActivity=ActivityInfo{3d226d3c co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
I/art     ( 2068): Explicit concurrent mark sweep GC freed 22932(1363KB) AllocSpace objects, 10(1440KB) LOS objects, 51% free, 30MB/62MB, paused 1.692ms total 65.940ms
V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2068): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2068): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2068): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2068): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ContextHelper( 6933): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2068): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2068): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2068): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2068): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2068): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2068): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2068): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/ContactsSyncAdapter( 2068): innerSync failed
D/ContactsSyncAdapter( 2068): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2068): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2068): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2068): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2068): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2068): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2068): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2068): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2068): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2068): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2068): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2068): 	at android.os.Bin,der.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
D/SyncManager( 1036): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 102009, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1036): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 167305, reason: 10019
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2c928bbd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/WebViewFactory( 6933): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6933): Loading: webviewchromium
I/LibraryLoader( 6933): Time to load native libraries: 3 ms (timestamps 6498-6501)
I/LibraryLoader( 6933): Expected native library version number "",actual native library version number ""
I/GAV2    ( 6846): Thread[GAThread,5,main]: No campaign data found.
V/WebViewChromiumFactoryProvider( 6933): Binding Chromium to main looper Looper (main, tid 1) {288d5e9f}
I/LibraryLoader( 6933): Expected native library version number "",actual native library version number ""
I/chromium( 6933): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6933): Initializing chromium process, renderers=0
W/art     ( 6933): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  316): registerClient() client 0xb558a2a0, uid 10311
D/BluetoothManagerService( 1036): Message: 20
D/BluetoothManagerService( 1036): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@23ba18b5:true
W/chromium( 6933): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6933): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6933): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 6933): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6933): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6933): Build Date: 12/12/14 금
I/Adreno-EGL( 6933): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6933): Remote Branch: 
I/Adreno-EGL( 6933): Local Patches: 
I/Adreno-EGL( 6933): Reconstruct Branch: 
W/ProcessCpuTracker( 1036): Skipping unknown process pid 6909
W/ProcessCpuTracker( 1036): Skipping unknown process pid 6912
W/chromium( 6933): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6933): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6933): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6933): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6933): CordovaWebView is running on device made by: LGE
W/art     ( 6933): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6933): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6933): Render dirty regions requested: true
I/OpenGLRenderer( 6933): Initialized EGL, version 1.4
D/OpenGLRenderer( 6933): Enabling debug mode 0
D/Atlas   ( 6933): Validating map...
D/SplitWindow( 1036): check instance of lgWin Window{756a487 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 6933): LgDataFeature() Constructor: none
D/LgDataFeature( 6933): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1036): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1472): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1472): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1472):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1472): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1036): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1036): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1036): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@25e72728,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/ActivityManager( 1036): Displayed com.test.thalitest/.MainActivity: +614ms (total +723ms)
I/Timeline( 1036): Timeline: Activity_windows_visible id: ActivityRecord{22177790 u0 com.test.thalitest/.MainActivity t4} time:106938
I/Timeline( 6933): Timeline: Activity_idle id: android.os.BinderProxy@1c112d8f time:106940
D/JsMessageQueue( 6933): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 6933): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6933): 
D/jxcore_app_log( 6933): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435229952
I/chromium( 6933): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6933): 
I/chromium( 6933): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/GBMv2   (  335): DFP En is all cleared set to be enabled
,E/GBMv2   (  335): Set value is all cleared set the max
I/GBMv2   (  335): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6933): Initializing JXcore engine
W/jxcore-log( 6933): JXcore engine is ready
,W/Thread-799( 6994): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10260]" dev="sockfs" ino=10260 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-799( 6994): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-799( 6994): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8701]" dev="sockfs" ino=8701 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-799( 6994): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-799( 6994): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33482]" dev="sockfs" ino=33482 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6933): Starting JXcore engine
,W/jxcore-log( 6933): Platform android
W/jxcore-log( 6933): 
W/jxcore-log( 6933): Process ARCH arm
W/jxcore-log( 6933): 
,I/jxcore-log( 6933): JXcore Cordova bridge is ready!
I/jxcore-log( 6933): 
,W/jxcore-log( 6933): JXcore engine is started
I/jxcore-log( 6933): Toggling radios to true
I/jxcore-log( 6933): 
,D/BluetoothAdapter( 6933): enable(): BT is already enabled..!
D/WifiService( 1036): New client listening to asynchronous messages
D/WifiServiceImplEx( 1036): setWifiEnabled: true pid=6933, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1036): setWifiEnabled: true pid=6933, uid=10311
E/WifiService( 1036): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1036): disconnect pid=6933, uid=10311, packageName=com.test.thalitest
,E/WifiStateMachine( 1036):  ConnectedState CMD_DISCONNECT 0 0
D/WifiServiceImplEx( 1036): reconnect pid=6933, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6933): Radios toggled
I/jxcore-log( 6933): 
I/jxcore-log( 6933): My device name is: LGE-LG-D855
I/jxcore-log( 6933): 
E/WifiStateMachine( 1036):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1036): [110,117,888 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1036): doBoolean: DISCONNECT
,I/wpa_supplicant( 2790): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1036): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiNative-wlan0( 1036): DISCONNECT: returned true
D/Tethering( 1036): InitialState.processMessage what=4
E/WifiMonitor( 1036): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
E/WifiStateMachine( 1036): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1036): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1036): doBoolean: SET_NETWORK 0 bssid any
D/Tethering( 1036): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiNative-wlan0( 1036): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1036): doBoolean: SAVE_CONFIG
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/WifiNative-wlan0( 1036): SAVE_CONFIG: returned true
,D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2790): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 1
D/WifiNative-wlan0( 1036): SET ps 1: returned true
D/DhcpStateMachine( 1036): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  312): Clearing all IP addresses on wlan0
,V/NativeCrypto( 2068): Read error: ssl=0xaa761600: I/O error during system call, Connection timed out
,V/NativeCrypto( 2068): SSL shutdown failed: ssl=0xaa761600: I/O error during system call, Broken pipe
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/ActivityManager( 1036): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7010 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
,V/WfdStateTracker( 1937): handleWifiStateChangedEvent: 0
D/WifiHS20( 1036): hidePasspointNotification off =false
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1036): hidePasspointNotification off =false
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1036): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1036):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1036): [110,291,534 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1036): doBoolean: RECONNECT
,I/wpa_supplicant( 2790): wlan0: CTRL-EVENT-SCAN-STARTED 
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1036): RECONNECT: returned true
E/WifiStateMachine( 1036):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=110302
E/WifiStateMachine( 1036):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=110303
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2790): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 1
D/WifiNative-wlan0( 1036): SET ps 1: returned true
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/ConnectivityService( 1036): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/CommandListener(  312): Clearing all IP addresses on wlan0
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=0
D/ConnectivityService( 1036): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1036): Dns fail occured do internet check.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1036): disableDataServiceNotify
D/DSQN    ( 1036): stop dsqn bin
D/DSQN    ( 1036): EVENT_INTERNET_CHECK_REQUEST received
D/DSQN    ( 1036): try Internet connection check
E/WifiStateMachine( 1036):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/WifiHS20( 1036): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=110341  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=110342  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1036):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=0
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/DSQN    ( 1036): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1036):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1036): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1036): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Disconnected - quitting
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,D/CSLegacyTypeTracker( 1036): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1036): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524292
,D/ConnectivityService( 1036): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/DSQN    ( 1036): ThreadTCPConnectionCheck DNS fail internet is not possible
D/DSQN    ( 1036): ThreadInternetCheck internet check NOK 
D/DSQN    ( 1036): L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
W/ContextImpl( 1036): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
D/LocSvc_java( 1036): Sending msg: 4 arg1:0 arg2:1
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1036): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=110351  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/ConnectivityService( 1036): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
V/NetworkPolicy( 1036): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy( 1036): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1036): Sending msg: 4 arg1:0 arg2:1
D/WifiDataContinuityService( 1036): L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
D/ConnectivityService( 1036): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=110357  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/NetworkManagementService( 1036): Removing idletimer
W/Settings( 1036): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1036): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1036): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyNetworkFactory-1( 1849): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1849):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WifiServiceExtension( 1937): isInternetCheckAvailable return false
D/WIFI    ( 1036): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiHS20( 1036): hidePasspointNotification off =false
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/LocSvc_java( 1036): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1036): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1036): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1036): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1036): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1036): ignore wifi update if we are not in OPENING or CLOSING
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateSCANNING
W/ResourcesManager( 7010): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7010): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,W/ResourcesManager( 7010): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7010): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
W/ResourcesManager( 7010): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7010): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1036): StoppedState
D/DhcpStateMachine( 1036): StoppedState{ when=-108ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 7010): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7010): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7010): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7010): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7010): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7010): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7010): [AUTORUN] onReceive() : availableList=[]
,D/UsbSettingsReceiver( 7010): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7010): [AUTORUN] onReceive() : errorList=[]
,D/UsbSettingsControl( 7010): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7010): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1036): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7044 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1036): Killing 6155:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_10011/pid_6155/cgroup.procs: No such file or directory
,I/PCSuite ( 7044): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7044): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7044): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7010): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7010): LgDataFeature() Constructor: none
D/LgDataFeature( 7010): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7010): MCCMNC not supported: null
I/ActivityManager( 1036): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7068 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1036): Killing 6179:com.android.contacts/u0a19 (adj 15): empty #17
,W/libprocessgroup( 1036): failed to open /acct/uid_10019/pid_6179/cgroup.procs: No such file or directory
,W/ResourcesManager( 7068): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7068): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7068): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7068): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7068): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7068): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7068): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7068): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 7068): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/DSQN    ( 1036): EVENT_INTERNET_CHECK_ENABLE received
,I/art     ( 1036): Explicit concurrent mark sweep GC freed 47868(2MB) AllocSpace objects, 6(608KB) LOS objects, 33% free, 44MB/66MB, paused 3.126ms total 146.316ms
D/QRemote ( 7068): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7068): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7068): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 7068): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
I/PCSuite ( 7044): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7044): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7044): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7010): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/QRemote ( 7068): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,D/WiFiOffLoadBroadcast( 7010): MCCMNC not supported: null
D/QRemote ( 7068): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7068): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7068): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7044): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7044): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7044): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7010): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7010): MCCMNC not supported: null
D/QRemote ( 7068): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7068): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7068): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7044): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7044): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7044): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7010): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7010): MCCMNC not supported: null
D/QRemote ( 7068): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7068): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7068): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7010): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7010): MCCMNC not supported: null
D/QRemote ( 7068): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7068): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7068): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7068): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7068): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7068): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 7068): LgDataFeature() Constructor: none
D/LgDataFeature( 7068): LgDataFeature() Constructor Done, null
,V/SoundPool( 7068): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7068): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7068): create sampleID=1, fd=31, offset=17813 length=10857164
,V/SoundPool( 7068): doLoad: loading sample sampleID=1
I/QRemote ( 7068): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 7068): Start decode
V/MediaPlayer[Native]( 7068): decode(31, 10857164, 17813)
V/MediaPlayerService(  316): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  316): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  316): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  316): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  316): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  316): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  316): player type = 3
V/AwesomePlayer(  316): AwesomePlayer create()
V/AwesomePlayer(  316): reset_l() 
V/AwesomePlayer(  316): cancelPlayerEvents
V/AwesomePlayer(  316): setAudioSink() 
V/AwesomePlayer(  316): reset_l() 
V/AudioCache(  316): notify(0xb14324c0, 8, 0, 0)
V/AudioCache(  316): ignored
V/AwesomePlayer(  316): cancelPlayerEvents
D/Utils   (  316): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  316): setDataSource_l dataSource
V/LGParserOSAL(  316): SniffLGParser start
V/LGParserOSAL(  316): MainType:5, SubType=0
V/LGParserOSAL(  316): #### check Mime : application/ogg
D/QRemote ( 7068): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
V/LGParserOSAL(  316): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  316): Use LGExtractor :application/ogg 
D/UEI.SmartControl( 6762): QS Service created
E/QRemote ( 7068): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7068): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGMDMManager( 7068): Create singleton instance
,I/UEI.SmartControl( 6762): Service initServices...
D/UEI.SmartControl( 6762): QS start get config
V/LGParserOSAL(  316): supported mime: application/ogg
V/AwesomePlayer(  316): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  316): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  316): mBitrate = -1 bits/sec
V/AwesomePlayer(  316): AudioTrack Setting
V/AwesomePlayer(  316): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  316): setAudioSource() 
V/MediaPlayerService(  316): prepare
V/AwesomePlayer(  316): prepareAsync_l() 
V/MediaPlayerService(  316): wait for prepare
V/AwesomePlayer(  316): onPrepareAsyncEvent() 
V/AwesomePlayer(  316): initAudioDecoder() 
W/Utils   (  316): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  316): isOffloadSupported()
V/AudioPolicyManager(  316): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  316): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  316): isAudioPlaybackHookOn() false
V/AwesomePlayer(  316): getUseOffload() = 0 
V/OMXCodec(  316): OMXCodec::Create
V/OMXCodec(  316): findMatchingCodecs()
V/OMXCodec(  316): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  316): matchingCodecs.size()=1
V/OMXCodec(  316): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/OMXCodec(  316): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  316): LG Codec Adapter start
V/OMXCodec(  316): OMXCodec Createtor
V/OMXCodec(  316): setComponentRole
V/OMXCodec(  316): configureCodec protected=0
V/LGCodecAdapter(  316): called getLGCodecSpecificData
V/LGCodecOSAL(  316): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  316): Called LGconfigureCodecMETA
V/LGCodecOSAL(  316): Called LGconfigureCodecMSG
V/LGCodecOSAL(  316): Not support LGCodec
V/OMXCodec(  316): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  316): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  316): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  316): Could not offload audio decode, try pcm offload
W/Utils   (  316): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  316): isOffloadSupported()
V/AudioPolicyManager(  316): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  316): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  316): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  316): init()
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  316): allocateBuffers
V/OMXCodec(  316): allocateBuffersOnPort portIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14341a0 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434470 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14344c0 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434510 on input port
V/OMXCodec(  316): allocateBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14345b0 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14346a0 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14346f0 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434740 on output port
V/OMXCodec(  316): init() mAsyncCompletion wait!!! 
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  316): init() mAsyncCompletion wait!!! 
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  316): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  316): finishAsyncPrepare_l() 
V/AudioCache(  316): notify(0xb14324c0, 5, 0, 0)
V/AudioCache(  316): ignored
V/AudioCache(  316): notify(0xb14324c0, 1, 0, 0)
V/AudioCache(  316): prepared
V/AudioCache(  316): wait - success
V/MediaPlayerService(  316): start
V/AwesomePlayer(  316): play_l() 
V/AwesomePlayer(  316): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  316): createAudioPlayer_l
V/AwesomePlayer(  316): seekAudioIfNecessary_l() 
V/AwesomePlayer(  316): startAudioPlayer_l() 
D/AudioPlayer(  316): start of Playback, useOffload 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  316): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
,V/OMXCodec(  316): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  316): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975984
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976224
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976304
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976384
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  316): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  316): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  316): allocateBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14346f0 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14346a0 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14345b0 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14770b0 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  316): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  316): notify(0xb14324c0, 6, 0, 0)
V/AudioCache(  316): ignored
V/MediaPlayerService(  316): wait for playback complete
D/QRemote ( 7068): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab602000, 0xb57fc000, 4096)
D/QRemote ( 7068): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab603000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab604000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
D/QRemote ( 7068): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6979
V/AudioCache(  316): memcpy(0xab605000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab606000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab607000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab608000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab609000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab60a000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab60b000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab60c000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab60d000, 0xb57fc000, 4096)
,V/AudioCache(  316): write(0xb57fc000, 4096),
V/AudioCache(  316): memcpy(0xab60e000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab60f000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab610000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab611000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab612000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab613000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab614000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab615000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab616000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab617000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab618000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab619000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab61a000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab61b000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab61c000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab61d000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab61e000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab61f000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab620000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab621000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab622000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab623000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab624000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab625000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab626000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab627000, 0xb57fc000, 4096)
,V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab628000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab629000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab62a000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab62b000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab62c000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab62d000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab62e000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab62f000, 0xb57fc000, 4096)
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab630000, 0xb57fc000, 4096)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] No more output data.
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab631000, 0xb57fc000, 4096)
,V/OMXCodec(  316): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AudioCache(  316): write(0xb57fc000, 4096)
V/AudioCache(  316): memcpy(0xab632000, 0xb57fc000, 4096)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AudioCache(  316): write(0xb57fc000, 4096)
,V/AudioCache(  316): memcpy(0xab633000, 0xb57fc000, 4096)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/OMXCodec(  316): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  316): postAudioEOS() 
V/AudioCache(  316): write(0xb57fc000, 280)
V/AudioCache(  316): memcpy(0xab634000, 0xb57fc000, 280)
V/AwesomePlayer(  316): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  316): onStreamDone
V/AwesomePlayer(  316): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  316): notify(0xb14324c0, 2, 0, 0)
V/AudioCache(  316): playback complete
V/AwesomePlayer(  316): pause_l() 
V/AudioCache(  316): notify(0xb14324c0, 7, 0, 0)
V/AudioCache(  316): wait - success
V/AudioCache(  316): ignored
V/AwesomePlayer(  316): cancelPlayerEvents
V/MediaPlayerService(  316): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  316): Pause Playback at 1068125
V/AwesomePlayer(  316): reset_l() 
V/AudioCache(  316): notify(0xb14324c0, 8, 0, 0)
V/AudioCache(  316): ignored
V/AwesomePlayer(  316): cancelPlayerEvents
D/AudioPlayer(  316): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  316): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  316): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434510 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb14344c0 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434470 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb14341a0 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb14770b0 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb14345b0 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb14346a0 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb14346f0 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  316): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  316): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  316): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  316): AudioPlayer releasing audio source
D/AudioPlayer(  316): AudioPlayer done releasing audio source
V/AwesomePlayer(  316): reset_l() 
V/AwesomePlayer(  316): cancelPlayerEvents
V/AwesomePlayer( , 316): ~AwesomePlayer call
V/AwesomePlayer(  316): reset_l() 
V/AwesomePlayer(  316): cancelPlayerEvents
V/SoundPool( 7068): close(31)
V/SoundPool( 7068): pointer = 0x9fffd000, size = 205080, sampleRate = 48000, numChannels = 2
,I/UEI.SmartControl( 6762): Supports setup maps: true,
,D/UEI.SmartControl( 6762): QS start statue = true Error code = 0,
I/UEI.SmartControl( 6762): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6762): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6762): ### init IR Blaster...
D/serial_port( 6762): Configuring serial port
E/UEI.SmartControl( 6762): UEIBLaster setting for 616
,I/UEI.SmartControl( 6762): Setting serial record hearder size = 2
I/UEI.SmartControl( 6762): configuring settings for MAXQ616,
I/UEI.SmartControl( 6762): Get version...
,D/UEI.SmartControl( 6762): serial port data available: 21
,D/UEI.SmartControl( 6762): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6762): IR Blaster version: 256702256704300002
,I/UEI.SmartControl( 6762): QS saving settings...
D/UEI.SmartControl( 6762): IR Blaster version: 25672567
D/UEI.SmartControl( 6762): serial port data available: 4
,I/UEI.SmartControl( 6762): Device manager: loading config....
,D/UEI.SmartControl( 6762): ----------- loading internal config...
W/ContextImpl( 6762): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6762): Services init done
D/UEI.SmartControl( 6762): QS Service init finished
D/UEI.SmartControl( 6762): QS Service version name: 2.1.91
D/UEI.SmartControl( 6762): QS Service version code: 201091
D/UEI.SmartControl( 6762): Service requested: Control
E/UEI.SmartControl( 6762): Loading SETTINGS...
,D/UEI.SmartControl( 6762): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 6762): Internal service binding...
I/QRemote ( 7068): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
D/UEI.SmartControl( 6762): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6762): ------ IControl API: 11
D/UEI.SmartControl( 6762): File observer start...
E/UEI.SmartControl( 6762): IR Port is disabled: false
D/UEI.SmartControl( 6762): Starting file observer...
I/UEI.SmartControl( 6762): Registering callback...
I/UEI.SmartControl( 6762): ------ IControl API: 19
I/UEI.SmartControl( 6762): Registering Services Ready callback...
I/UEI.SmartControl( 6762): Notify client services are ready...
I/UEI.SmartControl( 6762): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6762): -----service ready thread exits
I/QRemote ( 7068): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
I/QRemote ( 7068): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,D/QRemote ( 7068): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7068): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7068): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7068): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6762): ------ IControl API: 8
D/QRemote ( 7068): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7068): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7068): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7068): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7068): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
,D/QRemote ( 7068): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7068): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7068): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7068): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7068): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7068): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7068): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7068): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7068): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7068): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454681730226]
,D/QRemote ( 7068): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1036): Killing 6594:com.lge.email/u0a23 (adj 15): empty #17
D/QRemote ( 7068): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1036): failed to open /acct/uid_10023/pid_6594/cgroup.procs: No such file or directory
,V/QRemote ( 7068): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7068): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7068): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7068): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7068): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7068): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
,D/QRemote ( 7068): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7068): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1036): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1036): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
I/wpa_supplicant( 2790): Trying to associate with SSID 'NG700'
W/WifiMonitor( 1036): couldn't identify event type - WPS-AP-AVAILABLE 
,D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1036):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1036):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1036):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1036):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1036): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=112430  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=112431  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7010): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7010): MCCMNC not supported: null
D/QRemote ( 7068): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7068): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7068): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7010): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7010): MCCMNC not supported: null
,D/QRemote ( 7068): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7068): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7068): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,E/WifiStateMachine( 1036):  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):1 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:50528] from screen [on:0 period:-1312181932]
,V/AlarmManager( 1036): RTC_WAKEUP set : Alarm{3c4a376 type 0 when 1454681728723 android} when 1454681728723
V/AlarmManager( 1036): RTC_WAKEUP set : Alarm{6841de4 type 0 when 1454681731406 com.android.vending} when 1454681731406
,W/ContextImpl( 4552): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1036): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
D/Tethering( 1036): MasterInitialState.processMessage what=3
W/ContextImpl( 6530): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,D/GpsLocationProvider( 1036): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1036): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1036): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1036): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 5566): type=WIFI subType= reason=null isConnected=false
,V/SIM_STK ( 1036): Menu title from STK is T-Mobile
I/NetworkMonitor( 5566): type=WIFI subType= reason=null isConnected=false
,I/ActivityManager( 1036): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7131 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 7131): onCreate
,W/AppUp4:DB( 7131):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7131):  setFingerPrint start
I/AppUp4:DB( 7131):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 7131):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7131):  SDK version = 21
I/AppUp4:DB( 7131):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7131): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7131): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7131): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7131): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7131): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7131): onReceive
,I/wpa_supplicant( 2790): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/Tethering( 1036): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1036):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1036): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=113555  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=113555  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,E/WifiStateMachine( 1036):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=113556
E/WifiStateMachine( 1036):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=113556
E/WifiStateMachine( 1036):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=113556
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=113556
E/WifiStateMachine( 1036):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=113557
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=113557  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=113562  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 2790): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1036): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
I/wpa_supplicant( 2790): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1036): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=113565  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1036): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=113566  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1036):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=113566
E/WifiStateMachine( 1036):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=113566
D/WifiNative-wlan0( 1036): doString: [STATUS]
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1036):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1036): setVHTCapabilityType  : false
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateFOUR_WAY_HANDSHAKE
,I/WifiServerServiceExt( 1036): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1036): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1036): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1036): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1036): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1036): Got NetworkAgent Messenger
D/WifiNative-wlan0( 1036): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1036): doBoolean: SAVE_CONFIG
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1036): NetworkAgent connected
D/LgDataFeature( 7131): LgDataFeature() Constructor: none
D/LgDataFeature( 7131): LgDataFeature() Constructor Done, null
D/WifiNative-wlan0( 1036): SAVE_CONFIG: returned true
E/WifiConfigStore( 1036): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1036): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1036): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1036): doBoolean: SAVE_CONFIG
,D/AppUp4:CustFacade( 7131): Context : android.app.ReceiverRestrictedContext@1f618bb5
D/AppUp4:CustFacade( 7131): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7131): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7131): begin check event
I/AppUp4:CustModeStarterReceiver( 7131): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7131): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7131): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7131): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7131): handleAsyncCustNotification do not startCustService
D/LGDMClient( 4365): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4365): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4365): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/WifiNative-wlan0( 1036): SAVE_CONFIG: returned true
D/CommandListener(  312): Setting iface cfg
W/ContextImpl( 4365): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
E/WifiStateMachine( 1036): Start Dhcp Watchdog 2
,E/WifiStateMachine( 1036):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=113603  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/DhcpStateMachine( 1036): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1036): WaitBeforeStartState
E/WifiStateMachine( 1036):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=113604  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=113605  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1036):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=113606  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1036):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=113607  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=113607  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/LGDMClient( 4365): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
E/WifiStateMachine( 1036):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/LGDMClient( 4365): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4365): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1036): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1036):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1036): doBoolean: DRIVER SETSUSPENDMODE 0
,I/ActivityManager( 1036): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7155 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/wpa_supplicant( 2790): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1036): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 0
D/WifiNative-wlan0( 1036): SET ps 0: returned true
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2790): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1036): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1036): Current State is mWaitBeforeStartState.
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@102314f9 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1036): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@102314f9 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1036): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1036): DHCP Start wake lock is acquired.
D/CommandListener(  312): Setting iface cfg
D/CommandListener(  312): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1036): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1036):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1036):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2790): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1036): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2790): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1036): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 1
D/WifiNative-wlan0( 1036): SET ps 1: returned true
D/ConnectivityService( 1036): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1036):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1036): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1036):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1036): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1036): ignoring duplicate network state non-change
,W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1036): Adding iface wlan0 to network 101
E/WifiStateMachine( 1036): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1036): [PASSPOINT] passpointNotification: hs20AP list is checked
,I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/WfdStateTracker( 1937): handleWifiStateChangedEvent: 1
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1036): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ConnectivityService( 1036): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1036): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1036): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  312): netlink response contains error (File exists)
,D/ConnectivityService( 1036): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1036): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1036): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1036): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1036): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1036): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1036):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Connected
D/ConnectivityService( 1036):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1036):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1036):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
,D/ConnectivityService( 1036): currentScore = 0, newScore = 20
D/ConnectivityService( 1036):    accepting network in place of null
D/ConnectivityService( 1036): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1849): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1849):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1036): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/libc-netbsd(  312): res_queryN name = clients3.google.com, class = 1, type = 28
E/ConnectivityService( 1036): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1036): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1036): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1036): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1036): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService( 1036): validation of new default Network = false
D/ConnectivityService( 1036): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1036): enableDataServiceNotify 
D/DSQN    ( 1036): start dsqn bin
D/LocSvc_java( 1036): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1036): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1036): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1036): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1036): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524290
W/dsqn    ( 7176): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7176): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/ResourcesManager( 7155): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7155): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7155): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7155): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
V/NetworkPolicy( 1036): [LG_RESTRICTED] checkMobilePolicy_type()
E/DSQN    ( 7176): DSQN ssw
I/GLSUser ( 2068): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2068): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2068): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2068): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/Finsky  ( 6275): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6275): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6275): [1] 5.onFinished: Scheduling replication attempt 2.
,D/libc-netbsd(  312): res_queryN name = clients3.google.com, class = 1, type = 1
I/ActivityManager( 1036): Killing 6201:com.android.gallery3d/u0a27 (adj 15): empty #17
,D/libc-netbsd(  312): res_queryN name = clients3.google.com succeed
,D/LGDataListener(  312): argv[0]=dsqncommand
D/LGDataListener(  312): argv[1]=wlan0
D/LGDataListener(  312): argv[2]=1
D/LGDataListener(  312): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1036): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1036): start to monitor internet connection
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 05 Feb 2016 14:15:32 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454681732022], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454681731999]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Validated
D/ConnectivityService( 1036): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1036):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1036): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1036): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1036): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory-1( 1849): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524290
,D/TelephonyNetworkFactory-1( 1849):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,W/libprocessgroup( 1036): failed to open /acct/uid_10027/pid_6201/cgroup.procs: No such file or directory
I/LGEmail ( 7155): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/DhcpStateMachine( 1036): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1036): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1036): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7182): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7182): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
I/dhcpcd  ( 7182): version 5.5.6 starting
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
E/dhcpcd  ( 7182): get_duid: m
D/dhcpcd  ( 7182): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7182): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/LGEmail ( 7155): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/ResourceType( 7155): No package identifier when getting value for resource number 0x00000000
,D/dhcpcd  ( 7182): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7182): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7182): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7182): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7182): wlan0: sending REQUEST (xid 0xf244543f), next in 4.35 seconds
D/LgDataFeature( 7155): LgDataFeature() Constructor: none
D/LgDataFeature( 7155): LgDataFeature() Constructor Done, null
,D/eas_req ( 7155): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1036): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7197 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7155): JNI_OnLoad()
I/HubEmail( 7155): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7155): registerNatives()
I/HubEmail( 7155): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7155): registerNativeMethods()
I/HubEmail( 7155): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7155): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1036): Killing 6625:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/Settings( 7155): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/libprocessgroup( 1036): failed to open /acct/uid_10061/pid_6625/cgroup.procs: No such file or directory
W/Settings( 7155): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3399): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3399): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3399): networkInfo.isConnected() = false
,I/ActivityManager( 1036): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7225 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  312): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/ActivityManager( 1036): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7246 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1036): Killing 6670:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_10080/pid_6670/cgroup.procs: No such file or directory
,I/jxcore-log( 6933): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6933): 
,D/libc-netbsd(  312): res_queryN name = static-avc.lglime.com succeed
,I/ActivityManager( 1036): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7266 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1036): Killing 6737:com.lge.eula/1000 (adj 15): empty #17
V/FormManager( 7197): There are no updated forms. The schedule will be deleted.
,I/art     (  339): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 441us total 32.616ms
I/art     (  339): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 425us total 19.549ms
,V/FormManager( 7197): Alarm would be updated, because LastCheckTime has been updated.
I/art     (  339): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 428us total 22.105ms
,W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_6737/cgroup.procs: No such file or directory
I/ActivityManager( 1036): Killing 6695:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,I/art     ( 7266): Almond Protected OAT
,W/libprocessgroup( 1036): failed to open /acct/uid_10097/pid_6695/cgroup.procs: No such file or directory
,D/WeatherApplication( 7266): removeAccount
I/dhcpcd  ( 7182): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
D/WeatherApplication( 7266): Account.length = 0
E/WeatherApplication( 7266): OPERATOR:OPEN
D/WeatherAncestor( 7266): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:15:33
,D/Weather.Utils( 7266): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7266): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7266): 2 : This is isUpdating : false
D/WeatherAncestor( 7266): connectivity changed - connection : true
D/WeatherService( 7266): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 7266): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7266): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7266): 2 : Cache is not up-to-date, count: 0
I/dhcpcd  ( 7182): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7182): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7182): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7182): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7182): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7182): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7182): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7182): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,D/Weather_cast( 7266): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7266): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:15:33
,W/ProcessCpuTracker( 1036): Skipping unknown process pid 7296
,I/ActivityManager( 1036): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7298 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1036): Killing 6090:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_10005/pid_6090/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1036):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 1036):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7298): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7298): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/jxcore-log( 6933): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6933): 
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7298): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7298): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/jxcore-log( 6933): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6933): 
,I/jxcore-log( 6933): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 6933): 
I/jxcore-log( 6933): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6933): 
D/DhcpStateMachine( 1036): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1036): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1036): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1036): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1036): Don't need to update mDhcpResultsCacheList
,V/DhcpStateMachine( 1036): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1036): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1036): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1036): RunningState
I/WebViewFactory( 7298): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7298): Loading: webviewchromium
I/LibraryLoader( 7298): Time to load native libraries: 3 ms (timestamps 5564-5567)
I/LibraryLoader( 7298): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7298): Binding Chromium to main looper Looper (main, tid 1) {3c8b5eb4}
,I/LibraryLoader( 7298): Expected native library version number "",actual native library version number ""
I/chromium( 7298): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7298): Initializing chromium process, renderers=0
,W/art     ( 7298): Attempt to remove local handle scope entry from IRT, ignoring
E/WifiStateMachine( 1036):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1036): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1036): identical MTU - not setting
D/Nat464Xlat( 1036): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1036): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524295
W/chromium( 7298): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7298): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7298): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  316): registerClient() client 0xb1472160, uid 10093
W/AudioManagerAndroid( 7298): Requires BLUETOOTH permission
I/Adreno-EGL( 7298): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7298): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7298): Build Date: 12/12/14 금
I/Adreno-EGL( 7298): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7298): Remote Branch: 
I/Adreno-EGL( 7298): Local Patches: 
I/Adreno-EGL( 7298): Reconstruct Branch: 
,I/NSApplication( 7298): Starting up...
,I/ActivityManager( 1036): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7367 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1036): Killing 6784:com.lge.bnr/1000 (adj 15): empty #17
,I/CloudHub( 2181): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19966
,W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_6784/cgroup.procs: No such file or directory
,W/ResourcesManager( 7367): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 116035464386; DSPS: 3943682; Offset : -4329061310
D/ChimeraCfgMgr( 2313): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2313): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6530): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7131): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7131): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7131): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7131): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7131): onReceive
,D/AppUp4:CustFacade( 7131): Context : android.app.ReceiverRestrictedContext@1f618bb5
D/AppUp4:CustFacade( 7131): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7131): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7131): begin check event
I/AppUp4:CustModeStarterReceiver( 7131): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4365): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4365): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4365): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4365): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,I/GLSActivity( 2068): [ac] getting account id
V/DownloadManager( 3479): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4365): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4365): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3479): DownloadService onCreate
I/DownloadManager( 3479): in removeSpuriousFiles
D/LGDMClient( 4365): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4365): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3479): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3479): created cursor android.database.sqlite.SQLiteCursor@324c5949 on behalf of 3479
I/DownloadManager( 3479): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3479): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3479): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3479): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3479): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3479): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3479): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3479): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3479): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3479): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3479): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
,V/DownloadManager( 3479): DownloadService onStartCommand
V/DownloadManager( 3479): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/GLSUser ( 2068): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2068): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2068): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2068): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/ContextImpl( 4365): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,I/DownloadManager( 3479): in trimDatabase
V/DownloadManager( 3479): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3479): created cursor android.database.sqlite.SQLiteCursor@2135e47c on behalf of 3479
I/GLSUser ( 2068): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/LGDMClient( 4365): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4365): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4365): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3479): created cursor android.database.sqlite.SQLiteCursor@3784105 on behalf of 3479
W/Settings( 7155): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7155): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3479): processing inserted download 1
,V/DownloadManager( 3479): processing inserted download 4
V/DownloadManager( 3479): processing inserted download 7
V/DownloadManager( 3479): processing inserted download 8
V/DownloadManager( 3479): processing inserted download 9
I/LgeMiscReceiver( 3399): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3399): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3399): networkInfo.isConnected() = false
V/DownloadManager( 3479): processing inserted download 10
V/DownloadManager( 3479): processing inserted download 16
V/DownloadManager( 3479): processing inserted download 17
,V/DownloadManager( 3479): processing inserted download 18
V/DownloadManager( 3479): processing inserted download 21
V/DownloadManager( 3479): processing inserted download 22
D/WeatherAncestor( 7266): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:15:34
,V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2313): [AccountUtils] Account not ready
W/Kids    ( 2313): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2313): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2313): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2313): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2313): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2313): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2313): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2313): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2313): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2313): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2313): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2313): 	at java.lang.Thread.run(Thread.java:818)
D/Weather.Utils( 7266): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7266): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7266): 2 : This is isUpdating : false
D/WeatherAncestor( 7266): connectivity changed - connection : true
D/WeatherService( 7266): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@337345bb
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/ForecastDataCache( 7266): 2 : lastUpdatedTime: 1430558561343
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/ForecastDataCache( 7266): 2 : currentPackageVersion: 4.40.4
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/ForecastDataCache( 7266): 2 : Cache is up-to-date, count: 0
D/LgeQuickCoverNotificationData( 1419): showAll3
D/Weather_cast( 7266): 2 : isUpdateNeedForAlarm : no city return false
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/WeatherAncestor( 7266): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:15:34
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
,V/DownloadManager( 3479): DownloadService onDestroy
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2c928bbd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ChimeraCfgMgr( 2313): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/FormManager( 7197): There are no updated forms. The schedule will be deleted.
,D/UsbSettingsReceiver( 7010): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7010): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7010): [AUTORUN] sys.usb.state = ptp_only,adb
,D/UsbSettingsReceiver( 7010): [AUTORUN] persist.sys.usb.config = ptp_only,adb
V/FormManager( 7197): Alarm would be updated, because LastCheckTime has been updated.
D/UsbSettingsReceiver( 7010): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7010): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 7010): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7010): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7010): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7010): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7010): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7010): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7010): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/GLSUser ( 2068): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2068): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2068): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2068): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WiFiOffLoadBroadcast( 7010): MCCMNC not supported: null
D/QRemote ( 7068): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7068): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7068): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1419): onNotificationPosted
W/Kids    ( 2313): [AccountUtils] Account not ready
W/Kids    ( 2313): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2313): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2313): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2313): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2313): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2313): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2313): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2313): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2313): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2313): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2313): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2313): 	at java.lang.Thread.run(Thread.java:818)
I/art     ( 1036): Explicit concurrent mark sweep GC freed 63846(2MB) AllocSpace objects, 2(160KB) LOS objects, 33% free, 44MB/66MB, paused 1.921ms total 96.335ms
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
V/WiFiOffLoadBroadcast( 7010): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
,E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
D/WiFiOffLoadBroadcast( 7010): MCCMNC not supported: null
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2c928bbd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/QRemote ( 7068): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7068): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7068): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7010): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7010): MCCMNC not supported: null
D/QRemote ( 7068): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7068): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7068): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7010): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7010): MCCMNC not supported: null
D/QRemote ( 7068): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7068): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7068): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WifiInternetCheck( 1036): Single check msg out of sync, ignoring.
V/WiFiOffLoadBroadcast( 7010): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7010): MCCMNC not supported: null
D/QRemote ( 7068): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7068): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7068): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
V/WiFiOffLoadBroadcast( 7010): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/Tethering( 1036): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 5566): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1036): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1036): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WiFiOffLoadBroadcast( 7010): MCCMNC not supported: null
D/QRemote ( 7068): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7068): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7068): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7044): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7044): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7010): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7010): MCCMNC not supported: null
D/QRemote ( 7068): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7068): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7068): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 7068): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7068): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7044): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7044): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7010): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7010): MCCMNC not supported: null
D/QRemote ( 7068): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7068): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7068): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7068): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7068): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6530): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 7131): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7131): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 7131): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 7131): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7131): onReceive
D/AppUp4:CustFacade( 7131): Context : android.app.ReceiverRestrictedContext@1f618bb5
D/AppUp4:CustFacade( 7131): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7131): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7131): begin check event
I/AppUp4:CustModeStarterReceiver( 7131): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4365): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4365): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4365): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4365): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3479): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4365): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4365): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4365): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3479): DownloadService onCreate
I/LGDMClient( 4365): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3479): in removeSpuriousFiles
,V/DownloadManager( 3479): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3479): created cursor android.database.sqlite.SQLiteCursor@675c38b on behalf of 3479
I/DownloadManager( 3479): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3479): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3479): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3479): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3479): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3479): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3479): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3479): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3479): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
W/ContextImpl( 4365): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/DownloadManager( 3479): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3479): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3479): in trimDatabase
V/DownloadManager( 3479): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
E/LGDMClient( 4365): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4365): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4365): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
W/Settings( 7155): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 3479): created cursor android.database.sqlite.SQLiteCursor@25c0e881 on behalf of 3479
V/DownloadManager( 3479): DownloadService onStartCommand
I/LgeMiscReceiver( 3399): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3399): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3399): networkInfo.isConnected() = true
,D/PhoneState( 3399): setPdpRejectCasuse : false
V/DownloadManager( 3479): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/Settings( 7155): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3479): created cursor android.database.sqlite.SQLiteCursor@3f7b0d67 on behalf of 3479
,V/DownloadManager( 3479): processing inserted download 1
V/DownloadManager( 3479): processing inserted download 4
V/DownloadManager( 3479): processing inserted download 7
D/WeatherAncestor( 7266): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:15:35
V/DownloadManager( 3479): processing inserted download 8
D/Weather.Utils( 7266): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7266): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7266): 2 : This is isUpdating : false
D/WeatherAncestor( 7266): connectivity changed - connection : true
D/WeatherService( 7266): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@337345bb
V/DownloadManager( 3479): processing inserted download 9
V/DownloadManager( 3479): processing inserted download 10
D/ForecastDataCache( 7266): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7266): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7266): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7266): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7266): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:15:35
,V/DownloadManager( 3479): processing inserted download 16
V/DownloadManager( 3479): processing inserted download 17
V/DownloadManager( 3479): processing inserted download 18
V/DownloadManager( 3479): processing inserted download 21
V/DownloadManager( 3479): processing inserted download 22
V/DownloadManager( 3479): DownloadService onDestroy
,D/ChimeraCfgMgr( 2313): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 2068): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2068): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2068): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2068): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/FormManager( 7197): There are no updated forms. The schedule will be deleted.
,V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/FormManager( 7197): Alarm would be updated, because LastCheckTime has been updated.
D/UEI.SmartControl( 6762): Internal timer expired: 4
D/UEI.SmartControl( 6762): unbind internal service
,V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2313): [AccountUtils] Account not ready
W/Kids    ( 2313): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2313): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2313): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2313): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2313): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2313): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2313): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2313): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2313): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2313): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2313): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2313): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
D/serial_port( 6762): close(fd = 24)
I/UEI.SmartControl( 6762): Serial port is closed.
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2c928bbd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{2fb2c0ce type 2 when 117288 com.google.android.gms} when 117288
,V/QRemote ( 7068): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7068): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:6979
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  312): res_queryN name = mtalk.google.com, class = 1, type = 1
D/libc-netbsd(  312): res_queryN name = mtalk.google.com succeed
,D/GCM     ( 2068): Connected
,D/GCM     ( 2068): Message class com.google.f.a.a.p
,D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  312): res_queryN name = www.google.com, class = 1, type = 1
,D/libc-netbsd(  312): res_queryN name = www.google.com succeed
,D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  312): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  312): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1036): isHttpConnectionAvailable - We got a valid response : 204
,I/GAV4    ( 7298): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 6933): Test app app.js loaded
I/jxcore-log( 6933): 
,I/chromium( 6933): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/ActivityManager( 1036): Killing 6124:com.android.providers.calendar/u0a14 (adj 15): empty #17
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6933): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6933): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6933): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6933): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6933): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6933): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6933): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6933): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6933): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6933): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32a7d876 added. We now have 1 listener(s)
I/jxcore-log( 6933): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6933): 
W/libprocessgroup( 1036): failed to open /acct/uid_10014/pid_6124/cgroup.procs: No such file or directory
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{37be1bda type 2 when 131338 android} when 131338
,I/CloudHub( 2181): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,I/CloudHub( 2181): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 136037103701; DSPS: 4599096; Offset : -4329070153
,V/AlarmManager( 1036): RTC_WAKEUP set : Alarm{218aa6e8 type 0 when 1454681751951 com.android.vending} when 1454681751951
,V/SIM_STK ( 1036): Menu title from STK is T-Mobile
,V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2068): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2068): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2068): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2068): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6275): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6275): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6275): [1] 5.onFinished: Scheduling replication attempt 3.
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
E/WifiStateMachine( 1036):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1036):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1036):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 156038879788; DSPS: 5254514; Offset : -4329064110
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=778865943, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,V/AlarmManager( 1036): RTC_WAKEUP set : Alarm{3fad79fb type 0 when 1454681778052 com.android.vending} when 1454681778052
,D/[Concierge]Service( 2597): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=778865943 [*alarm*], flags=0x0
,V/SIM_STK ( 1036): Menu title from STK is T-Mobile
,V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2068): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2068): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2068): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2068): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6275): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6275): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6275): [1] 5.onFinished: Scheduling replication attempt 4.
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{a46665 type 2 when 170576 android} when 170576
,I/BooksSync( 6846): Starting books sync
,D/BooksSync( 6846): started syncMyEbooks
,V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2068): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2068): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2068): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2068): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2068): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2068): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2068): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2068): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2068): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2068): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2068): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6846): Authentication error
E/BooksAccountManager( 6846): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6846): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6846): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6846): null auth token
W/ResourcesManager( 1419): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1419): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LgeQuickCoverNLService( 1419): onNotificationPosted
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
W/ResourcesManager( 1419): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1419): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2c928bbd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  312): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  312): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6846): Error response from books API: {
W/ApiaryClient( 6846):  "error": {
W/ApiaryClient( 6846):   "errors": [
W/ApiaryClient( 6846):    {
W/ApiaryClient( 6846):     "domain": "global",
W/ApiaryClient( 6846):     "reason": "required",
W/ApiaryClient( 6846):     "message": "Login Required",
W/ApiaryClient( 6846):     "locationType": "header",
W/ApiaryClient( 6846):     "location": "Authorization"
W/ApiaryClient( 6846):    }
W/ApiaryClient( 6846):   ],
W/ApiaryClient( 6846):   "code": 401,
W/ApiaryClient( 6846):   "message": "Login Required"
W/ApiaryClient( 6846):  }
W/ApiaryClient( 6846): }
,W/ApiaryClient( 6846): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6846): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3194491835113286052&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6846): Headers:
W/ApiaryClient( 6846): accept-encoding: [gzip]
W/ApiaryClient( 6846): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6846): gdata-version: 2
,V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2068): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2068): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2068): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2068): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2068): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2068): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2068): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2068): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2068): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2068): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2068): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6846): Authentication error
E/BooksAccountManager( 6846): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6846): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6846): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6846): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2c928bbd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6846): Error response from books API: {
W/ApiaryClient( 6846):  "error": {
W/ApiaryClient( 6846):   "errors": [
W/ApiaryClient( 6846):    {
W/ApiaryClient( 6846):     "domain": "global",
W/ApiaryClient( 6846):     "reason": "required",
W/ApiaryClient( 6846):     "message": "Login Required",
W/ApiaryClient( 6846):     "locationType": "header",
W/ApiaryClient( 6846):     "location": "Authorization"
W/ApiaryClient( 6846):    }
W/ApiaryClient( 6846):   ],
W/ApiaryClient( 6846):   "code": 401,
W/ApiaryClient( 6846):   "message": "Login Required"
W/ApiaryClient( 6846):  }
W/ApiaryClient( 6846): }
,W/ApiaryClient( 6846): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6846): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3194491835113286052&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6846): Headers:
W/ApiaryClient( 6846): accept-encoding: [gzip]
W/ApiaryClient( 6846): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6846): gdata-version: 2
,V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2068): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2068): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2068): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2068): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2068): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2068): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2068): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2068): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2068): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2068): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2068): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6846): Authentication error
E/BooksAccountManager( 6846): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6846): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6846): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6846): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2c928bbd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6846): Error response from books API: {
W/ApiaryClient( 6846):  "error": {
W/ApiaryClient( 6846):   "errors": [
W/ApiaryClient( 6846):    {
W/ApiaryClient( 6846):     "domain": "global",
W/ApiaryClient( 6846):     "reason": "required",
W/ApiaryClient( 6846):     "message": "Login Required",
W/ApiaryClient( 6846):     "locationType": "header",
W/ApiaryClient( 6846):     "location": "Authorization"
W/ApiaryClient( 6846):    }
W/ApiaryClient( 6846):   ],
W/ApiaryClient( 6846):   "code": 401,
W/ApiaryClient( 6846):   "message": "Login Required"
W/ApiaryClient( 6846):  }
W/ApiaryClient( 6846): }
,W/ApiaryClient( 6846): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6846): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3194491835113286052&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6846): Headers:
W/ApiaryClient( 6846): accept-encoding: [gzip]
W/ApiaryClient( 6846): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6846): gdata-version: 2
,E/BooksSync( 6846): Soft error: 
E/BooksSync( 6846): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6846): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3194491835113286052&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6846): Headers:
E/BooksSync( 6846): accept-encoding: [gzip]
E/BooksSync( 6846): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6846): gdata-version: 2
E/BooksSync( 6846): 
E/BooksSync( 6846): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6846): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6846): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6846): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6846): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6846): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6846): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6846): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6846): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6846): {
E/BooksSync( 6846):  "error": {
E/BooksSync( 6846):   "errors": [
E/BooksSync( 6846):    {
E/BooksSync( 6846):     "domain": "global",
E/BooksSync( 6846):     "reason": "required",
E/BooksSync( 6846):     "message": "Login Required",
E/BooksSync( 6846):     "locationType": "header",
E/BooksSync( 6846):     "location": "Authorization"
E/BooksSync( 6846):    }
E/BooksSync( 6846):   ],
E/BooksSync( 6846):   "code": 401,
E/BooksSync( 6846):   "message": "Login Required"
E/BooksSync( 6846):  }
E/BooksSync( 6846): }
E/BooksSync( 6846): 
E/BooksSync( 6846): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6846): 	... 8 more
,E/BooksSync( 6846): Sync error
E/BooksSync( 6846): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6846): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3194491835113286052&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6846): Headers:
E/BooksSync( 6846): accept-encoding: [gzip]
E/BooksSync( 6846): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6846): gdata-version: 2
E/BooksSync( 6846): 
E/BooksSync( 6846): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6846): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6846): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6846): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6846): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6846): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6846): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6846): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6846): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6846): {
E/BooksSync( 6846):  "error": {
E/BooksSync( 6846):   "errors": [
E/BooksSync( 6846):    {
E/BooksSync( 6846):     "domain": "global",
E/BooksSync( 6846):     "reason": "required",
E/BooksSync( 6846):     "message": "Login Required",
E/BooksSync( 6846):     "locationType": "header",
E/BooksSync( 6846):     "location": "Authorization"
E/BooksSync( 6846):    }
E/BooksSync( 6846):   ],
E/BooksSync( 6846):   "code": 401,
E/BooksSync( 6846):   "message": "Login Required"
E/BooksSync( 6846):  }
E/BooksSync( 6846): }
E/BooksSync( 6846): 
E/BooksSync( 6846): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6846): 	... 8 more
I/BooksSync( 6846): Finished books sync
D/SyncManager( 1036): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 170576, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 176041422749; DSPS: 5909958; Offset : -4329084444
,V/AlarmManager( 1036): RTC_WAKEUP set : Alarm{113aaa54 type 0 when 1454681801376 com.android.vending} when 1454681801376
,V/SIM_STK ( 1036): Menu title from STK is T-Mobile
,V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2068): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2068): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2068): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2068): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6275): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6275): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6275): [1] 5.onFinished: Scheduling replication attempt 5.
I/[SystemUI]LGPowerUI( 1472): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1472): On Skip Timer : true
,D/WifiController( 1036): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1472): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/[SystemUI]LGPowerUI( 1472): onReceive = android.intent.action.BATTERY_CHANGED
,D/LEDHandler( 1937): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1937): Battery Level Remaining: 100%
D/LEDHandler( 1937): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1472): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3892): Disconnected process message: 10, size: 0
,D/LGDMClient( 4365): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
,D/LGDMClient( 4365): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 196042985814; DSPS: 6565369; Offset : -4329077828
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{2971ad16 type 2 when 200622 android} when 200622
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=778865943, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,V/AlarmManager( 1036): RTC_WAKEUP set : Alarm{29875084 type 0 when 1454681821706 com.android.vending} when 1454681821706
,D/[Concierge]Service( 2597): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=778865943 [*alarm*], flags=0x0
,V/SIM_STK ( 1036): Menu title from STK is T-Mobile
,V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2068): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2068): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2068): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2068): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6275): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6275): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6275): [1] 5.onFinished: Giving up after 6 failures.
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 216044610703; DSPS: 7220782; Offset : -4329070397
,V/AlarmManager( 1036): RTC_WAKEUP set : Alarm{3ccd87c6 type 0 when 1454681793441 com.google.android.gms} when 1454681793441
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{c055387 type 2 when 185897 com.google.android.gms} when 185897
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{1f21e2b4 type 2 when 210858 android} when 210858
,I/art     ( 1036): Explicit concurrent mark sweep GC freed 33819(1461KB) AllocSpace objects, 6(736KB) LOS objects, 33% free, 44MB/66MB, paused 2.930ms total 173.351ms
,V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/EventLogService( 2313): Aggregate from 1454679993357 (log), 1454679993357 (data)
,I/VacuumService( 2068): Vacuum at: now=1454681844844 tag=VacuumService
,I/GoogleURLConnFactory( 2068): Using platform SSLCertificateSocketFactory
,W/Uploader( 2068): No account for auth token provided
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  312): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  312): res_queryN name = play.googleapis.com succeed
,W/Uploader( 2068): No account for auth token provided
,W/Uploader( 2068): No account for auth token provided
,W/Uploader( 2068): No account for auth token provided
,W/Uploader( 2068):  no longer exists, so no auth token.
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{19042c77 type 2 when 230652 android} when 230652
,I/BooksSync( 6846): Starting books sync
,D/BooksSync( 6846): started syncMyEbooks
,V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2068): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2068): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2068): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2068): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2068): Explicit concurrent mark sweep GC freed 45308(2MB) AllocSpace objects, 17(2MB) LOS objects, 51% free, 30MB/62MB, paused 1.915ms total 61.392ms
,V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2068): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2068): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2068): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2068): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2068): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2068): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2068): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6846): Authentication error
E/BooksAccountManager( 6846): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6846): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6846): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6846): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2c928bbd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6846): Error response from books API: {
W/ApiaryClient( 6846):  "error": {
W/ApiaryClient( 6846):   "errors": [
W/ApiaryClient( 6846):    {
W/ApiaryClient( 6846):     "domain": "global",
W/ApiaryClient( 6846):     "reason": "required",
W/ApiaryClient( 6846):     "message": "Login Required",
W/ApiaryClient( 6846):     "locationType": "header",
W/ApiaryClient( 6846):     "location": "Authorization"
W/ApiaryClient( 6846):    }
W/ApiaryClient( 6846):   ],
W/ApiaryClient( 6846):   "code": 401,
W/ApiaryClient( 6846):   "message": "Login Required"
W/ApiaryClient( 6846):  }
W/ApiaryClient( 6846): }
,W/ApiaryClient( 6846): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6846): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1653665970440839148&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6846): Headers:
W/ApiaryClient( 6846): accept-encoding: [gzip]
W/ApiaryClient( 6846): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6846): gdata-version: 2
,V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2068): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2068): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2068): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2068): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2068): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2068): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2068): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2068): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2068): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2068): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2068): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6846): Authentication error
E/BooksAccountManager( 6846): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6846): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6846): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6846): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2c928bbd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6846): Error response from books API: {
W/ApiaryClient( 6846):  "error": {
W/ApiaryClient( 6846):   "errors": [
W/ApiaryClient( 6846):    {
W/ApiaryClient( 6846):     "domain": "global",
W/ApiaryClient( 6846):     "reason": "required",
W/ApiaryClient( 6846):     "message": "Login Required",
W/ApiaryClient( 6846):     "locationType": "header",
W/ApiaryClient( 6846):     "location": "Authorization"
W/ApiaryClient( 6846):    }
W/ApiaryClient( 6846):   ],
W/ApiaryClient( 6846):   "code": 401,
W/ApiaryClient( 6846):   "message": "Login Required"
W/ApiaryClient( 6846):  }
W/ApiaryClient( 6846): }
,W/ApiaryClient( 6846): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6846): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1653665970440839148&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6846): Headers:
W/ApiaryClient( 6846): accept-encoding: [gzip]
W/ApiaryClient( 6846): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6846): gdata-version: 2
V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2068): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2068): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2068): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2068): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2068): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2068): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2068): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2068): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2068): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2068): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2068): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6846): Authentication error
E/BooksAccountManager( 6846): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6846): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6846): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6846): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2c928bbd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6846): Error response from books API: {
W/ApiaryClient( 6846):  "error": {
W/ApiaryClient( 6846):   "errors": [
W/ApiaryClient( 6846):    {
W/ApiaryClient( 6846):     "domain": "global",
W/ApiaryClient( 6846):     "reason": "required",
W/ApiaryClient( 6846):     "message": "Login Required",
W/ApiaryClient( 6846):     "locationType": "header",
W/ApiaryClient( 6846):     "location": "Authorization"
W/ApiaryClient( 6846):    }
W/ApiaryClient( 6846):   ],
W/ApiaryClient( 6846):   "code": 401,
W/ApiaryClient( 6846):   "message": "Login Required"
W/ApiaryClient( 6846):  }
W/ApiaryClient( 6846): }
,W/ApiaryClient( 6846): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6846): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1653665970440839148&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6846): Headers:
W/ApiaryClient( 6846): accept-encoding: [gzip]
W/ApiaryClient( 6846): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6846): gdata-version: 2
,E/BooksSync( 6846): Soft error: 
E/BooksSync( 6846): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6846): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1653665970440839148&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6846): Headers:
E/BooksSync( 6846): accept-encoding: [gzip]
E/BooksSync( 6846): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6846): gdata-version: 2
E/BooksSync( 6846): 
E/BooksSync( 6846): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6846): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6846): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6846): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6846): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6846): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6846): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6846): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6846): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6846): {
E/BooksSync( 6846):  "error": {
E/BooksSync( 6846):   "errors": [
E/BooksSync( 6846):    {
E/BooksSync( 6846):     "domain": "global",
E/BooksSync( 6846):     "reason": "required",,
E/BooksSync( 6846):     "message": "Login Required",
E/BooksSync( 6846):     "locationType": "header",
E/BooksSync( 6846):     "location": "Authorization"
E/BooksSync( 6846):    }
E/BooksSync( 6846):   ],
E/BooksSync( 6846):   "code": 401,
E/BooksSync( 6846):   "message": "Login Required"
E/BooksSync( 6846):  }
E/BooksSync( 6846): }
E/BooksSync( 6846): 
E/BooksSync( 6846): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6846): 	... 8 more
,E/BooksSync( 6846): Sync error
E/BooksSync( 6846): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6846): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1653665970440839148&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6846): Headers:
E/BooksSync( 6846): accept-encoding: [gzip]
E/BooksSync( 6846): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6846): gdata-version: 2
E/BooksSync( 6846): 
E/BooksSync( 6846): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6846): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6846): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6846): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6846): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6846): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6846): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6846): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6846): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6846): {
E/BooksSync( 6846):  "error": {
E/BooksSync( 6846):   "errors": [
E/BooksSync( 6846):    {
E/BooksSync( 6846):     "domain": "global",
E/BooksSync( 6846):     "reason": "required",
E/BooksSync( 6846):     "message": "Login Required",
E/BooksSync( 6846):     "locationType": "header",
E/BooksSync( 6846):     "location": "Authorization"
E/BooksSync( 6846):    }
E/BooksSync( 6846):   ],
E/BooksSync( 6846):   "code": 401,
E/BooksSync( 6846):   "message": "Login Required"
E/BooksSync( 6846):  }
E/BooksSync( 6846): }
E/BooksSync( 6846): 
E/BooksSync( 6846): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6846): 	... 8 more
I/BooksSync( 6846): Finished books sync
D/SyncManager( 1036): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 205485, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 236046466840; DSPS: 7876203; Offset : -4329075805
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 256048373707; DSPS: 8531625; Offset : -4329061055
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{2748a429 type 2 when 260724 android} when 260724
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 276049942450; DSPS: 9187037; Offset : -4329079147
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 296052429057; DSPS: 9842478; Offset : -4329064490
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=778865943, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{3ca893ae type 2 when 296417 android} when 296417
D/[Concierge]Service( 2597): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=778865943 [*alarm*], flags=0x0
,I/BooksSync( 6846): Starting books sync
,D/BooksSync( 6846): started syncMyEbooks
,V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2068): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2068): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2068): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2068): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
W/GLSActivity( 2068): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2068): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2068): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2068): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2068): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2068): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2068): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6846): Authentication error
E/BooksAccountManager( 6846): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6846): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6846): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6846): null auth token
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2c928bbd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6846): Error response from books API: {
W/ApiaryClient( 6846):  "error": {
W/ApiaryClient( 6846):   "errors": [
W/ApiaryClient( 6846):    {
W/ApiaryClient( 6846):     "domain": "global",
W/ApiaryClient( 6846):     "reason": "required",
W/ApiaryClient( 6846):     "message": "Login Required",
W/ApiaryClient( 6846):     "locationType": "header",
W/ApiaryClient( 6846):     "location": "Authorization"
W/ApiaryClient( 6846):    }
W/ApiaryClient( 6846):   ],
W/ApiaryClient( 6846):   "code": 401,
W/ApiaryClient( 6846):   "message": "Login Required"
W/ApiaryClient( 6846):  }
W/ApiaryClient( 6846): }
,W/ApiaryClient( 6846): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6846): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7589791838470555614&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6846): Headers:
W/ApiaryClient( 6846): accept-encoding: [gzip]
W/ApiaryClient( 6846): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6846): gdata-version: 2
,V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2068): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2068): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2068): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2068): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2068): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2068): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2068): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2068): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2068): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2068): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2068): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6846): Authentication error
E/BooksAccountManager( 6846): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6846): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6846): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6846): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2c928bbd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6846): Error response from books API: {
W/ApiaryClient( 6846):  "error": {
W/ApiaryClient( 6846):   "errors": [
W/ApiaryClient( 6846):    {
W/ApiaryClient( 6846):     "domain": "global",
W/ApiaryClient( 6846):     "reason": "required",
W/ApiaryClient( 6846):     "message": "Login Required",
W/ApiaryClient( 6846):     "locationType": "header",
W/ApiaryClient( 6846):     "location": "Authorization"
W/ApiaryClient( 6846):    }
W/ApiaryClient( 6846):   ],
W/ApiaryClient( 6846):   "code": 401,
W/ApiaryClient( 6846):   "message": "Login Required"
W/ApiaryClient( 6846):  }
W/ApiaryClient( 6846): }
,W/ApiaryClient( 6846): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6846): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7589791838470555614&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6846): Headers:
W/ApiaryClient( 6846): accept-encoding: [gzip]
W/ApiaryClient( 6846): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6846): gdata-version: 2
,V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2068): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2068): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2068): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2068): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
,W/GLSActivity( 2068): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2068): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2068): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2068): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2068): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2068): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2068): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6846): Authentication error
E/BooksAccountManager( 6846): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6846): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6846): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6846): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2c928bbd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6846): Error response from books API: {
W/ApiaryClient( 6846):  "error": {
W/ApiaryClient( 6846):   "errors": [
W/ApiaryClient( 6846):    {
W/ApiaryClient( 6846):     "domain": "global",
W/ApiaryClient( 6846):     "reason": "required",
W/ApiaryClient( 6846):     "message": "Login Required",
W/ApiaryClient( 6846):     "locationType": "header",
W/ApiaryClient( 6846):     "location": "Authorization"
W/ApiaryClient( 6846):    }
W/ApiaryClient( 6846):   ],
W/ApiaryClient( 6846):   "code": 401,
W/ApiaryClient( 6846):   "message": "Login Required"
W/ApiaryClient( 6846):  }
W/ApiaryClient( 6846): }
,W/ApiaryClient( 6846): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6846): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7589791838470555614&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6846): Headers:
W/ApiaryClient( 6846): accept-encoding: [gzip]
W/ApiaryClient( 6846): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6846): gdata-version: 2
,E/BooksSync( 6846): Soft error: 
E/BooksSync( 6846): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6846): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7589791838470555614&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6846): Headers:
E/BooksSync( 6846): accept-encoding: [gzip]
E/BooksSync( 6846): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6846): gdata-version: 2
E/BooksSync( 6846): 
E/BooksSync( 6846): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6846): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6846): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6846): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6846): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6846): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6846): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6846): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6846): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6846): {
E/BooksSync( 6846):  "error": {
E/BooksSync( 6846):   "errors": [
E/BooksSync( 6846):    {
E/BooksSync( 6846):     "domain": "global",
E/BooksSync( 6846):     "reason": "required",
E/BooksSync( 6846):     "message": "Login Required",
E/BooksSync( 6846):     "locationType": "header",
E/BooksSync( 6846):     "location": "Authorization"
E/BooksSync( 6846):    }
E/BooksSync( 6846):   ],
E/BooksSync( 6846):   "code": 401,
E/BooksSync( 6846):   "message": "Login Required"
E/BooksSync( 6846):  }
E/BooksSync( 6846): }
E/BooksSync( 6846): 
E/BooksSync( 6846): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6846): 	... 8 more
,E/BooksSync( 6846): Sync error
E/BooksSync( 6846): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6846): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7589791838470555614&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6846): Headers:
E/BooksSync( 6846): accept-encoding: [gzip]
E/BooksSync( 6846): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6846): gdata-version: 2
E/BooksSync( 6846): 
E/BooksSync( 6846): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6846): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6846): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6846): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6846): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6846): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6846): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6846): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6846): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6846): {
E/BooksSync( 6846):  "error": {
E/BooksSync( 6846):   "errors": [
E/BooksSync( 6846):    {
E/BooksSync( 6846):     "domain": "global",
E/BooksSync( 6846):     "reason": "required",
E/BooksSync( 6846):     "message": "Login Required",
E/BooksSync( 6846):     "locationType": "header",
E/BooksSync( 6846):     "location": "Authorization"
E/BooksSync( 6846):    }
E/BooksSync( 6846):   ],
E/BooksSync( 6846):   "code": 401,
E/BooksSync( 6846):   "message": "Login Required"
E/BooksSync( 6846):  }
E/BooksSync( 6846): }
E/BooksSync( 6846): 
E/BooksSync( 6846): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6846): 	... 8 more
I/BooksSync( 6846): Finished books sync
D/SyncManager( 1036): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 296417, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 316054107800; DSPS: 10497893; Offset : -4329064292
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=778865943, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{2d136528 type 2 when 326543 android} when 326543
D/[Concierge]Service( 2597): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=778865943 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 336055696334; DSPS: 11153305; Offset : -4329062516
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 356057505128; DSPS: 11808725; Offset : -4329084855
,I/[SystemUI]LGPowerUI( 1472): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1472): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1472): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
D/WifiController( 1036): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1472): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]BatterySaverHandler( 1472): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1937): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1937): Battery Level Remaining: 100%
D/LEDHandler( 1937): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3892): Disconnected process message: 10, size: 0
D/LGDMClient( 4365): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4365): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2068): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2068): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2068): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2068): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2068): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2068): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2068): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2068): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2068): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2068): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2068): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 6275): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6275): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6275): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6275): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6275): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6275): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6275): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2c928bbd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/System  ( 6275): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  312): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  312): res_queryN name = play.googleapis.com succeed
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 376059399339; DSPS: 12464147; Offset : -4329082760
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=778865943, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,D/[Concierge]Service( 2597): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=778865943 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 396061260842; DSPS: 13119567; Offset : -4329052389
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 416062923386; DSPS: 13774982; Offset : -4329068183
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{1d3343ca type 2 when 423566 android} when 423566
,I/BooksSync( 6846): Starting books sync
,I/art     ( 1036): Explicit concurrent mark sweep GC freed 29192(1325KB) AllocSpace objects, 10(1056KB) LOS objects, 33% free, 44MB/66MB, paused 3.600ms total 157.921ms
,D/BooksSync( 6846): started syncMyEbooks
,V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2068): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2068): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2068): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2068): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1419): onNotificationPosted
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
,W/GLSActivity( 2068): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2068): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2068): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2068): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2068): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2068): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2068): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
E/BooksAccountManager( 6846): Authentication error
E/BooksAccountManager( 6846): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6846): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6846): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6846): null auth token
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2c928bbd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6846): Error response from books API: {
W/ApiaryClient( 6846):  "error": {
W/ApiaryClient( 6846):   "errors": [
W/ApiaryClient( 6846):    {
W/ApiaryClient( 6846):     "domain": "global",
W/ApiaryClient( 6846):     "reason": "required",
W/ApiaryClient( 6846):     "message": "Login Required",
W/ApiaryClient( 6846):     "locationType": "header",
W/ApiaryClient( 6846):     "location": "Authorization"
W/ApiaryClient( 6846):    }
W/ApiaryClient( 6846):   ],
W/ApiaryClient( 6846):   "code": 401,
W/ApiaryClient( 6846):   "message": "Login Required"
W/ApiaryClient( 6846):  }
W/ApiaryClient( 6846): }
W/ApiaryClient( 6846): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6846): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7030375174025780341&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6846): Headers:
W/ApiaryClient( 6846): accept-encoding: [gzip]
W/ApiaryClient( 6846): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6846): gdata-version: 2
,V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2068): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2068): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2068): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2068): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2068): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2068): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2068): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2068): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2068): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2068): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2068): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6846): Authentication error
E/BooksAccountManager( 6846): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6846): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6846): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6846): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2c928bbd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6846): Error response from books API: {
W/ApiaryClient( 6846):  "error": {
W/ApiaryClient( 6846):   "errors": [
W/ApiaryClient( 6846):    {
W/ApiaryClient( 6846):     "domain": "global",
W/ApiaryClient( 6846):     "reason": "required",
W/ApiaryClient( 6846):     "message": "Login Required",
W/ApiaryClient( 6846):     "locationType": "header",
W/ApiaryClient( 6846):     "location": "Authorization"
W/ApiaryClient( 6846):    }
W/ApiaryClient( 6846):   ],
W/ApiaryClient( 6846):   "code": 401,
W/ApiaryClient( 6846):   "message": "Login Required"
W/ApiaryClient( 6846):  }
W/ApiaryClient( 6846): }
,W/ApiaryClient( 6846): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6846): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7030375174025780341&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6846): Headers:
W/ApiaryClient( 6846): accept-encoding: [gzip]
W/ApiaryClient( 6846): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
,W/ApiaryClient( 6846): gdata-version: 2
V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2068): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2068): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2068): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2068): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2068): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2068): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2068): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2068): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2068): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2068): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2068): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6846): Authentication error
E/BooksAccountManager( 6846): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6846): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6846): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6846): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6846): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2c928bbd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6846): Error response from books API: {
W/ApiaryClient( 6846):  "error": {
W/ApiaryClient( 6846):   "errors": [
W/ApiaryClient( 6846):    {
W/ApiaryClient( 6846):     "domain": "global",
W/ApiaryClient( 6846):     "reason": "required",
W/ApiaryClient( 6846):     "message": "Login Required",
W/ApiaryClient( 6846):     "locationType": "header",
W/ApiaryClient( 6846):     "location": "Authorization"
W/ApiaryClient( 6846):    }
W/ApiaryClient( 6846):   ],
W/ApiaryClient( 6846):   "code": 401,
W/ApiaryClient( 6846):   "message": "Login Required"
W/ApiaryClient( 6846):  }
W/ApiaryClient( 6846): }
,W/ApiaryClient( 6846): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6846): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7030375174025780341&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6846): Headers:
W/ApiaryClient( 6846): accept-encoding: [gzip]
W/ApiaryClient( 6846): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6846): gdata-version: 2
,E/BooksSync( 6846): Soft error: 
E/BooksSync( 6846): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6846): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7030375174025780341&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6846): Headers:
E/BooksSync( 6846): accept-encoding: [gzip]
E/BooksSync( 6846): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6846): gdata-version: 2
E/BooksSync( 6846): 
E/BooksSync( 6846): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6846): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6846): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6846): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6846): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6846): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6846): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6846): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6846): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6846): {
E/BooksSync( 6846):  "error": {
E/BooksSync( 6846):   "errors": [
E/BooksSync( 6846):    {
E/BooksSync( 6846):     "domain": "global",
E/BooksSync( 6846):     "reason": "required",
E/BooksSync( 6846):     "message": "Login Required",
E/BooksSync( 6846):     "locationType": "header",
E/BooksSync( 6846):     "location": "Authorization",
E/BooksSync( 6846):    }
E/BooksSync( 6846):   ],
E/BooksSync( 6846):   "code": 401,
E/BooksSync( 6846):   "message": "Login Required"
E/BooksSync( 6846):  }
E/BooksSync( 6846): }
,E/BooksSync( 6846): 
E/BooksSync( 6846): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6846): 	... 8 more
,E/BooksSync( 6846): Sync error
E/BooksSync( 6846): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6846): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7030375174025780341&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6846): Headers:
E/BooksSync( 6846): accept-encoding: [gzip]
E/BooksSync( 6846): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6846): gdata-version: 2
E/BooksSync( 6846): 
E/BooksSync( 6846): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6846): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6846): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6846): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6846): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6846): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6846): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6846): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6846): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6846): {
E/BooksSync( 6846):  "error": {
E/BooksSync( 6846):   "errors": [
E/BooksSync( 6846):    {
E/BooksSync( 6846):     "domain": "global",
E/BooksSync( 6846):     "reason": "required",
E/BooksSync( 6846):     "message": "Login Required",
E/BooksSync( 6846):     "locationType": "header",
E/BooksSync( 6846):     "location": "Authorization"
E/BooksSync( 6846):    }
E/BooksSync( 6846):   ],
E/BooksSync( 6846):   "code": 401,
E/BooksSync( 6846):   "message": "Login Required"
E/BooksSync( 6846):  }
E/BooksSync( 6846): }
E/BooksSync( 6846): 
E/BooksSync( 6846): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6846): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6846): 	... 8 more
I/BooksSync( 6846): Finished books sync
D/SyncManager( 1036): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 423566, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 436064466556; DSPS: 14430393; Offset : -4329081331
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=778865943, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{2428264 type 2 when 453614 android} when 453614
D/[Concierge]Service( 2597): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=778865943 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 456066139777; DSPS: 15085807; Offset : -4329056189
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 476067521905; DSPS: 15741213; Offset : -4329077843
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 496069142210; DSPS: 16396626; Offset : -4329074996
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 516070482984; DSPS: 17052030; Offset : -4329077048
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 536071888185; DSPS: 17707436; Offset : -4329075629
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 556073457292; DSPS: 18362847; Offset : -4329062580
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 576075043950; DSPS: 19018259; Offset : -4329063304,
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 596076893005; DSPS: 19673680; Offset : -4329075744
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 616079289924; DSPS: 20329118; Offset : -4329059092
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
I/wpa_supplicant( 2790): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
E/WifiMonitor( 1036): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/WifiMonitor( 1036): handleNetworkStateChange: Could not parse disconnect string
E/WifiMonitor( 1036): WifiMonitor notify network disconnect: null reason=0
D/Tethering( 1036): InitialState.processMessage what=4
,E/WifiStateMachine( 1036):  ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=622152
E/WifiStateMachine( 1036):  L2ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=622152
E/WifiStateMachine( 1036):  ConnectModeState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=622153
E/WifiConfigStore( 1036): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1036): doBoolean: SET_NETWORK 0 bssid any
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1036): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1036): doBoolean: SAVE_CONFIG
,D/Tethering( 1036): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1036): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2790): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 1
D/WifiNative-wlan0( 1036): SET ps 1: returned true
D/DhcpStateMachine( 1036): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  312): Clearing all IP addresses on wlan0
V/NativeCrypto( 2068): Read error: ssl=0xaa760a00: I/O error during system call, Connection timed out
,D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
V/NativeCrypto( 2068): SSL shutdown failed: ssl=0xaa760a00: I/O error during system call, Broken pipe
I/jxcore-log( 6933): Toggling radios to false
I/jxcore-log( 6933): 
,I/wpa_supplicant( 2790): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1036): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@37642ccd mBinding = false
E/WifiStateMachine( 1036): WifiStateMachine: Leaving Connected state
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=622281  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=622281  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1036):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=622284  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=622285  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1036):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1036): ignoring duplicate network state non-change
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,D/WifiHS20( 1036): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1937): handleWifiStateChangedEvent: 0
,W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/BluetoothManagerService( 1036): Message: 2
D/BluetoothManagerService( 1036): Sending off request.
D/LGBluetoothServiceAdapter( 3892): [BTUI] Precleanup
D/BluetoothAdapterState( 3892): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
,D/BluetoothAdapterProperties( 3892): Setting state to 13
I/BluetoothAdapterState( 3892): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 3892): onBluetoothDisable()
I/BluetoothAdapterState( 3892): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/SettingsProvider( 1036): User 0 external modification to /data/data/com.android.providers.settings/databases/settings.db; event=2
D/SettingsProvider( 1036): User 0 updating our caches for /data/data/com.android.providers.settings/databases/settings.db
D/BluetoothManagerService( 1036): Message: 60
D/BluetoothManagerService( 1036): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1036): Bluetooth State Change Intent: 12 -> 13
D/LocationManagerService( 1036): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1036): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1036): JNI:system_update. Event-4
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1036): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): ValidatedState{ when=-6ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): DefaultState{ when=-6ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/WifiHS20( 1036): hidePasspointNotification off =false
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1036): hidePasspointNotification off =false
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1036): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1036): disableDataServiceNotify
D/DSQN    ( 1036): stop dsqn bin
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1036): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/ConnectivityService( 1036): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
D/SettingsProvider( 1036): row count exceeds max cache entries for table system
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/Nat464Xlat( 1036): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1036): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1036): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Disconnected - quitting
D/ConnectivityService( 1036): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/UsbSettingsReceiver( 7010): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/UsbSettingsReceiver( 7010): [AUTORUN] sys.usb.config = ptp_only,adb
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/UsbSettingsReceiver( 7010): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7010): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/WifiServiceImplEx( 1036): setWifiEnabled: false pid=6933, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiService( 1036): setWifiEnabled: false pid=6933, uid=10311
E/WifiService( 1036): Invoking mWifiStateMachine.setWifiEnabled
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/LocSvc_java( 1036): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1036): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1036): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1036): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1036): [LG_RESTRICTED] !!!isConnected  type  :1
D/Connectiv,ityService( 1036): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1036): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/NetworkManagementService( 1036): Removing idletimer
W/Settings( 1036): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1036): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/TelephonyNetworkFactory-1( 1849): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/TelephonyNetworkFactory-1( 1849):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/UsbSettingsReceiver( 7010): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/WifiNetworkAgent( 1036): NetworkAgent: NetworkAgent channel lost
D/WIFI    ( 1036): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/BluetoothAdapterProperties( 3892): Scan Mode:20
D/BluetoothAdapterState( 3892): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/BtOppRfcommListener( 3892): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/btif_config_util( 3892): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
V/BluetoothMapMasInstance( 3892): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3892): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3892): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 3892): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 3892): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 3892): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3892): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3892): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
V/BluetoothSapService( 3892): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothFtpService:RfcommSocketAcceptThread( 3892): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-l2cap( 3892): L2CAP - L2CA_Deregister() called for PSM: 0x000f
V/BluetoothPbapService( 3892): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-btif ( 3892): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
D/LGBluetoothAPIService( 1937): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/BluetoothMapService( 3892): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 3892): STATE_TURNING_OFF
V/BtOppService( 3892): Receiver DISABLED_ACTION 
V/BluetoothMapService( 3892): Handler(): got msg=4
D/BluetoothMapService( 3892): MAP Service closeService in
D/BluetoothMapMasInstance( 3892): MAP Service shutdown
D/LGBluetoothMapAdapter( 3892): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3892): MAP Service closeService out
I/BtOppRfcommListener( 3892): stopping Accept Thread
V/BtOppRfcommListener( 3892): close mBtServerSocket
D/LocationManagerService( 1036): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1036): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1036): JNI:system_update. Event-4
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/bt-l2cap( 3892): L2CAP - L2CA_Deregister() called for PSM: 0x0019
V/BtOppRfcommListener( 3892): waiting for thread to terminate
W/bt-l2cap( 3892): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3892): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3892): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3892): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3892): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3892): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3892): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3892): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3892): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3892): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 3892): bta_gattc_deregister Deregister Failedm unknown client cif
I/BtOppRfcommListener( 3892): BluetoothSocket listen thread finished
V/BtOppRfcommListener( 3892): done waiting for thread to terminate
I/jxcore-log( 6933): Radios toggled
I/jxcore-log( 6933): 
E/WifiStateMachine( 1036):  DisconnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
D/DhcpStateMachine( 1036): StoppedState
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
V/NetworkPolicy( 1036): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1036): Sending msg: 4 arg1:0 arg2:1
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateSCANNING
V/BtOppService( 3892): onDestroy
D/LocSvc_java( 1036): getAGpsConnectionInfo connType - 4
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LocSvc_java( 1036): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1036): ignore wifi update if we are not in OPENING or CLOSING
D/LGBluetoothOppAdapter( 3892): [BTUI] LGBluetoothOppAdapter cleanup
D/UsbSettingsControl( 7010): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7010): [AUTORUN] onReceive() : availableList=[]
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/UsbSettingsReceiver( 7010): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7010): [AUTORUN] onReceive() : errorList=[]
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/UsbSettingsControl( 7010): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/WifiMonitor( 1036): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@3c100450
D/UsbSettingsControl( 7010): [AUTORUN] setTetherStatus() : status=false
D/LGWifiP2pService( 1036): P2pDisablingState
D/LGWifiP2pService( 1036): P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): p2p socket connection lost
D/LGWifiP2pService( 1036): P2pDisabledState
E/WifiStateMachine( 1036):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2790): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
V/BluetoothPbapReceiver( 3892): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3892): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3892): ***********state = 13
V/BluetoothPbapReceiver( 3892): ***********Calling start service!!!! with action = null
D/WifiScanningService( 1036): SCAN_AVAILABLE : 1
D/RttService( 1036): SCAN_AVAILABLE : 1
D/WifiScanningService( 1036): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1036): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
V/WfdStateTracker( 1937): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsService( 1937): WifiP2pState is changed : false
D/WfdsService( 1937): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1937): Set the WFDS Monitor: false
V/BluetoothPbapService( 3892): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 3892): state: 13
V/BluetoothPbapService( 3892): Pbap Service closeService in
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 1
D/LGWifiP2pService( 1036): P2pDisabledState{ when=-7ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-7ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1937): WFDS Monitor is stopped
D/WfdsService( 1937): STATE : WfdsDisabledState - enter
D/WifiNative-wlan0( 1036): SET ps 1: returned true
D/CtrlSupplicant( 1937): Received on exit socket, terminate
E/CtrlSupplicant( 1937): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1937): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1937): WfdsMonitorThread is received the interrupt - closing
D/CommandListener(  312): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1036): StoppedState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
W/WfdsSession:Controller( 1937): DefaultState - msg [9441355] is not handled
W/WfdsService( 1937): DefaultState - msg [9445378] is not handled
,W/ContextImpl( 7010): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
I/ActivityManager( 1036): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7740 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
V/BluetoothPbapService( 3892): successfully stopped pbap service
V/BluetoothPbapService( 3892): Pbap Service closeService out
V/BluetoothPbapService( 3892): Pbap Service onDestroy
V/BluetoothPbapService( 3892): Pbap Service closeService in
V/BluetoothPbapService( 3892): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 3892): [BTUI] cleanup
D/WifiHS20( 1036): hidePasspointNotification off =false
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/PostponalbeReceiver( 6530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-p2p0( 1036): doBoolean: TERMINATE
D/WifiNative-p2p0( 1036): TERMINATE: returned true
E/WifiStateMachine( 1036): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1036): useWiFiOffloading() : false
E/WifiStateMachine( 1036): CONFIG_LGE_WLAN_PATH : true
D/WifiHS20( 1036): hidePasspointNotification off =false
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/BluetoothManagerService( 1036): Message: 20
D/BluetoothManagerService( 1036): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3399b9fc:true
E/WifiStateMachine( 1036):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_ON_QUIT 0 0
V/WfdStateTracker( 1937): WfdStateTracker handleDirectStateChangedEvent: 6
I/WifiServerServiceExt( 1036): WIFI_STATE_CHANGED_ACTION [0]
I/PCSuite ( 7044): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7044): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7044): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/BluetoothManagerService( 1036): Message: 30
,D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
I/[SystemUI]BluetoothHandler( 1472): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/BluetoothManagerService( 1036): Message: 30
D/LocalBluetoothProfileManager( 7010): Adding local MAP profile
D/BluetoothMap( 7010): Create BluetoothMap proxy object
D/BluetoothManagerService( 1036): Message: 30
D/BluetoothManagerService( 1036): Message: 30
D/LocalBluetoothProfileManager( 7010): LocalBluetoothProfileManager construction complete
,D/LGBluetoothFeatureConfig( 7010):  get() - isFeatureLoaded : false
D/LGBluetoothUserBindClient( 7010): [BTUI] initUserBindClient
,D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ContextImpl( 7010): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 7010): finishStartingService: stopping service
V/WiFiOffLoadBroadcast( 7010): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/ActivityThread( 7740): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 7740): No ProfileInfo entries
I/LG Account v2.2( 7740): isEnabled: false
I/Feature ( 7740): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 7740): [Lifetracker]Country: EU
I/Feature ( 7740): [Lifetracker]Operator: OPEN
I/Feature ( 7740): [Lifetracker]Ranking support: false
I/Feature ( 7740): [Lifetracker]Comfort support: false
I/Feature ( 7740): [Lifetracker]Accessory: true
I/Feature ( 7740): [Lifetracker]Health device: true
I/Feature ( 7740): [Lifetracker]Extra Pedometer: false
I/Feature ( 7740): [Lifetracker]Blood glucose device: false
I/Feature ( 7740): [Lifetracker]Device Number: 3
,D/WiFiOffLoadBroadcast( 7010): MCCMNC not supported: null
D/BluetoothInputDevice( 7010): Proxy object connected
D/HidProfile( 7010): Bluetooth service connected
D/BluetoothPan( 7010): BluetoothPAN Proxy object connected
D/PanProfile( 7010): Bluetooth service connected
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/BluetoothMap( 7010): Proxy object connected
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/MapProfile( 7010): Bluetooth service connected
D/BluetoothMap( 7010): getConnectedDevices()
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/BluetoothMap( 7010): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 7010): [BTUI] onServiceConnected
D/LGBluetoothAuthorization( 7010): [BTUI] cancel All Notification
D/BluetoothPermissionRequest( 7010): onReceive
,D/LGBluetoothAuthorization( 7010): [BTUI] cancel All Notification
I/ActivityManager( 1036): Killing 2181:com.lge.music/u0a34 (adj 15): empty #17
,D/LGBluetoothResetSettingReceiver( 7010): return without doing reset settings.
V/AudioFlinger(  316): 2181 died, releasing its sessions
V/AudioFlinger(  316):  pid 1849 @ 0
V/AudioFlinger(  316):  pid 3399 @ 1
V/AudioFlinger(  316):  pid 3399 @ 2
,V/BluetoothOppReceiver( 3892): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,D/BluetoothOppNotification( 3892): [BTUI] cancel opp incoming file confirm notification
W/libprocessgroup( 1036): failed to open /acct/uid_10034/pid_2181/cgroup.procs: No such file or directory
D/BluetoothOppNotification( 3892): [BTUI] cancel opp active transfer file notification
V/BluetoothFtpReceiver( 3892): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 3892): BluetoothFtpReceiver Start Service
V/BluetoothFtpService( 3892): Ftp Service onStartCommand
V/BluetoothFtpService( 3892): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 3892): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 3892): Shutdown
D/QRemote ( 7068): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,V/BluetoothFtpService( 3892): successfully stopped ftp service
V/BluetoothFtpService( 3892): Ftp Service onDestroy
V/BluetoothFtpService( 3892): Ftp Service closeService
D/QRemote ( 7068): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
V/BluetoothSapReceiver( 3892): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 3892): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 3892): SapReceiver onReceive 
V/BluetoothSapReceiver( 3892): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3892):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3892): Calling SAP service start service with action = null
I/QRemote ( 7068): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/BluetoothSapService( 3892): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3892): state: 13
V/BluetoothSapService( 3892): Stopping SAP server process
V/BluetoothSapService( 3892): Sap Service closeSapService in
V/BluetoothSapService( 3892): Close listen Socket : 
V/BluetoothSapService( 3892): Close rfcomm Socket : 
V/BluetoothSapService( 3892): Close sapd  Socket : 
,D/PostponalbeReceiver( 6530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/BluetoothSapService( 3892): Sap Service closeSapService out
,V/BluetoothSapService( 3892): Sap Service onDestroy
V/BluetoothSapService( 3892): Sap Service closeSapService in
V/BluetoothSapService( 3892): Close listen Socket : 
V/BluetoothSapService( 3892): Close rfcomm Socket : 
V/BluetoothSapService( 3892): Close sapd  Socket : 
I/ActivityManager( 1036): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7767 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/BluetoothSapService( 3892): Sap Service closeSapService out
I/PCSuite ( 7044): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7044): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7044): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7010): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7010): MCCMNC not supported: null
D/QRemote ( 7068): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7068): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7068): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7044): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7044): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7044): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7010): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7010): MCCMNC not supported: null
D/QRemote ( 7068): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7068): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,W/ResourcesManager( 7767): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/QRemote ( 7068): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7010): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/AuthorizationBluetoothService( 2068): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/WiFiOffLoadBroadcast( 7010): MCCMNC not supported: null
D/QRemote ( 7068): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7068): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7068): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7044): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7044): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7044): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7010): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7010): MCCMNC not supported: null
D/QRemote ( 7068): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7068): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7068): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7044): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7044): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7044): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7010): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7010): MCCMNC not supported: null
,D/QRemote ( 7068): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7068): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7068): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PCSuite ( 7044): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7010): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,W/FormManager( 7197): Network not available. Please check & try again.
,D/WiFiOffLoadBroadcast( 7010): MCCMNC not supported: null
,V/FormManager( 7197): Network unavailable.
,V/FormManager( 7197): Network unavailable.
I/ActivityManager( 1036): Killing 7131:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1036): failed to open /acct/uid_10011/pid_7131/cgroup.procs: No such file or directory
,D/bt_hci_bdroid( 3892): cleanup
,I/bt_lpm  ( 3892): LPM is already off!!!
I/bt_userial_mct( 3892): exiting userial_read_thread
D/bt_userial_mct( 3892): Leaving userial_evt_read_thread()
W/bt-btif ( 3892): ag scb idx 1 not allocated
E/bt-btif ( 3892): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3892): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3892): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3892): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3892): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3892): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3892): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3892): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3892): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3892): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3892): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3892): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3892): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3892): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3892): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3892): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3892): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3892): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3892): L2CAP - PSM: 0x001b not found for deregistration
E/bt-btif ( 3892): bta_gattc_deregister Deregister Failedm unknown client cif
D/bt_userial_mct( 3892): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 3892): hw_epilog_process
D/bt_hci_bdroid( 3892): cleanup Finalizing cleanup
D/bt_userial_mct( 3892): userial_close
,E/bt_userial_mct( 3892): pthread_join() FAILED result:3,
I/bt_vendor( 3892): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,D/bt_hci_bdroid( 3892): set_power 0
I/bt_vendor( 3892): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 3892): bluetooth satus is on
I/bt_vendor( 3892): bt-vendor : resetting BT status
I/bt_vendor( 3892): Starting hciattach daemon
I/bt_vendor( 3892): try to set false
,I/bt_vendor( 3892): Starting hciattach daemon
I/bt_vendor( 3892): try to set false
I/bt_vendor( 3892): cleanup
I/GKI_LINUX( 3892): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3892): GKI_exit_task 0 done
I/GKI_LINUX( 3892): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3892): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/HeadsetService( 3892): Received stop request...Stopping profile...
,I/LGBluetoothHfpAdapter( 3892): [BTUI] LGBluetoothHfpAdapter cleanup
,W/LGBluetoothHeadsetServiceJni( 3892): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3892): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1817d24a
D/HeadsetStateMachine( 3892): Exit Disconnected: -1
D/BluetoothHeadset( 1849): Proxy object disconnected
D/BluetoothHeadset( 1849): Proxy object disconnected
D/BluetoothHeadset( 1849): Proxy object disconnected
D/BluetoothHeadset( 1036): Proxy object disconnected
D/AudioService( 1036): onServiceDisconnected: Bluetooth profile: 1
D/A2dpService( 3892): Received stop request...Stopping profile...
D/A2dpStateMachine( 3892): Exit Disconnected: -1
D/LGBluetoothAvrcpQcomAdapter( 3892): [BTUI] cleanup
,D/BluetoothAdapterState( 3892): Stopping profile services that were post enabled
D/LGBluetoothA2dpAdapter( 3892): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 3892): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3892): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1817d24a
D/BluetoothA2dp( 1036): Proxy object disconnected
D/AudioService( 1036): onServiceDisconnected: Bluetooth profile: 2
D/HidService( 3892): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3892): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1817d24a
,D/HeadsetStateMachine( 3892): Unbinding service...
D/HeadsetPhoneState( 3892): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3892): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 3892): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3892): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 3892): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3892): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 3892): [BTUI] LGBluetoothHfpAdapter cleanup
D/HealthService( 3892): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3892): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1817d24a
D/PanService( 3892): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3892): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1817d24a
D/BtGatt.DebugUtils( 3892): handleDebugAction() action=null
,D/BtGatt.GattService( 3892): Received stop request...Stopping profile...
D/BtGatt.GattService( 3892): stop()
D/BtGatt.AdvertiseManager( 3892): advertise clients cleared
D/BluetoothAdapterService( 3892): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1817d24a
D/BluetoothMapService( 3892): Received stop request...Stopping profile...
D/BluetoothMapService( 3892): stop()
D/BluetoothMapEmailAppObserver( 3892): deinitObservers()
D/BluetoothMapEmailAppObserver( 3892): removeReceiver()
D/BluetoothAdapterService( 3892): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1817d24a
I/BluetoothA2dpServiceJni( 3892): cleanupNative
I/GKI_LINUX( 3892): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3892): GKI_exit_task 2 done
I/GKI_LINUX( 3892): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 3892): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3892): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3892): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3892): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 3892): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3892): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3892): Cleaning up Bluetooth PAN callback object
,V/BluetoothMapService( 3892): Handler(): got msg=4
D/BluetoothMapService( 3892): MAP Service closeService in
D/LGBluetoothMapAdapter( 3892): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3892): MAP Service closeService out
D/BluetoothAdapterState( 3892): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3892): Setting state to 10
I/BluetoothAdapterState( 3892): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService( 1036): Message: 60
D/BluetoothManagerService( 1036): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1036): Broadcasting onBluetoothStateChange(false) to 9 receivers.
D/BluetoothA2dp( 1036): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 3892): Entering OffState
D/BluetoothHeadset( 1036): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1849): onBluetoothStateChange: up=false
D/BluetoothPbap( 7010): onBluetoothStateChange: up=false
D/BluetoothMapService( 3892): cleanup()
D/BluetoothMapService( 3892): MAP Service closeService in
D/LGBluetoothMapAdapter( 3892): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3892): MAP Service closeService out
D/BluetoothHeadset( 1849): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1849): onBluetoothStateChange: up=false
D/BluetoothMap( 7010): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 7010): onBluetoothStateChange: up=false
D/BluetoothPan( 7010): onBluetoothStateChange on: false
D/BluetoothManagerService( 1036): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1036): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/BluetoothManagerService( 1036): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1036): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1036): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@37642ccd mBinding = false
D/BluetoothManagerService( 1036): Sending unbind request.
I/GKI_LINUX( 3892): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 3892): GKI_exit_task 1 done
I/GKI_LINUX( 3892): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3892): cleanupNative: return from cleanup
I/art     ( 3892): --- WEIRD: removing null entry 246
W/art     ( 3892): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
W/LGBluetoothServiceJni( 3892): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 3892): [BTUI] unregister observer for LG device name DB
D/BluetoothManagerService( 1036): Bluetooth State Change Intent: 13 -> 10
I/art     ( 3892): System.exit called, status: 0
I/AndroidRuntime( 3892): VM exiting with result code 0, cleanup skipped.
V/AudioFlinger(  316): 3892 died, releasing its sessions
V/AudioFlinger(  316):  pid 1849 @ 0
V/AudioFlinger(  316):  pid 3399 @ 1
V/AudioFlinger(  316):  pid 3399 @ 2
,D/LGBluetoothAPIService( 1937): [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1937): Message: 101
E/LGBluetoothAPIService( 1937): MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
D/LGBluetoothAPIService( 1937): Calling onBluetoothServiceDown callbacks
D/LGBluetoothAPIService( 1937): Broadcasting onBluetoothServiceDown() to 0 receivers.
D/LGBluetoothUserBindClient( 7010): [BTUI] onServiceDisconnected
I/ActivityManager( 1036): Process com.android.bluetooth (pid 3892) has died
W/ActivityManager( 1036): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
W/ActivityManager( 1036): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 11000ms
,D/LGBluetoothAPIService( 1937): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1472): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/BluetoothAdapter( 1472): 293624098: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1472): 293624098: getState() :  mService = null. Returning STATE_OFF
D/LGBluetoothAPIService( 1937): Message: 2
D/LGBluetoothAPIService( 1937): unbindAndFinish(): null mBinding = false
,D/LGBluetoothFeatureConfig( 7010): isPrivacyLogsEnabled : true
E/LGBluetoothEventManager( 7010): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 7010): [BTUI] clear device connection state
W/ContextImpl( 7010): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
I/ActivityManager( 1036): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7812 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,D/DockEventReceiver( 7010): finishStartingService: stopping service
,W/ResourcesManager( 7812): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 7812): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7812): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,W/ResourcesManager( 7812): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothAdapterApp( 7812): Loading JNI Library
,D/BluetoothAdapterApp( 7812): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2776f143 Instance Count = 1
,D/BluetoothAdapterApp( 7812): onCreate
D/ProfileConfigQcom( 7812): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 7812): Adding HeadsetService
D/ProfileConfigQcom( 7812): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 7812): Adding A2dpService
,D/ProfileConfigQcom( 7812): [BTUI] HidService is supported
D/ProfileConfigQcom( 7812): Adding HidService
D/ProfileConfigQcom( 7812): [BTUI] HealthService is supported
D/ProfileConfigQcom( 7812): Adding HealthService
D/LGBluetoothFeatureConfig( 7812): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 7812): [BTUI] PanService is supported
D/ProfileConfigQcom( 7812): Adding PanService
D/ProfileConfigQcom( 7812): [BTUI] GattService is supported
D/ProfileConfigQcom( 7812): Adding GattService
D/ProfileConfigQcom( 7812): [BTUI] BluetoothMapService is supported
,D/ProfileConfigQcom( 7812): Adding BluetoothMapService
D/ProfileConfigQcom( 7812): [BTUI] HeadsetClientService is NOT supported
V/BluetoothPbapReceiver( 7812): PbapReceiver onReceive 
,V/BluetoothPbapReceiver( 7812): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 7812): ***********state = 10
,V/LGMDMManagerInternal( 7812): Create singleton instance
D/LGBluetoothUserBindClient( 7010): [BTUI] onServiceConnected
D/LGBluetoothAPIServer( 7812): [BTUI] onCreate()
D/LGBluetoothAPIServer( 7812): [BTUI] onBind()
D/LGBluetoothAPIService( 1937): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1937): Message: 100
D/LGBluetoothAPIService( 1937): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothPermissionRequest( 7010): onReceive
,D/LGBluetoothUtils( 7010): [BTUI] FileNotFound: readProperty
D/BluetoothDiscoverableTimeoutReceiver( 7010): cancelDiscoverableAlarm(): Enter
D/LGBluetoothResetSettingReceiver( 7010): return without doing reset settings.
D/LGBluetoothOppAdapter( 7812): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,V/BluetoothFtpReceiver( 7812): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 7812): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 7812): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 7812): SapReceiver onReceive 
V/BluetoothSapReceiver( 7812): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 7812):  Bluetooth Adapter state = 10
D/LGBluetoothProfileConnectionReceiver_EasySetting( 7767): [BTUI] STATE_OFF : reset connected device information EasySettings
,D/AuthorizationBluetoothService( 2068): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/wpa_supplicant( 2790): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 2790): monitor socket send errors count : 1
,I/wpa_supplicant( 2790): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1937-2\x00 that cannot receive messages
,W/wpa_supplicant( 2790): USIM:  scard_deinit function
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor( 1036): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1036):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=624381  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine( 1036):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=624382  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
I/wpa_supplicant( 2790): wlan0: CTRL-EVENT-TERMINATING 
,D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1036): Disconnecting from the supplicant, no more events
E/WifiStateMachine( 1036):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 40 0
D/WfdsService( 1937): Supplicant Connection state is changed : false
D/WfdsService( 1937): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1937): Set the WFDS Monitor: false
D/WfdsMonitor( 1937): WFDS Monitor is stopped
D/WifiOffDelayIfNotUsed( 1036): stopMonitoring
E/WifiStateMachine( 1036): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1036): useWiFiOffloading() : false
E/WifiStateMachine( 1036): CONFIG_LGE_WLAN_PATH : true
,D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1937): WfdStateTracker handleDirectStateChangedEvent: 0
W/Settings( 1813): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiServerServiceExt( 1036): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt( 1036): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1036): batteryPsActivateMsgHandler : this is not treated
D/LGDMClient( 4365): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4365): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4365): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4365): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/PCSuite ( 7044): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
D/PCSuite ( 7044): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7044): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7010): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 7010): MCCMNC not supported: null
D/LGDMClient( 4365): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4365): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4365): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/FormManager( 7197): Network not available. Please check & try again.
,V/FormManager( 7197): Network unavailable.
V/FormManager( 7197): Network unavailable.
,D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1036): MasterInitialState.processMessage what=3
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1036): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1036): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/PostponalbeReceiver( 6530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6530): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5566): type=WIFI subType= reason=null isConnected=false
,I/NetworkMonitor( 5566): type=WIFI subType= reason=null isConnected=false
,I/ActivityManager( 1036): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7850 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1036): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1036): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1036): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7850): onCreate
,W/AppUp4:DB( 7850):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7850):  setFingerPrint start
,I/AppUp4:DB( 7850):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7850):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7850):  SDK version = 21
I/AppUp4:DB( 7850):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7850): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 7850): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7850): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7850): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7850): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7850): onReceive
,D/LgDataFeature( 7850): LgDataFeature() Constructor: none
D/LgDataFeature( 7850): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7850): Context : android.app.ReceiverRestrictedContext@1f618bb5
D/AppUp4:CustFacade( 7850): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7850): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7850): begin check event
I/AppUp4:CustModeStarterReceiver( 7850): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7850): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7850): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7850): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7850): handleAsyncCustNotification do not startCustService
,I/ActivityManager( 1036): Killing 7155:com.lge.email/u0a23 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_10023/pid_7155/cgroup.procs: No such file or directory
D/LGDMClient( 4365): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4365): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4365): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4365): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4365): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4365): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4365): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager( 1036): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7892 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7892): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7892): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7892): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7892): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7892): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7892): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7892): LgDataFeature() Constructor: none
D/LgDataFeature( 7892): LgDataFeature() Constructor Done, null
,D/eas_req ( 7892): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/HubEmail( 7892): JNI_OnLoad()
,I/HubEmail( 7892): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 7892): registerNatives()
I/HubEmail( 7892): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7892): registerNativeMethods()
I/HubEmail( 7892): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7892): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/LgeMiscReceiver( 3399): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3399): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3399): networkInfo.isConnected() = false
W/FormManager( 7197): Network not available. Please check & try again.
V/FormManager( 7197): Network unavailable.
D/WeatherAncestor( 7266): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:24:4
,D/Weather.Utils( 7266): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7266): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7266): 2 : This is isUpdating : false
D/WeatherAncestor( 7266): connectivity changed - connection : true
D/WeatherService( 7266): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@337345bb
D/ForecastDataCache( 7266): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7266): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7266): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7266): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7266): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:24:4
W/Settings( 7892): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/FormManager( 7197): Network unavailable.
I/ActivityManager( 1036): Killing 6275:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1036): failed to open /acct/uid_10044/pid_6275/cgroup.procs: No such file or directory
,I/iu.Environment( 2313): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2313): num queued entries: 0
,I/iu.UploadsManager( 2313): num updated entries: 0
I/iu.SyncManager( 2313): NEXT; no task
D/ChimeraCfgMgr( 2313): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6530): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 7850): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7850): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7850): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7850): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7850): onReceive
D/AppUp4:CustFacade( 7850): Context : android.app.ReceiverRestrictedContext@1f618bb5
D/AppUp4:CustFacade( 7850): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7850): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7850): begin check event
I/AppUp4:CustModeStarterReceiver( 7850): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/LGDMClient( 4365): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4365): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4365): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4365): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/eas_req ( 7892): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
D/LGDMClient( 4365): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4365): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4365): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/Settings( 7892): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3399): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3399): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3399): networkInfo.isConnected() = false
D/WeatherAncestor( 7266): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:24:4
,W/FormManager( 7197): Network not available. Please check & try again.
,D/Weather.Utils( 7266): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7266): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7266): 2 : This is isUpdating : false
D/WeatherAncestor( 7266): connectivity changed - connection : true
D/WeatherService( 7266): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@337345bb
D/ForecastDataCache( 7266): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7266): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7266): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7266): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7266): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:24:4
V/FormManager( 7197): Network unavailable.
,V/FormManager( 7197): Network unavailable.
D/ChimeraCfgMgr( 2313): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/LGWifiP2pService( 1036): P2pDisabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 1036):  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
,E/WifiStateMachine( 1036):  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=778865943, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{21760eaf type 2 when 628322 com.google.android.gms} when 628322
,D/[Concierge]Service( 2597): onStartCommand(). Type : 9
,D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1036): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=778865943 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 636081296064; DSPS: 20984544; Offset : -4329067268
,I/ActivityManager( 1036): Killing 6846:com.google.android.apps.books/u0a54 (adj 15): empty #17
,W/libprocessgroup( 1036): failed to open /acct/uid_10054/pid_6846/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 656082929129; DSPS: 21639958; Offset : -4329082101
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{217c2bc type 2 when 673959 android} when 673959
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 676084608079; DSPS: 22295373; Offset : -4329081540
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 696086287134; DSPS: 22950787; Offset : -4329050459
,I/[SystemUI]LGPowerUI( 1472): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1472): On Skip Timer : true
D/LEDHandler( 1937): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1937): Battery Level Remaining: 100%
D/LEDHandler( 1937): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1472): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1472): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1036): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1472): onReceive = android.intent.action.BATTERY_CHANGED
,D/LGDMClient( 4365): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
,D/LGDMClient( 4365): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 716088172542; DSPS: 23606209; Offset : -4329057167
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 736090832118; DSPS: 24261656; Offset : -4329052672
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 756092509038; DSPS: 24917072; Offset : -4329084607
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 776094279968; DSPS: 25572490; Offset : -4329083931
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 796095911157; DSPS: 26227903; Offset : -4329070095
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 816097328338; DSPS: 26883309; Offset : -4329056645
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 836098850518; DSPS: 27538719; Offset : -4329060343
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 856101462854; DSPS: 28194165; Offset : -4329072675
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 876102889878; DSPS: 28849572; Offset : -4329079899
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 896104568515; DSPS: 29504987; Offset : -4329079807
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 916106456738; DSPS: 30160409; Offset : -4329083727
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 936108073448; DSPS: 30815822; Offset : -4329084397
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 956109709847; DSPS: 31471235; Offset : -4329065428
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 976111441611; DSPS: 32126652; Offset : -4329072932
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=778865943, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,I/ActivityManager( 1036): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7985 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2597): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7985): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7985): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3500f03e
D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=778865943 [*alarm*], flags=0x0
I/ActivityManager( 1036): Killing 6762:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
I/QRemote ( 7068): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 7068): android.os.DeadObjectException
W/System.err( 7068): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7068): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7068): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7068): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 7068): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 7068): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 7068): 	at android.os.Handler.handleCallback(Handler.java:739)
,W/System.err( 7068): 	at android.os.Handler.dispatchMessage(Handler.java:95)
,W/System.err( 7068): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7068): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 7068): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7068): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7068): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 7068): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 7068): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7068): android.os.DeadObjectException
,W/System.err( 7068): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7068): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7068): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7068): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 7068): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 7068): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 7068): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7068): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7068): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7068): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 7068): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7068): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7068): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 7068): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 7068): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 7068): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_6762/cgroup.procs: No such file or directory
W/ActivityManager( 1036): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,D/QRemote ( 7068): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 7068): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
I/ActivityManager( 1036): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8019 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/QRemote ( 7068): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,D/UEI.SmartControl( 8019): Quickset Services start...
,I/UEI.SmartControl( 8019): Manufacture = LGE
D/UEI.SmartControl( 8019): Id = LGNevo
,D/UEI.SmartControl( 8019): File observer start...
E/UEI.SmartControl( 8019): IR Port is disabled: false
D/UEI.SmartControl( 8019): Starting file observer...
D/UEI.SmartControl( 8019): Extracting JNI libs...
D/UEI.SmartControl( 8019): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 8019): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 8019): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 8019): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 8019): --- Selecting new region: 6
,I/UEI.SmartControl( 8019): Model = LG-D855
D/UEI.SmartControl( 8019): QS Service created
I/UEI.SmartControl( 8019): Service initServices...
,D/UEI.SmartControl( 8019): QS start get config
D/UEI.SmartControl( 8019): Loading JNI Libs...
,I/UEI.SmartControl( 8019): Supports setup maps: true
,D/UEI.SmartControl( 8019): QS start statue = true Error code = 0
,I/UEI.SmartControl( 8019): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 8019): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 8019): ### init IR Blaster...
D/serial_port( 8019): Configuring serial port
E/UEI.SmartControl( 8019): UEIBLaster setting for 616
I/UEI.SmartControl( 8019): Setting serial record hearder size = 2
I/UEI.SmartControl( 8019): configuring settings for MAXQ616
I/UEI.SmartControl( 8019): Get version...
,D/UEI.SmartControl( 8019): serial port data available: 21
,D/UEI.SmartControl( 8019): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 8019): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 8019): QS saving settings...
,D/UEI.SmartControl( 8019): IR Blaster version: 25672567
,D/UEI.SmartControl( 8019): serial port data available: 4
,I/UEI.SmartControl( 8019): Device manager: loading config....
,D/UEI.SmartControl( 8019): ----------- loading internal config...
,W/ContextImpl( 8019): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 8019): Services init done
D/UEI.SmartControl( 8019): QS Service init finished
D/UEI.SmartControl( 8019): QS Service version name: 2.1.91
D/UEI.SmartControl( 8019): QS Service version code: 201091
,D/UEI.SmartControl( 8019): Service requested: Control
E/UEI.SmartControl( 8019): Loading SETTINGS...
D/UEI.SmartControl( 8019): Request IControl service: devices are loaded...
I/ActivityManager( 1036): Killing 7068:com.lge.qremote/u0a112 (adj 15): empty #17
,D/UEI.SmartControl( 8019): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 8019): Notify AllClients services are ready: 0
D/UEI.SmartControl( 8019): -----service ready thread exits
,W/libprocessgroup( 1036): failed to open /acct/uid_10112/pid_7068/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 8019): Internal service binding...
,D/serial_port( 8019): close(fd = 25)
,D/UEI.SmartControl( 8019): Internal timer expired: 1
,D/UEI.SmartControl( 8019): unbind internal service
D/UEI.SmartControl( 8019): Service.onUnbind: IControl
,D/UEI.SmartControl( 8019): Service.onDestroy
,D/UEI.SmartControl( 8019): Lock is in USE false
D/UEI.SmartControl( 8019): unbind internal service
I/UEI.SmartControl( 8019): Serial port is closed.
,I/UEI.SmartControl( 8019): Serial port is closed.
I/UEI.SmartControl( 8019): Serial port is closed.
,D/UEI.SmartControl( 8019): Blaster closed
D/UEI.SmartControl( 8019): Shut down QS...
D/UEI.SmartControl( 8019): Stopping QS lib
D/UEI.SmartControl( 8019): QS lib stop result = true
D/UEI.SmartControl( 8019): Stopped QS lib,
D/UEI.SmartControl( 8019): Stopped file observer...
D/UEI.SmartControl( 8019): QS shutdown complete
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2,
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0,
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 996113229207; DSPS: 32782070; Offset : -4329055304
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1016115101595; DSPS: 33437492; Offset : -4329075240
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1036116668671; DSPS: 34092903; Offset : -4329064404
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1056118556059; DSPS: 34748325; Offset : -4329068924
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1076121115167; DSPS: 35403769; Offset : -4329073526
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1096125956877; DSPS: 36059288; Offset : -4329084241
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1116127808900; DSPS: 36714708; Offset : -4329062961
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1136129717122; DSPS: 37370131; Offset : -4329077424
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1156131049927; DSPS: 38025534; Offset : -4329056954
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1176133928878; DSPS: 38680989; Offset : -4329077068
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1196135699339; DSPS: 39336407; Offset : -4329076653
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1216137597091; DSPS: 39991829; Offset : -4329071122
,I/UsageStatsService( 1036): User[0] Flushing usage stats to disk
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0,
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1236139200730; DSPS: 40647242; Offset : -4329084783
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1256141737858; DSPS: 41302685; Offset : -4329080640
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1276143377173; DSPS: 41958098; Offset : -4329058680
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1296145213780; DSPS: 42613519; Offset : -4329083800
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1316147016949; DSPS: 43268938; Offset : -4329081091
,TIME-OUT KILL (timeout was 1200000ms),D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1336148642046; DSPS: 43924351; Offset : -4329073503
I/[SystemUI]LGPowerUI( 1472): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1472): On Skip Timer : true
D/WifiController( 1036): battery changed pluggedType: 2
D/LGDMClient( 4365): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4365): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/LEDHandler( 1937): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1937): Battery Level Remaining: 100%
D/LEDHandler( 1937): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1472): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1472): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1472): onReceive = android.intent.action.BATTERY_CHANGED
D/AndroidRuntime( 8101): 
D/AndroidRuntime( 8101): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8101): CheckJNI is OFF
D/AndroidRuntime( 8101): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1036): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1036): Killing 6933:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
I/WindowState( 1036): WIN DEATH: Window{756a487 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1036): Client connection lost with reason: 4
D/InputDispatcher( 1036): Window went away: Window{756a487 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings( 1036): Skipping PackageSetting{29295602 com.example.hello/10319} due to missing metadata
E/libprocessgroup( 1036): failed to kill 1 processes for processgroup 6933
I/ActivityManager( 1036):   Force finishing activity ActivityRecord{22177790 u0 com.test.thalitest/.MainActivity t4}
E/GBMv2   (  335): DFP En is all cleared set to be enabled
W/ActivityManager( 1036): Spurious death for ProcessRecord{223324a7 6933:com.test.thalitest/u0a311}, curProc for 6933: null
I/ActivityManager( 1036): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1036):   Force finishing activity ActivityRecord{22177790 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1036): Duplicate finish request for ActivityRecord{22177790 u0 com.test.thalitest/.MainActivity t4 f}
I/[LGHome]EVENT( 2029): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2029): [Launcher.java:903:onResume()]onResume
D/SplitWindowPolicy( 1937): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1937): topRunningActivity=ActivityInfo{3d58fac5 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1937): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1937): topRunningActivity=ActivityInfo{34a8fc1a co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2029): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2029): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
D/KeyguardModel( 1472): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1813): Ignoring removeGeofence because network location is disabled.
D/LIA_Service_RemotePackageHandler( 1992): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3729): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
I/InputReader( 1036): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]GBoardWebView( 2029): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1902): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3729): handleMessage: what(1000) actionID(0x1000003)
W/System.err( 4552): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
D/PostponalbeReceiver( 6530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/System.err( 4552): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4552): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4552): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4552): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4552): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4552): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4552): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4552): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4552): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4552): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4552): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/art     ( 4602): Explicit concurrent mark sweep GC freed 16295(910KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 583us total 71.905ms
D/SplitUIManager( 1866): split_name #11 / not available #0
D/SplitUIService( 1866): removed split : 
I/ActivityManager( 1036): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=8152 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
I/[LGHome]LGActivityUtil( 2029): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2029): [Launcher.java:1056:onResume()]onResume end
I/[SystemUI]QSlideListController( 1472): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2029): [Launcher.java:1114:onPause()]onPause
I/[LGHome]GBoardWebView( 2029): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/ActionManagerService( 1902): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3729): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 3729): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/SplitUIManager( 1866): split_name #11 / not available #0
I/SplitUIService( 1866): split app #11
I/GBoardWebViewUtils( 2029): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2029): , create_time: 1430558575574
I/GBoardWebViewUtils( 2029): , expire_time: 0
I/GBoardWebViewUtils( 2029): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2029): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2029): , display: false
I/GBoardWebViewUtils( 2029): , animation: false }
I/GBoardWebViewUtils( 2029): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2029): , create_time: 1430558575600
I/GBoardWebViewUtils( 2029): , expire_time: 0
I/GBoardWebViewUtils( 2029): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2029): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2029): , display: false
I/GBoardWebViewUtils( 2029): , animation: false }
I/GBoardWebViewUtils( 2029): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1454599632914
I/GBoardWebViewUtils( 2029): , create_time: 1454599633839
I/GBoardWebViewUtils( 2029): , expire_time: 0
I/GBoardWebViewUtils( 2029): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2029): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2029): , display: false
I/GBoardWebViewUtils( 2029): , animation: false }
D/WallpaperManager( 2029): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/SystemUI[Framework]( 1036): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
V/SIM_STK ( 1036): Menu title from STK is T-Mobile
W/PhoneWindowManagerEx( 1036): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1036): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1036): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@25e72728,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1472): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1472): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 2029): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2029): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
I/art     ( 1036): Explicit concurrent mark sweep GC freed 88325(4MB) AllocSpace objects, 10(544KB) LOS objects, 33% free, 44MB/66MB, paused 1.618ms total 163.843ms
I/art     ( 1036): WaitForGcToComplete blocked for 147.723ms for cause Explicit
D/AppUp4:PreloadHelper( 7850): added Exclude : com.test.thalitest
D/administrator( 1036): Handling package changes for user 0
I/ActivityManager( 1036): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8172 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/[LGHome]EVENT( 2029): [Launcher.java:5349:onStop()]onStop
I/art     (  339): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 220us total 10.036ms
I/LockScreenSettings( 8152): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/art     (  339): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 190us total 8.768ms
I/art     (  339): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 181us total 8.748ms
D/KeyguardModel( 1472): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1472): createShortcutInfo...
D/KeyguardModel( 1472): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1472): createShortcutInfo...
W/ResourcesManager( 1472): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1472): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1472): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1472): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1472): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1472): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1472): createShortcutInfo...
W/ResourcesManager( 1472): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1472): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1472): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1472): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1472): createShortcutInfo...
W/ResourcesManager( 1472): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1472): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1472): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1472): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1472): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1472): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1472): createShortcutInfo...
I/ActivityManager( 1036): Killing 7740:com.lge.lifetracker/u0a37 (adj 15): empty #17
W/ResourcesManager( 8172): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/SIM_STK ( 1036): Menu title from STK is T-Mobile
W/ResourcesManager( 8172): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8172): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 8172): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 8172): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/NotificationService( 1036): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1036): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1036): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher.Model( 2029): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
D/KeyguardModel( 1472): handleShortcutListChanged...
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/art     ( 1036): Explicit concurrent mark sweep GC freed 8206(499KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.224ms total 207.301ms
D/PhoneStatusBar( 1472): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1472): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1472):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1472): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]Launcher.Model( 2029): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2029): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2029): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
D/KeyguardModel( 1472): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1472): createShortcutInfo...
W/libprocessgroup( 1036): failed to open /acct/uid_10037/pid_7740/cgroup.procs: No such file or directory
D/KeyguardModel( 1472): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1472): createShortcutInfo...
W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1472): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/TaskPersister( 1036): removeObsoleteFile: deleting file=4_task.xml
I/Timeline( 1036): Timeline: Activity_windows_visible id: ActivityRecord{37a4e96a u0 com.lge.launcher2/.Launcher t3} time:1338900
D/KeyguardModel( 1472): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1472): createShortcutInfo...
W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1472): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
D/KeyguardModel( 1472): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1472): createShortcutInfo...
I/[LGHome]Launcher.Model( 2029): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1472): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1472): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1472): createShortcutInfo...
I/[Concierge]WidgetView( 2029): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/KeyguardModel( 1472): handleShortcutListChanged...
D/[Concierge]Service( 2597): onStartCommand(). Type : 8
D/[Concierge]Service( 2597): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2597): Update widget ID : 11
D/[Concierge]WidgetView( 2029): change position of spinner
I/[Concierge]WidgetView( 2029): initWebView(). Time : 1454682957102
D/[Concierge]Service( 2597): onStartCommand(). Type : 0
I/SystemConfig( 8172): BUILD Country: EU
I/SystemConfig( 8172): BUILD Operator: OPEN
I/[Concierge]WebView( 2029): Return exist ConciergeWebView. Reuse : 287072509
D/[Concierge]WidgetView( 2029): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2029): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2029): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1e9b739d
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2029): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2029): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2029): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2029): Widget kill message received. Destory myself. My : 1454681645898, New one : 1454682957102
D/[Concierge]WidgetView( 2029): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2029): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/AndroidRuntime( 8101): Shutting down VM
I/[LgeWidgetLib]LgeAppWidgetHostView( 2029): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/ActivityManager( 1036): Killing 7767:com.lge.settings.easy/1000 (adj 15): empty #17
E/[LgeWidgetLib]LgeAppWidgetHostView( 2029): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2029): Timeline: Activity_idle id: android.os.BinderProxy@1c832fae time:1339019
W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_7767/cgroup.procs: No such file or directory
I/SystemConfig( 8172): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 8172): existFile = false
I/SystemConfig( 8172): canReadFile = false
I/SystemConfig( 8172): systemFeature RCS result false
D/SystemConfig( 8172): refreshRcsSupport() :false
I/PackageChangeReceiver( 7892): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/VoicemailCleanupService( 2349): Cleaning up data for package: com.test.thalitest
I/chromium( 2029): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
I/ActivityManager( 1036): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8194 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/GBoardtInterface( 2029): onReloaded()
I/GBoardWebViewClient( 2029): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 3729): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 3729): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1902): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3729): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3729): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1902): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3729): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3729): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3729): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3729): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3729): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2029): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2029): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2029): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2029): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2029): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2029): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
W/ResourcesManager( 8194): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8194): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8194): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 8194): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/AppConfig( 8194): Total System Memory = 2995761152
D/SystemHelper( 8194): region [EU], country [EU], operator [OPEN], sub-operator []
E/SharedPreferencesImpl( 8194): Couldn't rename file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml to backup file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml.bak

```
