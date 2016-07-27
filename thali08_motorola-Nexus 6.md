#### Test 77622416ad9274d_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
07-27 11:48:14.435  3482  3684 I BooksSync: Starting books sync for 61035162, extras: ade
07-27 11:48:14.465  3482  3685 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
07-27 11:48:14.492  2905  3683 V KeepSync: Connecting to GoogleApiClient
--------- beginning of system
07-27 11:48:14.492   874  1703 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
07-27 11:48:14.495  1525  1993 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-27 11:48:14.495  1525  1993 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-27 11:48:14.495  1525  1993 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 11:48:14.496  1525  1993 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-27 11:48:14.567  1525  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-27 11:48:14.567  1525  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-27 11:48:14.567  1525  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 11:48:14.567  1525  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-27 11:48:14.568  1525  1536 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
07-27 11:48:14.568  1525  1536 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-27 11:48:14.568  1525  1536 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 11:48:14.568  1525  1536 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-27 11:48:14.590  1867  3689 V BaseAuthAsyncOperation: access token request failed
07-27 11:48:14.591  3482  3685 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 11:48:14.591  2905  3683 V KeepSync: GoogleApiClient failed to connect with error code: 4
07-27 11:48:14.593  3482  3684 E BooksSync: Soft error
07-27 11:48:14.593  3482  3684 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 11:48:14.593  3482  3684 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-27 11:48:14.594  3482  3684 E BooksSync: Sync error
07-27 11:48:14.594  3482  3684 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 11:48:14.594  3482  3684 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-27 11:48:14.595  3482  3684 I BooksSync: Finished books sync
07-27 11:48:14.603   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 128428, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-27 11:48:14.675  1525  1993 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-27 11:48:14.675  1525  1993 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-27 11:48:14.676  1525  1993 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 11:48:14.676  1525  1993 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-27 11:48:14.704  2905  3683 E KeepSync: IOException
07-27 11:48:14.704  2905  3683 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-27 11:48:14.704  2905  3683 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-27 11:48:14.704  2905  3683 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-27 11:48:14.704  2905  3683 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-27 11:48:14.704  2905  3683 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-27 11:48:14.704  2905  3683 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-27 11:48:14.704  2905  3683 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-27 11:48:14.704  2905  3683 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-27 11:48:14.704  2905  3683 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-27 11:48:14.704  2905  3683 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-27 11:48:14.704  2905  3683 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-27 11:48:14.704  2905  3683 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-27 11:48:14.704  2905  3683 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-27 11:48:14.704  2905  3683 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-27 11:48:14.704  2905  3683 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 11:48:14.704  2905  3683 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 11:48:14.704  2905  3683 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-27 11:48:14.704  2905  3683 E KeepSync: 	... 10 more
07-27 11:48:14.704  2905  3683 W KeepSync: Sync result 2
07-27 11:48:14.714   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 127960, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
07-27 11:48:14.830  1525  3510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-27 11:48:14.830  1525  3510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 11:48:14.830  1525  3510 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 11:48:14.830  1525  3510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-27 11:48:14.867  3433  3691 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-27 11:48:14.867  3433  3691 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 11:48:14.867  3433  3691 E HttpOperation: 	at jdm.a(PG:82)
07-27 11:48:14.867  3433  3691 E HttpOperation: 	at jcs.o(PG:406)
07-27 11:48:14.867  3433  3691 E HttpOperation: 	at jcn.a(PG:1379)
07-27 11:48:14.867  3433  3691 E HttpOperation: 	at jcs.i(PG:143)
07-27 11:48:14.867  3433  3691 E HttpOperation: 	at blb.a(PG:3937)
07-27 11:48:14.867  3433  3691 E HttpOperation: 	at czp.a(PG:18188)
07-27 11:48:14.867  3433  3691 E HttpOperation: 	at czp.a(PG:9081)
07-27 11:48:14.867  3433  3691 E HttpOperation: 	at czq.run(PG:1686)
07-27 11:48:14.867  3433  3691 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 11:48:14.867  3433  3691 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 11:48:14.867  3433  3691 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 11:48:14.867  3433  3691 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 11:48:14.867  3433  3691 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 11:48:14.867  3433  3691 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 11:48:14.867  3433  3691 E HttpOperation: 	at jdj.a(PG:4091)
07-27 11:48:14.867  3433  3691 E HttpOperation: 	at jdj.a(PG:1125)
07-27 11:48:14.867  3433  3691 E HttpOperation: 	at jdm.a(PG:77)
07-27 11:48:14.867  3433  3691 E HttpOperation: 	... 12 more
07-27 11:48:14.867  3433  3691 E HttpOperation: Caused by: faj: BadAuthentication
07-27 11:48:14.867  3433  3691 E HttpOperation: 	at fal.a(PG:38)
07-27 11:48:14.867  3433  3691 E HttpOperation: 	at jdj.a(PG:4089)
07-27 11:48:14.867  3433  3691 E HttpOperation: 	... 14 more
07-27 11:48:14.943  1525  1993 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-27 11:48:14.943  1525  1993 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 11:48:14.943  1525  1993 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 11:48:14.943  1525  1993 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-27 11:48:14.969  3433  3691 E HttpOperation: [getmobileexperiments] Unexpected exception
07-27 11:48:14.969  3433  3691 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 11:48:14.969  3433  3691 E HttpOperation: 	at jdm.a(PG:82)
07-27 11:48:14.969  3433  3691 E HttpOperation: 	at jcs.o(PG:406)
07-27 11:48:14.969  3433  3691 E HttpOperation: 	at jcn.a(PG:1379)
07-27 11:48:14.969  3433  3691 E HttpOperation: 	at jcs.i(PG:143)
07-27 11:48:14.969  3433  3691 E HttpOperation: 	at hec.a(PG:42)
07-27 11:48:14.969  3433  3691 E HttpOperation: 	at hee.a(PG:102)
07-27 11:48:14.969  3433  3691 E HttpOperation: 	at czr.a(PG:65)
07-27 11:48:14.969  3433  3691 E HttpOperation: 	at kka.a(PG:108)
07-27 11:48:14.969  3433  3691 E HttpOperation: 	at czp.a(PG:19176)
07-27 11:48:14.969  3433  3691 E HttpOperation: 	at czp.a(PG:9081)
07-27 11:48:14.969  3433  3691 E HttpOperation: 	at czq.run(PG:1686)
07-27 11:48:14.969  3433  3691 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 11:48:14.969  3433  3691 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 11:48:14.969  3433  3691 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 11:48:14.969  3433  3691 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 11:48:14.969  3433  3691 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 11:48:14.969  3433  3691 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 11:48:14.969  3433  3691 E HttpOperation: 	at jdj.a(PG:4091)
07-27 11:48:14.969  3433  3691 E HttpOperation: 	at jdj.a(PG:1125)
07-27 11:48:14.969  3433  3691 E HttpOperation: 	at jdm.a(PG:77)
07-27 11:48:14.969  3433  3691 E HttpOperation: 	... 15 more
07-27 11:48:14.969  3433  3691 E HttpOperation: Caused by: faj: BadAuthentication
07-27 11:48:14.969  3433  3691 E HttpOperation: 	at fal.a(PG:38)
07-27 11:48:14.969  3433  3691 E HttpOperation: 	at jdj.a(PG:4089)
07-27 11:48:14.969  3433  3691 E HttpOperation: 	... 17 more
07-27 11:48:14.969  3433  3691 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-27 11:48:14.969  3433  3691 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-27 11:48:14.969  3433  3691 E ExperimentLoader: 	at jdm.a(PG:82)
07-27 11:48:14.969  3433  3691 E ExperimentLoader: 	at jcs.o(PG:406)
07-27 11:48:14.969  3433  3691 E ExperimentLoader: 	at jcn.a(PG:1379)
07-27 11:48:14.969  3433  3691 E ExperimentLoader: 	at jcs.i(PG:143)
07-27 11:48:14.969  3433  3691 E ExperimentLoader: 	at hec.a(PG:42)
07-27 11:48:14.969  3433  3691 E ExperimentLoader: 	at hee.a(PG:102)
07-27 11:48:14.969  3433  3691 E ExperimentLoader: 	at czr.a(PG:65)
07-27 11:48:14.969  3433  3691 E ExperimentLoader: 	at kka.a(PG:108)
07-27 11:48:14.969  3433  3691 E ExperimentLoader: 	at czp.a(PG:19176)
07-27 11:48:14.969  3433  3691 E ExperimentLoader: 	at czp.a(PG:9081)
07-27 11:48:14.969  3433  3691 E ExperimentLoader: 	at czq.run(PG:1686)
07-27 11:48:14.969  3433  3691 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 11:48:14.969  3433  3691 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 11:48:14.969  3433  3691 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 11:48:14.969  3433  3691 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 11:48:14.969  3433  3691 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-27 11:48:14.969  3433  3691 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 11:48:14.969  3433  3691 E ExperimentLoader: 	at jdj.a(PG:4091)
07-27 11:48:14.969  3433  3691 E ExperimentLoader: 	at jdj.a(PG:1125)
07-27 11:48:14.969  3433  3691 E ExperimentLoader: 	at jdm.a(PG:77)
07-27 11:48:14.969  3433  3691 E ExperimentLoader: 	... 15 more
07-27 11:48:14.969  3433  3691 E ExperimentLoader: Caused by: faj: BadAuthentication
07-27 11:48:14.969  3433  3691 E ExperimentLoader: 	at fal.a(PG:38)
07-27 11:48:14.969  3433  3691 E ExperimentLoader: 	at jdj.a(PG:4089)
07-27 11:48:14.969  3433  3691 E ExperimentLoader: 	... 17 more
07-27 11:48:15.141   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 129208, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
07-27 11:48:15.311  3692  3692 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-27 11:48:15.316  3692  3692 D AndroidRuntime: CheckJNI is OFF
07-27 11:48:15.351  3692  3692 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-27 11:48:15.396  3692  3692 I Radio-JNI: register_android_hardware_Radio DONE
07-27 11:48:15.416  3692  3692 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-27 11:48:15.421   874  1539 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-27 11:48:15.501   874  1539 I ActivityManager: Start proc 3702:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-27 11:48:15.509  3692  3692 D AndroidRuntime: Shutting down VM
07-27 11:48:15.660  3702  3702 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
07-27 11:48:15.716  3702  3702 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-27 11:48:15.739  3702  3702 I LibraryLoader: Time to load native libraries: 15 ms (timestamps 8151-8166)
07-27 11:48:15.739  3702  3702 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 11:48:15.782  3702  3702 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a213b41}
07-27 11:48:15.783  3702  3702 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 11:48:15.784  3702  3702 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-27 11:48:15.798  3702  3702 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-27 11:48:15.800  3702  3702 E SysUtils: ApplicationContext is null in ApplicationStatus
07-27 11:48:15.832  3702  3702 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-27 11:48:15.848  3702  3702 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-27 11:48:15.848  3702  3702 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-27 11:48:15.848  3702  3702 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-27 11:48:15.848  3702  3702 I Adreno  : Build Date                       : 10/20/15
07-27 11:48:15.848  3702  3702 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-27 11:48:15.848  3702  3702 I Adreno  : Local Branch                     : M14
07-27 11:48:15.848  3702  3702 I Adreno  : Remote Branch                    : 
07-27 11:48:15.848  3702  3702 I Adreno  : Remote Branch                    : 
07-27 11:48:15.848  3702  3702 I Adreno  : Reconstruct Branch               : 
07-27 11:48:15.958   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6c45642:true
07-27 11:48:16.020  3702  3702 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-27 11:48:16.040  3702  3702 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
07-27 11:48:16.088   874   887 W ActivityManager: Activity pause timeout for ActivityRecord{b85ddbf u0 com.test.thalitest/.MainActivity t2}
07-27 11:48:16.152  3702  3739 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
07-27 11:48:16.173  3702  3726 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
07-27 11:48:16.211  3702  3739 I OpenGLRenderer: Initialized EGL, version 1.4
07-27 11:48:16.299   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +711ms (total +834ms)
07-27 11:48:16.302  1670  1670 I Keyboard.Facilitator: onFinishInput()
07-27 11:48:16.384  3702  3702 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3702
07-27 11:48:16.462  3702  3702 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-27 11:48:16.640  3702  3741 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1684014800
07-27 11:48:16.646  3702  3741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-27 11:48:16.646  3702  3741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-27 11:48:16.646  3702  3741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-27 11:48:16.646  3702  3741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-27 11:48:16.646  3702  3741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-27 11:48:16.646  3702  3741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f572c added. We now have 1 listener(s)
07-27 11:48:16.650  3702  3741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
07-27 11:48:16.654  3702  3741 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-27 11:48:16.657  3702  3741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:48:16.657  3702  3741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:48:16.660  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-27 11:48:16.660  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-27 11:48:16.660  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-27 11:48:16.660  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
07-27 11:48:16.660  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-27 11:48:16.660  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-27 11:48:16.660  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-27 11:48:16.660  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-27 11:48:16.660  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
07-27 11:48:16.660  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-27 11:48:16.660  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-27 11:48:16.660  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-27 11:48:16.660  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-27 11:48:16.660  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-27 11:48:16.660  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24d19fb added. We now have 1 listener(s)
07-27 11:48:16.661  3702  3741 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:48:16.663   874  1318 D WifiService: New client listening to asynchronous messages
07-27 11:48:16.665  3702  3741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 11:48:16.665  3702  3741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-27 11:48:16.665  3702  3741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-27 11:48:16.665  3702  3741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-27 11:48:16.668  3702  3741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:48:16.669  3702  3741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
07-27 11:48:16.680  3702  3741 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
07-27 11:48:16.680  3702  3741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:48:16.680  3702  3741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:16.680  3702  3741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:16.680  3702  3741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:48:16.680  3702  3741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:48:16.680  3702  3741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:48:16.680  3702  3741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:48:16.680  3702  3741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:48:16.680  3702  3741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-27 11:48:16.680  3702  3741 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:48:16.681  3702  3741 I io.jxcore.node.LifeCycleMonitor: start: OK
07-27 11:48:16.683  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:48:16.686  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:48:16.716  3702  3702 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
07-27 11:48:17.879  3702  3748 W jxcore-log: Initializing JXcore engine
07-27 11:48:17.879  3702  3748 W jxcore-log: JXcore engine is ready
07-27 11:48:17.928  3748  3748 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8798 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
07-27 11:48:17.932  3748  3748 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[12924]" dev="sockfs" ino=12924 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-27 11:48:17.932  3748  3748 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-27 11:48:17.932  3748  3748 W Thread-329: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[23017]" dev="sockfs" ino=23017 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
07-27 11:48:17.943  3702  3748 W jxcore-log: Starting JXcore engine
07-27 11:48:18.020  3702  3748 W jxcore-log: Platform android
07-27 11:48:18.020  3702  3748 W jxcore-log: 
07-27 11:48:18.020  3702  3748 W jxcore-log: Process ARCH arm
07-27 11:48:18.020  3702  3748 W jxcore-log: 
07-27 11:48:18.179  3702  3748 I jxcore-log: JXcore Cordova bridge is ready!
07-27 11:48:18.179  3702  3748 I jxcore-log: 
07-27 11:48:18.180  3702  3748 W jxcore-log: JXcore engine is started
07-27 11:48:18.197  3702  3741 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-27 11:48:18.203  3702  3702 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-27 11:48:18.621  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 11:48:18.757  1525  3753 I VacuumService: Vacuum at: now=1469612898757 tag=VacuumService
,07-27 11:48:18.919  1525  3754 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,07-27 11:48:18.921  1525  3754 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-27 11:48:19.262  1525  3754 W Uploader:  no longer exists, so no auth token.
,07-27 11:48:19.435  1525  3754 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,07-27 11:48:19.435  1525  3754 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-27 11:48:19.436  1525  3754 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 11:48:19.436  1525  3754 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 11:48:19.456  1525  3754 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-27 11:48:19.456  1525  3754 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-27 11:48:19.456  1525  3754 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-27 11:48:19.456  1525  3754 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-27 11:48:19.456  1525  3754 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-27 11:48:19.456  1525  3754 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-27 11:48:19.456  1525  3754 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-27 11:48:19.456  1525  3754 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-27 11:48:19.456  1525  3754 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-27 11:48:19.456  1525  3754 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-27 11:48:19.456  1525  3754 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-27 11:48:19.456  1525  3754 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-27 11:48:19.456  1525  3754 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,07-27 11:48:20.180  1525  3754 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,07-27 11:48:20.180  1525  3754 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,07-27 11:48:20.180  1525  3754 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 11:48:20.180  1525  3754 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 11:48:20.196  1525  3754 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-27 11:48:20.196  1525  3754 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-27 11:48:20.196  1525  3754 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-27 11:48:20.196  1525  3754 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-27 11:48:20.196  1525  3754 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-27 11:48:20.196  1525  3754 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-27 11:48:20.196  1525  3754 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-27 11:48:20.196  1525  3754 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-27 11:48:20.196  1525  3754 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-27 11:48:20.196  1525  3754 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-27 11:48:20.196  1525  3754 E Uploader: 	,at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-27 11:48:20.196  1525  3754 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-27 11:48:20.196  1525  3754 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,07-27 11:48:20.568   874  1317 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,07-27 11:48:20.674  1525  3754 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,07-27 11:48:20.674  1525  3754 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-27 11:48:20.674  1525  3754 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 11:48:20.674  1525  3754 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 11:48:20.692  1525  3754 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-27 11:48:20.692  1525  3754 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-27 11:48:20.692  1525  3754 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-27 11:48:20.692  1525  3754 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-27 11:48:20.692  1525  3754 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-27 11:48:20.692  1525  3754 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-27 11:48:20.692  1525  3754 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-27 11:48:20.692  1525  3754 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-27 11:48:20.692  1525  3754 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-27 11:48:20.692  1525  3754 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-27 11:48:20.692  1525  3754 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-27 11:48:20.692  1525  3754 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-27 11:48:20.692  1525  3754 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,07-27 11:48:21.106  1525  3754 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,07-27 11:48:21.107  1525  3754 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-27 11:48:21.107  1525  3754 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 11:48:21.107  1525  3754 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 11:48:21.123  1525  3754 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-27 11:48:21.123  1525  3754 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-27 11:48:21.123  1525  3754 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-27 11:48:21.123  1525  3754 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-27 11:48:21.123  1525  3754 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-27 11:48:21.123  1525  3754 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-27 11:48:21.123  1525  3754 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-27 11:48:21.123  1525  3754 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-27 11:48:21.123  1525  3754 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-27 11:48:21.123  1525  3754 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-27 11:48:21.123  1525  3754 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-27 11:48:21.123  1525  3754 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-27 11:48:21.123  1525  3754 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,07-27 11:48:23.969   874  2027 D NetlinkSocketObserver: NeighborEvent{elapsedMs=166397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-27 11:48:28.370  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-27 11:48:28.370  3702  3748 I jxcore-log: 
07-27 11:48:28.373  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-27 11:48:28.373  3702  3748 I jxcore-log: 
,07-27 11:48:28.381  3702  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:48:28.381  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:28.381  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:28.381  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:48:28.381  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:48:28.381  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:48:28.381  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:48:28.381  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 11:48:28.386  3702  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-27 11:48:28.388  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-27 11:48:28.388  3702  3748 I jxcore-log: 
,07-27 11:48:28.390  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-27 11:48:28.390  3702  3748 I jxcore-log: 
,07-27 11:48:28.719  3702  3748 D ExecuteNativeTests: Running unit tests
,07-27 11:48:28.779  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-27 11:48:28.779  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6056f51 added. We now have 2 listener(s)
07-27 11:48:28.780  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-27 11:48:28.781  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:48:28.781  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:48:28.781  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:48:28.781  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 added. We now have 2 listener(s)
07-27 11:48:28.781  3702  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:48:28.781  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 11:48:28.785  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 11:48:28.798  3702  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:48:28.798  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:28.798  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:28.798  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:48:28.798  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:48:28.798  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:48:28.798  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:48:28.798  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 11:48:28.802  3702  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-27 11:48:28.802  3702  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-27 11:48:28.804  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:48:28.806  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:48:28.809  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,07-27 11:48:28.810  3702  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-27 11:48:28.810  3702  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-27 11:48:28.814  3702  3748 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,07-27 11:48:28.816  3702  3748 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,07-27 11:48:28.816  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,07-27 11:48:28.816  3702  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-27 11:48:28.817  3702  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-27 11:48:28.818  3702  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-27 11:48:28.819  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-27 11:48:28.819  3702  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:48:28.820  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-27 11:48:28.820  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:28.820  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:48:28.821  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:48:28.822  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6056f51 removed from the list
07-27 11:48:28.822  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:28.823  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 removed from the list
07-27 11:48:28.823  3702  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:48:28.823  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:28.824  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:28.824  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:28.825  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-27 11:48:28.825  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:48:28.825  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:28.825  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:28.827  3702  3748 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
07-27 11:48:28.827  3702  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-27 11:48:28.827  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:48:28.827  3702  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-27 11:48:28.828  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:48:28.828  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:28.828  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:28.828  3702  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6056f51 not in the list
,07-27 11:48:28.828  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:28.828  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
,07-27 11:48:28.828  3702  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:48:28.828  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 11:48:28.828  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:28.828  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:28.828  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
07-27 11:48:28.829  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:48:28.829  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:48:28.829  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-27 11:48:28.829  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
,07-27 11:48:28.834  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-27 11:48:28.834  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010],
07-27 11:48:28.834  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-27 11:48:28.834  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-27 11:48:28.834  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,07-27 11:48:28.834  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-27 11:48:28.834  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-27 11:48:28.834  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,07-27 11:48:28.834  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-27 11:48:28.835  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-27 11:48:28.835  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-27 11:48:28.835  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,07-27 11:48:28.835  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-27 11:48:28.835  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-27 11:48:28.835  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,07-27 11:48:28.835  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-27 11:48:28.835  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-27 11:48:28.835  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-27 11:48:28.835  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,07-27 11:48:28.835  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-27 11:48:28.835  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-27 11:48:28.835  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,07-27 11:48:28.835  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-27 11:48:28.835  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-27 11:48:28.835  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-27 11:48:28.835  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,07-27 11:48:28.835  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-27 11:48:28.835  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-27 11:48:28.836  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-27 11:48:28.836  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-27 11:48:28.836  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,07-27 11:48:28.836  3702  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:48:28.836  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:48:28.836  3702  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:48:28.836  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-27 11:48:28.836  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:28.836  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:28.836  3702  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6056f51 not in the list
07-27 11:48:28.836  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:28.836  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list,
07-27 11:48:28.836  3702  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:48:28.836  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:28.836  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:28.837  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
07-27 11:48:28.837  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:28.837  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:48:28.838  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:48:28.838  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
07-27 11:48:28.838  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:28.838  3702  3748 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-27 11:48:28.840  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 11:48:28.842  3702  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:48:28.842  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:28.842  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:28.842  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:48:28.842  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:48:28.842  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:48:28.842  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:48:28.842  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:48:28.844  3702  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 11:48:28.844  3702  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-27 11:48:28.845  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:48:28.846  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:48:28.846  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 11:48:28.846  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:48:28.846  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-27 11:48:28.847  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:48:28.855  3702  3748 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-27 11:48:28.855  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-27 11:48:28.867  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-27 11:48:28.871  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-27 11:48:28.872  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,07-27 11:48:28.875  3702  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,07-27 11:48:28.880  3702  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,07-27 11:48:28.881  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-27 11:48:28.881  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,07-27 11:48:28.883  3702  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,07-27 11:48:28.884  3702  3748 D BluetoothAdapter: STATE_ON
,07-27 11:48:28.891  2552  2563 D BtGatt.GattService: registerClient() - UUID=ccde5583-9465-4a26-8fac-4ee84d9b5c76
,07-27 11:48:28.893  2552  2604 D BtGatt.GattService: onClientRegistered() - UUID=ccde5583-9465-4a26-8fac-4ee84d9b5c76, clientIf=5
07-27 11:48:28.894  3702  3713 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-27 11:48:28.896  2552  2752 D BtGatt.GattService: start scan with filters
,07-27 11:48:28.901  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-27 11:48:28.902  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-27 11:48:28.902  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,07-27 11:48:28.902  2552  2607 D BtGatt.ScanManager: handling starting scan
07-27 11:48:28.902  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-27 11:48:28.904  2552  2607 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@670d5c3
,07-27 11:48:28.905  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-27 11:48:28.905  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-27 11:48:28.905  3702  3702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-27 11:48:28.906  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-27 11:48:28.910  3702  3748 I io.jxcore.node.ConnectionHelper: start: OK
,07-27 11:48:28.911  3702  3702 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:48:28.911  2552  2604 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,07-27 11:48:28.911  2552  2604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 11:48:28.913  3702  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-27 11:48:28.911  3702  3702 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-27 11:48:28.913  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-27 11:48:28.914  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 11:48:28.914  2552  2607 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,07-27 11:48:28.914  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-27 11:48:28.914  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts,
07-27 11:48:28.914  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,07-27 11:48:28.914  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,07-27 11:48:28.914  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-27 11:48:28.914  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-27 11:48:28.915  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-27 11:48:28.915  3702  3748 D BluetoothAdapter: STATE_ON
,07-27 11:48:28.916  2552  2565 D BtGatt.GattService: stopScan() - queue size =1
07-27 11:48:28.916  2552  2563 D BtGatt.GattService: unregisterClient() - clientIf=5
07-27 11:48:28.917  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-27 11:48:28.917  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-27 11:48:28.917  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-27 11:48:28.917  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-27 11:48:28.917  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-27 11:48:28.919  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-27 11:48:28.919  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-27 11:48:28.919  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-27 11:48:28.919  2552  2604 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,07-27 11:48:28.920  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 11:48:28.920  2552  2604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-27 11:48:28.920  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-27 11:48:28.920  2552  2607 D BtGatt.ScanManager: Starting BLE batch scan
,07-27 11:48:28.920  2552  2607 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-27 11:48:28.921  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-27 11:48:28.922  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 11:48:28.922  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-27 11:48:28.922  3702  3702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 11:48:28.922  3702  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6056f51 not in the list
,07-27 11:48:28.922  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-27 11:48:28.922  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:28.922  3702  3748 D io.jxcore.node.ConnectivityMonitor: stop,
07-27 11:48:28.922  3702  3702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-27 11:48:28.922  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:28.922  3702  3702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
07-27 11:48:28.922  3702  3748 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,07-27 11:48:28.925  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 11:48:28.929  3702  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:48:28.929  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:28.929  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:28.929  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:48:28.929  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:48:28.929  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:48:28.929  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:48:28.929  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 11:48:28.931  2552  2604 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,07-27 11:48:28.931  3702  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-27 11:48:28.931  2552  2604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-27 11:48:28.931  3702  3748 D io.jxcore.node.ConnectivityMonitor: start: OK,
07-27 11:48:28.931  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:48:28.931  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-27 11:48:28.931  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:48:28.931  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-27 11:48:28.934  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:48:28.936  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:48:28.937  2552  2604 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-27 11:48:28.937  2552  2604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-27 11:48:28.940  3702  3748 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-27 11:48:28.940  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-27 11:48:28.943  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-27 11:48:28.944  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-27 11:48:28.944  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-27 11:48:28.944  2552  2604 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-27 11:48:28.944  2552  2604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 11:48:28.945  2552  2607 D BtGatt.ScanManager: stopping BLe Batch
07-27 11:48:28.947  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-27 11:48:28.947  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-27 11:48:28.947  3702  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-27 11:48:28.948  3702  3748 D BluetoothAdapter: STATE_ON
07-27 11:48:28.950  2552  2563 D BtGatt.GattService: registerClient() - UUID=cab0fa79-313b-46ea-be8c-beae7189393f
07-27 11:48:28.951  2552  2604 D BtGatt.GattService: onClientRegistered() - UUID=cab0fa79-313b-46ea-be8c-beae7189393f, clientIf=5
07-27 11:48:28.952  3702  3712 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-27 11:48:28.952  2552  2604 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-27 11:48:28.952  2552  2565 D BtGatt.GattService: start scan with filters
07-27 11:48:28.952  2552  2604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 11:48:28.953  2552  2607 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-27 11:48:28.957  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-27 11:48:28.957  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-27 11:48:28.958  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,07-27 11:48:28.958  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,07-27 11:48:28.958  2552  2604 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,07-27 11:48:28.959  2552  2604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-27 11:48:28.960  2552  2607 D BtGatt.ScanManager: handling starting scan
,07-27 11:48:28.962  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-27 11:48:28.962  3702  3702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-27 11:48:28.962  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-27 11:48:28.965  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-27 11:48:28.966  2552  2604 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-27 11:48:28.966  2552  2604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-27 11:48:28.966  2552  2607 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-27 11:48:28.968  3702  3748 I io.jxcore.node.ConnectionHelper: start: OK
07-27 11:48:28.969  3702  3702 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:48:28.969  3702  3702 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,07-27 11:48:28.971  3702  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-27 11:48:28.971  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-27 11:48:28.971  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 11:48:28.971  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-27 11:48:28.971  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-27 11:48:28.971  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-27 11:48:28.971  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-27 11:48:28.971  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-27 11:48:28.972  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,07-27 11:48:28.972  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-27 11:48:28.972  3702  3748 D BluetoothAdapter: STATE_ON
07-27 11:48:28.973  2552  2565 D BtGatt.GattService: stopScan() - queue size =1
07-27 11:48:28.973  2552  2604 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-27 11:48:28.973  2552  2604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 11:48:28.973  2552  2607 D BtGatt.ScanManager: Starting BLE batch scan
07-27 11:48:28.973  2552  2607 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-27 11:48:28.973  2552  2563 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-27 11:48:28.974  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:48:28.974  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-27 11:48:28.974  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-27 11:48:28.974  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-27 11:48:28.974  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-27 11:48:28.975  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-27 11:48:28.975  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-27 11:48:28.975  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-27 11:48:28.975  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-27 11:48:28.975  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:48:28.976  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:48:28.976  3702  3702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
07-27 11:48:28.976  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 11:48:28.976  3702  3702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 11:48:28.976  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:48:28.976  3702  3702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 11:48:28.977  3702  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6056f51 not in the list
07-27 11:48:28.977  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:28.977  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:28.977  3702  3748 D io.jxcore.node.ConnectivityMonitor: stop
,07-27 11:48:28.977  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:28.977  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:28.978  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 11:48:28.978  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:48:28.979  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:48:28.979  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-27 11:48:28.979  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:28.979  3702  3748 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-27 11:48:28.981  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:48:28.982  2552  2604 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-27 11:48:28.982  2552  2604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-27 11:48:28.986  3702  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:48:28.986  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:28.986  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:28.986  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:48:28.986  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:48:28.986  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:48:28.986  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:48:28.986  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:48:28.988  2552  2604 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-27 11:48:28.989  3702  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 11:48:28.988  2552  2604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 11:48:28.989  3702  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:48:28.989  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:48:28.989  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-27 11:48:28.990  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:48:28.990  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-27 11:48:28.992  3702  3748 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-27 11:48:28.992  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-27 11:48:28.994  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:48:28.996  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-27 11:48:28.998  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-27 11:48:28.998  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-27 11:48:29.001  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:48:29.002  2552  2604 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-27 11:48:29.002  2552  2604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 11:48:29.002  2552  2607 D BtGatt.ScanManager: stopping BLe Batch
,07-27 11:48:29.004  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-27 11:48:29.004  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,07-27 11:48:29.004  3702  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-27 11:48:29.005  3702  3748 D BluetoothAdapter: STATE_ON
07-27 11:48:29.007  2552  2563 D BtGatt.GattService: registerClient() - UUID=d61159bc-5b95-420d-a2f7-44ef7aa190d2
07-27 11:48:29.008  2552  2604 D BtGatt.GattService: onClientRegistered() - UUID=d61159bc-5b95-420d-a2f7-44ef7aa190d2, clientIf=5
07-27 11:48:29.008  2552  2604 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-27 11:48:29.008  2552  2604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-27 11:48:29.008  2552  2607 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-27 11:48:29.008  3702  3712 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-27 11:48:29.008  2552  2565 D BtGatt.GattService: start scan with filters
07-27 11:48:29.012  2552  2604 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-27 11:48:29.012  2552  2604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-27 11:48:29.012  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-27 11:48:29.012  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-27 11:48:29.012  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-27 11:48:29.012  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-27 11:48:29.014  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-27 11:48:29.014  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-27 11:48:29.014  3702  3702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-27 11:48:29.015  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-27 11:48:29.016  2552  2607 D BtGatt.ScanManager: handling starting scan
,07-27 11:48:29.016  3702  3748 I io.jxcore.node.ConnectionHelper: start: OK
07-27 11:48:29.016  3702  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:48:29.016  3702  3702 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:48:29.016  3702  3702 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-27 11:48:29.017  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-27 11:48:29.017  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.017  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-27 11:48:29.017  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,07-27 11:48:29.017  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-27 11:48:29.017  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-27 11:48:29.017  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-27 11:48:29.017  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-27 11:48:29.017  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
07-27 11:48:29.019  3702  3748 D BluetoothAdapter: STATE_ON
07-27 11:48:29.019  2552  2752 D BtGatt.GattService: stopScan() - queue size =1
07-27 11:48:29.020  2552  2565 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-27 11:48:29.020  2552  2604 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-27 11:48:29.020  2552  2604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 11:48:29.020  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:48:29.020  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
07-27 11:48:29.020  2552  2607 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-27 11:48:29.020  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-27 11:48:29.020  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-27 11:48:29.020  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,07-27 11:48:29.021  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 11:48:29.021  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-27 11:48:29.021  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-27 11:48:29.021  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 11:48:29.022  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:48:29.022  3702  3702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 11:48:29.022  3702  3702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 11:48:29.022  3702  3702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-27 11:48:29.022  3702  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:48:29.023  3702  3702 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:48:29.023  3702  3702 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-27 11:48:29.023  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:48:29.023  3702  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:48:29.023  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-27 11:48:29.023  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.023  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:48:29.023  3702  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6056f51 not in the list
07-27 11:48:29.023  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.023  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
,07-27 11:48:29.023  3702  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:48:29.023  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.023  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.023  2552  2604 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-27 11:48:29.024  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.024  2552  2604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-27 11:48:29.024  2552  2607 D BtGatt.ScanManager: Starting BLE batch scan
07-27 11:48:29.024  2552  2607 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-27 11:48:29.024  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:48:29.024  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-27 11:48:29.024  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.024  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.025  3702  3748 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-27 11:48:29.025  3702  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:48:29.025  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:48:29.025  3702  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-27 11:48:29.025  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:48:29.025  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.025  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.025  3702  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6056f51 not in the list
07-27 11:48:29.025  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.025  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
,07-27 11:48:29.025  3702  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:48:29.025  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.026  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 11:48:29.026  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.026  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.026  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:48:29.026  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-27 11:48:29.026  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.026  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.027  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,07-27 11:48:29.027  3702  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:48:29.027  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:48:29.027  3702  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-27 11:48:29.028  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:48:29.028  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.028  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.028  3702  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6056f51 not in the list
07-27 11:48:29.028  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-27 11:48:29.028  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.028  3702  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:48:29.028  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.028  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.028  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 11:48:29.028  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.029  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:48:29.029  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-27 11:48:29.029  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.029  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.030  3702  3748 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,07-27 11:48:29.030  3702  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-27 11:48:29.030  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:48:29.030  3702  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-27 11:48:29.030  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:48:29.030  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.030  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.030  2552  2604 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,07-27 11:48:29.030  2552  2604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 11:48:29.030  3702  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6056f51 not in the list
07-27 11:48:29.030  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-27 11:48:29.030  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.030  3702  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:48:29.031  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 11:48:29.031  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.031  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.031  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.031  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:48:29.031  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-27 11:48:29.031  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.031  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.032  3702  3748 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-27 11:48:29.032  3702  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-27 11:48:29.032  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:48:29.032  3702  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:48:29.032  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:48:29.032  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.032  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 11:48:29.033  3702  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6056f51 not in the list
07-27 11:48:29.033  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.033  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.033  3702  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:48:29.033  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 11:48:29.033  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.033  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.033  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.034  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-27 11:48:29.034  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-27 11:48:29.034  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.034  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.034  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-27 11:48:29.034  2552  2604 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-27 11:48:29.034  2552  2604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 11:48:29.034  3702  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-27 11:48:29.034  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-27 11:48:29.034  3702  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-27 11:48:29.034  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-27 11:48:29.035  3702  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-27 11:48:29.035  3702  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:48:29.035  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:48:29.035  3702  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:48:29.035  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:48:29.035  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.035  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.035  3702  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6056f51 not in the list
07-27 11:48:29.035  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.035  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.035  3702  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:48:29.035  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.035  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.036  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.036  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.037  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:48:29.037  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:48:29.037  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.037  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorli,b.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.038  3702  3748 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 11:48:29.039  3702  3748 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-27 11:48:29.039  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-27 11:48:29.041  2552  2604 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-27 11:48:29.041  2552  2604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 11:48:29.041  2552  2607 D BtGatt.ScanManager: stopping BLe Batch
07-27 11:48:29.043  3702  3748 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 11:48:29.043  3702  3748 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-27 11:48:29.043  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-27 11:48:29.043  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-27 11:48:29.043  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-27 11:48:29.043  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-27 11:48:29.043  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-27 11:48:29.043  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-27 11:48:29.043  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-27 11:48:29.043  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-27 11:48:29.043  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-27 11:48:29.043  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-27 11:48:29.043  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-27 11:48:29.044  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-27 11:48:29.044  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-27 11:48:29.044  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-27 11:48:29.044  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-27 11:48:29.044  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-27 11:48:29.044  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-27 11:48:29.044  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-27 11:48:29.044  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-27 11:48:29.044  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-27 11:48:29.044  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-27 11:48:29.044  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-27 11:48:29.044  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-27 11:48:29.044  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-27 11:48:29.044  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-27 11:48:29.044  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-27 11:48:29.044  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-27 11:48:29.045  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-27 11:48:29.045  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-27 11:48:29.045  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-27 11:48:29.045  3702  3748 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-27 11:48:29.045  3702  3748 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-27 11:48:29.045  3702  3748 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-27 11:48:29.045  3702  3748 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 11:48:29.045  3702  3748 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-27 11:48:29.045  2552  2604 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-27 11:48:29.046  2552  2604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 11:48:29.046  2552  2607 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-27 11:48:29.046  3702  3748 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-27 11:48:29.046  3702  3748 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 11:48:29.046  3702  3748 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-27 11:48:29.046  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
07-27 11:48:29.049  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
07-27 11:48:29.050  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
07-27 11:48:29.050  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
07-27 11:48:29.050  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
07-27 11:48:29.051  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-27 11:48:29.051  3702  3748 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-27 11:48:29.051  3702  3748 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 11:48:29.051  3702  3748 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-27 11:48:29.051  3702  3763 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 394)
07-27 11:48:29.051  3702  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:48:29.052  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:48:29.052  3702  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:48:29.052  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:48:29.052  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.052  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.052  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
07-27 11:48:29.052  2552  2604 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-27 11:48:29.052  2552  2604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 11:48:29.053  3702  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6056f51 not in the list
07-27 11:48:29.053  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.053  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.053  3702  3763 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 11:48:29.053  3702  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:48:29.053  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.053  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.053  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.053  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.054  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:48:29.054  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:48:29.054  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.054  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.054  3702  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 394
07-27 11:48:29.055  3702  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 394)
07-27 11:48:29.055  2552  2749 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
07-27 11:48:29.055  3702  3763 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 394)
07-27 11:48:29.055  3702  3748 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-27 11:48:29.055  3702  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 394)
07-27 11:48:29.055  3702  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:48:29.055  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:48:29.055  3702  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:48:29.056  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:48:29.056  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.056  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.056  3702  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6056f51 not in the list
07-27 11:48:29.056  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.056  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.056  3702  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:48:29.056  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.056  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.056  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.056  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.057  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:48:29.057  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:48:29.057  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.057  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.058  3702  3748 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-27 11:48:29.058  3702  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:48:29.058  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:48:29.058  3702  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:48:29.058  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:48:29.058  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.058  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.058  3702  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6056f51 not in the list
07-27 11:48:29.058  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.058  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.058  3702  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:48:29.059  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.059  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.059  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.059  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.059  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:48:29.060  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:48:29.060  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.060  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.060  3702  3748 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-27 11:48:29.060  3702  3748 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-27 11:48:29.060  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-27 11:48:29.060  3702  3748 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-27 11:48:29.060  3702  3748 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-27 11:48:29.060  3702  3748 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-27 11:48:29.060  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-27 11:48:29.060  3702  3748 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-27 11:48:29.060  3702  3748 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-27 11:48:29.060  3702  3748 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-27 11:48:29.061  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-27 11:48:29.061  3702  3748 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-27 11:48:29.061  3702  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:48:29.061  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:48:29.061  3702  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:48:29.061  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:48:29.061  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.061  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.061  3702  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6056f51 not in the list
07-27 11:48:29.061  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.061  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.061  3702  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:48:29.061  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.061  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.061  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.061  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.062  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:48:29.062  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:48:29.062  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.063  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.063  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:48:29.063  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.063  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.063  3702  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6056f51 not in the list
07-27 11:48:29.063  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.063  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.063  3702  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:48:29.063  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.063  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.063  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.063  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.063  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:48:29.063  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.063  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.064  3702  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6056f51 not in the list
07-27 11:48:29.064  3702  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:48:29.064  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:48:29.064  3702  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:48:29.064  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:48:29.064  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.064  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.064  3702  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6056f51 not in the list
07-27 11:48:29.064  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.064  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.064  3702  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:48:29.064  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.064  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.064  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.064  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.065  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:48:29.065  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:48:29.065  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.065  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.066  3702  3748 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-27 11:48:29.066  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:48:29.067  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-27 11:48:29.068  3702  3748 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-27 11:48:29.068  3702  3748 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-27 11:48:29.068  3702  3702 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-27 11:48:29.068  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-27 11:48:29.068  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-27 11:48:29.068  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:48:29.068  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-27 11:48:29.068  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-27 11:48:29.069  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-27 11:48:29.069  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.069  3702  3748 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-27 11:48:29.069  3702  3702 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-27 11:48:29.069  3702  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6056f51 not in the list
07-27 11:48:29.069  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.069  3702  3765 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 11:48:29.069  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-27 11:48:29.069  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-27 11:48:29.069  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-27 11:48:29.069  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.069  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.070  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 11:48:29.070  3702  3702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 11:48:29.070  3702  3702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 11:48:29.070  3702  3702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 11:48:29.070  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.070  3702  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:48:29.071  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:48:29.071  3702  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:48:29.071  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:48:29.071  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.071  3702  3765 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-27 11:48:29.071  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.071  3702  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-27 11:4,8:29.071  3702  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6056f51 not in the list
07-27 11:48:29.071  3702  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-27 11:48:29.071  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.071  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.071  3702  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:48:29.071  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.071  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.071  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.071  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.071  3702  3702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-27 11:48:29.072  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:48:29.072  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:48:29.072  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.072  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.073  3702  3748 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-27 11:48:29.073  3702  3748 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-27 11:48:29.073  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-27 11:48:29.074  3702  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-27 11:48:29.075  3702  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:48:29.075  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:48:29.075  3702  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:48:29.075  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:48:29.076  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.076  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.076  3702  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6056f51 not in the list
07-27 11:48:29.076  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.076  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.076  3702  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:48:29.076  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.076  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.076  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.076  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.077  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:48:29.077  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:48:29.077  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.077  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.081  3702  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:48:29.081  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:48:29.081  3702  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:48:29.081  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:48:29.081  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.081  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.081  3702  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6056f51 not in the list
07-27 11:48:29.081  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.081  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.081  3702  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:48:29.081  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.081  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.081  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.081  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.083  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-27 11:48:29.083  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:48:29.083  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.083  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.083  3702  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:48:29.084  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:48:29.084  3702  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:48:29.084  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:48:29.084  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.084  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.084  3702  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6056f51 not in the list
07-27 11:48:29.084  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.084  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.084  3702  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:48:29.084  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.084  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.084  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:29.084  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:29.085  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:48:29.085  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:48:29.085  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:29.085  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e143b6 not in the list
07-27 11:48:29.086  3702  3748 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-27 11:48:29.086  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-27 11:48:29.086  3702  3748 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-27 11:48:29.086  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-27 11:48:29.086  3702  3748 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-27 11:48:29.086  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-27 11:48:29.087  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-27 11:48:29.087  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-27 11:48:29.088  3702  3748 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-27 11:48:29.088  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-27 11:48:29.088  3702  3748 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-27 11:48:29.088  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-27 11:48:29.088  3702  3748 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-27 11:48:29.088  3702  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-27 11:48:29.088  3702  3748 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-27 11:48:29.088  3702  3748 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-27 11:48:29.089  3702  3748 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-27 11:48:29.089  3702  3748 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-27 11:48:29.089  3702  3748 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-27 11:48:29.089  3702  3748 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-27 11:48:29.090  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:48:29.090  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@21863a8 added. We now have 2 listener(s)
07-27 11:48:29.090  3702  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:48:29.091  3702  3748 D BluetoothAdapter: enable(): BT is already enabled..!
07-27 11:48:29.091   874  1776 D WifiService: setWifiEnabled: true pid=3702, uid=10000
07-27 11:48:29.091   874  1776 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-27 11:48:29.092  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:48:29.092  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@eafcec1 added. We now have 3 listener(s)
07-27 11:48:29.092  3702  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:48:29.096  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:48:29.096  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c200666 added. We now have 4 listener(s)
07-27 11:48:29.096  3702  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:48:29.097  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:48:29.097  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@479fda7 added. We now have 5 listener(s)
07-27 11:48:29.097  3702  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:48:29.099   874  1767 D WifiService: setWifiEnabled: false pid=3702, uid=10000
07-27 11:48:29.099   874  1767 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-27 11:48:29.107  2552  2600 D BluetoothAdapterState: Current state: ON, message: 23
07-27 11:48:29.107  2552  2600 D BluetoothAdapterProperties: Setting state to 13
07-27 11:48:29.107  2552  2600 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-27 11:48:29.108  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:48:29.108  2552  2600 D BluetoothAdapterProperties: onBluetoothDisable()
07-27 11:48:29.109  2552  2600 I BluetoothAdapterState: Entering PendingCommandState
07-27 11:48:29.112  2552  2552 D BluetoothMapService: onReceive
07-27 11:48:29.112  2552  2552 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:48:29.112  2552  2552 D BluetoothMapService: STATE_TURNING_OFF
07-27 11:48:29.112  2552  2552 D BluetoothMapService: MAP Service closeService in
07-27 11:48:29.113  2552  2552 D BluetoothMapMasInstance0: MAP Service shutdown
07-27 11:48:29.113  2552  2552 D ObexServerSockets0: shutdown(block = true)
07-27 11:48:29.113  2552  2552 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-27 11:48:29.114  2552  2552 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-27 11:48:29.114  2552  2761 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-27 11:48:29.114  2552  2760 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-27 11:48:29.114  2552  2749 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-27 11:48:29.115  2552  2552 I BtOppRfcommListener: stopping Accept Thread
07-27 11:48:29.115  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-27 11:48:29.116  2552  3289 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 11:48:29.116   874  1317 D WifiStateMachine: WifiStateMachine: Leaving Connected state
07-27 11:48:29.116  2552  3289 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-27 11:48:29.116   874  1317 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
07-27 11:48:29.116   874  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-27 11:48:29.116   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 11:48:29.123  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:48:29.123  3702  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:48:29.123  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:29.123  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:29.123  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:48:29.123  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:48:29.123  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:48:29.123  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:48:29.123  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:48:29.124   874   887 I ActivityManager: Start proc 3768:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
07-27 11:48:29.124  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:48:29.124  3702  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 11:48:29.124  3702  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:48:29.125  2552  2604 D BluetoothAdapterProperties: Scan Mode:20
07-27 11:48:29.125  2552  2600 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-27 11:48:29.126   874  1317 E native  : do suspend true
07-27 11:48:29.127  2552  2552 D HeadsetService: Received stop request...Stopping profile...
07-27 11:48:29.127  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:48:29.128   874   874 D BluetoothHeadset: Proxy object disconnected
07-27 11:48:29.128  1748  1761 D BluetoothHeadset: Proxy object disconnected
07-27 11:48:29.129  2552  2552 D A2dpService: Received stop request...Stopping profile...
07-27 11:48:29.129  2552  2755 D A2dpStateMachine: Exit Disconnected: -1
07-27 11:48:29.129  1372  1392 D BluetoothHeadset: Proxy object disconnected
07-27 11:48:29.130   874   874 D BluetoothHeadset: Proxy object disconnected
07-27 11:48:29.130   874   874 D BluetoothHeadset: Proxy object disconnected
07-27 11:48:29.130   874   874 D BluetoothA2dp: Proxy object disconnected
07-27 11:48:29.131  1372  1372 D HeadsetProfile: Bluetooth service disconnected
07-27 11:48:29.131  1372  1372 D BluetoothA2dp: Proxy object disconnected
07-27 11:48:29.132  2552  2552 V BluetoothAdapterState: isTurningOff()=true
07-27 11:48:29.132  2552  2552 V BluetoothAdapterState: isTurningOn()=false
07-27 11:48:29.132  2552  2552 V BluetoothAdapterState: isBleTurningOn()=false
07-27 11:48:29.132  2552  2552 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 11:48:29.132  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:48:29.133  2552  2552 D HidService: Received stop request...Stopping profile...
07-27 11:48:29.133  2552  2552 D HidService: Stopping Bluetooth HidService
,07-27 11:48:29.133  1372  1372 D BluetoothInputDevice: Proxy object disconnected
07-27 11:48:29.133  1372  1372 D HidProfile: Bluetooth service disconnected
07-27 11:48:29.136  2552  2552 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-27 11:48:29.136  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:48:29.136  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:48:29.136  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:29.136  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:29.136  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:48:29.136  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:48:29.136  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:48:29.136  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:48:29.136  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:48:29.136  2552  2728 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-27 11:48:29.136  2552  2728 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-27 11:48:29.136  2552  2728 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-27 11:48:29.136  2552  2604 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-27 11:48:29.136  2552  2604 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,07-27 11:48:29.136  2552  2552 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-27 11:48:29.137  2552  2552 D HealthService: Received stop request...Stopping profile...
07-27 11:48:29.137  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:48:29.137  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 11:48:29.138   874  2030 D DhcpClient: Clearing IP address
,07-27 11:48:29.138   372   872 D CommandListener: Clearing all IP addresses on wlan0
,07-27 11:48:29.139  2552  2552 V BluetoothAdapterState: isTurningOff()=true
07-27 11:48:29.139  2552  2552 V BluetoothAdapterState: isTurningOn()=false
07-27 11:48:29.139  2552  2552 V BluetoothAdapterState: isBleTurningOn()=false
,07-27 11:48:29.139  2552  2552 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 11:48:29.140  2552  2552 D PanService: Received stop request...Stopping profile...
07-27 11:48:29.141  1372  1372 D BluetoothPan: BluetoothPAN Proxy object disconnected
,07-27 11:48:29.141  1372  1372 D PanProfile: Bluetooth service disconnected
07-27 11:48:29.141  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:48:29.141   372   872 D CommandListener: Setting iface cfg
07-27 11:48:29.143  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:48:29.145  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:48:29.145  1525  2304 V NativeCrypto: Read error: ssl=0x9ad87000: I/O error during system call, Connection timed out
07-27 11:48:29.146   874  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-27 11:48:29.146   874  1317 D WifiStateMachine: Start Disconnecting Watchdog 1
07-27 11:48:29.146   874  2033 D DhcpClient: Receive thread stopped
07-27 11:48:29.146   874  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
07-27 11:48:29.147   874  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-27 11:48:29.147   874  1317 E native  : do suspend true
07-27 11:48:29.149  2552  2604 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,07-27 11:48:29.149  2552  2728 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-27 11:48:29.149  2552  2728 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-27 11:48:29.149  2552  2728 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 11:48:29.149  2552  2728 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 11:48:29.149  2552  2728 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 11:48:29.149  2552  2728 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 11:48:29.150  2552  2552 D BluetoothMapService: Received stop request...Stopping profile...
07-27 11:48:29.150  2552  2552 D BluetoothMapService: stop()
,07-27 11:48:29.153  2552  2552 D BluetoothMapAppObserver: deinitObservers()
,07-27 11:48:29.153  2552  2552 D BluetoothMapAppObserver: removeReceiver()
07-27 11:48:29.153   395   395 E Parcel  : Reading a NULL string not supported here.
,07-27 11:48:29.154  1372  1372 D BluetoothMap: Proxy object disconnected
,07-27 11:48:29.154  1372  1372 D MapProfile: Bluetooth service disconnected
07-27 11:48:29.154  2552  2552 V BluetoothAdapterState: isTurningOff()=true
07-27 11:48:29.154  2552  2552 V BluetoothAdapterState: isTurningOn()=false
07-27 11:48:29.154  2552  2552 V BluetoothAdapterState: isBleTurningOn()=false
,07-27 11:48:29.154   874  1320 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-27 11:48:29.154  2552  2552 V BluetoothAdapterState: isBleTurningOff()=false
07-27 11:48:29.155  2552  2552 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-27 11:48:29.155  2552  2604 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-27 11:48:29.155  2552  2552 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-27 11:48:29.156  2552  2552 V BluetoothAdapterState: isTurningOff()=true
,07-27 11:48:29.156  2552  2552 V BluetoothAdapterState: isTurningOn()=false
07-27 11:48:29.156  2552  2552 V BluetoothAdapterState: isBleTurningOn()=false
07-27 11:48:29.156  2552  2552 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 11:48:29.156  2552  2552 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-27 11:48:29.156  2552  2604 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-27 11:48:29.157  2552  2552 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-27 11:48:29.157  2552  2552 V BluetoothAdapterState: isTurningOff()=true
07-27 11:48:29.157  2552  2552 V BluetoothAdapterState: isTurningOn()=false
,07-27 11:48:29.157  2552  2552 V BluetoothAdapterState: isBleTurningOn()=false
07-27 11:48:29.157  2552  2552 V BluetoothAdapterState: isBleTurningOff()=false
07-27 11:48:29.157  2552  2552 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-27 11:48:29.158  2552  2552 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-27 11:48:29.159  2552  2552 D BluetoothMapService: MAP Service closeService in
07-27 11:48:29.159  2552  2552 V BluetoothAdapterState: isTurningOff()=true
07-27 11:48:29.159  2552  2552 V BluetoothAdapterState: isTurningOn()=false
07-27 11:48:29.159  2552  2552 V BluetoothAdapterState: isBleTurningOn()=false
,07-27 11:48:29.159  2552  2552 V BluetoothAdapterState: isBleTurningOff()=false
07-27 11:48:29.159  2552  2600 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-27 11:48:29.159  2552  2600 D BluetoothAdapterProperties: Setting state to 15
07-27 11:48:29.159  2552  2600 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-27 11:48:29.159  2552  2552 D BluetoothMapService: cleanup()
07-27 11:48:29.159  2552  2552 D BluetoothMapService: MAP Service closeService in
07-27 11:48:29.160  1372  1386 D BluetoothMap: onBluetoothStateChange: up=false
07-27 11:48:29.160   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
07-27 11:48:29.160   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 11:48:29.160  1372  1392 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-27 11:48:29.161  1748  1761 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 11:48:29.161  1372  1709 D BluetoothPan: onBluetoothStateChange on: false
07-27 11:48:29.162  2552  2600 I BluetoothAdapterState: Entering BleOnState
07-27 11:48:29.162  1372  1386 D BluetoothA2dp: onBluetoothStateChange: up=false
07-27 11:48:29.163  1372  1392 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-27 11:48:29.163   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 11:48:29.163   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 11:48:29.163  1372  1709 D BluetoothPbap: onBluetoothStateChange: up=false
07-27 11:48:29.164  2552  2600 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-27 11:48:29.164  2552  2600 D BluetoothAdapterProperties: Setting state to 16
,07-27 11:48:29.164  2552  2600 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-27 11:48:29.165  2552  2600 D BluetoothAdapterProperties: onBleDisable
07-27 11:48:29.165  2552  2600 I BluetoothAdapterState: Entering PendingCommandState
07-27 11:48:29.165  2552  2601 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-27 11:48:29.166  2552  2728 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,07-27 11:48:29.166  2552  2728 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-27 11:48:29.166  2552  2604 D BluetoothAdapterProperties: Scan Mode:20
07-27 11:48:29.167  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:48:29.167  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:48:29.167  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:29.167  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:29.167  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:48:29.167  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:48:29.167  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:48:29.167  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:48:29.167  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:48:29.167  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:48:29.168  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:48:29.170  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:48:29.170  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:48:29.170  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:29.170  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:29.170  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:48:29.170  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:48:29.170  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:48:29.170  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:48:29.170  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:48:29.170  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:48:29.171  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:48:29.172  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:48:29.173  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:48:29.181  1525  2304 V NativeCrypto: SSL shutdown failed: ssl=0x9ad87000: I/O error during system call, Broken pipe
,07-27 11:48:29.192   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-27 11:48:29.195  3768  3768 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,07-27 11:48:29.203  3768  3768 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-27 11:48:29.208  1525  1525 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-27 11:48:29.209   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-27 11:48:29.209   372   872 D CommandListener: Clearing all IP addresses on wlan0
,07-27 11:48:29.209   874  1320 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-27 11:48:29.210   874  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-27 11:48:29.212   874   891 D Tethering: MasterInitialState.processMessage what=3
07-27 11:48:29.213  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:48:29.214  3276  3276 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@9537d83 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
07-27 11:48:29.214  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:48:29.223   874  1729 I ActivityManager: Start proc 3785:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,07-27 11:48:29.224   874  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-27 11:48:29.230   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@88c1f3:true
,07-27 11:48:29.239   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,07-27 11:48:29.242  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:48:29.242   874  1317 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-27 11:48:29.242  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:48:29.242  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:29.242  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:29.242  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:48:29.242  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:48:29.242  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:48:29.242  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:48:29.242  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:48:29.242  1854  2072 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:48:29.243  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:48:29.243  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:48:29.244  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:48:29.244  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:48:29.244  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:29.244  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:29.244  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:48:29.244  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:48:29.244  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:48:29.244  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:48:29.244  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:48:29.245  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:48:29.246  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:48:29.255  3768  3768 D LocalBluetoothProfileManager: Adding local MAP profile
,07-27 11:48:29.260  3768  3768 D BluetoothMap: Create BluetoothMap proxy object
,07-27 11:48:29.268  3785  3785 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,07-27 11:48:29.268   372   872 E Netd    : netlink response contains error (No such file or directory)
,07-27 11:48:29.270  3768  3768 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-27 11:48:29.279  3768  3768 D DockEventReceiver: finishStartingService: stopping service
,07-27 11:48:29.290   874   885 I ActivityManager: Killing 3276:com.google.android.music:main/u0a66 (adj 15): empty #17
,07-27 11:48:29.368  2552  2604 I bt_hci  : shut_down
,07-27 11:48:29.369  2552  2608 D bt_hwcfg: hw_epilog_process
,07-27 11:48:29.370  2552  2608 I bt_vendor: low_power_mode_cb
,07-27 11:48:29.392  2552  2608 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-27 11:48:29.392  2552  2608 I bt_vendor: epilog_cb
07-27 11:48:29.392  2552  2608 I bt_hci  : epilog_finished_callback
,07-27 11:48:29.397  2552  2604 I bt_hci_h4: hal_close
,07-27 11:48:29.397  2552  2604 I bt_userial_vendor: device fd = 51 close
,07-27 11:48:29.476  3785  3785 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at java.io.File.exists(File.java:361)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-27 11:48:29.476  3785  3785 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-27 11:48:29.476  3785  3785 D StrictMode: 	,at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 11:48:29.476  3785  3785 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2,
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
,07-27 11:48:29.476  3785  3785 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384),
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-27 11:48:29.476  3785  3785 D StrictMode: 	,at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531),
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 11:48:29.476  3785  3785 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.r.e.b(PG:170)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27, 11:48:29.476  3785  3785 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 11:48:29.476  3785  3785 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-27 11:48:29.476  3785  3785 D StrictMode: ,	at java.io.FileInputStream.read(FileInputStream.java:177)
,07-27 11:48:29.476  3785  3785 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.r.k.d(PG:1187),
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.r.k.c(PG:18147)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.r.k.d(PG:583)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.r.v.a(PG:1161)
,07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.r.e.b(PG:170)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244),
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 11:48:29.476  3785  3785 D StrictMode: 	,at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 11:48:29.476  3785  3785 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-27 11:48:29.477  3785  3785 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 11:48:29.477  3785  3785 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at java.io.File.exists(File.java:361)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
07-27 11:48:29.477  3785  3785 D StrictMode: 	,at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 11:48:29.477  3785  3785 D StrictMode: 	,at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
,07-27 11:48:29.477  3785  3785 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 11:48:29.477  3785  3785 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 11:48:29.477  3785  3785 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at java.io.File.doAccess(File.java:281),
07-27 11:48:29.477  3785  3785 D StrictMode: 	at java.io.File.exists(File.java:361)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
,07-27 11:48:29.477  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 11:48:29.477  3785  3785 D StrictMode: ,	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 11:48:29.477  3785  3785 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 11:48:29.477  3785  3785 D StrictMode: 	,at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at java.io.File.lastModified(File.java:569)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 11:48:29.477  3785  3785 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-27 11:48:29.482  3768  3768 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-27 11:48:29.489  1525  1525 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-27 11:48:29.496  3768  3768 D DockEventReceiver: finishStartingService: stopping service
,07-27 11:48:29.514   874  1776 I ActivityManager: Killing 3320:com.android.providers.calendar/u0a3 (adj 15): empty #17
,07-27 11:48:29.577  1867  1867 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,07-27 11:48:29.577  2552  2601 D bt_stack_manager: event_shut_down_stack finished.
07-27 11:48:29.577  2552  2600 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,07-27 11:48:29.583  2552  2600 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-27 11:48:29.583  2552  2552 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-27 11:48:29.585  2552  2552 D BtGatt.GattService: Received stop request...Stopping profile...
,07-27 11:48:29.585  2552  2552 D BtGatt.GattService: stop()
07-27 11:48:29.585  2552  2552 D BtGatt.AdvertiseManager: advertise clients cleared
,07-27 11:48:29.586  1867  1867 D SystemUpdateService: onCreate
,07-27 11:48:29.589  2552  2552 V BluetoothAdapterState: isTurningOff()=false
,07-27 11:48:29.590  2552  2552 V BluetoothAdapterState: isTurningOn()=false
07-27 11:48:29.590  2552  2552 V BluetoothAdapterState: isBleTurningOn()=false
07-27 11:48:29.590  2552  2552 V BluetoothAdapterState: isBleTurningOff()=true
,07-27 11:48:29.590  1867  1867 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,07-27 11:48:29.591  2552  2600 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,07-27 11:48:29.591  2552  2600 D BluetoothAdapterProperties: Setting state to 10
07-27 11:48:29.591  2552  2600 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-27 11:48:29.591  2552  2600 I BluetoothAdapterState: Entering OffState
07-27 11:48:29.592   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,07-27 11:48:29.599  1867  3819 I SystemUpdateService: active receiver: enabled
,07-27 11:48:29.603  2552  2552 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
07-27 11:48:29.603  2552  2552 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-27 11:48:29.603  2552  2552 I BluetoothServiceJni: cleanupNative: return from cleanup
07-27 11:48:29.604  2552  2601 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,07-27 11:48:29.609  2552  2601 D bt_stack_manager: event_clean_up_stack finished.
,07-27 11:48:29.610  1867  1867 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
07-27 11:48:29.611  1867  2344 I iu.UploadsManager: num queued entries: 0
,07-27 11:48:29.626  2552  2552 I art     : System.exit called, status: 0
,07-27 11:48:29.626  2552  2552 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-27 11:48:29.630  1867  1867 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-27 11:48:29.632  1867  2344 I iu.UploadsManager: num updated entries: 0
,07-27 11:48:29.633  1867  2344 I iu.SyncManager: NEXT; no task
,07-27 11:48:29.634  1867  1867 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-27 11:48:29.651  1867  3819 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,07-27 11:48:29.654   874  1767 I ActivityManager: Start proc 3822:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,07-27 11:48:29.661  1867  3819 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,07-27 11:48:29.661  1867  3819 I SystemUpdateService: now status is 0 (complete)
,07-27 11:48:29.661  1867  3819 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
07-27 11:48:29.661  1867  3819 I SystemUpdateService: file has been verified
,07-27 11:48:29.661  1867  3819 I SystemUpdateService: OTA package size = 12249756
,07-27 11:48:29.669  1867  3819 I SystemUpdateService: showing system update notification
,07-27 11:48:29.678   874  2996 I ActivityManager: Process com.android.bluetooth (pid 2552) has died
,07-27 11:48:29.714  3822  3822 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,07-27 11:48:29.716  3822  3822 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:48:29.721  1867  1867 D SystemUpdateService: onDestroy
,07-27 11:48:29.735  3822  3822 D SprintDMHelper: simOperator: 
,07-27 11:48:29.735  3822  3822 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-27 11:48:29.748  3785  3815 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-27 11:48:29.756   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8340a36:true
,07-27 11:48:29.775   874  1767 I ActivityManager: Start proc 3836:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,07-27 11:48:29.775   874  1767 I ActivityManager: Killing 1704:android.process.acore/u0a5 (adj 15): empty #17
,07-27 11:48:29.945  3353  3850 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,07-27 11:48:29.961   874  1759 I ActivityManager: Start proc 3851:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-27 11:48:30.018  3851  3851 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,07-27 11:48:30.068  3851  3851 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-27 11:48:30.068  3851  3851 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-27 11:48:30.068  3851  3851 I GAv4    :   adb logcat -s GAv4
,07-27 11:48:30.084  3851  3851 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-27 11:48:30.091  3851  3851 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-27 11:48:30.120  3851  3868 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-27 11:48:30.229  3851  3851 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,07-27 11:48:30.267  3851  3851 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-27 11:48:30.278  3851  3851 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 2700-2706)
,07-27 11:48:30.282  3851  3851 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-27 11:48:30.297  3851  3851 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {afb0665}
07-27 11:48:30.297  3851  3851 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-27 11:48:30.297  3851  3851 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-27 11:48:30.306  3851  3851 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-27 11:48:30.308  3851  3851 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-27 11:48:30.324  3851  3851 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-27 11:48:30.336  3851  3851 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-27 11:48:30.336  3851  3851 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-27 11:48:30.337  3851  3851 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-27 11:48:30.337  3851  3851 I Adreno  : Build Date                       : 10/20/15
07-27 11:48:30.337  3851  3851 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-27 11:48:30.337  3851  3851 I Adreno  : Local Branch                     : M14
07-27 11:48:30.337  3851  3851 I Adreno  : Remote Branch                    : 
07-27 11:48:30.337  3851  3851 I Adreno  : Remote Branch                    : 
07-27 11:48:30.337  3851  3851 I Adreno  : Reconstruct Branch               : 
,07-27 11:48:30.403  3851  3851 I NSApplication: Starting up...
,07-27 11:48:30.426  3851  3897 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-27 11:48:30.432   874  1401 I ActivityManager: Start proc 3902:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-27 11:48:30.433   874  1401 I ActivityManager: Killing 3561:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,07-27 11:48:30.507  3902  3902 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-27 11:48:30.700   874  1539 I ActivityManager: Killing 3577:com.android.musicfx/u0a18 (adj 15): empty #17
,07-27 11:48:30.790   874  1776 I ActivityManager: Start proc 3916:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,07-27 11:48:30.871  3916  3916 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,07-27 11:48:30.932  3916  3916 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,07-27 11:48:30.993   874  1703 I ActivityManager: Killing 2049:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,07-27 11:48:32.128   874  1722 D WifiService: setWifiEnabled: true pid=3702, uid=10000
,07-27 11:48:32.129   874  1722 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-27 11:48:32.140   874  1317 D WifiConfigStore: Loading config and enabling all networks 
,07-27 11:48:32.148  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-27 11:48:32.149  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:48:32.149  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:32.149  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:32.149  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:48:32.149  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:48:32.149  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:48:32.149  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:48:32.149  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:48:32.149  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-27 11:48:32.150  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:48:32.153  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-27 11:48:32.153  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:48:32.153  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:32.153  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:32.153  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:48:32.153  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:48:32.153  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:48:32.153  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:48:32.153  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:48:32.153  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:48:32.154  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:48:32.174   874  1317 D WifiConfigStore: loaded 0 passpoint configs
,07-27 11:48:32.174   874  1317 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-27 11:48:32.175   874  1317 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,07-27 11:48:32.176   874  1317 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-27 11:48:32.176   874  1317 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-27 11:48:32.177   874  1317 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,07-27 11:48:32.177   874  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
07-27 11:48:32.177   874  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-27 11:48:32.194   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
07-27 11:48:32.195   874  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-27 11:48:32.196   372   872 D CommandListener: Setting iface cfg
,07-27 11:48:32.205   874  1316 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)'
,07-27 11:48:32.205   874  1316 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-27 11:48:32.206   874  1317 E native  : do suspend true
,07-27 11:48:32.222   874  1316 D WifiNative-HAL: p2pGetDeviceAddress
,07-27 11:48:32.223   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,07-27 11:48:32.223   874  1316 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,07-27 11:48:33.513   874  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-27 11:48:33.586   874  1317 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.25 rxSuccessRate=9.19 delta 1000 -> 994
,07-27 11:48:33.590   874  1317 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,07-27 11:48:33.591   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 11:48:33.607   874  1317 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,07-27 11:48:33.660   874  1317 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,07-27 11:48:33.662  1468  1468 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-27 11:48:34.093  1468  1468 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-27 11:48:34.133  1468  1468 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-27 11:48:34.134  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,07-27 11:48:34.146   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,07-27 11:48:34.160   874  1317 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-27 11:48:34.160   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 11:48:34.160   874  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-27 11:48:34.179   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 11:48:34.193   372   872 D CommandListener: Setting iface cfg
,07-27 11:48:34.195   874  1317 D WifiStateMachine: Start Dhcp Watchdog 2
,07-27 11:48:34.203   874  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,07-27 11:48:34.240   874  3949 D DhcpClient: Receive thread started
,07-27 11:48:34.320   874  1317 E native  : do suspend false
,07-27 11:48:34.337   874  2030 D DhcpClient: Broadcasting DHCPDISCOVER
,07-27 11:48:34.349   874  3949 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172646, domain null
,07-27 11:48:34.349   874  2030 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172646 seconds
,07-27 11:48:34.352   874  2030 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,07-27 11:48:34.363   874  3949 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-27 11:48:34.364   874  2030 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-27 11:48:34.369   372   872 D CommandListener: Setting iface cfg
,07-27 11:48:34.374   874  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,07-27 11:48:34.376   874  1317 E native  : do suspend true
,07-27 11:48:34.377   874  2030 D DhcpClient: Scheduling renewal in 86399s
,07-27 11:48:34.391   874  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-27 11:48:34.392   874  1317 D WifiConfigStore: No blacklist allowed without epno enabled
,07-27 11:48:34.392   874  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-27 11:48:34.393   874  1317 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-27 11:48:34.395   874  1320 D ConnectivityService: Adding iface wlan0 to network 101
,07-27 11:48:34.426   874  1320 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-27 11:48:34.426   874  1320 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
07-27 11:48:34.427   874  1320 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,07-27 11:48:34.428   874  1320 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,07-27 11:48:34.428   874  1320 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,07-27 11:48:34.434   874  1320 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-27 11:48:34.439   874  1320 D ConnectivityService: scheduleUnvalidatedPrompt 101
07-27 11:48:34.439   874  1320 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
07-27 11:48:34.439   874  1320 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
07-27 11:48:34.439   874  1317 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-27 11:48:34.439   874  1320 D ConnectivityService:    accepting network in place of null
07-27 11:48:34.439   874  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-27 11:48:34.440   874  1320 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-27 11:48:34.449   874  3948 D NetlinkSocketObserver: NeighborEvent{elapsedMs=176877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-27 11:48:34.462   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-27 11:48:34.467  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 11:48:34.472  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 11:48:34.473  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 11:48:34.493   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-27 11:48:34.496   874  1320 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,07-27 11:48:34.496   874  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:48:34.499   874   891 D Tethering: MasterInitialState.processMessage what=3,
07-27 11:48:34.502  1525  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
07-27 11:48:34.505  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:48:34.505  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:48:34.505  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:34.505  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:34.505  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:48:34.505  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:48:34.505  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:48:34.505  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:48:34.505  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 11:48:34.505  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:48:34.505  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 11:48:34.502  1525  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,07-27 11:48:34.507  1525  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 11:48:34.507  1525  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-27 11:48:34.508  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:48:34.508  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:48:34.508  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:34.508  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:34.508  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:48:34.508  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:48:34.508  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:48:34.508  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:48:34.508  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 11:48:34.508   874  1320 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
07-27 11:48:34.508  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:48:34.508  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-27 11:48:34.514   874  3947 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:816::200e
07-27 11:48:34.519  1867  1867 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,07-27 11:48:34.521  1867  1867 D SystemUpdateService: onCreate
,07-27 11:48:34.525  1867  1867 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,07-27 11:48:34.526  3393  3393 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-27 11:48:34.527  3393  3393 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-27 11:48:34.528  3393  3393 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,07-27 11:48:34.531  1867  3961 I SystemUpdateService: active receiver: enabled
,07-27 11:48:34.536  1867  3961 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,07-27 11:48:34.538  1867  3961 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,07-27 11:48:34.538  1867  3961 I SystemUpdateService: now status is 0 (complete)
07-27 11:48:34.538  1867  3961 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
07-27 11:48:34.538  1867  3961 I SystemUpdateService: file has been verified
,07-27 11:48:34.540  1867  3961 I SystemUpdateService: OTA package size = 12249756
,07-27 11:48:34.545  1867  3961 I SystemUpdateService: showing system update notification
,07-27 11:48:34.548  1867  1867 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-27 11:48:34.549  1867  2344 I iu.UploadsManager: num queued entries: 0
07-27 11:48:34.550  1867  2344 I iu.UploadsManager: num updated entries: 0
,07-27 11:48:34.551  1867  2344 I iu.SyncManager: NEXT; no task
,07-27 11:48:34.558  1867  1867 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-27 11:48:34.559  1867  1867 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-27 11:48:34.561  3822  3822 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:48:34.562  1867  3966 I MDM     : [213] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,07-27 11:48:34.562  1867  3966 W BaseAppContext: Using Auth Proxy for data requests.
07-27 11:48:34.563  1867  3966 V GoogleAuthProtoRequest: [213] a.<init>: mAccountName set to: thalitester@gmail.com
,07-27 11:48:34.567  3822  3822 D SprintDMHelper: simOperator: 
,07-27 11:48:34.567  3822  3822 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-27 11:48:34.569  1867  1867 D SystemUpdateService: onDestroy
,07-27 11:48:34.592   874  3947 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 27 Jul 2016 09:48:34 GMT], X-Android-Received-Millis=[1469612914591], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1469612914562]}
,07-27 11:48:34.595   874  1320 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-27 11:48:34.595   874  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
07-27 11:48:34.595   874  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-27 11:48:34.597   874  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-27 11:48:34.607  1525  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,07-27 11:48:34.608  1525  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
07-27 11:48:34.608  1525  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 11:48:34.608  1525  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 11:48:34.626  1867  3966 E MDM     : [213] SitrepService.a: Error sending sitrep.
,07-27 11:48:34.695  3353  3968 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,07-27 11:48:34.997   874  1776 I ActivityManager: Killing 3599:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,07-27 11:48:35.136   874  1738 D WifiService: setWifiEnabled: false pid=3702, uid=10000
,07-27 11:48:35.136   874  1738 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-27 11:48:35.164  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,07-27 11:48:35.173   874  1317 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,07-27 11:48:35.173   874  1317 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
07-27 11:48:35.173   874  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-27 11:48:35.174   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 11:48:35.195   874  1317 E native  : do suspend true
,07-27 11:48:35.211   874  2030 D DhcpClient: Clearing IP address
,07-27 11:48:35.212   372   872 D CommandListener: Setting iface cfg
,07-27 11:48:35.220   372   872 D CommandListener: Clearing all IP addresses on wlan0
,07-27 11:48:35.223   874  3949 D DhcpClient: Receive thread stopped
,07-27 11:48:35.228  1525  3973 V NativeCrypto: Read error: ssl=0xaa182800: I/O error during system call, Connection timed out
,07-27 11:48:35.233  1525  3973 V NativeCrypto: SSL shutdown failed: ssl=0xaa182800: I/O error during system call, Broken pipe
,07-27 11:48:35.242   874  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,07-27 11:48:35.243   874  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,07-27 11:48:35.247   874  1317 D WifiStateMachine: Start Disconnecting Watchdog 2,
07-27 11:48:35.253   395   395 E Parcel  : Reading a NULL string not supported here.
,07-27 11:48:35.253   874  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-27 11:48:35.253   874  1317 E native  : do suspend true
,07-27 11:48:35.262   874  1320 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,07-27 11:48:35.296   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-27 11:48:35.330   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-27 11:48:35.330   372   872 D CommandListener: Clearing all IP addresses on wlan0
,07-27 11:48:35.331   874  1320 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-27 11:48:35.332   874  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:48:35.336   874   891 D Tethering: MasterInitialState.processMessage what=3
,07-27 11:48:35.341   874  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
07-27 11:48:35.345  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:48:35.346  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:48:35.346  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:35.346  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:35.346  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:48:35.346  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:48:35.346  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:48:35.346  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:48:35.346  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:48:35.347  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:48:35.347  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:48:35.349  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:48:35.349  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:48:35.349  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:35.349  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:35.349  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:48:35.349  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:48:35.349  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:48:35.349  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:48:35.349  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:48:35.350  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:48:35.350  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:48:35.364  1867  1867 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,07-27 11:48:35.367   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,07-27 11:48:35.373  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-27 11:48:35.373  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:48:35.373  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:35.373  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:35.373  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:48:35.373  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:48:35.373  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:48:35.373  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:48:35.373  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:48:35.373  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:48:35.373  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:48:35.374  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-27 11:48:35.374  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:48:35.374  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:35.374  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:35.374  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:48:35.374  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:48:35.374  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:48:35.374  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:48:35.374  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:48:35.374  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:48:35.374  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:48:35.374  1867  1867 D SystemUpdateService: onCreate
07-27 11:48:35.375   874  1317 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-27 11:48:35.376  1854  2072 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:48:35.377  1867  1867 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
07-27 11:48:35.395  1867  3983 I SystemUpdateService: active receiver: enabled
07-27 11:48:35.396  1867  1867 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-27 11:48:35.404  1867  1867 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-27 11:48:35.406  1867  1867 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-27 11:48:35.407  1867  3983 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,07-27 11:48:35.409  3822  3822 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:48:35.413  3822  3822 D SprintDMHelper: simOperator: 
,07-27 11:48:35.413  3822  3822 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-27 11:48:35.426   372   872 E Netd    : netlink response contains error (No such file or directory)
,07-27 11:48:35.427   874  1320 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,07-27 11:48:35.407  1867  2344 I iu.UploadsManager: num queued entries: 0
,07-27 11:48:35.447  1867  2344 I iu.UploadsManager: num updated entries: 0
,07-27 11:48:35.449  3353  3987 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,07-27 11:48:35.451  1867  3983 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,07-27 11:48:35.451  1867  3983 I SystemUpdateService: now status is 0 (complete)
07-27 11:48:35.451  1867  3983 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
07-27 11:48:35.451  1867  3983 I SystemUpdateService: file has been verified
07-27 11:48:35.451  1867  3983 I SystemUpdateService: OTA package size = 12249756
,07-27 11:48:35.458  1867  2344 I iu.SyncManager: NEXT; no task
,07-27 11:48:35.465  1867  3983 I SystemUpdateService: showing system update notification
,07-27 11:48:35.474  1867  1867 D SystemUpdateService: onDestroy
,07-27 11:48:35.496   874  1320 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,07-27 11:48:38.190   874   891 I ActivityManager: Start proc 3990:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-27 11:48:38.335  3990  3990 D AdapterServiceConfig: Adding HeadsetService
07-27 11:48:38.336  3990  3990 D AdapterServiceConfig: Adding A2dpService
,07-27 11:48:38.336  3990  3990 D AdapterServiceConfig: Adding HidService
,07-27 11:48:38.336  3990  3990 D AdapterServiceConfig: Adding HealthService
07-27 11:48:38.336  3990  3990 D AdapterServiceConfig: Adding PanService
07-27 11:48:38.336  3990  3990 D AdapterServiceConfig: Adding GattService
07-27 11:48:38.337  3990  3990 D AdapterServiceConfig: Adding BluetoothMapService
,07-27 11:48:38.356  3990  3990 D BluetoothAdapterState: make() - Creating AdapterState
,07-27 11:48:38.356   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ffcbc7:true
,07-27 11:48:38.365  3990  3990 I bt_bluedroid: init
,07-27 11:48:38.366  3990  4002 I BluetoothAdapterState: Entering OffState
,07-27 11:48:38.369  3990  4003 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-27 11:48:38.369  3990  4003 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-27 11:48:38.369  3990  4003 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-27 11:48:38.369  3990  4003 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-27 11:48:38.370  3990  3990 I bt_bluedroid: get_profile_interface socket
,07-27 11:48:38.374  3990  4006 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-27 11:48:38.377  3990  3990 I bt_bluedroid: get_profile_interface sdp
,07-27 11:48:38.377  3990  4006 D BluetoothAdapterProperties: Name is: Nexus 6
,07-27 11:48:38.383  3990  4001 I bt_bluedroid: config_hci_snoop_log
,07-27 11:48:38.385   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,07-27 11:48:38.393  3990  4002 D BluetoothAdapterState: Current state: OFF, message: 0
,07-27 11:48:38.393  3990  4002 D BluetoothAdapterProperties: Setting state to 14
07-27 11:48:38.393  3990  4002 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-27 11:48:38.397  3990  4002 D BluetoothBondStateMachine: make
,07-27 11:48:38.400  3990  4007 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-27 11:48:38.406  3990  4002 I BluetoothAdapterState: Entering PendingCommandState
,07-27 11:48:38.410  3990  3990 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-27 11:48:38.419  3990  3990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@670d5c3
,07-27 11:48:38.421  3990  3990 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-27 11:48:38.422  3990  3990 D BtGatt.GattService: Received start request. Starting profile...
07-27 11:48:38.422  3990  3990 D BtGatt.GattService: start()
,07-27 11:48:38.422  3990  3990 I bt_bluedroid: get_profile_interface gatt
,07-27 11:48:38.423  3990  3990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@670d5c3
07-27 11:48:38.423  3990  3990 D BtGatt.AdvertiseManager: advertise manager created
,07-27 11:48:38.431  3990  3990 V BluetoothAdapterState: isTurningOff()=false
07-27 11:48:38.431  3990  3990 V BluetoothAdapterState: isTurningOn()=false
,07-27 11:48:38.432  3990  3990 V BluetoothAdapterState: isBleTurningOn()=true
,07-27 11:48:38.432  3990  3990 V BluetoothAdapterState: isBleTurningOff()=false
07-27 11:48:38.432  3990  4002 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,07-27 11:48:38.433  3990  4002 I bt_bluedroid: enable
07-27 11:48:38.433  3990  4003 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-27 11:48:38.433  3990  4003 I bt_hci  : start_up
,07-27 11:48:38.440  3990  4003 I bt_vendor: alloc value 0xb39a0189
07-27 11:48:38.440  3990  4003 I bt_vendor: init
07-27 11:48:38.440  3990  4003 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-27 11:48:38.440  3990  4003 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-27 11:48:38.548  3990  4003 D bt_hci  : start_up starting async portion
,07-27 11:48:38.549  3990  4010 I bt_hci  : event_finish_startup
07-27 11:48:38.549  3990  4010 I bt_hci_h4: hal_open
,07-27 11:48:38.550  3990  4010 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-27 11:48:38.561  3990  4010 I bt_userial_vendor: device fd = 51 open
,07-27 11:48:38.590  3990  4010 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-27 11:48:38.622  3990  4010 D bt_hwcfg: Chipset BCM4354A2
,07-27 11:48:38.623  3990  4010 D bt_hwcfg: Target name = [BCM4354A2]
07-27 11:48:38.624  3990  4010 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,07-27 11:48:39.276  3990  4010 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-27 11:48:39.277  3990  4010 D bt_hwcfg: Settlement delay -- 100 ms
07-27 11:48:39.278  3990  4010 I bt_hwcfg: Setting fw settlement delay to 100 
,07-27 11:48:39.394  3990  4010 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-27 11:48:39.396  3990  4010 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,07-27 11:48:39.425  3990  4010 I bt_hwcfg: vendor lib fwcfg completed
,07-27 11:48:39.425  3990  4010 I bt_vendor: firmware callback
07-27 11:48:39.425  3990  4010 I bt_hci  : firmware_config_callback
,07-27 11:48:39.436  3990  4014 I bt_btu  : btu_task pending for preload complete event
,07-27 11:48:39.437  3990  4014 I bt_btu_task: Bluetooth chip preload is complete
07-27 11:48:39.437  3990  4014 I bt_btu  : btu_task received preload complete event
,07-27 11:48:39.445  3990  4014 I         : BTE_InitTraceLevels -- TRC_HCI,
07-27 11:48:39.445  3990  4014 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-27 11:48:39.445  3990  4014 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-27 11:48:39.445  3990  4014 I         : BTE_InitTraceLevels -- TRC_AVDT
07-27 11:48:39.445  3990  4014 I         : BTE_InitTraceLevels -- TRC_AVRC
07-27 11:48:39.446  3990  4014 I         : BTE_InitTraceLevels -- TRC_A2D
,07-27 11:48:39.446  3990  4014 I         : BTE_InitTraceLevels -- TRC_BNEP
07-27 11:48:39.446  3990  4014 I         : BTE_InitTraceLevels -- TRC_BTM
07-27 11:48:39.446  3990  4014 I         : BTE_InitTraceLevels -- TRC_GAP
07-27 11:48:39.446  3990  4014 I         : BTE_InitTraceLevels -- TRC_PAN
07-27 11:48:39.446  3990  4014 I         : BTE_InitTraceLevels -- TRC_SDP
,07-27 11:48:39.446  3990  4014 I         : BTE_InitTraceLevels -- TRC_GATT
07-27 11:48:39.446  3990  4014 I         : BTE_InitTraceLevels -- TRC_SMP
07-27 11:48:39.446  3990  4014 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-27 11:48:39.446  3990  4014 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-27 11:48:39.578  3990  4014 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb391dd9d
07-27 11:48:39.579  3990  4014 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb391dd9d ,
,07-27 11:48:39.586  3990  4006 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false,
,07-27 11:48:39.587  3990  4006 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000,
07-27 11:48:39.588  3990  4006 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
07-27 11:48:39.591  3990  4006 D BluetoothAdapterProperties: Name is: Nexus 6
,07-27 11:48:39.594  3990  4006 D BluetoothAdapterProperties: Scan Mode:20
,07-27 11:48:39.595  3990  4006 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 11:48:39.595  3990  4006 D bt_hci  : do_postload posting postload work item
07-27 11:48:39.596  3990  4010 I bt_hci  : event_postload
,07-27 11:48:39.596  3990  4010 I bt_vendor: sco_config_cb
07-27 11:48:39.596  3990  4010 I bt_hci  : sco_config_callback postload finished.
07-27 11:48:39.600  3990  4006 D bt_bte_conf: Device ID record 1 : primary
07-27 11:48:39.600  3990  4006 D bt_bte_conf:   vendorId            = 000f
07-27 11:48:39.600  3990  4006 D bt_bte_conf:   vendorIdSource      = 0001
07-27 11:48:39.600  3990  4006 D bt_bte_conf:   product             = 1200
07-27 11:48:39.601  3990  4006 D bt_bte_conf:   version             = 1436
07-27 11:48:39.601  3990  4006 D bt_bte_conf:   clientExecutableURL = 
07-27 11:48:39.601  3990  4006 D bt_bte_conf:   serviceDescription  = 
07-27 11:48:39.601  3990  4006 D bt_bte_conf:   documentationURL    = 
,07-27 11:48:39.601  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:48:39.601  3990  4006 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-27 11:48:39.602  3990  4003 D bt_stack_manager: event_start_up_stack finished
07-27 11:48:39.603  3990  4002 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-27 11:48:39.603  3990  4002 D BluetoothAdapterProperties: Setting state to 15
07-27 11:48:39.603  3990  4002 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-27 11:48:39.604  3990  4010 I bt_vendor: low_power_mode_cb
07-27 11:48:39.605  3990  4002 I BluetoothAdapterState: Entering BleOnState
07-27 11:48:39.606  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:48:39.611  3990  4002 D BluetoothAdapterState: Current state: BLE ON, message: 1
,07-27 11:48:39.611  3990  4002 D BluetoothAdapterProperties: Setting state to 11
,07-27 11:48:39.611  3990  4002 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,07-27 11:48:39.617  3990  3990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@670d5c3
07-27 11:48:39.619  3990  3990 D HeadsetService: Received start request. Starting profile...
07-27 11:48:39.623  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:48:39.625  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:48:39.625  3990  3990 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-27 11:48:39.626  3990  3990 D HeadsetStateMachine: make
07-27 11:48:39.632  3990  4002 I BluetoothAdapterState: Entering PendingCommandState
07-27 11:48:39.636  3990  3990 D HeadsetStateMachine: max_hf_connections = 1
,07-27 11:48:39.636  3990  3990 I bt_bluedroid: get_profile_interface handsfree
07-27 11:48:39.636  3990  4006 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-27 11:48:39.637  3990  4006 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,07-27 11:48:39.640  3990  3990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@670d5c3
,07-27 11:48:39.640  3990  3990 D A2dpService: Received start request. Starting profile...
,07-27 11:48:39.642  3990  3990 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-27 11:48:39.642  3990  3990 I bt_bluedroid: get_profile_interface avrcp
,07-27 11:48:39.648  3990  3990 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-27 11:48:39.649  3990  3990 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-27 11:48:39.649  3990  3990 D A2dpStateMachine: make
,07-27 11:48:39.650  3990  3990 I bt_bluedroid: get_profile_interface a2dp
,07-27 11:48:39.650  3990  4006 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,07-27 11:48:39.652  3990  4023 D A2dpStateMachine: Enter Disconnected: -2
,07-27 11:48:39.652  3990  3990 I BluetoothHidServiceJni: classInitNative: succeeds
,07-27 11:48:39.653  3990  3990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@670d5c3
,07-27 11:48:39.655  3990  3990 D HidService: Received start request. Starting profile...
,07-27 11:48:39.655  3768  3768 D BluetoothInputDevice: Proxy object connected
07-27 11:48:39.655  3990  3990 I bt_bluedroid: get_profile_interface hidhost
07-27 11:48:39.655  3990  3990 D HidService: setHidService(): set to: null
07-27 11:48:39.655  3990  4006 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38ff3e5
07-27 11:48:39.655  3990  4006 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-27 11:48:39.656  3990  3990 I BluetoothHealthServiceJni: classInitNative: succeeds
07-27 11:48:39.656  3768  3768 D HidProfile: Bluetooth service connected
07-27 11:48:39.656  3990  3990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@670d5c3
,07-27 11:48:39.657  3990  3990 D HealthService: Received start request. Starting profile...
07-27 11:48:39.659  3990  3990 I bt_bluedroid: get_profile_interface health
,07-27 11:48:39.659  3990  3990 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-27 11:48:39.660  3990  3990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@670d5c3
,07-27 11:48:39.661  3990  3990 D PanService: Received start request. Starting profile...
,07-27 11:48:39.662  3768  3768 D BluetoothPan: BluetoothPAN Proxy object connected
,07-27 11:48:39.662  3990  3990 D BluetoothPanServiceJni: initializeNative(L110): pan
07-27 11:48:39.662  3990  3990 I bt_bluedroid: get_profile_interface pan
07-27 11:48:39.663  3990  4006 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-27 11:48:39.664  3768  3768 D PanProfile: Bluetooth service connected
,07-27 11:48:39.667  3990  3990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@670d5c3
,07-27 11:48:39.669  3990  3990 D BluetoothMapService: Received start request. Starting profile...
07-27 11:48:39.669  3768  3768 D BluetoothMap: Proxy object connected
07-27 11:48:39.669  3990  3990 D BluetoothMapService: start()
07-27 11:48:39.669  3768  3768 D MapProfile: Bluetooth service connected
07-27 11:48:39.670  3768  3768 D BluetoothMap: getConnectedDevices()
,07-27 11:48:39.671  3768  3768 D BluetoothMap: Bluetooth is Not enabled
,07-27 11:48:39.671  3990  3990 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,07-27 11:48:39.672  3990  3990 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,07-27 11:48:39.672  3990  3990 D BluetoothMapAppObserver: createReceiver()
,07-27 11:48:39.673  3990  3990 D BluetoothMapAppObserver: initObservers()
07-27 11:48:39.673  3990  3990 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-27 11:48:39.682  1525  1525 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-27 11:48:39.683  3990  3990 V BluetoothAdapterState: isTurningOff()=false
07-27 11:48:39.683  3990  3990 V BluetoothAdapterState: isTurningOn()=true
07-27 11:48:39.683  3990  3990 V BluetoothAdapterState: isBleTurningOn()=false
07-27 11:48:39.683  3990  3990 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 11:48:39.685  3990  4021 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-27 11:48:39.686  3990  3990 V BluetoothAdapterState: isTurningOff()=false
07-27 11:48:39.686  3990  3990 V BluetoothAdapterState: isTurningOn()=true
,07-27 11:48:39.686  3990  3990 V BluetoothAdapterState: isBleTurningOn()=false
07-27 11:48:39.686  3990  3990 V BluetoothAdapterState: isBleTurningOff()=false
07-27 11:48:39.686  3990  3990 V BluetoothAdapterState: isTurningOff()=false
,07-27 11:48:39.686  3990  3990 V BluetoothAdapterState: isTurningOn()=true
07-27 11:48:39.686  3990  3990 V BluetoothAdapterState: isBleTurningOn()=false
,07-27 11:48:39.686  3990  3990 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 11:48:39.686  3990  3990 V BluetoothAdapterState: isTurningOff()=false
,07-27 11:48:39.687  3990  3990 V BluetoothAdapterState: isTurningOn()=true
,07-27 11:48:39.687  3990  3990 V BluetoothAdapterState: isBleTurningOn()=false
,07-27 11:48:39.687  3990  3990 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 11:48:39.687  3990  3990 V BluetoothAdapterState: isTurningOff()=false
,07-27 11:48:39.687  3990  3990 V BluetoothAdapterState: isTurningOn()=true
,07-27 11:48:39.687  3990  3990 V BluetoothAdapterState: isBleTurningOn()=false
07-27 11:48:39.687  3990  3990 V BluetoothAdapterState: isBleTurningOff()=false
07-27 11:48:39.687  3990  3990 V BluetoothAdapterState: isTurningOff()=false
07-27 11:48:39.687  3990  3990 V BluetoothAdapterState: isTurningOn()=true
07-27 11:48:39.687  3990  3990 V BluetoothAdapterState: isBleTurningOn()=false
,07-27 11:48:39.687  3990  3990 V BluetoothAdapterState: isBleTurningOff()=false
07-27 11:48:39.688  3990  4002 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-27 11:48:39.688  3990  4002 D BluetoothAdapterProperties: ScanMode =  20
07-27 11:48:39.688  3990  4002 D BluetoothAdapterProperties: State =  11
07-27 11:48:39.688  3990  4002 D BluetoothAdapterProperties: Setting state to 12
07-27 11:48:39.689  3990  4002 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-27 11:48:39.689  1372  1709 D BluetoothMap: onBluetoothStateChange: up=true
07-27 11:48:39.690  3990  4002 I BluetoothAdapterState: Entering OnState
07-27 11:48:39.692  3990  4006 D BluetoothAdapterProperties: Scan Mode:21
07-27 11:48:39.692  3990  4006 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 11:48:39.694   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
07-27 11:48:39.694  1372  1372 D BluetoothMap: Proxy object connected
,07-27 11:48:39.694  1372  1372 D MapProfile: Bluetooth service connected
07-27 11:48:39.694  1372  1372 D BluetoothMap: getConnectedDevices()
07-27 11:48:39.695   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 11:48:39.695  1372  1386 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 11:48:39.696   874   874 D BluetoothA2dp: Proxy object connected
07-27 11:48:39.696  1748  2144 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 11:48:39.697  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:48:39.697  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:39.697  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:39.697  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:48:39.697  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:48:39.697  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:48:39.697  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:48:39.697  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:48:39.697  1372  1392 D BluetoothPan: onBluetoothStateChange on: true
07-27 11:48:39.699  1372  1386 D BluetoothA2dp: onBluetoothStateChange: up=true
07-27 11:48:39.699  1372  1372 D BluetoothPan: BluetoothPAN Proxy object connected
07-27 11:48:39.699  1372  1372 D PanProfile: Bluetooth service connected
07-27 11:48:39.699  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:48:39.700  3990  3990 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-27 11:48:39.701  1372  1372 D BluetoothA2dp: Proxy object connected
07-27 11:48:39.701  3990  3990 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-27 11:48:39.703  3768  3778 D BluetoothPbap: onBluetoothStateChange: up=true
,07-27 11:48:39.704  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:48:39.704  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:39.704  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:39.704  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:48:39.704  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:48:39.704  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:48:39.704  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:48:39.704  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:48:39.704  1372  1709 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-27 11:48:39.706  3990  3990 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 11:48:39.707   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 11:48:39.707   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 11:48:39.707  1372  1372 D BluetoothInputDevice: Proxy object connected
07-27 11:48:39.707  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:48:39.707  1372  1372 D HidProfile: Bluetooth service connected
07-27 11:48:39.708  3768  3779 D BluetoothPan: onBluetoothStateChange on: true
07-27 11:48:39.708  1372  1392 D BluetoothPbap: onBluetoothStateChange: up=true
07-27 11:48:39.709  3990  3990 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 11:48:39.710  3768  3778 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-27 11:48:39.711  3768  3779 D BluetoothMap: onBluetoothStateChange: up=true
07-27 11:48:39.711  3990  3990 D ObexServerSockets: Succeed to create listening sockets 
,07-27 11:48:39.711  3990  3990 D ObexServerSockets0: startAccept()
07-27 11:48:39.711  3990  3990 D ObexServerSockets0: prepareForNewConnect()
,07-27 11:48:39.712   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,07-27 11:48:39.715  3990  3990 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,07-27 11:48:39.715  3990  3990 D BluetoothSdpJni: SDP Create record success - handle: 0
,07-27 11:48:39.716  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:48:39.716  3768  3768 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-27 11:48:39.717  3990  4029 D ObexServerSockets0: Accepting socket connection...
07-27 11:48:39.717  3990  4030 D ObexServerSockets0: Accepting socket connection...
07-27 11:48:39.718  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:48:39.718  3990  3990 D BluetoothMapService: onReceive
07-27 11:48:39.718  3990  3990 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:48:39.718  3990  3990 D BluetoothMapService: STATE_ON
,07-27 11:48:39.722  3768  3768 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-27 11:48:39.728  3768  3768 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-27 11:48:39.730  3768  3768 D BluetoothA2dp: Proxy object connected
,07-27 11:48:39.734  1525  1525 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-27 11:48:39.740  3768  3768 D DockEventReceiver: finishStartingService: stopping service
,07-27 11:48:39.743  3768  3768 D BluetoothPbap: Proxy object connected
,07-27 11:48:39.743  1372  1372 D BluetoothPbap: Proxy object connected
07-27 11:48:39.743  3768  3768 D PbapServerProfile: Bluetooth service connected
07-27 11:48:39.743  1372  1372 D PbapServerProfile: Bluetooth service connected
,07-27 11:48:39.748  3990  3990 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-27 11:48:39.748  3990  3990 D ObexServerSockets0: prepareForNewConnect()
,07-27 11:48:39.752  3990  4034 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 11:48:39.774  3990  4038 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 11:48:39.777  3990  4038 I BtOppRfcommListener: Accept thread started.
,07-27 11:48:39.797   874   874 D BluetoothHeadset: Proxy object connected
,07-27 11:48:39.798  1748  1760 D BluetoothHeadset: Proxy object connected
,07-27 11:48:39.799  1372  1386 D BluetoothHeadset: Proxy object connected
,07-27 11:48:39.799  1372  1372 D HeadsetProfile: Bluetooth service connected
07-27 11:48:39.799   874   874 D BluetoothHeadset: Proxy object connected
,07-27 11:48:39.800   874   874 D BluetoothHeadset: Proxy object connected
,07-27 11:48:39.808   874   891 D BluetoothHeadset: Proxy object connected
,07-27 11:48:39.808   874   891 D BluetoothHeadset: Proxy object connected
,07-27 11:48:39.825  3768  3778 D BluetoothHeadset: Proxy object connected
,07-27 11:48:39.826  3768  3768 D HeadsetProfile: Bluetooth service connected
,07-27 11:48:41.151  3990  4002 D BluetoothAdapterState: Current state: ON, message: 23
,07-27 11:48:41.152  3990  4002 D BluetoothAdapterProperties: Setting state to 13
07-27 11:48:41.152  3990  4002 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,07-27 11:48:41.154  3990  4002 D BluetoothAdapterProperties: onBluetoothDisable()
,07-27 11:48:41.165  3990  4002 I BluetoothAdapterState: Entering PendingCommandState,
07-27 11:48:41.168  3990  3990 D BluetoothMapService: onReceive
07-27 11:48:41.168  3990  3990 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,07-27 11:48:41.170  3990  3990 D BluetoothMapService: STATE_TURNING_OFF
,07-27 11:48:41.171  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:48:41.171  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:48:41.171  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:41.171  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:41.171  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:48:41.171  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:48:41.171  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:48:41.171  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:48:41.171  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:48:41.171  3990  3990 D BluetoothMapService: MAP Service closeService in
,07-27 11:48:41.172  3990  3990 D BluetoothMapMasInstance0: MAP Service shutdown
07-27 11:48:41.172  3990  3990 D ObexServerSockets0: shutdown(block = true)
07-27 11:48:41.173  3990  4029 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-27 11:48:41.174  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:48:41.174  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:48:41.177  3990  4006 D BluetoothAdapterProperties: Scan Mode:20
07-27 11:48:41.177  3990  4002 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,07-27 11:48:41.182  3990  3990 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-27 11:48:41.183  3990  4030 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-27 11:48:41.183  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:48:41.183  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:48:41.183  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:41.183  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:41.183  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:48:41.183  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:48:41.183  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:48:41.183  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:48:41.183  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:48:41.184  3702  3702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:48:41.184  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:48:41.184  3768  3768 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-27 11:48:41.185  3990  3990 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-27 11:48:41.185  3990  4017 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-27 11:48:41.185  3990  3990 I BtOppRfcommListener: stopping Accept Thread
07-27 11:48:41.186  3990  4038 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 11:48:41.186  3990  4038 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-27 11:48:41.187  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:48:41.189  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:48:41.195  3990  3990 D HeadsetService: Received stop request...Stopping profile...
,07-27 11:48:41.196   874   874 D BluetoothHeadset: Proxy object disconnected
07-27 11:48:41.197  1748  1761 D BluetoothHeadset: Proxy object disconnected
07-27 11:48:41.197  3990  3990 D A2dpService: Received stop request...Stopping profile...
07-27 11:48:41.197  3990  4023 D A2dpStateMachine: Exit Disconnected: -1
07-27 11:48:41.198  3768  3778 D BluetoothHeadset: Proxy object disconnected
07-27 11:48:41.199  1372  1372 D BluetoothA2dp: Proxy object disconnected
,07-27 11:48:41.199  1372  1709 D BluetoothHeadset: Proxy object disconnected
07-27 11:48:41.199  1372  1372 D HeadsetProfile: Bluetooth service disconnected
07-27 11:48:41.199   874   874 D BluetoothHeadset: Proxy object disconnected
07-27 11:48:41.199   874   874 D BluetoothHeadset: Proxy object disconnected
07-27 11:48:41.199  3990  3990 D HidService: Received stop request...Stopping profile...
07-27 11:48:41.199  3990  3990 D HidService: Stopping Bluetooth HidService
07-27 11:48:41.199   874   874 D BluetoothA2dp: Proxy object disconnected
,07-27 11:48:41.200  1372  1372 D BluetoothInputDevice: Proxy object disconnected
07-27 11:48:41.200  1372  1372 D HidProfile: Bluetooth service disconnected
,07-27 11:48:41.202  3990  3990 D HealthService: Received stop request...Stopping profile...
07-27 11:48:41.203  3768  3768 D DockEventReceiver: finishStartingService: stopping service
,07-27 11:48:41.205  3990  3990 D PanService: Received stop request...Stopping profile...
,07-27 11:48:41.207  1372  1372 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-27 11:48:41.207  1372  1372 D PanProfile: Bluetooth service disconnected
07-27 11:48:41.207  3990  3990 V BluetoothAdapterState: isTurningOff()=true
07-27 11:48:41.207  3990  3990 V BluetoothAdapterState: isTurningOn()=false
,07-27 11:48:41.207  3990  3990 V BluetoothAdapterState: isBleTurningOn()=false
07-27 11:48:41.207  3990  3990 V BluetoothAdapterState: isBleTurningOff()=false
07-27 11:48:41.208  1525  1525 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-27 11:48:41.209  3768  3768 D HeadsetProfile: Bluetooth service disconnected
07-27 11:48:41.209  3990  3990 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,07-27 11:48:41.209  3990  3990 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-27 11:48:41.210  3768  3768 D BluetoothA2dp: Proxy object disconnected
,07-27 11:48:41.210  3990  4006 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-27 11:48:41.210  3990  3990 D BluetoothMapService: Received stop request...Stopping profile...
07-27 11:48:41.210  3990  4014 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-27 11:48:41.211  3990  3990 D BluetoothMapService: stop()
,07-27 11:48:41.211  3990  4014 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-27 11:48:41.211  3990  4014 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-27 11:48:41.211  3990  4006 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
07-27 11:48:41.210  3768  3768 D BluetoothInputDevice: Proxy object disconnected
07-27 11:48:41.211  3990  3990 D BluetoothMapAppObserver: deinitObservers()
07-27 11:48:41.211  3990  3990 D BluetoothMapAppObserver: removeReceiver()
07-27 11:48:41.211  3768  3768 D HidProfile: Bluetooth service disconnected
,07-27 11:48:41.213  3990  3990 V BluetoothAdapterState: isTurningOff()=true
07-27 11:48:41.213  3990  3990 V BluetoothAdapterState: isTurningOn()=false
07-27 11:48:41.213  1372  1372 D BluetoothMap: Proxy object disconnected
07-27 11:48:41.213  3990  3990 V BluetoothAdapterState: isBleTurningOn()=false
07-27 11:48:41.213  1372  1372 D MapProfile: Bluetooth service disconnected
,07-27 11:48:41.213  3990  3990 V BluetoothAdapterState: isBleTurningOff()=false
07-27 11:48:41.213  3990  3990 V BluetoothAdapterState: isTurningOff()=true
,07-27 11:48:41.213  3990  3990 V BluetoothAdapterState: isTurningOn()=false
07-27 11:48:41.214  3990  3990 V BluetoothAdapterState: isBleTurningOn()=false
07-27 11:48:41.214  3990  3990 V BluetoothAdapterState: isBleTurningOff()=false
07-27 11:48:41.215  3768  3768 D BluetoothPan: BluetoothPAN Proxy object disconnected
,07-27 11:48:41.215  3990  4006 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,07-27 11:48:41.215  3990  4014 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-27 11:48:41.216  3990  4014 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-27 11:48:41.216  3990  3990 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-27 11:48:41.216  3990  4014 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 11:48:41.216  3990  3990 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-27 11:48:41.216  3990  4006 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-27 11:48:41.216  3990  4014 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 11:48:41.216  3990  4014 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 11:48:41.216  3990  4014 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 11:48:41.215  3768  3768 D PanProfile: Bluetooth service disconnected
07-27 11:48:41.216  3990  3990 V BluetoothAdapterState: isTurningOff()=true
07-27 11:48:41.216  3990  3990 V BluetoothAdapterState: isTurningOn()=false
,07-27 11:48:41.216  3990  3990 V BluetoothAdapterState: isBleTurningOn()=false
07-27 11:48:41.217  3990  3990 V BluetoothAdapterState: isBleTurningOff()=false
07-27 11:48:41.217  3990  3990 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-27 11:48:41.217  3990  4006 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,07-27 11:48:41.217  3990  3990 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-27 11:48:41.217  3768  3768 D BluetoothMap: Proxy object disconnected
07-27 11:48:41.218  3768  3768 D MapProfile: Bluetooth service disconnected
07-27 11:48:41.219  1372  1372 D BluetoothPbap: Proxy object disconnected
07-27 11:48:41.219  1372  1372 D PbapServerProfile: Bluetooth service disconnected
07-27 11:48:41.220  3768  3768 D BluetoothPbap: Proxy object disconnected
07-27 11:48:41.220  3990  3990 V BluetoothAdapterState: isTurningOff()=true
,07-27 11:48:41.220  3990  3990 V BluetoothAdapterState: isTurningOn()=false
07-27 11:48:41.220  3990  3990 V BluetoothAdapterState: isBleTurningOn()=false
07-27 11:48:41.220  3990  3990 V BluetoothAdapterState: isBleTurningOff()=false
07-27 11:48:41.220  3768  3768 D PbapServerProfile: Bluetooth service disconnected
07-27 11:48:41.221  3990  3990 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,07-27 11:48:41.221  3990  3990 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,07-27 11:48:41.223  3990  3990 D BluetoothMapService: MAP Service closeService in
,07-27 11:48:41.224  3990  3990 V BluetoothAdapterState: isTurningOff()=true
07-27 11:48:41.224  3990  3990 V BluetoothAdapterState: isTurningOn()=false
07-27 11:48:41.224  3990  3990 V BluetoothAdapterState: isBleTurningOn()=false
07-27 11:48:41.224  3990  3990 V BluetoothAdapterState: isBleTurningOff()=false
07-27 11:48:41.224  3990  4002 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-27 11:48:41.224  3990  4002 D BluetoothAdapterProperties: Setting state to 15
,07-27 11:48:41.224  3990  4002 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-27 11:48:41.225  3990  3990 D BluetoothMapService: cleanup()
07-27 11:48:41.225  3990  3990 D BluetoothMapService: MAP Service closeService in
07-27 11:48:41.225  1372  1392 D BluetoothMap: onBluetoothStateChange: up=false
07-27 11:48:41.226  3990  4002 I BluetoothAdapterState: Entering BleOnState
,07-27 11:48:41.228   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
07-27 11:48:41.229  3768  3778 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-27 11:48:41.230   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-27 11:48:41.230  1372  1709 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-27 11:48:41.231  1748  1890 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 11:48:41.231  1372  1386 D BluetoothPan: onBluetoothStateChange on: false
,07-27 11:48:41.232  1372  1392 D BluetoothA2dp: onBluetoothStateChange: up=false
07-27 11:48:41.232  3768  3779 D BluetoothPbap: onBluetoothStateChange: up=false
,07-27 11:48:41.233  1372  1709 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-27 11:48:41.233   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 11:48:41.233   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 11:48:41.234  3768  3778 D BluetoothPan: onBluetoothStateChange on: false
,07-27 11:48:41.234  1372  1386 D BluetoothPbap: onBluetoothStateChange: up=false
,07-27 11:48:41.235  3768  3779 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-27 11:48:41.235  3768  3778 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-27 11:48:41.236  3768  3779 D BluetoothMap: onBluetoothStateChange: up=false
,07-27 11:48:41.237  3990  4002 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-27 11:48:41.237  3990  4002 D BluetoothAdapterProperties: Setting state to 16
07-27 11:48:41.237  3990  4002 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,07-27 11:48:41.238  3990  4002 D BluetoothAdapterProperties: onBleDisable
07-27 11:48:41.238  3990  4002 I BluetoothAdapterState: Entering PendingCommandState
07-27 11:48:41.238  3990  4003 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-27 11:48:41.240  3990  4014 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-27 11:48:41.240  3990  4014 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-27 11:48:41.241  3990  4006 D BluetoothAdapterProperties: Scan Mode:20
,07-27 11:48:41.241  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:48:41.242  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:48:41.244  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:48:41.245  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:48:41.245  3768  3768 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-27 11:48:41.249  1525  1525 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-27 11:48:41.251  3768  3768 D DockEventReceiver: finishStartingService: stopping service
,07-27 11:48:41.440  3990  4006 I bt_hci  : shut_down
,07-27 11:48:41.457  3990  4010 I bt_vendor: low_power_mode_cb,
,07-27 11:48:41.462  3990  4010 D bt_hwcfg: hw_epilog_process
,07-27 11:48:41.480  3990  4010 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-27 11:48:41.481  3990  4010 I bt_vendor: epilog_cb
07-27 11:48:41.481  3990  4010 I bt_hci  : epilog_finished_callback
,07-27 11:48:41.488  3990  4006 I bt_hci_h4: hal_close
,07-27 11:48:41.490  3990  4006 I bt_userial_vendor: device fd = 51 close
,07-27 11:48:41.610  3990  4003 D bt_stack_manager: event_shut_down_stack finished.
,07-27 11:48:41.611  3990  4002 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,07-27 11:48:41.617  3990  3990 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-27 11:48:41.617  3990  4002 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-27 11:48:41.619  3990  3990 D BtGatt.GattService: Received stop request...Stopping profile...
,07-27 11:48:41.619  3990  3990 D BtGatt.GattService: stop()
07-27 11:48:41.620  3990  3990 D BtGatt.AdvertiseManager: advertise clients cleared
,07-27 11:48:41.624  3990  3990 V BluetoothAdapterState: isTurningOff()=false
07-27 11:48:41.625  3990  3990 V BluetoothAdapterState: isTurningOn()=false,
07-27 11:48:41.625  3990  3990 V BluetoothAdapterState: isBleTurningOn()=false
07-27 11:48:41.626  3990  3990 V BluetoothAdapterState: isBleTurningOff()=true
,07-27 11:48:41.626  3990  4002 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,07-27 11:48:41.627  3990  4002 D BluetoothAdapterProperties: Setting state to 10
,07-27 11:48:41.627  3990  4002 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-27 11:48:41.629  3990  4002 I BluetoothAdapterState: Entering OffState
,07-27 11:48:41.632   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,07-27 11:48:41.654  3990  3990 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-27 11:48:41.655  3990  3990 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,07-27 11:48:41.655  3990  4003 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,07-27 11:48:41.660  3990  3990 I BluetoothServiceJni: cleanupNative: return from cleanup
,07-27 11:48:41.666  3990  4003 D bt_stack_manager: event_clean_up_stack finished.
,07-27 11:48:41.671  3990  3990 I art     : System.exit called, status: 0
,07-27 11:48:41.671  3990  3990 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-27 11:48:41.722   874  1703 I ActivityManager: Process com.android.bluetooth (pid 3990) has died
,07-27 11:48:42.446   874  1320 D ConnectivityService: handlePromptUnvalidated 101
,07-27 11:48:42.839  3012  3012 I NewsWeather: Last usage 0, idle 1469612922 seconds, sync interval 2160000 seconds
,07-27 11:48:42.840  3012  3012 I NewsWeather: Last usage 0, idle 1469612922 seconds, sync interval 2160000 seconds
07-27 11:48:42.840  3012  3012 I NewsWeather: setPeriodicSync in 2160000 seconds
,07-27 11:48:42.888  3012  3012 I NewsWeather: Last usage 1447148544093, idle 22464378 seconds, sync interval 2160000 seconds
,07-27 11:48:42.888  3012  3012 I NewsWeather: Last usage 1447148544093, idle 22464378 seconds, sync interval 2160000 seconds
07-27 11:48:42.889  3012  3012 I NewsWeather: setPeriodicSync in 2160000 seconds
,07-27 11:48:44.149  3702  3748 D io.jxcore.node.ConnectivityMonitor: stop
,07-27 11:48:44.150  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 11:48:47.158  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-27 11:48:47.158  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e2995fd added. We now have 6 listener(s)
,07-27 11:48:47.159  3702  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 11:48:47.165  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-27 11:48:47.166  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@21622f2 added. We now have 7 listener(s)
07-27 11:48:47.166  3702  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:48:47.168  3702  3748 I System.out: IsBluetoothEnabled
,07-27 11:48:47.180  3702  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:48:47.215   874   891 I ActivityManager: Start proc 4049:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-27 11:48:47.332  4049  4049 D AdapterServiceConfig: Adding HeadsetService
,07-27 11:48:47.333  4049  4049 D AdapterServiceConfig: Adding A2dpService
,07-27 11:48:47.333  4049  4049 D AdapterServiceConfig: Adding HidService
07-27 11:48:47.333  4049  4049 D AdapterServiceConfig: Adding HealthService
07-27 11:48:47.333  4049  4049 D AdapterServiceConfig: Adding PanService
07-27 11:48:47.333  4049  4049 D AdapterServiceConfig: Adding GattService
07-27 11:48:47.333  4049  4049 D AdapterServiceConfig: Adding BluetoothMapService
,07-27 11:48:47.346   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ca82208:true
,07-27 11:48:47.347  4049  4049 D BluetoothAdapterState: make() - Creating AdapterState
,07-27 11:48:47.353  4049  4049 I bt_bluedroid: init
,07-27 11:48:47.354  4049  4061 I BluetoothAdapterState: Entering OffState
,07-27 11:48:47.355  4049  4062 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-27 11:48:47.356  4049  4062 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-27 11:48:47.356  4049  4062 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,07-27 11:48:47.356  4049  4062 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-27 11:48:47.356  4049  4049 I bt_bluedroid: get_profile_interface socket
,07-27 11:48:47.357  4049  4049 I bt_bluedroid: get_profile_interface sdp
,07-27 11:48:47.362  4049  4060 I bt_bluedroid: config_hci_snoop_log
07-27 11:48:47.363   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
07-27 11:48:47.363  4049  4065 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-27 11:48:47.374  4049  4065 D BluetoothAdapterProperties: Name is: Nexus 6
,07-27 11:48:47.376  4049  4061 D BluetoothAdapterState: Current state: OFF, message: 0
,07-27 11:48:47.377  4049  4061 D BluetoothAdapterProperties: Setting state to 14
,07-27 11:48:47.377  4049  4061 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-27 11:48:47.378  4049  4061 D BluetoothBondStateMachine: make
,07-27 11:48:47.381  4049  4066 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-27 11:48:47.384  4049  4049 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-27 11:48:47.385  4049  4061 I BluetoothAdapterState: Entering PendingCommandState
,07-27 11:48:47.386  4049  4049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@670d5c3
,07-27 11:48:47.387  4049  4049 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-27 11:48:47.387  4049  4049 D BtGatt.GattService: Received start request. Starting profile...
,07-27 11:48:47.388  4049  4049 D BtGatt.GattService: start()
07-27 11:48:47.388  4049  4049 I bt_bluedroid: get_profile_interface gatt
,07-27 11:48:47.388  4049  4049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@670d5c3
07-27 11:48:47.389  4049  4049 D BtGatt.AdvertiseManager: advertise manager created
,07-27 11:48:47.394  4049  4049 V BluetoothAdapterState: isTurningOff()=false
07-27 11:48:47.394  4049  4049 V BluetoothAdapterState: isTurningOn()=false
,07-27 11:48:47.394  4049  4049 V BluetoothAdapterState: isBleTurningOn()=true
07-27 11:48:47.394  4049  4049 V BluetoothAdapterState: isBleTurningOff()=false
07-27 11:48:47.394  4049  4061 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,07-27 11:48:47.395  4049  4061 I bt_bluedroid: enable
07-27 11:48:47.395  4049  4062 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-27 11:48:47.395  4049  4062 I bt_hci  : start_up
,07-27 11:48:47.400  4049  4062 I bt_vendor: alloc value 0xb39a0189
,07-27 11:48:47.400  4049  4062 I bt_vendor: init
07-27 11:48:47.400  4049  4062 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-27 11:48:47.400  4049  4062 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-27 11:48:47.507  4049  4062 D bt_hci  : start_up starting async portion
,07-27 11:48:47.508  4049  4069 I bt_hci  : event_finish_startup
,07-27 11:48:47.508  4049  4069 I bt_hci_h4: hal_open
,07-27 11:48:47.509  4049  4069 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-27 11:48:47.518  4049  4069 I bt_userial_vendor: device fd = 51 open
,07-27 11:48:47.549  4049  4069 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-27 11:48:47.581  4049  4069 D bt_hwcfg: Chipset BCM4354A2
,07-27 11:48:47.581  4049  4069 D bt_hwcfg: Target name = [BCM4354A2]
07-27 11:48:47.582  4049  4069 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,07-27 11:48:48.237  4049  4069 I bt_hwcfg: bt vendor lib: set UART baud 115200,
07-27 11:48:48.239  4049  4069 D bt_hwcfg: Settlement delay -- 100 ms
07-27 11:48:48.239  4049  4069 I bt_hwcfg: Setting fw settlement delay to 100 
,07-27 11:48:48.356  4049  4069 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-27 11:48:48.357  4049  4069 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,07-27 11:48:48.390  4049  4069 I bt_hwcfg: vendor lib fwcfg completed
,07-27 11:48:48.391  4049  4069 I bt_vendor: firmware callback,
07-27 11:48:48.391  4049  4069 I bt_hci  : firmware_config_callback
,07-27 11:48:48.402  4049  4071 I bt_btu  : btu_task pending for preload complete event
,07-27 11:48:48.402  4049  4071 I bt_btu_task: Bluetooth chip preload is complete
07-27 11:48:48.402  4049  4071 I bt_btu  : btu_task received preload complete event
,07-27 11:48:48.405  3012  3012 I NewsWeather: Last usage 0, idle 1469612928 seconds, sync interval 2160000 seconds
,07-27 11:48:48.405  3012  3012 I NewsWeather: Last usage 0, idle 1469612928 seconds, sync interval 2160000 seconds
07-27 11:48:48.405  3012  3012 I NewsWeather: setPeriodicSync in 2160000 seconds
,07-27 11:48:48.412  4049  4071 I         : BTE_InitTraceLevels -- TRC_HCI
07-27 11:48:48.413  4049  4071 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-27 11:48:48.413  4049  4071 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-27 11:48:48.413  4049  4071 I         : BTE_InitTraceLevels -- TRC_AVDT
07-27 11:48:48.413  4049  4071 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-27 11:48:48.413  4049  4071 I         : BTE_InitTraceLevels -- TRC_A2D
,07-27 11:48:48.414  4049  4071 I         : BTE_InitTraceLevels -- TRC_BNEP
07-27 11:48:48.414  4049  4071 I         : BTE_InitTraceLevels -- TRC_BTM
,07-27 11:48:48.414  4049  4071 I         : BTE_InitTraceLevels -- TRC_GAP
07-27 11:48:48.414  4049  4071 I         : BTE_InitTraceLevels -- TRC_PAN
07-27 11:48:48.415  4049  4071 I         : BTE_InitTraceLevels -- TRC_SDP
,07-27 11:48:48.415  4049  4071 I         : BTE_InitTraceLevels -- TRC_GATT
,07-27 11:48:48.415  4049  4071 I         : BTE_InitTraceLevels -- TRC_SMP
,07-27 11:48:48.415  4049  4071 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-27 11:48:48.415  4049  4071 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-27 11:48:48.430  3012  3012 I NewsWeather: Last usage 1447148544093, idle 22464384 seconds, sync interval 2160000 seconds
,07-27 11:48:48.431  3012  3012 I NewsWeather: Last usage 1447148544093, idle 22464384 seconds, sync interval 2160000 seconds
,07-27 11:48:48.431  3012  3012 I NewsWeather: setPeriodicSync in 2160000 seconds
,07-27 11:48:48.546  4049  4071 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb391dd9d
,07-27 11:48:48.546  4049  4071 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb391dd9d 
,07-27 11:48:48.560  4049  4065 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,07-27 11:48:48.561  4049  4065 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-27 11:48:48.562  4049  4065 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-27 11:48:48.565  4049  4065 D BluetoothAdapterProperties: Name is: Nexus 6
,07-27 11:48:48.569  4049  4065 D BluetoothAdapterProperties: Scan Mode:20
07-27 11:48:48.569  4049  4065 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 11:48:48.570  4049  4065 D bt_hci  : do_postload posting postload work item
07-27 11:48:48.571  4049  4069 I bt_hci  : event_postload
07-27 11:48:48.571  4049  4069 I bt_vendor: sco_config_cb
07-27 11:48:48.571  4049  4069 I bt_hci  : sco_config_callback postload finished.
,07-27 11:48:48.575  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,07-27 11:48:48.578  4049  4065 D bt_bte_conf: Device ID record 1 : primary
07-27 11:48:48.578  4049  4065 D bt_bte_conf:   vendorId            = 000f
07-27 11:48:48.578  4049  4065 D bt_bte_conf:   vendorIdSource      = 0001
07-27 11:48:48.579  4049  4065 D bt_bte_conf:   product             = 1200
07-27 11:48:48.579  4049  4065 D bt_bte_conf:   version             = 1436
07-27 11:48:48.579  4049  4065 D bt_bte_conf:   clientExecutableURL = 
07-27 11:48:48.580  4049  4065 D bt_bte_conf:   serviceDescription  = 
07-27 11:48:48.580  4049  4065 D bt_bte_conf:   documentationURL    = 
07-27 11:48:48.580  4049  4065 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-27 11:48:48.581  4049  4062 D bt_stack_manager: event_start_up_stack finished
07-27 11:48:48.584  4049  4069 I bt_vendor: low_power_mode_cb
07-27 11:48:48.584  4049  4061 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-27 11:48:48.586  4049  4061 D BluetoothAdapterProperties: Setting state to 15
07-27 11:48:48.586  4049  4061 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-27 11:48:48.587  4049  4061 I BluetoothAdapterState: Entering BleOnState
,07-27 11:48:48.592  4049  4061 D BluetoothAdapterState: Current state: BLE ON, message: 1
,07-27 11:48:48.592  4049  4061 D BluetoothAdapterProperties: Setting state to 11
,07-27 11:48:48.592  4049  4061 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,07-27 11:48:48.600  4049  4049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@670d5c3
,07-27 11:48:48.607  4049  4049 D HeadsetService: Received start request. Starting profile...
,07-27 11:48:48.607  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:48:48.613  4049  4049 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-27 11:48:48.614  4049  4049 D HeadsetStateMachine: make
,07-27 11:48:48.627  4049  4061 I BluetoothAdapterState: Entering PendingCommandState
,07-27 11:48:48.627  4049  4049 D HeadsetStateMachine: max_hf_connections = 1
,07-27 11:48:48.627  4049  4049 I bt_bluedroid: get_profile_interface handsfree
,07-27 11:48:48.629  4049  4065 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,07-27 11:48:48.629  4049  4065 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,07-27 11:48:48.635  4049  4049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@670d5c3
,07-27 11:48:48.636  4049  4049 D A2dpService: Received start request. Starting profile...
,07-27 11:48:48.637  4049  4049 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-27 11:48:48.637  4049  4049 I bt_bluedroid: get_profile_interface avrcp
,07-27 11:48:48.651  4049  4049 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-27 11:48:48.652  4049  4049 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-27 11:48:48.652  4049  4049 D A2dpStateMachine: make
,07-27 11:48:48.654  4049  4049 I bt_bluedroid: get_profile_interface a2dp
,07-27 11:48:48.656  4049  4065 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,07-27 11:48:48.660  4049  4080 D A2dpStateMachine: Enter Disconnected: -2
,07-27 11:48:48.662  4049  4049 I BluetoothHidServiceJni: classInitNative: succeeds
,07-27 11:48:48.664  4049  4049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@670d5c3
,07-27 11:48:48.666  4049  4049 D HidService: Received start request. Starting profile...
,07-27 11:48:48.666  4049  4049 I bt_bluedroid: get_profile_interface hidhost
07-27 11:48:48.666  4049  4065 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38ff3e5
,07-27 11:48:48.666  4049  4065 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-27 11:48:48.666  4049  4049 D HidService: setHidService(): set to: null
,07-27 11:48:48.668  4049  4049 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-27 11:48:48.669  4049  4049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@670d5c3
07-27 11:48:48.669  4049  4049 D HealthService: Received start request. Starting profile...
07-27 11:48:48.670  1525  1525 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-27 11:48:48.671  4049  4049 I bt_bluedroid: get_profile_interface health
07-27 11:48:48.673  4049  4049 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-27 11:48:48.674  4049  4049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@670d5c3
,07-27 11:48:48.674  4049  4049 D PanService: Received start request. Starting profile...
,07-27 11:48:48.675  4049  4049 D BluetoothPanServiceJni: initializeNative(L110): pan
07-27 11:48:48.675  4049  4049 I bt_bluedroid: get_profile_interface pan
07-27 11:48:48.675  4049  4065 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-27 11:48:48.678  4049  4049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@670d5c3
,07-27 11:48:48.678  4049  4049 D BluetoothMapService: Received start request. Starting profile...
,07-27 11:48:48.679  4049  4049 D BluetoothMapService: start()
,07-27 11:48:48.681  4049  4049 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER,
,07-27 11:48:48.682  4049  4049 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-27 11:48:48.682  4049  4049 D BluetoothMapAppObserver: createReceiver(),
07-27 11:48:48.684  4049  4049 D BluetoothMapAppObserver: initObservers(),
07-27 11:48:48.684  4049  4049 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-27 11:48:48.692  4049  4078 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-27 11:48:48.692  4049  4049 V BluetoothAdapterState: isTurningOff()=false
,07-27 11:48:48.692  4049  4049 V BluetoothAdapterState: isTurningOn()=true
,07-27 11:48:48.692  4049  4049 V BluetoothAdapterState: isBleTurningOn()=false
,07-27 11:48:48.692  4049  4049 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 11:48:48.694  4049  4049 V BluetoothAdapterState: isTurningOff()=false
07-27 11:48:48.694  4049  4049 V BluetoothAdapterState: isTurningOn()=true
07-27 11:48:48.694  4049  4049 V BluetoothAdapterState: isBleTurningOn()=false,
07-27 11:48:48.694  4049  4049 V BluetoothAdapterState: isBleTurningOff()=false
07-27 11:48:48.695  4049  4049 V BluetoothAdapterState: isTurningOff()=false
07-27 11:48:48.695  4049  4049 V BluetoothAdapterState: isTurningOn()=true
,07-27 11:48:48.695  4049  4049 V BluetoothAdapterState: isBleTurningOn()=false
07-27 11:48:48.695  4049  4049 V BluetoothAdapterState: isBleTurningOff()=false
07-27 11:48:48.695  4049  4049 V BluetoothAdapterState: isTurningOff()=false
07-27 11:48:48.695  4049  4049 V BluetoothAdapterState: isTurningOn()=true,
07-27 11:48:48.695  4049  4049 V BluetoothAdapterState: isBleTurningOn()=false
,07-27 11:48:48.695  4049  4049 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 11:48:48.696  4049  4049 V BluetoothAdapterState: isTurningOff()=false
07-27 11:48:48.696  4049  4049 V BluetoothAdapterState: isTurningOn()=true
07-27 11:48:48.696  4049  4049 V BluetoothAdapterState: isBleTurningOn()=false
07-27 11:48:48.696  4049  4049 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 11:48:48.696  4049  4049 V BluetoothAdapterState: isTurningOff()=false
07-27 11:48:48.696  4049  4049 V BluetoothAdapterState: isTurningOn()=true
,07-27 11:48:48.697  4049  4049 V BluetoothAdapterState: isBleTurningOn()=false
07-27 11:48:48.697  4049  4049 V BluetoothAdapterState: isBleTurningOff()=false
07-27 11:48:48.697  4049  4061 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-27 11:48:48.697  4049  4061 D BluetoothAdapterProperties: ScanMode =  20
07-27 11:48:48.697  4049  4061 D BluetoothAdapterProperties: State =  11
,07-27 11:48:48.700  4049  4065 D BluetoothAdapterProperties: Scan Mode:21
07-27 11:48:48.700  4049  4065 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-27 11:48:48.701  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:48:48.700  4049  4061 D BluetoothAdapterProperties: Setting state to 12
07-27 11:48:48.702  4049  4061 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-27 11:48:48.702  4049  4061 I BluetoothAdapterState: Entering OnState
,07-27 11:48:48.704  1372  1386 D BluetoothMap: onBluetoothStateChange: up=true
,07-27 11:48:48.706   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-27 11:48:48.707  3768  3779 D BluetoothA2dp: onBluetoothStateChange: up=true
07-27 11:48:48.707  1372  1372 D BluetoothMap: Proxy object connected
,07-27 11:48:48.707  1372  1372 D MapProfile: Bluetooth service connected
07-27 11:48:48.707  1372  1372 D BluetoothMap: getConnectedDevices()
,07-27 11:48:48.708   874   874 D BluetoothA2dp: Proxy object connected
07-27 11:48:48.709   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 11:48:48.709  1372  1709 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-27 11:48:48.711  4049  4049 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-27 11:48:48.711  1748  1760 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-27 11:48:48.711  4049  4049 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,07-27 11:48:48.712  1372  1386 D BluetoothPan: onBluetoothStateChange on: true
07-27 11:48:48.710  3768  3768 D BluetoothA2dp: Proxy object connected
07-27 11:48:48.713  4049  4049 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 11:48:48.716  4049  4049 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 11:48:48.716  1372  1392 D BluetoothA2dp: onBluetoothStateChange: up=true
07-27 11:48:48.717  4049  4049 D ObexServerSockets: Succeed to create listening sockets 
,07-27 11:48:48.717  4049  4049 D ObexServerSockets0: startAccept()
07-27 11:48:48.717  4049  4049 D ObexServerSockets0: prepareForNewConnect()
,07-27 11:48:48.719  1372  1372 D BluetoothA2dp: Proxy object connected
,07-27 11:48:48.719  3768  3779 D BluetoothPbap: onBluetoothStateChange: up=true
,07-27 11:48:48.720  4049  4049 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,07-27 11:48:48.720  4049  4049 D BluetoothSdpJni: SDP Create record success - handle: 0
,07-27 11:48:48.722  4049  4086 D ObexServerSockets0: Accepting socket connection...
07-27 11:48:48.722  4049  4087 D ObexServerSockets0: Accepting socket connection...
,07-27 11:48:48.723  1372  1372 D BluetoothPan: BluetoothPAN Proxy object connected
07-27 11:48:48.723  1372  1372 D PanProfile: Bluetooth service connected
07-27 11:48:48.724  1372  1392 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-27 11:48:48.726   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-27 11:48:48.726   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-27 11:48:48.727  1372  1372 D BluetoothInputDevice: Proxy object connected
,07-27 11:48:48.727  1372  1372 D HidProfile: Bluetooth service connected
07-27 11:48:48.727  3768  3778 D BluetoothPan: onBluetoothStateChange on: true
,07-27 11:48:48.730  3768  3768 D BluetoothPan: BluetoothPAN Proxy object connected
,07-27 11:48:48.730  3768  3768 D PanProfile: Bluetooth service connected
,07-27 11:48:48.730  1372  1386 D BluetoothPbap: onBluetoothStateChange: up=true
,07-27 11:48:48.732  3768  3779 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-27 11:48:48.733  3768  4085 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-27 11:48:48.734  3768  3779 D BluetoothMap: onBluetoothStateChange: up=true
,07-27 11:48:48.734  3768  3768 D BluetoothInputDevice: Proxy object connected
07-27 11:48:48.734  3768  3768 D HidProfile: Bluetooth service connected
,07-27 11:48:48.736  3768  3768 D BluetoothMap: Proxy object connected
,07-27 11:48:48.736  3768  3768 D MapProfile: Bluetooth service connected
07-27 11:48:48.736   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,07-27 11:48:48.737  4049  4049 D BluetoothMapService: onReceive
07-27 11:48:48.737  4049  4049 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,07-27 11:48:48.737  4049  4049 D BluetoothMapService: STATE_ON
07-27 11:48:48.736  3768  3768 D BluetoothMap: getConnectedDevices()
,07-27 11:48:48.741  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:48:48.741  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:48.741  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:48.741  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:48:48.741  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:48:48.741  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:48:48.741  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:48:48.741  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:48:48.743  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:48:48.745  3768  3768 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-27 11:48:48.751  1525  1525 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-27 11:48:48.752  3768  3768 D DockEventReceiver: finishStartingService: stopping service
,07-27 11:48:48.763  1372  1372 D BluetoothPbap: Proxy object connected
,07-27 11:48:48.763  3768  3768 D BluetoothPbap: Proxy object connected
07-27 11:48:48.763  1372  1372 D PbapServerProfile: Bluetooth service connected
07-27 11:48:48.763  3768  3768 D PbapServerProfile: Bluetooth service connected
,07-27 11:48:48.768  4049  4049 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-27 11:48:48.769  4049  4049 D ObexServerSockets0: prepareForNewConnect()
07-27 11:48:48.772  4049  4092 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 11:48:48.791  4049  4096 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 11:48:48.793  4049  4096 I BtOppRfcommListener: Accept thread started.
,07-27 11:48:48.813   874   874 D BluetoothHeadset: Proxy object connected
,07-27 11:48:48.813  1748  1761 D BluetoothHeadset: Proxy object connected
07-27 11:48:48.813  1748  1890 D BluetoothHeadset: Proxy object connected
07-27 11:48:48.814  3768  3779 D BluetoothHeadset: Proxy object connected
,07-27 11:48:48.815  1372  1392 D BluetoothHeadset: Proxy object connected
,07-27 11:48:48.816  1372  1372 D HeadsetProfile: Bluetooth service connected
07-27 11:48:48.816   874   874 D BluetoothHeadset: Proxy object connected
,07-27 11:48:48.816   874   874 D BluetoothHeadset: Proxy object connected
,07-27 11:48:48.826   874   891 D BluetoothHeadset: Proxy object connected
,07-27 11:48:48.827  3768  3768 D HeadsetProfile: Bluetooth service connected
,07-27 11:48:48.827   874   891 D BluetoothHeadset: Proxy object connected
,07-27 11:48:48.832  3768  3778 D BluetoothHeadset: Proxy object connected
,07-27 11:48:48.833  3768  3768 D HeadsetProfile: Bluetooth service connected
,07-27 11:48:49.203  3702  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:48:49.203  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:49.203  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:49.203  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:48:49.203  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:48:49.203  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:48:49.203  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:48:49.203  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:48:49.209  3702  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:48:49.214  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-27 11:48:49.214  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b3ecd43 added. We now have 8 listener(s)
,07-27 11:48:49.215  3702  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 11:48:49.221   874  2996 D WifiService: setWifiEnabled: false pid=3702, uid=10000
,07-27 11:48:49.221   874  2996 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-27 11:48:49.234  3702  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:48:49.235   874  1759 D WifiService: setWifiEnabled: true pid=3702, uid=10000
07-27 11:48:49.235   874  1759 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-27 11:48:49.248   874  1317 D WifiConfigStore: Loading config and enabling all networks 
,07-27 11:48:49.268  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:48:49.268  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:49.268  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:49.268  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:48:49.268  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:48:49.268  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:48:49.268  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:48:49.268  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:48:49.274  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:48:49.283   874  1317 D WifiConfigStore: loaded 0 passpoint configs
07-27 11:48:49.283   874  1317 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-27 11:48:49.283   874  1317 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
07-27 11:48:49.284   874  1317 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-27 11:48:49.285   874  1317 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-27 11:48:49.286   874  1317 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,07-27 11:48:49.286   874  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
07-27 11:48:49.286   874  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-27 11:48:49.303   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,07-27 11:48:49.304   874  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-27 11:48:49.305   372   872 D CommandListener: Setting iface cfg
,07-27 11:48:49.356   874  1316 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
07-27 11:48:49.357   874  1316 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-27 11:48:49.359   874  1317 E native  : do suspend true
,07-27 11:48:49.383   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,07-27 11:48:49.384   874  1316 D WifiNative-HAL: p2pGetDeviceAddress
,07-27 11:48:49.387   874  1316 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,07-27 11:48:50.259  3702  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:48:50.259  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:50.259  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:50.259  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:48:50.259  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:48:50.259  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:48:50.259  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:48:50.259  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:48:50.266  3702  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:48:50.279  3702  3748 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-27 11:48:50.281  3702  3748 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-27 11:48:50.287  3702  3748 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a810b1f Bundle[{}]
,07-27 11:48:50.289  3702  3748 I io.jxcore.node.LifeCycleMonitor: start: OK,
07-27 11:48:50.290  3702  3748 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-27 11:48:50.293  3702  3748 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-27 11:48:50.293  3702  3748 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-27 11:48:50.294  3702  3748 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-27 11:48:50.295  3702  3748 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-27 11:48:50.300  3702  3748 I System.out: Running OutgoingSocketThread
07-27 11:48:50.304  3702  4102 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 424)
07-27 11:48:50.306  3702  4102 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 38883
07-27 11:48:50.307  3702  4102 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,07-27 11:48:50.665   874  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-27 11:48:50.804   874  1317 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.94 rxSuccessRate=10.62 delta 1000 -> 994
,07-27 11:48:50.807   874  1317 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
07-27 11:48:50.807   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 11:48:50.821   874  1317 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,07-27 11:48:50.872   874  1317 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,07-27 11:48:50.877  1468  1468 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-27 11:48:51.304  3702  3748 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 425)
,07-27 11:48:51.304  3702  3748 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 425)
07-27 11:48:51.305  3702  3748 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 425)
07-27 11:48:51.306  3702  3748 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 425)
,07-27 11:48:51.311  1468  1468 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-27 11:48:51.315  3702  3748 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 430)
,07-27 11:48:51.316  3702  3748 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 430)
,07-27 11:48:51.316  3702  3748 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 430)
,07-27 11:48:51.320  3702  3748 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 431)
,07-27 11:48:51.321  3702  3748 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 433)
,07-27 11:48:51.324  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-27 11:48:51.324  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@119ffc0 added. We now have 2 listener(s)
07-27 11:48:51.326  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-27 11:48:51.326  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:48:51.327  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-27 11:48:51.327  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:48:51.327  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27e94f9 added. We now have 9 listener(s)
07-27 11:48:51.327  3702  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:48:51.327  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-27 11:48:51.331  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:48:51.337  3702  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:48:51.337  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:51.337  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:51.337  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:48:51.337  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:48:51.337  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:48:51.337  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:48:51.337  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:48:51.339  3702  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:48:51.340  3702  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:48:51.340  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:48:51.340  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f6fa9f added. We now have 3 listener(s)
07-27 11:48:51.341  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:48:51.343  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:48:51.346  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-27 11:48:51.346  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:48:51.346  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:48:51.347  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-27 11:48:51.347  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f57ec added. We now have 10 listener(s)
07-27 11:48:51.347  3702  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:48:51.347  3702  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-27 11:48:51.348  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:48:51.348  3702  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:48:51.348  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-27 11:48:51.350  1468  1468 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-27 11:48:51.350  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,07-27 11:48:51.348  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:51.353  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:48:51.354  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:48:51.354  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@119ffc0 removed from the list
,07-27 11:48:51.354  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:51.355   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
07-27 11:48:51.354  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27e94f9 removed from the list
07-27 11:48:51.355  3702  3748 D io.jxcore.node.ConnectivityMonitor: stop
,07-27 11:48:51.356  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:51.357  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 11:48:51.357  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 11:48:51.360  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
07-27 11:48:51.360  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:48:51.360  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-27 11:48:51.360  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27e94f9 not in the list
,07-27 11:48:51.361   874  1317 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 11:48:51.361   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 11:48:51.361   874  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-27 11:48:51.361  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:51.361  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:51.363  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:48:51.363  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:48:51.363  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-27 11:48:51.364  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f57ec removed from the list
07-27 11:48:51.364  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:48:51.364  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 11:48:51.364  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:51.364  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:48:51.365  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f6fa9f removed from the list
,07-27 11:48:51.366  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:48:51.366  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88a87b5 added. We now have 2 listener(s)
,07-27 11:48:51.371  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-27 11:48:51.371  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-27 11:48:51.371  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:48:51.371  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:48:51.371  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3531e4a added. We now have 9 listener(s)
07-27 11:48:51.371  3702  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:48:51.372  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-27 11:48:51.375  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 11:48:51.376   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 11:48:51.379  3702  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:48:51.379  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:51.379  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:51.379  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:48:51.379  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:48:51.379  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:48:51.379  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:48:51.379  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:48:51.381  3702  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:48:51.382  3702  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:48:51.383  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:48:51.383  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d8 added. We now have 3 listener(s)
07-27 11:48:51.383   372   872 D CommandListener: Setting iface cfg
07-27 11:48:51.383  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:48:51.385  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:48:51.385  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-27 11:48:51.385  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:48:51.385  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:48:51.385  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:48:51.385  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528ea31 added. We now have 10 listener(s)
07-27 11:48:51.385  3702  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:48:51.386  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-27 11:48:51.386  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 11:48:51.386  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:48:51.386  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-27 11:48:51.387   874  1317 D WifiStateMachine: Start Dhcp Watchdog 3
,07-27 11:48:51.389  3702  3748 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-27 11:48:51.389  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-27 11:48:51.392  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-27 11:48:51.393  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-27 11:48:51.393  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-27 11:48:51.394   874  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,07-27 11:48:51.396  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-27 11:48:51.396  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-27 11:48:51.396  3702  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-27 11:48:51.397  3702  3748 D BluetoothAdapter: STATE_ON
,07-27 11:48:51.400  4049  4060 D BtGatt.GattService: registerClient() - UUID=9233dcab-29b6-4326-b692-3c5b85a5c583
,07-27 11:48:51.401  4049  4065 D BtGatt.GattService: onClientRegistered() - UUID=9233dcab-29b6-4326-b692-3c5b85a5c583, clientIf=5
,07-27 11:48:51.401  3702  3762 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-27 11:48:51.402  4049  4059 D BtGatt.GattService: start scan with filters
,07-27 11:48:51.405  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-27 11:48:51.405  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-27 11:48:51.405  4049  4068 D BtGatt.ScanManager: handling starting scan
07-27 11:48:51.405  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-27 11:48:51.405  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,07-27 11:48:51.406  4049  4068 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@670d5c3
,07-27 11:48:51.408  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-27 11:48:51.408  3702  3702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-27 11:48:51.409  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-27 11:48:51.410  4049  4065 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,07-27 11:48:51.410  4049  4065 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 11:48:51.410  4049  4068 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,07-27 11:48:51.411  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-27 11:48:51.411   874  4107 D DhcpClient: Receive thread started
,07-27 11:48:51.414  3702  3748 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,07-27 11:48:51.414  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-27 11:48:51.414  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:51.414  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-27 11:48:51.414  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,07-27 11:48:51.415  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,07-27 11:48:51.415  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-27 11:48:51.415  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-27 11:48:51.415  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,07-27 11:48:51.415  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-27 11:48:51.416  3702  3748 D BluetoothAdapter: STATE_ON
,07-27 11:48:51.416  4049  4077 D BtGatt.GattService: stopScan() - queue size =1
07-27 11:48:51.417  4049  4088 D BtGatt.GattService: unregisterClient() - clientIf=5
07-27 11:48:51.417  4049  4065 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,07-27 11:48:51.417  4049  4065 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-27 11:48:51.417  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:48:51.417  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-27 11:48:51.417  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,07-27 11:48:51.417  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-27 11:48:51.417  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-27 11:48:51.418  4049  4068 D BtGatt.ScanManager: Starting BLE batch scan
07-27 11:48:51.418  4049  4068 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-27 11:48:51.419  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 11:48:51.419  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-27 11:48:51.419  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-27 11:48:51.419  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 11:48:51.419  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:48:51.420  3702  3702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 11:48:51.420  3702  3702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 11:48:51.420  3702  3702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 11:48:51.423  3702  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:48:51.423  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:48:51.423  3702  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:48:51.423  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:48:51.423  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:51.423  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:48:51.423  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:48:51.423  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88a87b5 removed from the list
07-27 11:48:51.423  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:51.424  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3531e4a removed from the list
07-27 11:48:51.424  3702  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:48:51.424  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:51.424  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:51.424  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:51.425  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:48:51.425  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:48:51.425  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:51.425  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3531e4a not in the list
07-27 11:48:51.425  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:51.425  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:51.426  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-27 11:48:51.426  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:48:51.426  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-27 11:48:51.426  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528ea31 removed from the list
07-27 11:48:51.427  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:48:51.427  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:51.427  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:51.427  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-27 11:48:51.427  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d8 removed from the list
07-27 11:48:51.428  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:48:51.428  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@570f86d added. We now have 2 listener(s)
,07-27 11:48:51.429  4049  4065 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-27 11:48:51.429  4049  4065 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 11:48:51.430  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-27 11:48:51.430  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
,07-27 11:48:51.430  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:48:51.430  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-27 11:48:51.431  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e192ca2 added. We now have 9 listener(s)
07-27 11:48:51.431  3702  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 11:48:51.431  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 11:48:51.434  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:48:51.435  4049  4065 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-27 11:48:51.435  4049  4065 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-27 11:48:51.438  3702  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:48:51.438  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:51.438  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:51.438  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:48:51.438  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:48:51.438  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:48:51.438  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:48:51.438  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:48:51.440  3702  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:48:51.440  3702  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:48:51.440  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-27 11:48:51.440  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38cd8f0 added. We now have 3 listener(s)
,07-27 11:48:51.441  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:48:51.443  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:48:51.443  4049  4065 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-27 11:48:51.443  4049  4065 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 11:48:51.443  4049  4068 D BtGatt.ScanManager: stopping BLe Batch
,07-27 11:48:51.444  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-27 11:48:51.444  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:48:51.444  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:48:51.444  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-27 11:48:51.444  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b1ae69 added. We now have 10 listener(s)
07-27 11:48:51.444  3702  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:48:51.444  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:48:51.445  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:48:51.445  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-27 11:48:51.445  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:48:51.445  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-27 11:48:51.449  3702  3748 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-27 11:48:51.449  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-27 11:48:51.450  4049  4065 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-27 11:48:51.450  4049  4065 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-27 11:48:51.450  4049  4068 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-27 11:48:51.454  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-27 11:48:51.455  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-27 11:48:51.455  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-27 11:48:51.455  4049  4065 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,07-27 11:48:51.455  4049  4065 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-27 11:48:51.458  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-27 11:48:51.458  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-27 11:48:51.458  3702  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-27 11:48:51.458  3702  3748 D BluetoothAdapter: STATE_ON
,07-27 11:48:51.460  4049  4060 D BtGatt.GattService: registerClient() - UUID=5850a6e2-5396-4815-a1b3-04dde3b69f52
,07-27 11:48:51.460  4049  4065 D BtGatt.GattService: onClientRegistered() - UUID=5850a6e2-5396-4815-a1b3-04dde3b69f52, clientIf=5
07-27 11:48:51.461  3702  3762 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-27 11:48:51.461  4049  4059 D BtGatt.GattService: start scan with filters
,07-27 11:48:51.463  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-27 11:48:51.463  4049  4068 D BtGatt.ScanManager: handling starting scan
07-27 11:48:51.463  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-27 11:48:51.463  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-27 11:48:51.463  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,07-27 11:48:51.467  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-27 11:48:51.468  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-27 11:48:51.468  3702  3702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-27 11:48:51.469  4049  4065 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-27 11:48:51.469  4049  4065 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 11:48:51.469  4049  4068 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,07-27 11:48:51.470  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-27 11:48:51.473  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,07-27 11:48:51.473  3702  3748 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-27 11:48:51.473  3702  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:48:51.473  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:48:51.473  3702  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-27 11:48:51.474  4049  4065 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-27 11:48:51.474  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:48:51.474  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 11:48:51.474  4049  4065 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 11:48:51.474  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-27 11:48:51.474  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:48:51.474  4049  4068 D BtGatt.ScanManager: Starting BLE batch scan
07-27 11:48:51.474  4049  4068 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,07-27 11:48:51.474  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@570f86d removed from the list
07-27 11:48:51.474  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:51.474  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e192ca2 removed from the list
07-27 11:48:51.475  3702  3748 D io.jxcore.node.ConnectivityMonitor: stop
,07-27 11:48:51.475  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:48:51.475  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:51.475  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-27 11:48:51.475  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:51.475  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-27 11:48:51.477  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:48:51.477  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-27 11:48:51.477  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:51.477  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e192ca2 not in the list
07-27 11:48:51.477  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-27 11:48:51.477  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-27 11:48:51.477  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-27 11:48:51.477  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-27 11:48:51.478  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-27 11:48:51.479  3702  3748 D BluetoothAdapter: STATE_ON
,07-27 11:48:51.479  4049  4077 D BtGatt.GattService: stopScan() - queue size =1
07-27 11:48:51.480  4049  4088 D BtGatt.GattService: unregisterClient() - clientIf=5
07-27 11:48:51.480  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-27 11:48:51.480  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-27 11:48:51.480  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-27 11:48:51.480  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-27 11:48:51.481  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,07-27 11:48:51.482  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 11:48:51.482  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-27 11:48:51.482  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-27 11:48:51.482  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 11:48:51.483  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 11:48:51.483  4049  4065 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-27 11:48:51.483  4049  4065 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 11:48:51.484  3702  3702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 11:48:51.484  3702  3702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 11:48:51.484  3702  3702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-27 11:48:51.484  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:48:51.484  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:48:51.484  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:51.485  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b1ae69 removed from the list
,07-27 11:48:51.485  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:48:51.485  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:51.485  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:51.485  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-27 11:48:51.485  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38cd8f0 removed from the list
07-27 11:48:51.486  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:48:51.486  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22dc825 added. We now have 2 listener(s)
,07-27 11:48:51.488  4049  4065 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,07-27 11:48:51.488  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-27 11:48:51.488  4049  4065 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 11:48:51.488  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:48:51.488  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-27 11:48:51.489  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:48:51.489  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@217adfa added. We now have 9 listener(s)
07-27 11:48:51.489  3702  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:48:51.489  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-27 11:48:51.492  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 11:48:51.493   874  1317 E native  : do suspend false
,07-27 11:48:51.494  4049  4065 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,07-27 11:48:51.494  4049  4065 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 11:48:51.495  4049  4068 D BtGatt.ScanManager: stopping BLe Batch
07-27 11:48:51.496  3702  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:48:51.496  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:51.496  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:51.496  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:48:51.496  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:48:51.496  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:48:51.496  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:48:51.496  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:48:51.498  3702  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:48:51.498  3702  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-27 11:48:51.499  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:48:51.500  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-27 11:48:51.500  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a6ed608 added. We now have 3 listener(s)
07-27 11:48:51.500  4049  4065 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,07-27 11:48:51.500  4049  4065 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 11:48:51.500  4049  4068 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-27 11:48:51.501  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:48:51.502  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-27 11:48:51.502  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:48:51.502  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:48:51.502  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:48:51.502  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@897c1a1 added. We now have 10 listener(s)
07-27 11:48:51.502  3702  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:48:51.502  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:48:51.503  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-27 11:48:51.503  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:48:51.503  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-27 11:48:51.505   874  2030 D DhcpClient: Broadcasting DHCPDISCOVER
07-27 11:48:51.506  4049  4065 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-27 11:48:51.506  4049  4065 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 11:48:51.506  3702  3748 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-27 11:48:51.506  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-27 11:48:51.509  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-27 11:48:51.509  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-27 11:48:51.509  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-27 11:48:51.512  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-27 11:48:51.512  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-27 11:48:51.512  3702  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,07-27 11:48:51.512  3702  3748 D BluetoothAdapter: STATE_ON
,07-27 11:48:51.514  4049  4088 D BtGatt.GattService: registerClient() - UUID=5f88c1bc-17d7-4793-b41c-0cef46126c52
,07-27 11:48:51.514  4049  4065 D BtGatt.GattService: onClientRegistered() - UUID=5f88c1bc-17d7-4793-b41c-0cef46126c52, clientIf=5
07-27 11:48:51.514  3702  3762 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-27 11:48:51.515  4049  4060 D BtGatt.GattService: start scan with filters
,07-27 11:48:51.516   874  4107 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,07-27 11:48:51.517   874  2030 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
07-27 11:48:51.517  4049  4068 D BtGatt.ScanManager: handling starting scan
07-27 11:48:51.517  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-27 11:48:51.517  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-27 11:48:51.517  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-27 11:48:51.517  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,07-27 11:48:51.517   874  2030 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,07-27 11:48:51.520  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-27 11:48:51.520  3702  3702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-27 11:48:51.520  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-27 11:48:51.521  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-27 11:48:51.522  4049  4065 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-27 11:48:51.522  4049  4065 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 11:48:51.522  4049  4068 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,07-27 11:48:51.526  3702  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:48:51.526  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-27 11:48:51.526  3702  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:48:51.526  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:48:51.526  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 11:48:51.526  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-27 11:48:51.526  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:48:51.526  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22dc825 removed from the list
,07-27 11:48:51.527  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:51.527  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@217adfa removed from the list
07-27 11:48:51.527  3702  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:48:51.527  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:48:51.527  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-27 11:48:51.527  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-27 11:48:51.527  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:51.527  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:48:51.527  4049  4065 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-27 11:48:51.528  4049  4065 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 11:48:51.528  4049  4068 D BtGatt.ScanManager: Starting BLE batch scan
,07-27 11:48:51.528  4049  4068 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,07-27 11:48:51.528  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:48:51.528  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-27 11:48:51.528   874  4107 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
07-27 11:48:51.528  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:51.529  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@217adfa not in the list
,07-27 11:48:51.529  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-27 11:48:51.529  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-27 11:48:51.529  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-27 11:48:51.529   874  2030 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
07-27 11:48:51.529  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-27 11:48:51.529  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-27 11:48:51.530  3702  3748 D BluetoothAdapter: STATE_ON
07-27 11:48:51.530  4049  4059 D BtGatt.GattService: stopScan() - queue size =1
07-27 11:48:51.531   372   872 D CommandListener: Setting iface cfg
07-27 11:48:51.531  4049  4088 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-27 11:48:51.531  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:48:51.531  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-27 11:48:51.531  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-27 11:48:51.531  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-27 11:48:51.531  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-27 11:48:51.532  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 11:48:51.533  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-27 11:48:51.533  3702  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-27 11:48:51.533  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-27 11:48:51.533  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:51.533   874  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
07-27 11:48:51.534  3702  3702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 11:48:51.534  3702  3702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 11:48:51.534  3702  3702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 11:48:51.534  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-27 11:48:51.534  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:48:51.534  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:51.534  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@897c1a1 removed from the list
07-27 11:48:51.535  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:48:51.535  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:51.535  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:51.535  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:48:51.535  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a6ed608 removed from the list
,07-27 11:48:51.536  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:48:51.536  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@94dd6dd added. We now have 2 listener(s)
07-27 11:48:51.538  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-27 11:48:51.538   874  1317 E native  : do suspend true
07-27 11:48:51.538  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:48:51.538  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:48:51.538  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-27 11:48:51.539  4049  4065 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-27 11:48:51.539  4049  4065 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 11:48:51.539  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98a0252 added. We now have 9 listener(s)
07-27 11:48:51.539   874  2030 D DhcpClient: Scheduling renewal in 86399s
07-27 11:48:51.539  3702  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:48:51.539  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 11:48:51.543  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:48:51.545  4049  4065 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-27 11:48:51.545  4049  4065 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 11:48:51.546  3702  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:48:51.546  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:51.546  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:51.546  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:48:51.546  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:48:51.546  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:48:51.546  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:48:51.546  3702  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:48:51.548  3702  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:48:51.548  3702  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-27 11:48:51.549  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:48:51.549  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:48:51.550  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec05e20 added. We now have 3 listener(s)
07-27 11:48:51.550  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:48:51.551  4049  4065 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-27 11:48:51.551  4049  4065 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-27 11:48:51.551  4049  4068 D BtGatt.ScanManager: stopping BLe Batch
07-27 11:48:51.551   874  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
07-27 11:48:51.552   874  1317 D WifiConfigStore: No blacklist allowed without epno enabled
,07-27 11:48:51.552  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-27 11:48:51.552   874  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-27 11:48:51.552  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:48:51.552  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:48:51.555   874  1317 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-27 11:48:51.555   874  1320 D ConnectivityService: Adding iface wlan0 to network 102
07-27 11:48:51.556  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-27 11:48:51.557  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15603d9 added. We now have 10 listener(s)
07-27 11:48:51.557  3702  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:48:51.557  3702  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:48:51.557  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:48:51.557  3702  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:48:51.557  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:48:51.557  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 11:48:51.557  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:48:51.558  4049  4065 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-27 11:48:51.558  4049  4065 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 11:48:51.558  4049  4068 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-27 11:48:51.558  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-27 11:48:51.558  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@94dd6dd removed from the list
07-27 11:48:51.558  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:51.558  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98a0252 removed from the list
07-27 11:48:51.558  3702  3748 D io.jxcore.node.ConnectivityMonitor: stop
,07-27 11:48:51.558  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 11:48:51.559  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:51.559  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:51.560  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-27 11:48:51.560  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:48:51.560  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:48:51.560  3702  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98a0252 not in the list,
07-27 11:48:51.560  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:48:51.560  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:51.561  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-27 11:48:51.561  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:48:51.561  3702  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-27 11:48:51.561  3702  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15603d9 removed from the list
07-27 11:48:51.561  3702  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:48:51.561  3702  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 11:48:51.561  3702  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:48:51.561  3702  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:48:51.561  3702  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec05e20 removed from the list
07-27 11:48:51.562  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,07-27 11:48:51.562  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-27 11:48:51.562  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-27 11:48:51.562  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-27 11:48:51.562  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,07-27 11:48:51.562  3702  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-27 11:48:51.563  4049  4065 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-27 11:48:51.563  4049  4065 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 11:48:51.569  3702  4109 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: My test thread name)
07-27 11:48:51.569  3702  4109 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 439, thread name: My test thread name)
07-27 11:48:51.569  3702  4109 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 439, name: My test thread name)
07-27 11:48:51.570  3702  4110 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 441, name: My test thread name)
07-27 11:48:51.571  3702  4110 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 441, thread name: My test thread name)
07-27 11:48:51.571  3702  4110 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 441, name: My test thread name)
07-27 11:48:51.572  3702  3748 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 84
07-27 11:48:51.572  3702  3748 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 84
07-27 11:48:51.572  3702  3748 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-27 11:48:51.572  3702  3748 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-27 11:48:51.572  3702  3748 D com.test.thalitest.ThaliTestRunner: Total duration: 22795 ms
07-27 11:48:51.574  3702  3748 I jxcore-log: Total number of executed tests:  84
07-27 11:48:51.574  3702  3748 I jxcore-log: 
07-27 11:48:51.574  3702  3748 I jxcore-log: Number of passed tests:  84
07-27 11:48:51.574  3702  3748 I jxcore-log: 
07-27 11:48:51.574  3702  3748 I jxcore-log: Number of failed tests:  0
07-27 11:48:51.574  3702  3748 I jxcore-log: 
07-27 11:48:51.575  3702  3748 I jxcore-log: Number of ignored tests:  0
07-27 11:48:51.575  3702  3748 I jxcore-log: 
07-27 11:48:51.575  3702  3748 I jxcore-log: Total duration:  22795
07-27 11:48:51.575  3702  3748 I jxcore-log: 
07-27 11:48:51.575  3702  3748 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
07-27 11:48:51.575  3702  3748 I jxcore-log: 
07-27 11:48:51.577  3702  3748 I jxcore-log: Unit Test app is loaded
07-27 11:48:51.577  3702  3748 I jxcore-log: 
07-27 11:48:51.586  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:48:51.586  3702  3748 I jxcore-log: 
07-27 11:48:51.587  3702  3702 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-27 11:48:51.589  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:48:51.589  3702  3748 I jxcore-log: 
07-27 11:48:51.590  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:48:51.590  3702  3748 I jxcore-log: 
07-27 11:48:51.591  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-27 11:48:51.591  3702  3748 I jxcore-log: 
07-27 11:48:51.592  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-27 11:48:51.592  3702  3748 I jxcore-log: 
07-27 11:48:51.593  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:48:51.593  3702  3748 I jxcore-log: 
07-27 11:48:51.593   874  1320 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-27 11:48:51.594   874  1320 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
07-27 11:48:51.595   874  1320 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
07-27 11:48:51.595  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-27 11:48:51.595  3702  3748 I jxcore-log: 
07-27 11:48:51.596   874  1320 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
07-27 11:48:51.597  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-27 11:48:51.597  3702  3748 I jxcore-log: 
07-27 11:48:51.597   874  1320 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
07-27 11:48:51.598  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:48:51.598  3702  3748 I jxcore-log: 
07-27 11:48:51.601  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-27 11:48:51.601  3702  3748 I jxcore-log: 
07-27 11:48:51.601  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-27 11:48:51.601  3702  3748 I jxcore-log: 
07-27 11:48:51.602  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-27 11:48:51.602  3702  3748 I jxcore-log: 
07-27 11:48:51.602  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-27 11:48:51.602  3702  3748 I jxcore-log: 
07-27 11:48:51.603  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:48:51.603  3702  3748 I jxcore-log: 
07-27 11:48:51.604  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:48:51.604  3702  3748 I jxcore-log: 
07-27 11:48:51.604  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-27 11:48:51.604  3702  3748 I jxcore-log: 
07-27 11:48:51.605  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-27 11:48:51.605  3702  3748 I jxcore-log: 
07-27 11:48:51.606  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 11:48:51.606  3702  3748 I jxcore-log: 
07-27 11:48:51.606   874  1320 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
07-27 11:48:51.606  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 11:48:51.606  3702  3748 I jxcore-log: 
07-27 11:48:51.607  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-27 11:48:51.607  3702  3748 I jxcore-log: 
07-27 11:48:51.608  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-27 11:48:51.608  3702  3748 I jxcore-log: 
07-27 11:48:51.608  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:48:51.608  3702  3748 I jxcore-log: 
07-27 11:48:51.609  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:48:51.609  3702  3748 I jxcore-log: 
07-27 11:48:51.609  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-27 11:48:51.609  3702  3748 I jxcore-log: 
07-27 11:48:51.610  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-27 11:48:51.610  3702  3748 I jxcore-log: 
07-27 11:48:51.610  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 11:48:51.610  3702  3748 I jxcore-log: 
07-27 11:48:51.611  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 11:48:51.611  3702  3748 I jxcore-log: 
07-27 11:48:51.612  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 11:48:51.612  3702  3748 I jxcore-log: 
07-27 11:48:51.612  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 11:48:51.612  3702  3748 I jxcore-log: 
07-27 11:48:51.613  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 11:48:51.613  3702  3748 I jxcore-log: 
07-27 11:48:51.613   874  1320 D ConnectivityService: scheduleUnvalidatedPrompt 102
07-27 11:48:51.613   874  1320 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
07-27 11:48:51.613   874  1320 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
07-27 11:48:51.613   874  1317 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-27 11:48:51.613   874  1320 D ConnectivityService:    accepting network in place of null
07-27 11:48:51.613  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 11:48:51.613  3702  3748 I jxcore-log: 
07-27 11:48:51.614   874  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-27 11:48:51.614  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 11:48:51.614  3702  3748 I jxcore-log: 
07-27 11:48:51.614   874  1320 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 11:48:51.614  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 11:48:51.614  3702  3748 I jxcore-log: 
07-27 11:48:51.615  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 11:48:51.615  3702  3748 I jxcore-log: 
07-27 11:48:51.616  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 11:48:51.616  3702  3748 I jxcore-log: 
07-27 11:48:51.616  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 11:48:51.616  3702  3748 I jxcore-log: 
07-27 11:48:51.617  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 11:48:51.617  3702  3748 I jxcore-log: 
07-27 11:48:51.617  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-27 11:48:51.617  3702  3748 I jxcore-log: 
07-27 11:48:51.618  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-27 11:48:51.618  3702  3748 I jxcore-log: 
07-27 11:48:51.618  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 11:48:51.618  3702  3748 I jxcore-log: 
07-27 11:48:51.619  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-27 11:48:51.619  3702  3748 I jxcore-log: 
07-27 11:48:51.620  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-27 11:48:51.620  3702  3748 I jxcore-log: 
,07-27 11:48:51.620   874  4106 D NetlinkSocketObserver: NeighborEvent{elapsedMs=194047, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
07-27 11:48:51.620  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 11:48:51.620  3702  3748 I jxcore-log: 
07-27 11:48:51.621  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-27 11:48:51.621  3702  3748 I jxcore-log: 
07-27 11:48:51.621  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-27 11:48:51.621  3702  3748 I jxcore-log: 
07-27 11:48:51.622  3702  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 11:48:51.622  3702  3748 I jxcore-log: 
07-27 11:48:51.624  3702  3748 I jxcore-log: My device name is: motorola-Nexus 6
07-27 11:48:51.624  3702  3748 I jxcore-log: 
,07-27 11:48:51.645   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-27 11:48:51.675   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-27 11:48:51.687   874  1320 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,07-27 11:48:51.688   874  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-27 11:48:51.689   874  4105 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.19.238,2a00:1450:4001:800::200e
,07-27 11:48:51.690   874  1320 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
07-27 11:48:51.693   874   891 D Tethering: MasterInitialState.processMessage what=3
07-27 11:48:51.703  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:48:51.703  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:48:51.703  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 11:48:51.703  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:48:51.703  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:48:51.703  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:48:51.703  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:48:51.703  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:48:51.704  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-27 11:48:51.717  1867  1867 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,07-27 11:48:51.722  1867  1867 D SystemUpdateService: onCreate
,07-27 11:48:51.725  1867  1867 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,07-27 11:48:51.751  1867  1867 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-27 11:48:51.754  1867  2344 I iu.UploadsManager: num queued entries: 0
07-27 11:48:51.754  1867  2344 I iu.UploadsManager: num updated entries: 0
07-27 11:48:51.755  1867  2344 I iu.SyncManager: NEXT; no task
,07-27 11:48:51.765  1867  4120 I SystemUpdateService: active receiver: enabled
,07-27 11:48:51.767  1867  1867 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-27 11:48:51.768  1867  1867 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
07-27 11:48:51.769  3822  3822 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:48:51.773  3822  3822 D SprintDMHelper: simOperator: 
,07-27 11:48:51.773  3822  3822 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-27 11:48:51.798  1867  4122 I MDM     : [218] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,07-27 11:48:51.798  1867  4122 W BaseAppContext: Using Auth Proxy for data requests.
07-27 11:48:51.800  1867  4122 V GoogleAuthProtoRequest: [218] a.<init>: mAccountName set to: thalitester@gmail.com
,07-27 11:48:51.812  1867  4120 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,07-27 11:48:51.822   874  4105 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 27 Jul 2016 09:48:51 GMT], X-Android-Received-Millis=[1469612931821], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1469612931740]}
,07-27 11:48:51.823   874  1320 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-27 11:48:51.823   874  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,07-27 11:48:51.823   874  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
07-27 11:48:51.824   874  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-27 11:48:51.826  1867  4120 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
07-27 11:48:51.826  1867  4120 I SystemUpdateService: now status is 0 (complete)
07-27 11:48:51.826  1867  4120 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
07-27 11:48:51.826  1867  4120 I SystemUpdateService: file has been verified
07-27 11:48:51.826  1867  4120 I SystemUpdateService: OTA package size = 12249756,
07-27 11:48:51.829  1867  4120 I SystemUpdateService: showing system update notification
,07-27 11:48:51.851  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 11:48:51.854  1867  1867 D SystemUpdateService: onDestroy
07-27 11:48:51.855  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 11:48:51.873  1525  1915 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,07-27 11:48:51.873  1525  1915 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
07-27 11:48:51.874  1525  1915 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 11:48:51.874  1525  1915 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 11:48:51.887  1867  4122 E MDM     : [218] SitrepService.a: Error sending sitrep.
,07-27 11:48:51.921  3353  4125 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,07-27 11:48:52.277  4117  4117 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,07-27 11:48:52.281  4117  4117 D AndroidRuntime: CheckJNI is OFF
,07-27 11:48:52.328  4117  4117 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,07-27 11:48:52.374  4117  4117 I Radio-JNI: register_android_hardware_Radio DONE
,07-27 11:48:52.397  4117  4117 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-27 11:48:52.409   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
07-27 11:48:52.409   874   887 I ActivityManager: Killing 3702:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,07-27 11:48:52.498   874   897 W PackageSettings: Skipping PackageSetting{aef7724 com.example.hello/10273} due to missing metadata
,07-27 11:48:52.510   874  1539 D GraphicsStats: Buffer count: 2
,07-27 11:48:52.510   874  1539 I WindowState: WIN DEATH: Window{4a2d3f2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-27 11:48:52.511   874  1318 D WifiService: Client connection lost with reason: 4
,07-27 11:48:52.540   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,07-27 11:48:52.540   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,07-27 11:48:52.541   874   887 E ActivityManager: Failure starting process com.test.thalitest
07-27 11:48:52.541   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
07-27 11:48:52.541   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
07-27 11:48:52.541   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
07-27 11:48:52.541   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
07-27 11:48:52.541   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
07-27 11:48:52.541   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
07-27 11:48:52.541   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
07-27 11:48:52.541   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
07-27 11:48:52.541   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
07-27 11:48:52.541   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
07-27 11:48:52.541   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
07-27 11:48:52.541   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
07-27 11:48:52.541   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
07-27 11:48:52.541   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
07-27 11:48:52.541   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
07-27 11:48:52.541   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:48:52.541   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
07-27 11:48:52.541   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 11:48:52.541   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-27 11:48:52.541   874   887 I ActivityManager:   Force finishing activity ActivityRecord{b85ddbf u0 com.test.thalitest/.MainActivity t2}
07-27 11:48:52.543   874   897 I art     : Starting a blocking GC Explicit
,07-27 11:48:52.552   874  1767 W ActivityManager: Spurious death for ProcessRecord{57d97ed 0:com.test.thalitest/u0a0}, curProc for 3702: null
,07-27 11:48:52.585   874   897 I art     : Explicit concurrent mark sweep GC freed 51220(3MB) AllocSpace objects, 9(224KB) LOS objects, 33% free, 29MB/43MB, paused 701us total 41.169ms
,07-27 11:48:52.611   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,07-27 11:48:52.615  4117  4117 I art     : System.exit called, status: 0
,07-27 11:48:52.615  4117  4117 I AndroidRuntime: VM exiting with result code 0.
,07-27 11:48:52.617   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,07-27 11:48:52.634   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,07-27 11:48:52.637  1670  1670 I Keyboard.Facilitator: resetDictionaries() : en_US
,07-27 11:48:52.639   874  1309 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-27 11:48:52.640  4049  4049 D BluetoothMapAppObserver: onReceive
07-27 11:48:52.640  4049  4049 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,07-27 11:48:52.641  1854  2032 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-27 11:48:52.644  3547  3547 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,07-27 11:48:52.653  1670  4141 I Keyboard.Facilitator.DecoderInitializer: run()
,07-27 11:48:52.657  1670  4141 I Decoder : createOrResetDecoder
,07-27 11:48:52.673   874  1759 I ActivityManager: Start proc 4144:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,07-27 11:48:52.675  1748  1748 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,07-27 11:48:52.683  1525  1525 I ConfigService: onCreate
,07-27 11:48:52.710  1670  4141 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,07-27 11:48:52.733   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-27 11:48:52.735  4144  4144 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,07-27 11:48:52.739   874  2996 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3702 uid 10000
,07-27 11:48:52.740  1670  1670 I Keyboard.Facilitator: onFinishInput()
,07-27 11:48:52.751  1670  4141 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,07-27 11:48:52.754  1670  4141 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,07-27 11:48:52.754  1670  4141 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,07-27 11:48:52.757  1670  4141 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,07-27 11:48:52.757  1670  4141 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
07-27 11:48:52.758  1670  4141 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
07-27 11:48:52.758  1670  4141 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
07-27 11:48:52.758   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,07-27 11:48:52.758  1670  4141 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
07-27 11:48:52.758  1670  4141 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
07-27 11:48:52.758  1670  4141 I Keyboard.Facilitator.Delight2FileSweeper: run()
07-27 11:48:52.759  1670  4141 I Keyboard.Facilitator.RecurringTaskScheduler: run()
07-27 11:48:52.759  1670  4141 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,07-27 11:48:52.759  1670  4141 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,07-27 11:48:52.760   874   886 E PackageManager: Failed to write settings, restoring backup
07-27 11:48:52.760   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
07-27 11:48:52.760   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
07-27 11:48:52.760   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
07-27 11:48:52.760   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
07-27 11:48:52.760   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
07-27 11:48:52.760   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:48:52.760   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
07-27 11:48:52.760   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-27 11:48:52.788  1762  1842 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
07-27 11:48:52.788   874   887 E DropBoxManagerService: Can't write: system_server_wtf
07-27 11:48:52.788   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
07-27 11:48:52.788   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-27 11:48:52.788   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-27 11:48:52.788   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-27 11:48:52.788   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-27 11:48:52.788   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-27 11:48:52.788   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-27 11:48:52.788   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
07-27 11:48:52.788   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
07-27 11:48:52.788   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
07-27 11:48:52.788   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 11:48:52.788   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 11:48:52.788   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
07-27 11:48:52.788   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 11:48:52.788   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-27 11:48:52.788   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-27 11:48:52.788   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-27 11:48:52.788   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-27 11:48:52.788   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-27 11:48:52.788   874   887 E DropBoxManagerService: 	... 13 more
,07-27 11:48:52.791  4144  4144 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,07-27 11:48:52.796  4144  4159 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
07-27 11:48:52.796  4144  4159 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 11:48:52.796  4144  4159 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 11:48:52.796  4144  4159 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-27 11:48:52.796  4144  4159 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-27 11:48:52.796  4144  4159 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-27 11:48:52.796  4144  4159 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-27 11:48:52.796  4144  4159 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-27 11:48:52.796  4144  4159 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-27 11:48:52.796  4144  4159 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-27 11:48:52.796  4144  4159 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-27 11:48:52.796  4144  4159 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-27 11:48:52.796  4144  4159 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-27 11:48:52.796  4144  4159 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 11:48:52.796  4144  4159 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-27 11:48:52.796  4144  4159 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
07-27 11:48:52.796  4144  4159 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
07-27 11:48:52.796  4144  4159 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
07-27 11:48:52.796  4144  4159 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
07-27 11:48:52.796  4144  4159 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:48:52.796  4144  4159 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
07-27 11:48:52.796  4144  4159 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-27 11:48:52.797  4144  4159 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
07-27 11:48:52.797  4144  4159 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 11:48:52.797  4144  4159 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 11:48:52.797  4144  4159 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-27 11:48:52.797  4144  4159 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-27 11:48:52.797  4144  4159 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-27 11:48:52.797  4144  4159 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-27 11:48:52.797  4144  4159 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-27 11:48:52.797  4144  4159 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-27 11:48:52.797  4144  4159 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-27 11:48:52.797  4144  4159 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-27 11:48:52.797  4144  4159 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-27 11:48:52.797  4144  4159 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-27 11:48:52.797  4144  4159 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 11:48:52.797  4144  4159 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-27 11:48:52.797  4144  4159 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
07-27 11:48:52.797  4144  4159 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
07-27 11:48:52.797  4144  4159 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
07-27 11:48:52.797  4144  4159 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
07-27 11:48:52.797  4144  4159 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:48:52.797  4144  4159 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
07-27 11:48:52.797  4144  4159 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-27 11:48:52.800   874  1703 I ActivityManager: Start proc 4161:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
07-27 11:48:52.800  1762  1842 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
07-27 11:48:52.800  1762  1842 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1762
07-27 11:48:52.800  1762  1842 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-27 11:48:52.800  1762  1842 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-27 11:48:52.800  1762  1842 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
07-27 11:48:52.800  1762  1842 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-27 11:48:52.800  1762  1842 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-27 11:48:52.800  1762  1842 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
07-27 11:48:52.800  1762  1842 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
07-27 11:48:52.800  1762  1842 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
07-27 11:48:52.800  1762  1842 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 11:48:52.800  1762  1842 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 11:48:52.800  1762  1842 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-27 11:48:52.800  1762  1842 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-27 11:48:52.802   874  2996 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,07-27 11:48:52.802   874  4167 E DropBoxManagerService: Can't write: system_app_crash
07-27 11:48:52.802   874  4167 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
07-27 11:48:52.802   874  4167 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-27 11:48:52.802   874  4167 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-27 11:48:52.802   874  4167 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-27 11:48:52.802   874  4167 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-27 11:48:52.802   874  4167 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-27 11:48:52.802   874  4167 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-27 11:48:52.802   874  4167 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-27 11:48:52.802   874  4167 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-27 11:48:52.802   874  4167 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-27 11:48:52.802   874  4167 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-27 11:48:52.802   874  4167 E DropBoxManagerService: 	... 5 more
,07-27 11:48:52.808  1762  1842 I Process : Sending signal. PID: 1762 SIG: 9
,07-27 11:48:52.818   874  1759 I ActivityManager: Start proc 4175:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,07-27 11:48:52.819  4144  4180 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,07-27 11:48:52.845  4175  4175 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,07-27 11:48:52.879  1525  1525 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,07-27 11:48:52.880  1525  1525 D AndroidRuntime: Shutting down VM
,07-27 11:48:52.881  1525  1525 E AndroidRuntime: FATAL EXCEPTION: main
07-27 11:48:52.881  1525  1525 E AndroidRuntime: Process: com.google.process.gapps, PID: 1525
07-27 11:48:52.881  1525  1525 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-27 11:48:52.881  1525  1525 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
07-27 11:48:52.881  1525  1525 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
07-27 11:48:52.881  1525  1525 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
07-27 11:48:52.881  1525  1525 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:48:52.881  1525  1525 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-27 11:48:52.881  1525  1525 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 11:48:52.881  1525  1525 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:48:52.881  1525  1525 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 11:48:52.881  1525  1525 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 11:48:52.881  1525  1525 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-27 11:48:52.881  1525  1525 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-27 11:48:52.881  1525  1525 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
07-27 11:48:52.881  1525  1525 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-27 11:48:52.881  1525  1525 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-27 11:48:52.881  1525  1525 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
07-27 11:48:52.881  1525  1525 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
07-27 11:48:52.881  1525  1525 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
07-27 11:48:52.881  1525  1525 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
07-27 11:48:52.881  1525  1525 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
07-27 11:48:52.881  1525  1525 E AndroidRuntime: 	... 8 more
,07-27 11:48:52.885   874  4192 E DropBoxManagerService: Can't write: system_app_crash
07-27 11:48:52.885   874  4192 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
07-27 11:48:52.885   874  4192 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-27 11:48:52.885   874  4192 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-27 11:48:52.885   874  4192 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-27 11:48:52.885   874  4192 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-27 11:48:52.885   874  4192 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-27 11:48:52.885   874  4192 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-27 11:48:52.885   874  4192 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-27 11:48:52.885   874  4192 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-27 11:48:52.885   874  4192 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-27 11:48:52.885   874  4192 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-27 11:48:52.885   874  4192 E DropBoxManagerService: 	... 5 more
,07-27 11:48:52.885  1525  1525 I Process : Sending signal. PID: 1525 SIG: 9
,07-27 11:48:52.918   874  1759 D GraphicsStats: Buffer count: 1
,07-27 11:48:52.918   874  1729 I WindowState: WIN DEATH: Window{f3253f1 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,07-27 11:48:52.929   874  2996 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1762) has died
,07-27 11:48:52.930   874  2996 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,07-27 11:48:52.932   874  2996 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,07-27 11:48:52.949   874   887 I ActivityManager: Start proc 4195:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,07-27 11:48:52.950   874  1703 I ActivityManager: Killing 3012:com.google.android.apps.genie.geniewidget/u0a80 (adj 15): empty #17
,07-27 11:48:52.983  4144  4159 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,07-27 11:48:52.988  4144  4180 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
07-27 11:48:52.988  4144  4180 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 11:48:52.988  4144  4180 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 11:48:52.988  4144  4180 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-27 11:48:52.988  4144  4180 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-27 11:48:52.988  4144  4180 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-27 11:48:52.988  4144  4180 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-27 11:48:52.988  4144  4180 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-27 11:48:52.988  4144  4180 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-27 11:48:52.988  4144  4180 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-27 11:48:52.988  4144  4180 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-27 11:48:52.988  4144  4180 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-27 11:48:52.988  4144  4180 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-27 11:48:52.988  4144  4180 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 11:48:52.988  4144  4180 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 11:48:52.988  4144  4180 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
07-27 11:48:52.988  4144  4180 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
07-27 11:48:52.988  4144  4180 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
07-27 11:48:52.988  4144  4180 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
07-27 11:48:52.988  4144  4180 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
07-27 11:48:52.988  4144  4180 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
07-27 11:48:52.988  4144  4180 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-27 11:48:52.988  4144  4180 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:48:52.988  4144  4180 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
07-27 11:48:52.988  4144  4180 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-27 11:48:52.988  4144  4180 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
07-27 11:48:52.988  4144  4180 E AndroidRuntime: Process: android.process.acore, PID: 4144
07-27 11:48:52.988  4144  4180 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 11:48:52.988  4144  4180 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 11:48:52.988  4144  4180 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-27 11:48:52.988  4144  4180 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-27 11:48:52.988  4144  4180 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-27 11:48:52.988  4144  4180 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-27 11:48:52.988  4144  4180 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-27 11:48:52.988  4144  4180 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-27 11:48:52.988  4144  4180 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-27 11:48:52.988  4144  4180 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-27 11:48:52.988  4144  4180 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-27 11:48:52.988  4144  4180 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-27 11:48:52.988  4144  4180 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 11:48:52.988  4144  4180 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 11:48:52.988  4144  4180 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
07-27 11:48:52.988  4144  4180 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
07-27 11:48:52.988  4144  4180 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
07-27 11:48:52.988  4144  4180 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
07-27 11:48:52.988  4144  4180 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
07-27 11:48:52.988  4144  4180 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
07-27 11:48:52.988  4144  4180 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-27 11:48:52.988  4144  4180 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:48:52.988  4144  4180 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-27 11:48:52.988  4144  4180 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-27 11:48:52.989  4144  4159 I Process : Sending signal. PID: 4144 SIG: 9
,07-27 11:48:53.003   874  1318 D WifiService: Client connection lost with reason: 4
,07-27 11:48:53.023   874  1401 I ActivityManager: Process com.google.process.gapps (pid 1525) has died
,07-27 11:48:53.024   874  1401 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 1000ms
07-27 11:48:53.025   874  1401 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
,07-27 11:48:53.025   874  1401 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 20999ms
07-27 11:48:53.025   874  1401 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30999ms
,07-27 11:48:53.026   874  1401 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 40998ms
07-27 11:48:53.026   874  4207 E DropBoxManagerService: Can't write: system_app_crash
07-27 11:48:53.026   874  4207 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
07-27 11:48:53.026   874  4207 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-27 11:48:53.026   874  4207 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-27 11:48:53.026   874  4207 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-27 11:48:53.026   874  4207 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-27 11:48:53.026   874  4207 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-27 11:48:53.026   874  4207 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-27 11:48:53.026   874  4207 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-27 11:48:53.026   874  4207 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-27 11:48:53.026   874  4207 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-27 11:48:53.026   874  4207 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-27 11:48:53.026   874  4207 E DropBoxManagerService: 	... 5 more
,07-27 11:48:53.042  1867  1867 W RocketImpressions: ClearcutLogger connection suspended: 1
,07-27 11:48:53.059  4195  4195 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
07-27 11:48:53.059  4195  4195 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 11:48:53.059  4195  4195 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 11:48:53.059  4195  4195 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-27 11:48:53.059  4195  4195 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-27 11:48:53.059  4195  4195 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-27 11:48:53.059  4195  4195 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-27 11:48:53.059  4195  4195 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-27 11:48:53.059  4195  4195 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-27 11:48:53.059  4195  4195 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-27 11:48:53.059  4195  4195 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-27 11:48:53.059  4195  4195 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-27 11:48:53.059  4195  4195 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-27 11:48:53.059  4195  4195 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 11:48:53.059  4195  4195 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 11:48:53.059  4195  4195 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
07-27 11:48:53.059  4195  4195 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
07-27 11:48:53.059  4195  4195 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
07-27 11:48:53.059  4195  4195 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
07-27 11:48:53.059  4195  4195 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
07-27 11:48:53.059  4195  4195 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
07-27 11:48:53.059  4195  4195 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
07-27 11:48:53.059  4195  4195 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 11:48:53.059  4195  4195 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 11:48:53.059  4195  4195 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:48:53.059  4195  4195 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
07-27 11:48:53.059  4195  4195 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 11:48:53.059  4195  4195 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:48:53.059  4195  4195 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 11:48:53.059  4195  4195 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-27 11:48:53.060  4195  4195 D AndroidRuntime: Shutting down VM
,07-27 11:48:53.070   874  1759 I ActivityManager: Start proc 4209:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,07-27 11:48:53.074   874  1767 I ActivityManager: Process android.process.acore (pid 4144) has died
,07-27 11:48:53.075   874  1767 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 50950ms
,07-27 11:48:53.082  4195  4195 E AndroidRuntime: FATAL EXCEPTION: main
07-27 11:48:53.082  4195  4195 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4195
07-27 11:48:53.082  4195  4195 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 11:48:53.082  4195  4195 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
07-27 11:48:53.082  4195  4195 E AndroidRuntime: 	... 10 more
07-27 11:48:53.085   874  1722 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
07-27 11:48:53.086  4195  4195 I Process : Sending signal. PID: 4195 SIG: 9
07-27 11:48:53.094   874  4221 E DropBoxManagerService: Can't write: system_app_crash
07-27 11:48:53.094   874  4221 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
07-27 11:48:53.094   874  4221 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-27 11:48:53.094   874  4221 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-27 11:48:53.094   874  4221 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-27 11:48:53.094   874  4221 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-27 11:48:53.094   874  4221 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-27 11:48:53.094   874  4221 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-27 11:48:53.094   874  4221 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-27 11:48:53.094   874  4221 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-27 11:48:53.094   874  4221 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-27 11:48:53.094   874  4221 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-27 11:48:53.094   874  4221 E DropBoxManagerService: 	... 5 more
,07-27 11:48:53.112   874  1729 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4195) has died
,07-27 11:48:53.113   874  1729 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,07-27 11:48:53.125  4209  4209 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,07-27 11:48:53.130   874   887 I ActivityManager: Start proc 4224:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
07-27 11:48:53.131  1867  1867 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-27 11:48:53.131  1867  1867 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,07-27 11:48:53.135  1867  1867 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,07-27 11:48:53.135  1867  1867 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,07-27 11:48:53.143  4209  4209 I GservicesProvider: Gservices pushing to system: true; secure/global: true

```
