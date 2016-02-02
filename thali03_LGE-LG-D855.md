#### Test 5753124305d96c2_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
--------- beginning of system
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6714): Authentication error
E/BooksAccountManager( 6714): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6714): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6714): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6714): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{1585aee6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6714): Error response from books API: {
W/ApiaryClient( 6714):  "error": {
W/ApiaryClient( 6714):   "errors": [
W/ApiaryClient( 6714):    {
W/ApiaryClient( 6714):     "domain": "global",
W/ApiaryClient( 6714):     "reason": "required",
W/ApiaryClient( 6714):     "message": "Login Required",
W/ApiaryClient( 6714):     "locationType": "header",
W/ApiaryClient( 6714):     "location": "Authorization"
W/ApiaryClient( 6714):    }
W/ApiaryClient( 6714):   ],
W/ApiaryClient( 6714):   "code": 401,
W/ApiaryClient( 6714):   "message": "Login Required"
W/ApiaryClient( 6714):  }
W/ApiaryClient( 6714): }
W/ApiaryClient( 6714): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6714): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8215803570948499588&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6714): Headers:
W/ApiaryClient( 6714): accept-encoding: [gzip]
W/ApiaryClient( 6714): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6714): gdata-version: 2
E/BooksSync( 6714): Soft error: 
E/BooksSync( 6714): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6714): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8215803570948499588&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6714): Headers:
E/BooksSync( 6714): accept-encoding: [gzip]
E/BooksSync( 6714): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6714): gdata-version: 2
E/BooksSync( 6714): 
E/BooksSync( 6714): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6714): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6714): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6714): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6714): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6714): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6714): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6714): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6714): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6714): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6714): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6714): {
E/BooksSync( 6714):  "error": {
E/BooksSync( 6714):   "errors": [
E/BooksSync( 6714):    {
E/BooksSync( 6714):     "domain": "global",
E/BooksSync( 6714):     "reason": "required",
E/BooksSync( 6714):     "message": "Login Required",
E/BooksSync( 6714):     "locationType": "header",
E/BooksSync( 6714):     "location": "Authorization"
E/BooksSync( 6714):    }
E/BooksSync( 6714):   ],
E/BooksSync( 6714):   "code": 401,
E/BooksSync( 6714):   "message": "Login Required"
E/BooksSync( 6714):  }
E/BooksSync( 6714): }
E/BooksSync( 6714): 
E/BooksSync( 6714): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6714): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6714): 	... 8 more
E/BooksSync( 6714): Sync error
E/BooksSync( 6714): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6714): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8215803570948499588&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6714): Headers:
E/BooksSync( 6714): accept-encoding: [gzip]
E/BooksSync( 6714): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6714): gdata-version: 2
E/BooksSync( 6714): 
E/BooksSync( 6714): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6714): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6714): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6714): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6714): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6714): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6714): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6714): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6714): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6714): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6714): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6714): {
E/BooksSync( 6714):  "error": {
E/BooksSync( 6714):   "errors": [
E/BooksSync( 6714):    {
E/BooksSync( 6714):     "domain": "global",
E/BooksSync( 6714):     "reason": "required",
E/BooksSync( 6714):     "message": "Login Required",
E/BooksSync( 6714):     "locationType": "header",
E/BooksSync( 6714):     "location": "Authorization"
E/BooksSync( 6714):    }
E/BooksSync( 6714):   ],
E/BooksSync( 6714):   "code": 401,
E/BooksSync( 6714):   "message": "Login Required"
E/BooksSync( 6714):  }
E/BooksSync( 6714): }
E/BooksSync( 6714): 
E/BooksSync( 6714): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6714): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6714): 	... 8 more
I/BooksSync( 6714): Finished books sync
I/ActivityManager( 1038): Killing 6478:com.google.android.partnersetup/u0a8 (adj 15): empty #17
D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 79961, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
W/libprocessgroup( 1038): failed to open /acct/uid_10008/pid_6478/cgroup.procs: No such file or directory
,D/AndroidRuntime( 6780): 
D/AndroidRuntime( 6780): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6780): CheckJNI is OFF
I/MusicWidget( 2747): mDelayedStopHandler : unbind
I/MusicBrowser( 2236): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2236): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2236): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2236): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2236): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2236): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2236): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2236): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1038):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@3789f7dccom.lge.music.MediaPlaybackService$5@3f6bc0e5
D/MusicBrowser( 2236): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2236): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@2f4e980a
I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2236): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2236): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2236): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2236): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2236): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2236): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2236): reset
V/MediaPlayer[Native]( 2236): setListener
D/AndroidRuntime( 6780): Calling main entry com.android.commands.am.Am
V/MediaPlayer[Native]( 2236): disconnect
V/MediaPlayer[Native]( 2236): destructor
V/AudioFlinger(  320): releasing 13 from 2236 for -1
V/AudioFlinger(  320):  decremented refcount to 0
V/AudioFlinger(  320): purging stale effects
V/MediaPlayer[Native]( 2236): disconnect
D/MusicBrowser( 2236): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
I/ActivityManager( 1038): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/SmartShareClient( 2236): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2236): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2236): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2236): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2236): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2236): [SmartShareManagerClient] unregisterListener: 734336954
W/SmartShareClient( 2236): [SmartShareManagerClient] unregisterListener invalid listener: 734336954
I/SmartShareClient( 2236): [SmartShareManagerClient] terminate service: 2236/MediaPlaybackService/38090624
V/SplitWindowPolicy( 1969): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
E/HomeCloudIF( 2236): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2236): [SmartShareManagerClient] unbindService context:android.app.Application@401f66b
D/SplitInfo( 1038): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{21d7c077 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{21d7c077 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1038): AppWindowTokenEx init.. 
E/GBMv2   (  339): DFP En is all cleared set to be enabled
I/ActivityManager( 1038): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6807 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6780): Shutting down VM
V/CloudHub( 2236): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2236): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2236): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2236): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
I/ActivityManager( 1038): Killing 6119:com.lge.appbox.client/u0a11 (adj 15): empty #17
I/CloudHub( 2236): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29997
W/libprocessgroup( 1038): failed to open /acct/uid_10011/pid_6119/cgroup.procs: No such file or directory
V/ActivityManager( 1038): Display changed displayId=0
D/DSDPConnection( 1873): Display #0 changed.
I/GAV2    ( 6714): Thread[GAThread,5,main]: No campaign data found.
D/SplitWindowPolicy( 1969): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1969): topRunningActivity=ActivityInfo{3b1a53d0 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1969): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1969): topRunningActivity=ActivityInfo{129f3fc9 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6807): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6807): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6807): Loading: webviewchromium
I/LibraryLoader( 6807): Time to load native libraries: 5 ms (timestamps 8422-8427)
I/LibraryLoader( 6807): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6807): Binding Chromium to main looper Looper (main, tid 1) {2453780}
,I/LibraryLoader( 6807): Expected native library version number "",actual native library version number ""
,I/chromium( 6807): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6807): Initializing chromium process, renderers=0
,W/art     ( 6807): Attempt to remove local handle scope entry from IRT, ignoring
,V/AudioPolicyService(  320): registerClient() client 0xb1427fa0, uid 10311
,D/BluetoothManagerService( 1038): Message: 20
D/BluetoothManagerService( 1038): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a50476f:true
W/chromium( 6807): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6807): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6807): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 6807): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6807): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6807): Build Date: 12/12/14 금
I/Adreno-EGL( 6807): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6807): Remote Branch: 
I/Adreno-EGL( 6807): Local Patches: 
I/Adreno-EGL( 6807): Reconstruct Branch: 
,W/chromium( 6807): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6807): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 6807): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6807): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6807): CordovaWebView is running on device made by: LGE
,W/art     ( 6807): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6807): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6807): Render dirty regions requested: true
I/OpenGLRenderer( 6807): Initialized EGL, version 1.4
,W/ActivityManager( 1038): Activity pause timeout for ActivityRecord{388b64e4 u0 com.test.thalitest/.MainActivity t4}
D/OpenGLRenderer( 6807): Enabling debug mode 0
D/Atlas   ( 6807): Validating map...
,D/SplitWindow( 1038): check instance of lgWin Window{1c5bf1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 6807): LgDataFeature() Constructor: none
,D/LgDataFeature( 6807): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1038): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1478): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1038): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1038): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1038): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3722d2e8,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1478): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1478):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1478): , Keyguard show=false, IME shown=false, Panel expanded=false
I/Timeline( 6807): Timeline: Activity_idle id: android.os.BinderProxy@4d580b0 time:108901
,I/ActivityManager( 1038): Displayed com.test.thalitest/.MainActivity: +683ms (total +786ms)
I/Timeline( 1038): Timeline: Activity_windows_visible id: ActivityRecord{388b64e4 u0 com.test.thalitest/.MainActivity t4} time:108918
,I/chromium( 6807): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6807): 
,D/JsMessageQueue( 6807): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6807): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435221760
,I/chromium( 6807): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6807): 
,I/chromium( 6807): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/GBMv2   (  339): DFP En is all cleared set to be enabled
E/GBMv2   (  339): Set value is all cleared set the max
I/GBMv2   (  339): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6807): Initializing JXcore engine
W/jxcore-log( 6807): JXcore engine is ready
,W/Thread-803( 6870): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8386]" dev="sockfs" ino=8386 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-803( 6870): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-803( 6870): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9829]" dev="sockfs" ino=9829 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-803( 6870): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-803( 6870): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[34061]" dev="sockfs" ino=34061 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6807): Starting JXcore engine
,W/jxcore-log( 6807): Platform android
W/jxcore-log( 6807): 
W/jxcore-log( 6807): Process ARCH arm
W/jxcore-log( 6807): 
,I/jxcore-log( 6807): JXcore Cordova bridge is ready!
I/jxcore-log( 6807): 
,W/jxcore-log( 6807): JXcore engine is started
I/jxcore-log( 6807): Toggling radios to true
I/jxcore-log( 6807): 
,D/BluetoothAdapter( 6807): enable(): BT is already enabled..!
D/WifiService( 1038): New client listening to asynchronous messages
,D/WifiServiceImplEx( 1038): setWifiEnabled: true pid=6807, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1038): setWifiEnabled: true pid=6807, uid=10311
E/WifiService( 1038): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1038): disconnect pid=6807, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1038): reconnect pid=6807, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1038):  ConnectedState CMD_DISCONNECT 0 0
I/jxcore-log( 6807): Radios toggled
I/jxcore-log( 6807): 
E/WifiStateMachine( 1038):  L2ConnectedState CMD_DISCONNECT 0 0
I/jxcore-log( 6807): My device name is: LGE-LG-D855
I/jxcore-log( 6807): 
E/WifiNative: ( 1038): [111,464,557 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1038): doBoolean: DISCONNECT
,I/wpa_supplicant( 2801): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1038): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1038): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/Tethering( 1038): InitialState.processMessage what=4
D/Tethering( 1038): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1038): DISCONNECT: returned true
E/WifiStateMachine( 1038): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2801): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/DhcpStateMachine( 1038): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  316): Clearing all IP addresses on wlan0
V/NativeCrypto( 2141): Read error: ssl=0xaf4d7600: I/O error during system call, Connection timed out
,V/NativeCrypto( 2141): SSL shutdown failed: ssl=0xaf4d7600: I/O error during system call, Broken pipe
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1038): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,I/ActivityManager( 1038): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6886 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/WifiHS20( 1038): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1969): handleWifiStateChangedEvent: 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1038): hidePasspointNotification off =false
,E/WifiStateMachine( 1038): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1038):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1038): [111,597,065 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1038): doBoolean: RECONNECT
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 2801): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1038): RECONNECT: returned true
E/WifiStateMachine( 1038):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=111599
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=111599
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2801): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
,D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/CommandListener(  316): Clearing all IP addresses on wlan0
D/ConnectivityService( 1038): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1038): disableDataServiceNotify
D/DSQN    ( 1038): stop dsqn bin
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1038): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1038):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=111622  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=111622  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1038): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1038): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1478): CM callback handler got msg 524292
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1038): NetworkAgent: NetworkAgent channel lost
D/CSLegacyTypeTracker( 1038): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1038): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Disconnected - quitting
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1038): Removing idletimer
W/Settings( 1038): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1038): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
,E/ConnectivityService( 1038): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/TelephonyNetworkFactory-1( 1873): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1873):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=111640  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=111646  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WIFI    ( 1038): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateSCANNING
,D/TelephonyIcons( 1478): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 6886): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6886): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 6886): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6886): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6886): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6886): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyIcons( 1478): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/DhcpStateMachine( 1038): StoppedState
D/DhcpStateMachine( 1038): StoppedState{ when=-128ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 6886): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,D/UsbSettingsReceiver( 6886): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6886): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6886): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6886): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6886): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 6886): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6886): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6886): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6886): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6886): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6447): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1038): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6907 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6144:com.android.contacts/u0a19 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10019/pid_6144/cgroup.procs: No such file or directory
,I/PCSuite ( 6907): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6907): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6907): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6886): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 6886): LgDataFeature() Constructor: none
,D/LgDataFeature( 6886): LgDataFeature() Constructor Done, null
D/WiFiOffLoadBroadcast( 6886): MCCMNC not supported: null
I/ActivityManager( 1038): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6931 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1038): Killing 6509:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10023/pid_6509/cgroup.procs: No such file or directory
,W/ResourcesManager( 6931): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 6931): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6931): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 6931): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6931): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6931): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6931): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6931): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 6931): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6931): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6931): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6931): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6447): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 6931): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
I/PCSuite ( 6907): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6907): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6907): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 6931): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/WiFiOffLoadBroadcast( 6886): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6886): MCCMNC not supported: null
D/QRemote ( 6931): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6931): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6931): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6447): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6907): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6907): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6907): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6886): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6886): MCCMNC not supported: null
,D/QRemote ( 6931): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6931): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6931): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6447): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6907): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6907): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6907): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6886): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6886): MCCMNC not supported: null
D/QRemote ( 6931): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6931): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6931): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6447): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6886): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6886): MCCMNC not supported: null
D/QRemote ( 6931): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6931): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6931): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 6931): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6931): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6931): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 6931): LgDataFeature() Constructor: none
D/LgDataFeature( 6931): LgDataFeature() Constructor Done, null
,V/SoundPool( 6931): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6931): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6931): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6931): doLoad: loading sample sampleID=1
I/QRemote ( 6931): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 6931): Start decode
V/MediaPlayer[Native]( 6931): decode(31, 10857164, 17813)
V/MediaPlayerService(  320): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  320): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  320): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  320): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  320): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  320): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  320): player type = 3
,V/AwesomePlayer(  320): AwesomePlayer create()
V/AwesomePlayer(  320): reset_l() 
V/AwesomePlayer(  320): cancelPlayerEvents
V/AwesomePlayer(  320): setAudioSink() 
V/AwesomePlayer(  320): reset_l() 
V/AudioCache(  320): notify(0xb1163840, 8, 0, 0)
V/AudioCache(  320): ignored
V/AwesomePlayer(  320): cancelPlayerEvents
D/Utils   (  320): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  320): setDataSource_l dataSource
V/LGParserOSAL(  320): SniffLGParser start
V/LGParserOSAL(  320): MainType:5, SubType=0
V/LGParserOSAL(  320): #### check Mime : application/ogg
V/LGParserOSAL(  320): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  320): Use LGExtractor :application/ogg 
D/UEI.SmartControl( 6631): QS Service created
D/QRemote ( 6931): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 6931): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6931): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGParserOSAL(  320): supported mime: application/ogg
V/AwesomePlayer(  320): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  320): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  320): mBitrate = -1 bits/sec
V/AwesomePlayer(  320): AudioTrack Setting
V/AwesomePlayer(  320): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  320): setAudioSource() 
V/MediaPlayerService(  320): prepare
V/AwesomePlayer(  320): prepareAsync_l() 
V/MediaPlayerService(  320): wait for prepare
V/AwesomePlayer(  320): onPrepareAsyncEvent() 
V/AwesomePlayer(  320): initAudioDecoder() 
W/Utils   (  320): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  320): isOffloadSupported()
V/AudioPolicyManager(  320): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  320): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  320): isAudioPlaybackHookOn() false
V/AwesomePlayer(  320): getUseOffload() = 0 
V/OMXCodec(  320): OMXCodec::Create
V/OMXCodec(  320): findMatchingCodecs()
V/OMXCodec(  320): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  320): matchingCodecs.size()=1
V/OMXCodec(  320): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  320): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  320): LG Codec Adapter start
V/OMXCodec(  320): OMXCodec Createtor
V/OMXCodec(  320): setComponentRole
V/OMXCodec(  320): configureCodec protected=0
V/LGCodecAdapter(  320): called getLGCodecSpecificData
V/LGCodecOSAL(  320): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  320): Called LGconfigureCodecMETA
V/LGCodecOSAL(  320): Called LGconfigureCodecMSG
V/LGCodecOSAL(  320): Not support LGCodec
V/OMXCodec(  320): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  320): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  320): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  320): Could not offload audio decode, try pcm offload
W/Utils   (  320): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  320): isOffloadSupported()
V/AudioPolicyManager(  320): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  320): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  320): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  320): init()
V/OMXCodec(  32,0): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  320): allocateBuffers
V/OMXCodec(  320): allocateBuffersOnPort portIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb1434650 on input port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb14346a0 on input port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb14346f0 on input port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb1434740 on input port
V/OMXCodec(  320): allocateBuffersOnPort portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb1434790 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb1434ab0 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb1434b50 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb1434ba0 on output port
V/OMXCodec(  320): init() mAsyncCompletion wait!!! 
V/OMXCodec(  320): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  320): init() mAsyncCompletion wait!!! 
V/OMXCodec(  320): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  320): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  320): finishAsyncPrepare_l() 
V/AudioCache(  320): notify(0xb1163840, 5, 0, 0)
V/AudioCache(  320): ignored
V/AudioCache(  320): notify(0xb1163840, 1, 0, 0)
V/AudioCache(  320): prepared
V/AudioCache(  320): wait - success
V/MediaPlayerService(  320): start
V/AwesomePlayer(  320): play_l() 
V/AwesomePlayer(  320): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  320): createAudioPlayer_l
V/AwesomePlayer(  320): seekAudioIfNecessary_l() 
V/AwesomePlayer(  320): startAudioPlayer_l() 
D/AudioPlayer(  320): start of Playback, useOffload 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  320): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  320): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  320): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976464
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973977264
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973977424
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973977504
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  320): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  320): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  320): allocateBuffersOnPort portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb1434b50 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb1434ab0 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb1434790 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb119a0b0 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  320): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  320): notify(0xb1163840, 6, 0, 0)
V/AudioCache(  320): ignored
V/MediaPlayerService(  320): wait for playback complete
I/UEI.SmartControl( 6631): Service initServices...
D/UEI.SmartControl( 6631): QS start get config
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab602000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab603000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab604000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/LGMDMManager( 6931): Create singleton instance
V/AudioCache(  320): memcpy(0xab605000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab606000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab607000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab608000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab609000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab60a000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab60b000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab60c000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab60d000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab60e000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab60f000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab610000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab611000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab612000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab613000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab614000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab615000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab616000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab617000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab618000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab619000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab61a000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab61b000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab61c000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab61d000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab61e000, 0xb124a000, 4096)
,V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab61f000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab620000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab621000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab622000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab623000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab624000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab625000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab626000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab627000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab628000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab629000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab62a000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab62b000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab62c000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab62d000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab62e000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab62f000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab630000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
,V/AudioCache(  320): memcpy(0xab631000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab632000, 0xb124a000, 4096)
V/AudioCache(  320): write(0xb124a000, 4096)
V/AudioCache(  320): memcpy(0xab633000, 0xb124a000, 4096)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  320): postAudioEOS() 
V/AudioCache(  320): write(0xb124a000, 280)
V/AudioCache(  320): memcpy(0xab634000, 0xb124a000, 280)
V/AwesomePlayer(  320): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  320): onStreamDone
V/AwesomePlayer(  320): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  320): notify(0xb1163840, 2, 0, 0)
V/AudioCache(  320): playback complete
V/AwesomePlayer(  320): pause_l() 
V/AudioCache(  320): wait - success
V/MediaPlayerService(  320): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AudioCache(  320): notify(0xb1163840, 7, 0, 0)
V/AudioCache(  320): ignored
V/AwesomePlayer(  320): cancelPlayerEvents
D/AudioPlayer(  320): Pause Playback at 1068125
V/AwesomePlayer(  320): reset_l() 
V/AudioCache(  320): notify(0xb1163840, 8, 0, 0)
V/AudioCache(  320): ignored
V/AwesomePlayer(  320): cancelPlayerEvents
D/AudioPlayer(  320): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  320): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  320): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  320): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb1434740 on port 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb14346f0 on port 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb14346a0 on port 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb1434650 on port 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb119a0b0 on port 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb1434790 on port 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb1434ab0 on port 1
,V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb1434b50 on port 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  320): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  320): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  320): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  320): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  320): AudioPlayer releasing audio source
D/AudioPlayer(  320): AudioPlayer done releasing audio source
V/AwesomePlayer(  320): reset_l() 
V/AwesomePlayer(  320): cancelPlayerEvents
V/AwesomePlayer(  320): ~AwesomePlayer call
V/AwesomePlayer(  320): reset_l() 
V/AwesomePlayer(  320): cancelPlayerEvents
V/SoundPool( 6931): close(31)
V/SoundPool( 6931): pointer = 0x9ffc9000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 6931): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6931): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 6931): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5809
,I/UEI.SmartControl( 6631): Supports setup maps: true
,D/UEI.SmartControl( 6631): QS start statue = true Error code = 0
I/UEI.SmartControl( 6631): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6631): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6631): ### init IR Blaster...
D/serial_port( 6631): Configuring serial port
E/UEI.SmartControl( 6631): UEIBLaster setting for 616
I/UEI.SmartControl( 6631): Setting serial record hearder size = 2
I/UEI.SmartControl( 6631): configuring settings for MAXQ616
I/UEI.SmartControl( 6631): Get version...
D/UEI.SmartControl( 6631): serial port data available: 21
,D/UEI.SmartControl( 6631): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6631): IR Blaster version: 256702256704300002
,I/UEI.SmartControl( 6631): QS saving settings...
D/UEI.SmartControl( 6631): IR Blaster version: 25672567
D/UEI.SmartControl( 6631): serial port data available: 4
,W/ContextImpl( 6631): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6631): Services init done
D/UEI.SmartControl( 6631): QS Service init finished
D/UEI.SmartControl( 6631): QS Service version name: 2.1.91
D/UEI.SmartControl( 6631): QS Service version code: 201091
D/UEI.SmartControl( 6631): Service requested: Control
,D/UEI.SmartControl( 6631): Internal service binding...
I/QRemote ( 6931): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6631): Device manager: loading config....
I/UEI.SmartControl( 6631): ------ IControl API: 11
D/UEI.SmartControl( 6631): File observer start...
D/UEI.SmartControl( 6631): ----------- loading internal config...
E/UEI.SmartControl( 6631): IR Port is disabled: false
D/UEI.SmartControl( 6631): Starting file observer...
I/UEI.SmartControl( 6631): Registering callback...
I/UEI.SmartControl( 6631): ------ IControl API: 19
I/UEI.SmartControl( 6631): Registering Services Ready callback...
E/UEI.SmartControl( 6631): Loading SETTINGS...
,D/UEI.SmartControl( 6631): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6631): Notify AllClients services are ready: 0
,I/QRemote ( 6931): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/UEI.SmartControl( 6631): -----service ready thread exits
D/QRemote ( 6931): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6931): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6931): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6931): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6631): ------ IControl API: 8
D/QRemote ( 6931): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6931): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6931): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6931): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6931): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6931): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6931): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6931): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6931): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6931): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6931): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6931): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 6931): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6931): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6931): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454422580165]
D/QRemote ( 6931): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1038): Killing 6166:com.android.gallery3d/u0a27 (adj 15): empty #17
D/QRemote ( 6931): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1038): failed to open /acct/uid_10027/pid_6166/cgroup.procs: No such file or directory
,V/QRemote ( 6931): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 6931): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6931): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6931): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6931): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6931): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6931): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6931): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{8460b6b type 0 when 1454422578693 android} when 1454422578693
E/WifiStateMachine( 1038):  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):2 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:50997] from screen [on:0 period:-1571333035]
V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{2b2b2361 type 0 when 1454422580303 com.android.vending} when 1454422580303
W/ContextImpl( 4529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1038): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
I/wpa_supplicant( 2801): Trying to associate with SSID 'NG700'
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1038): couldn't identify event type - WPS-AP-AVAILABLE 
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1038):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
,E/WifiStateMachine( 1038):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1038):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1038):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
D/WifiNative-wlan0( 1038): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=113657  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=113669  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/PostponalbeReceiver( 6447): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATING
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6886): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WiFiOffLoadBroadcast( 6886): MCCMNC not supported: null
D/QRemote ( 6931): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6931): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/Finsky  ( 6235): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6235): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6235): [1] 5.onFinished: Scheduling replication attempt 2.
I/QRemote ( 6931): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6447): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6886): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6886): MCCMNC not supported: null
D/QRemote ( 6931): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6931): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6931): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2801): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1038): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=113752  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=113752  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1038):  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=113753
E/WifiStateMachine( 1038):  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=113753
E/WifiStateMachine( 1038):  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=113754
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=113754
E/WifiStateMachine( 1038):  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=113754
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=113755  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/Tethering( 1038): sendTetherStateChangedBroadcast 1, 0, 0
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,D/UsbSettingsReceiver( 6886): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=113767  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/UsbSettingsReceiver( 6886): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6886): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6886): [AUTORUN] persist.sys.usb.config = ptp_only,adb
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
E/WifiStateMachine( 1038):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/UsbSettingsReceiver( 6886): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateFOUR_WAY_HANDSHAKE
I/wpa_supplicant( 2801): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/UsbSettingsControl( 6886): [AUTORUN] getUsbConnected() : connected=true
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 2801): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/UsbSettingsReceiver( 6886): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6886): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6886): [AUTORUN] onReceive() : errorList=[]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1038): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1038): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=113777  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
,E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=113778  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1038):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=113779
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=113780
D/WifiNative-wlan0( 1038): doString: [STATUS]
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1038):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1038): setVHTCapabilityType  : false
D/UsbSettingsControl( 6886): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6886): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6886): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6447): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/WifiServerServiceExt( 1038): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1038): setKeepAlivePacketInterval msec : 60
V/WiFiOffLoadBroadcast( 6886): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 6886): MCCMNC not supported: null
D/QRemote ( 6931): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6931): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6931): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6447): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/ConnectivityService( 1038): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1038): Got NetworkAgent Messenger
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1038): NetworkAgent connected
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 6886): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6886): MCCMNC not supported: null
,D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
D/QRemote ( 6931): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6931): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6931): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6447): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
,D/CommandListener(  316): Setting iface cfg
E/WifiStateMachine( 1038): Start Dhcp Watchdog 2
E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=113838  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/DhcpStateMachine( 1038): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): WaitBeforeStartState
E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=113839  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=113839  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=113839  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=113840  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=113840  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETSUSPENDMODE 0
V/WiFiOffLoadBroadcast( 6886): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6886): MCCMNC not supported: null
D/QRemote ( 6931): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6931): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6931): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6447): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/wpa_supplicant( 2801): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 0
D/WifiNative-wlan0( 1038): SET ps 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2801): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1038): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1038): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1038): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@26747c90 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@26747c90 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): DHCP Start wake lock is acquired.
D/CommandListener(  316): Setting iface cfg
D/CommandListener(  316): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1038): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1038):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2801): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2801): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
E/WifiStateMachine( 1038):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1038): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/ConnectivityService( 1038): ignoring duplicate network state non-change
V/WiFiOffLoadBroadcast( 6886): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1038): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/WifiStateMachine( 1038): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1969): handleWifiStateChangedEvent: 1
D/WiFiOffLoadBroadcast( 6886): MCCMNC not supported: null
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
,E/ConnectivityService( 1038): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1038): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1038): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  316): netlink response contains error (File exists)
D/ConnectivityService( 1038): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService( 1038): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1038): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1038): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1038): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Connected
D/ConnectivityService( 1038): currentScore = 0, newScore = 20
D/ConnectivityService( 1038):    accepting network in place of null
D/ConnectivityService( 1038): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on "NG700"
D/WIFI    ( 1038): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1873): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1873):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService( 1038): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses,: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1038): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/libc-netbsd(  316): res_queryN name = clients3.google.com, class = 1, type = 28
,D/QRemote ( 6931): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6931): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = true, mWifiLevel = 0
I/QRemote ( 6931): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1038): [e] list.add(nai) empty : false size: 1
,D/ConnectivityService( 1038): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1038): validation of new default Network = false
D/ConnectivityService( 1038): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1038): enableDataServiceNotify 
D/DSQN    ( 1038): start dsqn bin
D/LocSvc_java( 1038): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1038): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1478): CM callback handler got msg 524290
,V/NetworkPolicy( 1038): [LG_RESTRICTED] checkMobilePolicy_type()
W/dsqn    ( 6990): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6990): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/PostponalbeReceiver( 6447): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,E/DSQN    ( 6990): DSQN ssw
V/WiFiOffLoadBroadcast( 6886): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/TelephonyIcons( 1478): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 6886): MCCMNC not supported: null
D/QRemote ( 6931): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6931): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6931): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/libc-netbsd(  316): res_queryN name = clients3.google.com, class = 1, type = 1
D/PostponalbeReceiver( 6447): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6886): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6886): MCCMNC not supported: null
D/QRemote ( 6931): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6931): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6931): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6447): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6907): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6907): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6886): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6886): MCCMNC not supported: null
D/libc-netbsd(  316): res_queryN name = clients3.google.com succeed
D/QRemote ( 6931): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6931): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6931): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 6931): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 6931): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6447): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/LGDataListener(  316): argv[0]=dsqncommand
D/LGDataListener(  316): argv[1]=wlan0
D/LGDataListener(  316): argv[2]=1
D/LGDataListener(  316): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1038): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1038): start to monitor internet connection
I/PCSuite ( 6907): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6907): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6886): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6886): MCCMNC not supported: null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 14:16:20 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454422580902], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454422580880]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Don't send network conditions - lacking user consent.
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Validated
D/ConnectivityService( 1038): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1038): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
,D/ConnectivityService( 1038): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1478): CM callback handler got msg 524290
D/ConnectivityService( 1038): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1038): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1873): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/QRemote ( 6931): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/TelephonyNetworkFactory-1( 1873):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/QRemote ( 6931): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6931): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6931): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6931): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/TelephonyIcons( 1478): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/DhcpStateMachine( 1038): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1038): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1038): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 6996): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6996): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/dhcpcd  ( 6996): version 5.5.6 starting
,E/dhcpcd  ( 6996): get_duid: m
D/dhcpcd  ( 6996): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6996): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 6996): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6996): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6996): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 6996): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 6996): wlan0: sending REQUEST (xid 0x90c18415), next in 4.26 seconds
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1038): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1038): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6447): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6447): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5565): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5565): type=WIFI subType= reason=null isConnected=true
I/ActivityManager( 1038): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7030 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 7030): onCreate
,W/AppUp4:DB( 7030):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7030):  setFingerPrint start
I/AppUp4:DB( 7030):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7030):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7030):  SDK version = 21
I/AppUp4:DB( 7030):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7030): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7030): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7030): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7030): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7030): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7030): onReceive
D/LgDataFeature( 7030): LgDataFeature() Constructor: none
D/LgDataFeature( 7030): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7030): Context : android.app.ReceiverRestrictedContext@4a2d9fe
D/AppUp4:CustFacade( 7030): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7030): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7030): begin check event
I/AppUp4:CustModeStarterReceiver( 7030): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7030): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7030): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7030): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7030): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1038): Killing 6540:com.google.android.apps.docs/u0a61 (adj 15): empty #17
D/LGDMClient( 4299): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4299): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/libprocessgroup( 1038): failed to open /acct/uid_10061/pid_6540/cgroup.procs: No such file or directory
W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3394): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4299): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4299): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 3394): DownloadService onCreate
D/LGDMClient( 4299): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4299): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/DownloadManager( 3394): in removeSpuriousFiles
V/DownloadManager( 3394): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3394): created cursor android.database.sqlite.SQLiteCursor@168875c2 on behalf of 3394
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3394): in trimDatabase
V/DownloadManager( 3394): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3394): created cursor android.database.sqlite.SQLiteCursor@2076fd3 on behalf of 3394
,I/ActivityManager( 1038): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7060 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3394): DownloadService onStartCommand,
V/DownloadManager( 3394): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4299): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,D/LGDMClient( 4299): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4299): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3394): created cursor android.database.sqlite.SQLiteCursor@266c2c0e on behalf of 3394
V/DownloadManager( 3394): processing inserted download 1
V/DownloadManager( 3394): processing inserted download 4
,V/DownloadManager( 3394): processing inserted download 7
V/DownloadManager( 3394): processing inserted download 8
V/DownloadManager( 3394): processing inserted download 9
V/DownloadManager( 3394): processing inserted download 10
V/DownloadManager( 3394): processing inserted download 16
V/DownloadManager( 3394): processing inserted download 17
V/DownloadManager( 3394): processing inserted download 18
V/DownloadManager( 3394): processing inserted download 21
V/DownloadManager( 3394): processing inserted download 22
V/DownloadManager( 3394): DownloadService onDestroy
,W/ResourcesManager( 7060): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7060): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7060): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7060): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 83141(3MB) AllocSpace objects, 7(624KB) LOS objects, 33% free, 44MB/66MB, paused 2.284ms total 158.842ms
,I/LGEmail ( 7060): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
E/WifiStateMachine( 1038):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1038): identical MTU - not setting
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1038): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1478): CM callback handler got msg 524295
D/LGEmail ( 7060): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
I/dhcpcd  ( 6996): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 6996): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 6996): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6996): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6996): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6996): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6996): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6996): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6996): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,W/ResourceType( 7060): No package identifier when getting value for resource number 0x00000000
D/LgDataFeature( 7060): LgDataFeature() Constructor: none
D/LgDataFeature( 7060): LgDataFeature() Constructor Done, null
,D/DhcpStateMachine( 1038): DHCPV4 succeeded on wlan0
D/eas_req ( 7060): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
D/LgDhcpStateMachineHelper( 1038): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1038): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1038): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
,V/LgDhcpStateMachineHelper( 1038): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1038): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1038): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1038): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1038): RunningState
I/ActivityManager( 1038): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7107 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7060): JNI_OnLoad()
I/HubEmail( 7060): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7060): registerNatives()
I/HubEmail( 7060): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7060): registerNativeMethods()
I/HubEmail( 7060): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7060): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1038): Killing 6587:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/Settings( 7060): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/libprocessgroup( 1038): failed to open /acct/uid_10080/pid_6587/cgroup.procs: No such file or directory
W/Settings( 7060): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3355): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3355): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3355): networkInfo.isConnected() = false
,I/ActivityManager( 1038): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7130 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  316): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/ActivityManager( 1038): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7150 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6209:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,I/art     (  355): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 425us total 22.731ms
,I/art     (  355): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 401us total 19.059ms
,I/art     (  355): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 406us total 18.275ms
,I/jxcore-log( 6807): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6807): 
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 116396671677; DSPS: 3954928; Offset : -4311866471
W/libprocessgroup( 1038): failed to open /acct/uid_10097/pid_6209/cgroup.procs: No such file or directory
,D/libc-netbsd(  316): res_queryN name = static-avc.lglime.com succeed
,I/ActivityManager( 1038): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7168 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1038): Killing 6612:com.lge.eula/1000 (adj 15): empty #17
E/WifiStateMachine( 1038):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 1038):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6612/cgroup.procs: No such file or directory
,I/art     ( 7168): Almond Protected OAT
,D/WeatherApplication( 7168): removeAccount
,D/WeatherApplication( 7168): Account.length = 0
E/WeatherApplication( 7168): OPERATOR:OPEN
D/WeatherAncestor( 7168): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:16:23
D/Weather.Utils( 7168): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7168): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7168): 2 : This is isUpdating : false
D/WeatherAncestor( 7168): connectivity changed - connection : true
,D/WeatherService( 7168): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7168): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7168): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7168): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7168): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7168): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:16:23
,I/ActivityManager( 1038): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7189 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1038): Killing 6057:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
V/WifiInternetCheck( 1038): Single check msg out of sync, ignoring.
,W/libprocessgroup( 1038): failed to open /acct/uid_10005/pid_6057/cgroup.procs: No such file or directory
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1038): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 5565): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/jxcore-log( 6807): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6807): 
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7189): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7189): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/jxcore-log( 6807): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6807): 
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7189): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,I/jxcore-log( 6807): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 6807): 
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7189): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/jxcore-log( 6807): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6807): 
I/WebViewFactory( 7189): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7189): Loading: webviewchromium
,I/LibraryLoader( 7189): Time to load native libraries: 7 ms (timestamps 7285-7292)
,I/LibraryLoader( 7189): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7189): Binding Chromium to main looper Looper (main, tid 1) {2c9c8661}
,I/LibraryLoader( 7189): Expected native library version number "",actual native library version number ""
I/chromium( 7189): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7189): Initializing chromium process, renderers=0
W/art     ( 7189): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7189): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7189): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7189): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  320): registerClient() client 0xb1525280, uid 10093
,W/AudioManagerAndroid( 7189): Requires BLUETOOTH permission
I/Adreno-EGL( 7189): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7189): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7189): Build Date: 12/12/14 금
I/Adreno-EGL( 7189): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7189): Remote Branch: 
I/Adreno-EGL( 7189): Local Patches: 
I/Adreno-EGL( 7189): Reconstruct Branch: 
I/NSApplication( 7189): Starting up...
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{ce677f7 type 2 when 117461 com.google.android.gms} when 117461
,V/FormManager( 7107): There are no updated forms. The schedule will be deleted.
I/ActivityManager( 1038): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7250 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1038): Killing 6653:com.lge.bnr/1000 (adj 15): empty #17
,V/FormManager( 7107): Alarm would be updated, because LastCheckTime has been updated.
W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6653/cgroup.procs: No such file or directory
,I/ActivityManager( 1038): Killing 6087:com.android.providers.calendar/u0a14 (adj 15): empty #17
,W/ResourcesManager( 7250): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/libprocessgroup( 1038): failed to open /acct/uid_10014/pid_6087/cgroup.procs: No such file or directory
,I/GLSActivity( 2141): [ac] getting account id
,I/GLSUser ( 2141): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
D/ChimeraCfgMgr( 2367): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2367): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6447): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6447): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7030): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7030): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7030): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7030): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7030): onReceive
,D/AppUp4:CustFacade( 7030): Context : android.app.ReceiverRestrictedContext@4a2d9fe
D/AppUp4:CustFacade( 7030): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7030): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7030): begin check event
I/AppUp4:CustModeStarterReceiver( 7030): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4299): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4299): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  316): res_queryN name = www.google.com, class = 1, type = 1
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3394): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3394): DownloadService onCreate
,I/DownloadManager( 3394): in removeSpuriousFiles
V/DownloadManager( 3394): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3394): created cursor android.database.sqlite.SQLiteCursor@2596943c on behalf of 3394
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
D/LGDMClient( 4299): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/DownloadManager( 3394): in trimDatabase
V/DownloadManager( 3394): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
,W/Kids    ( 2367): [AccountUtils] Account not ready
W/Kids    ( 2367): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2367): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2367): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2367): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2367): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2367): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2367): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2367): 	at java.lang.Thread.run(Thread.java:818)
I/LGDMClient( 4299): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
V/DownloadManager( 3394): created cursor android.database.sqlite.SQLiteCursor@4af95c5 on behalf of 3394
D/libc-netbsd(  316): res_queryN name = www.google.com succeed
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  316): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  316): res_queryN name = clients3.google.com succeed
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
I/LgeMiscReceiver( 3355): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3355): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3355): networkInfo.isConnected() = false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
D/LGDMClient( 4299): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4299): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/WeatherAncestor( 7168): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:16:25
,V/DownloadManager( 3394): DownloadService onStartCommand
V/DownloadManager( 3394): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/Settings( 7060): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7060): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3394): created cursor android.database.sqlite.SQLiteCursor@a56b828 on behalf of 3394
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{1585aee6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/Weather.Utils( 7168): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7168): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7168): 2 : This is isUpdating : false
D/WeatherAncestor( 7168): connectivity changed - connection : true
D/WeatherService( 7168): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@20864bac
D/ForecastDataCache( 7168): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7168): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7168): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7168): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 7168): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:16:25
W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/CloudHub( 2236): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19987
E/LGDMClient( 4299): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4299): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4299): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3394): processing inserted download 1
,V/DownloadManager( 3394): processing inserted download 4
V/WifiInternetCheck( 1038): isHttpConnectionAvailable - We got a valid response : 204
V/DownloadManager( 3394): processing inserted download 7
V/DownloadManager( 3394): processing inserted download 8
V/DownloadManager( 3394): processing inserted download 9
V/DownloadManager( 3394): processing inserted download 10
V/DownloadManager( 3394): processing inserted download 16
V/DownloadManager( 3394): processing inserted download 17
V/DownloadManager( 3394): processing inserted download 18
,V/DownloadManager( 3394): processing inserted download 21
V/DownloadManager( 3394): processing inserted download 22
V/DownloadManager( 3394): DownloadService onDestroy
D/ChimeraCfgMgr( 2367): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6447): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6447): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/UEI.SmartControl( 6631): Internal timer expired: 2
D/UEI.SmartControl( 6631): unbind internal service
,V/FormManager( 7107): There are no updated forms. The schedule will be deleted.
V/FormManager( 7107): Alarm would be updated, because LastCheckTime has been updated.
,I/NetworkStateForAutoUpdateMonitor( 7030): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7030): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7030): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7030): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7030): onReceive
,D/AppUp4:CustFacade( 7030): Context : android.app.ReceiverRestrictedContext@4a2d9fe
D/AppUp4:CustFacade( 7030): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7030): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7030): begin check event
I/AppUp4:CustModeStarterReceiver( 7030): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/LGDMClient( 4299): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LGDMClient( 4299): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3394): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4299): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3394): DownloadService onCreate
I/DownloadManager( 3394): in removeSpuriousFiles
V/DownloadManager( 3394): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3394): created cursor android.database.sqlite.SQLiteCursor@1585aee6 on behalf of 3394
,I/LGDMClient( 4299): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4299): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
D/LGDMClient( 4299): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3394): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3394): in trimDatabase
V/DownloadManager( 3394): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/DownloadManager( 3394): created cursor android.database.sqlite.SQLiteCursor@1119bc27 on behalf of 3394
W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
W/Settings( 7060): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Kids    ( 2367): [AccountUtils] Account not ready
W/Kids    ( 2367): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2367): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2367): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2367): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2367): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2367): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2367): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2367): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
V/DownloadManager( 3394): DownloadService onStartCommand
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
V/DownloadManager( 3394): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
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
E/LGDMClient( 4299): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/serial_port( 6631): close(fd = 24)
D/LGDMClient( 4299): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4299): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
W/Settings( 7060): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
I/UEI.SmartControl( 6631): Serial port is closed.
V/DownloadManager( 3394): created cursor android.database.sqlite.SQLiteCursor@36dd372 on behalf of 3394
I/LgeMiscReceiver( 3355): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3355): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3355): networkInfo.isConnected() = true
D/PhoneState( 3355): setPdpRejectCasuse : false
V/DownloadManager( 3394): processing inserted download 1
V/DownloadManager( 3394): processing inserted download 4
V/DownloadManager( 3394): processing inserted download 7
,V/DownloadManager( 3394): processing inserted download 8
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
V/DownloadManager( 3394): processing inserted download 9
V/DownloadManager( 3394): processing inserted download 10
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{1585aee6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/DownloadManager( 3394): processing inserted download 16
V/DownloadManager( 3394): processing inserted download 17
V/DownloadManager( 3394): processing inserted download 18
V/DownloadManager( 3394): processing inserted download 21
D/WeatherAncestor( 7168): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:16:25
V/DownloadManager( 3394): processing inserted download 22
D/Weather.Utils( 7168): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7168): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7168): 2 : This is isUpdating : false
D/WeatherAncestor( 7168): connectivity changed - connection : true
D/WeatherService( 7168): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@20864bac
D/ForecastDataCache( 7168): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7168): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7168): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7168): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7168): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:16:25
V/DownloadManager( 3394): DownloadService onDestroy
,V/FormManager( 7107): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7107): Alarm would be updated, because LastCheckTime has been updated.
D/ChimeraCfgMgr( 2367): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  316): res_queryN name = mtalk.google.com, class = 1, type = 1
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
,D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/libc-netbsd(  316): res_queryN name = mtalk.google.com succeed
W/Kids    ( 2367): [AccountUtils] Account not ready
W/Kids    ( 2367): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2367): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2367): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2367): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2367): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2367): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2367): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2367): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
,D/LgeQuickCoverNotificationData( 1419): showAll3
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
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{1585aee6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/GCM     ( 2141): Connected
,D/GCM     ( 2141): Message class com.google.f.a.a.p
I/jxcore-log( 6807): Test app app.js loaded
I/jxcore-log( 6807): 
,I/chromium( 6807): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6807): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6807): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6807): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6807): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6807): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6807): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6807): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6807): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6807): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6807): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38e489ac added. We now have 1 listener(s)
,I/jxcore-log( 6807): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6807): 
I/GAV4    ( 7189): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1038): Killing 6714:com.google.android.apps.books/u0a54 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10054/pid_6714/cgroup.procs: No such file or directory
,I/[SystemUI]LGPowerUI( 1478): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1478): On Skip Timer : true
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1038): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1478): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 299
D/LEDHandler( 1969): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1969): Battery Level Remaining: 100%
D/LEDHandler( 1969): Battery Temp: 299, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 3811): Disconnected process message: 10, size: 0
I/[SystemUI]LGPowerUI( 1478): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1478): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4299): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4299): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{27f13251 type 2 when 132913 android} when 132913
,V/QRemote ( 6931): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,D/QRemote ( 6931): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:5809
V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{75073b7 type 0 when 1454422600578 com.android.vending} when 1454422600578
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 36509(1714KB) AllocSpace objects, 3(432KB) LOS objects, 33% free, 44MB/66MB, paused 3.345ms total 163.563ms
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6235): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6235): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6235): [1] 5.onFinished: Scheduling replication attempt 3.
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 136398970628; DSPS: 4610363; Offset : -4311857667
,I/CloudHub( 2236): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,I/CloudHub( 2236): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,I/[SystemUI]TimeTickManager( 1478): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1478): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1478): called onTimeUpdated()
,I/[SystemUI]Clock( 1478): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1478): handleTimeUpdate
,E/WifiStateMachine( 1038):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1038):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1038):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1038):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 156401045256; DSPS: 5265791; Offset : -4311858130
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=50998299, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{2f7bcd66 type 0 when 1454422622561 com.android.vending} when 1454422622561
,D/[Concierge]Service( 2591): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=50998299 [*alarm*], flags=0x0
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6235): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6235): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6235): [1] 5.onFinished: Scheduling replication attempt 4.
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{2875d8 type 2 when 172029 android} when 172029
,I/ActivityManager( 1038): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=7371 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ReaderUtils( 7371): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,W/GAV2    ( 7371): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 7371): Created application version: 3.2.35 (30235)
,I/BooksSync( 7371): Starting books sync
,D/BooksSync( 7371): started syncMyEbooks
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
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
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/BooksAccountManager( 7371): Authentication error
E/BooksAccountManager( 7371): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7371): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7371): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7371): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7371): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7371): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7371): null auth token
,E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  316): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{1585aee6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  316): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7371): Error response from books API: {
W/ApiaryClient( 7371):  "error": {
W/ApiaryClient( 7371):   "errors": [
W/ApiaryClient( 7371):    {
W/ApiaryClient( 7371):     "domain": "global",
W/ApiaryClient( 7371):     "reason": "required",
W/ApiaryClient( 7371):     "message": "Login Required",
W/ApiaryClient( 7371):     "locationType": "header",
W/ApiaryClient( 7371):     "location": "Authorization"
W/ApiaryClient( 7371):    }
W/ApiaryClient( 7371):   ],
W/ApiaryClient( 7371):   "code": 401,
W/ApiaryClient( 7371):   "message": "Login Required"
W/ApiaryClient( 7371):  }
W/ApiaryClient( 7371): }
,W/ApiaryClient( 7371): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7371): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6328221920366674310&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7371): Headers:
W/ApiaryClient( 7371): accept-encoding: [gzip]
W/ApiaryClient( 7371): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7371): gdata-version: 2
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/ResourcesManager( 1419): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1419): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7371): Authentication error
E/BooksAccountManager( 7371): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7371): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7371): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7371): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7371): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7371): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7371): null auth token
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
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1419): Notification difference=198
,D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{1585aee6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7371): Error response from books API: {
W/ApiaryClient( 7371):  "error": {
W/ApiaryClient( 7371):   "errors": [
W/ApiaryClient( 7371):    {
W/ApiaryClient( 7371):     "domain": "global",
W/ApiaryClient( 7371):     "reason": "required",
W/ApiaryClient( 7371):     "message": "Login Required",
W/ApiaryClient( 7371):     "locationType": "header",
W/ApiaryClient( 7371):     "location": "Authorization"
W/ApiaryClient( 7371):    }
W/ApiaryClient( 7371):   ],
W/ApiaryClient( 7371):   "code": 401,
W/ApiaryClient( 7371):   "message": "Login Required"
W/ApiaryClient( 7371):  }
W/ApiaryClient( 7371): }
,W/ApiaryClient( 7371): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7371): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6328221920366674310&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7371): Headers:
W/ApiaryClient( 7371): accept-encoding: [gzip]
W/ApiaryClient( 7371): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7371): gdata-version: 2
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7371): Authentication error
E/BooksAccountManager( 7371): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7371): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7371): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7371): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7371): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7371): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7371): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{1585aee6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7371): Error response from books API: {
W/ApiaryClient( 7371):  "error": {
W/ApiaryClient( 7371):   "errors": [
W/ApiaryClient( 7371):    {
W/ApiaryClient( 7371):     "domain": "global",
W/ApiaryClient( 7371):     "reason": "required",
W/ApiaryClient( 7371):     "message": "Login Required",
W/ApiaryClient( 7371):     "locationType": "header",
W/ApiaryClient( 7371):     "location": "Authorization"
W/ApiaryClient( 7371):    }
W/ApiaryClient( 7371):   ],
W/ApiaryClient( 7371):   "code": 401,
W/ApiaryClient( 7371):   "message": "Login Required"
W/ApiaryClient( 7371):  }
W/ApiaryClient( 7371): }
,W/ApiaryClient( 7371): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7371): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6328221920366674310&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7371): Headers:
W/ApiaryClient( 7371): accept-encoding: [gzip]
W/ApiaryClient( 7371): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7371): gdata-version: 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 176403047123; DSPS: 5921217; Offset : -4311870528
,E/BooksSync( 7371): Soft error: 
E/BooksSync( 7371): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7371): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6328221920366674310&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7371): Headers:
E/BooksSync( 7371): accept-encoding: [gzip]
E/BooksSync( 7371): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7371): gdata-version: 2
E/BooksSync( 7371): 
E/BooksSync( 7371): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7371): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7371): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7371): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7371): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7371): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7371): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7371): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7371): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7371): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7371): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7371): {
E/BooksSync( 7371):  "error": {
E/BooksSync( 7371):   "errors": [
E/BooksSync( 7371):    {
E/BooksSync( 7371):     "domain": "global",
E/BooksSync( 7371):     "reason": "required",
E/BooksSync( 7371):     "message": "Login Required",
E/BooksSync( 7371):     "locationType": "header",
E/BooksSync( 7371):     "location": "Authorization"
E/BooksSync( 7371):    }
E/BooksSync( 7371):   ],
E/BooksSync( 7371):   "code": 401,
E/BooksSync( 7371):   "message": "Login Required"
E/BooksSync( 7371):  }
E/BooksSync( 7371): }
E/BooksSync( 7371): 
E/BooksSync( 7371): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7371): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7371): 	... 8 more
,E/BooksSync( 7371): Sync error
E/BooksSync( 7371): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7371): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6328221920366674310&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7371): Headers:
E/BooksSync( 7371): accept-encoding: [gzip]
E/BooksSync( 7371): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7371): gdata-version: 2
E/BooksSync( 7371): 
E/BooksSync( 7371): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7371): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7371): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7371): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7371): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7371): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7371): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7371): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7371): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7371): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7371): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7371): {
E/BooksSync( 7371):  "error": {
E/BooksSync( 7371):   "errors": [
E/BooksSync( 7371):    {
E/BooksSync( 7371):     "domain": "global",
E/BooksSync( 7371):     "reason": "required",
E/BooksSync( 7371):     "message": "Login Required",
E/BooksSync( 7371):     "locationType": "header",
E/BooksSync( 7371):     "location": "Authorization"
E/BooksSync( 7371):    }
E/BooksSync( 7371):   ],
E/BooksSync( 7371):   "code": 401,
E/BooksSync( 7371):   "message": "Login Required"
E/BooksSync( 7371):  }
E/BooksSync( 7371): }
E/BooksSync( 7371): 
E/BooksSync( 7371): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7371): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7371): 	... 8 more
I/BooksSync( 7371): Finished books sync
I/ActivityManager( 1038): Killing 2236:com.lge.music/u0a34 (adj 15): empty #17
,D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 172029, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/AudioFlinger(  320): 2236 died, releasing its sessions
V/AudioFlinger(  320):  pid 1873 @ 0
V/AudioFlinger(  320):  pid 3355 @ 1
V/AudioFlinger(  320):  pid 3355 @ 2
,W/libprocessgroup( 1038): failed to open /acct/uid_10034/pid_2236/cgroup.procs: No such file or directory
,I/GAV2    ( 7371): Thread[GAThread,5,main]: No campaign data found.
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 196405072428; DSPS: 6576643; Offset : -4311859226
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{15afd214 type 0 when 1454422656567 com.android.vending} when 1454422656567
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6235): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6235): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6235): [1] 5.onFinished: Scheduling replication attempt 5.
V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{29030ed6 type 2 when 202190 android} when 202190
,I/[SystemUI]TimeTickManager( 1478): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1478): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1478): called onTimeUpdated()
,I/[SystemUI]Clock( 1478): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1478): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 216406823357; DSPS: 7232061; Offset : -4311878343
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{3456b557 type 2 when 211047 android} when 211047
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{c75e844 type 2 when 189065 com.google.android.gms} when 189065
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{20f94262 type 0 when 1454422687277 com.android.vending} when 1454422687277
D/[Concierge]Service( 2591): onStartCommand(). Type : 9
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2141): Explicit concurrent mark sweep GC freed 35399(2MB) AllocSpace objects, 20(2MB) LOS objects, 51% free, 30MB/62MB, paused 1.631ms total 71.944ms
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,I/VacuumService( 2141): Vacuum at: now=1454422695912 tag=VacuumService
,I/GoogleURLConnFactory( 2141): Using platform SSLCertificateSocketFactory
,W/Uploader( 2141): No account for auth token provided
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  316): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  316): res_queryN name = play.googleapis.com succeed
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6235): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6235): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6235): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 2141): No account for auth token provided
,W/Uploader( 2141): No account for auth token provided
,W/Uploader( 2141): No account for auth token provided
,W/Uploader( 2141):  no longer exists, so no auth token.
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 24823(1038KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 3.295ms total 156.677ms
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 236408871735; DSPS: 7887488; Offset : -4311874591
,I/[SystemUI]LGPowerUI( 1478): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1478): On Skip Timer : true
,D/LEDHandler( 1969): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1969): Battery Level Remaining: 100%
D/LEDHandler( 1969): Battery Temp: 292, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1478): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
,I/[SystemUI]LGPowerUI( 1478): onReceive = android.intent.action.BATTERY_CHANGED
,D/WifiController( 1038): battery changed pluggedType: 2
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3811): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1478): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4299): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4299): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 256411026572; DSPS: 8542918; Offset : -4311855984
,I/[SystemUI]TimeTickManager( 1478): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1478): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1478): called onTimeUpdated()
,I/[SystemUI]Clock( 1478): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1478): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 276412911825; DSPS: 9198340; Offset : -4311863055
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 296414980306; DSPS: 9853768; Offset : -4311869587
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=50998299, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{188b876a type 2 when 305855 android} when 305855
D/[Concierge]Service( 2591): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=50998299 [*alarm*], flags=0x0
,I/BooksSync( 7371): Starting books sync
,D/BooksSync( 7371): started syncMyEbooks
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7371): Authentication error
E/BooksAccountManager( 7371): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7371): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7371): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7371): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7371): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7371): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7371): null auth token
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
,D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
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
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{1585aee6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7371): Error response from books API: {
W/ApiaryClient( 7371):  "error": {
W/ApiaryClient( 7371):   "errors": [
W/ApiaryClient( 7371):    {
W/ApiaryClient( 7371):     "domain": "global",
W/ApiaryClient( 7371):     "reason": "required",
W/ApiaryClient( 7371):     "message": "Login Required",
W/ApiaryClient( 7371):     "locationType": "header",
W/ApiaryClient( 7371):     "location": "Authorization"
W/ApiaryClient( 7371):    }
W/ApiaryClient( 7371):   ],
W/ApiaryClient( 7371):   "code": 401,
W/ApiaryClient( 7371):   "message": "Login Required"
W/ApiaryClient( 7371):  }
W/ApiaryClient( 7371): }
W/ApiaryClient( 7371): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7371): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4948240855916544178&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7371): Headers:
W/ApiaryClient( 7371): accept-encoding: [gzip]
W/ApiaryClient( 7371): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7371): gdata-version: 2
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{1585aee6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/BooksAccountManager( 7371): Authentication error
E/BooksAccountManager( 7371): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7371): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7371): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7371): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7371): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7371): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7371): null auth token
,W/ApiaryClient( 7371): Error response from books API: {
W/ApiaryClient( 7371):  "error": {
W/ApiaryClient( 7371):   "errors": [
W/ApiaryClient( 7371):    {
W/ApiaryClient( 7371):     "domain": "global",
W/ApiaryClient( 7371):     "reason": "required",
W/ApiaryClient( 7371):     "message": "Login Required",
W/ApiaryClient( 7371):     "locationType": "header",
W/ApiaryClient( 7371):     "location": "Authorization"
W/ApiaryClient( 7371):    }
W/ApiaryClient( 7371):   ],
W/ApiaryClient( 7371):   "code": 401,
W/ApiaryClient( 7371):   "message": "Login Required"
W/ApiaryClient( 7371):  }
W/ApiaryClient( 7371): }
,W/ApiaryClient( 7371): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7371): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4948240855916544178&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7371): Headers:
W/ApiaryClient( 7371): accept-encoding: [gzip]
W/ApiaryClient( 7371): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7371): gdata-version: 2
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7371): Authentication error
E/BooksAccountManager( 7371): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7371): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7371): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7371): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7371): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7371): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7371): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{1585aee6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7371): Error response from books API: {
W/ApiaryClient( 7371):  "error": {
W/ApiaryClient( 7371):   "errors": [
W/ApiaryClient( 7371):    {
W/ApiaryClient( 7371):     "domain": "global",
W/ApiaryClient( 7371):     "reason": "required",
W/ApiaryClient( 7371):     "message": "Login Required",
W/ApiaryClient( 7371):     "locationType": "header",
W/ApiaryClient( 7371):     "location": "Authorization"
W/ApiaryClient( 7371):    }
W/ApiaryClient( 7371):   ],
W/ApiaryClient( 7371):   "code": 401,
W/ApiaryClient( 7371):   "message": "Login Required"
W/ApiaryClient( 7371):  }
W/ApiaryClient( 7371): }
,W/ApiaryClient( 7371): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7371): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4948240855916544178&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7371): Headers:
W/ApiaryClient( 7371): accept-encoding: [gzip]
W/ApiaryClient( 7371): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7371): gdata-version: 2
,E/BooksSync( 7371): Soft error: 
E/BooksSync( 7371): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7371): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4948240855916544178&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7371): Headers:
E/BooksSync( 7371): accept-encoding: [gzip]
E/BooksSync( 7371): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7371): gdata-version: 2
E/BooksSync( 7371): 
E/BooksSync( 7371): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7371): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7371): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7371): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7371): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7371): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7371): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7371): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7371): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7371): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7371): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7371): {
E/BooksSync( 7371):  "error": {
E/BooksSync( 7371):   "errors": [
E/BooksSync( 7371):    {
E/BooksSync( 7371):     "domain": "global",
E/BooksSync( 7371):     "reason": "required",
E/BooksSync( 7371):     "message": "Login Required",
E/BooksSync( 7371):     "locationType": "header",
E/BooksSync( 7371):     "location": "Authorization"
E/BooksSync( 7371):    }
E/BooksSync( 7371):   ],
E/BooksSync( 7371):   "code": 401,
E/BooksSync( 7371):   "message": "Login Required"
E/BooksSync( 7371):  }
E/BooksSync( 7371): }
E/BooksSync( 7371): 
E/BooksSync( 7371): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7371): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7371): 	... 8 more
,E/BooksSync( 7371): Sync error
E/BooksSync( 7371): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7371): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4948240855916544178&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7371): Headers:
E/BooksSync( 7371): accept-encoding: [gzip]
E/BooksSync( 7371): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7371): gdata-version: 2
E/BooksSync( 7371): 
E/BooksSync( 7371): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7371): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7371): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7371): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7371): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7371): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7371): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7371): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7371): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7371): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7371): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7371): {
E/BooksSync( 7371):  "error": {
E/BooksSync( 7371):   "errors": [
E/BooksSync( 7371):    {
E/BooksSync( 7371):     "domain": "global",
E/BooksSync( 7371):     "reason": "required",
E/BooksSync( 7371):     "message": "Login Required",
E/BooksSync( 7371):     "locationType": "header",
E/BooksSync( 7371):     "location": "Authorization"
E/BooksSync( 7371):    }
E/BooksSync( 7371):   ],
E/BooksSync( 7371):   "code": 401,
E/BooksSync( 7371):   "message": "Login Required"
E/BooksSync( 7371):  }
E/BooksSync( 7371): }
E/BooksSync( 7371): 
E/BooksSync( 7371): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7371): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7371): 	... 8 more
I/BooksSync( 7371): Finished books sync
D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 305855, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 316416372955; DSPS: 10509174; Offset : -4311880981
,I/[SystemUI]TimeTickManager( 1478): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1478): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1478): called onTimeUpdated()
,I/[SystemUI]Clock( 1478): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1478): called onTimeUpdated()
,I/[SystemUI]DateView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1478): handleTimeUpdate
D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=50998299, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{19ef7904 type 2 when 336158 android} when 336158
D/[Concierge]Service( 2591): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=50998299 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 336418258468; DSPS: 11164595; Offset : -4311856702
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 356420406482; DSPS: 11820026; Offset : -4311875670,
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 6235): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6235): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6235): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6235): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6235): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6235): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6235): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{1585aee6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/System  ( 6235): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  316): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  316): res_queryN name = play.googleapis.com succeed
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 376422572411; DSPS: 12475457; Offset : -4311876437
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=50998299, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,D/[Concierge]Service( 2591): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1478): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1478): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1478): called onTimeUpdated()
I/[SystemUI]Clock( 1478): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1478): handleTimeUpdate
D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=50998299 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 396424552873; DSPS: 13130882; Offset : -4311879488
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 416426642969; DSPS: 13786310; Offset : -4311864795
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 436428464054; DSPS: 14441730; Offset : -4311874661
,I/wpa_supplicant( 2801): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
E/WifiMonitor( 1038): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/WifiMonitor( 1038): handleNetworkStateChange: Could not parse disconnect string
E/WifiMonitor( 1038): WifiMonitor notify network disconnect: null reason=0
D/Tethering( 1038): InitialState.processMessage what=4
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1038):  ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=441841
E/WifiStateMachine( 1038):  L2ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=441842
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=441842
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
,D/Tethering( 1038): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2801): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/DhcpStateMachine( 1038): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  316): Clearing all IP addresses on wlan0
,V/NativeCrypto( 2141): Read error: ssl=0xaa6d5a00: I/O error during system call, Connection timed out
V/NativeCrypto( 2141): SSL shutdown failed: ssl=0xaa6d5a00: I/O error during system call, Broken pipe
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,I/jxcore-log( 6807): Toggling radios to false
I/jxcore-log( 6807): 
,I/wpa_supplicant( 2801): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/ConnectivityService( 1038): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on "NG700"
,D/UsbSettingsReceiver( 6886): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6886): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6886): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6886): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6886): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1038): ignoring duplicate network state non-change
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1038): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@25e6e07 mBinding = false
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=0
,D/WifiHS20( 1038): hidePasspointNotification off =false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/DSQN    ( 1038): Dns fail occured do internet check.
V/WfdStateTracker( 1969): handleWifiStateChangedEvent: 0
D/DSQN    ( 1038): EVENT_INTERNET_CHECK_REQUEST received
D/DSQN    ( 1038): try Internet connection check
E/WifiStateMachine( 1038): WifiStateMachine: Leaving Connected state
,E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=442004  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=442005  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1038):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=442010  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/WifiHS20( 1038): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=442023  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1038): NetworkAgent: NetworkAgent channel lost
,D/LocationManagerService( 1038): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1038): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Ulp_jni ( 1038): JNI:system_update. Event-4
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/UsbSettingsControl( 6886): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6886): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6886): [AUTORUN] onReceive() : activeList=[]
D/WifiServiceImplEx( 1038): setWifiEnabled: false pid=6807, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/UsbSettingsReceiver( 6886): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6886): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/WifiService( 1038): setWifiEnabled: false pid=6807, uid=10311
E/WifiService( 1038): Invoking mWifiStateMachine.setWifiEnabled
D/UsbSettingsControl( 6886): [AUTORUN] setTetherStatus() : status=false
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateSCANNING
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/BluetoothManagerService( 1038): Message: 2
D/BluetoothManagerService( 1038): Sending off request.
D/LGBluetoothServiceAdapter( 3811): [BTUI] Precleanup
D/BluetoothAdapterState( 3811): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3811): Setting state to 13
I/BluetoothAdapterState( 3811): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 3811): onBluetoothDisable()
D/BluetoothManagerService( 1038): Message: 60
I/BluetoothAdapterState( 3811): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/PostponalbeReceiver( 6447): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/BluetoothManagerService( 1038): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1038): Bluetooth State Change Intent: 12 -> 13
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
I/jxcore-log( 6807): Radios toggled
I/jxcore-log( 6807): 
E/WifiStateMachine( 1038):  DisconnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
,D/LocationManagerService( 1038): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1038): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1038): JNI:system_update. Event-4
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/LGBluetoothAPIService( 1969): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/BluetoothMapService( 3811): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 3811): STATE_TURNING_OFF
V/BluetoothMapService( 3811): Handler(): got msg=4
D/BluetoothMapService( 3811): MAP Service closeService in
D/BluetoothMapMasInstance( 3811): MAP Service shutdown
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
V/BluetoothMapMasInstance( 3811): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3811): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3811): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 3811): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 3811): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 3811): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3811): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3811): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LGBluetoothMapAdapter( 3811): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3811): MAP Service closeService out
D/ConnectivityService( 1038): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1038): disableDataServiceNotify
D/DSQN    ( 1038): stop dsqn bin
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=0
V/BtOppService( 3811): Receiver DISABLED_ACTION 
I/BtOppRfcommListener( 3811): stopping Accept Thread
V/BtOppRfcommListener( 3811): close mBtServerSocket
V/BtOppRfcommListener( 3811): waiting for thread to terminate
E/BtOppRfcommListener( 3811): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/DSQN    ( 1038): ThreadTCPConnectionCheck DNS fail internet is not possible
I/BtOppRfcommListener( 3811): BluetoothSocket listen thread finished
D/DSQN    ( 1038): ThreadInternetCheck internet check NOK 
D/DSQN    ( 1038): InternetcheckProgress is not set don't send DS quality intent
V/BtOppRfcommListener( 3811): done waiting for thread to terminate
D/DSQN    ( 1038): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/[SystemUI]BluetoothHandler( 1478): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/BluetoothAdapterProperties( 3811): Scan Mode:20
D/BluetoothAdapterState( 3811): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
V/BtOppService( 3811): onDestroy
V/BluetoothPbapService( 3811): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothFtpService:RfcommSocketAcceptThread( 3811): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothSapService( 3811): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/btif_config_util( 3811): btif_config_save_file(L188): in file name:/data/misc/bluedroi,d/bt_config.new
,D/ConnectivityService( 1038): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
W/bt-l2cap( 3811): L2CAP - L2CA_Deregister() called for PSM: 0x000f
W/bt-btif ( 3811): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
D/ConnectivityManager.CallbackHandler( 1478): CM callback handler got msg 524292
W/bt-l2cap( 3811): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3811): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3811): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3811): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3811): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 3811): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3811): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3811): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3811): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3811): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3811): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 3811): bta_gattc_deregister Deregister Failedm unknown client cif
W/ContextImpl( 6886): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Disconnected - quitting
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/CSLegacyTypeTracker( 1038): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
I/PCSuite ( 6907): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/CSLegacyTypeTracker( 1038): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/PCSuite ( 6907): [StartReceiver][getUpdateNecessity]update = false
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PCSuite ( 6907): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/LGBluetoothOppAdapter( 3811): [BTUI] LGBluetoothOppAdapter cleanup
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/WifiMonitor( 1038): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2fa16f0d
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/LGWifiP2pService( 1038): P2pDisablingState
D/ConnectivityService( 1038): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/LGWifiP2pService( 1038): P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): p2p socket connection lost
D/LGWifiP2pService( 1038): P2pDisabledState
E/WifiStateMachine( 1038):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2801): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1038): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/CommandListener(  316): Clearing all IP addresses on wlan0
D/TelephonyNetworkFactory-1( 1873): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiScanningService( 1038): SCAN_AVAILABLE : 1
D/RttService( 1038): SCAN_AVAILABLE : 1
D/TelephonyNetworkFactory-1( 1873):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/RttService( 1038): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService( 1038): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/NetworkManagementService( 1038): Removing idletimer
W/Settings( 1038): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1038): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/BluetoothManagerService( 1038): Message: 20
D/BluetoothManagerService( 1038): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@260016d2:true
V/WfdStateTracker( 1969): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsService( 1969): WifiP2pState is changed : false
D/WfdsService( 1969): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1969): Set the WFDS Monitor: false
D/WifiHS20( 1038): hidePasspointNotification off =false
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-p2p0( 1038): doBoolean: TERMINATE
D/WifiNative-p2p0( 1038): TERMINATE: returned true
E/WifiStateMachine( 1038): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1038): useWiFiOffloading() : false
E/WifiStateMachine( 1038): CONFIG_LGE_WLAN_PATH : true
D/WIFI    ( 1038): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/BluetoothManagerService( 1038): Message: 30
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,V/WfdStateTracker( 1969): WfdStateTracker handleDirectStateChangedEvent: 6
D/WfdsMonitor( 1969): WFDS Monitor is stopped
D/WfdsService( 1969): STATE : WfdsDisabledState - enter
W/WfdsSession:Controller( 1969): DefaultState - msg [9441355] is not handled
D/CtrlSupplicant( 1969): Received on exit socket, terminate
E/CtrlSupplicant( 1969): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1969): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1969): WfdsMonitorThread is received the interrupt - closing
W/WfdsService( 1969): DefaultState - msg [9445378] is not handled
V/BluetoothPbapReceiver( 3811): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3811): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
I/WifiServerServiceExt( 1038): WIFI_STATE_CHANGED_ACTION [0]
V/BluetoothPbapReceiver( 3811): ***********state = 13
V/BluetoothPbapReceiver( 3811): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3811): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 3811): state: 13
V/BluetoothPbapService( 3811): Pbap Service closeService in
V/BluetoothPbapService( 3811): successfully stopped pbap service
V/BluetoothPbapService( 3811): Pbap Service closeService out
V/BluetoothPbapService( 3811): Pbap Service onDestroy
V/BluetoothPbapService( 3811): Pbap Service closeService in
V/BluetoothPbapService( 3811): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 3811): [BTUI] cleanup
D/BluetoothManagerService( 1038): Message: 30
D/LocalBluetoothProfileManager( 6886): Adding local MAP profile
,D/BluetoothMap( 6886): Create BluetoothMap proxy object
D/BluetoothManagerService( 1038): Message: 30
,I/ActivityManager( 1038): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7575 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
D/DhcpStateMachine( 1038): StoppedState
D/DhcpStateMachine( 1038): StoppedState{ when=-74ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService( 1038): Message: 30
E/WifiStateMachine( 1038):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_ON_QUIT 0 0
D/LocalBluetoothProfileManager( 6886): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 6886):  get() - isFeatureLoaded : false
,D/TelephonyIcons( 1478): null signal icon name: drawable/stat_sys_signal_null
,D/LGBluetoothUserBindClient( 6886): [BTUI] initUserBindClient
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ContextImpl( 6886): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 6886): finishStartingService: stopping service
V/WiFiOffLoadBroadcast( 6886): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6886): MCCMNC not supported: null
D/BluetoothInputDevice( 6886): Proxy object connected
D/HidProfile( 6886): Bluetooth service connected
D/BluetoothPan( 6886): BluetoothPAN Proxy object connected
D/PanProfile( 6886): Bluetooth service connected
D/TelephonyIcons( 1478): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/BluetoothMap( 6886): Proxy object connected
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/MapProfile( 6886): Bluetooth service connected
D/BluetoothMap( 6886): getConnectedDevices()
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/BluetoothMap( 6886): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 6886): [BTUI] onServiceConnected
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/QRemote ( 6931): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6931): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6931): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6447): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6907): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6907): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6907): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6886): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6886): MCCMNC not supported: null
D/QRemote ( 6931): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6931): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6931): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/PostponalbeReceiver( 6447): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
I/PCSuite ( 6907): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6907): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6907): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6886): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,E/ActivityThread( 7575): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 7575): No ProfileInfo entries
I/LG Account v2.2( 7575): isEnabled: false
I/Feature ( 7575): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 7575): [Lifetracker]Country: EU
I/Feature ( 7575): [Lifetracker]Operator: OPEN
I/Feature ( 7575): [Lifetracker]Ranking support: false
I/Feature ( 7575): [Lifetracker]Comfort support: false
I/Feature ( 7575): [Lifetracker]Accessory: true
I/Feature ( 7575): [Lifetracker]Health device: true
I/Feature ( 7575): [Lifetracker]Extra Pedometer: false
I/Feature ( 7575): [Lifetracker]Blood glucose device: false
I/Feature ( 7575): [Lifetracker]Device Number: 3
D/WiFiOffLoadBroadcast( 6886): MCCMNC not supported: null
D/LGBluetoothAuthorization( 6886): [BTUI] cancel All Notification
D/BluetoothPermissionRequest( 6886): onReceive
D/LGBluetoothAuthorization( 6886): [BTUI] cancel All Notification
D/LGBluetoothResetSettingReceiver( 6886): return without doing reset settings.
I/ActivityManager( 1038): Killing 7030:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10011/pid_7030/cgroup.procs: No such file or directory
,V/BluetoothOppReceiver( 3811): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 3811): [BTUI] cancel opp incoming file confirm notification
D/BluetoothOppNotification( 3811): [BTUI] cancel opp active transfer file notification
D/QRemote ( 6931): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6931): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
V/BluetoothFtpReceiver( 3811): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 3811): BluetoothFtpReceiver Start Service
I/QRemote ( 6931): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/BluetoothFtpService( 3811): Ftp Service onStartCommand
V/BluetoothFtpService( 3811): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 3811): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 3811): Shutdown
,D/PostponalbeReceiver( 6447): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/BluetoothFtpService( 3811): successfully stopped ftp service
V/BluetoothFtpService( 3811): Ftp Service onDestroy
V/BluetoothFtpService( 3811): Ftp Service closeService
,V/BluetoothSapReceiver( 3811): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 3811): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 3811): SapReceiver onReceive 
V/BluetoothSapReceiver( 3811): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3811):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3811): Calling SAP service start service with action = null
V/BluetoothSapService( 3811): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3811): state: 13
V/BluetoothSapService( 3811): Stopping SAP server process
V/BluetoothSapService( 3811): Sap Service closeSapService in
V/BluetoothSapService( 3811): Close listen Socket : 
V/WiFiOffLoadBroadcast( 6886): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/BluetoothSapService( 3811): Close rfcomm Socket : 
V/BluetoothSapService( 3811): Close sapd  Socket : 
,D/WiFiOffLoadBroadcast( 6886): MCCMNC not supported: null
,I/ActivityManager( 1038): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7601 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
V/BluetoothSapService( 3811): Sap Service closeSapService out
V/BluetoothSapService( 3811): Sap Service onDestroy
V/BluetoothSapService( 3811): Sap Service closeSapService in
,V/BluetoothSapService( 3811): Close listen Socket : 
V/BluetoothSapService( 3811): Close rfcomm Socket : 
V/BluetoothSapService( 3811): Close sapd  Socket : 
V/BluetoothSapService( 3811): Sap Service closeSapService out
D/QRemote ( 6931): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6931): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6931): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6447): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6907): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6907): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6907): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6886): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6886): MCCMNC not supported: null
D/QRemote ( 6931): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6931): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6931): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6447): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ResourcesManager( 7601): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/PCSuite ( 6907): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6907): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6907): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6886): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/AuthorizationBluetoothService( 2141): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/WiFiOffLoadBroadcast( 6886): MCCMNC not supported: null
,D/QRemote ( 6931): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6931): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6931): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PCSuite ( 6907): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6886): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,W/FormManager( 7107): Network not available. Please check & try again.
,V/FormManager( 7107): Network unavailable.
,V/FormManager( 7107): Network unavailable.
D/WiFiOffLoadBroadcast( 6886): MCCMNC not supported: null
I/ActivityManager( 1038): Killing 7060:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10023/pid_7060/cgroup.procs: No such file or directory
,D/DSQN    ( 1038): EVENT_INTERNET_CHECK_ENABLE received
,D/bt_hci_bdroid( 3811): cleanup
I/bt_lpm  ( 3811): LPM is already off!!!
I/bt_userial_mct( 3811): exiting userial_read_thread
D/bt_userial_mct( 3811): Leaving userial_evt_read_thread()
W/bt-btif ( 3811): ag scb idx 1 not allocated
E/bt-btif ( 3811): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3811): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3811): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3811): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3811): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3811): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3811): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3811): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3811): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3811): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3811): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3811): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3811): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3811): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3811): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3811): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3811): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3811): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3811): L2CAP - PSM: 0x001b not found for deregistration
E/bt-btif ( 3811): bta_gattc_deregister Deregister Failedm unknown client cif
D/bt_userial_mct( 3811): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 3811): hw_epilog_process
D/bt_hci_bdroid( 3811): cleanup Finalizing cleanup
D/bt_userial_mct( 3811): userial_close
E/bt_userial_mct( 3811): pthread_join() FAILED result:3
I/bt_vendor( 3811): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
D/bt_hci_bdroid( 3811): set_power 0
I/bt_vendor( 3811): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 3811): bluetooth satus is on
I/bt_vendor( 3811): bt-vendor : resetting BT status
I/bt_vendor( 3811): Starting hciattach daemon
I/bt_vendor( 3811): try to set false
,I/bt_vendor( 3811): Starting hciattach daemon
I/bt_vendor( 3811): try to set false
I/bt_vendor( 3811): cleanup
I/GKI_LINUX( 3811): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3811): GKI_exit_task 0 done
I/GKI_LINUX( 3811): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3811): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/HeadsetService( 3811): Received stop request...Stopping profile...
,I/LGBluetoothHfpAdapter( 3811): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 3811): Cleaning up Bluetooth Handsfree callback object
D/HeadsetStateMachine( 3811): Exit Disconnected: -1
D/BluetoothAdapterService( 3811): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3036655f
D/BluetoothAdapterState( 3811): Stopping profile services that were post enabled
D/BluetoothHeadset( 1873): Proxy object disconnected
D/BluetoothHeadset( 1873): Proxy object disconnected
D/BluetoothHeadset( 1873): Proxy object disconnected
D/BluetoothHeadset( 1038): Proxy object disconnected
D/AudioService( 1038): onServiceDisconnected: Bluetooth profile: 1
D/A2dpService( 3811): Received stop request...Stopping profile...
D/A2dpStateMachine( 3811): Exit Disconnected: -1
D/LGBluetoothAvrcpQcomAdapter( 3811): [BTUI] cleanup
,D/LGBluetoothA2dpAdapter( 3811): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 3811): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3811): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3036655f
D/BluetoothA2dp( 1038): Proxy object disconnected
D/AudioService( 1038): onServiceDisconnected: Bluetooth profile: 2
D/HidService( 3811): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3811): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3036655f
D/HealthService( 3811): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3811): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3036655f
D/PanService( 3811): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3811): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3036655f
,D/BtGatt.DebugUtils( 3811): handleDebugAction() action=null
D/BtGatt.GattService( 3811): Received stop request...Stopping profile...
D/BtGatt.GattService( 3811): stop()
D/BtGatt.AdvertiseManager( 3811): advertise clients cleared
D/BluetoothAdapterService( 3811): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3036655f
D/BluetoothMapService( 3811): Received stop request...Stopping profile...
D/BluetoothMapService( 3811): stop()
D/BluetoothMapEmailAppObserver( 3811): deinitObservers()
D/BluetoothMapEmailAppObserver( 3811): removeReceiver()
D/BluetoothAdapterService( 3811): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3036655f
D/HeadsetStateMachine( 3811): Unbinding service...
,D/HeadsetPhoneState( 3811): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3811): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 3811): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3811): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 3811): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3811): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 3811): [BTUI] LGBluetoothHfpAdapter cleanup
I/BluetoothA2dpServiceJni( 3811): cleanupNative
I/GKI_LINUX( 3811): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3811): GKI_exit_task 2 done
I/GKI_LINUX( 3811): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 3811): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3811): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3811): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3811): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 3811): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3811): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3811): Cleaning up Bluetooth PAN callback object
V/BluetoothMapService( 3811): Handler(): got msg=4
D/BluetoothMapService( 3811): MAP Service closeService in
D/LGBluetoothMapAdapter( 3811): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3811): MAP Service closeService out
D/BluetoothAdapterState( 3811): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3811): Setting state to 10
I/BluetoothAdapterState( 3811): Bluetooth adapter state changed: 13-> 10
D/BluetoothMapService( 3811): cleanup()
D/BluetoothMapService( 3811): MAP Service closeService in
D/LGBluetoothMapAdapter( 3811): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3811): MAP Service closeService out
,D/BluetoothManagerService( 1038): Message: 60
D/BluetoothManagerService( 1038): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1038): Broadcasting onBluetoothStateChange(false) to 9 receivers.
I/BluetoothAdapterState( 3811): Entering OffState
D/BluetoothHeadset( 1873): onBluetoothStateChange: up=false
D/BluetoothPan( 6886): onBluetoothStateChange on: false
D/BluetoothHeadset( 1873): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1038): onBluetoothStateChange: up=false
D/BluetoothPbap( 6886): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1873): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1038): onBluetoothStateChange: up=false
D/BluetoothMap( 6886): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 6886): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1038): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1038): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/BluetoothManagerService( 1038): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1038): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1038): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@25e6e07 mBinding = false
,D/BluetoothManagerService( 1038): Sending unbind request.
I/GKI_LINUX( 3811): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 3811): GKI_exit_task 1 done
I/GKI_LINUX( 3811): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3811): cleanupNative: return from cleanup
I/art     ( 3811): --- WEIRD: removing null entry 246
W/art     ( 3811): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
W/LGBluetoothServiceJni( 3811): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 3811): [BTUI] unregister observer for LG device name DB
D/BluetoothManagerService( 1038): Bluetooth State Change Intent: 13 -> 10
I/art     ( 3811): System.exit called, status: 0
I/AndroidRuntime( 3811): VM exiting with result code 0, cleanup skipped.
V/AudioFlinger(  320): 3811 died, releasing its sessions
V/AudioFlinger(  320):  pid 1873 @ 0
V/AudioFlinger(  320):  pid 3355 @ 1
V/AudioFlinger(  320):  pid 3355 @ 2
,D/LGBluetoothAPIService( 1969): [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1969): Message: 101
E/LGBluetoothAPIService( 1969): MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
D/LGBluetoothAPIService( 1969): Calling onBluetoothServiceDown callbacks
D/LGBluetoothAPIService( 1969): Broadcasting onBluetoothServiceDown() to 0 receivers.
D/LGBluetoothUserBindClient( 6886): [BTUI] onServiceDisconnected
I/ActivityManager( 1038): Process com.android.bluetooth (pid 3811) has died
W/ActivityManager( 1038): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
W/ActivityManager( 1038): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
,D/LGBluetoothAPIService( 1969): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,D/LGBluetoothAPIService( 1969): Message: 2
D/LGBluetoothAPIService( 1969): unbindAndFinish(): null mBinding = false
D/LGBluetoothFeatureConfig( 6886): isPrivacyLogsEnabled : true
E/LGBluetoothEventManager( 6886): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 6886): [BTUI] clear device connection state
,I/[SystemUI]BluetoothHandler( 1478): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,D/BluetoothAdapter( 1478): 883319153: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1478): 883319153: getState() :  mService = null. Returning STATE_OFF
W/ContextImpl( 6886): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,I/ActivityManager( 1038): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7650 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
D/DockEventReceiver( 6886): finishStartingService: stopping service
,W/ResourcesManager( 7650): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 7650): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7650): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7650): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothAdapterApp( 7650): Loading JNI Library
,D/BluetoothAdapterApp( 7650): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@c374e14 Instance Count = 1
,D/BluetoothAdapterApp( 7650): onCreate
D/ProfileConfigQcom( 7650): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 7650): Adding HeadsetService
D/ProfileConfigQcom( 7650): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 7650): Adding A2dpService
D/ProfileConfigQcom( 7650): [BTUI] HidService is supported
D/ProfileConfigQcom( 7650): Adding HidService
D/ProfileConfigQcom( 7650): [BTUI] HealthService is supported
,D/ProfileConfigQcom( 7650): Adding HealthService
,D/LGBluetoothFeatureConfig( 7650): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 7650): [BTUI] PanService is supported
D/ProfileConfigQcom( 7650): Adding PanService
,D/ProfileConfigQcom( 7650): [BTUI] GattService is supported
D/ProfileConfigQcom( 7650): Adding GattService
D/ProfileConfigQcom( 7650): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 7650): Adding BluetoothMapService
D/ProfileConfigQcom( 7650): [BTUI] HeadsetClientService is NOT supported
V/BluetoothPbapReceiver( 7650): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 7650): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 7650): ***********state = 10
V/LGMDMManagerInternal( 7650): Create singleton instance
D/LGBluetoothAPIServer( 7650): [BTUI] onCreate()
D/LGBluetoothAPIServer( 7650): [BTUI] onBind()
,D/LGBluetoothAPIService( 1969): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1969): Message: 100
D/LGBluetoothAPIService( 1969): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/LGBluetoothUserBindClient( 6886): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 6886): onReceive
D/LGBluetoothUtils( 6886): [BTUI] FileNotFound: readProperty
D/BluetoothDiscoverableTimeoutReceiver( 6886): cancelDiscoverableAlarm(): Enter
,D/LGBluetoothResetSettingReceiver( 6886): return without doing reset settings.
D/LGBluetoothOppAdapter( 7650): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,V/BluetoothFtpReceiver( 7650): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 7650): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 7650): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 7650): SapReceiver onReceive 
V/BluetoothSapReceiver( 7650): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 7650):  Bluetooth Adapter state = 10
D/LGBluetoothProfileConnectionReceiver_EasySetting( 7601): [BTUI] STATE_OFF : reset connected device information EasySettings
,D/AuthorizationBluetoothService( 2141): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/wpa_supplicant( 2801): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 2801): monitor socket send errors count : 1
I/wpa_supplicant( 2801): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1969-2\x00 that cannot receive messages
W/wpa_supplicant( 2801): USIM:  scard_deinit function
D/WifiMonitor( 1038): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor( 1038): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1038):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=444086  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
,E/WifiStateMachine( 1038):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=444089  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
I/wpa_supplicant( 2801): wlan0: CTRL-EVENT-TERMINATING 
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1038): Disconnecting from the supplicant, no more events
E/WifiStateMachine( 1038):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 47 0
D/WfdsService( 1969): Supplicant Connection state is changed : false
,D/WfdsService( 1969): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1969): Set the WFDS Monitor: false
D/WfdsMonitor( 1969): WFDS Monitor is stopped
D/WifiOffDelayIfNotUsed( 1038): stopMonitoring
E/WifiStateMachine( 1038): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1038): useWiFiOffloading() : false
E/WifiStateMachine( 1038): CONFIG_LGE_WLAN_PATH : true
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1969): WfdStateTracker handleDirectStateChangedEvent: 0
,W/Settings( 1838): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiServerServiceExt( 1038): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt( 1038): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1038): batteryPsActivateMsgHandler : this is not treated
D/LGDMClient( 4299): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4299): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/PCSuite ( 6907): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
D/PCSuite ( 6907): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6907): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6886): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/LGDMClient( 4299): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/WiFiOffLoadBroadcast( 6886): MCCMNC not supported: null
D/LGDMClient( 4299): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4299): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,W/FormManager( 7107): Network not available. Please check & try again.
,V/FormManager( 7107): Network unavailable.
,V/FormManager( 7107): Network unavailable.
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1038): MasterInitialState.processMessage what=3
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1038): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6447): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6447): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5565): type=WIFI subType= reason=null isConnected=false
,I/NetworkMonitor( 5565): type=WIFI subType= reason=null isConnected=false
,D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 1038): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7685 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7685): onCreate
W/AppUp4:DB( 7685):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7685):  setFingerPrint start
I/AppUp4:DB( 7685):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 7685):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7685):  SDK version = 21
,I/AppUp4:DB( 7685):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7685): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 7685): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7685): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7685): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 7685): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7685): onReceive
,D/LgDataFeature( 7685): LgDataFeature() Constructor: none
,D/LgDataFeature( 7685): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7685): Context : android.app.ReceiverRestrictedContext@4a2d9fe
D/AppUp4:CustFacade( 7685): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7685): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7685): begin check event
I/AppUp4:CustModeStarterReceiver( 7685): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7685): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7685): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7685): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7685): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1038): Killing 7130:com.android.chrome/u0a57 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10057/pid_7130/cgroup.procs: No such file or directory
,D/LGDMClient( 4299): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4299): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4299): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4299): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4299): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager( 1038): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7724 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7724): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7724): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7724): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7724): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7724): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7724): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7724): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7724): LgDataFeature() Constructor: none
,D/LgDataFeature( 7724): LgDataFeature() Constructor Done, null
,D/eas_req ( 7724): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 3355): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3355): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3355): networkInfo.isConnected() = false
,I/HubEmail( 7724): JNI_OnLoad()
I/HubEmail( 7724): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7724): registerNatives()
I/HubEmail( 7724): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7724): registerNativeMethods()
I/HubEmail( 7724): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7724): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1038): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7756 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/FormManager( 7107): Network not available. Please check & try again.
,W/Settings( 7724): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/FormManager( 7107): Network unavailable.
V/FormManager( 7107): Network unavailable.
I/ActivityManager( 1038): Killing 7150:com.lge.drmservice/u0a62 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10062/pid_7150/cgroup.procs: No such file or directory
,I/ActivityManager( 1038): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7774 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 7168:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,I/art     (  355): Explicit concurrent mark sweep GC freed 703(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 4.191ms total 25.007ms
,I/art     (  355): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 362us total 17.228ms
,I/art     (  355): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 291us total 16.434ms
,W/libprocessgroup( 1038): failed to open /acct/uid_10085/pid_7168/cgroup.procs: No such file or directory
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 64306(2MB) AllocSpace objects, 6(608KB) LOS objects, 33% free, 44MB/66MB, paused 2.812ms total 162.313ms
,I/ActivityManager( 1038): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7805 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1038): Killing 7189:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10093/pid_7189/cgroup.procs: No such file or directory
,I/art     ( 7805): Almond Protected OAT
,D/LGWifiP2pService( 1038): P2pDisabledState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WeatherApplication( 7805): removeAccount
,D/WeatherApplication( 7805): Account.length = 0
E/WeatherApplication( 7805): OPERATOR:OPEN
D/WeatherAncestor( 7805): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:21:53
E/WifiStateMachine( 1038):  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
E/WifiStateMachine( 1038):  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
D/Weather.Utils( 7805): 2 : the weather widgets(using time tick) are gone.
,D/Weather.Utils( 7805): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7805): 2 : This is isUpdating : false
D/WeatherAncestor( 7805): connectivity changed - connection : true
D/WeatherService( 7805): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7805): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7805): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7805): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7805): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 7805): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:21:54
I/ActivityManager( 1038): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7824 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 7250:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10097/pid_7250/cgroup.procs: No such file or directory
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7824): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7824): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7824): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7824): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7824): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7824): Loading: webviewchromium
,I/LibraryLoader( 7824): Time to load native libraries: 5 ms (timestamps 7699-7704)
I/LibraryLoader( 7824): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7824): Binding Chromium to main looper Looper (main, tid 1) {401f66b}
I/LibraryLoader( 7824): Expected native library version number "",actual native library version number ""
I/chromium( 7824): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7824): Initializing chromium process, renderers=0
,W/art     ( 7824): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7824): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7824): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7824): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,V/AudioPolicyService(  320): registerClient() client 0xb1427cc0, uid 10093
W/AudioManagerAndroid( 7824): Requires BLUETOOTH permission
I/Adreno-EGL( 7824): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7824): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7824): Build Date: 12/12/14 금
I/Adreno-EGL( 7824): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7824): Remote Branch: 
I/Adreno-EGL( 7824): Local Patches: 
I/Adreno-EGL( 7824): Reconstruct Branch: 
,I/NSApplication( 7824): Starting up...
,I/ActivityManager( 1038): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7880 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6235:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10044/pid_6235/cgroup.procs: No such file or directory
,W/ResourcesManager( 7880): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.Environment( 2367): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2367): num queued entries: 0
I/iu.UploadsManager( 2367): num updated entries: 0
I/iu.SyncManager( 2367): NEXT; no task
D/ChimeraCfgMgr( 2367): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6447): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6447): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7685): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7685): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7685): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7685): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7685): onReceive
,D/AppUp4:CustFacade( 7685): Context : android.app.ReceiverRestrictedContext@4a2d9fe
D/AppUp4:CustFacade( 7685): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7685): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7685): begin check event
I/AppUp4:CustModeStarterReceiver( 7685): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4299): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4299): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/eas_req ( 7724): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
D/LGDMClient( 4299): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/GLSActivity( 2141): [ac] getting account id
,D/LGDMClient( 4299): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4299): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,W/Settings( 7724): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/FormManager( 7107): Network not available. Please check & try again.
I/LgeMiscReceiver( 3355): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3355): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3355): networkInfo.isConnected() = false
I/GLSUser ( 2141): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
V/FormManager( 7107): Network unavailable.
D/WeatherAncestor( 7805): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:21:55
,V/FormManager( 7107): Network unavailable.
D/Weather.Utils( 7805): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7805): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7805): 2 : This is isUpdating : false
D/WeatherAncestor( 7805): connectivity changed - connection : true
D/WeatherService( 7805): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@20864bac
D/ForecastDataCache( 7805): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7805): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7805): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7805): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7805): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:21:55
D/ChimeraCfgMgr( 2367): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{36125866 type 2 when 450885 com.google.android.gms} when 450885
,D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1038): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/GAV4    ( 7824): Thread[GAThread,5,main]: No campaign data found.
,I/[SystemUI]TimeTickManager( 1478): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1478): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1478): called onTimeUpdated()
I/[SystemUI]Clock( 1478): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1478): called onTimeUpdated()
,I/[SystemUI]DateView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1478): handleTimeUpdate
,I/ActivityManager( 1038): Killing 7371:com.google.android.apps.books/u0a54 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10054/pid_7371/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 456429829099; DSPS: 15097134; Offset : -4311852363
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 476432575706; DSPS: 15752584; Offset : -4311852287
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 496434329085; DSPS: 16408002; Offset : -4311868875
,I/[SystemUI]TimeTickManager( 1478): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1478): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1478): called onTimeUpdated()
I/[SystemUI]Clock( 1478): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1478): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 516436457097; DSPS: 17063432; Offset : -4311877275
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 536438424485; DSPS: 17718856; Offset : -4311862935
,I/[SystemUI]LGPowerUI( 1478): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1478): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1478): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1478): onReceive = android.intent.action.BATTERY_CHANGED
,D/WifiController( 1038): battery changed pluggedType: 2
D/LEDHandler( 1969): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1969): Battery Level Remaining: 100%
D/LEDHandler( 1969): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1478): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4299): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4299): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 556440336822; DSPS: 18374279; Offset : -4311873153
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=50998299, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{4b58ffd type 2 when 567986 android} when 567986
D/[Concierge]Service( 2591): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=50998299 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1478): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1478): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1478): called onTimeUpdated()
I/[SystemUI]Clock( 1478): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1478): called onTimeUpdated()
,I/[SystemUI]DateView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1478): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 576442492543; DSPS: 19029709; Offset : -4311853558
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 596443935660; DSPS: 19685117; Offset : -4311875389
,I/[SystemUI]LGPowerUI( 1478): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1478): On Skip Timer : true
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 616446029299; DSPS: 20340545; Offset : -4311856945
,I/[SystemUI]TimeTickManager( 1478): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1478): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1478): called onTimeUpdated()
I/[SystemUI]Clock( 1478): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1478): called onTimeUpdated(),
I/[SystemUI]DateView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1478): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 636448101895; DSPS: 20995973; Offset : -4311859544
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 656449910533; DSPS: 21651392; Offset : -4311851470
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 676452613130; DSPS: 22306841; Offset : -4311864833
,I/[SystemUI]TimeTickManager( 1478): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1478): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1478): called onTimeUpdated()
I/[SystemUI]Clock( 1478): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1478): called onTimeUpdated()
,I/[SystemUI]DateView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1478): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 696454702966; DSPS: 22962269; Offset : -4311850374
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 716456768480; DSPS: 23617697; Offset : -4311859952
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 736458830138; DSPS: 24273125; Offset : -4311873385
,I/[SystemUI]TimeTickManager( 1478): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1478): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1478): called onTimeUpdated()
,I/[SystemUI]Clock( 1478): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1478): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 756461562891; DSPS: 24928574; Offset : -4311857087
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=50998299, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{2ddb94f2 type 0 when 1454423198502 com.google.android.gms} when 1454423198502
,D/[Concierge]Service( 2591): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=50998299 [*alarm*], flags=0x0
,I/EventLogService( 2367): Aggregate from 1454421398343 (log), 1454421398343 (data)
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 776463622624; DSPS: 25584002; Offset : -4311872419
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 796465079855; DSPS: 26239410; Offset : -4311880109
,I/[SystemUI]TimeTickManager( 1478): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1478): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1478): called onTimeUpdated()
,I/[SystemUI]Clock( 1478): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1478): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 816471377296; DSPS: 26894976; Offset : -4311869238
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 836473454163; DSPS: 27550404; Offset : -4311867566
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 856475334936; DSPS: 28205826; Offset : -4311878675
,I/[SystemUI]TimeTickManager( 1478): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1478): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1478): called onTimeUpdated()
,I/[SystemUI]Clock( 1478): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1478): called onTimeUpdated()
,I/[SystemUI]DateView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1478): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 876477449408; DSPS: 28861255; Offset : -4311870150
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 896479240858; DSPS: 29516674; Offset : -4311879055
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 916481833091; DSPS: 30172119; Offset : -4311880868
,I/[SystemUI]TimeTickManager( 1478): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1478): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1478): called onTimeUpdated()
I/[SystemUI]Clock( 1478): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1478): handleTimeUpdate
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=50998299, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,I/ActivityManager( 1038): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8014 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2591): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 8014): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8014): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@7390c03
I/ActivityManager( 1038): Killing 6631:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=50998299 [*alarm*], flags=0x0
I/QRemote ( 6931): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6931): android.os.DeadObjectException
W/System.err( 6931): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6931): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6931): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6931): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6931): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6931): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6931): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6931): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6931): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6931): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6931): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6931): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6931): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6931): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6931): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6931): android.os.DeadObjectException
W/System.err( 6931): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6931): 	at android.os.BinderProxy.transact(Binder.java:496)
,W/System.err( 6931): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6931): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6931): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6931): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6931): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6931): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6931): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6931): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6931): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6931): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6931): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
,W/System.err( 6931): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6931): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6931): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6631/cgroup.procs: No such file or directory
W/ActivityManager( 1038): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,D/QRemote ( 6931): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6931): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
I/ActivityManager( 1038): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8049 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/QRemote ( 6931): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,D/UEI.SmartControl( 8049): Quickset Services start...
,I/UEI.SmartControl( 8049): Manufacture = LGE
D/UEI.SmartControl( 8049): Id = LGNevo
D/UEI.SmartControl( 8049): File observer start...
E/UEI.SmartControl( 8049): IR Port is disabled: false
D/UEI.SmartControl( 8049): Starting file observer...
D/UEI.SmartControl( 8049): Extracting JNI libs...
D/UEI.SmartControl( 8049): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 8049): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 8049): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 8049): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 8049): --- Selecting new region: 6
,I/UEI.SmartControl( 8049): Model = LG-D855
D/UEI.SmartControl( 8049): QS Service created
I/UEI.SmartControl( 8049): Service initServices...
,D/UEI.SmartControl( 8049): QS start get config
,D/UEI.SmartControl( 8049): Loading JNI Libs...
,I/UEI.SmartControl( 8049): Supports setup maps: true
,D/UEI.SmartControl( 8049): QS start statue = true Error code = 0
I/UEI.SmartControl( 8049): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 8049): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 8049): ### init IR Blaster...
D/serial_port( 8049): Configuring serial port
,E/UEI.SmartControl( 8049): UEIBLaster setting for 616
I/UEI.SmartControl( 8049): Setting serial record hearder size = 2
I/UEI.SmartControl( 8049): configuring settings for MAXQ616
I/UEI.SmartControl( 8049): Get version...
D/UEI.SmartControl( 8049): serial port data available: 21
,D/UEI.SmartControl( 8049): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 8049): IR Blaster version: 256702256704300002
,I/UEI.SmartControl( 8049): QS saving settings...
,D/UEI.SmartControl( 8049): IR Blaster version: 25672567
D/UEI.SmartControl( 8049): serial port data available: 4
,I/UEI.SmartControl( 8049): Device manager: loading config....
,W/ContextImpl( 8049): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,D/UEI.SmartControl( 8049): ----------- loading internal config...
E/UEI.SmartControl( 8049): Services init done
D/UEI.SmartControl( 8049): QS Service init finished
D/UEI.SmartControl( 8049): QS Service version name: 2.1.91
D/UEI.SmartControl( 8049): QS Service version code: 201091
D/UEI.SmartControl( 8049): Service requested: Control
E/UEI.SmartControl( 8049): Loading SETTINGS...
,D/UEI.SmartControl( 8049): Request IControl service: devices are loaded...
I/ActivityManager( 1038): Killing 6931:com.lge.qremote/u0a112 (adj 15): empty #17
D/UEI.SmartControl( 8049): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 8049): Notify AllClients services are ready: 0
D/UEI.SmartControl( 8049): -----service ready thread exits
,W/libprocessgroup( 1038): failed to open /acct/uid_10112/pid_6931/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 8049): Internal service binding...
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 936484789750; DSPS: 30827576; Offset : -4311884179
D/serial_port( 8049): close(fd = 25)
,I/UEI.SmartControl( 8049): Serial port is closed.
D/UEI.SmartControl( 8049): Internal timer expired: 1
D/UEI.SmartControl( 8049): unbind internal service
,D/UEI.SmartControl( 8049): Service.onUnbind: IControl
D/UEI.SmartControl( 8049): Service.onDestroy
D/UEI.SmartControl( 8049): Lock is in USE false
D/UEI.SmartControl( 8049): unbind internal service
W/System.err( 8049): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2f4e980a
W/System.err( 8049): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
W/System.err( 8049): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
W/System.err( 8049): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 8049): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 8049): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 8049): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
W/System.err( 8049): 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
W/System.err( 8049): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
W/System.err( 8049): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8049): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 8049): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 8049): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 8049): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 8049): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 8049): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 8049): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2f4e980a
I/UEI.SmartControl( 8049): Serial port is closed.
I/UEI.SmartControl( 8049): Serial port is closed.
D/UEI.SmartControl( 8049): Blaster closed
D/UEI.SmartControl( 8049): Shut down QS...
D/UEI.SmartControl( 8049): Stopping QS lib
D/UEI.SmartControl( 8049): QS lib stop result = true
D/UEI.SmartControl( 8049): Stopped QS lib
,D/UEI.SmartControl( 8049): Stopped file observer...
,D/UEI.SmartControl( 8049): QS shutdown complete
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 956486641929; DSPS: 31482996; Offset : -4311863264
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 976488514421; DSPS: 32138417; Offset : -4311852214
,I/[SystemUI]TimeTickManager( 1478): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1478): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1478): called onTimeUpdated()
I/[SystemUI]Clock( 1478): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1478): called onTimeUpdated()
,I/[SystemUI]DateView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1478): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 996491455925; DSPS: 32793874; Offset : -4311871123
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1016493210605; DSPS: 33449291; Offset : -4311855763
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1036495258670; DSPS: 34104718; Offset : -4311852480
,I/[SystemUI]TimeTickManager( 1478): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1478): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1478): called onTimeUpdated()
I/[SystemUI]Clock( 1478): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1478): called onTimeUpdated()
,I/[SystemUI]DateView( 1478): called onTimeUpdated()
,I/[SystemUI]DateView( 1478): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1478): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1056497074079; DSPS: 34760138; Offset : -4311868281
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1076498898602; DSPS: 35415558; Offset : -4311874684
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1096501005523; DSPS: 36070987; Offset : -4311873527
,I/[SystemUI]TimeTickManager( 1478): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1478): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1478): called onTimeUpdated()
I/[SystemUI]Clock( 1478): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1478): called onTimeUpdated()
,I/[SystemUI]DateView( 1478): called onTimeUpdated()
,I/[SystemUI]DateView( 1478): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1478): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1116503073327; DSPS: 36726415; Offset : -4311880971
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1136504984413; DSPS: 37381837; Offset : -4311861818
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1156506622635; DSPS: 38037251; Offset : -4311871728
,I/[SystemUI]TimeTickManager( 1478): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1478): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1478): called onTimeUpdated()
,I/[SystemUI]Clock( 1478): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1478): called onTimeUpdated()
,I/[SystemUI]DateView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1478): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1176508723147; DSPS: 38692680; Offset : -4311876798
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1196511921787; DSPS: 39348144; Offset : -4311851856
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1216513711674; DSPS: 40003563; Offset : -4311862584
,I/UsageStatsService( 1038): User[0] Flushing usage stats to disk
,I/[SystemUI]TimeTickManager( 1478): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1478): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1478): called onTimeUpdated()
I/[SystemUI]Clock( 1478): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1478): called onTimeUpdated()
,I/[SystemUI]DateView( 1478): called onTimeUpdated()
,I/[SystemUI]DateView( 1478): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1478): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1236515561302; DSPS: 40658984; Offset : -4311874607,
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1256517620201; DSPS: 41314411; Offset : -4311860386
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1276519702953; DSPS: 41969839; Offset : -4311852674
,I/[SystemUI]TimeTickManager( 1478): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1478): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1478): called onTimeUpdated()
I/[SystemUI]Clock( 1478): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1478): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1296522395133; DSPS: 42625288; Offset : -4311876661
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1316524233667; DSPS: 43280708; Offset : -4311869208
,TIME-OUT KILL (timeout was 1200000ms)
```
