#### Test 58741471ee11130_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
--------- beginning of system
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1416): onNotificationPosted
D/SmartCoverUpdateMonitor( 1416): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1416): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1416): handleNotificationPosted(true)
D/QuickCircle( 1416): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1416): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): post do just update job
D/LgeQuickCoverNotificationData( 1416): showAll3
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1416): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1416): updateNotificationData: count=3
W/GLSActivity( 2144): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2144): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2144): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2144): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6634): Authentication error
E/BooksAccountManager( 6634): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6634): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6634): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6634): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6634): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6634): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6634): null auth token
D/QuickStatusbarLayout( 1416): Notification difference=198
D/QuickStatusbarLayout( 1416): child = android.widget.LinearLayout{3c6df3e7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6634): Error response from books API: {
W/ApiaryClient( 6634):  "error": {
W/ApiaryClient( 6634):   "errors": [
W/ApiaryClient( 6634):    {
W/ApiaryClient( 6634):     "domain": "global",
W/ApiaryClient( 6634):     "reason": "required",
W/ApiaryClient( 6634):     "message": "Login Required",
W/ApiaryClient( 6634):     "locationType": "header",
W/ApiaryClient( 6634):     "location": "Authorization"
W/ApiaryClient( 6634):    }
W/ApiaryClient( 6634):   ],
W/ApiaryClient( 6634):   "code": 401,
W/ApiaryClient( 6634):   "message": "Login Required"
W/ApiaryClient( 6634):  }
W/ApiaryClient( 6634): }
W/ApiaryClient( 6634): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6634): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2988016975487831911&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6634): Headers:
W/ApiaryClient( 6634): accept-encoding: [gzip]
W/ApiaryClient( 6634): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6634): gdata-version: 2
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1416): onNotificationPosted
D/SmartCoverUpdateMonitor( 1416): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1416): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1416): handleNotificationPosted(true)
D/QuickCircle( 1416): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1416): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): post do just update job
D/LgeQuickCoverNotificationData( 1416): showAll3
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1416): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1416): updateNotificationData: count=3
W/GLSActivity( 2144): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2144): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2144): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2144): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6634): Authentication error
E/BooksAccountManager( 6634): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6634): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6634): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6634): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6634): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6634): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6634): null auth token
D/QuickStatusbarLayout( 1416): Notification difference=198
D/QuickStatusbarLayout( 1416): child = android.widget.LinearLayout{3c6df3e7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6634): Error response from books API: {
W/ApiaryClient( 6634):  "error": {
W/ApiaryClient( 6634):   "errors": [
W/ApiaryClient( 6634):    {
W/ApiaryClient( 6634):     "domain": "global",
W/ApiaryClient( 6634):     "reason": "required",
W/ApiaryClient( 6634):     "message": "Login Required",
W/ApiaryClient( 6634):     "locationType": "header",
W/ApiaryClient( 6634):     "location": "Authorization"
W/ApiaryClient( 6634):    }
W/ApiaryClient( 6634):   ],
W/ApiaryClient( 6634):   "code": 401,
W/ApiaryClient( 6634):   "message": "Login Required"
W/ApiaryClient( 6634):  }
W/ApiaryClient( 6634): }
W/ApiaryClient( 6634): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6634): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2988016975487831911&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6634): Headers:
W/ApiaryClient( 6634): accept-encoding: [gzip]
W/ApiaryClient( 6634): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6634): gdata-version: 2
,D/AndroidRuntime( 6705): 
D/AndroidRuntime( 6705): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6705): CheckJNI is OFF
D/AndroidRuntime( 6705): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1035): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1992): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1035): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1035): setTaskToReturnTo : TaskRecord{3068322d #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1035): setTaskToReturnTo : TaskRecord{3068322d #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1035): AppWindowTokenEx init.. 
E/GBMv2   (  363): DFP En is all cleared set to be enabled
I/ActivityManager( 1035): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6720 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6705): Shutting down VM
I/art     (  373): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 283us total 40.967ms
I/art     (  373): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 248us total 12.099ms
V/ActivityManager( 1035): Display changed displayId=0
I/art     (  373): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 254us total 17.153ms
D/DSDPConnection( 1872): Display #0 changed.
D/SplitWindowPolicy( 1992): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1992): topRunningActivity=ActivityInfo{1f658989 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1992): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1992): topRunningActivity=ActivityInfo{37197d8e co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6720): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6720): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6720): Loading: webviewchromium
I/LibraryLoader( 6720): Time to load native libraries: 3 ms (timestamps 6203-6206)
I/LibraryLoader( 6720): Expected native library version number "",actual native library version number ""
,E/BooksSync( 6634): Soft error: 
E/BooksSync( 6634): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6634): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2988016975487831911&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6634): Headers:
E/BooksSync( 6634): accept-encoding: [gzip]
E/BooksSync( 6634): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6634): gdata-version: 2
E/BooksSync( 6634): 
E/BooksSync( 6634): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6634): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6634): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6634): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6634): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6634): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6634): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6634): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6634): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6634): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6634): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6634): {
E/BooksSync( 6634):  "error": {
E/BooksSync( 6634):   "errors": [
E/BooksSync( 6634):    {
E/BooksSync( 6634):     "domain": "global",
E/BooksSync( 6634):     "reason": "required",
E/BooksSync( 6634):     "message": "Login Required",
E/BooksSync( 6634):     "locationType": "header",
E/BooksSync( 6634):     "location": "Authorization"
E/BooksSync( 6634):    }
E/BooksSync( 6634):   ],
E/BooksSync( 6634):   "code": 401,
E/BooksSync( 6634):   "message": "Login Required"
E/BooksSync( 6634):  }
E/BooksSync( 6634): }
E/BooksSync( 6634): 
E/BooksSync( 6634): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6634): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6634): 	... 8 more
E/BooksSync( 6634): Sync error
E/BooksSync( 6634): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6634): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2988016975487831911&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6634): Headers:
E/BooksSync( 6634): accept-encoding: [gzip]
E/BooksSync( 6634): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6634): gdata-version: 2
E/BooksSync( 6634): 
E/BooksSync( 6634): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6634): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6634): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6634): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6634): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6634): 	at com.google.android.apps.books.data.NetworkTas,kQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6634): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6634): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6634): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6634): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6634): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6634): {
E/BooksSync( 6634):  "error": {
E/BooksSync( 6634):   "errors": [
E/BooksSync( 6634):    {
E/BooksSync( 6634):     "domain": "global",
E/BooksSync( 6634):     "reason": "required",
E/BooksSync( 6634):     "message": "Login Required",
E/BooksSync( 6634):     "locationType": "header",
E/BooksSync( 6634):     "location": "Authorization"
E/BooksSync( 6634):    }
E/BooksSync( 6634):   ],
E/BooksSync( 6634):   "code": 401,
E/BooksSync( 6634):   "message": "Login Required"
E/BooksSync( 6634):  }
E/BooksSync( 6634): }
E/BooksSync( 6634): 
E/BooksSync( 6634): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6634): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6634): 	... 8 more
I/BooksSync( 6634): Finished books sync
,D/SyncManager( 1035): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 77749, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/ActivityManager( 1035): Killing 6417:com.google.android.partnersetup/u0a8 (adj 15): empty #17
V/WebViewChromiumFactoryProvider( 6720): Binding Chromium to main looper Looper (main, tid 1) {100e8b79}
I/LibraryLoader( 6720): Expected native library version number "",actual native library version number ""
I/chromium( 6720): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6720): Initializing chromium process, renderers=0
W/art     ( 6720): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  324): registerClient() client 0xb558a2a0, uid 10311
,W/chromium( 6720): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6720): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6720): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1035): Message: 20
D/BluetoothManagerService( 1035): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3631354f:true
I/Adreno-EGL( 6720): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6720): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6720): Build Date: 12/12/14 금
I/Adreno-EGL( 6720): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6720): Remote Branch: 
I/Adreno-EGL( 6720): Local Patches: 
I/Adreno-EGL( 6720): Reconstruct Branch: 
,W/libprocessgroup( 1035): failed to open /acct/uid_10008/pid_6417/cgroup.procs: No such file or directory
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/MusicWidget( 2627): mDelayedStopHandler : unbind
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/MusicBrowser( 2237): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2237): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2237): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2237): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2237): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
,D/MusicBrowser( 2237): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2237): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2237): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1035):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@143b46a5com.lge.music.MediaPlaybackService$5@35618a7a
D/MusicBrowser( 2237): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2237): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2237): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2237): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2237): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@28a6e43b
I/MusicBrowser( 2237): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
W/chromium( 6720): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
I/MusicBrowser( 2237): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2237): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
I/MusicBrowser( 2237): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
W/chromium( 6720): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/GLSActivity( 2144): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2144): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2144): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2144): 	at android.os.Binder.execTransact(Binder.java:446)
I/MusicBrowser( 2237): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2237): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
D/ContactsSyncAdapter( 2144): innerSync failed
D/ContactsSyncAdapter( 2144): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2144): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2144): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2144): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2144): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2144): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2144): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2144): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2144): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2144): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2144): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2144): 	at android.os.Binder.execTransact(Binder.java:446)
I/MusicBrowser( 2237): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
D/LgeQuickCoverNLService( 1416): onNotificationPosted
I/MusicBrowser( 2237): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,D/SmartCoverUpdateMonitor( 1416): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1416): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1416): handleNotificationPosted(true)
D/QuickCircle( 1416): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1416): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): post do just update job
D/LgeQuickCoverNotificationData( 1416): showAll3
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1416): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
I/MusicBrowser( 2237): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
I/MusicBrowser( 2237): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
E/LgeQuickCoverOverlayWindow( 1416): updateNotificationData: count=3
I/MusicBrowser( 2237): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2237): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2237): [MediaPlaybackService.java:6665:stop()] oooooo 
,V/MediaPlayer[Native]( 2237): reset
V/MediaPlayer[Native]( 2237): setListener
V/MediaPlayer[Native]( 2237): disconnect
V/MediaPlayer[Native]( 2237): destructor
V/AudioFlinger(  324): releasing 13 from 2237 for -1
V/AudioFlinger(  324):  decremented refcount to 0
V/AudioFlinger(  324): purging stale effects
V/MediaPlayer[Native]( 2237): disconnect
W/art     ( 6720): Attempt to remove local handle scope entry from IRT, ignoring
D/MusicBrowser( 2237): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
I/SmartShareClient( 2237): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2237): [SmartShareManagerClient] smartshare client enabled
D/SyncManager( 1035): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 103487, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1035): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 170591, reason: 10019
I/MusicBrowser( 2237): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2237): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2237): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2237): [SmartShareManagerClient] unregisterListener: 118837803
W/SmartShareClient( 2237): [SmartShareManagerClient] unregisterListener invalid listener: 118837803
W/AwContents( 6720): onDetachedFromWindow called when already detached. Ignoring
D/QuickStatusbarLayout( 1416): Notification difference=198
D/QuickStatusbarLayout( 1416): child = android.widget.LinearLayout{3c6df3e7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/SmartShareClient( 2237): [SmartShareManagerClient] terminate service: 2237/MediaPlaybackService/269388665
E/HomeCloudIF( 2237): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2237): [SmartShareManagerClient] unbindService context:android.app.Application@3b5f4688
D/SystemWebViewEngine( 6720): CordovaWebView is running on device made by: LGE
,W/art     ( 6720): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6720): Attempt to remove local handle scope entry from IRT, ignoring
V/CloudHub( 2237): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2237): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2237): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2237): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
I/CloudHub( 2237): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29999
I/ActivityManager( 1035): Killing 6009:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/LgDataFeature( 6720): LgDataFeature() Constructor: none
D/LgDataFeature( 6720): LgDataFeature() Constructor Done, null
,W/libprocessgroup( 1035): failed to open /acct/uid_10011/pid_6009/cgroup.procs: No such file or directory
D/OpenGLRenderer( 6720): Render dirty regions requested: true
I/OpenGLRenderer( 6720): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6720): Enabling debug mode 0
I/GAV2    ( 6634): Thread[GAThread,5,main]: No campaign data found.
,D/Atlas   ( 6720): Validating map...
D/SplitWindow( 1035): check instance of lgWin Window{3b29241 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/ActivityManager( 1035): Activity pause timeout for ActivityRecord{17754362 u0 com.test.thalitest/.MainActivity t4}
,I/SystemUI[Framework]( 1035): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1035): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1035): setLGSystemUiVisibility(0x0)
,D/StatusBarManagerServiceEx( 1035): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1035): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1d092eb6,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1035): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1469): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1469): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1469):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1469): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1035): Displayed com.test.thalitest/.MainActivity: +672ms (total +796ms)
I/Timeline( 1035): Timeline: Activity_windows_visible id: ActivityRecord{17754362 u0 com.test.thalitest/.MainActivity t4} time:106718
I/Timeline( 6720): Timeline: Activity_idle id: android.os.BinderProxy@356c44e9 time:106718
,I/chromium( 6720): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6720): 
,D/JsMessageQueue( 6720): Set native->JS mode to OnlineEventsBridgeMode
,E/GBMv2   (  363): DFP En is all cleared set to be enabled
E/GBMv2   (  363): Set value is all cleared set the max
I/GBMv2   (  363): DFP Enabled. Ignore VFP set
,I/chromium( 6720): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6720): 
,D/jxcore_app_log( 6720): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435218048
,I/chromium( 6720): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6720): Initializing JXcore engine
W/jxcore-log( 6720): JXcore engine is ready
,W/Thread-788( 6797): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8451]" dev="sockfs" ino=8451 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-788( 6797): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-788( 6797): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7900]" dev="sockfs" ino=7900 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-788( 6797): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,W/Thread-788( 6797): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32288]" dev="sockfs" ino=32288 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 6720): Starting JXcore engine
,W/jxcore-log( 6720): Platform android
W/jxcore-log( 6720): 
W/jxcore-log( 6720): Process ARCH arm
W/jxcore-log( 6720): 
,I/jxcore-log( 6720): JXcore Cordova bridge is ready!
I/jxcore-log( 6720): 
W/jxcore-log( 6720): JXcore engine is started
,I/jxcore-log( 6720): Toggling radios to true
I/jxcore-log( 6720): 
,D/BluetoothAdapter( 6720): enable(): BT is already enabled..!
D/WifiService( 1035): New client listening to asynchronous messages
D/WifiServiceImplEx( 1035): setWifiEnabled: true pid=6720, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1035): setWifiEnabled: true pid=6720, uid=10311
E/WifiService( 1035): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiServiceImplEx( 1035): disconnect pid=6720, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1035):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1035): [109,099,434 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1035): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1035): reconnect pid=6720, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6720): Radios toggled
I/jxcore-log( 6720): 
I/jxcore-log( 6720): My device name is: LGE-LG-D855
I/jxcore-log( 6720): 
,I/wpa_supplicant( 2661): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/WifiNative-wlan0( 1035): DISCONNECT: returned true
E/WifiStateMachine( 1035): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1035): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1035): doBoolean: SET_NETWORK 0 bssid any
D/Tethering( 1035): InitialState.processMessage what=4
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1035): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1035): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1035): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1035): doBoolean: SAVE_CONFIG
D/Tethering( 1035): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiNative-wlan0( 1035): SAVE_CONFIG: returned true
,D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1035): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1035): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1035): doBoolean: SET ps 1
,D/WifiNative-wlan0( 1035): SET ps 1: returned true
D/DhcpStateMachine( 1035): RunningState{ when=-13ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  318): Clearing all IP addresses on wlan0
V/NativeCrypto( 2144): Read error: ssl=0xaa6dfc00: I/O error during system call, Connection timed out
,I/ActivityManager( 1035): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6803 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
V/NativeCrypto( 2144): SSL shutdown failed: ssl=0xaa6dfc00: I/O error during system call, Broken pipe
,D/ConnectivityService( 1035): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1035): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/WifiHS20( 1035): hidePasspointNotification off =false
,V/WfdStateTracker( 1992): handleWifiStateChangedEvent: 0
,I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiStateMachine( 1035): Start Disconnecting Watchdog 1
,E/WifiStateMachine( 1035):  DisconnectingState CMD_RECONNECT 0 0
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1035):  ConnectModeState CMD_RECONNECT 0 0
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=123015549, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
E/WifiNative: ( 1035): [109,388,380 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1035): doBoolean: RECONNECT
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 2661): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiHS20( 1035): hidePasspointNotification off =false
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/WifiNative-wlan0( 1035): RECONNECT: returned true
E/WifiStateMachine( 1035):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=109404
E/WifiStateMachine( 1035):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=109405
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1035): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1035): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1035): doBoolean: SET ps 1
D/WifiNative-wlan0( 1035): SET ps 1: returned true
D/CommandListener(  318): Clearing all IP addresses on wlan0
D/ConnectivityService( 1035): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1035): disableDataServiceNotify
D/DSQN    ( 1035): stop dsqn bin
,D/WifiHS20( 1035): hidePasspointNotification off =false
D/ConnectivityService( 1035): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=109420  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Checking http://clients3.google.com/generate_204 on <unknown ssid>
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=109420  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1035):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1035):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1035): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1035): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine( 1035):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/Nat464Xlat( 1035): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
E/WifiStateMachine( 1035):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/CSLegacyTypeTracker( 1035): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1035): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy( 1035): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService( 1035): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/WifiNetworkAgent( 1035): NetworkAgent: NetworkAgent channel lost
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 1035):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=109429  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/ConnectivityManager.CallbackHandler( 1469): CM callback handler got msg 524292
D/LocSvc_java( 1035): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1035): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1035): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1035): ignore wifi update if we are not in OPENING or CLOSING
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/libc-netbsd(  318): default dns: query_ipv6=,0, query_ipv4=0
D/DSQN    ( 1035): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=109436  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): EvaluatingState{ when=-14ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): DefaultState{ when=-14ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Disconnected - quitting
V/NetworkPolicy( 1035): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService( 1035): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1035): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1035): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1035):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/NetworkManagementService( 1035): Removing idletimer
D/TelephonyNetworkFactory-1( 1872): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1872):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
W/Settings( 1035): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1035): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1035): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/LocSvc_java( 1035): Sending msg: 4 arg1:0 arg2:1
D/WifiHS20( 1035): hidePasspointNotification off =false
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LocSvc_java( 1035): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1035): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1035): ignore wifi update if we are not in OPENING or CLOSING
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateSCANNING
,D/TelephonyIcons( 1469): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 6803): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6803): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6803): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6803): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6803): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6803): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyIcons( 1469): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/[Concierge]Service( 2644): onStartCommand(). Type : 9
,D/DhcpStateMachine( 1035): StoppedState
D/DhcpStateMachine( 1035): StoppedState{ when=-166ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 6803): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6803): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6803): [AUTORUN] sys.usb.state = ptp_only,adb
,D/UsbSettingsReceiver( 6803): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6803): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6803): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6803): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6803): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6803): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6803): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6803): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6381): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1035): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6846 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1035): Killing 6029:com.android.contacts/u0a19 (adj 15): empty #17
,W/libprocessgroup( 1035): failed to open /acct/uid_10019/pid_6029/cgroup.procs: No such file or directory
,I/PCSuite ( 6846): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6846): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6846): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6803): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 6803): LgDataFeature() Constructor: none
D/LgDataFeature( 6803): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 6803): MCCMNC not supported: null
I/ActivityManager( 1035): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6870 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1035): Killing 6454:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1035): failed to open /acct/uid_10023/pid_6454/cgroup.procs: No such file or directory
,W/ResourcesManager( 6870): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 6870): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6870): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 6870): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6870): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6870): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6870): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6870): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6870): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6870): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6870): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6870): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/QRemote ( 6870): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,D/QRemote ( 6870): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
D/PostponalbeReceiver( 6381): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6846): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6846): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6846): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6803): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6803): MCCMNC not supported: null
D/QRemote ( 6870): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6870): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6870): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=123015549 [*alarm*], flags=0x0
D/PostponalbeReceiver( 6381): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6846): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6846): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6846): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6803): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6803): MCCMNC not supported: null
D/QRemote ( 6870): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6870): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6870): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
W/ContextImpl( 4505): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
D/PostponalbeReceiver( 6381): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6846): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6846): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6846): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6803): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6803): MCCMNC not supported: null
,D/QRemote ( 6870): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6870): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6870): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6381): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6803): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6803): MCCMNC not supported: null
D/QRemote ( 6870): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6870): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6870): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 6870): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6870): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6870): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 6870): LgDataFeature() Constructor: none
D/LgDataFeature( 6870): LgDataFeature() Constructor Done, null
,V/SoundPool( 6870): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6870): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6870): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6870): doLoad: loading sample sampleID=1
V/SoundPool( 6870): Start decode
V/MediaPlayer[Native]( 6870): decode(31, 10857164, 17813)
V/MediaPlayerService(  324): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  324): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  324): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  324): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  324): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  324): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  324): player type = 3
V/AwesomePlayer(  324): AwesomePlayer create()
I/QRemote ( 6870): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/AwesomePlayer(  324): reset_l() 
V/AwesomePlayer(  324): cancelPlayerEvents
V/AwesomePlayer(  324): setAudioSink() 
V/AwesomePlayer(  324): reset_l() 
V/AudioCache(  324): notify(0xb5474840, 8, 0, 0)
V/AudioCache(  324): ignored
V/AwesomePlayer(  324): cancelPlayerEvents
D/Utils   (  324): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  324): setDataSource_l dataSource
V/LGParserOSAL(  324): SniffLGParser start
V/LGParserOSAL(  324): MainType:5, SubType=0
V/LGParserOSAL(  324): #### check Mime : application/ogg
V/LGParserOSAL(  324): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  324): Use LGExtractor :application/ogg 
D/QRemote ( 6870): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
D/UEI.SmartControl( 6551): QS Service created
E/QRemote ( 6870): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 6870): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGMDMManager( 6870): Create singleton instance
V/LGParserOSAL(  324): supported mime: application/ogg
V/AwesomePlayer(  324): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  324): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  324): mBitrate = -1 bits/sec
V/AwesomePlayer(  324): AudioTrack Setting
V/AwesomePlayer(  324): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  324): setAudioSource() 
V/MediaPlayerService(  324): prepare
V/AwesomePlayer(  324): prepareAsync_l() 
V/MediaPlayerService(  324): wait for prepare
V/AwesomePlayer(  324): onPrepareAsyncEvent() 
V/AwesomePlayer(  324): initAudioDecoder() 
W/Utils   (  324): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  324): isOffloadSupported()
V/AudioPolicyManager(  324): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  324): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  324): isAudioPlaybackHookOn() false
V/AwesomePlayer(  324): getUseOffload() = 0 
V/OMXCodec(  324): OMXCodec::Create
V/OMXCodec(  324): findMatchingCodecs()
V/OMXCodec(  324): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  324): matchingCodecs.size()=1
V/OMXCodec(  324): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  324): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  324): LG Codec Adapter start
V/OMXCodec(  324): OMXCodec Createtor
V/OMXCodec(  324): setComponentRole
V/OMXCodec(  324): configureCodec protected=0
V/LGCodecAdapter(  324): called getLGCodecSpecificData
V/LGCodecOSAL(  324): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  324): Called LGconfigureCodecMETA
V/LGCodecOSAL(  324): Called LGconfigureCodecMSG
V/LGCodecOSAL(  324): Not support LGCodec
V/OMXCodec(  324): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  324): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  324): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  324): Could not offload audio decode, try pcm offload
W/Utils   (  324): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  324): isOffloadSupported()
V/AudioPolicyManager(  324): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  324): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  324): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  324): init()
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  324): allocateBuffers
V/OMXCodec(  324): allocateBuffersOnPort portIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on input port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on input port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on input port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on input port
V/OMXCodec(  324): allocateBuffersOnPort portIndex=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf2e0 on output port,
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf3d0 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf510 on output port
V/OMXCodec(  324): init() mAsyncCompletion wait!!! 
I/UEI.SmartControl( 6551): Service initServices...
D/UEI.SmartControl( 6551): QS start get config
,V/OMXCodec(  324): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  324): init() mAsyncCompletion wait!!! 
V/OMXCodec(  324): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  324): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  324): finishAsyncPrepare_l() 
V/AudioCache(  324): notify(0xb5474840, 5, 0, 0)
V/AudioCache(  324): ignored
V/AudioCache(  324): notify(0xb5474840, 1, 0, 0)
V/AudioCache(  324): prepared
V/AudioCache(  324): wait - success
V/MediaPlayerService(  324): start
V/AwesomePlayer(  324): play_l() 
V/AwesomePlayer(  324): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  324): createAudioPlayer_l
V/AwesomePlayer(  324): seekAudioIfNecessary_l() 
V/AwesomePlayer(  324): startAudioPlayer_l() 
D/AudioPlayer(  324): start of Playback, useOffload 0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  324): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  324): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  324): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  324): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885888
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044799200
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044799440
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044799760
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  324): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  324): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  324): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  324): allocateBuffersOnPort portIndex=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf3d0 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf2e0 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb1434240 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
,V/AudioCache(  324): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  324): notify(0xb5474840, 6, 0, 0)
V/AudioCache(  324): ignored
V/MediaPlayerService(  324): wait for playback complete
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf406000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf407000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf408000, 0xb173c000, 4096)
,V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf409000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf40a000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf40b000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf40c000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf40d000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf40e000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf40f000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf410000, 0xb173c000, 4096)
,V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf411000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf412000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf413000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf414000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf415000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
,V/AudioCache(  324): memcpy(0xaf416000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf417000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf418000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf419000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf41a000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf41b000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf41c000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf41d000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf41e000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf41f000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf420000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf421000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf422000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf423000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf424000, 0xb173c000, 4096)
D/QRemote ( 6870): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf425000, 0xb173c000, 4096)
D/QRemote ( 6870): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf426000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf427000, 0xb173c000, 4096)
D/QRemote ( 6870): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9038
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf428000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf429000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf42a000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf42b000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf42c000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf42d000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf42e000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf42f000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf430000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf431000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf432000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf433000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf434000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf435000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf436000, 0xb173c000, 4096)
V/AudioCache(  324): write(0xb173c000, 4096)
V/AudioCache(  324): memcpy(0xaf437000, 0xb173c000, 4096)
V/OMXCodec(  324): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  324): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  324): postAudioEOS() 
V/Audi,oCache(  324): write(0xb173c000, 280)
V/AudioCache(  324): memcpy(0xaf438000, 0xb173c000, 280)
V/AwesomePlayer(  324): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  324): onStreamDone
V/AwesomePlayer(  324): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  324): notify(0xb5474840, 2, 0, 0)
V/AudioCache(  324): playback complete
V/AwesomePlayer(  324): pause_l() 
V/AudioCache(  324): wait - success
V/AudioCache(  324): notify(0xb5474840, 7, 0, 0)
V/AudioCache(  324): ignored
V/MediaPlayerService(  324): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  324): cancelPlayerEvents
D/AudioPlayer(  324): Pause Playback at 1068125
V/AwesomePlayer(  324): reset_l() 
V/AudioCache(  324): notify(0xb5474840, 8, 0, 0)
V/AudioCache(  324): ignored
V/AwesomePlayer(  324): cancelPlayerEvents
D/AudioPlayer(  324): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  324): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  324): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  324): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e70 on port 0
,V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e20 on port 0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
,V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb1434240 on port 1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
,V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ec0 on port 1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb57bf2e0 on port 1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb57bf3d0 on port 1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  324): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  324): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  324): [OMX.google.vorbis.decoder] onStateChange 1
,V/OMXCodec(  324): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  324): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
,D/AudioPlayer(  324): AudioPlayer releasing audio source
D/AudioPlayer(  324): AudioPlayer done releasing audio source
V/AwesomePlayer(  324): reset_l() 
V/AwesomePlayer(  324): cancelPlayerEvents
V/AwesomePlayer(  324): ~AwesomePlayer call
,V/AwesomePlayer(  324): reset_l() 
V/AwesomePlayer(  324): cancelPlayerEvents
V/SoundPool( 6870): close(31)
V/SoundPool( 6870): pointer = 0x9ffdb000, size = 205080, sampleRate = 48000, numChannels = 2
I/UEI.SmartControl( 6551): Supports setup maps: true
,D/UEI.SmartControl( 6551): QS start statue = true Error code = 0
I/UEI.SmartControl( 6551): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6551): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6551): ### init IR Blaster...
D/serial_port( 6551): Configuring serial port
E/UEI.SmartControl( 6551): UEIBLaster setting for 616
I/UEI.SmartControl( 6551): Setting serial record hearder size = 2
I/UEI.SmartControl( 6551): configuring settings for MAXQ616
I/UEI.SmartControl( 6551): Get version...
,D/UEI.SmartControl( 6551): serial port data available: 21
,D/UEI.SmartControl( 6551): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6551): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6551): QS saving settings...
D/UEI.SmartControl( 6551): IR Blaster version: 25672567
,D/UEI.SmartControl( 6551): serial port data available: 4
,W/ContextImpl( 6551): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 6551): Services init done
D/UEI.SmartControl( 6551): QS Service init finished
D/UEI.SmartControl( 6551): QS Service version name: 2.1.91
D/UEI.SmartControl( 6551): QS Service version code: 201091
D/UEI.SmartControl( 6551): Service requested: Control
D/UEI.SmartControl( 6551): Internal service binding...
I/QRemote ( 6870): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6551): Device manager: loading config....
D/UEI.SmartControl( 6551): ----------- loading internal config...
I/UEI.SmartControl( 6551): ------ IControl API: 11
D/UEI.SmartControl( 6551): File observer start...
E/UEI.SmartControl( 6551): IR Port is disabled: false
D/UEI.SmartControl( 6551): Starting file observer...
I/UEI.SmartControl( 6551): Registering callback...
I/UEI.SmartControl( 6551): ------ IControl API: 19
I/UEI.SmartControl( 6551): Registering Services Ready callback...
,E/UEI.SmartControl( 6551): Loading SETTINGS...
,D/UEI.SmartControl( 6551): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 6551): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6551): -----service ready thread exits
I/QRemote ( 6870): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6870): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6870): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6870): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6870): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6551): ------ IControl API: 8
,D/QRemote ( 6870): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6870): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6870): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6870): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6870): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6870): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6870): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,V/QRemote ( 6870): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6870): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6870): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6870): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6870): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6870): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6870): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6870): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1455023227846]
D/QRemote ( 6870): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1035): Killing 6051:com.android.gallery3d/u0a27 (adj 15): empty #17
D/QRemote ( 6870): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1035): failed to open /acct/uid_10027/pid_6051/cgroup.procs: No such file or directory
,V/QRemote ( 6870): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6870): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6870): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6870): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6870): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6870): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6870): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6870): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,V/AlarmManager( 1035): RTC_WAKEUP set : Alarm{28238db1 type 0 when 1455023226625 android} when 1455023226625
,E/WifiStateMachine( 1035):  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):1 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:46475] from screen [on:0 period:-970684920]
V/AlarmManager( 1035): RTC_WAKEUP set : Alarm{39afae17 type 0 when 1455023228421 com.android.vending} when 1455023228421
V/SIM_STK ( 1035): Menu title from STK is T-Mobile
,I/wpa_supplicant( 2661): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1035): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1035): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1035): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1035):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1035):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1035):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1035):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1035): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=111529  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=111530  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/PostponalbeReceiver( 6381): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateASSOCIATING
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6803): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6803): MCCMNC not supported: null
,D/QRemote ( 6870): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6870): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6870): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6381): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6803): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6803): MCCMNC not supported: null
D/QRemote ( 6870): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6870): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6870): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/wpa_supplicant( 2661): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1035): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=111631  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=111632  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1035):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111632
E/WifiStateMachine( 1035):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111632
E/WifiStateMachine( 1035):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111632
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111633
E/WifiStateMachine( 1035):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111633
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=111633  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/PostponalbeReceiver( 6381): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=111640  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/Tethering( 1035): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateFOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1035):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 2661): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 2661): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1035): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiStateMachine( 1035):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1035): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1035): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1035):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=111652  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=111652  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1035):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=111652
E/WifiStateMachine( 1035):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=111653
D/WifiNative-wlan0( 1035): doString: [STATUS]
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1035):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1035): setVHTCapabilityType  : false
,V/WiFiOffLoadBroadcast( 6803): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/WifiServerServiceExt( 1035): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1035): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1035): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1035): Got NetworkAgent Messenger
E/WifiConfigStore( 1035): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1035): doBoolean: SET_NETWORK 0 bssid any
,D/ConnectivityService( 1035): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1035): NetworkAgent connected
D/WifiNative-wlan0( 1035): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1035): doBoolean: SAVE_CONFIG
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 6803): MCCMNC not supported: null
D/WifiNative-wlan0( 1035): SAVE_CONFIG: returned true
E/WifiConfigStore( 1035): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1035): doBoolean: SET_NETWORK 0 bssid any
D/QRemote ( 6870): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6870): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6870): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1035): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1035): doBoolean: SAVE_CONFIG
,D/PostponalbeReceiver( 6381): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1035): SAVE_CONFIG: returned true
D/CommandListener(  318): Setting iface cfg
E/WifiStateMachine( 1035): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1035): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1035): WaitBeforeStartState
E/WifiStateMachine( 1035):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=111690  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1035):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=111690  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=111690  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1035):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=111692  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1035):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=111693  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=111693  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1035):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1035): doBoolean: DRIVER SETSUSPENDMODE 0
D/ConnectivityService( 1035): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
V/WiFiOffLoadBroadcast( 6803): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6803): MCCMNC not supported: null
D/QRemote ( 6870): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6870): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6870): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/UsbSettingsReceiver( 6803): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6803): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6803): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6803): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6803): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1035): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1035): doBoolean: SET ps 0
D/WifiNative-wlan0( 1035): SET ps 0: returned true
D/WifiNative-wlan0( 1035): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1035): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1035): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1035): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1035): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@265936d4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@265936d4 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1035): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1035): DHCP Start wake lock is acquired.
D/CommandListener(  318): Setting iface cfg
D/CommandListener(  318): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1035): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1035):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateCOMPLETED
D/ConnectivityService( 1035): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1035):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1035):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1035): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1035): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1035): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1035): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1035): doBoolean: SET ps 1
D/WifiNative-wlan0( 1035): SET ps 1: returned true
E/WifiStateMachine( 1035):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1035): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1035): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/ConnectivityService( 1035): ignoring duplicate network state non-change
D/UsbSettingsControl( 6803): [AUTORUN] getUsbConnected() : connected=true
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.Netw,orkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/UsbSettingsReceiver( 6803): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6803): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6803): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6803): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6803): [AUTORUN] onReceive() : TetherState Changed=wlan0
,D/UsbSettingsControl( 6803): [AUTORUN] setTetherStatus() : status=false
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1035): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1035): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1035): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1035): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = true, mWifiLevel = 0
D/PostponalbeReceiver( 6381): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1992): handleWifiStateChangedEvent: 1
E/WifiStateMachine( 1035): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
V/WiFiOffLoadBroadcast( 6803): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/ConnectivityService( 1035): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1035): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1035): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  318): netlink response contains error (File exists)
D/ConnectivityService( 1035): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1035): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1035): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1035): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1035): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1035): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1035):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Connected
D/ConnectivityService( 1035):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1035):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1035):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1035): currentScore = 0, newScore = 20
D/ConnectivityService( 1035):    accepting network in place of null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1035): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService( 1035): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTrac,ker( 1035): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory-1( 1872): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1872):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1035): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1035): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1035): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/WIFI    ( 1035): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1035):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1035): validation of new default Network = false
D/ConnectivityService( 1035): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1035): enableDataServiceNotify 
D/DSQN    ( 1035): start dsqn bin
,D/LocSvc_java( 1035): Sending msg: 4 arg1:1 arg2:1
D/libc-netbsd(  318): res_queryN name = clients3.google.com, class = 1, type = 28
D/LocSvc_java( 1035): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1035): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1035): ignore wifi update if we are not in OPENING or CLOSING
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = true, mWifiLevel = 0
V/NetworkPolicy( 1035): [LG_RESTRICTED] checkMobilePolicy_type()
D/ConnectivityService( 1035): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1035): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 6939): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6939): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityManager.CallbackHandler( 1469): CM callback handler got msg 524290
,D/WiFiOffLoadBroadcast( 6803): MCCMNC not supported: null
E/DSQN    ( 6939): DSQN ssw
D/QRemote ( 6870): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6870): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6870): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6381): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/WiFiOffLoadBroadcast( 6803): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6803): MCCMNC not supported: null
D/QRemote ( 6870): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/TelephonyIcons( 1469): null signal icon name: drawable/stat_sys_signal_null
D/QRemote ( 6870): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6870): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6381): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6803): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/art     ( 2144): Explicit concurrent mark sweep GC freed 23790(1419KB) AllocSpace objects, 12(1728KB) LOS objects, 51% free, 30MB/62MB, paused 1.691ms total 29.954ms
,D/WiFiOffLoadBroadcast( 6803): MCCMNC not supported: null
D/QRemote ( 6870): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6870): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6870): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6381): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6803): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/WiFiOffLoadBroadcast( 6803): MCCMNC not supported: null
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/QRemote ( 6870): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6870): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6870): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6381): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6846): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/Finsky  ( 6117): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6117): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6117): [1] 5.onFinished: Scheduling replication attempt 2.
D/PCSuite ( 6846): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6803): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6803): MCCMNC not supported: null
D/QRemote ( 6870): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6870): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6870): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6870): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 6870): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6381): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6846): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6846): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6803): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6803): MCCMNC not supported: null
D/QRemote ( 6870): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6870): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6870): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 6870): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6870): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/DhcpStateMachine( 1035): DHCPV4 request on wlan0
D/libc-netbsd(  318): res_queryN name = clients3.google.com, class = 1, type = 1
V/LgDhcpStateMachineHelper( 1035): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1035): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/dhcpcd  ( 6944): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6944): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 6944): version 5.5.6 starting
,E/dhcpcd  ( 6944): get_duid: m
D/dhcpcd  ( 6944): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
,D/dhcpcd  ( 6944): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/libc-netbsd(  318): res_queryN name = clients3.google.com succeed
D/LGDataListener(  318): argv[0]=dsqncommand
D/LGDataListener(  318): argv[1]=wlan0
D/LGDataListener(  318): argv[2]=1
D/LGDataListener(  318): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1035): DSQM DsqnNotification wlan0  1
,D/DSQN    ( 1035): start to monitor internet connection
D/dhcpcd  ( 6944): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6944): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
,D/dhcpcd  ( 6944): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 6944): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 6944): wlan0: sending REQUEST (xid 0x6940cf5f), next in 4.61 seconds
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 13:07:09 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455023229341], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455023229024]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Validated
,D/ConnectivityService( 1035): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1035):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1035):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1035): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1035): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1035): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1469): CM callback handler got msg 524290
D/ConnectivityService( 1035): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1035): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1035):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1872): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1872):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyIcons( 1469): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1035): MasterInitialState.processMessage what=3
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 5423): type=WIFI subType= reason=null isConnected=true
D/Tethering( 1035): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6381): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6381): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/GpsLocationProvider( 1035): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1035): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1035): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1035): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5423): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1035): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6972 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 6972): onCreate
,W/AppUp4:DB( 6972):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6972):  setFingerPrint start
I/AppUp4:DB( 6972):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 6972):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6972):  SDK version = 21
I/AppUp4:DB( 6972):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6972): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6972): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6972): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6972): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6972): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6972): onReceive
,D/LgDataFeature( 6972): LgDataFeature() Constructor: none
D/LgDataFeature( 6972): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 6972): Context : android.app.ReceiverRestrictedContext@1e4c151f
D/AppUp4:CustFacade( 6972): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6972): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6972): begin check event
I/AppUp4:CustModeStarterReceiver( 6972): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6972): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6972): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6972): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6972): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1035): Killing 6487:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/libprocessgroup( 1035): failed to open /acct/uid_10061/pid_6487/cgroup.procs: No such file or directory
,D/LGDMClient( 4336): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4336): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 4336): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3365): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/LGDMClient( 4336): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3365): DownloadService onCreate
,I/DownloadManager( 3365): in removeSpuriousFiles
V/DownloadManager( 3365): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 4336): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4336): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3365): created cursor android.database.sqlite.SQLiteCursor@2f76afd0 on behalf of 3365
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3365): in trimDatabase
V/DownloadManager( 3365): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3365): created cursor android.database.sqlite.SQLiteCursor@29fa6bc9 on behalf of 3365
I/ActivityManager( 1035): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7001 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3365): DownloadService onStartCommand
V/DownloadManager( 3365): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
E/LGDMClient( 4336): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4336): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4336): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3365): created cursor android.database.sqlite.SQLiteCursor@379b35ef on behalf of 3365
V/DownloadManager( 3365): processing inserted download 1
V/DownloadManager( 3365): processing inserted download 4
,V/DownloadManager( 3365): processing inserted download 7
V/DownloadManager( 3365): processing inserted download 8
V/DownloadManager( 3365): processing inserted download 9
V/DownloadManager( 3365): processing inserted download 10
V/DownloadManager( 3365): processing inserted download 16
V/DownloadManager( 3365): processing inserted download 17
,V/DownloadManager( 3365): processing inserted download 18
V/DownloadManager( 3365): processing inserted download 21
V/DownloadManager( 3365): processing inserted download 22
V/DownloadManager( 3365): DownloadService onDestroy
,W/ResourcesManager( 7001): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7001): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7001): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7001): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/LGEmail ( 7001): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7001): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7001): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7001): LgDataFeature() Constructor: none
D/LgDataFeature( 7001): LgDataFeature() Constructor Done, null
,D/eas_req ( 7001): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1035): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7031 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7001): JNI_OnLoad()
I/HubEmail( 7001): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7001): registerNatives()
I/HubEmail( 7001): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7001): registerNativeMethods()
I/HubEmail( 7001): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7001): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager( 1035): Killing 6071:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,E/WifiStateMachine( 1035):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1035):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1035):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1035):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1035): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1035): identical MTU - not setting
D/Nat464Xlat( 1035): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1035): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1035): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1469): CM callback handler got msg 524295
I/dhcpcd  ( 6944): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 6944): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 6944): wlan0: adding IP address 192.168.1.141/24
,D/dhcpcd  ( 6944): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6944): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6944): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6944): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6944): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6944): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
W/libprocessgroup( 1035): failed to open /acct/uid_10080/pid_6071/cgroup.procs: No such file or directory
W/Settings( 7001): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 7001): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     ( 1035): Explicit concurrent mark sweep GC freed 86117(4MB) AllocSpace objects, 7(624KB) LOS objects, 33% free, 44MB/66MB, paused 5.124ms total 168.108ms
,D/DhcpStateMachine( 1035): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1035): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1035): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1035): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1035): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1035): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1035): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1035): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1035): RunningState
I/LgeMiscReceiver( 3310): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3310): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3310): networkInfo.isConnected() = false
I/ActivityManager( 1035): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7074 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  318): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/ActivityManager( 1035): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7094 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1035): Killing 6094:com.google.android.apps.plus/u0a97 (adj 15): empty #17
W/libprocessgroup( 1035): failed to open /acct/uid_10097/pid_6094/cgroup.procs: No such file or directory
,I/ActivityManager( 1035): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7111 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1035): Killing 6528:com.lge.eula/1000 (adj 15): empty #17
,I/jxcore-log( 6720): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6720): 
,D/libc-netbsd(  318): res_queryN name = static-avc.lglime.com succeed
,W/libprocessgroup( 1035): failed to open /acct/uid_1000/pid_6528/cgroup.procs: No such file or directory
,I/art     ( 7111): Almond Protected OAT
,V/FormManager( 7031): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7031): Alarm would be updated, because LastCheckTime has been updated.
D/WeatherApplication( 7111): removeAccount
,D/WeatherApplication( 7111): Account.length = 0
E/WeatherApplication( 7111): OPERATOR:OPEN
D/WeatherAncestor( 7111): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:7:11
,I/ActivityManager( 1035): Killing 5942:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
D/Weather.Utils( 7111): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7111): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7111): 2 : This is isUpdating : false
D/WeatherAncestor( 7111): connectivity changed - connection : true
,D/WeatherService( 7111): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7111): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7111): 2 : currentPackageVersion: 4.40.4
,D/ForecastDataCache( 7111): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7111): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7111): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:7:11
,E/WifiStateMachine( 1035):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1035):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1035):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1035):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1035):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,I/ActivityManager( 1035): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7130 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1035): Killing 6569:com.lge.bnr/1000 (adj 15): empty #17
W/libprocessgroup( 1035): failed to open /acct/uid_10005/pid_5942/cgroup.procs: No such file or directory
,W/libprocessgroup( 1035): failed to open /acct/uid_1000/pid_6569/cgroup.procs: No such file or directory
V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{28686a8a type 2 when 114608 com.google.android.gms} when 114608
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7130): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7130): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7130): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7130): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
V/WifiInternetCheck( 1035): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1035): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1035): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5423): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1035): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/jxcore-log( 6720): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6720): 
,I/WebViewFactory( 7130): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 7130): Loading: webviewchromium
I/LibraryLoader( 7130): Time to load native libraries: 2 ms (timestamps 4906-4908)
I/LibraryLoader( 7130): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7130): Binding Chromium to main looper Looper (main, tid 1) {306dd446}
I/LibraryLoader( 7130): Expected native library version number "",actual native library version number ""
,I/chromium( 7130): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7130): Initializing chromium process, renderers=0
,W/art     ( 7130): Attempt to remove local handle scope entry from IRT, ignoring
,V/AudioPolicyService(  324): registerClient() client 0xb558a480, uid 10093
,W/AudioManagerAndroid( 7130): Requires BLUETOOTH permission
W/chromium( 7130): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7130): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,I/chromium( 7130): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
I/jxcore-log( 6720): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6720): 
,I/Adreno-EGL( 7130): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7130): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7130): Build Date: 12/12/14 금
I/Adreno-EGL( 7130): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7130): Remote Branch: 
I/Adreno-EGL( 7130): Local Patches: 
I/Adreno-EGL( 7130): Reconstruct Branch: 
I/jxcore-log( 6720): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6720): 
I/jxcore-log( 6720): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6720): 
I/NSApplication( 7130): Starting up...
,I/jxcore-log( 6720): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 6720): 
,I/ActivityManager( 1035): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7191 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1035): Killing 5971:com.android.providers.calendar/u0a14 (adj 15): empty #17
I/art     (  373): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 410us total 21.788ms
,I/art     (  373): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 402us total 21.521ms
,I/art     (  373): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 404us total 18.624ms
,W/libprocessgroup( 1035): failed to open /acct/uid_10014/pid_5971/cgroup.procs: No such file or directory
,W/ResourcesManager( 7191): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 2326): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 2326): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
D/PostponalbeReceiver( 6381): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6381): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 6972): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6972): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6972): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6972): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6972): onReceive
,D/AppUp4:CustFacade( 6972): Context : android.app.ReceiverRestrictedContext@1e4c151f
D/AppUp4:CustFacade( 6972): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6972): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6972): begin check event
I/AppUp4:CustModeStarterReceiver( 6972): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4336): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4336): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/GLSActivity( 2144): [ac] getting account id
W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/GLSUser ( 2144): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
V/DownloadManager( 3365): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4336): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4336): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/LGDMClient( 4336): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3365): DownloadService onCreate
I/LGDMClient( 4336): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3365): in removeSpuriousFiles
V/DownloadManager( 3365): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3365): created cursor android.database.sqlite.SQLiteCursor@34fb85 on behalf of 3365
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
V/DownloadManager( 3365): DownloadService onStartCommand
V/DownloadManager( 3365): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3365): in trimDatabase
V/DownloadManager( 3365): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3365): created cursor android.database.sqlite.SQLiteCursor@520a8e8 on behalf of 3365
V/DownloadManager( 3365): processing inserted download 1
V/DownloadManager( 3365): processing inserted download 4
V/DownloadManager( 3365): processing inserted download 7
V/DownloadManager( 3365): created cursor android.database.sqlite.SQLiteCursor@2dcecb01 on behalf of 3365
W/Settings( 7001): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3365): processing inserted download 8
,W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3365): processing inserted download 9
W/Settings( 7001): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3365): processing inserted download 10
V/DownloadManager( 3365): processing inserted download 16
V/DownloadManager( 3365): processing inserted download 17
V/DownloadManager( 3365): processing inserted download 18
V/DownloadManager( 3365): processing inserted download 21
,V/DownloadManager( 3365): processing inserted download 22
E/LGDMClient( 4336): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
I/LgeMiscReceiver( 3310): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
D/LGDMClient( 4336): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
I/LgeMiscReceiver( 3310): action = android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4336): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LgeMiscReceiver( 3310): networkInfo.isConnected() = false
V/DownloadManager( 3365): DownloadService onDestroy
D/WeatherAncestor( 7111): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:7:12
D/Weather.Utils( 7111): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7111): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7111): 2 : This is isUpdating : false
D/WeatherAncestor( 7111): connectivity changed - connection : true
D/WeatherService( 7111): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@21636635
,D/ForecastDataCache( 7111): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7111): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7111): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7111): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7111): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:7:12
D/ChimeraCfgMgr( 2326): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/Kids    ( 2326): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,V/FormManager( 7031): There are no updated forms. The schedule will be deleted.
,D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  318): res_queryN name = mtalk.google.com, class = 1, type = 1
D/PostponalbeReceiver( 6381): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6381): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 6972): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6972): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6972): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6972): [onReceive] request level :IDLE....
V/FormManager( 7031): Alarm would be updated, because LastCheckTime has been updated.
I/AppUp4:CustModeStarterReceiver( 6972): onReceive
,D/AppUp4:CustFacade( 6972): Context : android.app.ReceiverRestrictedContext@1e4c151f
D/AppUp4:CustFacade( 6972): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6972): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6972): begin check event
I/AppUp4:CustModeStarterReceiver( 6972): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4336): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4336): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3365): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4336): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4336): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4336): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 4336): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3365): DownloadService onCreate
I/DownloadManager( 3365): in removeSpuriousFiles
D/libc-netbsd(  318): res_queryN name = mtalk.google.com succeed
,V/DownloadManager( 3365): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3365): DownloadService onStartCommand
V/DownloadManager( 3365): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
E/LGDMClient( 4336): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3365): created cursor android.database.sqlite.SQLiteCursor@27dc163d on behalf of 3365
W/Settings( 7001): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 4336): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4336): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
W/Settings( 7001): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3365): created cursor android.database.sqlite.SQLiteCursor@37aa3e32 on behalf of 3365
,I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/LgeMiscReceiver( 3310): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3310): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3310): networkInfo.isConnected() = true
D/PhoneState( 3310): setPdpRejectCasuse : false
I/DownloadManager( 3365): in trimDatabase
V/DownloadManager( 3365): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3365): processing inserted download 1
V/DownloadManager( 3365): processing inserted download 4
V/DownloadManager( 3365): processing inserted download 7
V/DownloadManager( 3365): processing inserted download 8
,V/DownloadManager( 3365): created cursor android.database.sqlite.SQLiteCursor@1f1be783 on behalf of 3365
V/DownloadManager( 3365): processing inserted download 9
V/DownloadManager( 3365): processing inserted download 10
V/DownloadManager( 3365): processing inserted download 16
D/WeatherAncestor( 7111): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:7:12
V/DownloadManager( 3365): processing inserted download 17
D/Weather.Utils( 7111): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7111): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7111): 2 : This is isUpdating : false
D/WeatherAncestor( 7111): connectivity changed - connection : true
D/WeatherService( 7111): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@21636635
V/DownloadManager( 3365): processing inserted download 18
D/ForecastDataCache( 7111): 2 : lastUpdatedTime: 1430558561343
,D/ForecastDataCache( 7111): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7111): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7111): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7111): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:7:12
V/DownloadManager( 3365): processing inserted download 21
V/DownloadManager( 3365): processing inserted download 22
D/UEI.SmartControl( 6551): Internal timer expired: 4
D/UEI.SmartControl( 6551): unbind internal service
V/DownloadManager( 3365): DownloadService onDestroy
,D/ChimeraCfgMgr( 2326): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 2326): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
V/FormManager( 7031): There are no updated forms. The schedule will be deleted.
V/FormManager( 7031): Alarm would be updated, because LastCheckTime has been updated.
,D/serial_port( 6551): close(fd = 24)
I/UEI.SmartControl( 6551): Serial port is closed.
,D/GCM     ( 2144): Connected
D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  318): res_queryN name = www.google.com, class = 1, type = 1
,D/GCM     ( 2144): Message class com.google.f.a.a.p
,D/libc-netbsd(  318): res_queryN name = www.google.com succeed
,D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  318): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  318): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1035): isHttpConnectionAvailable - We got a valid response : 204
,I/CloudHub( 2237): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19980
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 117943328812; DSPS: 4006265; Offset : -4332888081
,I/GAV4    ( 7130): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 6720): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6720): 
,I/jxcore-log( 6720): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6720): 
I/jxcore-log( 6720): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6720): 
,I/ActivityManager( 1035): Killing 6634:com.google.android.apps.books/u0a54 (adj 15): empty #17
,W/libprocessgroup( 1035): failed to open /acct/uid_10054/pid_6634/cgroup.procs: No such file or directory
,I/jxcore-log( 6720): Test app app.js loaded
I/jxcore-log( 6720): 
,I/chromium( 6720): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6720): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6720): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6720): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6720): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6720): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6720): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6720): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6720): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6720): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6720): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd53ecd added. We now have 1 listener(s)
,I/jxcore-log( 6720): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6720): 
,V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{3150b14a type 2 when 131464 android} when 131464
,V/QRemote ( 6870): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,D/QRemote ( 6870): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:9038
,V/AlarmManager( 1035): RTC_WAKEUP set : Alarm{1d6f51d8 type 0 when 1455023248868 com.android.vending} when 1455023248868
,V/SIM_STK ( 1035): Menu title from STK is T-Mobile
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6117): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6117): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6117): [1] 5.onFinished: Scheduling replication attempt 3.
,I/CloudHub( 2237): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,I/CloudHub( 2237): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,W/ProcessCpuTracker( 1035): Skipping unknown process pid 7311
,W/ProcessCpuTracker( 1035): Skipping unknown process pid 7314
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 137945311357; DSPS: 4661690; Offset : -4332889283
,E/WifiStateMachine( 1035):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1035):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1035):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 157947048016; DSPS: 5317107; Offset : -4332892152
,V/AlarmManager( 1035): RTC_WAKEUP set : Alarm{3948c6ab type 0 when 1455023273182 com.android.vending} when 1455023273182
,V/SIM_STK ( 1035): Menu title from STK is T-Mobile
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6117): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6117): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6117): [1] 5.onFinished: Scheduling replication attempt 4.
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=123015549, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{14018395 type 2 when 168629 android} when 168629
D/[Concierge]Service( 2644): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=123015549 [*alarm*], flags=0x0
,I/ActivityManager( 1035): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=7346 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ReaderUtils( 7346): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,W/GAV2    ( 7346): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/art     ( 1035): Explicit concurrent mark sweep GC freed 35028(1608KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.735ms total 122.573ms
,I/BooksApp( 7346): Created application version: 3.2.35 (30235)
,I/BooksSync( 7346): Starting books sync
,D/BooksSync( 7346): started syncMyEbooks
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2144): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2144): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2144): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2144): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7346): Authentication error
E/BooksAccountManager( 7346): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7346): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7346): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7346): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7346): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7346): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1416): onNotificationPosted
,E/HttpHelper( 7346): null auth token
,D/SmartCoverUpdateMonitor( 1416): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1416): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1416): handleNotificationPosted(true)
D/QuickCircle( 1416): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1416): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): post do just update job
D/LgeQuickCoverNotificationData( 1416): showAll3
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1416): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1416): updateNotificationData: count=3
D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  318): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/QuickStatusbarLayout( 1416): Notification difference=198
D/QuickStatusbarLayout( 1416): child = android.widget.LinearLayout{3c6df3e7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  318): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7346): Error response from books API: {
W/ApiaryClient( 7346):  "error": {
W/ApiaryClient( 7346):   "errors": [
W/ApiaryClient( 7346):    {
W/ApiaryClient( 7346):     "domain": "global",
W/ApiaryClient( 7346):     "reason": "required",
W/ApiaryClient( 7346):     "message": "Login Required",
W/ApiaryClient( 7346):     "locationType": "header",
W/ApiaryClient( 7346):     "location": "Authorization"
W/ApiaryClient( 7346):    }
W/ApiaryClient( 7346):   ],
W/ApiaryClient( 7346):   "code": 401,
W/ApiaryClient( 7346):   "message": "Login Required"
W/ApiaryClient( 7346):  }
W/ApiaryClient( 7346): }
,W/ApiaryClient( 7346): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7346): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3824064342672789828&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7346): Headers:
W/ApiaryClient( 7346): accept-encoding: [gzip]
W/ApiaryClient( 7346): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7346): gdata-version: 2
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1416): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1416): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1416): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1416): handleNotificationPosted(true)
D/QuickCircle( 1416): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1416): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): post do just update job
D/LgeQuickCoverNotificationData( 1416): showAll3
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1416): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1416): updateNotificationData: count=3
W/GLSActivity( 2144): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2144): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2144): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2144): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7346): Authentication error
E/BooksAccountManager( 7346): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7346): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7346): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7346): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7346): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7346): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7346): null auth token
D/QuickStatusbarLayout( 1416): Notification difference=198
D/QuickStatusbarLayout( 1416): child = android.widget.LinearLayout{3c6df3e7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7346): Error response from books API: {
W/ApiaryClient( 7346):  "error": {
W/ApiaryClient( 7346):   "errors": [
W/ApiaryClient( 7346):    {
W/ApiaryClient( 7346):     "domain": "global",
W/ApiaryClient( 7346):     "reason": "required",
W/ApiaryClient( 7346):     "message": "Login Required",
W/ApiaryClient( 7346):     "locationType": "header",
W/ApiaryClient( 7346):     "location": "Authorization"
W/ApiaryClient( 7346):    }
W/ApiaryClient( 7346):   ],
W/ApiaryClient( 7346):   "code": 401,
W/ApiaryClient( 7346):   "message": "Login Required"
W/ApiaryClient( 7346):  }
W/ApiaryClient( 7346): }
,W/ApiaryClient( 7346): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7346): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3824064342672789828&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7346): Headers:
W/ApiaryClient( 7346): accept-encoding: [gzip]
W/ApiaryClient( 7346): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7346): gdata-version: 2
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1416): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1416): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1416): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1416): handleNotificationPosted(true)
D/QuickCircle( 1416): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1416): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): post do just update job
D/LgeQuickCoverNotificationData( 1416): showAll3
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1416): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1416): updateNotificationData: count=3
W/GLSActivity( 2144): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2144): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2144): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2144): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7346): Authentication error
E/BooksAccountManager( 7346): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7346): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7346): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7346): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7346): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7346): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7346): null auth token
,D/QuickStatusbarLayout( 1416): Notification difference=198
,D/QuickStatusbarLayout( 1416): child = android.widget.LinearLayout{3c6df3e7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7346): Error response from books API: {
W/ApiaryClient( 7346):  "error": {
W/ApiaryClient( 7346):   "errors": [
W/ApiaryClient( 7346):    {
W/ApiaryClient( 7346):     "domain": "global",
W/ApiaryClient( 7346):     "reason": "required",
W/ApiaryClient( 7346):     "message": "Login Required",
W/ApiaryClient( 7346):     "locationType": "header",
W/ApiaryClient( 7346):     "location": "Authorization"
W/ApiaryClient( 7346):    }
W/ApiaryClient( 7346):   ],
W/ApiaryClient( 7346):   "code": 401,
W/ApiaryClient( 7346):   "message": "Login Required"
W/ApiaryClient( 7346):  }
W/ApiaryClient( 7346): }
,W/ApiaryClient( 7346): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7346): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3824064342672789828&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7346): Headers:
W/ApiaryClient( 7346): accept-encoding: [gzip]
W/ApiaryClient( 7346): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7346): gdata-version: 2
I/GAV2    ( 7346): Thread[GAThread,5,main]: No campaign data found.
,E/BooksSync( 7346): Soft error: 
E/BooksSync( 7346): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7346): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3824064342672789828&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7346): Headers:
E/BooksSync( 7346): accept-encoding: [gzip]
E/BooksSync( 7346): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7346): gdata-version: 2
E/BooksSync( 7346): 
E/BooksSync( 7346): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7346): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7346): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7346): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7346): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7346): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7346): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7346): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7346): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7346): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7346): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7346): {
E/BooksSync( 7346):  "error": {
E/BooksSync( 7346):   "errors": [
E/BooksSync( 7346):    {
E/BooksSync( 7346):     "domain": "global",
E/BooksSync( 7346):     "reason": "required",
E/BooksSync( 7346):     "message": "Login Required",
E/BooksSync( 7346):     "locationType": "header",
E/BooksSync( 7346):     "location": "Authorization"
E/BooksSync( 7346):    }
E/BooksSync( 7346):   ],
E/BooksSync( 7346):   "code": 401,
E/BooksSync( 7346):   "message": "Login Required"
E/BooksSync( 7346):  }
E/BooksSync( 7346): }
E/BooksSync( 7346): 
E/BooksSync( 7346): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7346): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7346): 	... 8 more
E/BooksSync( 7346): Sync error
E/BooksSync( 7346): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7346): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3824064342672789828&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7346): Headers:
E/BooksSync( 7346): accept-encoding: [gzip]
E/BooksSync( 7346): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7346): gdata-version: 2
E/BooksSync( 7346): 
E/BooksSync( 7346): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7346): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7346): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7346): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7346): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7346): 	at com.google.android.apps.books.data.NetworkTas,kQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7346): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7346): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7346): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7346): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7346): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7346): {
E/BooksSync( 7346):  "error": {
E/BooksSync( 7346):   "errors": [
E/BooksSync( 7346):    {
E/BooksSync( 7346):     "domain": "global",
E/BooksSync( 7346):     "reason": "required",
E/BooksSync( 7346):     "message": "Login Required",
E/BooksSync( 7346):     "locationType": "header",
E/BooksSync( 7346):     "location": "Authorization"
E/BooksSync( 7346):    }
E/BooksSync( 7346):   ],
E/BooksSync( 7346):   "code": 401,
E/BooksSync( 7346):   "message": "Login Required"
E/BooksSync( 7346):  }
E/BooksSync( 7346): }
E/BooksSync( 7346): 
E/BooksSync( 7346): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7346): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7346): 	... 8 more
I/BooksSync( 7346): Finished books sync
I/ActivityManager( 1035): Killing 2237:com.lge.music/u0a34 (adj 15): empty #17
,D/SyncManager( 1035): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 168629, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/AudioFlinger(  324): 2237 died, releasing its sessions
V/AudioFlinger(  324):  pid 1872 @ 0
V/AudioFlinger(  324):  pid 3310 @ 1
V/AudioFlinger(  324):  pid 3310 @ 2
W/libprocessgroup( 1035): failed to open /acct/uid_10034/pid_2237/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 177949064570; DSPS: 5972533; Offset : -4332889602
,V/AlarmManager( 1035): RTC_WAKEUP set : Alarm{31e61586 type 0 when 1455023297643 com.android.vending} when 1455023297643
,V/SIM_STK ( 1035): Menu title from STK is T-Mobile
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6117): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6117): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6117): [1] 5.onFinished: Scheduling replication attempt 5.
I/[SystemUI]LGPowerUI( 1469): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1469): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1469): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 297
I/[SystemUI]LGPowerUI( 1469): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1035): battery changed pluggedType: 2
,D/LEDHandler( 1992): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1992): Battery Level Remaining: 100%
D/LEDHandler( 1992): Battery Temp: 297, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1469): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 3812): Disconnected process message: 10, size: 0
D/LGDMClient( 4336): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4336): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1469): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1469): On Skip Timer : true
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 197951594564; DSPS: 6627976; Offset : -4332892802
,V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{9c140f8 type 2 when 198799 android} when 198799
,V/AlarmManager( 1035): RTC_WAKEUP set : Alarm{2224ec36 type 0 when 1455023321267 com.android.vending} when 1455023321267
,V/SIM_STK ( 1035): Menu title from STK is T-Mobile
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6117): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6117): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6117): [1] 5.onFinished: Giving up after 6 failures.
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 217953708878; DSPS: 7283405; Offset : -4332884148
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
,I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
,I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{3a82d828 type 2 when 209967 android} when 209967
,V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{1e826941 type 2 when 184655 com.google.android.gms} when 184655
,D/[Concierge]Service( 2644): onStartCommand(). Type : 9
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 2144): Vacuum at: now=1455023352920 tag=VacuumService
,I/GoogleURLConnFactory( 2144): Using platform SSLCertificateSocketFactory
,W/Uploader( 2144): No account for auth token provided
,D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  318): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  318): res_queryN name = play.googleapis.com succeed
,W/Uploader( 2144): No account for auth token provided
,W/Uploader( 2144): No account for auth token provided
,W/Uploader( 2144): No account for auth token provided
,W/Uploader( 2144):  no longer exists, so no auth token.
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 237955638818; DSPS: 7938829; Offset : -4332907281
,I/jxcore-log( 6720): --= Surplus to requirements =--
I/jxcore-log( 6720): 
I/jxcore-log( 6720): ****TEST TOOK:  ms ****
I/jxcore-log( 6720): 
I/jxcore-log( 6720): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6720): 
,D/AndroidRuntime( 7463): 
D/AndroidRuntime( 7463): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7463): CheckJNI is OFF
D/AndroidRuntime( 7463): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1035): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1035): Killing 6720:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,I/WindowState( 1035): WIN DEATH: Window{3b29241 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1035): Client connection lost with reason: 4
,D/InputDispatcher( 1035): Window went away: Window{3b29241 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings( 1035): Skipping PackageSetting{3d33af64 com.example.hello/10319} due to missing metadata
,I/ActivityManager( 1035):   Force finishing activity ActivityRecord{17754362 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  363): DFP En is all cleared set to be enabled
W/ActivityManager( 1035): Spurious death for ProcessRecord{3537a46c 6720:com.test.thalitest/u0a311}, curProc for 6720: null
I/ActivityManager( 1035): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
,I/ActivityManager( 1035):   Force finishing activity ActivityRecord{17754362 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1035): Duplicate finish request for ActivityRecord{17754362 u0 com.test.thalitest/.MainActivity t4 f}
,D/SplitWindowPolicy( 1992): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1992): topRunningActivity=ActivityInfo{23efe9af co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
,D/SplitWindowPolicy( 1992): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1992): topRunningActivity=ActivityInfo{12b401bc co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/KeyguardModel( 1469): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 2103): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2103): [Launcher.java:903:onResume()]onResume
,D/LIA_Service_RemotePackageHandler( 2051): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/InputReader( 1035): Reconfiguring input devices.  changes=0x00000010
D/PostponalbeReceiver( 6381): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
D/LIA_MrGDBLogger_PackageInfoDetector( 3751): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,I/art     ( 4561): Explicit concurrent mark sweep GC freed 16911(943KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 617us total 58.469ms
E/LGBluetoothAvrcpQcomAdapter( 3812): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3812): [BTUI] [+] updateMediaPlayerInfo
W/System.err( 4505): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4505): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4505): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4505): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4505): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4505): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4505): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4505): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4505): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4505): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4505): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4505): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
W/GeofencerStateMachine( 1837): Ignoring removeGeofence because network location is disabled.
,I/ActivityManager( 1035): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7496 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,I/[LGHome]EVENT( 2103): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2103): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
I/[LGHome]GBoardWebView( 2103): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1934): notifyUserLog: 1000003
,D/LIA_Informant_ActionManagerMessageHandler( 3751): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]LGActivityUtil( 2103): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2103): [Launcher.java:1056:onResume()]onResume end
I/[SystemUI]QSlideListController( 1469): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2103): [Launcher.java:1114:onPause()]onPause
I/[LGHome]GBoardWebView( 2103): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/ActionManagerService( 1934): notifyUserLog: 1000004
,D/LIA_Informant_ActionManagerMessageHandler( 3751): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 3751): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2103): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2103): , create_time: 1430558575574
I/GBoardWebViewUtils( 2103): , expire_time: 0
I/GBoardWebViewUtils( 2103): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2103): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2103): , display: false
I/GBoardWebViewUtils( 2103): , animation: false }
I/GBoardWebViewUtils( 2103): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2103): , create_time: 1430558575600
I/GBoardWebViewUtils( 2103): , expire_time: 0
I/GBoardWebViewUtils( 2103): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2103): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2103): , display: false
I/GBoardWebViewUtils( 2103): , animation: false }
I/GBoardWebViewUtils( 2103): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1454599632914
I/GBoardWebViewUtils( 2103): , create_time: 1454599633839
I/GBoardWebViewUtils( 2103): , expire_time: 0
I/GBoardWebViewUtils( 2103): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2103): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2103): , display: false
I/GBoardWebViewUtils( 2103): , animation: false }
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1469): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1469): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/SplitUIManager( 1889): split_name #11 / not available #0
D/SplitUIService( 1889): removed split : 
,D/WallpaperManager( 2103): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/SystemUI[Framework]( 1035): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1035): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1035): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1035): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1035): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1d092eb6,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1035): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
V/SIM_STK ( 1035): Menu title from STK is T-Mobile
I/[LGHome]EVENT( 2103): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2103): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,I/art     ( 1035): Explicit concurrent mark sweep GC freed 26730(1514KB) AllocSpace objects, 6(480KB) LOS objects, 33% free, 44MB/66MB, paused 2.998ms total 192.038ms
I/art     ( 1035): WaitForGcToComplete blocked for 185.709ms for cause Explicit
,I/LockScreenSettings( 7496): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/administrator( 1035): Handling package changes for user 0
,V/SIM_STK ( 1035): Menu title from STK is T-Mobile
V/SIM_STK ( 1035): Menu title from STK is T-Mobile
D/AppUp4:PreloadHelper( 6972): added Exclude : com.test.thalitest
D/SplitUIManager( 1889): split_name #11 / not available #0
I/SplitUIService( 1889): split app #11
,I/ActivityManager( 1035): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7516 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,D/KeyguardModel( 1469): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1469): createShortcutInfo...
I/[LGHome]EVENT( 2103): [Launcher.java:5349:onStop()]onStop
D/KeyguardModel( 1469): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1469): createShortcutInfo...
V/SIM_STK ( 1035): Menu title from STK is T-Mobile
,W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1469): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1469): createShortcutInfo...
,W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
W/ActivityManager( 1035): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,D/LGBluetoothAvrcpQcomAdapter( 3812): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3812): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3812): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3812): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3812): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3812): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3812): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3812): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3812): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3812): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3812): [BTUI] [-] updateMediaPlayerInfo
D/KeyguardModel( 1469): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1469): createShortcutInfo...
,W/ResourcesManager( 7516): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7516): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7516): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7516): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7516): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1469): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1469): createShortcutInfo...
,I/ActivityManager( 1035): Killing 6846:com.lge.sync/1000 (adj 15): empty #17
I/NotificationService( 1035): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1035): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1035): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher.Model( 2103): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2103): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2103): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2103): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2103): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2103): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,I/[LGHome]Launcher.Model( 2103): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2103): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2103): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2103): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2103): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,I/[LGHome]Launcher.Model( 2103): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2103): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/KeyguardModel( 1469): handleShortcutListChanged...
I/[Concierge]WidgetView( 2103): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/PhoneStatusBar( 1469): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1469): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1469):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1469): , Keyguard show=false, IME shown=false, Panel expanded=false
W/libprocessgroup( 1035): failed to open /acct/uid_1000/pid_6846/cgroup.procs: No such file or directory
D/[Concierge]Service( 2644): onStartCommand(). Type : 8
D/[Concierge]Service( 2644): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]WidgetView( 2103): change position of spinner
D/[Concierge]Service( 2644): Update widget ID : 11
D/TaskPersister( 1035): removeObsoleteFile: deleting file=4_task.xml
I/Timeline( 1035): Timeline: Activity_windows_visible id: ActivityRecord{14c17aaf u0 com.lge.launcher2/.Launcher t3} time:257219
D/KeyguardModel( 1469): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1469): createShortcutInfo...
,D/KeyguardModel( 1469): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1469): createShortcutInfo...
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[Concierge]WidgetView( 2103): initWebView(). Time : 1455023374219
D/[Concierge]Service( 2644): onStartCommand(). Type : 0
D/KeyguardModel( 1469): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1469): createShortcutInfo...
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1469): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1469): createShortcutInfo...
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1469): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1469): createShortcutInfo...
D/KeyguardModel( 1469): handleShortcutListChanged...
,I/SystemConfig( 7516): BUILD Country: EU
I/SystemConfig( 7516): BUILD Operator: OPEN
I/art     ( 1035): Explicit concurrent mark sweep GC freed 8766(475KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.940ms total 267.466ms
I/[Concierge]WebView( 2103): Return exist ConciergeWebView. Reuse : 558984061
D/[Concierge]WidgetView( 2103): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2103): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,I/[LgeWidgetLib]ExtViewHost( 2103): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@eacc85c
I/[LGHome]EVENT( 2103): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2103): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2103): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2103): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2103): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2103): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2103): Widget kill message received. Destory myself. My : 1455023144900, New one : 1455023374219
D/[Concierge]WidgetView( 2103): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2103): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2103): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2103): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2103): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2103): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2103): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2103): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2103): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2103): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ActivityManager( 1035): Killing 6803:com.android.settings/1000 (adj 15): empty #17
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2103): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2103): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,W/ResourcesManager( 1035): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 2103): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2103): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourceType( 1035): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
D/AndroidRuntime( 7463): Shutting down VM
,I/Timeline( 2103): Timeline: Activity_idle id: android.os.BinderProxy@1c165630 time:257345
W/libprocessgroup( 1035): failed to open /acct/uid_1000/pid_6803/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 2103): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/VoicemailCleanupService( 2167): Cleaning up data for package: com.test.thalitest
I/SystemConfig( 7516): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7516): existFile = false
I/SystemConfig( 7516): canReadFile = false
I/SystemConfig( 7516): systemFeature RCS result false
,D/SystemConfig( 7516): refreshRcsSupport() :false
I/PackageChangeReceiver( 7001): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/ActivityManager( 1035): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7539 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 7539): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7539): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7539): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7539): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/chromium( 2103): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/GBoardtInterface( 2103): onReloaded()
,I/GBoardWebViewClient( 2103): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 3751): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 3751): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1934): notifyUserLog: 1000001
,D/LIA_Informant_ActionManagerMessageHandler( 3751): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3751): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1934): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3751): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3751): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3751): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3751): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3751): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2103): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2103): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2103): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2103): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2103): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2103): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,I/AppConfig( 7539): Total System Memory = 2995761152
D/SystemHelper( 7539): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager( 1035): Killing 7031:com.lge.formmanager/u0a26 (adj 15): empty #17
,D/LIA_Service_NativeEventReceiver( 2051): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/LIA_Service_PlatformUtil( 2051): startLIAService() : Trying to start LIA service ...
W/libprocessgroup( 1035): failed to open /acct/uid_10026/pid_7031/cgroup.procs: No such file or directory
,D/LIA_Service_LIAService( 2051): onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
D/PostponalbeReceiver( 6381): OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/ActivityManager( 1035): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=7561 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a

```
