#### Test 583805004251330_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
V/GLSActivity( 2180): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2180): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2180): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2180): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2180): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2180): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
--------- beginning of system
V/NotificationService( 1047): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1047): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1047): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1047): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1047): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2180): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2180): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2180): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2180): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2180): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2180): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2180): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6769): Authentication error
E/BooksAccountManager( 6769): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6769): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6769): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6769): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6769): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6769): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6769): null auth token
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{d09c689 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6769): Error response from books API: {
W/ApiaryClient( 6769):  "error": {
W/ApiaryClient( 6769):   "errors": [
W/ApiaryClient( 6769):    {
W/ApiaryClient( 6769):     "domain": "global",
W/ApiaryClient( 6769):     "reason": "required",
W/ApiaryClient( 6769):     "message": "Login Required",
W/ApiaryClient( 6769):     "locationType": "header",
W/ApiaryClient( 6769):     "location": "Authorization"
W/ApiaryClient( 6769):    }
W/ApiaryClient( 6769):   ],
W/ApiaryClient( 6769):   "code": 401,
W/ApiaryClient( 6769):   "message": "Login Required"
W/ApiaryClient( 6769):  }
W/ApiaryClient( 6769): }
W/ApiaryClient( 6769): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6769): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1851332253669548705&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6769): Headers:
W/ApiaryClient( 6769): accept-encoding: [gzip]
W/ApiaryClient( 6769): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6769): gdata-version: 2
V/GLSActivity( 2180): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2180): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2180): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2180): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2180): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2180): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1047): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1047): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1047): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1047): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1047): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2180): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2180): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2180): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2180): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2180): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2180): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2180): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6769): Authentication error
E/BooksAccountManager( 6769): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6769): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6769): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6769): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6769): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6769): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6769): null auth token
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{d09c689 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6769): Error response from books API: {
W/ApiaryClient( 6769):  "error": {
W/ApiaryClient( 6769):   "errors": [
W/ApiaryClient( 6769):    {
W/ApiaryClient( 6769):     "domain": "global",
W/ApiaryClient( 6769):     "reason": "required",
W/ApiaryClient( 6769):     "message": "Login Required",
W/ApiaryClient( 6769):     "locationType": "header",
W/ApiaryClient( 6769):     "location": "Authorization"
W/ApiaryClient( 6769):    }
W/ApiaryClient( 6769):   ],
W/ApiaryClient( 6769):   "code": 401,
W/ApiaryClient( 6769):   "message": "Login Required"
W/ApiaryClient( 6769):  }
W/ApiaryClient( 6769): }
W/ApiaryClient( 6769): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6769): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1851332253669548705&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6769): Headers:
W/ApiaryClient( 6769): accept-encoding: [gzip]
W/ApiaryClient( 6769): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6769): gdata-version: 2
,D/AndroidRuntime( 6834): 
D/AndroidRuntime( 6834): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6834): CheckJNI is OFF
D/AndroidRuntime( 6834): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1047): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1977): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1047): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1047): setTaskToReturnTo : TaskRecord{52eb76e #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1047): setTaskToReturnTo : TaskRecord{52eb76e #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1047): AppWindowTokenEx init.. 
E/GBMv2   (  338): DFP En is all cleared set to be enabled
I/ActivityManager( 1047): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6853 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6834): Shutting down VM
V/ActivityManager( 1047): Display changed displayId=0
D/DSDPConnection( 1858): Display #0 changed.
D/SplitWindowPolicy( 1977): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1977): topRunningActivity=ActivityInfo{297a709b co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1977): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1977): topRunningActivity=ActivityInfo{2a535c38 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6853): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
E/BooksSync( 6769): Soft error: 
E/BooksSync( 6769): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6769): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1851332253669548705&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6769): Headers:
E/BooksSync( 6769): accept-encoding: [gzip]
E/BooksSync( 6769): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6769): gdata-version: 2
E/BooksSync( 6769): 
E/BooksSync( 6769): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6769): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6769): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6769): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6769): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6769): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6769): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6769): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6769): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6769): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6769): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6769): {
E/BooksSync( 6769):  "error": {
E/BooksSync( 6769):   "errors": [
E/BooksSync( 6769):    {
E/BooksSync( 6769):     "domain": "global",
E/BooksSync( 6769):     "reason": "required",
E/BooksSync( 6769):     "message": "Login Required",
E/BooksSync( 6769):     "locationType": "header",
E/BooksSync( 6769):     "location": "Authorization"
E/BooksSync( 6769):    }
E/BooksSync( 6769):   ],
E/BooksSync( 6769):   "code": 401,
E/BooksSync( 6769):   "message": "Login Required"
E/BooksSync( 6769):  }
E/BooksSync( 6769): }
E/BooksSync( 6769): 
E/BooksSync( 6769): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6769): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6769): 	... 8 more
E/BooksSync( 6769): Sync error
E/BooksSync( 6769): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6769): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1851332253669548705&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6769): Headers:
E/BooksSync( 6769): accept-encoding: [gzip]
E/BooksSync( 6769): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6769): gdata-version: 2
E/BooksSync( 6769): 
E/BooksSync( 6769): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6769): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6769): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6769): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6769): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6769): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6769): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6769): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6769): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6769): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6769): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6769): {
E/BooksSync( 6769):  "error": {
E/BooksSync( 6769):   "errors": [
E/BooksSync( 6769):    {
E/BooksSync( 6769):     "domain": "global",
E/BooksSync( 6769):     "reason": "required",
E/BooksSync( 6769):     "message": "Login Required",
E/BooksSync( 6769):     "locationType": "header",
E/BooksSync( 6769):     "location": "Authorization"
E/BooksSync( 6769):    }
E/BooksSync( 6769):   ],
E/BooksSync( 6769):   "code": 401,
E/BooksSync( 6769):   "message": "Login Required"
E/BooksSync( 6769):  }
E/BooksSync( 6769): }
E/BooksSync( 6769): 
E/BooksSync( 6769): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6769): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6769): 	... 8 more
I/BooksSync( 6769): Finished books sync
I/ActivityManager( 1047): Killing 6529:com.google.android.partnersetup/u0a8 (adj 15): empty #17
D/SyncManager( 1047): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 79710, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/WebViewFactory( 6853): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,W/libprocessgroup( 1047): failed to open /acct/uid_10008/pid_6529/cgroup.procs: No such file or directory
,I/LibraryLoader( 6853): Loading: webviewchromium
I/LibraryLoader( 6853): Time to load native libraries: 3 ms (timestamps 6597-6600)
I/LibraryLoader( 6853): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6853): Binding Chromium to main looper Looper (main, tid 1) {16ac970b}
I/LibraryLoader( 6853): Expected native library version number "",actual native library version number ""
I/chromium( 6853): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6853): Initializing chromium process, renderers=0
W/art     ( 6853): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  314): registerClient() client 0xb57f4de0, uid 10311
,W/chromium( 6853): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6853): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6853): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1047): Message: 20
D/BluetoothManagerService( 1047): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@396de888:true
I/Adreno-EGL( 6853): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6853): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6853): Build Date: 12/12/14 금
I/Adreno-EGL( 6853): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6853): Remote Branch: 
I/Adreno-EGL( 6853): Local Patches: 
I/Adreno-EGL( 6853): Reconstruct Branch: 
,W/chromium( 6853): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6853): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6853): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6853): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6853): CordovaWebView is running on device made by: LGE
,W/art     ( 6853): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6853): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6853): Render dirty regions requested: true
I/OpenGLRenderer( 6853): Initialized EGL, version 1.4
D/OpenGLRenderer( 6853): Enabling debug mode 0
,D/Atlas   ( 6853): Validating map...
D/SplitWindow( 1047): check instance of lgWin Window{2bb2c282 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 6853): LgDataFeature() Constructor: none
D/LgDataFeature( 6853): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1047): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1466): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1466): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1466):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1466): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1047): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1047): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1047): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1047): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3cadd1e2,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1047): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/ActivityManager( 1047): Displayed com.test.thalitest/.MainActivity: +632ms (total +710ms)
,I/Timeline( 1047): Timeline: Activity_windows_visible id: ActivityRecord{3ddbce0f u0 com.test.thalitest/.MainActivity t4} time:107037
I/Timeline( 6853): Timeline: Activity_idle id: android.os.BinderProxy@119558fb time:107039
D/JsMessageQueue( 6853): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 6853): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6853): 
,D/jxcore_app_log( 6853): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435006720
,I/chromium( 6853): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6853): 
,I/GAV2    ( 6769): Thread[GAThread,5,main]: No campaign data found.
,I/chromium( 6853): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/DSQN    ( 1047): Dns fail occured do internet check.
,D/DSQN    ( 1047): EVENT_INTERNET_CHECK_REQUEST received
D/DSQN    ( 1047): try Internet connection check
W/System.err( 5659): java.net.UnknownHostException: Unable to resolve host "nist.time.nosc.us": No address associated with hostname
W/System.err( 5659): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:462)
W/System.err( 5659): 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
W/System.err( 5659): 	at java.net.InetAddress.getByName(InetAddress.java:305)
W/System.err( 5659): 	at com.lge.drmservice.activation.DrmSntpClient.processRequest(DrmSntpClient.java:231)
W/System.err( 5659): 	at com.lge.drmservice.activation.DrmSntpClient.run(DrmSntpClient.java:127)
W/System.err( 5659): Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
W/System.err( 5659): 	at libcore.io.Posix.android_getaddrinfo(Native Method)
W/System.err( 5659): 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
W/System.err( 5659): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:443)
W/System.err( 5659): 	... 4 more
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/DrmSntpClient( 5659): Server : 6
D/libc-netbsd(  310): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  310): res_queryN name = clients3.google.com succeed
D/DSQN    ( 1047): ThreadTCPConnectionCheck connect try to216.58.209.78
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = time.nist.gov, class = 1, type = 1
D/DSQN    ( 1047): ThreadInternetCheck internet check OK 
,D/libc-netbsd(  310): res_queryN name = time.nist.gov succeed
,E/GBMv2   (  338): DFP En is all cleared set to be enabled
E/GBMv2   (  338): Set value is all cleared set the max
I/GBMv2   (  338): DFP Enabled. Ignore VFP set
,I/MusicWidget( 2666): mDelayedStopHandler : unbind
,I/MusicBrowser( 2202): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2202): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2202): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2202): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2202): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2202): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2202): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2202): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1047):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@35836556com.lge.music.MediaPlaybackService$5@85689d7
D/MusicBrowser( 2202): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2202): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2202): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2202): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2202): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@15c6c33d
I/MusicBrowser( 2202): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2202): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2202): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2202): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2202): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2202): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2202): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2202): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2202): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2202): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2202): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2202): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2202): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2202): reset
V/MediaPlayer[Native]( 2202): setListener
V/MediaPlayer[Native]( 2202): disconnect
V/MediaPlayer[Native]( 2202): destructor
,V/AudioFlinger(  314): releasing 13 from 2202 for -1
V/AudioFlinger(  314):  decremented refcount to 0
V/AudioFlinger(  314): purging stale effects
V/MediaPlayer[Native]( 2202): disconnect
D/MusicBrowser( 2202): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
I/SmartShareClient( 2202): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2202): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2202): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2202): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2202): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2202): [SmartShareManagerClient] unregisterListener: 505569988
W/SmartShareClient( 2202): [SmartShareManagerClient] unregisterListener invalid listener: 505569988
I/SmartShareClient( 2202): [SmartShareManagerClient] terminate service: 2202/MediaPlaybackService/380409611
,E/HomeCloudIF( 2202): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2202): [SmartShareManagerClient] unbindService context:android.app.Application@3653f5ad
V/CloudHub( 2202): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2202): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2202): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2202): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
I/ActivityManager( 1047): Killing 6152:com.lge.appbox.client/u0a11 (adj 15): empty #17
,I/CloudHub( 2202): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29994
W/libprocessgroup( 1047): failed to open /acct/uid_10011/pid_6152/cgroup.procs: No such file or directory
,D/DSQN    ( 1047): EVENT_INTERNET_CHECK_ENABLE received
,W/jxcore-log( 6853): Initializing JXcore engine
W/jxcore-log( 6853): JXcore engine is ready
,W/Thread-804( 6906): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[9675]" dev="sockfs" ino=9675 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-804( 6906): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-804( 6906): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9807]" dev="sockfs" ino=9807 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-804( 6906): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-804( 6906): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[34157]" dev="sockfs" ino=34157 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6853): Starting JXcore engine
,W/jxcore-log( 6853): Platform android
W/jxcore-log( 6853): 
W/jxcore-log( 6853): Process ARCH arm
W/jxcore-log( 6853): 
,I/jxcore-log( 6853): JXcore Cordova bridge is ready!
I/jxcore-log( 6853): 
,W/jxcore-log( 6853): JXcore engine is started
,I/jxcore-log( 6853): Toggling radios to true
I/jxcore-log( 6853): 
,D/BluetoothAdapter( 6853): enable(): BT is already enabled..!
,D/WifiService( 1047): New client listening to asynchronous messages
D/WifiServiceImplEx( 1047): setWifiEnabled: true pid=6853, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1047): setWifiEnabled: true pid=6853, uid=10311
E/WifiService( 1047): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1047): disconnect pid=6853, uid=10311, packageName=com.test.thalitest
,E/WifiStateMachine( 1047):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1047):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1047): [109,657,276 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1047): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1047): reconnect pid=6853, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6853): Radios toggled
I/jxcore-log( 6853): 
I/jxcore-log( 6853): My device name is: LGE-LG-D855
I/jxcore-log( 6853): 
I/wpa_supplicant( 2614): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiNative-wlan0( 1047): DISCONNECT: returned true
E/WifiStateMachine( 1047): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1047): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1047): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1047): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1047): doBoolean: SAVE_CONFIG
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1047): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1047): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1047): InitialState.processMessage what=4
,D/WifiNative-wlan0( 1047): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1047): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2614): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1047): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1047): doBoolean: SET ps 1
D/WifiNative-wlan0( 1047): SET ps 1: returned true
D/LGWifiP2pService( 1047): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  310): Clearing all IP addresses on wlan0
V/NativeCrypto( 2180): Read error: ssl=0xaf0d7600: I/O error during system call, Connection timed out
,D/DhcpStateMachine( 1047): RunningState{ when=-11ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 2180): SSL shutdown failed: ssl=0xaf0d7600: I/O error during system call, Broken pipe
D/LGWifiP2pService( 1047): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering( 1047): sendTetherStateChangedBroadcast 0, 0, 0
,D/ConnectivityService( 1047): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService( 1047): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/ActivityManager( 1047): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6924 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/AlarmManager( 1047): RTC_WAKEUP set : Alarm{9255585 type 0 when 1455034025500 com.android.vending} when 1455034025500
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1977): handleWifiStateChangedEvent: 0
E/WifiStateMachine( 1047): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1047):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1047):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1047): [109,831,875 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1047): doBoolean: RECONNECT
I/wpa_supplicant( 2614): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1047): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1047): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1047): RECONNECT: returned true
D/WifiHS20( 1047): hidePasspointNotification off =false
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1047): hidePasspointNotification off =false
E/WifiStateMachine( 1047):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=109837
E/WifiStateMachine( 1047):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=109837
D/WifiNative-wlan0( 1047): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2614): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1047): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1047): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1047): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1047): doBoolean: SET ps 1
D/WifiNative-wlan0( 1047): SET ps 1: returned true
,W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1047): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): Checking http://clients3.google.com/generate_204 on <unknown ssid>
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
,D/CommandListener(  310): Clearing all IP addresses on wlan0
D/ConnectivityService( 1047): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1047): disableDataServiceNotify
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1047): stop dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1047): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1047):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=109860  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1047):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=109861  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1047):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1047):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
D/WifiHS20( 1047): hidePasspointNotification off =false
E/WifiStateMachine( 1047):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1047):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1047):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1047):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1047): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1047):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1047):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine( 1047):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1047): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1047): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
,D/CSLegacyTypeTracker( 1047): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 1047): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): Disconnected - quitting
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1047): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1466): CM callback handler got msg 524292
E/WifiStateMachine( 1047):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNetworkAgent( 1047): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1047):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1047): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1047): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 1047):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1047): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1047): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 1047):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1047): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1047): Remov,ing idletimer
E/WifiStateMachine( 1047):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
W/Settings( 1047): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1047): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1047): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
E/WifiStateMachine( 1047):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=109879  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
V/NetworkPolicy( 1047): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy( 1047): [LG_RESTRICTED] !!!isConnected  type  :1
,E/WifiStateMachine( 1047):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=109882  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WIFI    ( 1047): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1047):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/LocSvc_java( 1047): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1047): Sending msg: 4 arg1:0 arg2:1
D/WifiHS20( 1047): hidePasspointNotification off =false
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/TelephonyNetworkFactory-1( 1858): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/LocSvc_java( 1047): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1047): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1047): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1047): getAGpsConnectionInfo connType - 4
D/TelephonyNetworkFactory-1( 1858):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/LocSvc_java( 1047): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1047): ignore wifi update if we are not in OPENING or CLOSING
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1047): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1047): setSupplicantStateSCANNING
,W/ResourcesManager( 6924): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6924): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6924): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6924): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6924): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6924): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyIcons( 1466): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
V/SIM_STK ( 1047): Menu title from STK is T-Mobile
D/TelephonyIcons( 1466): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1047): StoppedState
D/DhcpStateMachine( 1047): StoppedState{ when=-169ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 6924): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6924): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6924): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6924): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6924): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6924): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6924): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6924): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6924): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6924): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6924): [AUTORUN] setTetherStatus() : status=false
,D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1047): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6958 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/GLSActivity( 2180): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2180): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2180): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2180): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2180): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2180): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/PCSuite ( 6958): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6958): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6958): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6924): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/art     ( 2180): Explicit concurrent mark sweep GC freed 24137(1444KB) AllocSpace objects, 10(1440KB) LOS objects, 51% free, 30MB/62MB, paused 1.233ms total 52.070ms
,D/Finsky  ( 6261): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6261): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6261): [1] 5.onFinished: Scheduling replication attempt 1.
D/LgDataFeature( 6924): LgDataFeature() Constructor: none
D/LgDataFeature( 6924): LgDataFeature() Constructor Done, null
,I/ActivityManager( 1047): Killing 6172:com.android.contacts/u0a19 (adj 15): empty #17
D/WiFiOffLoadBroadcast( 6924): MCCMNC not supported: null
W/libprocessgroup( 1047): failed to open /acct/uid_10019/pid_6172/cgroup.procs: No such file or directory
,I/ActivityManager( 1047): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6979 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1047): Killing 6560:com.lge.email/u0a23 (adj 15): empty #17
W/libprocessgroup( 1047): failed to open /acct/uid_10023/pid_6560/cgroup.procs: No such file or directory
,W/ResourcesManager( 6979): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 6979): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6979): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 6979): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 6979): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6979): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6979): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6979): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6979): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6979): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6979): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6979): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/QRemote ( 6979): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6958): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6958): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6958): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6924): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/QRemote ( 6979): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
D/WiFiOffLoadBroadcast( 6924): MCCMNC not supported: null
D/QRemote ( 6979): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6979): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6979): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6958): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6958): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6958): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6924): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/ContextImpl( 4576): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/WiFiOffLoadBroadcast( 6924): MCCMNC not supported: null
D/QRemote ( 6979): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6979): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6979): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6958): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6958): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6958): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6924): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6924): MCCMNC not supported: null
D/QRemote ( 6979): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6979): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6979): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6924): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6924): MCCMNC not supported: null
D/QRemote ( 6979): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6979): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6979): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 6979): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6979): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6979): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 6979): LgDataFeature() Constructor: none
D/LgDataFeature( 6979): LgDataFeature() Constructor Done, null
,V/SoundPool( 6979): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6979): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6979): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6979): doLoad: loading sample sampleID=1
V/SoundPool( 6979): Start decode
V/MediaPlayer[Native]( 6979): decode(31, 10857164, 17813)
I/QRemote ( 6979): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/MediaPlayerService(  314): decode(24, 10857164, 17813)
,W/BrunchPlayerTypeImpl(  314): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  314): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  314): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  314): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  314): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  314): player type = 3
V/AwesomePlayer(  314): AwesomePlayer create()
D/UEI.SmartControl( 6711): QS Service created
V/AwesomePlayer(  314): reset_l() 
V/AwesomePlayer(  314): cancelPlayerEvents
V/AwesomePlayer(  314): setAudioSink() 
V/AwesomePlayer(  314): reset_l() 
V/AudioCache(  314): notify(0xb5474980, 8, 0, 0)
V/AudioCache(  314): ignored
V/AwesomePlayer(  314): cancelPlayerEvents
D/Utils   (  314): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  314): setDataSource_l dataSource
V/LGParserOSAL(  314): SniffLGParser start
V/LGParserOSAL(  314): MainType:5, SubType=0
V/LGParserOSAL(  314): #### check Mime : application/ogg
V/LGParserOSAL(  314): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  314): Use LGExtractor :application/ogg 
D/QRemote ( 6979): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
I/UEI.SmartControl( 6711): Service initServices...
D/UEI.SmartControl( 6711): QS start get config
E/QRemote ( 6979): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6979): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,V/LGMDMManager( 6979): Create singleton instance
V/LGParserOSAL(  314): supported mime: application/ogg
V/AwesomePlayer(  314): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  314): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  314): mBitrate = -1 bits/sec
V/AwesomePlayer(  314): AudioTrack Setting
V/AwesomePlayer(  314): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  314): setAudioSource() 
V/MediaPlayerService(  314): prepare
V/AwesomePlayer(  314): prepareAsync_l() 
V/MediaPlayerService(  314): wait for prepare
V/AwesomePlayer(  314): onPrepareAsyncEvent() 
V/AwesomePlayer(  314): initAudioDecoder() 
W/Utils   (  314): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  314): isOffloadSupported()
V/AudioPolicyManager(  314): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  314): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  314): isAudioPlaybackHookOn() false
V/AwesomePlayer(  314): getUseOffload() = 0 
V/OMXCodec(  314): OMXCodec::Create
V/OMXCodec(  314): findMatchingCodecs()
V/OMXCodec(  314): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  314): matchingCodecs.size()=1
V/OMXCodec(  314): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  314): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  314): LG Codec Adapter start
V/OMXCodec(  314): OMXCodec Createtor
V/OMXCodec(  314): setComponentRole
V/OMXCodec(  314): configureCodec protected=0
V/LGCodecAdapter(  314): called getLGCodecSpecificData
V/LGCodecOSAL(  314): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  314): Called LGconfigureCodecMETA
V/LGCodecOSAL(  314): Called LGconfigureCodecMSG
V/LGCodecOSAL(  314): Not support LGCodec
V/OMXCodec(  314): [OMX.google.vorbis.decoder] initOutputFormat()
,V/OMXCodec(  314): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  314): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  314): Could not offload audio decode, try pcm offload
W/Utils   (  314): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  314): isOffloadSupported()
V/AudioPolicyManager(  314): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  314): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  314): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  314): init()
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  314): allocateBuffers
V/OMXCodec(  314): allocateBuffersOnPort portIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on input port
V/OMXCodec(  314): allocateBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb57ff5b0 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb57ff600 on output port
V/OMXCodec(  314): init() mAsyncCompletion wait!!! 
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  314): init() mAsyncCompletion wait!!! 
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  314): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  314): finishAsyncPrepare_l() 
V/AudioCache(  314): notify(0xb5474980, 5, 0, 0)
V/AudioCache(  314): ignored
V/AudioCache(  314): notify(0xb5474980, 1, 0, 0)
V/AudioCache(  314): prepared
V/AudioCache(  314): wait - success
V/MediaPlayerService(  314): start
V/AwesomePlayer(  314): play_l() 
V/AwesomePlayer(  314): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  314): createAudioPlayer_l
V/AwesomePlayer(  314): seekAudioIfNecessary_l() 
V/AwesomePlayer(  314): startAudioPlayer_l() 
D/AudioPlayer(  314): start of Playback, useOffload 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  314): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  314): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  314): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314),: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886128
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045062064
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045062144
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  314): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  314): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  314): allocateBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb57ff5b0 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb57ff740 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  314): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  314): notify(0xb5474980, 6, 0, 0)
V/AudioCache(  314): ignored
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab602000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab603000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab604000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab605000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab606000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab607000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab608000, 0xb57e0000, 4096)
V/MediaPlayerService(  314): wait for playback complete
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab609000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab60a000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab60b000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab60c000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab60d000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab60e000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab60f000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab610000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab611000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab612000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab613000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab614000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab615000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab616000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab617000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab618000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab619000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab61a000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab61b000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab61c000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab61d000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab61e000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab61f000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab620000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab621000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab622000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab623000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab624000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab625000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab626000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab627000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab628000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab629000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab62a000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab62b000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab62c000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab62d000, 0xb57e0000, 4096)
D/QRemote ( 6979): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6979): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 6979): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1315
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab62e000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
,V/AudioCache(  314): memcpy(0xab62f000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab630000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab631000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab632000, 0xb57e0000, 4096)
V/AudioCache(  314): write(0xb57e0000, 4096)
V/AudioCache(  314): memcpy(0xab633000, 0xb57e0000, 4096)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  314): postAudioEOS() 
V/AudioCache(  314): write(0xb57e0000, 280)
V/AudioCache(  314): memcpy(0xab634000, 0xb57e0000, 280)
V/AwesomePlayer(  314): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  314): onStreamDone
V/AwesomePlayer(  314): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  314): notify(0xb5474980, 2, 0, 0)
V/AudioCache(  314): playback complete
V/AwesomePlayer(  314): pause_l() 
V/AudioCache(  314): notify(0xb5474980, 7, 0, 0)
V/AudioCache(  314): ignored
V/AwesomePlayer(  314): cancelPlayerEvents
V/AudioCache(  314): wait - success
V/MediaPlayerService(  314): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  314): Pause Playback at 1068125
V/AwesomePlayer(  314): reset_l() 
V/AudioCache(  314): notify(0xb5474980, 8, 0, 0)
V/AudioCache(  314): ignored
V/AwesomePlayer(  314): cancelPlayerEvents
D/AudioPlayer(  314): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  314): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  314): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb57ff740 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7fb0 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb57ff5b0 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  314): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  314): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  314): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  314): AudioPlayer releasing audio source
D/AudioPlayer(  314): AudioPlayer done releasing audio source
V/AwesomePlayer(  314): reset_l() 
V/AwesomePlayer(  314): cancelPlayerEvents
V/AwesomePlayer(  314): ~AwesomePlayer call
V/AwesomePlayer(  314): reset_l() 
V/AwesomePlayer(  314): cancelPlayerEvents
V/SoundPool( 6979): close(31)
V/SoundPool( 6979): pointer = 0x9ff4f000, size = 205080, sampleRate = 48000, numChannels = 2
,I/UEI.SmartControl( 6711): Supports setup maps: true
,D/UEI.SmartControl( 6711): QS start statue = true Error code = 0
,I/UEI.SmartControl( 6711): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6711): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6711): ### init IR Blaster...
D/serial_port( 6711): Configuring serial port
E/UEI.SmartControl( 6711): UEIBLaster setting for 616
I/UEI.SmartControl( 6711): Setting serial record hearder size = 2
I/UEI.SmartControl( 6711): configuring settings for MAXQ616
I/UEI.SmartControl( 6711): Get version...
D/UEI.SmartControl( 6711): serial port data available: 21
,D/UEI.SmartControl( 6711): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6711): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6711): QS saving settings...
D/UEI.SmartControl( 6711): IR Blaster version: 25672567
,D/UEI.SmartControl( 6711): serial port data available: 4
,W/ContextImpl( 6711): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 6711): Services init done
D/UEI.SmartControl( 6711): QS Service init finished
D/UEI.SmartControl( 6711): QS Service version name: 2.1.91
D/UEI.SmartControl( 6711): QS Service version code: 201091
D/UEI.SmartControl( 6711): Service requested: Control
I/UEI.SmartControl( 6711): Device manager: loading config....
D/UEI.SmartControl( 6711): ----------- loading internal config...
D/UEI.SmartControl( 6711): Internal service binding...
I/QRemote ( 6979): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6711): ------ IControl API: 11
,D/UEI.SmartControl( 6711): File observer start...
E/UEI.SmartControl( 6711): IR Port is disabled: false
D/UEI.SmartControl( 6711): Starting file observer...
I/UEI.SmartControl( 6711): Registering callback...
I/UEI.SmartControl( 6711): ------ IControl API: 19
,I/UEI.SmartControl( 6711): Registering Services Ready callback...
,E/UEI.SmartControl( 6711): Loading SETTINGS...
D/UEI.SmartControl( 6711): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 6711): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6711): -----service ready thread exits
I/QRemote ( 6979): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6979): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6979): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6979): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6979): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6711): ------ IControl API: 8
D/QRemote ( 6979): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6979): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6979): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6979): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6979): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
,D/QRemote ( 6979): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6979): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6979): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6979): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6979): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6979): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6979): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6979): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6979): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6979): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1455034030602]
,D/QRemote ( 6979): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1047): Killing 6191:com.android.gallery3d/u0a27 (adj 15): empty #17
D/QRemote ( 6979): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1047): failed to open /acct/uid_10027/pid_6191/cgroup.procs: No such file or directory
,V/QRemote ( 6979): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6979): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 6979): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6979): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6979): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6979): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6979): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6979): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2614): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1047): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1047): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1047): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1047):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1047):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1047):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1047):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
D/WifiNative-wlan0( 1047): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1047):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=111928  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1047):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=111968  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServerServiceExt( 1047): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1047): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6924): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6924): MCCMNC not supported: null
D/QRemote ( 6979): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6979): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6979): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6924): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6924): MCCMNC not supported: null
D/QRemote ( 6979): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6979): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6979): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/wpa_supplicant( 2614): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,D/WifiMonitor( 1047): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
,E/WifiStateMachine( 1047):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=112196  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,E/WifiStateMachine( 1047):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=112197  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1047):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=112197
,E/WifiStateMachine( 1047):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=112197
E/WifiStateMachine( 1047):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=112197
E/WifiStateMachine( 1047):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=112198
E/WifiStateMachine( 1047):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=112198
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1047):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=112199  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1047):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=112200  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1047): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1047): setSupplicantStateFOUR_WAY_HANDSHAKE
D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 2614): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2614): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1047):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=112217  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1047):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=112217  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/WifiServerServiceExt( 1047): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1047): setSupplicantStateGROUP_HANDSHAKE
D/WifiMonitor( 1047): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1047): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1047): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1047):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=112220
E/WifiStateMachine( 1047):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=112220
D/WifiNative-wlan0( 1047): doString: [STATUS]
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1047): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiNative-wlan0( 1047):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1047): setVHTCapabilityType  : false
,V/WiFiOffLoadBroadcast( 6924): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6924): MCCMNC not supported: null
I/WifiServerServiceExt( 1047): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1047): setKeepAlivePacketInterval msec : 60
D/QRemote ( 6979): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6979): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
I/QRemote ( 6979): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6924): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/ConnectivityService( 1047): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1047): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 1047): Got NetworkAgent Messenger
D/WifiNative-wlan0( 1047): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1047): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1047): NetworkAgent connected
D/WifiNative-wlan0( 1047): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1047): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 6924): MCCMNC not supported: null
D/QRemote ( 6979): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6979): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6979): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/UsbSettingsReceiver( 6924): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6924): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6924): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6924): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6924): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 6924): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 6924): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6924): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6924): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6924): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/WifiNative-wlan0( 1047): SAVE_CONFIG: returned true
E/WifiConfigStore( 1047): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1047): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1047): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1047): doBoolean: SAVE_CONFIG
D/UsbSettingsReceiver( 6924): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6924): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1047): SAVE_CONFIG: returned true
D/CommandListener(  310): Setting iface cfg
E/WifiStateMachine( 1047): Start Dhcp Watchdog 2
E/WifiStateMachine( 1047):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=112286  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1047):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=112286  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1047):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=112286  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1047):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=112287  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1047):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=112287  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1047):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=112287  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1047):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1047):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1047):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1047):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1047):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1047):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1047):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1047):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/DhcpStateMachine( 1047): StoppedState{ when=-5ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1047): WaitBeforeStartState
D/ConnectivityService( 1047): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/WifiServerServiceExt( 1047): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1047): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1047): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1047): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1047):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1047):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1047): doBoolean: DRIVER SETSUSPENDMODE 0
V/WiFiOffLoadBroadcast( 6924): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6924): MCCMNC not supported: null
D/QRemote ( 6979): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6979): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6979): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/wpa_supplicant( 2614): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1047): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1047): doBoolean: SET ps 0
D/WifiNative-wlan0( 1047): SET ps 0: returned true
D/WifiNative-wlan0( 1047): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2614): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1047): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1047): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1047): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1047): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@13535f7a target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1047): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1047): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@13535f7a target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1047): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1047): DHCP Start wake lock is acquired.
D/CommandListener(  310): Setting iface cfg
D/CommandListener(  310): Trying to bring up wlan0
,V/WiFiOffLoadBroadcast( 6924): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/LgDhcpStateMachineHelper( 1047): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
E/WifiStateMachine( 1047):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1047):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1047): doBoolean: DRIVER BTCOEXMODE 2
D/ConnectivityService( 1047): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
I/wpa_supplicant( 2614): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1047): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1047): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1047): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1047): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2614): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1047): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1047): doBoolean: SET ps 1
D/WiFiOffLoadBroadcast( 6924): MCCMNC not supported: null
D/QRemote ( 6979): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6979): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6979): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1047): SET ps 1: returned true
E/WifiStateMachine( 1047):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1047):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1047): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1047): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/ConnectivityService( 1047): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1047): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1047): Adding iface wlan0 to network 101
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1047): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1047): [PASSPOINT] passpointNotification: hs20AP list is checked
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1977): handleWifiStateChangedEvent: 1
D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = true, mWifiLevel = 0
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1047): [PASSPOINT] passpointNotification: hs20AP list is checked
E/ConnectivityService( 1047): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1047): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1047): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,E/Netd    (  310): netlink response contains error (File exists)
D/ConnectivityService( 1047): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1047): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1047): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService( 1047): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1047): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1047): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1047): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1047): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1047):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1047):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1047):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1047):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1047):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1047): currentScore = 0, newScore = 20
D/ConnectivityService( 1047):    accepting network in place of null
D/ConnectivityService( 1047): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1047): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1047):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): Checking http://clients3.google.com/generate_204 on "NG700"
D/TelephonyNetworkFactory-1( 1858): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1858):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1047): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{1,01}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1047): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1047): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/libc-netbsd(  310): res_queryN name = clients3.google.com, class = 1, type = 28
,D/ConnectivityService( 1047): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1047): [e] list.add(nai) empty : false size: 1
,D/ConnectivityService( 1047): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
V/WiFiOffLoadBroadcast( 6924): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1047): validation of new default Network = false
D/ConnectivityService( 1047): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1047): enableDataServiceNotify 
D/DSQN    ( 1047): start dsqn bin
D/LocSvc_java( 1047): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1047): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1047): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1047): ignore wifi update if we are not in OPENING or CLOSING
,D/WiFiOffLoadBroadcast( 6924): MCCMNC not supported: null
D/ConnectivityService( 1047): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1047):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1047):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1047): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 7043): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7043): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/QRemote ( 6979): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6979): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
V/NetworkPolicy( 1047): [LG_RESTRICTED] checkMobilePolicy_type()
D/ConnectivityManager.CallbackHandler( 1466): CM callback handler got msg 524290
I/QRemote ( 6979): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,E/DSQN    ( 7043): DSQN ssw
V/WiFiOffLoadBroadcast( 6924): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6924): MCCMNC not supported: null
D/TelephonyIcons( 1466): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 6979): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6979): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6979): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/libc-netbsd(  310): res_queryN name = clients3.google.com, class = 1, type = 1
,D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6958): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6958): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6924): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6924): MCCMNC not supported: null
D/QRemote ( 6979): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6979): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6979): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6979): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6979): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6958): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6958): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6924): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6924): MCCMNC not supported: null
,D/QRemote ( 6979): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/libc-netbsd(  310): res_queryN name = clients3.google.com succeed
D/QRemote ( 6979): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6979): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6979): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6979): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/LGDataListener(  310): argv[0]=dsqncommand
,D/LGDataListener(  310): argv[1]=wlan0
D/LGDataListener(  310): argv[2]=1
D/LGDataListener(  310): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1047): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1047): start to monitor internet connection
D/DhcpStateMachine( 1047): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1047): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1047): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7049): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7049): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 7049): version 5.5.6 starting
E/dhcpcd  ( 7049): get_duid: m
D/dhcpcd  ( 7049): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7049): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 16:07:11 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455034031949], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455034031834]}
D/dhcpcd  ( 7049): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): Don't send network conditions - lacking user consent.
D/dhcpcd  ( 7049): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): Validated
D/dhcpcd  ( 7049): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7049): wlan0: rebinding lease of 192.168.1.141
D/ConnectivityService( 1047): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1047): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1047):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/dhcpcd  ( 7049): wlan0: sending REQUEST (xid 0x80283e9), next in 4.57 seconds
D/ConnectivityService( 1047):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1047):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1047): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1047): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1047):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1047):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1047): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1047): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1047): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1047): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1047):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1466): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1858): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1858):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,D/TelephonyIcons( 1466): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/ConnectivityService( 1047): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1047): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1047): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1047): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1047): MasterInitialState.processMessage what=3
,D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6497): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,D/GpsLocationProvider( 1047): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1047): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1047): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5517): type=WIFI subType= reason=null isConnected=true
I/NetworkMonitor( 5517): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1047): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7075 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 7075): onCreate
W/AppUp4:DB( 7075):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7075):  setFingerPrint start
I/AppUp4:DB( 7075):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 7075):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,I/AppUp4:DB( 7075):  SDK version = 21
I/AppUp4:DB( 7075):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7075): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7075): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7075): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7075): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7075): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7075): onReceive
D/LgDataFeature( 7075): LgDataFeature() Constructor: none
,D/LgDataFeature( 7075): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 7075): Context : android.app.ReceiverRestrictedContext@1e78a801
D/AppUp4:CustFacade( 7075): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7075): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7075): begin check event
I/AppUp4:CustModeStarterReceiver( 7075): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7075): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7075): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7075): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7075): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1047): Killing 6215:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1047): failed to open /acct/uid_10080/pid_6215/cgroup.procs: No such file or directory
D/LGDMClient( 4361): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4361): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4361): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4361): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3321): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4361): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4361): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4361): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4361): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3321): DownloadService onCreate
I/DownloadManager( 3321): in removeSpuriousFiles
V/DownloadManager( 3321): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,W/ContextImpl( 4361): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/ActivityManager( 1047): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7104 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
E/LGDMClient( 4361): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4361): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4361): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/art     ( 1047): Explicit concurrent mark sweep GC freed 82970(3MB) AllocSpace objects, 7(624KB) LOS objects, 33% free, 44MB/66MB, paused 1.945ms total 78.363ms
V/DownloadManager( 3321): created cursor android.database.sqlite.SQLiteCursor@1bfb39d5 on behalf of 3321
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
,I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
V/DownloadManager( 3321): DownloadService onStartCommand
V/DownloadManager( 3321): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3321): in trimDatabase
V/DownloadManager( 3321): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3321): created cursor android.database.sqlite.SQLiteCursor@2b1d7778 on behalf of 3321
V/DownloadManager( 3321): processing inserted download 1
V/DownloadManager( 3321): processing inserted download 4
V/DownloadManager( 3321): processing inserted download 7
V/DownloadManager( 3321): processing inserted download 8
V/DownloadManager( 3321): processing inserted download 9
V/DownloadManager( 3321): processing inserted download 10
V/DownloadManager( 3321): processing inserted download 16
V/DownloadManager( 3321): processing inserted download 17
V/DownloadManager( 3321): processing inserted download 18
V/DownloadManager( 3321): processing inserted download 21
V/DownloadManager( 3321): processing inserted download 22
V/DownloadManager( 3321): created cursor android.database.sqlite.SQLiteCursor@34c29e51 on behalf of 3321
,W/ResourcesManager( 7104): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7104): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7104): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7104): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
V/DownloadManager( 3321): DownloadService onDestroy
I/LGEmail ( 7104): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7104): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/ResourceType( 7104): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7104): LgDataFeature() Constructor: none
D/LgDataFeature( 7104): LgDataFeature() Constructor Done, null
,D/eas_req ( 7104): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1047): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7136 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
I/dhcpcd  ( 7049): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/HubEmail( 7104): JNI_OnLoad()
I/HubEmail( 7104): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7104): registerNatives()
I/HubEmail( 7104): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7104): registerNativeMethods()
I/HubEmail( 7104): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7104): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1047): Killing 6592:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,I/dhcpcd  ( 7049): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7049): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7049): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7049): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7049): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7049): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7049): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
,D/dhcpcd  ( 7049): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,W/Settings( 7104): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/libprocessgroup( 1047): failed to open /acct/uid_10061/pid_6592/cgroup.procs: No such file or directory
,W/Settings( 7104): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3272): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3272): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3272): networkInfo.isConnected() = false
,I/ActivityManager( 1047): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7179 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,E/WifiStateMachine( 1047):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1047):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1047):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1047):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1047):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1047):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1047): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1047): identical MTU - not setting
D/Nat464Xlat( 1047): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1047): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1047):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1047):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1047): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1466): CM callback handler got msg 524295
D/libc-netbsd(  310): res_queryN name = static-avc.lglime.com succeed
,I/ActivityManager( 1047): Killing 6238:com.google.android.apps.plus/u0a97 (adj 15): empty #17
V/FormManager( 7136): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7136): Alarm would be updated, because LastCheckTime has been updated.
,D/DhcpStateMachine( 1047): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1047): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1047): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1047): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1047): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1047): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1047): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1047): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1047): RunningState
W/libprocessgroup( 1047): failed to open /acct/uid_10097/pid_6238/cgroup.procs: No such file or directory
I/ActivityManager( 1047): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7200 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  342): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 442us total 19.739ms
I/ActivityManager( 1047): Killing 6643:com.lge.eula/1000 (adj 15): empty #17
,I/art     (  342): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 424us total 19.945ms
I/art     (  342): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 394us total 17.645ms
,W/libprocessgroup( 1047): failed to open /acct/uid_1000/pid_6643/cgroup.procs: No such file or directory
,I/art     ( 7200): Almond Protected OAT
,D/WeatherApplication( 7200): removeAccount
,D/WeatherApplication( 7200): Account.length = 0
E/WeatherApplication( 7200): OPERATOR:OPEN
D/WeatherAncestor( 7200): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:7:13
D/Weather.Utils( 7200): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7200): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7200): 2 : This is isUpdating : false
D/WeatherAncestor( 7200): connectivity changed - connection : true
D/WeatherService( 7200): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 7200): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7200): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7200): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7200): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7200): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:7:13
,I/ActivityManager( 1047): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7225 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1047): Killing 6078:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,I/jxcore-log( 6853): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6853): 
,V/AlarmManager( 1047): ELAPSED_WAKEUP set : Alarm{370e5bcb type 2 when 114540 com.google.android.gms} when 114540
,W/libprocessgroup( 1047): failed to open /acct/uid_10005/pid_6078/cgroup.procs: No such file or directory
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7225): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7225): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7225): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7225): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/WifiStateMachine( 1047):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1047):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1047):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1047):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1047):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1047):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,I/WebViewFactory( 7225): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7225): Loading: webviewchromium
,I/LibraryLoader( 7225): Time to load native libraries: 3 ms (timestamps 4998-5001)
I/LibraryLoader( 7225): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7225): Binding Chromium to main looper Looper (main, tid 1) {2e44e730}
,I/LibraryLoader( 7225): Expected native library version number "",actual native library version number ""
I/chromium( 7225): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7225): Initializing chromium process, renderers=0
W/art     ( 7225): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7225): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7225): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,I/chromium( 7225): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,V/AudioPolicyService(  314): registerClient() client 0xb57cdd40, uid 10093
W/AudioManagerAndroid( 7225): Requires BLUETOOTH permission
I/Adreno-EGL( 7225): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7225): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7225): Build Date: 12/12/14 금
I/Adreno-EGL( 7225): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7225): Remote Branch: 
I/Adreno-EGL( 7225): Local Patches: 
I/Adreno-EGL( 7225): Reconstruct Branch: 
,I/NSApplication( 7225): Starting up...
,I/ActivityManager( 1047): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7289 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1047): Killing 6669:com.lge.bnr/1000 (adj 15): empty #17
,I/jxcore-log( 6853): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6853): 
,V/WifiInternetCheck( 1047): Single check msg out of sync, ignoring.
,W/libprocessgroup( 1047): failed to open /acct/uid_1000/pid_6669/cgroup.procs: No such file or directory
,D/ConnectivityService( 1047): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1047): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1047): MasterInitialState.processMessage what=3
I/NetworkMonitor( 5517): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1047): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ResourcesManager( 7289): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/jxcore-log( 6853): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6853): 
I/jxcore-log( 6853): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6853): 
,I/jxcore-log( 6853): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6853): 
,I/jxcore-log( 6853): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 6853): 
,D/ChimeraCfgMgr( 2417): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 2417): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6497): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/GLSActivity( 2180): [ac] getting account id
I/NetworkStateForAutoUpdateMonitor( 7075): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7075): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7075): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7075): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7075): onReceive
,I/GLSUser ( 2180): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
D/AppUp4:CustFacade( 7075): Context : android.app.ReceiverRestrictedContext@1e78a801
D/AppUp4:CustFacade( 7075): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7075): isPhone : true
,D/AppUp4:CustModeStarterReceiver( 7075): begin check event
I/AppUp4:CustModeStarterReceiver( 7075): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4361): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4361): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4361): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4361): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3321): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3321): DownloadService onCreate
D/LGDMClient( 4361): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4361): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3321): in removeSpuriousFiles
V/DownloadManager( 3321): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3321): created cursor android.database.sqlite.SQLiteCursor@1c2dbfb7 on behalf of 3321
D/LGDMClient( 4361): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4361): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
,I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3321): in trimDatabase
V/DownloadManager( 3321): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3321): created cursor android.database.sqlite.SQLiteCursor@2e6e9324 on behalf of 3321
V/DownloadManager( 3321): DownloadService onStartCommand
V/DownloadManager( 3321): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/Settings( 7104): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 7104): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3321): created cursor android.database.sqlite.SQLiteCursor@7d4a053 on behalf of 3321
W/ContextImpl( 4361): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/LgeMiscReceiver( 3272): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3272): action = android.net.conn.CONNECTIVITY_CHANGE
E/LGDMClient( 4361): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
I/LgeMiscReceiver( 3272): networkInfo.isConnected() = false
D/LGDMClient( 4361): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4361): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3321): processing inserted download 1
V/DownloadManager( 3321): processing inserted download 4
V/DownloadManager( 3321): processing inserted download 7
,V/DownloadManager( 3321): processing inserted download 8
V/DownloadManager( 3321): processing inserted download 9
V/DownloadManager( 3321): processing inserted download 10
V/DownloadManager( 3321): processing inserted download 16
V/DownloadManager( 3321): processing inserted download 17
V/DownloadManager( 3321): processing inserted download 18
D/WeatherAncestor( 7200): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:7:15
V/DownloadManager( 3321): processing inserted download 21
D/Weather.Utils( 7200): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7200): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7200): 2 : This is isUpdating : false
D/WeatherAncestor( 7200): connectivity changed - connection : true
D/WeatherService( 7200): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3b0b98e7
V/DownloadManager( 3321): processing inserted download 22
D/ForecastDataCache( 7200): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7200): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7200): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7200): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7200): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:7:15
V/DownloadManager( 3321): DownloadService onDestroy
D/ChimeraCfgMgr( 2417): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 2417): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
V/FormManager( 7136): There are no updated forms. The schedule will be deleted.
V/FormManager( 7136): Alarm would be updated, because LastCheckTime has been updated.
,D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6497): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = mtalk.google.com, class = 1, type = 1
I/NetworkStateForAutoUpdateMonitor( 7075): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7075): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7075): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7075): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7075): onReceive
D/AppUp4:CustFacade( 7075): Context : android.app.ReceiverRestrictedContext@1e78a801
D/AppUp4:CustFacade( 7075): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7075): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7075): begin check event
I/AppUp4:CustModeStarterReceiver( 7075): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4361): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4361): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4361): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4361): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3321): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3321): DownloadService onCreate
D/LGDMClient( 4361): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4361): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3321): in removeSpuriousFiles
V/DownloadManager( 3321): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3321): created cursor android.database.sqlite.SQLiteCursor@d09c689 on behalf of 3321
D/LGDMClient( 4361): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4361): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
D/libc-netbsd(  310): res_queryN name = mtalk.google.com succeed
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3321): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/LgeMiscReceiver( 3272): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
V/DownloadManager( 3321): DownloadService onStartCommand
I/DownloadManager( 3321): in trimDatabase
V/DownloadManager( 3321): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3321): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 3272): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3272): networkInfo.isConnected() = true
D/PhoneState( 3272): setPdpRejectCasuse : false
,V/DownloadManager( 3321): created cursor android.database.sqlite.SQLiteCursor@3d9f22bc on behalf of 3321
V/DownloadManager( 3321): created cursor android.database.sqlite.SQLiteCursor@12bf4245 on behalf of 3321
W/ContextImpl( 4361): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
W/Settings( 7104): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/LGDMClient( 4361): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4361): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4361): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/WeatherAncestor( 7200): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:7:15
W/Settings( 7104): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/Weather.Utils( 7200): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7200): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7200): 2 : This is isUpdating : false
D/WeatherAncestor( 7200): connectivity changed - connection : true
D/WeatherService( 7200): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3b0b98e7
D/ForecastDataCache( 7200): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7200): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7200): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7200): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7200): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:7:15
V/DownloadManager( 3321): processing inserted download 1
V/DownloadManager( 3321): processing inserted download 4
V/DownloadManager( 3321): processing inserted download 7
V/DownloadManager( 3321): processing inserted download 8
V/DownloadManager( 3321): processing inserted download 9
V/DownloadManager( 3321): processing inserted download 10
V/DownloadManager( 3321): processing inserted download 16
V/DownloadManager( 3321): processing inserted download 17
V/DownloadManager( 3321): processing inserted download 18
V/DownloadManager( 3321): processing inserted download 21
V/DownloadManager( 3321): processing inserted download 22
,V/DownloadManager( 3321): DownloadService onDestroy
D/ChimeraCfgMgr( 2417): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 2417): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
V/FormManager( 7136): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7136): Alarm would be updated, because LastCheckTime has been updated.
,D/GCM     ( 2180): Connected
,D/GCM     ( 2180): Message class com.google.f.a.a.p
,D/UEI.SmartControl( 6711): Internal timer expired: 2
D/UEI.SmartControl( 6711): unbind internal service
,D/serial_port( 6711): close(fd = 24)
,I/UEI.SmartControl( 6711): Serial port is closed.
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  310): res_queryN name = www.google.com, class = 1, type = 1
D/libc-netbsd(  310): res_queryN name = www.google.com succeed
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  310): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  310): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1047): isHttpConnectionAvailable - We got a valid response : 204
,W/System.err( 5659): java.net.SocketTimeoutException
,W/System.err( 5659): 	at libcore.io.IoBridge.maybeThrowAfterRecvfrom(IoBridge.java:598)
,W/System.err( 5659): 	at libcore.io.IoBridge.recvfrom(IoBridge.java:556)
W/System.err( 5659): 	at java.net.PlainDatagramSocketImpl.doRecv(PlainDatagramSocketImpl.java:163)
W/System.err( 5659): 	at java.net.PlainDatagramSocketImpl.receive(PlainDatagramSocketImpl.java:171)
W/System.err( 5659): 	at java.net.DatagramSocket.receive(DatagramSocket.java:274)
W/System.err( 5659): 	at com.lge.drmservice.activation.DrmSntpClient.processRequest(DrmSntpClient.java:257)
W/System.err( 5659): 	at com.lge.drmservice.activation.DrmSntpClient.run(DrmSntpClient.java:127)
W/System.err( 5659): Caused by: android.system.ErrnoException: recvfrom failed: EAGAIN (Try again)
W/System.err( 5659): ,	at libcore.io.Posix.recvfromBytes(Native Method)
W/System.err( 5659): 	at libcore.io.Posix.recvfrom(Posix.java:161)
,W/System.err( 5659): 	at libcore.io.BlockGuardOs.recvfrom(BlockGuardOs.java:250)
W/System.err( 5659): 	at libcore.io.IoBridge.recvfrom(IoBridge.java:553)
W/System.err( 5659): 	,... 5 more
D/DrmService( 5659): Completed !! request = 2
D/DrmService( 5659): Request count = 0
,V/DrmService( 5659): Service onDestroy
I/ActivityManager( 1047): Killing 6688:com.android.calendar/u0a13 (adj 15): empty #17
,W/libprocessgroup( 1047): failed to open /acct/uid_10013/pid_6688/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 118145937719; DSPS: 4012217; Offset : -4311695295
,I/CloudHub( 2202): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19984
,I/GAV4    ( 7225): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 6853): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6853): 
,I/jxcore-log( 6853): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 6853): 
I/jxcore-log( 6853): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6853): 
,I/jxcore-log( 6853): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6853): 
,I/ActivityManager( 1047): Killing 6108:com.android.providers.calendar/u0a14 (adj 15): empty #17
,W/libprocessgroup( 1047): failed to open /acct/uid_10014/pid_6108/cgroup.procs: No such file or directory
,I/jxcore-log( 6853): Test app app.js loaded
I/jxcore-log( 6853): 
,I/chromium( 6853): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6853): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6853): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6853): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6853): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6853): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6853): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6853): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6853): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6853): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6853): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37a6e987 added. We now have 1 listener(s)
,I/jxcore-log( 6853): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6853): 
I/[SystemUI]LGPowerUI( 1466): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1466): On Skip Timer : true
,D/HeadsetStateMachine( 3790): Disconnected process message: 10, size: 0
,D/LEDHandler( 1977): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1977): Battery Level Remaining: 100%
D/LEDHandler( 1977): Battery Temp: 293, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1466): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
I/[SystemUI]LGPowerUI( 1466): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1466): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController( 1047): battery changed pluggedType: 2
D/LGDMClient( 4361): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4361): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,V/AlarmManager( 1047): RTC_WAKEUP set : Alarm{165cb081 type 0 when 1455034049581 com.android.vending} when 1455034049581
,V/AlarmManager( 1047): ELAPSED_WAKEUP set : Alarm{804a526 type 2 when 132127 android} when 132127
V/QRemote ( 6979): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,D/QRemote ( 6979): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:1315
V/SIM_STK ( 1047): Menu title from STK is T-Mobile
,V/GLSActivity( 2180): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2180): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2180): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2180): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2180): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2180): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6261): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6261): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6261): [1] 5.onFinished: Scheduling replication attempt 2.
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 138147916409; DSPS: 4667642; Offset : -4311701446
,I/CloudHub( 2202): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,I/CloudHub( 2202): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,E/WifiStateMachine( 1047):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1047):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1047):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1047):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1047):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1047):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 158149494943; DSPS: 5323053; Offset : -4311679466
,V/AlarmManager( 1047): RTC_WAKEUP set : Alarm{3db1bbf1 type 0 when 1455034072662 com.android.vending} when 1455034072662
,V/SIM_STK ( 1047): Menu title from STK is T-Mobile
,V/GLSActivity( 2180): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1047): Explicit concurrent mark sweep GC freed 36641(1698KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.290ms total 103.555ms
,I/GLSUser ( 2180): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2180): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2180): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2180): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
V/GLSActivity( 2180): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6261): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6261): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6261): [1] 5.onFinished: Scheduling replication attempt 3.
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
,I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
,D/PowerManagerServiceEx( 1047): acquireWakeLockInternal: lock=497280442, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1047
,V/AlarmManager( 1047): ELAPSED_WAKEUP set : Alarm{391c6b6b type 2 when 170819 android} when 170819
D/[Concierge]Service( 2615): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1047): releaseWakeLockInternal: lock=497280442 [*alarm*], flags=0x0
,I/BooksSync( 6769): Starting books sync
,D/BooksSync( 6769): started syncMyEbooks
,V/GLSActivity( 2180): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2180): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2180): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2180): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2180): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2180): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1047): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1047): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1047): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1047): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1047): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2180): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2180): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2180): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2180): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2180): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2180): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2180): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6769): Authentication error
E/BooksAccountManager( 6769): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6769): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6769): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6769): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6769): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6769): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6769): null auth token
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{d09c689 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  310): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6769): Error response from books API: {
W/ApiaryClient( 6769):  "error": {
W/ApiaryClient( 6769):   "errors": [
W/ApiaryClient( 6769):    {
W/ApiaryClient( 6769):     "domain": "global",
W/ApiaryClient( 6769):     "reason": "required",
W/ApiaryClient( 6769):     "message": "Login Required",
W/ApiaryClient( 6769):     "locationType": "header",
W/ApiaryClient( 6769):     "location": "Authorization"
W/ApiaryClient( 6769):    }
W/ApiaryClient( 6769):   ],
W/ApiaryClient( 6769):   "code": 401,
W/ApiaryClient( 6769):   "message": "Login Required"
W/ApiaryClient( 6769):  }
W/ApiaryClient( 6769): }
,W/ApiaryClient( 6769): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6769): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8638102992411540276&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6769): Headers:
W/ApiaryClient( 6769): accept-encoding: [gzip]
W/ApiaryClient( 6769): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6769): gdata-version: 2
,V/GLSActivity( 2180): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2180): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2180): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2180): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2180): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2180): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1047): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1047): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1047): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1047): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1047): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2180): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2180): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2180): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2180): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2180): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2180): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2180): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6769): Authentication error
E/BooksAccountManager( 6769): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6769): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6769): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6769): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6769): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6769): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6769): null auth token
,D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{d09c689 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6769): Error response from books API: {
W/ApiaryClient( 6769):  "error": {
W/ApiaryClient( 6769):   "errors": [
W/ApiaryClient( 6769):    {
W/ApiaryClient( 6769):     "domain": "global",
W/ApiaryClient( 6769):     "reason": "required",
W/ApiaryClient( 6769):     "message": "Login Required",
W/ApiaryClient( 6769):     "locationType": "header",
W/ApiaryClient( 6769):     "location": "Authorization"
W/ApiaryClient( 6769):    }
W/ApiaryClient( 6769):   ],
W/ApiaryClient( 6769):   "code": 401,
W/ApiaryClient( 6769):   "message": "Login Required"
W/ApiaryClient( 6769):  }
W/ApiaryClient( 6769): }
,W/ApiaryClient( 6769): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6769): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8638102992411540276&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6769): Headers:
W/ApiaryClient( 6769): accept-encoding: [gzip]
W/ApiaryClient( 6769): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6769): gdata-version: 2
,V/GLSActivity( 2180): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2180): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2180): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2180): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2180): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2180): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1047): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1047): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1047): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1047): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1047): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2180): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2180): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2180): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2180): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2180): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2180): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2180): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6769): Authentication error
E/BooksAccountManager( 6769): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6769): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6769): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6769): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6769): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6769): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6769): null auth token
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{d09c689 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6769): Error response from books API: {
W/ApiaryClient( 6769):  "error": {
W/ApiaryClient( 6769):   "errors": [
W/ApiaryClient( 6769):    {
W/ApiaryClient( 6769):     "domain": "global",
W/ApiaryClient( 6769):     "reason": "required",
W/ApiaryClient( 6769):     "message": "Login Required",
W/ApiaryClient( 6769):     "locationType": "header",
W/ApiaryClient( 6769):     "location": "Authorization"
W/ApiaryClient( 6769):    }
W/ApiaryClient( 6769):   ],
W/ApiaryClient( 6769):   "code": 401,
W/ApiaryClient( 6769):   "message": "Login Required"
W/ApiaryClient( 6769):  }
W/ApiaryClient( 6769): }
,W/ApiaryClient( 6769): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6769): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8638102992411540276&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6769): Headers:
W/ApiaryClient( 6769): accept-encoding: [gzip]
W/ApiaryClient( 6769): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6769): gdata-version: 2
,E/BooksSync( 6769): Soft error: 
E/BooksSync( 6769): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6769): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8638102992411540276&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6769): Headers:
E/BooksSync( 6769): accept-encoding: [gzip]
E/BooksSync( 6769): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6769): gdata-version: 2
E/BooksSync( 6769): 
E/BooksSync( 6769): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6769): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6769): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6769): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6769): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6769): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6769): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6769): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6769): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6769): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6769): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6769): {
E/BooksSync( 6769):  "error": {
E/BooksSync( 6769):   "errors": [
E/BooksSync( 6769):    {
E/BooksSync( 6769):     "domain": "global",
E/BooksSync( 6769):     "reason": "required",
E/BooksSync( 6769):     "message": "Login Required",
E/BooksSync( 6769):     "locationType": "header",
E/BooksSync( 6769):     "location": "Authorization"
E/BooksSync( 6769):    }
E/BooksSync( 6769):   ],
E/BooksSync( 6769):   "code": 401,
E/BooksSync( 6769):   "message": "Login Required"
E/BooksSync( 6769):  }
E/BooksSync( 6769): }
E/BooksSync( 6769): 
E/BooksSync( 6769): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6769): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6769): 	... 8 more
,E/BooksSync( 6769): Sync error
E/BooksSync( 6769): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6769): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8638102992411540276&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6769): Headers:
E/BooksSync( 6769): accept-encoding: [gzip]
E/BooksSync( 6769): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6769): gdata-version: 2
E/BooksSync( 6769): 
E/BooksSync( 6769): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6769): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6769): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6769): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6769): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6769): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6769): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6769): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6769): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6769): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6769): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6769): {
E/BooksSync( 6769):  "error": {
E/BooksSync( 6769):   "errors": [
E/BooksSync( 6769):    {
E/BooksSync( 6769):     "domain": "global",
E/BooksSync( 6769):     "reason": "required",
E/BooksSync( 6769):     "message": "Login Required",
E/BooksSync( 6769):     "locationType": "header",
E/BooksSync( 6769):     "location": "Authorization"
E/BooksSync( 6769):    }
E/BooksSync( 6769):   ],
E/BooksSync( 6769):   "code": 401,
E/BooksSync( 6769):   "message": "Login Required"
E/BooksSync( 6769):  }
E/BooksSync( 6769): }
E/BooksSync( 6769): 
E/BooksSync( 6769): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6769): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6769): 	... 8 more
I/BooksSync( 6769): Finished books sync
D/SyncManager( 1047): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 170819, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 178151953269; DSPS: 5978494; Offset : -4311693037
,V/AlarmManager( 1047): RTC_WAKEUP set : Alarm{33399c72 type 0 when 1455034099180 com.android.vending} when 1455034099180
,V/SIM_STK ( 1047): Menu title from STK is T-Mobile
,V/GLSActivity( 2180): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2180): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2180): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2180): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2180): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2180): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6261): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6261): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6261): [1] 5.onFinished: Scheduling replication attempt 4.
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 198153563106; DSPS: 6633907; Offset : -4311700396
,V/AlarmManager( 1047): ELAPSED_WAKEUP set : Alarm{23be9604 type 2 when 200931 android} when 200931
,V/AlarmManager( 1047): RTC_WAKEUP set : Alarm{19ce0622 type 0 when 1455034131738 com.android.vending} when 1455034131738
,V/SIM_STK ( 1047): Menu title from STK is T-Mobile
,V/GLSActivity( 2180): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2180): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2180): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2180): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2180): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2180): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6261): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6261): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6261): [1] 5.onFinished: Scheduling replication attempt 5.
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 218154624400; DSPS: 7289302; Offset : -4311707531
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
,I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 238156403975; DSPS: 7944720; Offset : -4311697898
,V/AlarmManager( 1047): ELAPSED_WAKEUP set : Alarm{36758834 type 2 when 209487 android} when 209487
,V/AlarmManager( 1047): ELAPSED_WAKEUP set : Alarm{bc3065d type 2 when 187680 com.google.android.gms} when 187680
,V/AlarmManager( 1047): RTC_WAKEUP set : Alarm{3987a4a3 type 0 when 1455034156206 com.android.vending} when 1455034156206
D/[Concierge]Service( 2615): onStartCommand(). Type : 9
,V/GLSActivity( 2180): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/SIM_STK ( 1047): Menu title from STK is T-Mobile
,I/VacuumService( 2180): Vacuum at: now=1455034158309 tag=VacuumService
,I/GoogleURLConnFactory( 2180): Using platform SSLCertificateSocketFactory
,W/Uploader( 2180): No account for auth token provided
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = play.googleapis.com, class = 1, type = 1
,V/GLSActivity( 2180): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2180): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2180): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2180): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2180): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2180): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6261): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6261): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6261): [1] 5.onFinished: Giving up after 6 failures.
,D/libc-netbsd(  310): res_queryN name = play.googleapis.com succeed
,W/Uploader( 2180): No account for auth token provided
,W/Uploader( 2180): No account for auth token provided
,W/Uploader( 2180): No account for auth token provided
,W/Uploader( 2180):  no longer exists, so no auth token.
I/jxcore-log( 6853): --= Surplus to requirements =--
I/jxcore-log( 6853): 
I/jxcore-log( 6853): ****TEST TOOK:  ms ****
I/jxcore-log( 6853): 
I/jxcore-log( 6853): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6853): 
,D/AndroidRuntime( 7457): 
D/AndroidRuntime( 7457): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7457): CheckJNI is OFF
D/AndroidRuntime( 7457): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1047): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg,
I/ActivityManager( 1047): Killing 6853:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,I/WindowState( 1047): WIN DEATH: Window{2bb2c282 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1047): Client connection lost with reason: 4
D/InputDispatcher( 1047): Window went away: Window{2bb2c282 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings( 1047): Skipping PackageSetting{f1db7de com.example.hello/10319} due to missing metadata
,I/ActivityManager( 1047):   Force finishing activity ActivityRecord{3ddbce0f u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  338): DFP En is all cleared set to be enabled
,W/ActivityManager( 1047): Spurious death for ProcessRecord{2f636b0b 6853:com.test.thalitest/u0a311}, curProc for 6853: null
I/ActivityManager( 1047): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
,I/ActivityManager( 1047):   Force finishing activity ActivityRecord{3ddbce0f u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1047): Duplicate finish request for ActivityRecord{3ddbce0f u0 com.test.thalitest/.MainActivity t4 f}
,I/[LGHome]EVENT( 2090): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2090): [Launcher.java:903:onResume()]onResume
,D/SplitWindowPolicy( 1977): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1977): topRunningActivity=ActivityInfo{36e78411 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1977): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1977): topRunningActivity=ActivityInfo{20f69976 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2090): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2090): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/ActionManagerService( 1928): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3726): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2090): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
I/[LGHome]LGActivityUtil( 2090): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2090): [Launcher.java:1056:onResume()]onResume end
,I/[LGHome]EVENT( 2090): [Launcher.java:1114:onPause()]onPause
D/KeyguardModel( 1466): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader( 1047): Reconfiguring input devices.  changes=0x00000010
E/LGBluetoothAvrcpQcomAdapter( 3790): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3790): [BTUI] [+] updateMediaPlayerInfo
,I/[LGHome]GBoardWebView( 2090): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/LIA_Service_RemotePackageHandler( 2036): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3726): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
D/ActionManagerService( 1928): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3726): handleMessage: what(1000) actionID(0x1000004)
W/GeofencerStateMachine( 1823): Ignoring removeGeofence because network location is disabled.
D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
V/SIM_STK ( 1047): Menu title from STK is T-Mobile
,I/ActivityManager( 1047): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7487 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
W/System.err( 4576): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4576): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4576): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4576): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4576): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4576): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4576): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4576): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4576): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4576): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4576): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4576): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,I/art     ( 4626): Explicit concurrent mark sweep GC freed 16119(915KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 3.555ms total 168.135ms
V/BoardContentProvider( 3726): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/[SystemUI]QSlideListController( 1466): onReceive = android.intent.action.PACKAGE_REMOVED
I/GBoardWebViewUtils( 2090): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2090): , create_time: 1430558575574
I/GBoardWebViewUtils( 2090): , expire_time: 0
I/GBoardWebViewUtils( 2090): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2090): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2090): , display: false
I/GBoardWebViewUtils( 2090): , animation: false }
I/GBoardWebViewUtils( 2090): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2090): , create_time: 1430558575600
I/GBoardWebViewUtils( 2090): , expire_time: 0
I/GBoardWebViewUtils( 2090): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2090): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2090): , display: false
I/GBoardWebViewUtils( 2090): , animation: false }
I/GBoardWebViewUtils( 2090): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1454599632914
I/GBoardWebViewUtils( 2090): , create_time: 1454599633839
I/GBoardWebViewUtils( 2090): , expire_time: 0
I/GBoardWebViewUtils( 2090): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2090): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2090): , display: false
I/GBoardWebViewUtils( 2090): , animation: false }
I/SystemUI[Framework]( 1047): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1047): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1047): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1047): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1047): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3cadd1e2,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1047): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,D/WallpaperManager( 2090): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/[LGHome]GBoardWebView( 2090): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
I/art     ( 1047): Explicit concurrent mark sweep GC freed 28621(1572KB) AllocSpace objects, 6(480KB) LOS objects, 33% free, 44MB/66MB, paused 2.369ms total 179.589ms
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1466): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
,D/KeyguardModel( 1466): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/LockScreenSettings( 7487): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,V/SIM_STK ( 1047): Menu title from STK is T-Mobile
V/SIM_STK ( 1047): Menu title from STK is T-Mobile
,D/KeyguardModel( 1466): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1466): createShortcutInfo...
D/SplitUIManager( 1881): split_name #11 / not available #0
D/SplitUIService( 1881): removed split : 
D/KeyguardModel( 1466): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1466): createShortcutInfo...
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 2090): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1466): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1466): createShortcutInfo...
,D/administrator( 1047): Handling package changes for user 0
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1466): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1466): createShortcutInfo...
I/[LGHome]EVENT( 2090): [Launcher.java:5349:onStop()]onStop
D/AppUp4:PreloadHelper( 7075): added Exclude : com.test.thalitest
W/ResourcesManager( 1466): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/SplitUIManager( 1881): split_name #11 / not available #0
W/ResourcesManager( 1466): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/SplitUIService( 1881): split app #11
,W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1466): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1466): createShortcutInfo...
I/ActivityManager( 1047): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7510 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
W/ActivityManager( 1047): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3790): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3790): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3790): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3790): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3790): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3790): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3790): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3790): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3790): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3790): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3790): [BTUI] [-] updateMediaPlayerInfo
D/KeyguardModel( 1466): handleShortcutListChanged...
D/KeyguardModel( 1466): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1466): createShortcutInfo...
V/SIM_STK ( 1047): Menu title from STK is T-Mobile
D/KeyguardModel( 1466): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1466): createShortcutInfo...
,W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1466): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1466): createShortcutInfo...
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1466): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1466): createShortcutInfo...
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1466): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1466): createShortcutInfo...
I/ThermalEngine(  328): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3172): Thermal-Lib-Client: Client request sent
,I/ActivityManager( 1047): Killing 2202:com.lge.music/u0a34 (adj 15): empty #17
I/[LGHome]Launcher.Model( 2090): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
V/AudioFlinger(  314): 2202 died, releasing its sessions
V/AudioFlinger(  314):  pid 1858 @ 0
V/AudioFlinger(  314):  pid 3272 @ 1
V/AudioFlinger(  314):  pid 3272 @ 2
I/NotificationService( 1047): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1047): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1047): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher.Model( 2090): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2090): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2090): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2090): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[Concierge]WidgetView( 2090): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,D/KeyguardModel( 1466): handleShortcutListChanged...
,W/libprocessgroup( 1047): failed to open /acct/uid_10034/pid_2202/cgroup.procs: No such file or directory
D/PhoneStatusBar( 1466): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1466): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1466):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1466): , Keyguard show=false, IME shown=false, Panel expanded=false
I/Timeline( 1047): Timeline: Activity_windows_visible id: ActivityRecord{1a7dec7f u0 com.lge.launcher2/.Launcher t3} time:244698
D/TaskPersister( 1047): removeObsoleteFile: deleting file=4_task.xml
D/[Concierge]Service( 2615): onStartCommand(). Type : 8
D/[Concierge]Service( 2615): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2615): Update widget ID : 11
D/[Concierge]WidgetView( 2090): change position of spinner
I/[Concierge]WidgetView( 2090): initWebView(). Time : 1455034164046
D/[Concierge]Service( 2615): onStartCommand(). Type : 0
,W/ResourcesManager( 7510): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7510): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7510): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7510): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7510): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/art     ( 1047): Explicit concurrent mark sweep GC freed 8399(457KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.945ms total 218.395ms
I/[Concierge]WebView( 2090): Return exist ConciergeWebView. Reuse : 730582239
,D/[Concierge]WidgetView( 2090): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2090): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2090): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3788a316
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2090): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2090): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2090): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2090): Widget kill message received. Destory myself. My : 1455033947048, New one : 1455034164046
D/[Concierge]WidgetView( 2090): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2090): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/SystemConfig( 7510): BUILD Country: EU
I/SystemConfig( 7510): BUILD Operator: OPEN
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2090): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
D/AndroidRuntime( 7457): Shutting down VM
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2090): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ActivityManager( 1047): Killing 6958:com.lge.sync/1000 (adj 15): empty #17
,I/Timeline( 2090): Timeline: Activity_idle id: android.os.BinderProxy@301d714a time:244819
,W/ResourcesManager( 1047): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1047): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/chromium( 2090): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/GBoardtInterface( 2090): onReloaded()
,I/GBoardWebViewClient( 2090): onPageFinished url:file:///android_asset/www/main.html
W/libprocessgroup( 1047): failed to open /acct/uid_1000/pid_6958/cgroup.procs: No such file or directory
,V/BoardContentProvider( 3726): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/SystemConfig( 7510): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7510): existFile = false
I/SystemConfig( 7510): canReadFile = false
I/SystemConfig( 7510): systemFeature RCS result false
D/SystemConfig( 7510): refreshRcsSupport() :false
D/VoicemailCleanupService( 2134): Cleaning up data for package: com.test.thalitest
I/PackageChangeReceiver( 7104): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
V/BoardContentProvider( 3726): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/ActivityManager( 1047): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7537 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/ActionManagerService( 1928): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3726): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3726): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1928): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3726): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3726): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3726): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3726): onSettingEvent() : GBoard On - add scheduler - 0
,V/BoardContentProvider( 3726): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2090): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2090): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2090): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2090): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2090): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2090): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/[LGHome]EVENT( 2090): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/ResourcesManager( 7537): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7537): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7537): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7537): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/AppConfig( 7537): Total System Memory = 2995761152
,D/SystemHelper( 7537): region [EU], country [EU], operator [OPEN], sub-operator []
E/SharedPreferencesImpl( 7537): Couldn't rename file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml to backup file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml.bak

```
