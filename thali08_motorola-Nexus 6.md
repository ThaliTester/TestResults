#### Test 75789268514fc25_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
07-15 15:21:57.792  1523  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-15 15:21:57.792  1523  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-15 15:21:57.792  1523  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:21:57.792  1523  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-15 15:21:57.820  3567  3818 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-15 15:21:57.820  3567  3818 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-15 15:21:57.820  3567  3818 E HttpOperation: 	at jdm.a(PG:82)
07-15 15:21:57.820  3567  3818 E HttpOperation: 	at jcs.o(PG:406)
07-15 15:21:57.820  3567  3818 E HttpOperation: 	at jcn.a(PG:1379)
07-15 15:21:57.820  3567  3818 E HttpOperation: 	at jcs.i(PG:143)
07-15 15:21:57.820  3567  3818 E HttpOperation: 	at blb.a(PG:3937)
07-15 15:21:57.820  3567  3818 E HttpOperation: 	at czp.a(PG:18188)
07-15 15:21:57.820  3567  3818 E HttpOperation: 	at czp.a(PG:9081)
07-15 15:21:57.820  3567  3818 E HttpOperation: 	at czq.run(PG:1686)
07-15 15:21:57.820  3567  3818 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-15 15:21:57.820  3567  3818 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-15 15:21:57.820  3567  3818 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-15 15:21:57.820  3567  3818 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-15 15:21:57.820  3567  3818 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-15 15:21:57.820  3567  3818 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-15 15:21:57.820  3567  3818 E HttpOperation: 	at jdj.a(PG:4091)
07-15 15:21:57.820  3567  3818 E HttpOperation: 	at jdj.a(PG:1125)
07-15 15:21:57.820  3567  3818 E HttpOperation: 	at jdm.a(PG:77)
07-15 15:21:57.820  3567  3818 E HttpOperation: 	... 12 more
07-15 15:21:57.820  3567  3818 E HttpOperation: Caused by: faj: BadAuthentication
07-15 15:21:57.820  3567  3818 E HttpOperation: 	at fal.a(PG:38)
07-15 15:21:57.820  3567  3818 E HttpOperation: 	at jdj.a(PG:4089)
07-15 15:21:57.820  3567  3818 E HttpOperation: 	... 14 more
07-15 15:21:57.890  1523  2101 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-15 15:21:57.890  1523  2101 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-15 15:21:57.890  1523  2101 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:21:57.891  1523  2101 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-15 15:21:57.922  3567  3818 E HttpOperation: [getmobileexperiments] Unexpected exception
07-15 15:21:57.922  3567  3818 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-15 15:21:57.922  3567  3818 E HttpOperation: 	at jdm.a(PG:82)
07-15 15:21:57.922  3567  3818 E HttpOperation: 	at jcs.o(PG:406)
07-15 15:21:57.922  3567  3818 E HttpOperation: 	at jcn.a(PG:1379)
07-15 15:21:57.922  3567  3818 E HttpOperation: 	at jcs.i(PG:143)
07-15 15:21:57.922  3567  3818 E HttpOperation: 	at hec.a(PG:42)
07-15 15:21:57.922  3567  3818 E HttpOperation: 	at hee.a(PG:102)
07-15 15:21:57.922  3567  3818 E HttpOperation: 	at czr.a(PG:65)
07-15 15:21:57.922  3567  3818 E HttpOperation: 	at kka.a(PG:108)
07-15 15:21:57.922  3567  3818 E HttpOperation: 	at czp.a(PG:19176)
07-15 15:21:57.922  3567  3818 E HttpOperation: 	at czp.a(PG:9081)
07-15 15:21:57.922  3567  3818 E HttpOperation: 	at czq.run(PG:1686)
07-15 15:21:57.922  3567  3818 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-15 15:21:57.922  3567  3818 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-15 15:21:57.922  3567  3818 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-15 15:21:57.922  3567  3818 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-15 15:21:57.922  3567  3818 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-15 15:21:57.922  3567  3818 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-15 15:21:57.922  3567  3818 E HttpOperation: 	at jdj.a(PG:4091)
07-15 15:21:57.922  3567  3818 E HttpOperation: 	at jdj.a(PG:1125)
07-15 15:21:57.922  3567  3818 E HttpOperation: 	at jdm.a(PG:77)
07-15 15:21:57.922  3567  3818 E HttpOperation: 	... 15 more
07-15 15:21:57.922  3567  3818 E HttpOperation: Caused by: faj: BadAuthentication
07-15 15:21:57.922  3567  3818 E HttpOperation: 	at fal.a(PG:38)
07-15 15:21:57.922  3567  3818 E HttpOperation: 	at jdj.a(PG:4089)
07-15 15:21:57.922  3567  3818 E HttpOperation: 	... 17 more
07-15 15:21:57.923  3567  3818 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-15 15:21:57.923  3567  3818 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-15 15:21:57.923  3567  3818 E ExperimentLoader: 	at jdm.a(PG:82)
07-15 15:21:57.923  3567  3818 E ExperimentLoader: 	at jcs.o(PG:406)
07-15 15:21:57.923  3567  3818 E ExperimentLoader: 	at jcn.a(PG:1379)
07-15 15:21:57.923  3567  3818 E ExperimentLoader: 	at jcs.i(PG:143)
07-15 15:21:57.923  3567  3818 E ExperimentLoader: 	at hec.a(PG:42)
07-15 15:21:57.923  3567  3818 E ExperimentLoader: 	at hee.a(PG:102)
07-15 15:21:57.923  3567  3818 E ExperimentLoader: 	at czr.a(PG:65)
07-15 15:21:57.923  3567  3818 E ExperimentLoader: 	at kka.a(PG:108)
07-15 15:21:57.923  3567  3818 E ExperimentLoader: 	at czp.a(PG:19176)
07-15 15:21:57.923  3567  3818 E ExperimentLoader: 	at czp.a(PG:9081)
07-15 15:21:57.923  3567  3818 E ExperimentLoader: 	at czq.run(PG:1686)
07-15 15:21:57.923  3567  3818 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-15 15:21:57.923  3567  3818 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-15 15:21:57.923  3567  3818 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-15 15:21:57.923  3567  3818 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-15 15:21:57.923  3567  3818 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-15 15:21:57.923  3567  3818 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-15 15:21:57.923  3567  3818 E ExperimentLoader: 	at jdj.a(PG:4091)
07-15 15:21:57.923  3567  3818 E ExperimentLoader: 	at jdj.a(PG:1125)
07-15 15:21:57.923  3567  3818 E ExperimentLoader: 	at jdm.a(PG:77)
07-15 15:21:57.923  3567  3818 E ExperimentLoader: 	... 15 more
07-15 15:21:57.923  3567  3818 E ExperimentLoader: Caused by: faj: BadAuthentication
07-15 15:21:57.923  3567  3818 E ExperimentLoader: 	at fal.a(PG:38)
07-15 15:21:57.923  3567  3818 E ExperimentLoader: 	at jdj.a(PG:4089)
07-15 15:21:57.923  3567  3818 E ExperimentLoader: 	... 17 more
07-15 15:21:58.046   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 130832, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
07-15 15:21:58.109  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-15 15:21:58.204  1523  3826 I VacuumService: Vacuum at: now=1468588918204 tag=VacuumService
07-15 15:21:58.279  1523  3827 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
07-15 15:21:58.281  1523  3827 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
07-15 15:21:58.300  1523  3827 W Uploader:  no longer exists, so no auth token.
07-15 15:21:58.474  3821  3821 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-15 15:21:58.479  3821  3821 D AndroidRuntime: CheckJNI is OFF
07-15 15:21:58.523  3821  3821 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-15 15:21:58.571  3821  3821 I Radio-JNI: register_android_hardware_Radio DONE
07-15 15:21:58.592  3821  3821 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-15 15:21:58.596   874  1758 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-15 15:21:58.652   874  1758 I ActivityManager: Start proc 3840:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-15 15:21:58.660  3821  3821 D AndroidRuntime: Shutting down VM
07-15 15:21:58.711  1523  3827 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
07-15 15:21:58.711  1523  3827 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-15 15:21:58.712  1523  3827 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:21:58.712  1523  3827 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-15 15:21:58.729  1523  3827 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-15 15:21:58.729  1523  3827 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-15 15:21:58.729  1523  3827 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-15 15:21:58.729  1523  3827 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-15 15:21:58.729  1523  3827 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-15 15:21:58.729  1523  3827 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-15 15:21:58.729  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-15 15:21:58.729  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-15 15:21:58.729  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-15 15:21:58.729  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-15 15:21:58.729  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-15 15:21:58.729  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-15 15:21:58.729  1523  3827 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
07-15 15:21:58.732  3840  3840 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
07-15 15:21:58.758  3840  3840 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
07-15 15:21:58.765  3840  3840 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1751-1754)
07-15 15:21:58.765  3840  3840 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-15 15:21:58.786  3840  3840 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3a8f718}
07-15 15:21:58.786  3840  3840 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-15 15:21:58.787  3840  3840 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-15 15:21:58.796  3840  3840 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-15 15:21:58.797  3840  3840 E SysUtils: ApplicationContext is null in ApplicationStatus
07-15 15:21:58.816  3840  3840 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-15 15:21:58.831  3840  3840 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-15 15:21:58.831  3840  3840 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-15 15:21:58.831  3840  3840 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-15 15:21:58.831  3840  3840 I Adreno  : Build Date                       : 10/20/15
07-15 15:21:58.831  3840  3840 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-15 15:21:58.831  3840  3840 I Adreno  : Local Branch                     : M14
07-15 15:21:58.831  3840  3840 I Adreno  : Remote Branch                    : 
07-15 15:21:58.831  3840  3840 I Adreno  : Remote Branch                    : 
07-15 15:21:58.831  3840  3840 I Adreno  : Reconstruct Branch               : 
,07-15 15:21:58.899   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@83ac328:true
07-15 15:21:58.945  3840  3840 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-15 15:21:58.957  3840  3840 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
07-15 15:21:59.018  3840  3878 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
07-15 15:21:59.036  3840  3865 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
07-15 15:21:59.081  3840  3878 I OpenGLRenderer: Initialized EGL, version 1.4
07-15 15:21:59.161   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +475ms (total +546ms)
07-15 15:21:59.163  1662  1662 I Keyboard.Facilitator: onFinishInput()
07-15 15:21:59.197  1523  3827 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
07-15 15:21:59.197  1523  3827 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-15 15:21:59.197  1523  3827 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:21:59.197  1523  3827 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-15 15:21:59.209  1523  3827 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-15 15:21:59.209  1523  3827 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-15 15:21:59.209  1523  3827 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-15 15:21:59.209  1523  3827 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-15 15:21:59.209  1523  3827 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-15 15:21:59.209  1523  3827 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-15 15:21:59.209  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-15 15:21:59.209  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-15 15:21:59.209  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-15 15:21:59.209  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-15 15:21:59.209  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-15 15:21:59.209  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-15 15:21:59.209  1523  3827 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
07-15 15:21:59.224  3840  3840 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3840
07-15 15:21:59.336  3840  3840 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-15 15:21:59.455  1523  3827 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
07-15 15:21:59.455  1523  3827 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-15 15:21:59.455  1523  3827 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:21:59.455  1523  3827 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-15 15:21:59.468  1523  3827 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-15 15:21:59.468  1523  3827 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-15 15:21:59.468  1523  3827 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-15 15:21:59.468  1523  3827 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-15 15:21:59.468  1523  3827 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-15 15:21:59.468  1523  3827 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-15 15:21:59.468  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-15 15:21:59.468  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-15 15:21:59.468  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-15 15:21:59.468  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-15 15:21:59.468  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-15 15:21:59.468  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-15 15:21:59.468  1523  3827 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
07-15 15:21:59.534  3840  3880 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1694959312
07-15 15:21:59.544  3840  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-15 15:21:59.544  3840  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-15 15:21:59.544  3840  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-15 15:21:59.544  3840  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-15 15:21:59.544  3840  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-15 15:21:59.544  3840  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@399a28f added. We now have 1 listener(s)
07-15 15:21:59.553  3840  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
07-15 15:21:59.558  3840  3880 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-15 15:21:59.559  3840  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:21:59.560  3840  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-15 15:21:59.571  3840  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-15 15:21:59.571  3840  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-15 15:21:59.571  3840  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-15 15:21:59.571  3840  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
07-15 15:21:59.571  3840  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-15 15:21:59.571  3840  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-15 15:21:59.571  3840  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-15 15:21:59.571  3840  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-15 15:21:59.571  3840  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-15 15:21:59.571  3840  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-15 15:21:59.571  3840  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-15 15:21:59.571  3840  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d81afa added. We now have 1 listener(s)
07-15 15:21:59.572  3840  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:21:59.583   874  1315 D WifiService: New client listening to asynchronous messages
07-15 15:21:59.589  3840  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
07-15 15:21:59.590  3840  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-15 15:21:59.590  3840  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-15 15:21:59.591  3840  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-15 15:21:59.591  3840  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-15 15:21:59.593  3840  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:21:59.594  3840  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
07-15 15:21:59.606  3840  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:21:59.606  3840  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:59.606  3840  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:21:59.606  3840  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:21:59.606  3840  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:21:59.606  3840  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-15 15:21:59.606  3840  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-15 15:21:59.606  3840  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-15 15:21:59.607  3840  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-15 15:21:59.607  3840  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
07-15 15:21:59.609  3840  3880 I io.jxcore.node.LifeCycleMonitor: start: OK
07-15 15:21:59.610  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:21:59.611  3840  3880 D io.jxcore.node.JXcoreExtension: Unit Tests on
07-15 15:21:59.613  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:21:59.645  3840  3840 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
07-15 15:21:59.799   874  1314 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
07-15 15:21:59.979  1523  3827 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
07-15 15:21:59.979  1523  3827 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-15 15:21:59.979  1523  3827 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:21:59.979  1523  3827 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-15 15:21:59.996  1523  3827 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-15 15:21:59.996  1523  3827 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-15 15:21:59.996  1523  3827 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-15 15:21:59.996  1523  3827 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-15 15:21:59.996  1523  3827 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-15 15:21:59.996  1523  3827 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-15 15:21:59.996  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-15 15:21:59.996  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-15 15:21:59.996  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-15 15:21:59.996  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-15 15:21:59.996  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-15 15:21:59.996  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-15 15:21:59.996  1523  3827 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,07-15 15:22:00.113  1523  3827 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
07-15 15:22:00.113  1523  3827 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-15 15:22:00.113  1523  3827 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:22:00.113  1523  3827 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-15 15:22:00.124  1523  3827 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-15 15:22:00.124  1523  3827 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-15 15:22:00.124  1523  3827 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-15 15:22:00.124  1523  3827 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-15 15:22:00.124  1523  3827 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-15 15:22:00.124  1523  3827 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-15 15:22:00.124  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-15 15:22:00.124  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-15 15:22:00.124  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-15 15:22:00.124  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-15 15:22:00.124  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-15 15:22:00.124  1523  3827 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-15 15:22:00.124  1523  3827 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
07-15 15:22:00.430  3840  3888 W jxcore-log: Initializing JXcore engine
07-15 15:22:00.430  3840  3888 W jxcore-log: JXcore engine is ready
07-15 15:22:00.464  3888  3888 W Thread-354: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8930 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
07-15 15:22:00.464  3888  3888 W Thread-354: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10504]" dev="sockfs" ino=10504 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-15 15:22:00.464  3888  3888 W Thread-354: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-15 15:22:00.464  3888  3888 W Thread-354: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25858]" dev="sockfs" ino=25858 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
07-15 15:22:00.480  3840  3888 W jxcore-log: Starting JXcore engine
07-15 15:22:00.560  3840  3888 W jxcore-log: Platform android
07-15 15:22:00.560  3840  3888 W jxcore-log: 
07-15 15:22:00.560  3840  3888 W jxcore-log: Process ARCH arm
07-15 15:22:00.560  3840  3888 W jxcore-log: 
07-15 15:22:00.753  3840  3888 I jxcore-log: JXcore Cordova bridge is ready!
07-15 15:22:00.753  3840  3888 I jxcore-log: 
07-15 15:22:00.753  3840  3888 W jxcore-log: JXcore engine is started
07-15 15:22:00.762  3840  3880 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-15 15:22:00.765  3840  3840 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-15 15:22:03.328   874  1966 D NetlinkSocketObserver: NeighborEvent{elapsedMs=166317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-15 15:22:10.923  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-15 15:22:10.923  3840  3888 I jxcore-log: 
,07-15 15:22:10.926  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-15 15:22:10.926  3840  3888 I jxcore-log: 
,07-15 15:22:10.939  3840  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:22:10.939  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:10.939  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:10.939  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:10.939  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:10.939  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-15 15:22:10.939  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-15 15:22:10.939  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-15 15:22:10.945  3840  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-15 15:22:10.948  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-15 15:22:10.948  3840  3888 I jxcore-log: 
,07-15 15:22:10.949  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-15 15:22:10.949  3840  3888 I jxcore-log: 
,07-15 15:22:11.296  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-15 15:22:11.296  3840  3888 I jxcore-log: 
,07-15 15:22:11.300  3840  3888 D ExecuteNativeTests: Running unit tests
,07-15 15:22:11.316  3840  3840 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-15 15:22:11.363  3840  3888 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,07-15 15:22:11.363  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,07-15 15:22:11.363  3840  3888 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,07-15 15:22:11.363  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,07-15 15:22:11.363  3840  3888 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,07-15 15:22:11.363  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-15 15:22:11.365  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,07-15 15:22:11.365  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,07-15 15:22:11.366  3840  3888 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,07-15 15:22:11.366  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-15 15:22:11.366  3840  3888 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,07-15 15:22:11.366  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-15 15:22:11.366  3840  3888 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,07-15 15:22:11.366  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-15 15:22:11.367  3840  3888 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,07-15 15:22:11.368  3840  3888 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,07-15 15:22:11.368  3840  3888 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-15 15:22:11.368  3840  3888 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-15 15:22:11.368  3840  3888 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-15 15:22:11.369  3840  3888 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-15 15:22:11.370  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-15 15:22:11.370  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4af7a0e added. We now have 2 listener(s)
,07-15 15:22:11.370  3840  3888 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:22:11.373  3840  3888 D BluetoothAdapter: enable(): BT is already enabled..!
07-15 15:22:11.374   874  1758 D WifiService: setWifiEnabled: true pid=3840, uid=10000
07-15 15:22:11.374   874  1758 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-15 15:22:11.376  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:22:11.376  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@abb6c2f added. We now have 3 listener(s)
07-15 15:22:11.376  3840  3888 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-15 15:22:11.392  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-15 15:22:11.392  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@81d923c added. We now have 4 listener(s)
07-15 15:22:11.392  3840  3888 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-15 15:22:11.397  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:22:11.398  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d8dbbc5 added. We now have 5 listener(s)
,07-15 15:22:11.398  3840  3888 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-15 15:22:11.402   874  1706 D WifiService: setWifiEnabled: false pid=3840, uid=10000
07-15 15:22:11.402   874  1706 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-15 15:22:11.410  2604  2628 D BluetoothAdapterState: Current state: ON, message: 23
,07-15 15:22:11.411  2604  2628 D BluetoothAdapterProperties: Setting state to 13
07-15 15:22:11.411  2604  2628 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-15 15:22:11.410  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-15 15:22:11.416  2604  2628 D BluetoothAdapterProperties: onBluetoothDisable()
,07-15 15:22:11.423  2604  2638 D BluetoothAdapterProperties: Scan Mode:20
,07-15 15:22:11.424  2604  2628 I BluetoothAdapterState: Entering PendingCommandState
07-15 15:22:11.424  2604  2628 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,07-15 15:22:11.424  3840  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:22:11.424  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:11.424  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:11.424  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:11.424  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:22:11.424  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-15 15:22:11.424  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-15 15:22:11.424  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-15 15:22:11.426  3840  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-15 15:22:11.426  3840  3888 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-15 15:22:11.431  2604  2604 D HeadsetService: Received stop request...Stopping profile...
,07-15 15:22:11.433   874   874 D BluetoothHeadset: Proxy object disconnected
,07-15 15:22:11.433   874   874 D BluetoothHeadset: Proxy object disconnected
07-15 15:22:11.433   874   874 D BluetoothHeadset: Proxy object disconnected
,07-15 15:22:11.434  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:22:11.434  1745  1756 D BluetoothHeadset: Proxy object disconnected
,07-15 15:22:11.434  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1,
,07-15 15:22:11.434  1359  2063 D BluetoothHeadset: Proxy object disconnected
,07-15 15:22:11.435  1359  1359 D HeadsetProfile: Bluetooth service disconnected
,07-15 15:22:11.435   874  1314 D WifiStateMachine: WifiStateMachine: Leaving Connected state
07-15 15:22:11.436   874  1314 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
07-15 15:22:11.436   874  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-15 15:22:11.436   874  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,07-15 15:22:11.436  2604  2604 D A2dpService: Received stop request...Stopping profile...
07-15 15:22:11.436  2604  2719 D A2dpStateMachine: Exit Disconnected: -1
,07-15 15:22:11.437  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:11.443   874   874 D BluetoothA2dp: Proxy object disconnected
,07-15 15:22:11.443  1359  1359 D BluetoothA2dp: Proxy object disconnected
,07-15 15:22:11.444  2604  2604 V BluetoothAdapterState: isTurningOff()=true
07-15 15:22:11.444  2604  2604 V BluetoothAdapterState: isTurningOn()=false
07-15 15:22:11.445  2604  2604 V BluetoothAdapterState: isBleTurningOn()=false
,07-15 15:22:11.445  2604  2604 V BluetoothAdapterState: isBleTurningOff()=false
,07-15 15:22:11.445  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:11.445  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:11.445  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:11.445  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:11.445  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:22:11.445  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-15 15:22:11.445  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-15 15:22:11.445  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-15 15:22:11.446  3840  3840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-15 15:22:11.447  2604  2604 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,07-15 15:22:11.447  2604  2604 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,07-15 15:22:11.447  2604  2638 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-15 15:22:11.447  2604  2707 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-15 15:22:11.448  2604  2707 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-15 15:22:11.448  2604  2707 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-15 15:22:11.448  2604  2604 D HidService: Received stop request...Stopping profile...,
07-15 15:22:11.448  2604  2604 D HidService: Stopping Bluetooth HidService
07-15 15:22:11.450  1359  1359 D BluetoothInputDevice: Proxy object disconnected
,07-15 15:22:11.450  1359  1359 D HidProfile: Bluetooth service disconnected
07-15 15:22:11.450  2604  2638 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
07-15 15:22:11.450  2604  2604 V BluetoothAdapterState: isTurningOff()=true
07-15 15:22:11.450  2604  2604 V BluetoothAdapterState: isTurningOn()=false
07-15 15:22:11.450  2604  2604 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:11.451  2604  2604 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:11.451  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:11.452  2604  2707 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-15 15:22:11.453  2604  2707 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-15 15:22:11.453  2604  2707 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,07-15 15:22:11.453  2604  2707 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,07-15 15:22:11.453  2604  2707 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,07-15 15:22:11.453  2604  2707 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-15 15:22:11.453  2604  2638 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-15 15:22:11.454  2604  2604 D HealthService: Received stop request...Stopping profile...
,07-15 15:22:11.454   874  1314 E native  : do suspend true
,07-15 15:22:11.456  2604  2604 V BluetoothAdapterState: isTurningOff()=true
07-15 15:22:11.456  2604  2604 V BluetoothAdapterState: isTurningOn()=false
,07-15 15:22:11.456  2604  2604 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:11.456  2604  2604 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:11.456  2604  2604 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-15 15:22:11.456  2604  2638 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-15 15:22:11.457  2604  2604 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-15 15:22:11.457  2604  2604 D PanService: Received stop request...Stopping profile...
07-15 15:22:11.458  1359  1359 D BluetoothPan: BluetoothPAN Proxy object disconnected
,07-15 15:22:11.458  1359  1359 D PanProfile: Bluetooth service disconnected
07-15 15:22:11.459  2604  2604 D BluetoothMapService: Received stop request...Stopping profile...
07-15 15:22:11.459  2604  2604 D BluetoothMapService: stop()
,07-15 15:22:11.460  2604  2604 D BluetoothMapAppObserver: deinitObservers()
07-15 15:22:11.460  2604  2604 D BluetoothMapAppObserver: removeReceiver()
,07-15 15:22:11.469   874  1968 D DhcpClient: Clearing IP address
07-15 15:22:11.469   371   872 D CommandListener: Clearing all IP addresses on wlan0
07-15 15:22:11.471   371   872 D CommandListener: Setting iface cfg
07-15 15:22:11.472   874   887 I ActivityManager: Start proc 3892:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,07-15 15:22:11.473   874  1972 D DhcpClient: Receive thread stopped
,07-15 15:22:11.474  2604  2604 V BluetoothAdapterState: isTurningOff()=true
07-15 15:22:11.474  2604  2604 V BluetoothAdapterState: isTurningOn()=false
07-15 15:22:11.474  2604  2604 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:11.474  2604  2604 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:11.474  2604  2604 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,07-15 15:22:11.475  2604  2604 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-15 15:22:11.475  2604  2604 V BluetoothAdapterState: isTurningOff()=true
07-15 15:22:11.475  2604  2604 V BluetoothAdapterState: isTurningOn()=false
,07-15 15:22:11.475  2604  2604 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:11.475  2604  2604 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:11.475  2604  2638 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-15 15:22:11.475  2604  2604 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-15 15:22:11.475  2604  2604 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-15 15:22:11.477  1523  2398 V NativeCrypto: Read error: ssl=0x9b485e00: I/O error during system call, Connection timed out
,07-15 15:22:11.478  2604  2604 D BluetoothMapService: MAP Service closeService in
07-15 15:22:11.478  2604  2604 D BluetoothMapMasInstance0: MAP Service shutdown
07-15 15:22:11.478  2604  2604 D ObexServerSockets0: shutdown(block = true)
07-15 15:22:11.479  2604  2604 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-15 15:22:11.479  2604  2731 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-15 15:22:11.479  2604  2730 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-15 15:22:11.480  2604  2713 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-15 15:22:11.480  2604  2604 D ObexServerSockets0: shutdown called from another thread - interrupt().
,07-15 15:22:11.480  2604  2604 V BluetoothAdapterState: isTurningOff()=true
07-15 15:22:11.480  2604  2604 V BluetoothAdapterState: isTurningOn()=false
,07-15 15:22:11.480  2604  2604 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:11.481  2604  2604 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:11.481  2604  2628 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-15 15:22:11.481  2604  2628 D BluetoothAdapterProperties: Setting state to 15
07-15 15:22:11.481  2604  2628 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-15 15:22:11.481   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-15 15:22:11.481   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
07-15 15:22:11.481   874  1314 D WifiStateMachine: Start Disconnecting Watchdog 1
07-15 15:22:11.481  1359  2063 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-15 15:22:11.482  1359  1384 D BluetoothMap: onBluetoothStateChange: up=false
07-15 15:22:11.482   874  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-15 15:22:11.482  2604  2628 I BluetoothAdapterState: Entering BleOnState
07-15 15:22:11.482   874  1314 E native  : do suspend true
07-15 15:22:11.482  2604  2604 D BluetoothMapService: cleanup()
07-15 15:22:11.482  2604  2604 D BluetoothMapService: MAP Service closeService in
07-15 15:22:11.483  2604  2604 I BtOppRfcommListener: stopping Accept Thread
07-15 15:22:11.483  2604  3407 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-15 15:22:11.484  2604  3407 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-15 15:22:11.485   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
07-15 15:22:11.485   874  1316 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,07-15 15:22:11.485   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
07-15 15:22:11.485  1359  1384 D BluetoothA2dp: onBluetoothStateChange: up=false
07-15 15:22:11.486   399   399 E Parcel  : Reading a NULL string not supported here.
07-15 15:22:11.487   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
07-15 15:22:11.487   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
07-15 15:22:11.487  1359  2063 D BluetoothHeadset: onBluetoothStateChange: up=false
07-15 15:22:11.487  1745  1937 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-15 15:22:11.487  1359  1385 D BluetoothPan: onBluetoothStateChange on: false
07-15 15:22:11.488  1359  1384 D BluetoothPbap: onBluetoothStateChange: up=false
07-15 15:22:11.490  2604  2628 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-15 15:22:11.490  2604  2628 D BluetoothAdapterProperties: Setting state to 16
07-15 15:22:11.490  2604  2628 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-15 15:22:11.491  2604  2628 D BluetoothAdapterProperties: onBleDisable
07-15 15:22:11.491  2604  2628 I BluetoothAdapterState: Entering PendingCommandState
07-15 15:22:11.491  2604  2632 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,07-15 15:22:11.492  2604  2638 D BluetoothAdapterProperties: Scan Mode:20
07-15 15:22:11.492  2604  2707 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-15 15:22:11.492  2604  2707 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-15 15:22:11.494  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:11.494  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:11.494  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:11.494  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:11.494  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:22:11.494  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:11.494  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:11.494  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:22:11.495  3840  3840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:22:11.495  1523  2398 V NativeCrypto: SSL shutdown failed: ssl=0x9b485e00: I/O error during system call, Broken pipe
,07-15 15:22:11.496  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:11.496  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:11.496  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:11.496  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:11.496  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:22:11.496  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:11.496  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:11.496  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:22:11.497  3840  3840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-15 15:22:11.528   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-15 15:22:11.530  3892  3892 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,07-15 15:22:11.539  3892  3892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-15 15:22:11.546  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-15 15:22:11.548   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-15 15:22:11.548   371   872 D CommandListener: Clearing all IP addresses on wlan0
07-15 15:22:11.549   874  1316 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-15 15:22:11.549   874  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-15 15:22:11.550   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8ae0ec9:true
,07-15 15:22:11.561   874  2033 I ActivityManager: Start proc 3908:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,07-15 15:22:11.562   874   891 D Tethering: MasterInitialState.processMessage what=3
,07-15 15:22:11.564   874  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-15 15:22:11.565  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:22:11.567  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:11.570  3408  3408 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@18bf91c and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,07-15 15:22:11.585   874  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,07-15 15:22:11.588  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:11.588  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:11.588  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:11.588  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:22:11.588  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:22:11.588  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:11.588  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:11.588  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:22:11.589  3840  3840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-15 15:22:11.589   874  1314 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,07-15 15:22:11.590  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:11.590  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:11.590  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:11.590  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:22:11.590  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:22:11.590  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:11.590  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:11.590  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:22:11.591  3840  3840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-15 15:22:11.592  1950  2112 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-15 15:22:11.605  3892  3892 D LocalBluetoothProfileManager: Adding local MAP profile
,07-15 15:22:11.606  3892  3892 D BluetoothMap: Create BluetoothMap proxy object
,07-15 15:22:11.620   371   872 E Netd    : netlink response contains error (No such file or directory)
,07-15 15:22:11.620  3908  3908 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,07-15 15:22:11.623  3892  3892 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-15 15:22:11.639  3892  3892 D DockEventReceiver: finishStartingService: stopping service
,07-15 15:22:11.641   874  1421 I ActivityManager: Killing 2970:com.google.android.calendar/u0a37 (adj 15): empty #17
,07-15 15:22:11.696  2604  2638 I bt_hci  : shut_down
,07-15 15:22:11.696  2604  2644 D bt_hwcfg: hw_epilog_process
,07-15 15:22:11.698  2604  2644 I bt_vendor: low_power_mode_cb
,07-15 15:22:11.720  2604  2644 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-15 15:22:11.721  2604  2644 I bt_vendor: epilog_cb
,07-15 15:22:11.721  2604  2644 I bt_hci  : epilog_finished_callback
,07-15 15:22:11.724  2604  2638 I bt_hci_h4: hal_close
,07-15 15:22:11.724  2604  2638 I bt_userial_vendor: device fd = 51 close
,07-15 15:22:11.810  3908  3908 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at java.io.File.exists(File.java:361)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-15 15:22:11.810  3908  3908 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-15 15:22:11.810  3908  3908 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-15 15:22:11.810  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-15 15:22:11.811  3908  3908 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.r.e.b(PG:170)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-15 15:22:11.811  3908  3908 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.r.k.c(PG:18147)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.r.k.d(PG:583)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.r.e.b(PG:170)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-15 15:22:11.811  3908  3908 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at java.io.File.exists(File.java:361)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-15 15:22:11.811  3908  3908 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at java.io.File.exists(File.java:361)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-15 15:22:11.811  3908  3908 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at java.io.File.lastModified(File.java:569)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-15 15:22:11.811  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-15 15:22:11.819  3892  3892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-15 15:22:11.826  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-15 15:22:11.829  3892  3892 D DockEventReceiver: finishStartingService: stopping service
,07-15 15:22:11.851   874  1702 I ActivityManager: Killing 3408:com.google.android.music:main/u0a66 (adj 15): empty #17
,07-15 15:22:11.908  2604  2632 D bt_stack_manager: event_shut_down_stack finished.
07-15 15:22:11.909  2604  2628 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,07-15 15:22:11.910  1973  1973 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
07-15 15:22:11.912  2604  2604 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-15 15:22:11.912  2604  2628 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,07-15 15:22:11.921  2604  2604 D BtGatt.GattService: Received stop request...Stopping profile...
,07-15 15:22:11.921  1973  1973 D SystemUpdateService: onCreate
,07-15 15:22:11.921  2604  2604 D BtGatt.GattService: stop()
,07-15 15:22:11.922  2604  2604 D BtGatt.AdvertiseManager: advertise clients cleared
,07-15 15:22:11.937  2604  2604 V BluetoothAdapterState: isTurningOff()=false
,07-15 15:22:11.937  2604  2604 V BluetoothAdapterState: isTurningOn()=false
07-15 15:22:11.937  2604  2604 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:11.937  2604  2604 V BluetoothAdapterState: isBleTurningOff()=true
,07-15 15:22:11.937  2604  2628 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-15 15:22:11.937  1973  1973 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,07-15 15:22:11.937  2604  2628 D BluetoothAdapterProperties: Setting state to 10
07-15 15:22:11.937  2604  2628 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10,
07-15 15:22:11.938  2604  2628 I BluetoothAdapterState: Entering OffState
07-15 15:22:11.939   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,07-15 15:22:11.952  2604  2604 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-15 15:22:11.952  2604  2604 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-15 15:22:11.952  2604  2604 I BluetoothServiceJni: cleanupNative: return from cleanup
,07-15 15:22:11.953  2604  2632 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,07-15 15:22:11.955  2604  2632 D bt_stack_manager: event_clean_up_stack finished.
,07-15 15:22:11.964  1973  1973 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-15 15:22:11.965  1973  3943 I SystemUpdateService: active receiver: enabled
,07-15 15:22:11.966  1973  2348 I iu.UploadsManager: num queued entries: 0
,07-15 15:22:11.974  2604  2604 I art     : System.exit called, status: 0
,07-15 15:22:11.974  2604  2604 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-15 15:22:11.985  1973  1973 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-15 15:22:11.992  1973  1973 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-15 15:22:11.993  1973  2348 I iu.UploadsManager: num updated entries: 0
,07-15 15:22:11.994  1973  2348 I iu.SyncManager: NEXT; no task
,07-15 15:22:11.994  1973  3943 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,07-15 15:22:11.997  1973  3943 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,07-15 15:22:12.003  1973  3943 I SystemUpdateService: now status is 0 (complete)
,07-15 15:22:12.004  1973  3943 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
07-15 15:22:12.004  1973  3943 I SystemUpdateService: file has been verified
07-15 15:22:12.004  1973  3943 I SystemUpdateService: OTA package size = 12249756
,07-15 15:22:12.024  1973  3943 I SystemUpdateService: showing system update notification
,07-15 15:22:12.027   874  1393 I ActivityManager: Start proc 3946:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,07-15 15:22:12.031   874  1421 I ActivityManager: Process com.android.bluetooth (pid 2604) has died
,07-15 15:22:12.052  1973  1973 D SystemUpdateService: onDestroy
,07-15 15:22:12.086  3908  3931 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-15 15:22:12.091  3946  3946 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,07-15 15:22:12.094  3946  3946 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-15 15:22:12.101  3946  3946 D SprintDMHelper: simOperator: 
,07-15 15:22:12.101  3946  3946 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-15 15:22:12.115   874  3204 I ActivityManager: Start proc 3960:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,07-15 15:22:12.122   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d1af365:true
,07-15 15:22:12.205  3489  3974 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,07-15 15:22:12.233   874  2031 I ActivityManager: Start proc 3975:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-15 15:22:12.236   874  1702 I ActivityManager: Killing 3453:com.android.providers.calendar/u0a3 (adj 15): empty #17
,07-15 15:22:12.317  3975  3975 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,07-15 15:22:12.390  3975  3975 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-15 15:22:12.390  3975  3975 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-15 15:22:12.390  3975  3975 I GAv4    :   adb logcat -s GAv4
,07-15 15:22:12.410  3975  3975 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-15 15:22:12.419  3975  3975 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-15 15:22:12.446  3975  3992 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-15 15:22:12.566  3975  3975 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,07-15 15:22:12.594  3975  3975 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-15 15:22:12.603  3975  3975 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5589-5592)
07-15 15:22:12.603  3975  3975 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-15 15:22:12.627  3975  3975 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2cde14c}
07-15 15:22:12.628  3975  3975 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-15 15:22:12.628  3975  3975 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-15 15:22:12.635  3975  3975 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-15 15:22:12.636  3975  3975 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-15 15:22:12.656  3975  3975 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-15 15:22:12.669  3975  3975 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-15 15:22:12.669  3975  3975 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-15 15:22:12.670  3975  3975 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-15 15:22:12.670  3975  3975 I Adreno  : Build Date                       : 10/20/15
07-15 15:22:12.670  3975  3975 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-15 15:22:12.670  3975  3975 I Adreno  : Local Branch                     : M14
07-15 15:22:12.670  3975  3975 I Adreno  : Remote Branch                    : 
07-15 15:22:12.670  3975  3975 I Adreno  : Remote Branch                    : 
07-15 15:22:12.670  3975  3975 I Adreno  : Reconstruct Branch               : 
,07-15 15:22:12.723  3975  3975 I NSApplication: Starting up...
,07-15 15:22:12.750  3975  4021 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-15 15:22:12.764   874  3202 I ActivityManager: Start proc 4026:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-15 15:22:12.766   874  3202 I ActivityManager: Killing 3643:com.google.android.apps.books/u0a34 (adj 15): empty #17
,07-15 15:22:12.849  4026  4026 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-15 15:22:13.060   874  1393 I ActivityManager: Killing 3034:android.process.acore/u0a5 (adj 15): empty #17
,07-15 15:22:13.149   874  3204 I ActivityManager: Start proc 4040:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,07-15 15:22:13.227  4040  4040 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,07-15 15:22:13.271  4040  4040 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,07-15 15:22:13.302   874  1706 I ActivityManager: Killing 3690:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,07-15 15:22:14.430   874  3202 D WifiService: setWifiEnabled: true pid=3840, uid=10000
07-15 15:22:14.430   874  3202 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-15 15:22:14.445   874  1314 D WifiConfigStore: Loading config and enabling all networks 
,07-15 15:22:14.454  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:14.454  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:14.454  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:14.454  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:14.454  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:22:14.454  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:14.454  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:14.454  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:22:14.455  3840  3840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-15 15:22:14.458  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:14.458  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:14.458  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:14.458  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:14.458  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:22:14.458  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:14.458  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:14.458  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:22:14.458  3840  3840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:22:14.481   874  1314 D WifiConfigStore: loaded 0 passpoint configs
,07-15 15:22:14.481   874  1314 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-15 15:22:14.482   874  1314 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,07-15 15:22:14.482   874  1314 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-15 15:22:14.483   874  1314 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,07-15 15:22:14.483   874  1314 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,07-15 15:22:14.484   874  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,07-15 15:22:14.484   874  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-15 15:22:14.499   874  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-15 15:22:14.499   371   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,07-15 15:22:14.504   371   872 D CommandListener: Setting iface cfg
,07-15 15:22:14.510   874  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)'
,07-15 15:22:14.511   874  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-15 15:22:14.511   874  1314 E native  : do suspend true
,07-15 15:22:14.524   874  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,07-15 15:22:14.529   874  1313 D WifiNative-HAL: p2pGetDeviceAddress
,07-15 15:22:14.532   874  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,07-15 15:22:15.916   874  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-15 15:22:15.975   874  1314 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.31 rxSuccessRate=10.81 delta 1000 -> 994
,07-15 15:22:15.982   874  1314 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,07-15 15:22:15.983   874  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-15 15:22:16.008   874  1314 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,07-15 15:22:16.076   874  1314 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,07-15 15:22:16.078  1466  1466 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-15 15:22:16.494  1466  1466 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-15 15:22:16.533  1466  1466 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-15 15:22:16.534  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,07-15 15:22:16.539   874  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,07-15 15:22:16.551   874  1314 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-15 15:22:16.551   874  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-15 15:22:16.551   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-15 15:22:16.576   874  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-15 15:22:16.591   371   872 D CommandListener: Setting iface cfg
,07-15 15:22:16.597   874  1314 D WifiStateMachine: Start Dhcp Watchdog 2
,07-15 15:22:16.606   874  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[],
,07-15 15:22:16.617   874  4075 D DhcpClient: Receive thread started
,07-15 15:22:16.712   874  1314 E native  : do suspend false
,07-15 15:22:16.722   874  1968 D DhcpClient: Broadcasting DHCPDISCOVER
,07-15 15:22:16.734   874  4075 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172643, domain null
,07-15 15:22:16.735   874  1968 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172643 seconds
,07-15 15:22:16.737   874  1968 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,07-15 15:22:16.749   874  4075 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-15 15:22:16.750   874  1968 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-15 15:22:16.754   371   872 D CommandListener: Setting iface cfg
,07-15 15:22:16.758   874  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,07-15 15:22:16.763   874  1314 E native  : do suspend true
,07-15 15:22:16.764   874  1968 D DhcpClient: Scheduling renewal in 86399s
,07-15 15:22:16.776   874  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-15 15:22:16.777   874  1314 D WifiConfigStore: No blacklist allowed without epno enabled
07-15 15:22:16.778   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-15 15:22:16.779   874  1314 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-15 15:22:16.780   874  1316 D ConnectivityService: Adding iface wlan0 to network 101
,07-15 15:22:16.820  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:22:16.826  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:22:16.827  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:22:16.836   874  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-15 15:22:16.836   874  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,07-15 15:22:16.837   874  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,07-15 15:22:16.838   874  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,07-15 15:22:16.839   874  1316 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,07-15 15:22:16.845   874  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-15 15:22:16.849  1523  2101 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-15 15:22:16.849  1523  2101 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-15 15:22:16.849  1523  2101 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-15 15:22:16.849  1523  2101 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-15 15:22:16.850   874  1316 D ConnectivityService: scheduleUnvalidatedPrompt 101
07-15 15:22:16.850   874  1316 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
07-15 15:22:16.850   874  1316 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,07-15 15:22:16.850   874  1316 D ConnectivityService:    accepting network in place of null
07-15 15:22:16.850   874  1314 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-15 15:22:16.851   874  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-15 15:22:16.851   874  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-15 15:22:16.863   874  4072 D NetlinkSocketObserver: NeighborEvent{elapsedMs=179852, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-15 15:22:16.867  3526  3526 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-15 15:22:16.867  3526  3526 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-15 15:22:16.867  3526  3526 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,07-15 15:22:16.876   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-15 15:22:16.894   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-15 15:22:16.897   874  1316 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,07-15 15:22:16.897   874  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-15 15:22:16.901   874  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,07-15 15:22:16.905   874   891 D Tethering: MasterInitialState.processMessage what=3
,07-15 15:22:16.909  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:16.909  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:16.909  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:16.909  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:16.909  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:22:16.909  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-15 15:22:16.909  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-15 15:22:16.909  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-15 15:22:16.909  3840  3840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-15 15:22:16.912  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:16.912  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:16.912  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:16.912  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:16.912  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:22:16.912  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-15 15:22:16.912  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-15 15:22:16.912  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-15 15:22:16.912  3840  3840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-15 15:22:16.916  1973  1973 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,07-15 15:22:16.919  1973  1973 D SystemUpdateService: onCreate
,07-15 15:22:16.921  1973  1973 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,07-15 15:22:16.924  1973  4088 I SystemUpdateService: active receiver: enabled
,07-15 15:22:16.927   874  4071 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.20.78,2a00:1450:4001:816::200e
,07-15 15:22:16.928  1973  4088 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,07-15 15:22:16.930  1973  4088 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,07-15 15:22:16.931  1973  4088 I SystemUpdateService: now status is 0 (complete)
07-15 15:22:16.931  1973  4088 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
07-15 15:22:16.931  1973  4088 I SystemUpdateService: file has been verified
,07-15 15:22:16.932  1973  4088 I SystemUpdateService: OTA package size = 12249756
,07-15 15:22:16.940  1973  4088 I SystemUpdateService: showing system update notification
,07-15 15:22:16.976   874   886 I ActivityManager: Start proc 4089:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,07-15 15:22:16.988   874  4071 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 15 Jul 2016 13:22:16 GMT], X-Android-Received-Millis=[1468588936986], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1468588936963]}
,07-15 15:22:16.989   874  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-15 15:22:16.989   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,07-15 15:22:16.991   874  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-15 15:22:17.000   874  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-15 15:22:17.001  4089  4089 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
07-15 15:22:17.005  1973  1973 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-15 15:22:17.005  1973  1973 D SystemUpdateService: onDestroy
07-15 15:22:17.009  1973  2348 I iu.UploadsManager: num queued entries: 0
07-15 15:22:17.012  1973  2348 I iu.UploadsManager: num updated entries: 0
07-15 15:22:17.014  1973  1973 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-15 15:22:17.015  1973  1973 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-15 15:22:17.015  1973  2348 I iu.SyncManager: NEXT; no task
07-15 15:22:17.017  3946  3946 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-15 15:22:17.018  1973  4103 I MDM     : [222] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
07-15 15:22:17.019  1973  4103 W BaseAppContext: Using Auth Proxy for data requests.
,07-15 15:22:17.020  1973  4103 V GoogleAuthProtoRequest: [222] a.<init>: mAccountName set to: thalitester@gmail.com
,07-15 15:22:17.023  3946  3946 D SprintDMHelper: simOperator: 
07-15 15:22:17.023  3946  3946 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-15 15:22:17.044  1523  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
07-15 15:22:17.046  1523  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,07-15 15:22:17.046  1523  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:22:17.046  1523  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:22:17.068  1973  4103 E MDM     : [222] SitrepService.a: Error sending sitrep.
,07-15 15:22:17.095  4089  4089 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-15 15:22:17.104  4089  4089 I BooksApp: Created application version: 3.6.9 (30609)
,07-15 15:22:17.114  3489  4106 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,07-15 15:22:17.229  4089  4117 I BooksSync: Starting books sync for 61035162, extras: ade
,07-15 15:22:17.420  4089  4123 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-15 15:22:17.436   874  2033 D WifiService: setWifiEnabled: false pid=3840, uid=10000
,07-15 15:22:17.437   874  2033 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-15 15:22:17.452  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,07-15 15:22:17.453   874  1314 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,07-15 15:22:17.454   874  1314 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,07-15 15:22:17.454   874  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-15 15:22:17.455   874  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-15 15:22:17.470   874  1314 E native  : do suspend true
,07-15 15:22:17.475  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-15 15:22:17.475  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-15 15:22:17.475  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:22:17.475  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:22:17.480   874  1968 D DhcpClient: Clearing IP address
,07-15 15:22:17.482   371   872 D CommandListener: Setting iface cfg
,07-15 15:22:17.485   371   872 D CommandListener: Clearing all IP addresses on wlan0
,07-15 15:22:17.489   874  4075 D DhcpClient: Receive thread stopped
,07-15 15:22:17.494  1523  4116 V NativeCrypto: Read error: ssl=0x9aefd000: I/O error during system call, Connection timed out
,07-15 15:22:17.503  1523  4116 V NativeCrypto: SSL shutdown failed: ssl=0x9aefd000: I/O error during system call, Broken pipe
,07-15 15:22:17.504   874  2032 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,07-15 15:22:17.505   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-15 15:22:17.505   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
07-15 15:22:17.506   874  4071 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
07-15 15:22:17.507   874  4071 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on <unknown ssid>, connectivitycheck.gstatic.com=172.217.20.78,2a00:1450:4001:816::200e
07-15 15:22:17.525   399   399 E Parcel  : Reading a NULL string not supported here.
07-15 15:22:17.528   874  4071 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:816::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,07-15 15:22:17.533   874  1316 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,07-15 15:22:17.533   874  1314 D WifiStateMachine: Start Disconnecting Watchdog 2
,07-15 15:22:17.538   874  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-15 15:22:17.540   874  1314 E native  : do suspend true
,07-15 15:22:17.550  1523  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-15 15:22:17.551  1523  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-15 15:22:17.551  1523  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:22:17.551  1523  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:22:17.563  4089  4123 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-15 15:22:17.565   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-15 15:22:17.566  4089  4117 E BooksSync: Soft error
07-15 15:22:17.566  4089  4117 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-15 15:22:17.566  4089  4117 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-15 15:22:17.566  4089  4117 E BooksSync: Sync error
07-15 15:22:17.566  4089  4117 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-15 15:22:17.566  4089  4117 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-15 15:22:17.570  4089  4117 I BooksSync: Finished books sync
,07-15 15:22:17.573   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 162558, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-15 15:22:17.580   874  1758 I ActivityManager: Killing 2067:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,07-15 15:22:17.589   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-15 15:22:17.589   371   872 D CommandListener: Clearing all IP addresses on wlan0
07-15 15:22:17.590   874  1316 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,07-15 15:22:17.590   874  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-15 15:22:17.617   874  1758 I ActivityManager: Killing 3707:com.android.musicfx/u0a18 (adj 15): empty #18
,07-15 15:22:17.656   874  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-15 15:22:17.660   874   891 D Tethering: MasterInitialState.processMessage what=3
07-15 15:22:17.674  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:17.674  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:17.674  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:17.674  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:17.674  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:22:17.674  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:17.674  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:17.674  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:22:17.674  3840  3840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:22:17.676  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:17.676  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:17.676  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:17.676  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:17.676  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:22:17.676  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:17.676  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:17.676  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:22:17.676  3840  3840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-15 15:22:17.686   874  1314 D WifiConfigStore: Retrieve network priorities after PNO.
07-15 15:22:17.689  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:17.689  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:17.689  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:17.689  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:22:17.689  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:22:17.689  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:17.689  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:17.689  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:22:17.689  1950  2112 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-15 15:22:17.689  1973  1973 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
07-15 15:22:17.689  3840  3840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-15 15:22:17.690   874  1314 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-15 15:22:17.690  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:17.690  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:17.690  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:17.690  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:22:17.690  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:22:17.690  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:17.690  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:17.690  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:22:17.690  3840  3840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:22:17.696  1973  1973 D SystemUpdateService: onCreate
,07-15 15:22:17.699  1973  1973 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,07-15 15:22:17.710  1973  1973 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-15 15:22:17.716  1973  4131 I SystemUpdateService: active receiver: enabled
,07-15 15:22:17.716  1973  2348 I iu.UploadsManager: num queued entries: 0
,07-15 15:22:17.720  1973  1973 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-15 15:22:17.722  1973  1973 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-15 15:22:17.724  1973  2348 I iu.UploadsManager: num updated entries: 0
,07-15 15:22:17.725  3946  3946 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-15 15:22:17.729  3946  3946 D SprintDMHelper: simOperator: 
,07-15 15:22:17.729  3946  3946 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-15 15:22:17.738   371   872 E Netd    : netlink response contains error (No such file or directory)
,07-15 15:22:17.738  1973  4131 I SystemUpdateService: Already downloaded, skipping offpeak checks.
07-15 15:22:17.739   874  1316 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
07-15 15:22:17.739   874  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-15 15:22:17.761  1973  2348 I iu.SyncManager: NEXT; no task
,07-15 15:22:17.761  1973  4131 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,07-15 15:22:17.764  1973  4131 I SystemUpdateService: now status is 0 (complete)
,07-15 15:22:17.764  1973  4131 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
07-15 15:22:17.764  1973  4131 I SystemUpdateService: file has been verified
07-15 15:22:17.764  1973  4131 I SystemUpdateService: OTA package size = 12249756
,07-15 15:22:17.766  3489  4135 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,07-15 15:22:17.778  1973  4131 I SystemUpdateService: showing system update notification,
,07-15 15:22:17.791  1973  1973 D SystemUpdateService: onDestroy
,07-15 15:22:17.897   874  1316 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,07-15 15:22:20.499   874   891 I ActivityManager: Start proc 4138:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-15 15:22:20.647  4138  4138 D AdapterServiceConfig: Adding HeadsetService
,07-15 15:22:20.647  4138  4138 D AdapterServiceConfig: Adding A2dpService
,07-15 15:22:20.648  4138  4138 D AdapterServiceConfig: Adding HidService
,07-15 15:22:20.648  4138  4138 D AdapterServiceConfig: Adding HealthService
,07-15 15:22:20.648  4138  4138 D AdapterServiceConfig: Adding PanService
,07-15 15:22:20.648  4138  4138 D AdapterServiceConfig: Adding GattService
,07-15 15:22:20.648  4138  4138 D AdapterServiceConfig: Adding BluetoothMapService
,07-15 15:22:20.662   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e35d212:true
,07-15 15:22:20.664  4138  4138 D BluetoothAdapterState: make() - Creating AdapterState
,07-15 15:22:20.673  4138  4150 I BluetoothAdapterState: Entering OffState
,07-15 15:22:20.673  4138  4138 I bt_bluedroid: init
,07-15 15:22:20.676  4138  4151 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf,
07-15 15:22:20.676  4138  4151 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-15 15:22:20.677  4138  4151 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-15 15:22:20.677  4138  4151 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-15 15:22:20.678  4138  4138 I bt_bluedroid: get_profile_interface socket
,07-15 15:22:20.681  4138  4154 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-15 15:22:20.682  4138  4154 D BluetoothAdapterProperties: Name is: Nexus 6
,07-15 15:22:20.683  4138  4138 I bt_bluedroid: get_profile_interface sdp
,07-15 15:22:20.691  4138  4149 I bt_bluedroid: config_hci_snoop_log
,07-15 15:22:20.692   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,07-15 15:22:20.697  4138  4150 D BluetoothAdapterState: Current state: OFF, message: 0
,07-15 15:22:20.697  4138  4150 D BluetoothAdapterProperties: Setting state to 14
,07-15 15:22:20.697  4138  4150 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
07-15 15:22:20.699  4138  4150 D BluetoothBondStateMachine: make
,07-15 15:22:20.702  4138  4155 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-15 15:22:20.706  4138  4150 I BluetoothAdapterState: Entering PendingCommandState
,07-15 15:22:20.708  4138  4138 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-15 15:22:20.715  4138  4138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e109ae2
,07-15 15:22:20.718  4138  4138 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-15 15:22:20.718  4138  4138 D BtGatt.GattService: Received start request. Starting profile...
,07-15 15:22:20.719  4138  4138 D BtGatt.GattService: start()
07-15 15:22:20.719  4138  4138 I bt_bluedroid: get_profile_interface gatt,
,07-15 15:22:20.720  4138  4138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e109ae2
,07-15 15:22:20.721  4138  4138 D BtGatt.AdvertiseManager: advertise manager created
,07-15 15:22:20.730  4138  4138 V BluetoothAdapterState: isTurningOff()=false
,07-15 15:22:20.730  4138  4138 V BluetoothAdapterState: isTurningOn()=false
07-15 15:22:20.730  4138  4138 V BluetoothAdapterState: isBleTurningOn()=true
07-15 15:22:20.731  4138  4138 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:20.731  4138  4150 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,07-15 15:22:20.732  4138  4150 I bt_bluedroid: enable
07-15 15:22:20.732  4138  4151 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-15 15:22:20.733  4138  4151 I bt_hci  : start_up
,07-15 15:22:20.740  4138  4151 I bt_vendor: alloc value 0xb3a43189
,07-15 15:22:20.740  4138  4151 I bt_vendor: init
07-15 15:22:20.740  4138  4151 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-15 15:22:20.740  4138  4151 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-15 15:22:20.848  4138  4151 D bt_hci  : start_up starting async portion
,07-15 15:22:20.849  4138  4158 I bt_hci  : event_finish_startup
07-15 15:22:20.849  4138  4158 I bt_hci_h4: hal_open
,07-15 15:22:20.849  4138  4158 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-15 15:22:20.857  4138  4158 I bt_userial_vendor: device fd = 51 open
,07-15 15:22:20.891  4138  4158 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-15 15:22:20.923  4138  4158 D bt_hwcfg: Chipset BCM4354A2
07-15 15:22:20.923  4138  4158 D bt_hwcfg: Target name = [BCM4354A2]
,07-15 15:22:20.924  4138  4158 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,07-15 15:22:21.580  4138  4158 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-15 15:22:21.581  4138  4158 D bt_hwcfg: Settlement delay -- 100 ms
,07-15 15:22:21.582  4138  4158 I bt_hwcfg: Setting fw settlement delay to 100 
,07-15 15:22:21.699  4138  4158 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-15 15:22:21.701  4138  4158 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,07-15 15:22:21.729  4138  4158 I bt_hwcfg: vendor lib fwcfg completed
,07-15 15:22:21.729  4138  4158 I bt_vendor: firmware callback
07-15 15:22:21.730  4138  4158 I bt_hci  : firmware_config_callback
,07-15 15:22:21.742  4138  4160 I bt_btu  : btu_task pending for preload complete event
,07-15 15:22:21.743  4138  4160 I bt_btu_task: Bluetooth chip preload is complete
,07-15 15:22:21.743  4138  4160 I bt_btu  : btu_task received preload complete event
,07-15 15:22:21.753  4138  4160 I         : BTE_InitTraceLevels -- TRC_HCI
,07-15 15:22:21.753  4138  4160 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-15 15:22:21.753  4138  4160 I         : BTE_InitTraceLevels -- TRC_RFCOMM,
,07-15 15:22:21.754  4138  4160 I         : BTE_InitTraceLevels -- TRC_AVDT
,07-15 15:22:21.754  4138  4160 I         : BTE_InitTraceLevels -- TRC_AVRC
07-15 15:22:21.754  4138  4160 I         : BTE_InitTraceLevels -- TRC_A2D
,07-15 15:22:21.755  4138  4160 I         : BTE_InitTraceLevels -- TRC_BNEP
07-15 15:22:21.755  4138  4160 I         : BTE_InitTraceLevels -- TRC_BTM
,07-15 15:22:21.755  4138  4160 I         : BTE_InitTraceLevels -- TRC_GAP
07-15 15:22:21.757  4138  4160 I         : BTE_InitTraceLevels -- TRC_PAN
,07-15 15:22:21.757  4138  4160 I         : BTE_InitTraceLevels -- TRC_SDP
07-15 15:22:21.758  4138  4160 I         : BTE_InitTraceLevels -- TRC_GATT
,07-15 15:22:21.758  4138  4160 I         : BTE_InitTraceLevels -- TRC_SMP
07-15 15:22:21.758  4138  4160 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-15 15:22:21.759  4138  4160 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-15 15:22:21.894  4138  4160 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39c0d9d
,07-15 15:22:21.895  4138  4160 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39c0d9d 
,07-15 15:22:21.921  4138  4154 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,07-15 15:22:21.923  4138  4154 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-15 15:22:21.924  4138  4154 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-15 15:22:21.928  4138  4154 D BluetoothAdapterProperties: Name is: Nexus 6
,07-15 15:22:21.931  4138  4154 D BluetoothAdapterProperties: Scan Mode:20
,07-15 15:22:21.931  4138  4154 D BluetoothAdapterProperties: Discoverable Timeout:120
07-15 15:22:21.932  4138  4154 D bt_hci  : do_postload posting postload work item
07-15 15:22:21.932  4138  4158 I bt_hci  : event_postload
07-15 15:22:21.932  4138  4158 I bt_vendor: sco_config_cb
07-15 15:22:21.932  4138  4158 I bt_hci  : sco_config_callback postload finished.
,07-15 15:22:21.934  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:22:21.936  4138  4154 D bt_bte_conf: Device ID record 1 : primary
07-15 15:22:21.936  4138  4154 D bt_bte_conf:   vendorId            = 000f
07-15 15:22:21.936  4138  4154 D bt_bte_conf:   vendorIdSource      = 0001
07-15 15:22:21.936  4138  4154 D bt_bte_conf:   product             = 1200
,07-15 15:22:21.937  4138  4154 D bt_bte_conf:   version             = 1436
07-15 15:22:21.937  4138  4154 D bt_bte_conf:   clientExecutableURL = 
,07-15 15:22:21.937  4138  4154 D bt_bte_conf:   serviceDescription  = 
07-15 15:22:21.937  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:22:21.938  4138  4154 D bt_bte_conf:   documentationURL    = 
,07-15 15:22:21.938  4138  4154 D bt_bte_conf: bte_load_did_conf no section named DID2.
,07-15 15:22:21.939  4138  4158 I bt_vendor: low_power_mode_cb
07-15 15:22:21.938  4138  4151 D bt_stack_manager: event_start_up_stack finished
07-15 15:22:21.940  4138  4150 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-15 15:22:21.941  4138  4150 D BluetoothAdapterProperties: Setting state to 15
07-15 15:22:21.941  4138  4150 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-15 15:22:21.942  4138  4150 I BluetoothAdapterState: Entering BleOnState
,07-15 15:22:21.946  4138  4150 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-15 15:22:21.947  4138  4150 D BluetoothAdapterProperties: Setting state to 11
07-15 15:22:21.947  4138  4150 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,07-15 15:22:21.958  4138  4138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e109ae2
07-15 15:22:21.958  4138  4138 D HeadsetService: Received start request. Starting profile...
07-15 15:22:21.962  4138  4138 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-15 15:22:21.962  4138  4138 D HeadsetStateMachine: make
,07-15 15:22:21.969  4138  4150 I BluetoothAdapterState: Entering PendingCommandState
,07-15 15:22:21.972  4138  4138 D HeadsetStateMachine: max_hf_connections = 1
,07-15 15:22:21.972  4138  4138 I bt_bluedroid: get_profile_interface handsfree
,07-15 15:22:21.973  4138  4154 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,07-15 15:22:21.973  4138  4154 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,07-15 15:22:21.978  4138  4138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e109ae2
,07-15 15:22:21.978  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-15 15:22:21.979  4138  4138 D A2dpService: Received start request. Starting profile...
07-15 15:22:21.980  4138  4138 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-15 15:22:21.980  4138  4138 I bt_bluedroid: get_profile_interface avrcp
,07-15 15:22:21.989  4138  4138 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-15 15:22:21.989  4138  4138 I BluetoothA2dpServiceJni: classInitNative: succeeds
,07-15 15:22:21.989  4138  4138 D A2dpStateMachine: make
,07-15 15:22:21.991  4138  4138 I bt_bluedroid: get_profile_interface a2dp
,07-15 15:22:21.992  4138  4154 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,07-15 15:22:21.995  4138  4169 D A2dpStateMachine: Enter Disconnected: -2
,07-15 15:22:21.996  4138  4138 I BluetoothHidServiceJni: classInitNative: succeeds
07-15 15:22:21.997  4138  4138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e109ae2
,07-15 15:22:21.999  3892  3892 D BluetoothInputDevice: Proxy object connected
07-15 15:22:21.999  4138  4138 D HidService: Received start request. Starting profile...
07-15 15:22:21.999  4138  4138 I bt_bluedroid: get_profile_interface hidhost
,07-15 15:22:21.999  4138  4154 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39a23e5
07-15 15:22:21.999  4138  4138 D HidService: setHidService(): set to: null
07-15 15:22:21.999  4138  4154 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-15 15:22:22.000  3892  3892 D HidProfile: Bluetooth service connected
,07-15 15:22:22.000  4138  4138 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-15 15:22:22.002  4138  4138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e109ae2
,07-15 15:22:22.003  4138  4138 D HealthService: Received start request. Starting profile...
,07-15 15:22:22.005  4138  4138 I bt_bluedroid: get_profile_interface health
,07-15 15:22:22.007  4138  4138 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-15 15:22:22.009  4138  4138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e109ae2
,07-15 15:22:22.011  3892  3892 D BluetoothPan: BluetoothPAN Proxy object connected
,07-15 15:22:22.011  4138  4138 D PanService: Received start request. Starting profile...
,07-15 15:22:22.011  4138  4138 D BluetoothPanServiceJni: initializeNative(L110): pan
07-15 15:22:22.011  4138  4138 I bt_bluedroid: get_profile_interface pan
07-15 15:22:22.011  3892  3892 D PanProfile: Bluetooth service connected
07-15 15:22:22.012  4138  4154 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-15 15:22:22.015  4138  4138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e109ae2
07-15 15:22:22.016  3892  3892 D BluetoothMap: Proxy object connected
07-15 15:22:22.016  4138  4138 D BluetoothMapService: Received start request. Starting profile...
07-15 15:22:22.016  4138  4138 D BluetoothMapService: start()
07-15 15:22:22.016  3892  3892 D MapProfile: Bluetooth service connected
07-15 15:22:22.016  3892  3892 D BluetoothMap: getConnectedDevices()
07-15 15:22:22.017  3892  3892 D BluetoothMap: Bluetooth is Not enabled
,07-15 15:22:22.020  4138  4138 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,07-15 15:22:22.021  4138  4138 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,07-15 15:22:22.021  4138  4138 D BluetoothMapAppObserver: createReceiver()
,07-15 15:22:22.024  4138  4138 D BluetoothMapAppObserver: initObservers()
,07-15 15:22:22.024  4138  4138 D BluetoothMapAppObserver: getEnabledAccountItems()
07-15 15:22:22.035  4138  4138 V BluetoothAdapterState: isTurningOff()=false
07-15 15:22:22.035  4138  4138 V BluetoothAdapterState: isTurningOn()=true
07-15 15:22:22.035  4138  4138 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:22.036  4138  4138 V BluetoothAdapterState: isBleTurningOff()=false
,07-15 15:22:22.040  4138  4167 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-15 15:22:22.042  4138  4138 V BluetoothAdapterState: isTurningOff()=false
07-15 15:22:22.042  4138  4138 V BluetoothAdapterState: isTurningOn()=true
,07-15 15:22:22.042  4138  4138 V BluetoothAdapterState: isBleTurningOn()=false
,07-15 15:22:22.043  4138  4138 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:22.043  4138  4138 V BluetoothAdapterState: isTurningOff()=false
07-15 15:22:22.043  4138  4138 V BluetoothAdapterState: isTurningOn()=true
,07-15 15:22:22.043  4138  4138 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:22.043  4138  4138 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:22.043  4138  4138 V BluetoothAdapterState: isTurningOff()=false
07-15 15:22:22.044  4138  4138 V BluetoothAdapterState: isTurningOn()=true
07-15 15:22:22.044  4138  4138 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:22.044  4138  4138 V BluetoothAdapterState: isBleTurningOff()=false
,07-15 15:22:22.044  4138  4138 V BluetoothAdapterState: isTurningOff()=false
07-15 15:22:22.044  4138  4138 V BluetoothAdapterState: isTurningOn()=true
07-15 15:22:22.044  4138  4138 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:22.044  4138  4138 V BluetoothAdapterState: isBleTurningOff()=false
,07-15 15:22:22.045  4138  4138 V BluetoothAdapterState: isTurningOff()=false
07-15 15:22:22.045  4138  4138 V BluetoothAdapterState: isTurningOn()=true
07-15 15:22:22.045  4138  4138 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:22.045  4138  4138 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:22.046  4138  4150 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-15 15:22:22.046  4138  4150 D BluetoothAdapterProperties: ScanMode =  20
,07-15 15:22:22.046  4138  4150 D BluetoothAdapterProperties: State =  11
07-15 15:22:22.046  4138  4150 D BluetoothAdapterProperties: Setting state to 12
07-15 15:22:22.046  4138  4150 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-15 15:22:22.047  4138  4150 I BluetoothAdapterState: Entering OnState
,07-15 15:22:22.047  1359  2063 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-15 15:22:22.048  4138  4154 D BluetoothAdapterProperties: Scan Mode:21
,07-15 15:22:22.048  4138  4154 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-15 15:22:22.050  1359  1359 D BluetoothInputDevice: Proxy object connected
,07-15 15:22:22.050  1359  1359 D HidProfile: Bluetooth service connected
07-15 15:22:22.050  1359  1385 D BluetoothMap: onBluetoothStateChange: up=true
07-15 15:22:22.053  1359  1359 D BluetoothMap: Proxy object connected
07-15 15:22:22.053  1359  1359 D MapProfile: Bluetooth service connected
07-15 15:22:22.053  1359  1359 D BluetoothMap: getConnectedDevices()
,07-15 15:22:22.053  3892  3904 D BluetoothPan: onBluetoothStateChange on: true
07-15 15:22:22.053   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-15 15:22:22.053  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:22.053  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:22.053  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:22.053  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:22:22.053  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:22.053  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:22.053  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:22.053  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:22:22.054   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
07-15 15:22:22.054  3892  3903 D BluetoothMap: onBluetoothStateChange: up=true
07-15 15:22:22.054  1359  2063 D BluetoothA2dp: onBluetoothStateChange: up=true
07-15 15:22:22.055  4138  4138 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-15 15:22:22.056  3892  3904 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-15 15:22:22.056  4138  4138 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-15 15:22:22.056  3892  3903 D BluetoothPbap: onBluetoothStateChange: up=true
,07-15 15:22:22.057   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-15 15:22:22.057   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-15 15:22:22.057  4138  4138 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-15 15:22:22.058  1359  1384 D BluetoothHeadset: onBluetoothStateChange: up=true
07-15 15:22:22.060  1745  1756 D BluetoothHeadset: onBluetoothStateChange: up=true
07-15 15:22:22.062  1359  1385 D BluetoothPan: onBluetoothStateChange on: true
07-15 15:22:22.062  3840  3840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-15 15:22:22.063  4138  4138 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-15 15:22:22.064  1359  1359 D BluetoothPan: BluetoothPAN Proxy object connected
07-15 15:22:22.064  1359  1359 D PanProfile: Bluetooth service connected
07-15 15:22:22.064  1359  1384 D BluetoothPbap: onBluetoothStateChange: up=true
07-15 15:22:22.065  4138  4138 D ObexServerSockets: Succeed to create listening sockets 
,07-15 15:22:22.065  4138  4138 D ObexServerSockets0: startAccept()
07-15 15:22:22.065  4138  4138 D ObexServerSockets0: prepareForNewConnect()
07-15 15:22:22.067   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
07-15 15:22:22.068  4138  4138 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-15 15:22:22.068  4138  4138 D BluetoothSdpJni: SDP Create record success - handle: 0
07-15 15:22:22.069  4138  4176 D ObexServerSockets0: Accepting socket connection...
07-15 15:22:22.070   874   874 D BluetoothA2dp: Proxy object connected
,07-15 15:22:22.070  1359  1359 D BluetoothA2dp: Proxy object connected
07-15 15:22:22.070  4138  4138 D BluetoothMapService: onReceive
07-15 15:22:22.070  4138  4138 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-15 15:22:22.071  4138  4138 D BluetoothMapService: STATE_ON
07-15 15:22:22.072  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:22.072  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:22.072  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:22.072  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:22:22.072  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:22.072  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:22.072  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:22.072  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:22:22.073  3892  3892 D LocalBluetoothProfileManager: Adding local A2DP profile
07-15 15:22:22.074  4138  4175 D ObexServerSockets0: Accepting socket connection...
07-15 15:22:22.074  3840  3840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:22:22.078  3892  3892 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-15 15:22:22.085  3892  3892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-15 15:22:22.089  3892  3892 D BluetoothA2dp: Proxy object connected
,07-15 15:22:22.091  4138  4138 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-15 15:22:22.091  4138  4138 D ObexServerSockets0: prepareForNewConnect()
,07-15 15:22:22.098  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-15 15:22:22.100  4089  4113 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-15 15:22:22.104  3892  3892 D DockEventReceiver: finishStartingService: stopping service
,07-15 15:22:22.109  1359  1359 D BluetoothPbap: Proxy object connected
,07-15 15:22:22.110  1359  1359 D PbapServerProfile: Bluetooth service connected
,07-15 15:22:22.113  3892  3892 D BluetoothPbap: Proxy object connected
,07-15 15:22:22.113  3892  3892 D PbapServerProfile: Bluetooth service connected
,07-15 15:22:22.121  4138  4183 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-15 15:22:22.140  4138  4187 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-15 15:22:22.142  4138  4187 I BtOppRfcommListener: Accept thread started.
,07-15 15:22:22.154   874   874 D BluetoothHeadset: Proxy object connected
,07-15 15:22:22.155   874   874 D BluetoothHeadset: Proxy object connected
07-15 15:22:22.155   874   874 D BluetoothHeadset: Proxy object connected
07-15 15:22:22.155  1745  1937 D BluetoothHeadset: Proxy object connected
07-15 15:22:22.155  1359  2063 D BluetoothHeadset: Proxy object connected
,07-15 15:22:22.156  1359  1359 D HeadsetProfile: Bluetooth service connected
,07-15 15:22:22.158   874   891 D BluetoothHeadset: Proxy object connected
,07-15 15:22:22.158   874   891 D BluetoothHeadset: Proxy object connected
07-15 15:22:22.158  1359  1385 D BluetoothHeadset: Proxy object connected
07-15 15:22:22.158  1359  1359 D HeadsetProfile: Bluetooth service connected
,07-15 15:22:22.161  1745  1856 D BluetoothHeadset: Proxy object connected
,07-15 15:22:22.182  3892  3904 D BluetoothHeadset: Proxy object connected
,07-15 15:22:22.183  3892  3892 D HeadsetProfile: Bluetooth service connected
,07-15 15:22:22.276  1523  2293 I art     : Waiting for a blocking GC DisableMovingGc
,07-15 15:22:22.294  1523  2293 I art     : WaitForGcToComplete blocked for 17.375ms for cause DisableMovingGc
07-15 15:22:22.294  1523  2293 I art     : Starting a blocking GC DisableMovingGc
,07-15 15:22:23.458  4138  4150 D BluetoothAdapterState: Current state: ON, message: 23
07-15 15:22:23.477  4138  4150 D BluetoothAdapterProperties: Setting state to 13
07-15 15:22:23.478  4138  4150 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,07-15 15:22:23.479  4138  4150 D BluetoothAdapterProperties: onBluetoothDisable()
,07-15 15:22:23.483  4138  4150 I BluetoothAdapterState: Entering PendingCommandState
,07-15 15:22:23.485  4138  4154 D BluetoothAdapterProperties: Scan Mode:20
,07-15 15:22:23.486  4138  4150 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,07-15 15:22:23.489  4138  4138 D HeadsetService: Received stop request...Stopping profile...
,07-15 15:22:23.491   874   874 D BluetoothHeadset: Proxy object disconnected
,07-15 15:22:23.491   874   874 D BluetoothHeadset: Proxy object disconnected
07-15 15:22:23.491  4138  4138 V BluetoothAdapterState: isTurningOff()=true
07-15 15:22:23.491   874   874 D BluetoothHeadset: Proxy object disconnected
,07-15 15:22:23.492  4138  4138 V BluetoothAdapterState: isTurningOn()=false
07-15 15:22:23.492  4138  4138 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:23.492  4138  4138 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:23.493  1745  1937 D BluetoothHeadset: Proxy object disconnected
,07-15 15:22:23.495  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:23.495  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:23.495  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:23.495  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:22:23.495  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:22:23.495  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:23.495  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:23.495  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:22:23.496  1359  1385 D BluetoothHeadset: Proxy object disconnected
07-15 15:22:23.497  3892  3903 D BluetoothHeadset: Proxy object disconnected
07-15 15:22:23.500  3840  3840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-15 15:22:23.501  1359  1359 D HeadsetProfile: Bluetooth service disconnected
,07-15 15:22:23.504  3892  3892 D HeadsetProfile: Bluetooth service disconnected
,07-15 15:22:23.504  4138  4138 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-15 15:22:23.504  4138  4138 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-15 15:22:23.505  4138  4160 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-15 15:22:23.505  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:23.505  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:23.505  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:23.505  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:22:23.505  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:22:23.505  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:23.505  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:23.505  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:22:23.505  4138  4160 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-15 15:22:23.505  4138  4160 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-15 15:22:23.505  4138  4154 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-15 15:22:23.505  4138  4154 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,07-15 15:22:23.506  4138  4138 D A2dpService: Received stop request...Stopping profile...
07-15 15:22:23.506  4138  4169 D A2dpStateMachine: Exit Disconnected: -1
07-15 15:22:23.506  3840  3840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-15 15:22:23.508   874   874 D BluetoothA2dp: Proxy object disconnected
07-15 15:22:23.509  1359  1359 D BluetoothA2dp: Proxy object disconnected
,07-15 15:22:23.509  4138  4138 V BluetoothAdapterState: isTurningOff()=true
07-15 15:22:23.509  4138  4138 V BluetoothAdapterState: isTurningOn()=false
07-15 15:22:23.510  4138  4138 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:23.510  4138  4138 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:23.511  4138  4160 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-15 15:22:23.511  4138  4160 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-15 15:22:23.511  4138  4160 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-15 15:22:23.511  4138  4160 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-15 15:22:23.511  4138  4160 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-15 15:22:23.511  4138  4160 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-15 15:22:23.512  4138  4154 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,07-15 15:22:23.515  4138  4138 D BluetoothMapService: onReceive
,07-15 15:22:23.515  4138  4138 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-15 15:22:23.516  4138  4138 D BluetoothMapService: STATE_TURNING_OFF
07-15 15:22:23.516  4138  4138 D BluetoothMapService: MAP Service closeService in
07-15 15:22:23.516  4138  4138 D BluetoothMapMasInstance0: MAP Service shutdown
07-15 15:22:23.516  4138  4138 D ObexServerSockets0: shutdown(block = true)
,07-15 15:22:23.516  4138  4175 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-15 15:22:23.518  3892  3892 D BluetoothA2dp: Proxy object disconnected
07-15 15:22:23.518  4138  4138 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-15 15:22:23.519  4138  4176 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-15 15:22:23.519  4138  4163 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-15 15:22:23.520  4138  4138 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-15 15:22:23.520  4138  4138 I BtOppRfcommListener: stopping Accept Thread
,07-15 15:22:23.520  3892  3892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-15 15:22:23.520  4138  4187 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-15 15:22:23.521  4138  4187 I BtOppRfcommListener: BluetoothSocket listen thread finished
,07-15 15:22:23.526  4138  4138 D HidService: Received stop request...Stopping profile...
07-15 15:22:23.526  4138  4138 D HidService: Stopping Bluetooth HidService
07-15 15:22:23.528  3892  3892 D DockEventReceiver: finishStartingService: stopping service
,07-15 15:22:23.531  3892  3892 D BluetoothInputDevice: Proxy object disconnected
,07-15 15:22:23.531  3892  3892 D HidProfile: Bluetooth service disconnected
,07-15 15:22:23.534  4138  4138 D HealthService: Received stop request...Stopping profile...
07-15 15:22:23.535  1359  1359 D BluetoothInputDevice: Proxy object disconnected
07-15 15:22:23.535  1359  1359 D HidProfile: Bluetooth service disconnected
,07-15 15:22:23.537  4138  4138 D PanService: Received stop request...Stopping profile...
,07-15 15:22:23.538  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-15 15:22:23.538  1359  1359 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-15 15:22:23.539  1359  1359 D PanProfile: Bluetooth service disconnected
07-15 15:22:23.539  4138  4138 V BluetoothAdapterState: isTurningOff()=true
07-15 15:22:23.539  4138  4138 V BluetoothAdapterState: isTurningOn()=false
07-15 15:22:23.539  4138  4138 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:23.539  4138  4138 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:23.540  4138  4138 D BluetoothMapService: Received stop request...Stopping profile...
07-15 15:22:23.540  4138  4138 D BluetoothMapService: stop()
07-15 15:22:23.540  3892  3892 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-15 15:22:23.540  3892  3892 D PanProfile: Bluetooth service disconnected
07-15 15:22:23.540  4138  4138 D BluetoothMapAppObserver: deinitObservers()
07-15 15:22:23.540  4138  4138 D BluetoothMapAppObserver: removeReceiver()
,07-15 15:22:23.541  3892  3892 D BluetoothMap: Proxy object disconnected
07-15 15:22:23.541  3892  3892 D MapProfile: Bluetooth service disconnected
07-15 15:22:23.541  1359  1359 D BluetoothMap: Proxy object disconnected
07-15 15:22:23.541  1359  1359 D MapProfile: Bluetooth service disconnected
07-15 15:22:23.542  4138  4138 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-15 15:22:23.542  4138  4138 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-15 15:22:23.542  4138  4154 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-15 15:22:23.542  4138  4138 V BluetoothAdapterState: isTurningOff()=true
07-15 15:22:23.542  4138  4138 V BluetoothAdapterState: isTurningOn()=false
07-15 15:22:23.542  4138  4138 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:23.542  4138  4138 V BluetoothAdapterState: isBleTurningOff()=false
,07-15 15:22:23.543  4138  4138 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-15 15:22:23.543  4138  4154 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-15 15:22:23.543  4138  4138 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,07-15 15:22:23.544  1359  1359 D BluetoothPbap: Proxy object disconnected
07-15 15:22:23.544  1359  1359 D PbapServerProfile: Bluetooth service disconnected
07-15 15:22:23.545  3892  3892 D BluetoothPbap: Proxy object disconnected
07-15 15:22:23.545  3892  3892 D PbapServerProfile: Bluetooth service disconnected
07-15 15:22:23.545  4138  4138 V BluetoothAdapterState: isTurningOff()=true
07-15 15:22:23.545  4138  4138 V BluetoothAdapterState: isTurningOn()=false
07-15 15:22:23.545  4138  4138 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:23.545  4138  4138 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:23.545  4138  4138 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,07-15 15:22:23.545  4138  4138 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,07-15 15:22:23.548  4138  4138 D BluetoothMapService: MAP Service closeService in
,07-15 15:22:23.549  4138  4138 V BluetoothAdapterState: isTurningOff()=true
,07-15 15:22:23.549  4138  4138 V BluetoothAdapterState: isTurningOn()=false
07-15 15:22:23.549  4138  4138 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:23.549  4138  4138 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:23.550  4138  4150 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-15 15:22:23.550  4138  4150 D BluetoothAdapterProperties: Setting state to 15
07-15 15:22:23.550  4138  4150 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-15 15:22:23.550  4138  4150 I BluetoothAdapterState: Entering BleOnState
07-15 15:22:23.550  4138  4138 D BluetoothMapService: cleanup()
07-15 15:22:23.550  4138  4138 D BluetoothMapService: MAP Service closeService in
07-15 15:22:23.550  1359  2063 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-15 15:22:23.551  1359  1385 D BluetoothMap: onBluetoothStateChange: up=false
07-15 15:22:23.552  3892  3904 D BluetoothPan: onBluetoothStateChange on: false
07-15 15:22:23.552   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
07-15 15:22:23.552   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
07-15 15:22:23.552  3892  3903 D BluetoothMap: onBluetoothStateChange: up=false
07-15 15:22:23.553  1359  1384 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-15 15:22:23.554  3892  3904 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-15 15:22:23.556  3892  3903 D BluetoothPbap: onBluetoothStateChange: up=false
,07-15 15:22:23.556   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
07-15 15:22:23.556   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-15 15:22:23.556  1359  2063 D BluetoothHeadset: onBluetoothStateChange: up=false
07-15 15:22:23.557  3892  3904 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-15 15:22:23.557  1745  1856 D BluetoothHeadset: onBluetoothStateChange: up=false
07-15 15:22:23.558  3892  3903 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-15 15:22:23.558  1359  1385 D BluetoothPan: onBluetoothStateChange on: false
07-15 15:22:23.559  1359  1384 D BluetoothPbap: onBluetoothStateChange: up=false
,07-15 15:22:23.560  4138  4150 D BluetoothAdapterState: Current state: BLE ON, message: 20
,07-15 15:22:23.560  4138  4150 D BluetoothAdapterProperties: Setting state to 16
07-15 15:22:23.560  4138  4150 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,07-15 15:22:23.560  4138  4150 D BluetoothAdapterProperties: onBleDisable
07-15 15:22:23.561  4138  4150 I BluetoothAdapterState: Entering PendingCommandState
07-15 15:22:23.561  4138  4151 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-15 15:22:23.561  4138  4160 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,07-15 15:22:23.562  4138  4160 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-15 15:22:23.563  4138  4154 D BluetoothAdapterProperties: Scan Mode:20
07-15 15:22:23.564  3892  3892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-15 15:22:23.565  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:23.566  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:22:23.570  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-15 15:22:23.575  3892  3892 D DockEventReceiver: finishStartingService: stopping service
,07-15 15:22:23.762  4138  4154 I bt_hci  : shut_down
07-15 15:22:23.762  4138  4158 D bt_hwcfg: hw_epilog_process
,07-15 15:22:23.776  4138  4158 I bt_vendor: low_power_mode_cb
,07-15 15:22:23.797  4138  4158 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-15 15:22:23.798  4138  4158 I bt_vendor: epilog_cb
,07-15 15:22:23.798  4138  4158 I bt_hci  : epilog_finished_callback
,07-15 15:22:23.805  4138  4154 I bt_hci_h4: hal_close
,07-15 15:22:23.807  4138  4154 I bt_userial_vendor: device fd = 51 close
,07-15 15:22:23.936  4138  4151 D bt_stack_manager: event_shut_down_stack finished.
,07-15 15:22:23.938  4138  4150 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,07-15 15:22:23.944  4138  4150 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-15 15:22:23.946  4138  4138 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-15 15:22:23.947  4138  4138 D BtGatt.GattService: Received stop request...Stopping profile...
,07-15 15:22:23.948  4138  4138 D BtGatt.GattService: stop(),
,07-15 15:22:23.948  4138  4138 D BtGatt.AdvertiseManager: advertise clients cleared,
07-15 15:22:23.953  4138  4138 V BluetoothAdapterState: isTurningOff()=false
07-15 15:22:23.955  4138  4138 V BluetoothAdapterState: isTurningOn()=false
07-15 15:22:23.955  4138  4138 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:23.955  4138  4138 V BluetoothAdapterState: isBleTurningOff()=true
07-15 15:22:23.955  4138  4150 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-15 15:22:23.956  4138  4150 D BluetoothAdapterProperties: Setting state to 10
07-15 15:22:23.956  4138  4150 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,07-15 15:22:23.958  4138  4150 I BluetoothAdapterState: Entering OffState
07-15 15:22:23.959   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,07-15 15:22:23.976  4138  4138 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-15 15:22:23.976  4138  4138 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-15 15:22:23.980  4138  4151 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,07-15 15:22:23.986  4138  4151 D bt_stack_manager: event_clean_up_stack finished.
07-15 15:22:23.986  4138  4138 I BluetoothServiceJni: cleanupNative: return from cleanup
,07-15 15:22:23.994  4138  4138 I art     : System.exit called, status: 0
,07-15 15:22:23.995  4138  4138 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-15 15:22:24.054   874  1421 I ActivityManager: Process com.android.bluetooth (pid 4138) has died
,07-15 15:22:24.858   874  1316 D ConnectivityService: handlePromptUnvalidated 101
,07-15 15:22:26.455  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
,07-15 15:22:26.456  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-15 15:22:27.143  3526  3537 D Finsky  : [297] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
07-15 15:22:27.163  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-15 15:22:27.178  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-15 15:22:27.182  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:22:27.257  1523  2098 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-15 15:22:27.258  1523  2098 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-15 15:22:27.258  1523  2098 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:22:27.258  1523  2098 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:22:27.320  3526  3537 D Finsky  : [297] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,07-15 15:22:29.470  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:22:29.471  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29c9c4b added. We now have 6 listener(s)
,07-15 15:22:29.471  3840  3888 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-15 15:22:29.475  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:22:29.475  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@14f9628 added. We now have 7 listener(s)
07-15 15:22:29.475  3840  3888 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-15 15:22:29.478  3840  3888 I System.out: IsBluetoothEnabled
,07-15 15:22:29.487  3840  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:22:29.526   874   891 I ActivityManager: Start proc 4200:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-15 15:22:29.655  4200  4200 D AdapterServiceConfig: Adding HeadsetService
,07-15 15:22:29.655  4200  4200 D AdapterServiceConfig: Adding A2dpService
07-15 15:22:29.655  4200  4200 D AdapterServiceConfig: Adding HidService,
07-15 15:22:29.655  4200  4200 D AdapterServiceConfig: Adding HealthService
07-15 15:22:29.656  4200  4200 D AdapterServiceConfig: Adding PanService
,07-15 15:22:29.656  4200  4200 D AdapterServiceConfig: Adding GattService
07-15 15:22:29.656  4200  4200 D AdapterServiceConfig: Adding BluetoothMapService
,07-15 15:22:29.670   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9fd05c9:true
,07-15 15:22:29.671  4200  4200 D BluetoothAdapterState: make() - Creating AdapterState
,07-15 15:22:29.679  4200  4212 I BluetoothAdapterState: Entering OffState
,07-15 15:22:29.679  4200  4200 I bt_bluedroid: init
,07-15 15:22:29.686  4200  4213 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-15 15:22:29.687  4200  4213 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,07-15 15:22:29.687  4200  4213 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,07-15 15:22:29.688  4200  4213 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-15 15:22:29.690  4200  4200 I bt_bluedroid: get_profile_interface socket
,07-15 15:22:29.692  4200  4216 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-15 15:22:29.693  4200  4216 D BluetoothAdapterProperties: Name is: Nexus 6
07-15 15:22:29.695  4200  4200 I bt_bluedroid: get_profile_interface sdp
,07-15 15:22:29.699  4200  4211 I bt_bluedroid: config_hci_snoop_log
,07-15 15:22:29.700   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,07-15 15:22:29.711  4200  4212 D BluetoothAdapterState: Current state: OFF, message: 0
07-15 15:22:29.712  4200  4212 D BluetoothAdapterProperties: Setting state to 14
,07-15 15:22:29.712  4200  4212 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
07-15 15:22:29.714  4200  4212 D BluetoothBondStateMachine: make
,07-15 15:22:29.717  4200  4217 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-15 15:22:29.720  4200  4212 I BluetoothAdapterState: Entering PendingCommandState
,07-15 15:22:29.723  4200  4200 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-15 15:22:29.730  4200  4200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e109ae2
,07-15 15:22:29.732  4200  4200 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-15 15:22:29.733  4200  4200 D BtGatt.GattService: Received start request. Starting profile...
,07-15 15:22:29.733  4200  4200 D BtGatt.GattService: start()
07-15 15:22:29.734  4200  4200 I bt_bluedroid: get_profile_interface gatt
,07-15 15:22:29.736  4200  4200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e109ae2
07-15 15:22:29.736  4200  4200 D BtGatt.AdvertiseManager: advertise manager created
,07-15 15:22:29.751  4200  4200 V BluetoothAdapterState: isTurningOff()=false
07-15 15:22:29.751  4200  4200 V BluetoothAdapterState: isTurningOn()=false
,07-15 15:22:29.752  4200  4200 V BluetoothAdapterState: isBleTurningOn()=true
,07-15 15:22:29.752  4200  4200 V BluetoothAdapterState: isBleTurningOff()=false
,07-15 15:22:29.753  4200  4212 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,07-15 15:22:29.753  4200  4212 I bt_bluedroid: enable
,07-15 15:22:29.753  4200  4213 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,07-15 15:22:29.754  4200  4213 I bt_hci  : start_up
,07-15 15:22:29.776  4200  4213 I bt_vendor: alloc value 0xb3a43189
,07-15 15:22:29.776  4200  4213 I bt_vendor: init
,07-15 15:22:29.776  4200  4213 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-15 15:22:29.777  4200  4213 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-15 15:22:29.884  4200  4213 D bt_hci  : start_up starting async portion
,07-15 15:22:29.885  4200  4220 I bt_hci  : event_finish_startup
,07-15 15:22:29.885  4200  4220 I bt_hci_h4: hal_open
07-15 15:22:29.886  4200  4220 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-15 15:22:29.897  4200  4220 I bt_userial_vendor: device fd = 51 open
,07-15 15:22:29.929  4200  4220 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-15 15:22:29.960  4200  4220 D bt_hwcfg: Chipset BCM4354A2
07-15 15:22:29.961  4200  4220 D bt_hwcfg: Target name = [BCM4354A2]
07-15 15:22:29.961  4200  4220 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,07-15 15:22:30.831  4200  4220 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-15 15:22:30.832  4200  4220 D bt_hwcfg: Settlement delay -- 100 ms,
07-15 15:22:30.832  4200  4220 I bt_hwcfg: Setting fw settlement delay to 100 
,07-15 15:22:30.950  4200  4220 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-15 15:22:30.951  4200  4220 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,07-15 15:22:30.980  4200  4220 I bt_hwcfg: vendor lib fwcfg completed
07-15 15:22:30.980  4200  4220 I bt_vendor: firmware callback
,07-15 15:22:30.980  4200  4220 I bt_hci  : firmware_config_callback
,07-15 15:22:30.994  4200  4222 I bt_btu  : btu_task pending for preload complete event
,07-15 15:22:30.994  4200  4222 I bt_btu_task: Bluetooth chip preload is complete,
,07-15 15:22:30.994  4200  4222 I bt_btu  : btu_task received preload complete event
,07-15 15:22:31.005  4200  4222 I         : BTE_InitTraceLevels -- TRC_HCI
,07-15 15:22:31.005  4200  4222 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-15 15:22:31.005  4200  4222 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-15 15:22:31.006  4200  4222 I         : BTE_InitTraceLevels -- TRC_AVDT
,07-15 15:22:31.006  4200  4222 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-15 15:22:31.006  4200  4222 I         : BTE_InitTraceLevels -- TRC_A2D
07-15 15:22:31.007  4200  4222 I         : BTE_InitTraceLevels -- TRC_BNEP
07-15 15:22:31.007  4200  4222 I         : BTE_InitTraceLevels -- TRC_BTM
,07-15 15:22:31.007  4200  4222 I         : BTE_InitTraceLevels -- TRC_GAP
07-15 15:22:31.007  4200  4222 I         : BTE_InitTraceLevels -- TRC_PAN
07-15 15:22:31.008  4200  4222 I         : BTE_InitTraceLevels -- TRC_SDP
07-15 15:22:31.008  4200  4222 I         : BTE_InitTraceLevels -- TRC_GATT
,07-15 15:22:31.008  4200  4222 I         : BTE_InitTraceLevels -- TRC_SMP
07-15 15:22:31.008  4200  4222 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-15 15:22:31.009  4200  4222 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-15 15:22:31.158  4200  4222 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39c0d9d
,07-15 15:22:31.159  4200  4222 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39c0d9d 
,07-15 15:22:31.171  4200  4216 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,07-15 15:22:31.173  4200  4216 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-15 15:22:31.174  4200  4216 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-15 15:22:31.177  4200  4216 D BluetoothAdapterProperties: Name is: Nexus 6
,07-15 15:22:31.184  4200  4216 D BluetoothAdapterProperties: Scan Mode:20
,07-15 15:22:31.184  4200  4216 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-15 15:22:31.185  4200  4216 D bt_hci  : do_postload posting postload work item
,07-15 15:22:31.185  4200  4220 I bt_hci  : event_postload
07-15 15:22:31.186  4200  4220 I bt_vendor: sco_config_cb
07-15 15:22:31.186  4200  4220 I bt_hci  : sco_config_callback postload finished.
,07-15 15:22:31.190  4200  4216 D bt_bte_conf: Device ID record 1 : primary
,07-15 15:22:31.191  4200  4216 D bt_bte_conf:   vendorId            = 000f
,07-15 15:22:31.191  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:31.191  4200  4216 D bt_bte_conf:   vendorIdSource      = 0001
07-15 15:22:31.191  4200  4216 D bt_bte_conf:   product             = 1200,
07-15 15:22:31.192  4200  4216 D bt_bte_conf:   version             = 1436
07-15 15:22:31.192  4200  4216 D bt_bte_conf:   clientExecutableURL = 
,07-15 15:22:31.192  4200  4216 D bt_bte_conf:   serviceDescription  = 
07-15 15:22:31.192  4200  4216 D bt_bte_conf:   documentationURL    = 
07-15 15:22:31.193  4200  4216 D bt_bte_conf: bte_load_did_conf no section named DID2.
,07-15 15:22:31.193  4200  4213 D bt_stack_manager: event_start_up_stack finished
07-15 15:22:31.195  4200  4220 I bt_vendor: low_power_mode_cb
,07-15 15:22:31.195  4200  4212 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-15 15:22:31.196  4200  4212 D BluetoothAdapterProperties: Setting state to 15
07-15 15:22:31.196  4200  4212 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15,
07-15 15:22:31.197  4200  4212 I BluetoothAdapterState: Entering BleOnState
,07-15 15:22:31.204  4200  4212 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-15 15:22:31.204  4200  4212 D BluetoothAdapterProperties: Setting state to 11
,07-15 15:22:31.205  4200  4212 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,07-15 15:22:31.216  4200  4200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e109ae2
,07-15 15:22:31.221  4200  4200 D HeadsetService: Received start request. Starting profile...
,07-15 15:22:31.224  4200  4200 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-15 15:22:31.224  4200  4200 D HeadsetStateMachine: make
,07-15 15:22:31.231  4200  4212 I BluetoothAdapterState: Entering PendingCommandState
,07-15 15:22:31.232  4200  4200 D HeadsetStateMachine: max_hf_connections = 1
,07-15 15:22:31.232  4200  4200 I bt_bluedroid: get_profile_interface handsfree
07-15 15:22:31.233  4200  4216 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040,
07-15 15:22:31.233  4200  4216 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,07-15 15:22:31.238  4200  4200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e109ae2
,07-15 15:22:31.239  4200  4200 D A2dpService: Received start request. Starting profile...
07-15 15:22:31.240  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-15 15:22:31.240  4200  4200 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-15 15:22:31.240  4200  4200 I bt_bluedroid: get_profile_interface avrcp
,07-15 15:22:31.247  4200  4200 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-15 15:22:31.248  4200  4200 I BluetoothA2dpServiceJni: classInitNative: succeeds
,07-15 15:22:31.248  4200  4200 D A2dpStateMachine: make
,07-15 15:22:31.250  4200  4200 I bt_bluedroid: get_profile_interface a2dp
,07-15 15:22:31.251  4200  4216 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,07-15 15:22:31.253  4200  4231 D A2dpStateMachine: Enter Disconnected: -2
07-15 15:22:31.253  4200  4200 I BluetoothHidServiceJni: classInitNative: succeeds
,07-15 15:22:31.254  4200  4200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e109ae2
,07-15 15:22:31.255  4200  4200 D HidService: Received start request. Starting profile...
,07-15 15:22:31.255  4200  4200 I bt_bluedroid: get_profile_interface hidhost
07-15 15:22:31.255  4200  4200 D HidService: setHidService(): set to: null
07-15 15:22:31.255  4200  4216 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39a23e5
07-15 15:22:31.255  4200  4216 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-15 15:22:31.256  4200  4200 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-15 15:22:31.257  4200  4200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e109ae2
07-15 15:22:31.258  4200  4200 D HealthService: Received start request. Starting profile...
,07-15 15:22:31.260  4200  4200 I bt_bluedroid: get_profile_interface health
07-15 15:22:31.260  4200  4200 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-15 15:22:31.261  4200  4200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e109ae2
07-15 15:22:31.261  4200  4200 D PanService: Received start request. Starting profile...
,07-15 15:22:31.262  4200  4200 D BluetoothPanServiceJni: initializeNative(L110): pan
07-15 15:22:31.262  4200  4200 I bt_bluedroid: get_profile_interface pan
07-15 15:22:31.262  4200  4216 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-15 15:22:31.265  4200  4200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e109ae2
,07-15 15:22:31.266  4200  4200 D BluetoothMapService: Received start request. Starting profile...
07-15 15:22:31.266  4200  4200 D BluetoothMapService: start()
,07-15 15:22:31.269  4200  4200 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,07-15 15:22:31.269  4200  4200 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-15 15:22:31.270  4200  4200 D BluetoothMapAppObserver: createReceiver()
,07-15 15:22:31.271  4200  4200 D BluetoothMapAppObserver: initObservers()
07-15 15:22:31.271  4200  4200 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-15 15:22:31.279  4200  4200 V BluetoothAdapterState: isTurningOff()=false
,07-15 15:22:31.279  4200  4200 V BluetoothAdapterState: isTurningOn()=true
07-15 15:22:31.279  4200  4200 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:31.279  4200  4200 V BluetoothAdapterState: isBleTurningOff()=false
,07-15 15:22:31.282  4200  4228 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-15 15:22:31.282  4200  4200 V BluetoothAdapterState: isTurningOff()=false
,07-15 15:22:31.282  4200  4200 V BluetoothAdapterState: isTurningOn()=true
,07-15 15:22:31.282  4200  4200 V BluetoothAdapterState: isBleTurningOn()=false
,07-15 15:22:31.282  4200  4200 V BluetoothAdapterState: isBleTurningOff()=false
,07-15 15:22:31.282  4200  4200 V BluetoothAdapterState: isTurningOff()=false
07-15 15:22:31.282  4200  4200 V BluetoothAdapterState: isTurningOn()=true
07-15 15:22:31.282  4200  4200 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:31.282  4200  4200 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:31.283  4200  4200 V BluetoothAdapterState: isTurningOff()=false
07-15 15:22:31.283  4200  4200 V BluetoothAdapterState: isTurningOn()=true
07-15 15:22:31.283  4200  4200 V BluetoothAdapterState: isBleTurningOn()=false
,07-15 15:22:31.283  4200  4200 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:31.283  4200  4200 V BluetoothAdapterState: isTurningOff()=false
,07-15 15:22:31.283  4200  4200 V BluetoothAdapterState: isTurningOn()=true
07-15 15:22:31.283  4200  4200 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:31.283  4200  4200 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:31.284  4200  4200 V BluetoothAdapterState: isTurningOff()=false
07-15 15:22:31.284  4200  4200 V BluetoothAdapterState: isTurningOn()=true
07-15 15:22:31.284  4200  4200 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:31.284  4200  4200 V BluetoothAdapterState: isBleTurningOff()=false
,07-15 15:22:31.284  4200  4212 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-15 15:22:31.284  4200  4212 D BluetoothAdapterProperties: ScanMode =  20
07-15 15:22:31.285  4200  4212 D BluetoothAdapterProperties: State =  11
07-15 15:22:31.286  4200  4216 D BluetoothAdapterProperties: Scan Mode:21
07-15 15:22:31.286  4200  4216 D BluetoothAdapterProperties: Discoverable Timeout:120
07-15 15:22:31.287  4200  4212 D BluetoothAdapterProperties: Setting state to 12
07-15 15:22:31.287  4200  4212 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-15 15:22:31.287  1359  1384 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-15 15:22:31.288  4200  4212 I BluetoothAdapterState: Entering OnState
07-15 15:22:31.290  1359  2063 D BluetoothMap: onBluetoothStateChange: up=true
07-15 15:22:31.292  1359  1359 D BluetoothInputDevice: Proxy object connected
07-15 15:22:31.292  1359  1359 D HidProfile: Bluetooth service connected
,07-15 15:22:31.297  4200  4200 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-15 15:22:31.297  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:31.297  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:31.297  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:31.297  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:22:31.297  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:31.297  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:31.297  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:31.297  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:22:31.298  4200  4200 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-15 15:22:31.299  4200  4200 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-15 15:22:31.300  3840  3840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-15 15:22:31.302  4200  4200 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-15 15:22:31.304  4200  4200 D ObexServerSockets: Succeed to create listening sockets 
,07-15 15:22:31.304  4200  4200 D ObexServerSockets0: startAccept()
07-15 15:22:31.304  4200  4200 D ObexServerSockets0: prepareForNewConnect()
07-15 15:22:31.304  3892  4192 D BluetoothPan: onBluetoothStateChange on: true
,07-15 15:22:31.307   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-15 15:22:31.307  4200  4200 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-15 15:22:31.307  4200  4200 D BluetoothSdpJni: SDP Create record success - handle: 0
07-15 15:22:31.307   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-15 15:22:31.308  4200  4236 D ObexServerSockets0: Accepting socket connection...
,07-15 15:22:31.308  1359  1359 D BluetoothMap: Proxy object connected
07-15 15:22:31.309  1359  1359 D MapProfile: Bluetooth service connected
07-15 15:22:31.309  1359  1359 D BluetoothMap: getConnectedDevices()
07-15 15:22:31.309  4200  4237 D ObexServerSockets0: Accepting socket connection...
,07-15 15:22:31.311  3892  3903 D BluetoothMap: onBluetoothStateChange: up=true
07-15 15:22:31.312   874   874 D BluetoothA2dp: Proxy object connected
07-15 15:22:31.314  3892  3892 D BluetoothPan: BluetoothPAN Proxy object connected
,07-15 15:22:31.314  3892  3892 D PanProfile: Bluetooth service connected
07-15 15:22:31.315  3892  3892 D BluetoothMap: Proxy object connected
07-15 15:22:31.315  3892  3892 D MapProfile: Bluetooth service connected
,07-15 15:22:31.315  1359  1385 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-15 15:22:31.315  3892  3892 D BluetoothMap: getConnectedDevices()
07-15 15:22:31.317  1359  1359 D BluetoothA2dp: Proxy object connected
07-15 15:22:31.318  3892  4192 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-15 15:22:31.321  3892  3904 D BluetoothPbap: onBluetoothStateChange: up=true
,07-15 15:22:31.323   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-15 15:22:31.323   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-15 15:22:31.323  3892  3892 D BluetoothInputDevice: Proxy object connected
,07-15 15:22:31.323  3892  3892 D HidProfile: Bluetooth service connected
07-15 15:22:31.323  1359  1384 D BluetoothHeadset: onBluetoothStateChange: up=true
07-15 15:22:31.324  3892  3903 D BluetoothHeadset: onBluetoothStateChange: up=true
07-15 15:22:31.325  1745  1856 D BluetoothHeadset: onBluetoothStateChange: up=true
07-15 15:22:31.326  3892  4192 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-15 15:22:31.329  3892  3892 D BluetoothA2dp: Proxy object connected
,07-15 15:22:31.329  1359  2063 D BluetoothPan: onBluetoothStateChange on: true
,07-15 15:22:31.331  1359  1359 D BluetoothPan: BluetoothPAN Proxy object connected
,07-15 15:22:31.331  1359  1359 D PanProfile: Bluetooth service connected
07-15 15:22:31.332  1359  1384 D BluetoothPbap: onBluetoothStateChange: up=true
,07-15 15:22:31.335   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,07-15 15:22:31.336  4200  4200 D BluetoothMapService: onReceive
07-15 15:22:31.336  4200  4200 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-15 15:22:31.336  4200  4200 D BluetoothMapService: STATE_ON
,07-15 15:22:31.346  3892  3892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-15 15:22:31.362  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-15 15:22:31.364  4200  4200 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-15 15:22:31.364  4200  4200 D ObexServerSockets0: prepareForNewConnect()
07-15 15:22:31.365  4200  4241 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-15 15:22:31.366  3892  3892 D DockEventReceiver: finishStartingService: stopping service
,07-15 15:22:31.370  3892  3892 D BluetoothPbap: Proxy object connected
07-15 15:22:31.370  3892  3892 D PbapServerProfile: Bluetooth service connected
07-15 15:22:31.372  1359  1359 D BluetoothPbap: Proxy object connected
,07-15 15:22:31.372  1359  1359 D PbapServerProfile: Bluetooth service connected
,07-15 15:22:31.401  4200  4247 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-15 15:22:31.402  4200  4247 I BtOppRfcommListener: Accept thread started.
,07-15 15:22:31.409   874   874 D BluetoothHeadset: Proxy object connected
,07-15 15:22:31.409   874   874 D BluetoothHeadset: Proxy object connected
07-15 15:22:31.409   874   874 D BluetoothHeadset: Proxy object connected,
07-15 15:22:31.410  1745  1757 D BluetoothHeadset: Proxy object connected
,07-15 15:22:31.411  1359  1385 D BluetoothHeadset: Proxy object connected
,07-15 15:22:31.412  1359  1359 D HeadsetProfile: Bluetooth service connected
,07-15 15:22:31.413  3892  3903 D BluetoothHeadset: Proxy object connected
,07-15 15:22:31.414  3892  3892 D HeadsetProfile: Bluetooth service connected
,07-15 15:22:31.422   874   891 D BluetoothHeadset: Proxy object connected
,07-15 15:22:31.424   874   891 D BluetoothHeadset: Proxy object connected
,07-15 15:22:31.424  1359  2063 D BluetoothHeadset: Proxy object connected
07-15 15:22:31.424  1359  1359 D HeadsetProfile: Bluetooth service connected
07-15 15:22:31.425  3892  3904 D BluetoothHeadset: Proxy object connected
,07-15 15:22:31.425  3892  3892 D HeadsetProfile: Bluetooth service connected
07-15 15:22:31.426  1745  1756 D BluetoothHeadset: Proxy object connected
,07-15 15:22:31.508  3840  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:31.508  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:31.508  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:31.508  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:22:31.508  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:31.508  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:31.508  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:31.508  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:22:31.517  3840  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:22:31.521  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:22:31.521  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9934f41 added. We now have 8 listener(s)
,07-15 15:22:31.521  3840  3888 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-15 15:22:31.527   874  3200 D WifiService: setWifiEnabled: false pid=3840, uid=10000
07-15 15:22:31.528   874  3200 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-15 15:22:31.542  3840  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:22:31.543   874  1702 D WifiService: setWifiEnabled: true pid=3840, uid=10000
,07-15 15:22:31.543   874  1702 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-15 15:22:31.561   874  1314 D WifiConfigStore: Loading config and enabling all networks 
,07-15 15:22:31.579  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:31.579  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:31.579  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:31.579  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:31.579  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:31.579  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:31.579  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:31.579  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:22:31.583  3840  3840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:22:31.594   874  1314 D WifiConfigStore: loaded 0 passpoint configs
,07-15 15:22:31.594   874  1314 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-15 15:22:31.595   874  1314 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,07-15 15:22:31.595   874  1314 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-15 15:22:31.596   874  1314 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-15 15:22:31.596   874  1314 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,07-15 15:22:31.597   874  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
07-15 15:22:31.597   874  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-15 15:22:31.612   371   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,07-15 15:22:31.613   874  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-15 15:22:31.616   371   872 D CommandListener: Setting iface cfg
,07-15 15:22:31.666   874  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
,07-15 15:22:31.667   874  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-15 15:22:31.670   874  1314 E native  : do suspend true
,07-15 15:22:31.691   874  1313 D WifiNative-HAL: p2pGetDeviceAddress
,07-15 15:22:31.704   874  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,07-15 15:22:31.705   874  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,07-15 15:22:32.571  3840  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:32.571  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:32.571  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:32.571  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:32.571  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:32.571  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:32.571  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:32.571  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:22:32.578  3840  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:22:32.583  3840  3888 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-15 15:22:32.586  3840  3888 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-15 15:22:32.592  3840  3888 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@fa1832e Bundle[{}]
,07-15 15:22:32.595  3840  3888 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-15 15:22:32.596  3840  3888 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-15 15:22:32.597  3840  3888 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-15 15:22:32.598  3840  3888 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-15 15:22:32.600  3840  3888 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-15 15:22:32.602  3840  3888 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-15 15:22:32.616  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,07-15 15:22:32.616  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,07-15 15:22:32.616  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-15 15:22:32.616  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,07-15 15:22:32.617  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,07-15 15:22:32.617  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-15 15:22:32.623  3840  3888 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 381)
,07-15 15:22:32.623  3840  3888 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 381)
,07-15 15:22:32.623  3840  3888 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 381)
,07-15 15:22:32.623  3840  3888 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 381)
,07-15 15:22:32.626  3840  3888 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 386)
,07-15 15:22:32.626  3840  3888 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 386)
,07-15 15:22:32.626  3840  3888 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 386)
07-15 15:22:32.627  3840  3888 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 387)
07-15 15:22:32.628  3840  3888 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 389)
07-15 15:22:32.633  3840  4253 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 395, name: My test thread name)
,07-15 15:22:32.634  3840  4253 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 395, thread name: My test thread name)
07-15 15:22:32.634  3840  4253 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 395, name: My test thread name)
,07-15 15:22:32.638  3840  4254 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 397, name: My test thread name)
,07-15 15:22:32.639  3840  4254 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 397, thread name: My test thread name)
07-15 15:22:32.639  3840  4254 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 397, name: My test thread name)
,07-15 15:22:32.643  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-15 15:22:32.643  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@324bce6 added. We now have 2 listener(s)
07-15 15:22:32.645  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-15 15:22:32.645  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
07-15 15:22:32.645  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-15 15:22:32.645  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:22:32.645  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@816b227 added. We now have 9 listener(s)
07-15 15:22:32.645  3840  3888 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-15 15:22:32.651  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-15 15:22:32.656  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-15 15:22:32.663  3840  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:22:32.663  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:32.663  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:32.663  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:32.663  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:32.663  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:32.663  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:32.663  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:22:32.668  3840  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:22:32.668  3840  3888 D io.jxcore.node.ConnectivityMonitor: start: OK
07-15 15:22:32.668  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-15 15:22:32.669  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7049e7d added. We now have 3 listener(s)
,07-15 15:22:32.671  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:32.672  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-15 15:22:32.672  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-15 15:22:32.672  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-15 15:22:32.673  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:22:32.673  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6efc172 added. We now have 10 listener(s)
07-15 15:22:32.673  3840  3888 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-15 15:22:32.674  3840  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:32.674  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:32.675  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-15 15:22:32.675  3840  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:32.676  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-15 15:22:32.676  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:22:32.676  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-15 15:22:32.676  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-15 15:22:32.677  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@324bce6 removed from the list
07-15 15:22:32.677  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-15 15:22:32.677  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@816b227 removed from the list
07-15 15:22:32.677  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
,07-15 15:22:32.677  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:32.678  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:32.679  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-15 15:22:32.679  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:32.679  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@816b227 not in the list
07-15 15:22:32.679  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:22:32.680  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:32.680  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:32.680  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6efc172 removed from the list
,07-15 15:22:32.680  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:32.680  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:32.680  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-15 15:22:32.681  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-15 15:22:32.681  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7049e7d removed from the list
07-15 15:22:32.683  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-15 15:22:32.683  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13249c3 added. We now have 2 listener(s)
,07-15 15:22:32.686  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-15 15:22:32.686  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:22:32.687  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-15 15:22:32.687  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:22:32.687  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b50240 added. We now have 9 listener(s)
07-15 15:22:32.688  3840  3888 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-15 15:22:32.693  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-15 15:22:32.698  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-15 15:22:32.704  3840  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:22:32.704  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:32.704  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:32.704  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:32.704  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:32.704  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:32.704  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:32.704  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:22:32.709  3840  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:22:32.709  3840  3888 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-15 15:22:32.710  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-15 15:22:32.710  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f482be added. We now have 3 listener(s)
07-15 15:22:32.713  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:32.713  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-15 15:22:32.713  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:22:32.713  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-15 15:22:32.714  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-15 15:22:32.714  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e5bf1f added. We now have 10 listener(s)
07-15 15:22:32.714  3840  3888 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:22:32.714  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-15 15:22:32.715  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-15 15:22:32.715  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:22:32.715  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-15 15:22:32.717  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:22:32.725  3840  3888 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-15 15:22:32.725  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-15 15:22:32.736  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-15 15:22:32.740  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-15 15:22:32.741  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-15 15:22:32.741  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-15 15:22:32.742  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-15 15:22:32.743  3840  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,07-15 15:22:32.745  3840  3888 D BluetoothAdapter: STATE_ON
,07-15 15:22:32.757  4200  4238 D BtGatt.GattService: registerClient() - UUID=6a79fa92-6d53-48b3-8a2e-adc37d35e5eb
,07-15 15:22:32.758  4200  4216 D BtGatt.GattService: onClientRegistered() - UUID=6a79fa92-6d53-48b3-8a2e-adc37d35e5eb, clientIf=5
07-15 15:22:32.759  3840  3852 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-15 15:22:32.763  4200  4239 D BtGatt.GattService: start scan with filters
,07-15 15:22:32.772  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-15 15:22:32.772  4200  4219 D BtGatt.ScanManager: handling starting scan
07-15 15:22:32.773  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,07-15 15:22:32.774  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-15 15:22:32.774  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,07-15 15:22:32.775  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,07-15 15:22:32.776  4200  4219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e109ae2
,07-15 15:22:32.776  3840  3840 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,07-15 15:22:32.778  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-15 15:22:32.780  4200  4216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,07-15 15:22:32.781  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-15 15:22:32.784  4200  4219 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-15 15:22:32.786  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-15 15:22:32.786  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-15 15:22:32.787  3840  3840 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-15 15:22:32.788  4200  4216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-15 15:22:32.789  3840  3888 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-15 15:22:32.789  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-15 15:22:32.789  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:32.789  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:22:32.790  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-15 15:22:32.790  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,07-15 15:22:32.790  4200  4219 D BtGatt.ScanManager: Starting BLE batch scan
07-15 15:22:32.791  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-15 15:22:32.791  4200  4219 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-15 15:22:32.791  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-15 15:22:32.793  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-15 15:22:32.793  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-15 15:22:32.795  3840  3888 D BluetoothAdapter: STATE_ON
,07-15 15:22:32.797  4200  4210 D BtGatt.GattService: stopScan() - queue size =1
,07-15 15:22:32.799  4200  4216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-15 15:22:32.799  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-15 15:22:32.800  4200  4229 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-15 15:22:32.801  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-15 15:22:32.801  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,07-15 15:22:32.802  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,07-15 15:22:32.802  4200  4216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
07-15 15:22:32.802  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,07-15 15:22:32.802  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,07-15 15:22:32.802  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-15 15:22:32.802  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,07-15 15:22:32.802  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-15 15:22:32.802  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-15 15:22:32.803  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-15 15:22:32.804  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:22:32.804  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-15 15:22:32.804  3840  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-15 15:22:32.804  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:22:32.804  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-15 15:22:32.807  4200  4216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,07-15 15:22:32.807  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-15 15:22:32.807  4200  4219 D BtGatt.ScanManager: stopping BLe Batch
07-15 15:22:32.809  3840  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-15 15:22:32.810  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:32.810  3840  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:32.810  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:32.810  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:22:32.810  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-15 15:22:32.810  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-15 15:22:32.810  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13249c3 removed from the list
07-15 15:22:32.810  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-15 15:22:32.811  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b50240 removed from the list
07-15 15:22:32.811  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:32.811  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:22:32.811  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:32.811  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,07-15 15:22:32.812  4200  4216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-15 15:22:32.812  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-15 15:22:32.812  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:32.812  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:22:32.812  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-15 15:22:32.812  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b50240 not in the list
07-15 15:22:32.813  4200  4219 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-15 15:22:32.815  4200  4216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-15 15:22:32.815  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-15 15:22:32.817  3840  3840 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-15 15:22:32.818  3840  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-15 15:22:32.828  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-15 15:22:32.830  3840  3840 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-15 15:22:32.830  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-15 15:22:32.831  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-15 15:22:32.832  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-15 15:22:32.833  3840  3888 D BluetoothAdapter: STATE_ON
,07-15 15:22:32.833  3840  3888 D BluetoothLeScanner: could not find callback wrapper
07-15 15:22:32.833  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-15 15:22:32.833  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-15 15:22:32.833  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:32.833  3840  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-15 15:22:32.834  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e5bf1f removed from the list
07-15 15:22:32.834  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:22:32.834  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-15 15:22:32.834  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:32.834  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:32.834  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:22:32.834  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-15 15:22:32.834  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f482be removed from the list
07-15 15:22:32.835  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-15 15:22:32.836  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bfa7317 added. We now have 2 listener(s)
07-15 15:22:32.838  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-15 15:22:32.838  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:22:32.838  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-15 15:22:32.838  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:22:32.838  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37e3304 added. We now have 9 listener(s)
07-15 15:22:32.838  3840  3888 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:22:32.840  3840  3840 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-15 15:22:32.840  3840  3840 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-15 15:22:32.840  3840  3840 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-15 15:22:32.842  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-15 15:22:32.848  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-15 15:22:32.852  3840  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:22:32.852  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:32.852  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:32.852  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:32.852  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:32.852  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:32.852  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:32.852  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:22:32.855  3840  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:22:32.855  3840  3888 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-15 15:22:32.856  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-15 15:22:32.856  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd76b22 added. We now have 3 listener(s)
07-15 15:22:32.857  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:32.857  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-15 15:22:32.858  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-15 15:22:32.858  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-15 15:22:32.858  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:22:32.858  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a929b3 added. We now have 10 listener(s)
07-15 15:22:32.858  3840  3888 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-15 15:22:32.858  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-15 15:22:32.860  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:32.860  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-15 15:22:32.861  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-15 15:22:32.861  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:22:32.861  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-15 15:22:32.866  3840  3888 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-15 15:22:32.866  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-15 15:22:32.871  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-15 15:22:32.872  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-15 15:22:32.872  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-15 15:22:32.873  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-15 15:22:32.873  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-15 15:22:32.873  3840  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,07-15 15:22:32.873  3840  3888 D BluetoothAdapter: STATE_ON
,07-15 15:22:32.877  4200  4239 D BtGatt.GattService: registerClient() - UUID=dac9da2c-67d8-4bdb-bb78-dd7a0095004e
,07-15 15:22:32.878  4200  4216 D BtGatt.GattService: onClientRegistered() - UUID=dac9da2c-67d8-4bdb-bb78-dd7a0095004e, clientIf=5
07-15 15:22:32.878  3840  3852 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-15 15:22:32.879  4200  4211 D BtGatt.GattService: start scan with filters
,07-15 15:22:32.886  4200  4219 D BtGatt.ScanManager: handling starting scan
,07-15 15:22:32.886  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-15 15:22:32.886  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-15 15:22:32.886  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-15 15:22:32.886  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-15 15:22:32.886  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,07-15 15:22:32.887  3840  3840 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
07-15 15:22:32.887  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-15 15:22:32.889  4200  4216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-15 15:22:32.889  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-15 15:22:32.889  4200  4219 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,07-15 15:22:32.890  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-15 15:22:32.891  4200  4216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,07-15 15:22:32.891  3840  3840 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-15 15:22:32.891  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-15 15:22:32.891  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-15 15:22:32.891  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-15 15:22:32.891  4200  4219 D BtGatt.ScanManager: Starting BLE batch scan
07-15 15:22:32.891  3840  3888 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,07-15 15:22:32.892  4200  4219 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-15 15:22:32.892  3840  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-15 15:22:32.893  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:32.893  3840  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:32.894  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-15 15:22:32.894  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:22:32.894  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:32.894  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-15 15:22:32.894  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bfa7317 removed from the list
07-15 15:22:32.894  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-15 15:22:32.894  4200  4216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-15 15:22:32.894  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37e3304 removed from the list
07-15 15:22:32.895  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
,07-15 15:22:32.895  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-15 15:22:32.895  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-15 15:22:32.896  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:22:32.896  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
,07-15 15:22:32.896  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:32.896  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-15 15:22:32.896  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:32.896  4200  4216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-15 15:22:32.896  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37e3304 not in the list,
07-15 15:22:32.897  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,07-15 15:22:32.897  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,07-15 15:22:32.897  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-15 15:22:32.897  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-15 15:22:32.897  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-15 15:22:32.897  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-15 15:22:32.898  3840  3888 D BluetoothAdapter: STATE_ON
07-15 15:22:32.899  4200  4210 D BtGatt.GattService: stopScan() - queue size =1
07-15 15:22:32.900  4200  4238 D BtGatt.GattService: unregisterClient() - clientIf=5
07-15 15:22:32.900  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-15 15:22:32.900  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-15 15:22:32.901  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-15 15:22:32.901  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-15 15:22:32.901  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-15 15:22:32.901  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-15 15:22:32.901  4200  4216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-15 15:22:32.901  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-15 15:22:32.901  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-15 15:22:32.902  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-15 15:22:32.902  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-15 15:22:32.902  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:22:32.902  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-15 15:22:32.902  4200  4219 D BtGatt.ScanManager: stopping BLe Batch
07-15 15:22:32.902  3840  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-15 15:22:32.902  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:22:32.902  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-15 15:22:32.905  4200  4216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-15 15:22:32.905  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-15 15:22:32.906  4200  4219 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-15 15:22:32.908  3840  3840 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-15 15:22:32.908  3840  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-15 15:22:32.909  4200  4216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,07-15 15:22:32.909  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,07-15 15:22:32.914  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,07-15 15:22:32.915  3840  3840 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-15 15:22:32.915  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-15 15:22:32.917  3840  3888 D BluetoothAdapter: STATE_ON
,07-15 15:22:32.917  3840  3888 D BluetoothLeScanner: could not find callback wrapper
07-15 15:22:32.917  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-15 15:22:32.917  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-15 15:22:32.917  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-15 15:22:32.917  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a929b3 removed from the list
07-15 15:22:32.917  3840  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-15 15:22:32.917  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-15 15:22:32.917  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:32.918  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-15 15:22:32.918  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-15 15:22:32.918  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd76b22 removed from the list
,07-15 15:22:32.919  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-15 15:22:32.919  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@546de9c added. We now have 2 listener(s)
,07-15 15:22:32.921  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-15 15:22:32.921  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-15 15:22:32.921  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-15 15:22:32.922  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:22:32.922  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa880a5 added. We now have 9 listener(s)
07-15 15:22:32.922  3840  3888 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-15 15:22:32.924  3840  3840 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-15 15:22:32.925  3840  3840 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-15 15:22:32.925  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-15 15:22:32.925  3840  3840 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-15 15:22:32.928  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-15 15:22:32.933  3840  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:22:32.933  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:32.933  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:32.933  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:32.933  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:32.933  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:32.933  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:32.933  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:22:32.935  3840  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:22:32.935  3840  3888 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-15 15:22:32.936  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-15 15:22:32.936  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc61c2b added. We now have 3 listener(s)
,07-15 15:22:32.938  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:22:32.938  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-15 15:22:32.939  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-15 15:22:32.939  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-15 15:22:32.939  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-15 15:22:32.939  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8314888 added. We now have 10 listener(s)
07-15 15:22:32.939  3840  3888 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-15 15:22:32.939  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-15 15:22:32.939  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
07-15 15:22:32.940  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-15 15:22:32.940  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-15 15:22:32.940  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:32.944  3840  3888 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-15 15:22:32.944  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-15 15:22:32.953  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-15 15:22:32.954  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-15 15:22:32.954  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-15 15:22:32.954  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-15 15:22:32.954  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-15 15:22:32.954  3840  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,07-15 15:22:32.955  3840  3888 D BluetoothAdapter: STATE_ON
07-15 15:22:32.958  4200  4238 D BtGatt.GattService: registerClient() - UUID=ed3bf461-8dfc-4c18-a5bc-2cc649aed340
,07-15 15:22:32.958  4200  4216 D BtGatt.GattService: onClientRegistered() - UUID=ed3bf461-8dfc-4c18-a5bc-2cc649aed340, clientIf=5
07-15 15:22:32.959  3840  3850 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-15 15:22:32.960  4200  4229 D BtGatt.GattService: start scan with filters
,07-15 15:22:32.963  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-15 15:22:32.964  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,07-15 15:22:32.964  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-15 15:22:32.964  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-15 15:22:32.964  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
07-15 15:22:32.964  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-15 15:22:32.964  4200  4219 D BtGatt.ScanManager: handling starting scan
,07-15 15:22:32.964  3840  3840 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
07-15 15:22:32.966  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-15 15:22:32.967  3840  3840 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-15 15:22:32.967  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-15 15:22:32.968  4200  4216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-15 15:22:32.968  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-15 15:22:32.969  4200  4219 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,07-15 15:22:32.970  3840  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:32.970  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:32.970  3840  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-15 15:22:32.971  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:32.971  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:22:32.971  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
,07-15 15:22:32.971  4200  4216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-15 15:22:32.971  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-15 15:22:32.971  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-15 15:22:32.971  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@546de9c removed from the list
07-15 15:22:32.971  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:32.971  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa880a5 removed from the list
07-15 15:22:32.972  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
,07-15 15:22:32.972  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:32.972  4200  4219 D BtGatt.ScanManager: Starting BLE batch scan
07-15 15:22:32.972  4200  4219 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-15 15:22:32.972  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:22:32.972  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
07-15 15:22:32.973  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:32.973  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:32.973  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-15 15:22:32.973  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa880a5 not in the list
07-15 15:22:32.973  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-15 15:22:32.973  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-15 15:22:32.973  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-15 15:22:32.974  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,07-15 15:22:32.974  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-15 15:22:32.975  3840  3888 D BluetoothAdapter: STATE_ON
07-15 15:22:32.976  4200  4229 D BtGatt.GattService: stopScan() - queue size =1
07-15 15:22:32.976  4200  4216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,07-15 15:22:32.976  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-15 15:22:32.976  4200  4211 D BtGatt.GattService: unregisterClient() - clientIf=5
07-15 15:22:32.977  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-15 15:22:32.977  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-15 15:22:32.977  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-15 15:22:32.977  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,07-15 15:22:32.977  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-15 15:22:32.977  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-15 15:22:32.977  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-15 15:22:32.978  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-15 15:22:32.978  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
,07-15 15:22:32.978  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-15 15:22:32.978  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-15 15:22:32.978  3840  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-15 15:22:32.978  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:22:32.978  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-15 15:22:32.978  4200  4216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-15 15:22:32.979  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-15 15:22:32.983  3840  3840 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-15 15:22:32.983  3840  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-15 15:22:32.985  4200  4216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-15 15:22:32.985  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-15 15:22:32.986  4200  4219 D BtGatt.ScanManager: stopping BLe Batch
,07-15 15:22:32.990  4200  4216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,07-15 15:22:32.990  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-15 15:22:32.991  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-15 15:22:32.992  4200  4219 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-15 15:22:32.992  3840  3840 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-15 15:22:32.992  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-15 15:22:32.992  3840  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-15 15:22:32.994  4200  4216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-15 15:22:32.994  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-15 15:22:32.996  3840  3840 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-15 15:22:32.997  3840  3840 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,07-15 15:22:32.998  3840  3888 D BluetoothAdapter: STATE_ON
,07-15 15:22:32.998  3840  3888 D BluetoothLeScanner: could not find callback wrapper
07-15 15:22:32.998  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-15 15:22:32.997  3840  3840 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-15 15:22:32.998  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-15 15:22:32.998  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-15 15:22:32.998  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8314888 removed from the list
07-15 15:22:32.998  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:32.998  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:32.998  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:32.999  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-15 15:22:32.999  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc61c2b removed from the list
,07-15 15:22:33.000  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-15 15:22:33.000  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3571f5d added. We now have 2 listener(s)
07-15 15:22:33.002  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-15 15:22:33.002  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:22:33.002  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-15 15:22:33.003  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-15 15:22:33.003  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@694e0d2 added. We now have 9 listener(s)
07-15 15:22:33.003  3840  3888 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-15 15:22:33.006  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-15 15:22:33.009  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-15 15:22:33.013  3840  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:22:33.013  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:33.013  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:33.013  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:33.013  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:33.013  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:33.013  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:33.013  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:22:33.015  3840  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:22:33.015  3840  3888 D io.jxcore.node.ConnectivityMonitor: start: OK
07-15 15:22:33.016  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-15 15:22:33.016  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f0ea0a0 added. We now have 3 listener(s)
,07-15 15:22:33.017  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-15 15:22:33.018  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:22:33.018  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-15 15:22:33.018  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:22:33.018  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eb5459 added. We now have 10 listener(s)
,07-15 15:22:33.018  3840  3888 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:22:33.019  3840  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:33.019  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:22:33.019  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:33.019  3840  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:33.019  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:33.019  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.019  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
07-15 15:22:33.019  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-15 15:22:33.019  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3571f5d removed from the list
07-15 15:22:33.019  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.019  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@694e0d2 removed from the list
,07-15 15:22:33.021  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:33.021  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:33.021  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.022  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.022  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
,07-15 15:22:33.022  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.022  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.022  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.022  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@694e0d2 not in the list
07-15 15:22:33.022  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.022  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
,07-15 15:22:33.022  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.022  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.023  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.023  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eb5459 removed from the list
07-15 15:22:33.023  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:33.023  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:22:33.023  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.023  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-15 15:22:33.023  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f0ea0a0 removed from the list
07-15 15:22:33.024  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-15 15:22:33.024  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc381e added. We now have 2 listener(s)
,07-15 15:22:33.026  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-15 15:22:33.026  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:22:33.026  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-15 15:22:33.026  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:22:33.026  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff added. We now have 9 listener(s)
07-15 15:22:33.026  3840  3888 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-15 15:22:33.029  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-15 15:22:33.032  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-15 15:22:33.037  3840  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:22:33.037  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:33.037  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:33.037  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:33.037  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:33.037  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:33.037  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:33.037  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:22:33.039  3840  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:22:33.040  3840  3888 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-15 15:22:33.041  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:33.042  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-15 15:22:33.042  3840  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-15 15:22:33.042  3840  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-15 15:22:33.043  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:22:33.043  3840  3888 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,07-15 15:22:33.043  3840  3888 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-15 15:22:33.044  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,07-15 15:22:33.044  3840  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-15 15:22:33.044  3840  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-15 15:22:33.045  3840  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:33.045  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:33.045  3840  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-15 15:22:33.046  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-15 15:22:33.046  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:22:33.046  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
,07-15 15:22:33.046  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-15 15:22:33.047  3840  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc381e removed from the list
,07-15 15:22:33.047  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.047  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff removed from the list
,07-15 15:22:33.047  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:33.047  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.048  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.048  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
,07-15 15:22:33.049  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:22:33.049  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.049  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.050  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.053  3840  3888 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,07-15 15:22:33.056  3840  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:33.056  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:33.056  3840  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-15 15:22:33.056  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:33.057  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.057  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.057  3840  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc381e not in the list
07-15 15:22:33.057  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-15 15:22:33.057  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.057  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
,07-15 15:22:33.057  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.058  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.058  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.058  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
07-15 15:22:33.058  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:22:33.058  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.058  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.058  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.065  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-15 15:22:33.065  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,07-15 15:22:33.065  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-15 15:22:33.065  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,07-15 15:22:33.065  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-15 15:22:33.065  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-15 15:22:33.065  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-15 15:22:33.066  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-15 15:22:33.066  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,07-15 15:22:33.066  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-15 15:22:33.066  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-15 15:22:33.066  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-15 15:22:33.066  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-15 15:22:33.066  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,07-15 15:22:33.067  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-15 15:22:33.067  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-15 15:22:33.067  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-15 15:22:33.067  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-15 15:22:33.067  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-15 15:22:33.067  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,07-15 15:22:33.067  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-15 15:22:33.068  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-15 15:22:33.068  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-15 15:22:33.068  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-15 15:22:33.068  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-15 15:22:33.068  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-15 15:22:33.068  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,07-15 15:22:33.068  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-15 15:22:33.069  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-15 15:22:33.069  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-15 15:22:33.069  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-15 15:22:33.069  3840  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-15 15:22:33.069  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:33.069  3840  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:33.069  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:33.070  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.070  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.070  3840  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc381e not in the list
07-15 15:22:33.070  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.070  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.070  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
,07-15 15:22:33.070  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.071  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.071  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.071  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
07-15 15:22:33.071  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.071  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,07-15 15:22:33.071  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.071  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.072  3840  3888 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-15 15:22:33.075  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:22:33.081  3840  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:22:33.081  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:33.081  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:33.081  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:33.081  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:33.081  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:33.081  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:33.081  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:22:33.084  3840  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:22:33.084  3840  3888 D io.jxcore.node.ConnectivityMonitor: start: OK
07-15 15:22:33.085  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-15 15:22:33.085  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-15 15:22:33.085  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:22:33.085  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-15 15:22:33.089  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:22:33.089  3840  3888 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-15 15:22:33.090  3840  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-15 15:22:33.091  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:22:33.099  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-15 15:22:33.101  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-15 15:22:33.101  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-15 15:22:33.101  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-15 15:22:33.101  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-15 15:22:33.102  3840  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,07-15 15:22:33.104  3840  3888 D BluetoothAdapter: STATE_ON
,07-15 15:22:33.107   874  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-15 15:22:33.108  4200  4239 D BtGatt.GattService: registerClient() - UUID=2c291113-7182-422b-ab68-9b6b687763bc
,07-15 15:22:33.109  4200  4216 D BtGatt.GattService: onClientRegistered() - UUID=2c291113-7182-422b-ab68-9b6b687763bc, clientIf=5
07-15 15:22:33.109  3840  3852 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-15 15:22:33.110  4200  4211 D BtGatt.GattService: start scan with filters
,07-15 15:22:33.114  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-15 15:22:33.114  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-15 15:22:33.114  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-15 15:22:33.114  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-15 15:22:33.115  4200  4219 D BtGatt.ScanManager: handling starting scan
07-15 15:22:33.115  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
07-15 15:22:33.115  3840  3840 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,07-15 15:22:33.116  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-15 15:22:33.119  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-15 15:22:33.119  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-15 15:22:33.120  3840  3840 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-15 15:22:33.120  3840  3840 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-15 15:22:33.120  3840  3840 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-15 15:22:33.120  3840  3888 I io.jxcore.node.ConnectionHelper: start: OK
,07-15 15:22:33.124  3840  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-15 15:22:33.124  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:33.124  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:22:33.125  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 6 listener(s) left
,07-15 15:22:33.125  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,07-15 15:22:33.125  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-15 15:22:33.125  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-15 15:22:33.125  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,07-15 15:22:33.125  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-15 15:22:33.126  3840  3888 D BluetoothAdapter: STATE_ON
07-15 15:22:33.127  4200  4211 D BtGatt.GattService: stopScan() - queue size =1
07-15 15:22:33.128  4200  4210 D BtGatt.GattService: unregisterClient() - clientIf=5,
07-15 15:22:33.130  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-15 15:22:33.130  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-15 15:22:33.130  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-15 15:22:33.131  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,07-15 15:22:33.131  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,07-15 15:22:33.131  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,07-15 15:22:33.131  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-15 15:22:33.131  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
07-15 15:22:33.131  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
07-15 15:22:33.132  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
,07-15 15:22:33.132  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
,07-15 15:22:33.132  4200  4216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,07-15 15:22:33.132  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-15 15:22:33.132  3840  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-15 15:22:33.132  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-15 15:22:33.132  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-15 15:22:33.132  4200  4219 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-15 15:22:33.133  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-15 15:22:33.133  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.133  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 6 listener(s) left
07-15 15:22:33.133  3840  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc381e not in the list
,07-15 15:22:33.133  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.133  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
,07-15 15:22:33.133  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:33.134  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
,07-15 15:22:33.135  3840  3888 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-15 15:22:33.138  3840  3840 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-15 15:22:33.138  3840  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-15 15:22:33.141  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:22:33.142  4200  4216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-15 15:22:33.142  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-15 15:22:33.142  4200  4219 D BtGatt.ScanManager: Starting BLE batch scan
,07-15 15:22:33.142  4200  4219 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-15 15:22:33.143  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-15 15:22:33.146  3840  3840 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-15 15:22:33.146  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
07-15 15:22:33.146  3840  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-15 15:22:33.148  3840  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:22:33.148  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:33.148  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:33.148  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:33.148  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:33.148  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:33.148  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:33.148  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:22:33.149  3840  3840 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-15 15:22:33.150  3840  3840 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-15 15:22:33.150  3840  3840 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-15 15:22:33.152  3840  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:22:33.152  3840  3888 D io.jxcore.node.ConnectivityMonitor: start: OK
07-15 15:22:33.153  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-15 15:22:33.154  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-15 15:22:33.154  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:33.154  4200  4216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-15 15:22:33.154  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-15 15:22:33.158  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:22:33.160  3840  3888 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-15 15:22:33.160  4200  4216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,07-15 15:22:33.161  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-15 15:22:33.160  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-15 15:22:33.161  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,07-15 15:22:33.161  3840  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,07-15 15:22:33.162  3840  3888 D BluetoothAdapter: STATE_ON
,07-15 15:22:33.165  4200  4210 D BtGatt.GattService: registerClient() - UUID=f810b055-3077-4dc0-95dd-a725d3a814b9
,07-15 15:22:33.165  4200  4216 D BtGatt.GattService: onClientRegistered() - UUID=f810b055-3077-4dc0-95dd-a725d3a814b9, clientIf=5
07-15 15:22:33.165  3840  3850 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-15 15:22:33.166  4200  4238 D BtGatt.GattService: start scan with filters
07-15 15:22:33.168  4200  4216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,07-15 15:22:33.168  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-15 15:22:33.168  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-15 15:22:33.168  4200  4219 D BtGatt.ScanManager: stopping BLe Batch
,07-15 15:22:33.169  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-15 15:22:33.169  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,07-15 15:22:33.169  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-15 15:22:33.169  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
07-15 15:22:33.169  3840  3840 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
07-15 15:22:33.169  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-15 15:22:33.172  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-15 15:22:33.172  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-15 15:22:33.172  3840  3840 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-15 15:22:33.172  3840  3840 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-15 15:22:33.173  3840  3840 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-15 15:22:33.173  3840  3888 I io.jxcore.node.ConnectionHelper: start: OK
07-15 15:22:33.175  4200  4216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,07-15 15:22:33.175  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-15 15:22:33.175  4200  4219 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-15 15:22:33.176   874  1314 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.00 rxSuccessRate=12.25 delta 1000 -> 994
,07-15 15:22:33.176  3840  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:33.177  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:33.177  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.177  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 6 listener(s) left
07-15 15:22:33.177  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-15 15:22:33.177  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,07-15 15:22:33.177  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-15 15:22:33.177  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-15 15:22:33.177  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-15 15:22:33.178  3840  3888 D BluetoothAdapter: STATE_ON
07-15 15:22:33.179   874  1314 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
07-15 15:22:33.179   874  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-15 15:22:33.179  4200  4238 D BtGatt.GattService: stopScan() - queue size =0
07-15 15:22:33.180  4200  4239 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-15 15:22:33.180  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-15 15:22:33.180  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-15 15:22:33.180  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-15 15:22:33.181  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-15 15:22:33.181  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,07-15 15:22:33.181  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-15 15:22:33.181  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-15 15:22:33.181  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-15 15:22:33.181  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
07-15 15:22:33.182  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
07-15 15:22:33.182  4200  4216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,07-15 15:22:33.182  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-15 15:22:33.182  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-15 15:22:33.182  3840  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-15 15:22:33.182  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:22:33.182  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
,07-15 15:22:33.183  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-15 15:22:33.183  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.184  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 6 listener(s) left
07-15 15:22:33.184  3840  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc381e not in the list
07-15 15:22:33.184  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.184  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
,07-15 15:22:33.184  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:33.184  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
07-15 15:22:33.186  4200  4219 D BtGatt.ScanManager: handling starting scan
,07-15 15:22:33.187  3840  3840 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-15 15:22:33.187  3840  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-15 15:22:33.187   874  1314 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
07-15 15:22:33.191  4200  4216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-15 15:22:33.191  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-15 15:22:33.191  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-15 15:22:33.192  3840  3840 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-15 15:22:33.192  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-15 15:22:33.192  3840  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-15 15:22:33.195  4200  4219 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-15 15:22:33.195  3840  3840 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-15 15:22:33.195  3840  3840 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,07-15 15:22:33.195  3840  3840 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-15 15:22:33.196  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
,07-15 15:22:33.196  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.196  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-15 15:22:33.197  3840  3888 D BluetoothAdapter: STATE_ON
07-15 15:22:33.197  3840  3888 D BluetoothLeScanner: could not find callback wrapper
,07-15 15:22:33.197  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-15 15:22:33.197  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-15 15:22:33.197  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.198  3840  3888 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-15 15:22:33.199  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-15 15:22:33.199  4200  4216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-15 15:22:33.200  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-15 15:22:33.200  4200  4219 D BtGatt.ScanManager: Starting BLE batch scan
07-15 15:22:33.200  4200  4219 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,07-15 15:22:33.202  3840  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:22:33.202  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:33.202  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:33.202  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:33.202  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:33.202  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:33.202  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:33.202  3840  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:22:33.203  3840  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:22:33.204  3840  3888 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-15 15:22:33.204  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-15 15:22:33.204  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-15 15:22:33.204  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:22:33.204  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-15 15:22:33.205  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:22:33.208  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:22:33.208  3840  3888 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-15 15:22:33.208  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-15 15:22:33.208  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-15 15:22:33.208  3840  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-15 15:22:33.209  3840  3888 D BluetoothAdapter: STATE_ON
,07-15 15:22:33.209  4200  4216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-15 15:22:33.209  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-15 15:22:33.211  4200  4229 D BtGatt.GattService: registerClient() - UUID=a734ce03-c1bf-4313-acb3-6e73d19aebe2
,07-15 15:22:33.211  4200  4216 D BtGatt.GattService: onClientRegistered() - UUID=a734ce03-c1bf-4313-acb3-6e73d19aebe2, clientIf=5
07-15 15:22:33.211  3840  3852 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-15 15:22:33.211  4200  4238 D BtGatt.GattService: start scan with filters
,07-15 15:22:33.214  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-15 15:22:33.214  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-15 15:22:33.214  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-15 15:22:33.214  4200  4216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-15 15:22:33.214  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-15 15:22:33.214  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-15 15:22:33.214  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
07-15 15:22:33.214  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-15 15:22:33.214  3840  3840 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
07-15 15:22:33.215  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-15 15:22:33.216  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-15 15:22:33.216  3840  3888 I io.jxcore.node.ConnectionHelper: start: OK
07-15 15:22:33.216  3840  3840 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-15 15:22:33.216  3840  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:33.216  3840  3840 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-15 15:22:33.216  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:33.216  3840  3840 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-15 15:22:33.216  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.216  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 6 listener(s) left
,07-15 15:22:33.216  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-15 15:22:33.216  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-15 15:22:33.216  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-15 15:22:33.216  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-15 15:22:33.216  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-15 15:22:33.217  3840  3888 D BluetoothAdapter: STATE_ON
07-15 15:22:33.217  4200  4210 D BtGatt.GattService: stopScan() - queue size =0
,07-15 15:22:33.218  4200  4229 D BtGatt.GattService: unregisterClient() - clientIf=5
07-15 15:22:33.218  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-15 15:22:33.218  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-15 15:22:33.218  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-15 15:22:33.218  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-15 15:22:33.218  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-15 15:22:33.218  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-15 15:22:33.218  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-15 15:22:33.218  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-15 15:22:33.218  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
07-15 15:22:33.219  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
,07-15 15:22:33.219  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-15 15:22:33.219  3840  3840 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:33.219  3840  3840 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,07-15 15:22:33.219  3840  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-15 15:22:33.219  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:22:33.219  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-15 15:22:33.220  4200  4216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-15 15:22:33.220  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-15 15:22:33.220  3840  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-15 15:22:33.220  4200  4219 D BtGatt.ScanManager: stopping BLe Batch
,07-15 15:22:33.220  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:33.220  3840  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:33.220  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:33.220  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:22:33.220  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 6 listener(s) left
07-15 15:22:33.222  3840  3840 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-15 15:22:33.222  3840  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-15 15:22:33.223  3840  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc381e not in the list
07-15 15:22:33.223  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.224  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.224  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:33.224  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
,07-15 15:22:33.225  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-15 15:22:33.226  4200  4216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,07-15 15:22:33.226  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-15 15:22:33.226  3840  3840 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-15 15:22:33.226  4200  4219 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-15 15:22:33.226  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-15 15:22:33.226  3840  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-15 15:22:33.230  3840  3840 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-15 15:22:33.230  3840  3840 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-15 15:22:33.230  3840  3840 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-15 15:22:33.231   874  1314 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
07-15 15:22:33.231  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
07-15 15:22:33.231  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.232  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-15 15:22:33.232  4200  4216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-15 15:22:33.232  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-15 15:22:33.232  3840  3888 D BluetoothAdapter: STATE_ON
07-15 15:22:33.232  3840  3888 D BluetoothLeScanner: could not find callback wrapper
07-15 15:22:33.232  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-15 15:22:33.232  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.232  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
,07-15 15:22:33.233  1466  1466 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-15 15:22:33.233  3840  3888 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-15 15:22:33.233  4200  4219 D BtGatt.ScanManager: handling starting scan
07-15 15:22:33.234  3840  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-15 15:22:33.234  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:33.234  3840  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-15 15:22:33.234  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:33.234  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.234  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.234  3840  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc381e not in the list
07-15 15:22:33.234  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.235  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
,07-15 15:22:33.235  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
,07-15 15:22:33.235  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.235  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.235  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:22:33.235  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
07-15 15:22:33.235  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.235  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.235  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-15 15:22:33.235  3840  3888 D BluetoothAdapter: STATE_ON
07-15 15:22:33.236  3840  3888 D BluetoothLeScanner: could not find callback wrapper
07-15 15:22:33.236  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-15 15:22:33.236  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-15 15:22:33.236  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.236  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,07-15 15:22:33.236  3840  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:33.237  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:33.237  3840  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-15 15:22:33.237  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:33.237  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.237  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.237  3840  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc381e not in the list
,07-15 15:22:33.237  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.237  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.237  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
,07-15 15:22:33.237  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.237  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.237  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.237  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
,07-15 15:22:33.237  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.237  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.238  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-15 15:22:33.238  3840  3888 D BluetoothAdapter: STATE_ON
,07-15 15:22:33.238  3840  3888 D BluetoothLeScanner: could not find callback wrapper
07-15 15:22:33.238  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-15 15:22:33.238  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.238  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
,07-15 15:22:33.239  4200  4216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-15 15:22:33.239  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-15 15:22:33.239  3840  3888 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-15 15:22:33.239  3840  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-15 15:22:33.239  4200  4219 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-15 15:22:33.239  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-15 15:22:33.239  3840  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:33.239  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:33.239  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.239  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,07-15 15:22:33.239  3840  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc381e not in the list
07-15 15:22:33.240  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-15 15:22:33.240  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
,07-15 15:22:33.240  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:33.240  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.240  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,07-15 15:22:33.240  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.240  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
07-15 15:22:33.240  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:22:33.240  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.240  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-15 15:22:33.241  3840  3888 D BluetoothAdapter: STATE_ON
,07-15 15:22:33.241  3840  3888 D BluetoothLeScanner: could not find callback wrapper
07-15 15:22:33.241  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-15 15:22:33.241  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-15 15:22:33.241  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.241  3840  3888 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-15 15:22:33.241  3840  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:33.242  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-15 15:22:33.242  3840  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:33.242  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:33.242  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.242  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.242  3840  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc381e not in the list
,07-15 15:22:33.242  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.242  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.242  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:33.242  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.242  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,07-15 15:22:33.242  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.242  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
07-15 15:22:33.242  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.242  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.242  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-15 15:22:33.243  3840  3888 D BluetoothAdapter: STATE_ON
07-15 15:22:33.243  3840  3888 D BluetoothLeScanner: could not find callback wrapper
07-15 15:22:33.243  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-15 15:22:33.243  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.243  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.244  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,07-15 15:22:33.244  4200  4216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-15 15:22:33.244  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-15 15:22:33.244  3840  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-15 15:22:33.244  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-15 15:22:33.244  3840  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-15 15:22:33.244  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-15 15:22:33.244  3840  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-15 15:22:33.244  3840  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:33.245  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-15 15:22:33.245  3840  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:33.245  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-15 15:22:33.245  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.245  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.245  3840  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc381e not in the list
07-15 15:22:33.245  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.245  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.245  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:33.245  4200  4219 D BtGatt.ScanManager: Starting BLE batch scan
,07-15 15:22:33.245  4200  4219 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-15 15:22:33.245  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.245  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.245  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.245  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
07-15 15:22:33.246  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.246  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.246  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-15 15:22:33.246  3840  3888 D BluetoothAdapter: STATE_ON
07-15 15:22:33.246  3840  3888 D BluetoothLeScanner: could not find callback wrapper
07-15 15:22:33.247  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-15 15:22:33.247  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-15 15:22:33.247  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
,07-15 15:22:33.248  3840  3888 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-15 15:22:33.248  3840  3888 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-15 15:22:33.248  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-15 15:22:33.249  3840  3888 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-15 15:22:33.249  3840  3888 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-15 15:22:33.249  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-15 15:22:33.249  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-15 15:22:33.249  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-15 15:22:33.250  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-15 15:22:33.250  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-15 15:22:33.250  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-15 15:22:33.250  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-15 15:22:33.250  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-15 15:22:33.250  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-15 15:22:33.250  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,07-15 15:22:33.250  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-15 15:22:33.250  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-15 15:22:33.251  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-15 15:22:33.251  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-15 15:22:33.252  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-15 15:22:33.252  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-15 15:22:33.252  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-15 15:22:33.252  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-15 15:22:33.252  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,07-15 15:22:33.253  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,07-15 15:22:33.253  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-15 15:22:33.253  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-15 15:22:33.253  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-15 15:22:33.253  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-15 15:22:33.253  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,07-15 15:22:33.253  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-15 15:22:33.253  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-15 15:22:33.253  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-15 15:22:33.253  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-15 15:22:33.253  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-15 15:22:33.254  3840  3888 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-15 15:22:33.255  3840  3888 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-15 15:22:33.255  3840  3888 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-15 15:22:33.255  3840  3888 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-15 15:22:33.255  3840  3888 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-15 15:22:33.255  3840  3888 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-15 15:22:33.255  3840  3888 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-15 15:22:33.255  3840  3888 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,07-15 15:22:33.256  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
07-15 15:22:33.256  4200  4216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-15 15:22:33.256  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-15 15:22:33.259  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
07-15 15:22:33.260  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
07-15 15:22:33.260  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
07-15 15:22:33.261  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
07-15 15:22:33.261  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-15 15:22:33.261  3840  3888 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-15 15:22:33.261  3840  3888 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-15 15:22:33.261  3840  3888 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,07-15 15:22:33.261  4200  4216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-15 15:22:33.262  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-15 15:22:33.262  3840  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:33.262  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:33.262  3840  4255 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 463)
07-15 15:22:33.262  3840  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:33.262  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:33.262  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.262  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.263  3840  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc381e not in the list
07-15 15:22:33.263  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-15 15:22:33.263  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.263  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:33.263  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.263  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.263  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.263  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
07-15 15:22:33.263  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.263  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.263  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-15 15:22:33.264  3840  3888 D BluetoothAdapter: STATE_ON
,07-15 15:22:33.264  3840  3888 D BluetoothLeScanner: could not find callback wrapper
07-15 15:22:33.264  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-15 15:22:33.264  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.264  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.265  3840  3888 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-15 15:22:33.265  3840  4255 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-15 15:22:33.265  3840  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:33.265  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:33.265  3840  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:33.265  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:33.265  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.265  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.265  3840  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc381e not in the list
07-15 15:22:33.265  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.265  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
,07-15 15:22:33.265  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:33.265  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.265  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.265  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.266  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
07-15 15:22:33.266  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.266  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.266  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-15 15:22:33.266  3840  3888 D BluetoothAdapter: STATE_ON
07-15 15:22:33.266  3840  3888 D BluetoothLeScanner: could not find callback wrapper
07-15 15:22:33.266  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-15 15:22:33.266  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.266  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.267  3840  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:33.267  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:33.267  3840  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:33.267  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:33.267  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.267  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.267  3840  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc381e not in the list
07-15 15:22:33.267  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.267  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.267  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
,07-15 15:22:33.267  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.267  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.267  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.268  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
07-15 15:22:33.268  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.268  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.268  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-15 15:22:33.268  3840  3888 D BluetoothAdapter: STATE_ON
07-15 15:22:33.268  3840  3888 D BluetoothLeScanner: could not find callback wrapper
07-15 15:22:33.268  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-15 15:22:33.268  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.268  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.269  3840  3888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-15 15:22:33.269  3840  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-15 15:22:33.269  4200  4216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-15 15:22:33.269  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-15 15:22:33.269  4200  4219 D BtGatt.ScanManager: stopping BLe Batch
07-15 15:22:33.269  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:33.270  3840  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:33.270  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:33.270  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.270  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.270  3840  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc381e not in the list
07-15 15:22:33.270  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.270  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
,07-15 15:22:33.270  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:33.270  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.270  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.270  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.270  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
07-15 15:22:33.270  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.270  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.271  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-15 15:22:33.271  3840  3888 D BluetoothAdapter: STATE_ON
,07-15 15:22:33.271  3840  3888 D BluetoothLeScanner: could not find callback wrapper
07-15 15:22:33.271  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-15 15:22:33.271  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.271  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.272  3840  3888 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-15 15:22:33.272  3840  3888 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-15 15:22:33.272  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,07-15 15:22:33.272  3840  3888 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-15 15:22:33.272  3840  3888 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-15 15:22:33.272  3840  3888 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-15 15:22:33.272  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-15 15:22:33.272  3840  3888 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-15 15:22:33.272  3840  3888 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-15 15:22:33.272  3840  3888 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,07-15 15:22:33.272  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-15 15:22:33.272  3840  3888 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-15 15:22:33.272  3840  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:33.272  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:33.272  3840  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-15 15:22:33.273  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:33.273  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:22:33.273  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.273  3840  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc381e not in the list
07-15 15:22:33.273  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-15 15:22:33.273  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.273  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:33.273  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.273  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.273  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.273  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
07-15 15:22:33.273  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.273  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.274  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-15 15:22:33.274  3840  3888 D BluetoothAdapter: STATE_ON
07-15 15:22:33.274  3840  3888 D BluetoothLeScanner: could not find callback wrapper
07-15 15:22:33.274  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-15 15:22:33.274  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.274  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.275  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:33.275  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.275  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.275  3840  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc381e not in the list
07-15 15:22:33.275  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.275  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.275  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:33.275  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.275  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.275  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.275  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.275  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:33.275  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.275  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.275  3840  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnec,torlib.ConnectionManager@2bc381e not in the list
07-15 15:22:33.275  3840  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:33.276  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:33.276  3840  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:33.276  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:33.276  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.276  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.276  3840  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc381e not in the list
07-15 15:22:33.276  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.276  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.276  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:33.276  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.276  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.276  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.276  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
07-15 15:22:33.276  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.276  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.276  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-15 15:22:33.277  3840  3888 D BluetoothAdapter: STATE_ON
07-15 15:22:33.277  3840  3888 D BluetoothLeScanner: could not find callback wrapper
07-15 15:22:33.277  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-15 15:22:33.277  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.277  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.278  3840  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-15 15:22:33.278  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:22:33.279  4200  4216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-15 15:22:33.279  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-15 15:22:33.279  4200  4219 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-15 15:22:33.279  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-15 15:22:33.279  3840  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-15 15:22:33.280  3,840  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-15 15:22:33.280  3840  3840 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-15 15:22:33.280  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-15 15:22:33.280  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:33.280  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-15 15:22:33.280  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-15 15:22:33.280  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-15 15:22:33.280  3840  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
07-15 15:22:33.281  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.280  3840  4257 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-15 15:22:33.281  3840  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc381e not in the list
07-15 15:22:33.281  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.281  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-15 15:22:33.281  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-15 15:22:33.281  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-15 15:22:33.281  3840  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-15 15:22:33.281  3840  3888 D BluetoothAdapter: STATE_ON
07-15 15:22:33.281  3840  3888 D BluetoothLeScanner: could not find callback wrapper
07-15 15:22:33.281  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-15 15:22:33.281  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-15 15:22:33.281  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-15 15:22:33.282  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.282  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
07-15 15:22:33.282  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.282  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.282  3840  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-15 15:22:33.282  3840  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-15 15:22:33.282  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:22:33.282  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-15 15:22:33.282  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.283  3840  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:33.283  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:33.283  3840  4257 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-15 15:22:33.283  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-15 15:22:33.283  3840  4257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-15 15:22:33.283  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.283  3840  4257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-15 15:22:33.283  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
07-15 15:22:33.284  3840  3840 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-15 15:22:33.284  3840  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-15 15:22:33.285  4200  4216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-15 15:22:33.285  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-15 15:22:33.287  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-15 15:22:33.287  3840  3840 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-15 15:22:33.287  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-15 15:22:33.287  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
07-15 15:22:33.288  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.288  3840  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-15 15:22:33.288  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:22:33.288  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:33.288  3840  3840 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-15 15:22:33.288  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-15 15:22:33.288  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.288  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
07-15 15:22:33.288  3840  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc381e not in the list
07-15 15:22:33.288  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.288  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.288  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:33.288  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.288  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
07-15 15:22:33.289  3840  3840 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-15 15:22:33.290  3840  3840 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-15 15:22:33.290  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
07-15 15:22:33.290  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.290  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-15 15:22:33.290  3840  3840 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-15 15:22:33.290  3840  3840 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-15 15:22:33.290  3840  3840 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-15 15:22:33.290  3840  3888 D BluetoothAdapter: STATE_ON
07-15 15:22:33.290  3840  3888 D BluetoothLeScanner: could not find callback wrapper
07-15 15:22:33.290  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-15 15:22:33.290  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.290  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.291  3840  3888 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-15 15:22:33.291  3840  3888 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-15 15:22:33.291  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-15 15:22:33.292  3840  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-15 15:22:33.292  3840  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:33.292  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:33.292  3840  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:33.292  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:33.292  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.292  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.292  3840  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc381e not in the list
07-15 15:22:33.292  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.292  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.292  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:33.292  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.292  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.292  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.293  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
07-15 15:22:33.293  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.293  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.293  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-15 15:22:33.294  3840  3888 D BluetoothAdapter: STATE_ON
07-15 15:22:33.294  3840  3888 D BluetoothLeScanner: could not find callback wrapper
07-15 15:22:33.294  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-15 15:22:33.294  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.295  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.297  3840  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:33.297  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:33.297  3840  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:33.297  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:33.297  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.297  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.297  3840  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc381e not in the list
07-15 15:22:33.297  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.297  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.297  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:33.297  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.298  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.298  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.298  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
07-15 15:22:33.298  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.298  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.298  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-15 15:22:33.298  3840  3888 D BluetoothAdapter: STATE_ON
07-15 15:22:33.298  3840  3888 D BluetoothLeScanner: could not find callback wrapper
07-15 15:22:33.298  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-15 15:22:33.298  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.298  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.299  3840  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:33.299  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:33.299  3840  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:33.299  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:33.299  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.299  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.299  3840  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc381e not in the list
07-15 15:22:33.300  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.300  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.300  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:33.300  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.300  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.300  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.300  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
07-15 15:22:33.300  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.300  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.300  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-15 15:22:33.301  3840  3888 D BluetoothAdapter: STATE_ON
07-15 15:22:33.301  3840  3888 D BluetoothLeScanner: could not find callback wrapper
07-15 15:22:33.301  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-15 15:22:33.301  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.301  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.301  3840  3888 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 00:11:22:33:44:55]
07-15 15:22:33.301  3840  3888 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID 00:11:22:33:44:55
07-15 15:22:33.302  3840  3840 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 00:11:22:33:44:55], Bluetooth address: 00:11:22:33:44:55, device name: , device address: 
07-15 15:22:33.302  3840  3888 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 00:11:22:33:44:55], added - the peer count is 1
07-15 15:22:33.302  3840  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-15 15:22:33.302  3840  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:33.302  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:33.302  3840  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:33.302  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:33.302  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.302  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.302  3840  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc381e not in the list
07-15 15:22:33.303  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.303  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.303  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:33.303  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.303  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.303  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.303  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
07-15 15:22:33.303  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.303  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.303  3840  3888 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
07-15 15:22:33.303  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-15 15:22:33.304  3840  3888 D BluetoothAdapter: STATE_ON
07-15 15:22:33.304  3840  3888 D BluetoothLeScanner: could not find callback wrapper
07-15 15:22:33.304  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-15 15:22:33.304  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.304  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.304  3840  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:33.304  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:33.304  3840  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:33.304  3840  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:33.304  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.304  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.304  3840  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc381e not in the list
07-15 15:22:33.304  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.304  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.305  3840  3888 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:33.305  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.305  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.305  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.305  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 3 listener(s) left
07-15 15:22:33.305  3840  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:33.305  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-15 15:22:33.305  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-15 15:22:33.305  3840  3888 D BluetoothAdapter: STATE_ON
07-15 15:22:33.305  3840  3888 D BluetoothLeScanner: could not find callback wrapper
07-15 15:22:33.305  3840  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-15 15:22:33.305  3840  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:33.306  3840  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87138ff not in the list
07-15 15:22:33.306  3840  3888 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 85
07-15 15:22:33.306  3840  3888 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 85
07-15 15:22:33.306  3840  3888 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-15 15:22:33.306  3840  3888 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-15 15:22:33.306  3840  3888 D com.test.thalitest.ThaliTestRunner: Total duration: 21947 ms
07-15 15:22:33.309  3840  3888 I jxcore-log: true
07-15 15:22:33.309  3840  3888 I jxcore-log: 
07-15 15:22:33.309  3840  3888 I jxcore-log: Total number of executed tests:  85
07-15 15:22:33.309  3840  3888 I jxcore-log: 
07-15 15:22:33.310  3840  3888 I jxcore-log: Number of passed tests:  85
07-15 15:22:33.310  3840  3888 I jxcore-log: 
07-15 15:22:33.310  3840  3888 I jxcore-log: Number of failed tests:  0
07-15 15:22:33.310  3840  3888 I jxcore-log: 
07-15 15:22:33.310  3840  3888 I jxcore-log: Number of ignored tests:  0
07-15 15:22:33.310  3840  3888 I jxcore-log: 
07-15 15:22:33.310  3840  3888 I jxcore-log: Total duration:  21947
07-15 15:22:33.310  3840  3888 I jxcore-log: 
07-15 15:22:33.311  3840  3888 I jxcore-log: My device name is: motorola-Nexus 6
07-15 15:22:33.311  3840  3888 I jxcore-log: 
07-15 15:22:33.313  3840  3888 I jxcore-log: WARN testUtils: myNameCallback not set!
07-15 15:22:33.313  3840  3888 I jxcore-log: 
,07-15 15:22:34.522  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-ASSOC-REJECT status_code=1
,07-15 15:22:35.976  1466  1466 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-15 15:22:37.374  3840  3888 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-15 15:22:37.374  3840  3888 I jxcore-log: 
,07-15 15:22:37.780  3840  3888 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-15 15:22:37.780  3840  3888 I jxcore-log: 
,07-15 15:22:37.805  3840  3888 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-15 15:22:37.805  3840  3888 I jxcore-log: 
,07-15 15:22:37.810  3840  3888 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-15 15:22:37.810  3840  3888 I jxcore-log: 
,07-15 15:22:37.827  3840  3888 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-15 15:22:37.827  3840  3888 I jxcore-log: 
,07-15 15:22:37.831  3840  3888 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-15 15:22:37.831  3840  3888 I jxcore-log: 
,07-15 15:22:38.396  4200  4222 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,07-15 15:22:38.397  4200  4225 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,07-15 15:22:38.398  3840  4255 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 463)
,07-15 15:22:38.398  3840  4255 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Maximum number of allowed retries (0) reached, giving up... (thread ID: 463)
,07-15 15:22:38.398  3840  4255 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 463)
,07-15 15:22:38.400  3840  3840 W org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnectionFailed: Failed to connect to peer [<no peer name> 00:11:22:33:44:55]: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,07-15 15:22:38.401  3840  3840 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,07-15 15:22:38.401  3840  3840 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-15 15:22:38.401  3840  3840 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-15 15:22:38.403  3840  4255 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: removeAndShutdownBluetoothClientThread: Failed to find a thread with ID 463
,07-15 15:22:38.403  3840  4255 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 463)
07-15 15:22:38.405  3840  4256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 463
07-15 15:22:38.405  3840  4256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 463)
,07-15 15:22:38.406  3840  4256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 463)
,07-15 15:22:39.876  3840  3888 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-15 15:22:39.876  3840  3888 I jxcore-log: 
,07-15 15:22:39.888  3840  3888 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-15 15:22:39.888  3840  3888 I jxcore-log: 
,07-15 15:22:39.898  3840  3888 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-15 15:22:39.898  3840  3888 I jxcore-log: 
,07-15 15:22:40.059  3840  3888 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-15 15:22:40.059  3840  3888 I jxcore-log: 
,07-15 15:22:40.107  1466  1466 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-15 15:22:40.148  1466  1466 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-15 15:22:40.151  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,07-15 15:22:40.156   874  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,07-15 15:22:40.171   874  1314 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-15 15:22:40.172   874  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-15 15:22:40.172   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-15 15:22:40.196   874  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-15 15:22:40.211   371   872 D CommandListener: Setting iface cfg
,07-15 15:22:40.213   874  1314 D WifiStateMachine: Start Dhcp Watchdog 3
,07-15 15:22:40.226   874  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,07-15 15:22:40.241   874  4260 D DhcpClient: Receive thread started
,07-15 15:22:40.324   874  1314 E native  : do suspend false
,07-15 15:22:40.342   874  1968 D DhcpClient: Broadcasting DHCPDISCOVER
,07-15 15:22:40.355   874  4260 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172776, domain null
,07-15 15:22:40.356   874  1968 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172776 seconds
,07-15 15:22:40.358   874  1968 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,07-15 15:22:40.371   874  4260 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-15 15:22:40.372   874  1968 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-15 15:22:40.376   371   872 D CommandListener: Setting iface cfg
,07-15 15:22:40.385   874  1968 D DhcpClient: Scheduling renewal in 86399s
,07-15 15:22:40.386   874  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,07-15 15:22:40.389   874  1314 E native  : do suspend true
,07-15 15:22:40.411   874  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-15 15:22:40.414   874  1314 D WifiConfigStore: No blacklist allowed without epno enabled
07-15 15:22:40.415   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-15 15:22:40.417   874  1316 D ConnectivityService: Adding iface wlan0 to network 102
,07-15 15:22:40.425   874  1314 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-15 15:22:40.471   874  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-15 15:22:40.471   874  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,07-15 15:22:40.473   874  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,07-15 15:22:40.476   874  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,07-15 15:22:40.478   874  1316 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,07-15 15:22:40.494   874  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,07-15 15:22:40.499   874  1316 D ConnectivityService: scheduleUnvalidatedPrompt 102
,07-15 15:22:40.499   874  1316 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102],
07-15 15:22:40.500   874  1316 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,07-15 15:22:40.500   874  1316 D ConnectivityService:    accepting network in place of null
,07-15 15:22:40.500   874  1314 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,07-15 15:22:40.501   874  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-15 15:22:40.501   874  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-15 15:22:40.545   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-15 15:22:40.574   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-15 15:22:40.578   874  1316 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,07-15 15:22:40.578   874  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-15 15:22:40.582   874  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
07-15 15:22:40.584   874   891 D Tethering: MasterInitialState.processMessage what=3
,07-15 15:22:40.600  3840  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:40.600  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:40.600  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:22:40.600  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:40.600  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:40.600  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-15 15:22:40.600  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-15 15:22:40.600  3840  3840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-15 15:22:40.603  3840  3840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-15 15:22:40.610  1973  1973 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,07-15 15:22:40.614  1973  1973 D SystemUpdateService: onCreate
,07-15 15:22:40.624  1973  1973 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,07-15 15:22:40.647  1973  4269 I SystemUpdateService: active receiver: enabled
,07-15 15:22:40.649   874  4259 D NetlinkSocketObserver: NeighborEvent{elapsedMs=203639, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-15 15:22:40.654  1973  1973 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-15 15:22:40.656  1973  2348 I iu.UploadsManager: num queued entries: 0
,07-15 15:22:40.656  1973  2348 I iu.UploadsManager: num updated entries: 0
,07-15 15:22:40.664  1973  4269 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,07-15 15:22:40.666  1973  1973 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-15 15:22:40.667  1973  1973 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-15 15:22:40.671  1973  4269 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,07-15 15:22:40.673  3946  3946 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-15 15:22:40.678  1973  4272 I MDM     : [227] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,07-15 15:22:40.678  1973  4272 W BaseAppContext: Using Auth Proxy for data requests.
,07-15 15:22:40.682  3946  3946 D SprintDMHelper: simOperator: 
,07-15 15:22:40.682  3946  3946 D SprintDMReceiver: Not Sprint UICC, don't do anything.
07-15 15:22:40.688  1973  4272 V GoogleAuthProtoRequest: [227] a.<init>: mAccountName set to: thalitester@gmail.com
,07-15 15:22:40.692  1973  4269 I SystemUpdateService: now status is 0 (complete)
,07-15 15:22:40.692  1973  4269 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
07-15 15:22:40.692  1973  4269 I SystemUpdateService: file has been verified
07-15 15:22:40.692  1973  4269 I SystemUpdateService: OTA package size = 12249756
,07-15 15:22:40.701  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:22:40.712  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:22:40.731  1973  2348 I iu.SyncManager: NEXT; no task
,07-15 15:22:40.749  1973  4269 I SystemUpdateService: showing system update notification
,07-15 15:22:40.776  1973  1973 D SystemUpdateService: onDestroy
,07-15 15:22:40.799  1523  1896 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,07-15 15:22:40.799  1523  1896 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
07-15 15:22:40.799  1523  1896 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:22:40.799  1523  1896 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:22:40.815  1973  4272 E MDM     : [227] SitrepService.a: Error sending sitrep.
,07-15 15:22:40.836   874  4258 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.142,2a00:1450:4001:816::200e
,07-15 15:22:40.862  3489  4274 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,07-15 15:22:40.877  3840  3888 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-15 15:22:40.877  3840  3888 I jxcore-log: 
,07-15 15:22:40.907   874  4258 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 15 Jul 2016 13:22:40 GMT], X-Android-Received-Millis=[1468588960905], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1468588960876]}
,07-15 15:22:40.910   874  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-15 15:22:40.910   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,07-15 15:22:40.911   874  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,07-15 15:22:40.912   874  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-15 15:22:40.941  3840  3888 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-15 15:22:40.941  3840  3888 I jxcore-log: 
,07-15 15:22:40.947  3840  3888 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-15 15:22:40.947  3840  3888 I jxcore-log: 
,07-15 15:22:41.161  3840  3888 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-15 15:22:41.161  3840  3888 I jxcore-log: 
,07-15 15:22:41.184  3840  3888 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-15 15:22:41.184  3840  3888 I jxcore-log: 
,07-15 15:22:41.189  3840  3888 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-15 15:22:41.189  3840  3888 I jxcore-log: 
,07-15 15:22:41.195  3840  3888 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-15 15:22:41.195  3840  3888 I jxcore-log: 
,07-15 15:22:41.213  3840  3888 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-15 15:22:41.213  3840  3888 I jxcore-log: 
,07-15 15:22:41.235  3840  3888 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-15 15:22:41.235  3840  3888 I jxcore-log: 
,07-15 15:22:41.323  3840  3888 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-15 15:22:41.323  3840  3888 I jxcore-log: 
,07-15 15:22:41.329  3840  3888 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-15 15:22:41.329  3840  3888 I jxcore-log: 
,07-15 15:22:41.358  3840  3888 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-15 15:22:41.358  3840  3888 I jxcore-log: 
,07-15 15:22:41.370  3840  3888 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-15 15:22:41.371  3840  3888 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
07-15 15:22:41.371  3840  3888 I jxcore-log: 
,07-15 15:22:41.422  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-15 15:22:41.422  3840  3888 I jxcore-log: 
,07-15 15:22:41.424  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-15 15:22:41.424  3840  3888 I jxcore-log: 
,07-15 15:22:41.425  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-15 15:22:41.425  3840  3888 I jxcore-log: 
,07-15 15:22:41.426  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-15 15:22:41.426  3840  3888 I jxcore-log: 
,07-15 15:22:41.428  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-15 15:22:41.428  3840  3888 I jxcore-log: 
,07-15 15:22:41.429  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-15 15:22:41.429  3840  3888 I jxcore-log: 
,07-15 15:22:41.430  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-15 15:22:41.430  3840  3888 I jxcore-log: 
,07-15 15:22:41.431  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-15 15:22:41.431  3840  3888 I jxcore-log: 
,07-15 15:22:41.431  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-15 15:22:41.431  3840  3888 I jxcore-log: 
07-15 15:22:41.432  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-15 15:22:41.432  3840  3888 I jxcore-log: 
07-15 15:22:41.433  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-15 15:22:41.433  3840  3888 I jxcore-log: 
,07-15 15:22:41.433  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-15 15:22:41.433  3840  3888 I jxcore-log: 
07-15 15:22:41.434  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-15 15:22:41.434  3840  3888 I jxcore-log: 
07-15 15:22:41.434  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-15 15:22:41.434  3840  3888 I jxcore-log: 
07-15 15:22:41.435  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-15 15:22:41.435  3840  3888 I jxcore-log: 
07-15 15:22:41.435  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-15 15:22:41.435  3840  3888 I jxcore-log: 
07-15 15:22:41.436  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-15 15:22:41.436  3840  3888 I jxcore-log: 
,07-15 15:22:41.436  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-15 15:22:41.436  3840  3888 I jxcore-log: 
07-15 15:22:41.437  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-15 15:22:41.437  3840  3888 I jxcore-log: 
07-15 15:22:41.437  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-15 15:22:41.437  3840  3888 I jxcore-log: 
07-15 15:22:41.438  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:22:41.438  3840  3888 I jxcore-log: 
07-15 15:22:41.438  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:22:41.438  3840  3888 I jxcore-log: 
07-15 15:22:41.439  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:22:41.439  3840  3888 I jxcore-log: 
07-15 15:22:41.439  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:22:41.439  3840  3888 I jxcore-log: 
,07-15 15:22:41.440  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-15 15:22:41.440  3840  3888 I jxcore-log: 
,07-15 15:22:41.441  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-15 15:22:41.441  3840  3888 I jxcore-log: 
,07-15 15:22:41.441  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-15 15:22:41.441  3840  3888 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,07-15 15:22:41.442  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-15 15:22:41.442  3840  3888 I jxcore-log: 
,07-15 15:22:41.442  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-15 15:22:41.442  3840  3888 I jxcore-log: 
07-15 15:22:41.443  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:22:41.443  3840  3888 I jxcore-log: 
07-15 15:22:41.443  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-15 15:22:41.443  3840  3888 I jxcore-log: 
,07-15 15:22:41.444  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-15 15:22:41.444  3840  3888 I jxcore-log: 
07-15 15:22:41.445  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-15 15:22:41.445  3840  3888 I jxcore-log: 
07-15 15:22:41.445  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-15 15:22:41.445  3840  3888 I jxcore-log: 
,07-15 15:22:41.446  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:22:41.446  3840  3888 I jxcore-log: 
07-15 15:22:41.448  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-15 15:22:41.448  3840  3888 I jxcore-log: 
07-15 15:22:41.448  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-15 15:22:41.448  3840  3888 I jxcore-log: 
07-15 15:22:41.448  3840  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-15 15:22:41.449  3840  3888 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
07-15 15:22:41.449  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-15 15:22:41.449  3840  3888 I jxcore-log: 
07-15 15:22:41.450  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-15 15:22:41.450  3840  3888 I jxcore-log: 
,07-15 15:22:41.450  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:22:41.450  3840  3888 I jxcore-log: 
,07-15 15:22:41.451  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:22:41.451  3840  3888 I jxcore-log: 
07-15 15:22:41.451  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:22:41.451  3840  3888 I jxcore-log: 
07-15 15:22:41.452  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-15 15:22:41.452  3840  3888 I jxcore-log: 
,07-15 15:22:41.452  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-15 15:22:41.452  3840  3888 I jxcore-log: 
07-15 15:22:41.453  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-15 15:22:41.453  3840  3888 I jxcore-log: 
07-15 15:22:41.453  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-15 15:22:41.453  3840  3888 I jxcore-log: 
,07-15 15:22:41.454  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:22:41.454  3840  3888 I jxcore-log: 
,07-15 15:22:41.454  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-15 15:22:41.454  3840  3888 I jxcore-log: 
07-15 15:22:41.455  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-15 15:22:41.455  3840  3888 I jxcore-log: 
07-15 15:22:41.455  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-15 15:22:41.455  3840  3888 I jxcore-log: 
,07-15 15:22:41.456  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-15 15:22:41.456  3840  3888 I jxcore-log: 
07-15 15:22:41.456  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:22:41.456  3840  3888 I jxcore-log: 
,07-15 15:22:41.457  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-15 15:22:41.457  3840  3888 I jxcore-log: 
07-15 15:22:41.457  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-15 15:22:41.457  3840  3888 I jxcore-log: 
07-15 15:22:41.458  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-15 15:22:41.458  3840  3888 I jxcore-log: 
,07-15 15:22:41.458  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-15 15:22:41.458  3840  3888 I jxcore-log: 
07-15 15:22:41.459  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-15 15:22:41.459  3840  3888 I jxcore-log: 
07-15 15:22:41.459  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-15 15:22:41.459  3840  3888 I jxcore-log: 
07-15 15:22:41.460  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state,
07-15 15:22:41.460  3840  3888 I jxcore-log: 
07-15 15:22:41.461  3840  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-15 15:22:41.461  3840  3888 I jxcore-log: 
,07-15 15:22:48.508   874  1316 D ConnectivityService: handlePromptUnvalidated 102
,07-15 15:22:59.205  1662  1780 I Keyboard.Facilitator.LanguageModelFlusher: run()
07-15 15:22:59.205  1662  1780 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-15 15:22:59.241  1523  1523 I ConfigService: onCreate
,07-15 15:23:04.313  1523  1523 I ConfigService: onDestroy
,07-15 15:23:04.601   874  4259 D NetlinkSocketObserver: NeighborEvent{elapsedMs=227590, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-15 15:23:10.737  4089  4283 I BooksSync: Starting books sync for 61035162, extras: ade
,07-15 15:23:10.765  4089  4284 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-15 15:23:10.780  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:23:10.782  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:23:10.819  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-15 15:23:10.819  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-15 15:23:10.819  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:23:10.820  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:23:10.852  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:23:10.856  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:23:10.895  1523  2101 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-15 15:23:10.895  1523  2101 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-15 15:23:10.896  1523  2101 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:23:10.896  1523  2101 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:23:10.923  4089  4284 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-15 15:23:10.924  4089  4283 E BooksSync: Soft error
07-15 15:23:10.924  4089  4283 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-15 15:23:10.924  4089  4283 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-15 15:23:10.925  4089  4283 E BooksSync: Sync error
07-15 15:23:10.925  4089  4283 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-15 15:23:10.925  4089  4283 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-15 15:23:10.925  4089  4283 I BooksSync: Finished books sync
,07-15 15:23:10.929   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 210947, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-15 15:23:41.163  3050  4287 V KeepSync: Connecting to GoogleApiClient
,07-15 15:23:41.164   874  2032 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-15 15:23:41.221  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:23:41.222  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:23:41.264  1523  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-15 15:23:41.264  1523  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-15 15:23:41.264  1523  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:23:41.264  1523  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:23:41.282  1973  4288 V BaseAuthAsyncOperation: access token request failed
,07-15 15:23:41.283  3050  4287 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-15 15:23:41.341  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-15 15:23:41.341  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-15 15:23:41.341  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:23:41.341  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:23:41.344   874   883 I art     : Background partial concurrent mark sweep GC freed 57100(3MB) AllocSpace objects, 6(116KB) LOS objects, 33% free, 29MB/43MB, paused 1.486ms total 107.007ms
,07-15 15:23:41.386  3050  4287 E KeepSync: IOException
07-15 15:23:41.386  3050  4287 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-15 15:23:41.386  3050  4287 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-15 15:23:41.386  3050  4287 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-15 15:23:41.386  3050  4287 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-15 15:23:41.386  3050  4287 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-15 15:23:41.386  3050  4287 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-15 15:23:41.386  3050  4287 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-15 15:23:41.386  3050  4287 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-15 15:23:41.386  3050  4287 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-15 15:23:41.386  3050  4287 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-15 15:23:41.386  3050  4287 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-15 15:23:41.386  3050  4287 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-15 15:23:41.386  3050  4287 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-15 15:23:41.386  3050  4287 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-15 15:23:41.386  3050  4287 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-15 15:23:41.386  3050  4287 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-15 15:23:41.386  3050  4287 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-15 15:23:41.386  3050  4287 E KeepSync: 	... 10 more
07-15 15:23:41.386  3050  4287 W KeepSync: Sync result 2
,07-15 15:23:41.397   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 256512, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-15 15:23:45.155   874  4259 D NetlinkSocketObserver: NeighborEvent{elapsedMs=268144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-15 15:24:08.581   874  4259 D NetlinkSocketObserver: NeighborEvent{elapsedMs=291570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-15 15:24:11.524  4089  4294 I BooksSync: Starting books sync for 61035162, extras: ade
,07-15 15:24:11.628  4089  4297 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-15 15:24:11.640  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:24:11.645  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:24:11.690  1523  2098 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-15 15:24:11.690  1523  2098 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-15 15:24:11.690  1523  2098 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:24:11.691  1523  2098 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:24:11.720  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:24:11.722  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:24:11.765  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-15 15:24:11.765  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-15 15:24:11.765  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:24:11.765  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:24:11.766  1523  2101 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-15 15:24:11.766  1523  2101 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-15 15:24:11.766  1523  2101 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:24:11.766  1523  2101 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:24:11.823  3567  4296 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-15 15:24:11.823  3567  4296 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-15 15:24:11.823  3567  4296 E HttpOperation: 	at jdm.a(PG:82)
07-15 15:24:11.823  3567  4296 E HttpOperation: 	at jcs.o(PG:406)
07-15 15:24:11.823  3567  4296 E HttpOperation: 	at jcn.a(PG:1379)
07-15 15:24:11.823  3567  4296 E HttpOperation: 	at jcs.i(PG:143)
07-15 15:24:11.823  3567  4296 E HttpOperation: 	at blb.a(PG:3937)
07-15 15:24:11.823  3567  4296 E HttpOperation: 	at czp.a(PG:18188)
07-15 15:24:11.823  3567  4296 E HttpOperation: 	at czp.a(PG:9081)
07-15 15:24:11.823  3567  4296 E HttpOperation: 	at czq.run(PG:1686)
07-15 15:24:11.823  3567  4296 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-15 15:24:11.823  3567  4296 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-15 15:24:11.823  3567  4296 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-15 15:24:11.823  3567  4296 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-15 15:24:11.823  3567  4296 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-15 15:24:11.823  3567  4296 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-15 15:24:11.823  3567  4296 E HttpOperation: 	at jdj.a(PG:4091)
07-15 15:24:11.823  3567  4296 E HttpOperation: 	at jdj.a(PG:1125)
07-15 15:24:11.823  3567  4296 E HttpOperation: 	at jdm.a(PG:77)
07-15 15:24:11.823  3567  4296 E HttpOperation: 	... 12 more
07-15 15:24:11.823  3567  4296 E HttpOperation: Caused by: faj: BadAuthentication
07-15 15:24:11.823  3567  4296 E HttpOperation: 	at fal.a(PG:38)
07-15 15:24:11.823  3567  4296 E HttpOperation: 	at jdj.a(PG:4089)
07-15 15:24:11.823  3567  4296 E HttpOperation: 	... 14 more
,07-15 15:24:11.830  4089  4297 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-15 15:24:11.831  4089  4294 E BooksSync: Soft error
07-15 15:24:11.831  4089  4294 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-15 15:24:11.831  4089  4294 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-15 15:24:11.832  4089  4294 E BooksSync: Sync error
07-15 15:24:11.832  4089  4294 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-15 15:24:11.832  4089  4294 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-15 15:24:11.832  4089  4294 I BooksSync: Finished books sync
,07-15 15:24:11.847   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 266254, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-15 15:24:11.879  1523  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-15 15:24:11.879  1523  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-15 15:24:11.879  1523  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-15 15:24:11.880  1523  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:24:11.893  3567  4296 E HttpOperation: [getmobileexperiments] Unexpected exception
07-15 15:24:11.893  3567  4296 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-15 15:24:11.893  3567  4296 E HttpOperation: 	at jdm.a(PG:82)
07-15 15:24:11.893  3567  4296 E HttpOperation: 	at jcs.o(PG:406)
07-15 15:24:11.893  3567  4296 E HttpOperation: 	at jcn.a(PG:1379)
07-15 15:24:11.893  3567  4296 E HttpOperation: 	at jcs.i(PG:143)
07-15 15:24:11.893  3567  4296 E HttpOperation: 	at hec.a(PG:42)
07-15 15:24:11.893  3567  4296 E HttpOperation: 	at hee.a(PG:102)
07-15 15:24:11.893  3567  4296 E HttpOperation: 	at czr.a(PG:65)
07-15 15:24:11.893  3567  4296 E HttpOperation: 	at kka.a(PG:108)
07-15 15:24:11.893  3567  4296 E HttpOperation: 	at czp.a(PG:19176)
07-15 15:24:11.893  3567  4296 E HttpOperation: 	at czp.a(PG:9081)
07-15 15:24:11.893  3567  4296 E HttpOperation: 	at czq.run(PG:1686)
07-15 15:24:11.893  3567  4296 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-15 15:24:11.893  3567  4296 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-15 15:24:11.893  3567  4296 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-15 15:24:11.893  3567  4296 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-15 15:24:11.893  3567  4296 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-15 15:24:11.893  3567  4296 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-15 15:24:11.893  3567  4296 E HttpOperation: 	at jdj.a(PG:4091)
07-15 15:24:11.893  3567  4296 E HttpOperation: 	at jdj.a(PG:1125)
07-15 15:24:11.893  3567  4296 E HttpOperation: 	at jdm.a(PG:77)
07-15 15:24:11.893  3567  4296 E HttpOperation: 	... 15 more
07-15 15:24:11.893  3567  4296 E HttpOperation: Caused by: faj: BadAuthentication
07-15 15:24:11.893  3567  4296 E HttpOperation: 	at fal.a(PG:38)
07-15 15:24:11.893  3567  4296 E HttpOperation: 	at jdj.a(PG:4089)
07-15 15:24:11.893  3567  4296 E HttpOperation: 	... 17 more
07-15 15:24:11.893  3567  4296 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-15 15:24:11.893  3567  4296 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-15 15:24:11.893  3567  4296 E ExperimentLoader: 	at jdm.a(PG:82)
07-15 15:24:11.893  3567  4296 E ExperimentLoader: 	at jcs.o(PG:406)
07-15 15:24:11.893  3567  4296 E ExperimentLoader: 	at jcn.a(PG:1379)
07-15 15:24:11.893  3567  4296 E ExperimentLoader: 	at jcs.i(PG:143)
07-15 15:24:11.893  3567  4296 E ExperimentLoader: 	at hec.a(PG:42)
07-15 15:24:11.893  3567  4296 E ExperimentLoader: 	at hee.a(PG:102)
07-15 15:24:11.893  3567  4296 E ExperimentLoader: 	at czr.a(PG:65)
07-15 15:24:11.893  3567  4296 E ExperimentLoader: 	at kka.a(PG:108)
07-15 15:24:11.893  3567  4296 E ExperimentLoader: 	at czp.a(PG:19176)
07-15 15:24:11.893  3567  4296 E ExperimentLoader: 	at czp.a(PG:9081)
07-15 15:24:11.893  3567  4296 E ExperimentLoader: 	at czq.run(PG:1686)
07-15 15:24:11.893  3567  4296 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-15 15:24:11.893  3567  4296 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-15 15:24:11.893  3567  4296 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-15 15:24:11.893  3567  4296 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-15 15:24:11.893  3567  4296 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-15 15:24:11.893  3567  4296 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-15 15:24:11.893  3567  4296 E ExperimentLoader: 	at jdj.a(PG:4091)
07-15 15:24:11.893  3567  4296 E ExperimentLoader: 	at jdj.a(PG:1,125)
07-15 15:24:11.893  3567  4296 E ExperimentLoader: 	at jdm.a(PG:77)
07-15 15:24:11.893  3567  4296 E ExperimentLoader: 	... 15 more
07-15 15:24:11.893  3567  4296 E ExperimentLoader: Caused by: faj: BadAuthentication
07-15 15:24:11.893  3567  4296 E ExperimentLoader: 	at fal.a(PG:38)
07-15 15:24:11.893  3567  4296 E ExperimentLoader: 	at jdj.a(PG:4089)
07-15 15:24:11.893  3567  4296 E ExperimentLoader: 	... 17 more
,07-15 15:24:12.045   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 289520, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-15 15:24:12.095  3050  4299 V KeepSync: Connecting to GoogleApiClient
,07-15 15:24:12.096   874  2033 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-15 15:24:12.163  1523  2101 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
07-15 15:24:12.163  1523  2101 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-15 15:24:12.163  1523  2101 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:24:12.163  1523  2101 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:24:12.181  1973  4300 V BaseAuthAsyncOperation: access token request failed
,07-15 15:24:12.182  3050  4299 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-15 15:24:12.232  1523  1896 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-15 15:24:12.232  1523  1896 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-15 15:24:12.232  1523  1896 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:24:12.233  1523  1896 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:24:12.251  3050  4299 E KeepSync: IOException
07-15 15:24:12.251  3050  4299 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-15 15:24:12.251  3050  4299 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-15 15:24:12.251  3050  4299 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-15 15:24:12.251  3050  4299 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-15 15:24:12.251  3050  4299 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-15 15:24:12.251  3050  4299 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-15 15:24:12.251  3050  4299 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-15 15:24:12.251  3050  4299 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-15 15:24:12.251  3050  4299 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-15 15:24:12.251  3050  4299 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-15 15:24:12.251  3050  4299 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-15 15:24:12.251  3050  4299 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-15 15:24:12.251  3050  4299 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-15 15:24:12.251  3050  4299 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-15 15:24:12.251  3050  4299 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-15 15:24:12.251  3050  4299 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-15 15:24:12.251  3050  4299 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-15 15:24:12.251  3050  4299 E KeepSync: 	... 10 more
07-15 15:24:12.251  3050  4299 W KeepSync: Sync result 2
,07-15 15:24:12.264   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 295029, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-15 15:24:43.166  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:24:43.168  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:24:43.200  1523  2101 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-15 15:24:43.200  1523  2101 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-15 15:24:43.200  1523  2101 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:24:43.200  1523  2101 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:24:43.224  3567  4303 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-15 15:24:43.224  3567  4303 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-15 15:24:43.224  3567  4303 E HttpOperation: 	at jdm.a(PG:82)
07-15 15:24:43.224  3567  4303 E HttpOperation: 	at jcs.o(PG:406)
07-15 15:24:43.224  3567  4303 E HttpOperation: 	at jcn.a(PG:1379)
07-15 15:24:43.224  3567  4303 E HttpOperation: 	at jcs.i(PG:143)
07-15 15:24:43.224  3567  4303 E HttpOperation: 	at blb.a(PG:3937)
07-15 15:24:43.224  3567  4303 E HttpOperation: 	at czp.a(PG:18188)
07-15 15:24:43.224  3567  4303 E HttpOperation: 	at czp.a(PG:9081)
07-15 15:24:43.224  3567  4303 E HttpOperation: 	at czq.run(PG:1686)
07-15 15:24:43.224  3567  4303 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-15 15:24:43.224  3567  4303 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-15 15:24:43.224  3567  4303 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-15 15:24:43.224  3567  4303 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-15 15:24:43.224  3567  4303 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-15 15:24:43.224  3567  4303 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-15 15:24:43.224  3567  4303 E HttpOperation: 	at jdj.a(PG:4091)
07-15 15:24:43.224  3567  4303 E HttpOperation: 	at jdj.a(PG:1125)
07-15 15:24:43.224  3567  4303 E HttpOperation: 	at jdm.a(PG:77)
07-15 15:24:43.224  3567  4303 E HttpOperation: 	... 12 more
07-15 15:24:43.224  3567  4303 E HttpOperation: Caused by: faj: BadAuthentication
07-15 15:24:43.224  3567  4303 E HttpOperation: 	at fal.a(PG:38)
07-15 15:24:43.224  3567  4303 E HttpOperation: 	at jdj.a(PG:4089)
07-15 15:24:43.224  3567  4303 E HttpOperation: 	... 14 more
,07-15 15:24:43.305  1523  2098 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-15 15:24:43.305  1523  2098 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-15 15:24:43.305  1523  2098 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:24:43.306  1523  2098 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:24:43.326  3567  4303 E HttpOperation: [getmobileexperiments] Unexpected exception
07-15 15:24:43.326  3567  4303 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-15 15:24:43.326  3567  4303 E HttpOperation: 	at jdm.a(PG:82)
07-15 15:24:43.326  3567  4303 E HttpOperation: 	at jcs.o(PG:406)
07-15 15:24:43.326  3567  4303 E HttpOperation: 	at jcn.a(PG:1379)
07-15 15:24:43.326  3567  4303 E HttpOperation: 	at jcs.i(PG:143)
07-15 15:24:43.326  3567  4303 E HttpOperation: 	at hec.a(PG:42)
07-15 15:24:43.326  3567  4303 E HttpOperation: 	at hee.a(PG:102)
07-15 15:24:43.326  3567  4303 E HttpOperation: 	at czr.a(PG:65)
07-15 15:24:43.326  3567  4303 E HttpOperation: 	at kka.a(PG:108)
07-15 15:24:43.326  3567  4303 E HttpOperation: 	at czp.a(PG:19176)
07-15 15:24:43.326  3567  4303 E HttpOperation: 	at czp.a(PG:9081)
07-15 15:24:43.326  3567  4303 E HttpOperation: 	at czq.run(PG:1686)
07-15 15:24:43.326  3567  4303 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-15 15:24:43.326  3567  4303 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-15 15:24:43.326  3567  4303 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-15 15:24:43.326  3567  4303 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-15 15:24:43.326  3567  4303 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-15 15:24:43.326  3567  4303 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-15 15:24:43.326  3567  4303 E HttpOperation: 	at jdj.a(PG:4091)
07-15 15:24:43.326  3567  4303 E HttpOperation: 	at jdj.a(PG:1125)
07-15 15:24:43.326  3567  4303 E HttpOperation: 	at jdm.a(PG:77)
07-15 15:24:43.326  3567  4303 E HttpOperation: 	... 15 more
07-15 15:24:43.326  3567  4303 E HttpOperation: Caused by: faj: BadAuthentication
07-15 15:24:43.326  3567  4303 E HttpOperation: 	at fal.a(PG:38)
07-15 15:24:43.326  3567  4303 E HttpOperation: 	at jdj.a(PG:4089)
07-15 15:24:43.326  3567  4303 E HttpOperation: 	... 17 more
,07-15 15:24:43.327  3567  4303 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-15 15:24:43.327  3567  4303 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-15 15:24:43.327  3567  4303 E ExperimentLoader: 	at jdm.a(PG:82)
07-15 15:24:43.327  3567  4303 E ExperimentLoader: 	at jcs.o(PG:406)
07-15 15:24:43.327  3567  4303 E ExperimentLoader: 	at jcn.a(PG:1379)
07-15 15:24:43.327  3567  4303 E ExperimentLoader: 	at jcs.i(PG:143)
07-15 15:24:43.327  3567  4303 E ExperimentLoader: 	at hec.a(PG:42)
07-15 15:24:43.327  3567  4303 E ExperimentLoader: 	at hee.a(PG:102)
07-15 15:24:43.327  3567  4303 E ExperimentLoader: 	at czr.a(PG:65)
07-15 15:24:43.327  3567  4303 E ExperimentLoader: 	at kka.a(PG:108)
07-15 15:24:43.327  3567  4303 E ExperimentLoader: 	at czp.a(PG:19176)
07-15 15:24:43.327  3567  4303 E ExperimentLoader: 	at czp.a(PG:9081)
07-15 15:24:43.327  3567  4303 E ExperimentLoader: 	at czq.run(PG:1686)
07-15 15:24:43.327  3567  4303 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-15 15:24:43.327  3567  4303 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-15 15:24:43.327  3567  4303 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-15 15:24:43.327  3567  4303 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-15 15:24:43.327  3567  4303 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-15 15:24:43.327  3567  4303 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-15 15:24:43.327  3567  4303 E ExperimentLoader: 	at jdj.a(PG:4091)
07-15 15:24:43.327  3567  4303 E ExperimentLoader: 	at jdj.a(PG:1125)
07-15 15:24:43.327  3567  4303 E ExperimentLoader: 	at jdm.a(PG:77)
07-15 15:24:43.327  3567  4303 E ExperimentLoader: 	... 15 more
07-15 15:24:43.327  3567  4303 E ExperimentLoader: Caused by: faj: BadAuthentication
07-15 15:24:43.327  3567  4303 E ExperimentLoader: 	at fal.a(PG:38)
07-15 15:24:43.327  3567  4303 E ExperimentLoader: 	at jdj.a(PG:4089)
07-15 15:24:43.327  3567  4303 E ExperimentLoader: 	... 17 more
,07-15 15:24:43.448   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 325852, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-15 15:25:00.330  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:25:00.340  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:25:00.345  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:25:00.384  1523  2101 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-15 15:25:00.384  1523  2101 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-15 15:25:00.384  1523  2101 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:25:00.384  1523  2101 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:25:00.412  1523  2101 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-15 15:25:00.412  1523  2101 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-15 15:25:00.412  1523  2101 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-15 15:25:00.412  1523  2101 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-15 15:25:00.412  1523  2101 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-15 15:25:00.412  1523  2101 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-15 15:25:00.412  1523  2101 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-15 15:25:00.417  3526  3557 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-15 15:25:00.417  3526  3557 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-15 15:25:00.417  3526  3557 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-15 15:25:00.417  3526  3557 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-15 15:25:00.417  3526  3557 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-15 15:25:00.417  3526  3557 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-15 15:25:00.417  3526  3557 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-15 15:25:05.461   874  4259 D NetlinkSocketObserver: NeighborEvent{elapsedMs=348450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-15 15:25:13.735  3050  4310 V KeepSync: Connecting to GoogleApiClient
,07-15 15:25:13.736   874  2033 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-15 15:25:13.802  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:25:13.806  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:25:13.865  1523  2101 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-15 15:25:13.865  1523  2101 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-15 15:25:13.866  1523  2101 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-15 15:25:13.866  1523  2101 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:25:13.904  1973  4311 V BaseAuthAsyncOperation: access token request failed
,07-15 15:25:13.905  3050  4310 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-15 15:25:13.992  1523  2098 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-15 15:25:13.992  1523  2098 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-15 15:25:13.992  1523  2098 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:25:13.992  1523  2098 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:25:14.027  3050  4310 E KeepSync: IOException
07-15 15:25:14.027  3050  4310 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-15 15:25:14.027  3050  4310 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-15 15:25:14.027  3050  4310 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-15 15:25:14.027  3050  4310 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-15 15:25:14.027  3050  4310 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-15 15:25:14.027  3050  4310 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-15 15:25:14.027  3050  4310 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-15 15:25:14.027  3050  4310 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-15 15:25:14.027  3050  4310 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-15 15:25:14.027  3050  4310 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-15 15:25:14.027  3050  4310 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-15 15:25:14.027  3050  4310 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-15 15:25:14.027  3050  4310 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-15 15:25:14.027  3050  4310 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-15 15:25:14.027  3050  4310 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-15 15:25:14.027  3050  4310 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-15 15:25:14.027  3050  4310 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-15 15:25:14.027  3050  4310 E KeepSync: 	... 10 more
,07-15 15:25:14.027  3050  4310 W KeepSync: Sync result 2
,07-15 15:25:14.041   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 356537, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-15 15:25:24.208   874  4259 D NetlinkSocketObserver: NeighborEvent{elapsedMs=367197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-15 15:25:44.140  4089  4314 I BooksSync: Starting books sync for 61035162, extras: ade
,07-15 15:25:44.199  4089  4315 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-15 15:25:44.235  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:25:44.239  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:25:44.288  1523  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-15 15:25:44.288  1523  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-15 15:25:44.295  1523  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:25:44.295  1523  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:25:44.329  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:25:44.332  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:25:44.362  1523  2101 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-15 15:25:44.362  1523  2101 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-15 15:25:44.362  1523  2101 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:25:44.363  1523  2101 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:25:44.389  4089  4315 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-15 15:25:44.391  4089  4314 E BooksSync: Soft error
07-15 15:25:44.391  4089  4314 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-15 15:25:44.391  4089  4314 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-15 15:25:44.392  4089  4314 E BooksSync: Sync error
07-15 15:25:44.392  4089  4314 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-15 15:25:44.392  4089  4314 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-15 15:25:44.393  4089  4314 I BooksSync: Finished books sync
,07-15 15:25:44.404   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 359509, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-15 15:26:05.328   874  4259 D NetlinkSocketObserver: NeighborEvent{elapsedMs=408317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-15 15:26:11.707  1523  1986 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-15 15:26:14.843  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:26:14.845  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:26:14.884  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-15 15:26:14.884  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-15 15:26:14.885  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-15 15:26:14.885  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:26:14.908  3567  4318 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-15 15:26:14.908  3567  4318 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-15 15:26:14.908  3567  4318 E HttpOperation: 	at jdm.a(PG:82)
07-15 15:26:14.908  3567  4318 E HttpOperation: 	at jcs.o(PG:406)
07-15 15:26:14.908  3567  4318 E HttpOperation: 	at jcn.a(PG:1379)
07-15 15:26:14.908  3567  4318 E HttpOperation: 	at jcs.i(PG:143)
07-15 15:26:14.908  3567  4318 E HttpOperation: 	at blb.a(PG:3937)
07-15 15:26:14.908  3567  4318 E HttpOperation: 	at czp.a(PG:18188)
07-15 15:26:14.908  3567  4318 E HttpOperation: 	at czp.a(PG:9081)
07-15 15:26:14.908  3567  4318 E HttpOperation: 	at czq.run(PG:1686)
07-15 15:26:14.908  3567  4318 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-15 15:26:14.908  3567  4318 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-15 15:26:14.908  3567  4318 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-15 15:26:14.908  3567  4318 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-15 15:26:14.908  3567  4318 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-15 15:26:14.908  3567  4318 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-15 15:26:14.908  3567  4318 E HttpOperation: 	at jdj.a(PG:4091)
07-15 15:26:14.908  3567  4318 E HttpOperation: 	at jdj.a(PG:1125)
07-15 15:26:14.908  3567  4318 E HttpOperation: 	at jdm.a(PG:77)
07-15 15:26:14.908  3567  4318 E HttpOperation: 	... 12 more
07-15 15:26:14.908  3567  4318 E HttpOperation: Caused by: faj: BadAuthentication
07-15 15:26:14.908  3567  4318 E HttpOperation: 	at fal.a(PG:38)
07-15 15:26:14.908  3567  4318 E HttpOperation: 	at jdj.a(PG:4089)
07-15 15:26:14.908  3567  4318 E HttpOperation: 	... 14 more
,07-15 15:26:14.959  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-15 15:26:14.959  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-15 15:26:14.959  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:26:14.959  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:26:14.974  3567  4318 E HttpOperation: [getmobileexperiments] Unexpected exception
07-15 15:26:14.974  3567  4318 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-15 15:26:14.974  3567  4318 E HttpOperation: 	at jdm.a(PG:82)
07-15 15:26:14.974  3567  4318 E HttpOperation: 	at jcs.o(PG:406)
07-15 15:26:14.974  3567  4318 E HttpOperation: 	at jcn.a(PG:1379)
07-15 15:26:14.974  3567  4318 E HttpOperation: 	at jcs.i(PG:143)
07-15 15:26:14.974  3567  4318 E HttpOperation: 	at hec.a(PG:42)
07-15 15:26:14.974  3567  4318 E HttpOperation: 	at hee.a(PG:102)
07-15 15:26:14.974  3567  4318 E HttpOperation: 	at czr.a(PG:65)
07-15 15:26:14.974  3567  4318 E HttpOperation: 	at kka.a(PG:108)
07-15 15:26:14.974  3567  4318 E HttpOperation: 	at czp.a(PG:19176)
07-15 15:26:14.974  3567  4318 E HttpOperation: 	at czp.a(PG:9081)
07-15 15:26:14.974  3567  4318 E HttpOperation: 	at czq.run(PG:1686)
07-15 15:26:14.974  3567  4318 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-15 15:26:14.974  3567  4318 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-15 15:26:14.974  3567  4318 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-15 15:26:14.974  3567  4318 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-15 15:26:14.974  3567  4318 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-15 15:26:14.974  3567  4318 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-15 15:26:14.974  3567  4318 E HttpOperation: 	at jdj.a(PG:4091)
07-15 15:26:14.974  3567  4318 E HttpOperation: 	at jdj.a(PG:1125)
07-15 15:26:14.974  3567  4318 E HttpOperation: 	at jdm.a(PG:77)
07-15 15:26:14.974  3567  4318 E HttpOperation: 	... 15 more
07-15 15:26:14.974  3567  4318 E HttpOperation: Caused by: faj: BadAuthentication
07-15 15:26:14.974  3567  4318 E HttpOperation: 	at fal.a(PG:38)
07-15 15:26:14.974  3567  4318 E HttpOperation: 	at jdj.a(PG:4089)
07-15 15:26:14.974  3567  4318 E HttpOperation: 	... 17 more
,07-15 15:26:14.975  3567  4318 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-15 15:26:14.975  3567  4318 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-15 15:26:14.975  3567  4318 E ExperimentLoader: 	at jdm.a(PG:82)
07-15 15:26:14.975  3567  4318 E ExperimentLoader: 	at jcs.o(PG:406)
07-15 15:26:14.975  3567  4318 E ExperimentLoader: 	at jcn.a(PG:1379)
07-15 15:26:14.975  3567  4318 E ExperimentLoader: 	at jcs.i(PG:143)
07-15 15:26:14.975  3567  4318 E ExperimentLoader: 	at hec.a(PG:42)
07-15 15:26:14.975  3567  4318 E ExperimentLoader: 	at hee.a(PG:102)
07-15 15:26:14.975  3567  4318 E ExperimentLoader: 	at czr.a(PG:65)
07-15 15:26:14.975  3567  4318 E ExperimentLoader: 	at kka.a(PG:108)
07-15 15:26:14.975  3567  4318 E ExperimentLoader: 	at czp.a(PG:19176)
07-15 15:26:14.975  3567  4318 E ExperimentLoader: 	at czp.a(PG:9081)
07-15 15:26:14.975  3567  4318 E ExperimentLoader: 	at czq.run(PG:1686)
07-15 15:26:14.975  3567  4318 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-15 15:26:14.975  3567  4318 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-15 15:26:14.975  3567  4318 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-15 15:26:14.975  3567  4318 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-15 15:26:14.975  3567  4318 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-15 15:26:14.975  3567  4318 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-15 15:26:14.975  3567  4318 E ExperimentLoader: 	at jdj.a(PG:4091)
07-15 15:26:14.975  3567  4318 E ExperimentLoader: 	at jdj.a(PG:1125)
07-15 15:26:14.975  3567  4318 E ExperimentLoader: 	at jdm.a(PG:77)
07-15 15:26:14.975  3567  4318 E ExperimentLoader: 	... 15 more
07-15 15:26:14.975  3567  4318 E ExperimentLoader: Caused by: faj: BadAuthentication
07-15 15:26:14.975  3567  4318 E ExperimentLoader: 	at fal.a(PG:38)
07-15 15:26:14.975  3567  4318 E ExperimentLoader: 	at jdj.a(PG:4089)
07-15 15:26:14.975  3567  4318 E ExperimentLoader: 	... 17 more
,07-15 15:26:15.093   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 388072, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-15 15:26:28.795   874  4259 D NetlinkSocketObserver: NeighborEvent{elapsedMs=431784, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-15 15:26:46.115   874  4259 D NetlinkSocketObserver: NeighborEvent{elapsedMs=449104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-15 15:27:09.595   874  4259 D NetlinkSocketObserver: NeighborEvent{elapsedMs=472584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-15 15:27:16.709  3050  4323 V KeepSync: Connecting to GoogleApiClient
,07-15 15:27:16.710   874  1702 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-15 15:27:16.751  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:27:16.753  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:27:16.775  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
07-15 15:27:16.775  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-15 15:27:16.775  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:27:16.775  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:27:16.791  1973  4324 V BaseAuthAsyncOperation: access token request failed
,07-15 15:27:16.793  3050  4323 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-15 15:27:16.837  1523  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-15 15:27:16.837  1523  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-15 15:27:16.837  1523  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:27:16.837  1523  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:27:16.857  3050  4323 E KeepSync: IOException
07-15 15:27:16.857  3050  4323 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-15 15:27:16.857  3050  4323 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-15 15:27:16.857  3050  4323 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-15 15:27:16.857  3050  4323 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-15 15:27:16.857  3050  4323 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-15 15:27:16.857  3050  4323 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-15 15:27:16.857  3050  4323 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-15 15:27:16.857  3050  4323 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-15 15:27:16.857  3050  4323 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-15 15:27:16.857  3050  4323 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-15 15:27:16.857  3050  4323 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-15 15:27:16.857  3050  4323 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-15 15:27:16.857  3050  4323 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-15 15:27:16.857  3050  4323 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-15 15:27:16.857  3050  4323 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-15 15:27:16.857  3050  4323 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-15 15:27:16.857  3050  4323 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-15 15:27:16.857  3050  4323 E KeepSync: 	... 10 more
,07-15 15:27:16.857  3050  4323 W KeepSync: Sync result 2
,07-15 15:27:16.869   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 479599, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-15 15:27:45.915   874  4259 D NetlinkSocketObserver: NeighborEvent{elapsedMs=508904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-15 15:27:53.849  4089  4327 I BooksSync: Starting books sync for 61035162, extras: ade
,07-15 15:27:53.878  4089  4328 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-15 15:27:53.890  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:27:53.893  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:27:53.920  1523  2098 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-15 15:27:53.920  1523  2098 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-15 15:27:53.920  1523  2098 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:27:53.920  1523  2098 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:27:53.948  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:27:53.951  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:27:53.975  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-15 15:27:53.975  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-15 15:27:53.975  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-15 15:27:53.976  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:27:53.991  4089  4328 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-15 15:27:53.992  4089  4327 E BooksSync: Soft error
07-15 15:27:53.992  4089  4327 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-15 15:27:53.992  4089  4327 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-15 15:27:53.992  4089  4327 E BooksSync: Sync error
07-15 15:27:53.992  4089  4327 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-15 15:27:53.992  4089  4327 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-15 15:27:53.992  4089  4327 I BooksSync: Finished books sync
,07-15 15:27:54.005   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 516738, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-15 15:28:09.381   874  4259 D NetlinkSocketObserver: NeighborEvent{elapsedMs=532370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-15 15:28:15.461   874  4259 D NetlinkSocketObserver: NeighborEvent{elapsedMs=538450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-15 15:28:24.388  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:28:24.389  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:28:24.420  1523  1896 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-15 15:28:24.420  1523  1896 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-15 15:28:24.420  1523  1896 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-15 15:28:24.420  1523  1896 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:28:24.437  3567  4331 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-15 15:28:24.437  3567  4331 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-15 15:28:24.437  3567  4331 E HttpOperation: 	at jdm.a(PG:82)
07-15 15:28:24.437  3567  4331 E HttpOperation: 	at jcs.o(PG:406)
07-15 15:28:24.437  3567  4331 E HttpOperation: 	at jcn.a(PG:1379)
07-15 15:28:24.437  3567  4331 E HttpOperation: 	at jcs.i(PG:143)
07-15 15:28:24.437  3567  4331 E HttpOperation: 	at blb.a(PG:3937)
07-15 15:28:24.437  3567  4331 E HttpOperation: 	at czp.a(PG:18188)
07-15 15:28:24.437  3567  4331 E HttpOperation: 	at czp.a(PG:9081)
07-15 15:28:24.437  3567  4331 E HttpOperation: 	at czq.run(PG:1686)
07-15 15:28:24.437  3567  4331 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-15 15:28:24.437  3567  4331 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-15 15:28:24.437  3567  4331 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-15 15:28:24.437  3567  4331 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-15 15:28:24.437  3567  4331 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-15 15:28:24.437  3567  4331 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-15 15:28:24.437  3567  4331 E HttpOperation: 	at jdj.a(PG:4091)
07-15 15:28:24.437  3567  4331 E HttpOperation: 	at jdj.a(PG:1125)
07-15 15:28:24.437  3567  4331 E HttpOperation: 	at jdm.a(PG:77)
07-15 15:28:24.437  3567  4331 E HttpOperation: 	... 12 more
07-15 15:28:24.437  3567  4331 E HttpOperation: Caused by: faj: BadAuthentication
07-15 15:28:24.437  3567  4331 E HttpOperation: 	at fal.a(PG:38)
07-15 15:28:24.437  3567  4331 E HttpOperation: 	at jdj.a(PG:4089)
07-15 15:28:24.437  3567  4331 E HttpOperation: 	... 14 more
,07-15 15:28:24.480  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-15 15:28:24.481  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-15 15:28:24.481  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:28:24.481  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:28:24.508  3567  4331 E HttpOperation: [getmobileexperiments] Unexpected exception
07-15 15:28:24.508  3567  4331 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-15 15:28:24.508  3567  4331 E HttpOperation: 	at jdm.a(PG:82)
07-15 15:28:24.508  3567  4331 E HttpOperation: 	at jcs.o(PG:406)
07-15 15:28:24.508  3567  4331 E HttpOperation: 	at jcn.a(PG:1379)
07-15 15:28:24.508  3567  4331 E HttpOperation: 	at jcs.i(PG:143)
07-15 15:28:24.508  3567  4331 E HttpOperation: 	at hec.a(PG:42)
07-15 15:28:24.508  3567  4331 E HttpOperation: 	at hee.a(PG:102)
07-15 15:28:24.508  3567  4331 E HttpOperation: 	at czr.a(PG:65)
07-15 15:28:24.508  3567  4331 E HttpOperation: 	at kka.a(PG:108)
07-15 15:28:24.508  3567  4331 E HttpOperation: 	at czp.a(PG:19176)
07-15 15:28:24.508  3567  4331 E HttpOperation: 	at czp.a(PG:9081)
07-15 15:28:24.508  3567  4331 E HttpOperation: 	at czq.run(PG:1686)
07-15 15:28:24.508  3567  4331 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-15 15:28:24.508  3567  4331 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-15 15:28:24.508  3567  4331 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-15 15:28:24.508  3567  4331 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-15 15:28:24.508  3567  4331 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-15 15:28:24.508  3567  4331 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-15 15:28:24.508  3567  4331 E HttpOperation: 	at jdj.a(PG:4091)
07-15 15:28:24.508  3567  4331 E HttpOperation: 	at jdj.a(PG:1125)
07-15 15:28:24.508  3567  4331 E HttpOperation: 	at jdm.a(PG:77)
07-15 15:28:24.508  3567  4331 E HttpOperation: 	... 15 more
07-15 15:28:24.508  3567  4331 E HttpOperation: Caused by: faj: BadAuthentication
07-15 15:28:24.508  3567  4331 E HttpOperation: 	at fal.a(PG:38)
07-15 15:28:24.508  3567  4331 E HttpOperation: 	at jdj.a(PG:4089)
07-15 15:28:24.508  3567  4331 E HttpOperation: 	... 17 more
07-15 15:28:24.508  3567  4331 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-15 15:28:24.508  3567  4331 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-15 15:28:24.508  3567  4331 E ExperimentLoader: 	at jdm.a(PG:82)
07-15 15:28:24.508  3567  4331 E ExperimentLoader: 	at jcs.o(PG:406)
07-15 15:28:24.508  3567  4331 E ExperimentLoader: 	at jcn.a(PG:1379)
07-15 15:28:24.508  3567  4331 E ExperimentLoader: 	at jcs.i(PG:143)
07-15 15:28:24.508  3567  4331 E ExperimentLoader: 	at hec.a(PG:42)
07-15 15:28:24.508  3567  4331 E ExperimentLoader: 	at hee.a(PG:102)
07-15 15:28:24.508  3567  4331 E ExperimentLoader: 	at czr.a(PG:65)
07-15 15:28:24.508  3567  4331 E ExperimentLoader: 	at kka.a(PG:108)
07-15 15:28:24.508  3567  4331 E ExperimentLoader: 	at czp.a(PG:19176)
07-15 15:28:24.508  3567  4331 E ExperimentLoader: 	at czp.a(PG:9081)
07-15 15:28:24.508  3567  4331 E ExperimentLoader: 	at czq.run(PG:1686)
07-15 15:28:24.508  3567  4331 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-15 15:28:24.508  3567  4331 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-15 15:28:24.508  3567  4331 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-15 15:28:24.508  3567  4331 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-15 15:28:24.508  3567  4331 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-15 15:28:24.508  3567  4331 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-15 15:28:24.508  3567  4331 E ExperimentLoader: 	at jdj.a(PG:4091)
07-15 15:28:24.508  3567  4331 E ExperimentLoader: 	at jdj.a(PG:1,125)
07-15 15:28:24.508  3567  4331 E ExperimentLoader: 	at jdm.a(PG:77)
07-15 15:28:24.508  3567  4331 E ExperimentLoader: 	... 15 more
07-15 15:28:24.508  3567  4331 E ExperimentLoader: Caused by: faj: BadAuthentication
07-15 15:28:24.508  3567  4331 E ExperimentLoader: 	at fal.a(PG:38)
07-15 15:28:24.508  3567  4331 E ExperimentLoader: 	at jdj.a(PG:4089)
07-15 15:28:24.508  3567  4331 E ExperimentLoader: 	... 17 more
,07-15 15:28:24.683   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 541350, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-15 15:28:38.928   874  4259 D NetlinkSocketObserver: NeighborEvent{elapsedMs=561917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-15 15:28:44.955   874  4259 D NetlinkSocketObserver: NeighborEvent{elapsedMs=567944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-15 15:29:08.421   874  4259 D NetlinkSocketObserver: NeighborEvent{elapsedMs=591411, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-15 15:29:36.564  3526  3526 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,07-15 15:29:36.788  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:29:36.795  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:29:36.800  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:29:36.880  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-15 15:29:36.881  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-15 15:29:36.881  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:29:36.882  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:29:36.893  4040  4336 V GoogleAuthProtoRequest: [370] a.<init>: mAccountName set to: thalitester@gmail.com
,07-15 15:29:36.934  3526  3526 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-15 15:29:36.957  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:29:37.002  1523  2098 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-15 15:29:37.002  1523  2098 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-15 15:29:37.003  1523  2098 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:29:37.003  1523  2098 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:29:37.017  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-15 15:29:37.017  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,07-15 15:29:37.018  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-15 15:29:37.018  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:29:37.057  4040  4336 W ExperimentUpdateService: [370] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-15 15:29:37.059  4040  4336 W ExperimentUpdateService: [370] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-15 15:29:37.059  4040  4336 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-15 15:29:37.059  4040  4336 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-15 15:29:37.059  4040  4336 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-15 15:29:37.059  4040  4336 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-15 15:29:37.059  4040  4336 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-15 15:29:37.059  4040  4336 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-15 15:29:37.059  4040  4336 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-15 15:29:37.059  4040  4336 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-15 15:29:37.059  4040  4336 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-15 15:29:37.059  4040  4336 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-15 15:29:37.113  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:29:37.198  1523  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
07-15 15:29:37.198  1523  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-15 15:29:37.198  1523  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:29:37.199  1523  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:29:37.227  3526  3526 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-15 15:29:37.494  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:29:37.548  1523  2098 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-15 15:29:37.548  1523  2098 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-15 15:29:37.548  1523  2098 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:29:37.549  1523  2098 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:29:37.579  3526  3526 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-15 15:29:37.581  3526  3526 D Finsky  : [1] WearSupportService.startHygiene: disabled
,07-15 15:29:37.583  3526  3526 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,07-15 15:29:37.591  3526  3599 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,07-15 15:29:37.592  3526  3526 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2)
,07-15 15:29:52.607  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:29:52.627  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:29:52.634  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:29:52.704  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-15 15:29:52.704  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,07-15 15:29:52.705  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:29:52.705  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:29:52.760  3526  3526 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-15 15:29:52.760  3526  3526 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-15 15:29:52.761  3526  3526 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,07-15 15:30:05.808   874  4259 D NetlinkSocketObserver: NeighborEvent{elapsedMs=648797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-15 15:30:12.857   874  3203 I ActivityManager: Start proc 4343:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,07-15 15:30:12.903   874  2033 I ActivityManager: Start proc 4355:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,07-15 15:30:12.951  4343  4343 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,07-15 15:30:12.953  4355  4355 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,07-15 15:30:12.972  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:30:12.973  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:30:12.996  4040  4367 V GoogleAuthProtoRequest: [371] a.<init>: mAccountName set to: thalitester@gmail.com
,07-15 15:30:13.015  4343  4343 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
07-15 15:30:13.015  4343  4343 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-15 15:30:13.015  4343  4343 I GAv4    :   adb logcat -s GAv4
,07-15 15:30:13.053  4343  4343 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-15 15:30:13.065  4343  4343 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-15 15:30:13.122  4355  4370 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-15 15:30:13.131  4343  4375 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-15 15:30:13.160  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-15 15:30:13.160  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,07-15 15:30:13.160  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-15 15:30:13.161  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:30:13.246  4040  4367 W ExperimentUpdateService: [371] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-15 15:30:13.246  4040  4367 W ExperimentUpdateService: [371] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-15 15:30:13.246  4040  4367 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-15 15:30:13.246  4040  4367 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-15 15:30:13.246  4040  4367 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-15 15:30:13.246  4040  4367 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-15 15:30:13.246  4040  4367 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-15 15:30:13.246  4040  4367 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.,
07-15 15:30:13.246  4040  4367 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-15 15:30:13.246  4040  4367 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-15 15:30:13.246  4040  4367 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-15 15:30:13.246  4040  4367 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-15 15:30:13.304  4355  4370 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-15 15:30:13.418  4355  4370 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-15 15:30:13.456  4355  4355 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,07-15 15:30:13.644  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:30:13.690  1523  1896 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-15 15:30:13.695  1523  1896 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-15 15:30:13.695  1523  1896 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:30:13.695  1523  1896 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:30:13.723  3526  3526 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-15 15:30:13.723  3526  3526 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-15 15:30:13.724  3526  3526 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,07-15 15:30:13.784  4355  4355 W InstanceID/Rpc: Found 10011
,07-15 15:30:13.809  4398  4398 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads-988755166.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-988755166.dex
,07-15 15:30:13.879   874  1393 I ActivityManager: Killing 3728:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,07-15 15:30:13.957  4398  4398 I dex2oat : dex2oat took 161.166ms (threads: 4) arena alloc=212KB java alloc=29KB native alloc=1514KB free=1557KB
,07-15 15:30:14.002   874  1702 I ActivityManager: Killing 3629:com.android.defcontainer/u0a7 (adj 15): empty #17
,07-15 15:30:37.621   874  4259 D NetlinkSocketObserver: NeighborEvent{elapsedMs=680610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-15 15:30:44.022  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:30:44.032  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:30:44.034  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:30:44.062  1523  1896 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-15 15:30:44.062  1523  1896 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,07-15 15:30:44.062  1523  1896 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-15 15:30:44.062  1523  1896 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:30:44.085  3526  3526 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-15 15:30:44.086  3526  3526 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-15 15:30:44.086  3526  3526 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,07-15 15:31:14.225  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:31:14.228  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:31:14.230  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:31:14.245  4040  4447 V GoogleAuthProtoRequest: [372] a.<init>: mAccountName set to: thalitester@gmail.com
,07-15 15:31:14.269  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
07-15 15:31:14.269  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-15 15:31:14.269  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-15 15:31:14.269  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:31:14.278  1523  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
07-15 15:31:14.279  1523  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-15 15:31:14.279  1523  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-15 15:31:14.279  1523  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:31:14.289  3526  3526 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
07-15 15:31:14.289  3526  3526 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-15 15:31:14.290  3526  3526 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,07-15 15:31:14.304  4040  4447 W ExperimentUpdateService: [372] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-15 15:31:14.304  4040  4447 W ExperimentUpdateService: [372] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-15 15:31:14.304  4040  4447 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-15 15:31:14.304  4040  4447 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-15 15:31:14.304  4040  4447 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-15 15:31:14.304  4040  4447 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-15 15:31:14.304  4040  4447 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-15 15:31:14.304  4040  4447 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-15 15:31:14.304  4040  4447 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-15 15:31:14.304  4040  4447 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-15 15:31:14.304  4040  4447 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-15 15:31:14.304  4040  4447 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-15 15:31:22.079  3050  4448 V KeepSync: Connecting to GoogleApiClient
07-15 15:31:22.080   874  2033 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-15 15:31:22.155  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:31:22.156  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:31:22.214  1523  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-15 15:31:22.214  1523  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-15 15:31:22.214  1523  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:31:22.214  1523  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:31:22.236  1973  4449 V BaseAuthAsyncOperation: access token request failed
,07-15 15:31:22.237  3050  4448 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-15 15:31:22.304  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-15 15:31:22.305  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-15 15:31:22.305  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:31:22.305  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:31:22.316  3050  4448 E KeepSync: IOException
07-15 15:31:22.316  3050  4448 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-15 15:31:22.316  3050  4448 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-15 15:31:22.316  3050  4448 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-15 15:31:22.316  3050  4448 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-15 15:31:22.316  3050  4448 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-15 15:31:22.316  3050  4448 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-15 15:31:22.316  3050  4448 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-15 15:31:22.316  3050  4448 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-15 15:31:22.316  3050  4448 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-15 15:31:22.316  3050  4448 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-15 15:31:22.316  3050  4448 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-15 15:31:22.316  3050  4448 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-15 15:31:22.316  3050  4448 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-15 15:31:22.316  3050  4448 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-15 15:31:22.316  3050  4448 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-15 15:31:22.316  3050  4448 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-15 15:31:22.316  3050  4448 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-15 15:31:22.316  3050  4448 E KeepSync: 	... 10 more
07-15 15:31:22.316  3050  4448 W KeepSync: Sync result 2
,07-15 15:31:22.325   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 724995, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-15 15:31:44.669  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:31:44.677  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:31:44.680  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:31:44.737  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-15 15:31:44.737  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-15 15:31:44.738  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:31:44.738  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:31:44.785  3526  3526 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-15 15:31:44.786  3526  3526 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-15 15:31:44.786  3526  3526 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,07-15 15:32:04.985  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:32:04.993  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:32:04.995  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:32:05.018  1523  4450 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
07-15 15:32:05.018  1523  4450 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,07-15 15:32:05.018  1523  4450 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:32:05.018  1523  4450 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:32:05.043  3526  3526 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
07-15 15:32:05.043  3526  3526 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-15 15:32:05.043  3526  3526 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,07-15 15:32:12.757  4089  4456 I BooksSync: Starting books sync for 61035162, extras: ade
,07-15 15:32:12.788  4089  4457 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-15 15:32:12.802  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:32:12.804  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:32:12.836  1523  1896 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-15 15:32:12.836  1523  1896 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-15 15:32:12.836  1523  1896 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:32:12.836  1523  1896 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:32:12.865  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:32:12.868  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:32:12.890  1523  2101 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-15 15:32:12.890  1523  2101 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-15 15:32:12.890  1523  2101 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:32:12.890  1523  2101 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:32:12.919  4089  4457 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-15 15:32:12.920  4089  4456 E BooksSync: Soft error
07-15 15:32:12.920  4089  4456 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-15 15:32:12.920  4089  4456 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-15 15:32:12.920  4089  4456 E BooksSync: Sync error
07-15 15:32:12.920  4089  4456 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-15 15:32:12.920  4089  4456 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-15 15:32:12.920  4089  4456 I BooksSync: Finished books sync
,07-15 15:32:12.931   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 775683, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-15 15:32:43.315  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:32:43.316  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:32:43.364  1523  2098 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-15 15:32:43.364  1523  2098 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-15 15:32:43.365  1523  2098 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:32:43.365  1523  2098 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:32:43.380  3567  4460 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-15 15:32:43.380  3567  4460 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-15 15:32:43.380  3567  4460 E HttpOperation: 	at jdm.a(PG:82)
07-15 15:32:43.380  3567  4460 E HttpOperation: 	at jcs.o(PG:406)
07-15 15:32:43.380  3567  4460 E HttpOperation: 	at jcn.a(PG:1379)
07-15 15:32:43.380  3567  4460 E HttpOperation: 	at jcs.i(PG:143)
07-15 15:32:43.380  3567  4460 E HttpOperation: 	at blb.a(PG:3937)
07-15 15:32:43.380  3567  4460 E HttpOperation: 	at czp.a(PG:18188)
07-15 15:32:43.380  3567  4460 E HttpOperation: 	at czp.a(PG:9081)
07-15 15:32:43.380  3567  4460 E HttpOperation: 	at czq.run(PG:1686)
07-15 15:32:43.380  3567  4460 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-15 15:32:43.380  3567  4460 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-15 15:32:43.380  3567  4460 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-15 15:32:43.380  3567  4460 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-15 15:32:43.380  3567  4460 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-15 15:32:43.380  3567  4460 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-15 15:32:43.380  3567  4460 E HttpOperation: 	at jdj.a(PG:4091)
07-15 15:32:43.380  3567  4460 E HttpOperation: 	at jdj.a(PG:1125)
07-15 15:32:43.380  3567  4460 E HttpOperation: 	at jdm.a(PG:77)
07-15 15:32:43.380  3567  4460 E HttpOperation: 	... 12 more
07-15 15:32:43.380  3567  4460 E HttpOperation: Caused by: faj: BadAuthentication
07-15 15:32:43.380  3567  4460 E HttpOperation: 	at fal.a(PG:38)
07-15 15:32:43.380  3567  4460 E HttpOperation: 	at jdj.a(PG:4089)
07-15 15:32:43.380  3567  4460 E HttpOperation: 	... 14 more
,07-15 15:32:43.435  1523  1896 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-15 15:32:43.435  1523  1896 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-15 15:32:43.435  1523  1896 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:32:43.435  1523  1896 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:32:43.450  3567  4460 E HttpOperation: [getmobileexperiments] Unexpected exception
07-15 15:32:43.450  3567  4460 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-15 15:32:43.450  3567  4460 E HttpOperation: 	at jdm.a(PG:82)
07-15 15:32:43.450  3567  4460 E HttpOperation: 	at jcs.o(PG:406)
07-15 15:32:43.450  3567  4460 E HttpOperation: 	at jcn.a(PG:1379)
07-15 15:32:43.450  3567  4460 E HttpOperation: 	at jcs.i(PG:143)
07-15 15:32:43.450  3567  4460 E HttpOperation: 	at hec.a(PG:42)
07-15 15:32:43.450  3567  4460 E HttpOperation: 	at hee.a(PG:102)
07-15 15:32:43.450  3567  4460 E HttpOperation: 	at czr.a(PG:65)
07-15 15:32:43.450  3567  4460 E HttpOperation: 	at kka.a(PG:108)
07-15 15:32:43.450  3567  4460 E HttpOperation: 	at czp.a(PG:19176)
07-15 15:32:43.450  3567  4460 E HttpOperation: 	at czp.a(PG:9081)
07-15 15:32:43.450  3567  4460 E HttpOperation: 	at czq.run(PG:1686)
07-15 15:32:43.450  3567  4460 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-15 15:32:43.450  3567  4460 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-15 15:32:43.450  3567  4460 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-15 15:32:43.450  3567  4460 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-15 15:32:43.450  3567  4460 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-15 15:32:43.450  3567  4460 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-15 15:32:43.450  3567  4460 E HttpOperation: 	at jdj.a(PG:4091)
07-15 15:32:43.450  3567  4460 E HttpOperation: 	at jdj.a(PG:1125)
07-15 15:32:43.450  3567  4460 E HttpOperation: 	at jdm.a(PG:77)
07-15 15:32:43.450  3567  4460 E HttpOperation: 	... 15 more
07-15 15:32:43.450  3567  4460 E HttpOperation: Caused by: faj: BadAuthentication
07-15 15:32:43.450  3567  4460 E HttpOperation: 	at fal.a(PG:38)
07-15 15:32:43.450  3567  4460 E HttpOperation: 	at jdj.a(PG:4089)
07-15 15:32:43.450  3567  4460 E HttpOperation: 	... 17 more
,07-15 15:32:43.450  3567  4460 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-15 15:32:43.450  3567  4460 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-15 15:32:43.450  3567  4460 E ExperimentLoader: 	at jdm.a(PG:82)
07-15 15:32:43.450  3567  4460 E ExperimentLoader: 	at jcs.o(PG:406)
07-15 15:32:43.450  3567  4460 E ExperimentLoader: 	at jcn.a(PG:1379)
07-15 15:32:43.450  3567  4460 E ExperimentLoader: 	at jcs.i(PG:143)
07-15 15:32:43.450  3567  4460 E ExperimentLoader: 	at hec.a(PG:42)
07-15 15:32:43.450  3567  4460 E ExperimentLoader: 	at hee.a(PG:102)
07-15 15:32:43.450  3567  4460 E ExperimentLoader: 	at czr.a(PG:65)
07-15 15:32:43.450  3567  4460 E ExperimentLoader: 	at kka.a(PG:108)
07-15 15:32:43.450  3567  4460 E ExperimentLoader: 	at czp.a(PG:19176)
07-15 15:32:43.450  3567  4460 E ExperimentLoader: 	at czp.a(PG:9081)
07-15 15:32:43.450  3567  4460 E ExperimentLoader: 	at czq.run(PG:1686)
07-15 15:32:43.450  3567  4460 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-15 15:32:43.450  3567  4460 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-15 15:32:43.450  3567  4460 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-15 15:32:43.450  3567  4460 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-15 15:32:43.450  3567  4460 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-15 15:32:43.450  3567  4460 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-15 15:32:43.450  3567  4460 E ExperimentLoader: 	at jdj.a(PG:4091)
07-15 15:32:43.450  3567  4460 E ExperimentLoader: 	at jdj.a(PG:1125)
07-15 15:32:43.450  3567  4460 E ExperimentLoader: 	at jdm.a(PG:77)
07-15 15:32:43.450  3567  4460 E ExperimentLoader: 	... 15 more
07-15 15:32:43.450  3567  4460 E ExperimentLoader: Caused by: faj: BadAuthentication
07-15 15:32:43.450  3567  4460 E ExperimentLoader: 	at fal.a(PG:38)
07-15 15:32:43.450  3567  4460 E ExperimentLoader: 	at jdj.a(PG:4089)
07-15 15:32:43.450  3567  4460 E ExperimentLoader: 	... 17 more
,07-15 15:32:43.572   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 794209, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-15 15:33:14.502  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:33:14.503  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:33:14.514  4040  4463 V GoogleAuthProtoRequest: [373] a.<init>: mAccountName set to: thalitester@gmail.com
,07-15 15:33:14.537  1523  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-15 15:33:14.537  1523  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-15 15:33:14.537  1523  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:33:14.537  1523  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:33:14.553  4040  4463 W ExperimentUpdateService: [373] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-15 15:33:14.554  4040  4463 W ExperimentUpdateService: [373] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-15 15:33:14.554  4040  4463 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-15 15:33:14.554  4040  4463 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-15 15:33:14.554  4040  4463 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-15 15:33:14.554  4040  4463 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-15 15:33:14.554  4040  4463 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-15 15:33:14.554  4040  4463 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-15 15:33:14.554  4040  4463 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-15 15:33:14.554  4040  4463 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-15 15:33:14.554  4040  4463 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-15 15:33:14.554  4040  4463 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-15 15:39:11.314  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:39:11.315  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:39:11.324  4040  4480 V GoogleAuthProtoRequest: [374] a.<init>: mAccountName set to: thalitester@gmail.com
,07-15 15:39:11.382  1973  4482 I EventLogService: Opted in for usage reporting
,07-15 15:39:11.388  1973  4482 I EventLogService: Aggregate from 1468588150992 (log), 1468588150992 (data)
,07-15 15:39:11.485  1523  1523 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-15 15:39:11.538  1523  4450 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-15 15:39:11.538  1523  4450 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-15 15:39:11.538  1523  4450 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:39:11.538  1523  4450 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:39:11.573  4040  4480 W ExperimentUpdateService: [374] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-15 15:39:11.573  4040  4480 W ExperimentUpdateService: [374] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-15 15:39:11.573  4040  4480 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-15 15:39:11.573  4040  4480 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-15 15:39:11.573  4040  4480 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-15 15:39:11.573  4040  4480 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-15 15:39:11.573  4040  4480 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-15 15:39:11.573  4040  4480 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-15 15:39:11.573  4040  4480 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-15 15:39:11.573  4040  4480 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-15 15:39:11.573  4040  4480 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-15 15:39:11.573  4040  4480 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-15 15:39:11.615  1973  4482 W EventLogAggregator: Unknown tag: snet_gcore
07-15 15:39:11.615  1973  4482 W EventLogAggregator: Unknown tag: snet_launch_service
,07-15 15:39:11.669  1973  4482 I ServiceDumpSys: dumping service [account]
,07-15 15:39:11.844  1523  4483 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,07-15 15:39:16.314   874  4259 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1199303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-15 15:39:32.634   874  4259 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1215623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-15 15:39:32.710  3050  4494 V KeepSync: Connecting to GoogleApiClient
,07-15 15:39:32.710   874  3204 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-15 15:39:32.756  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:39:32.758  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:39:32.785  1523  2101 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-15 15:39:32.785  1523  2101 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-15 15:39:32.786  1523  2101 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:39:32.786  1523  2101 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:39:32.805  1973  4495 V BaseAuthAsyncOperation: access token request failed
,07-15 15:39:32.806  3050  4494 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-15 15:39:32.857  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-15 15:39:32.857  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-15 15:39:32.857  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:39:32.857  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:39:32.873  3050  4494 E KeepSync: IOException
07-15 15:39:32.873  3050  4494 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-15 15:39:32.873  3050  4494 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-15 15:39:32.873  3050  4494 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-15 15:39:32.873  3050  4494 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-15 15:39:32.873  3050  4494 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-15 15:39:32.873  3050  4494 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-15 15:39:32.873  3050  4494 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-15 15:39:32.873  3050  4494 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-15 15:39:32.873  3050  4494 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-15 15:39:32.873  3050  4494 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-15 15:39:32.873  3050  4494 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-15 15:39:32.873  3050  4494 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-15 15:39:32.873  3050  4494 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-15 15:39:32.873  3050  4494 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-15 15:39:32.873  3050  4494 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-15 15:39:32.873  3050  4494 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-15 15:39:32.873  3050  4494 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-15 15:39:32.873  3050  4494 E KeepSync: 	... 10 more
07-15 15:39:32.873  3050  4494 W KeepSync: Sync result 2
,07-15 15:39:32.886   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 1215587, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-15 15:39:35.731   874   886 I UsageStatsService: User[0] Flushing usage stats to disk
,07-15 15:40:50.575  4089  4500 I BooksSync: Starting books sync for 61035162, extras: ade
,07-15 15:40:50.607  4089  4501 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-15 15:40:50.617  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:40:50.622  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:40:50.660  1523  2101 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-15 15:40:50.660  1523  2101 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-15 15:40:50.660  1523  2101 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:40:50.661  1523  2101 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:40:50.696  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:40:50.698  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:40:50.733  1523  1896 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-15 15:40:50.734  1523  1896 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-15 15:40:50.734  1523  1896 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:40:50.734  1523  1896 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:40:50.756  4089  4501 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-15 15:40:50.758  4089  4500 E BooksSync: Soft error
07-15 15:40:50.758  4089  4500 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-15 15:40:50.758  4089  4500 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-15 15:40:50.758  4089  4500 E BooksSync: Sync error
07-15 15:40:50.758  4089  4500 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-15 15:40:50.758  4089  4500 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-15 15:40:50.758  4089  4500 I BooksSync: Finished books sync
,07-15 15:40:50.773   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1293297, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-15 15:41:21.162  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:41:21.171  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-15 15:41:21.224  1523  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-15 15:41:21.224  1523  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-15 15:41:21.224  1523  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-15 15:41:21.224  1523  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:41:21.246  3567  4504 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-15 15:41:21.246  3567  4504 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-15 15:41:21.246  3567  4504 E HttpOperation: 	at jdm.a(PG:82)
07-15 15:41:21.246  3567  4504 E HttpOperation: 	at jcs.o(PG:406)
07-15 15:41:21.246  3567  4504 E HttpOperation: 	at jcn.a(PG:1379)
07-15 15:41:21.246  3567  4504 E HttpOperation: 	at jcs.i(PG:143)
07-15 15:41:21.246  3567  4504 E HttpOperation: 	at blb.a(PG:3937)
07-15 15:41:21.246  3567  4504 E HttpOperation: 	at czp.a(PG:18188)
07-15 15:41:21.246  3567  4504 E HttpOperation: 	at czp.a(PG:9081)
07-15 15:41:21.246  3567  4504 E HttpOperation: 	at czq.run(PG:1686)
07-15 15:41:21.246  3567  4504 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-15 15:41:21.246  3567  4504 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-15 15:41:21.246  3567  4504 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-15 15:41:21.246  3567  4504 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-15 15:41:21.246  3567  4504 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-15 15:41:21.246  3567  4504 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-15 15:41:21.246  3567  4504 E HttpOperation: 	at jdj.a(PG:4091)
07-15 15:41:21.246  3567  4504 E HttpOperation: 	at jdj.a(PG:1125)
07-15 15:41:21.246  3567  4504 E HttpOperation: 	at jdm.a(PG:77)
07-15 15:41:21.246  3567  4504 E HttpOperation: 	... 12 more
07-15 15:41:21.246  3567  4504 E HttpOperation: Caused by: faj: BadAuthentication
07-15 15:41:21.246  3567  4504 E HttpOperation: 	at fal.a(PG:38)
07-15 15:41:21.246  3567  4504 E HttpOperation: 	at jdj.a(PG:4089)
07-15 15:41:21.246  3567  4504 E HttpOperation: 	... 14 more
,07-15 15:41:21.289  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-15 15:41:21.289  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-15 15:41:21.289  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
07-15 15:41:21.289  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-15 15:41:21.307  3567  4504 E HttpOperation: [getmobileexperiments] Unexpected exception
07-15 15:41:21.307  3567  4504 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-15 15:41:21.307  3567  4504 E HttpOperation: 	at jdm.a(PG:82)
07-15 15:41:21.307  3567  4504 E HttpOperation: 	at jcs.o(PG:406)
07-15 15:41:21.307  3567  4504 E HttpOperation: 	at jcn.a(PG:1379)
07-15 15:41:21.307  3567  4504 E HttpOperation: 	at jcs.i(PG:143)
07-15 15:41:21.307  3567  4504 E HttpOperation: 	at hec.a(PG:42)
07-15 15:41:21.307  3567  4504 E HttpOperation: 	at hee.a(PG:102)
07-15 15:41:21.307  3567  4504 E HttpOperation: 	at czr.a(PG:65)
07-15 15:41:21.307  3567  4504 E HttpOperation: 	at kka.a(PG:108)
07-15 15:41:21.307  3567  4504 E HttpOperation: 	at czp.a(PG:19176)
07-15 15:41:21.307  3567  4504 E HttpOperation: 	at czp.a(PG:9081)
07-15 15:41:21.307  3567  4504 E HttpOperation: 	at czq.run(PG:1686)
07-15 15:41:21.307  3567  4504 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-15 15:41:21.307  3567  4504 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-15 15:41:21.307  3567  4504 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-15 15:41:21.307  3567  4504 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-15 15:41:21.307  3567  4504 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-15 15:41:21.307  3567  4504 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-15 15:41:21.307  3567  4504 E HttpOperation: 	at jdj.a(PG:4091)
07-15 15:41:21.307  3567  4504 E HttpOperation: 	at jdj.a(PG:1125)
07-15 15:41:21.307  3567  4504 E HttpOperation: 	at jdm.a(PG:77)
07-15 15:41:21.307  3567  4504 E HttpOperation: 	... 15 more
07-15 15:41:21.307  3567  4504 E HttpOperation: Caused by: faj: BadAuthentication
07-15 15:41:21.307  3567  4504 E HttpOperation: 	at fal.a(PG:38)
07-15 15:41:21.307  3567  4504 E HttpOperation: 	at jdj.a(PG:4089)
07-15 15:41:21.307  3567  4504 E HttpOperation: 	... 17 more
,07-15 15:41:21.308  3567  4504 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-15 15:41:21.308  3567  4504 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-15 15:41:21.308  3567  4504 E ExperimentLoader: 	at jdm.a(PG:82)
07-15 15:41:21.308  3567  4504 E ExperimentLoader: 	at jcs.o(PG:406)
07-15 15:41:21.308  3567  4504 E ExperimentLoader: 	at jcn.a(PG:1379)
07-15 15:41:21.308  3567  4504 E ExperimentLoader: 	at jcs.i(PG:143)
07-15 15:41:21.308  3567  4504 E ExperimentLoader: 	at hec.a(PG:42)
07-15 15:41:21.308  3567  4504 E ExperimentLoader: 	at hee.a(PG:102)
07-15 15:41:21.308  3567  4504 E ExperimentLoader: 	at czr.a(PG:65)
07-15 15:41:21.308  3567  4504 E ExperimentLoader: 	at kka.a(PG:108)
07-15 15:41:21.308  3567  4504 E ExperimentLoader: 	at czp.a(PG:19176)
07-15 15:41:21.308  3567  4504 E ExperimentLoader: 	at czp.a(PG:9081)
07-15 15:41:21.308  3567  4504 E ExperimentLoader: 	at czq.run(PG:1686)
07-15 15:41:21.308  3567  4504 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-15 15:41:21.308  3567  4504 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-15 15:41:21.308  3567  4504 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-15 15:41:21.308  3567  4504 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-15 15:41:21.308  3567  4504 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-15 15:41:21.308  3567  4504 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-15 15:41:21.308  3567  4504 E ExperimentLoader: 	at jdj.a(PG:4091)
07-15 15:41:21.308  3567  4504 E ExperimentLoader: 	at jdj.a(PG:1125)
07-15 15:41:21.308  3567  4504 E ExperimentLoader: 	at jdm.a(PG:77)
07-15 15:41:21.308  3567  4504 E ExperimentLoader: 	... 15 more
07-15 15:41:21.308  3567  4504 E ExperimentLoader: Caused by: faj: BadAuthentication
07-15 15:41:21.308  3567  4504 E ExperimentLoader: 	at fal.a(PG:38)
07-15 15:41:21.308  3567  4504 E ExperimentLoader: 	at jdj.a(PG:4089)
07-15 15:41:21.308  3567  4504 E ExperimentLoader: 	... 17 more
,07-15 15:41:21.432   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1299634, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-15 15:43:17.061   874  4259 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1440050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-15 15:43:37.914   874  4259 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1460903, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-15 15:44:16.821   874  4259 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1499810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-15 15:44:36.261   874  4259 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1519250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1400000ms),07-15 15:45:32.144  4517  4517 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-15 15:45:32.148  4517  4517 D AndroidRuntime: CheckJNI is OFF
07-15 15:45:32.185  4517  4517 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-15 15:45:32.224  4517  4517 I Radio-JNI: register_android_hardware_Radio DONE
07-15 15:45:32.245  4517  4517 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-15 15:45:32.256   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
07-15 15:45:32.257   874   887 I ActivityManager: Killing 3840:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
07-15 15:45:32.360   874  1393 D GraphicsStats: Buffer count: 2
07-15 15:45:32.360   874  1706 I WindowState: WIN DEATH: Window{9394658 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-15 15:45:32.361   874  1315 D WifiService: Client connection lost with reason: 4
07-15 15:45:32.389   874   897 W PackageSettings: Skipping PackageSetting{4000567 com.example.hello/10273} due to missing metadata
07-15 15:45:32.418   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
07-15 15:45:32.418   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
07-15 15:45:32.419   874   887 E ActivityManager: Failure starting process com.test.thalitest
07-15 15:45:32.419   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
07-15 15:45:32.419   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
07-15 15:45:32.419   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
07-15 15:45:32.419   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
07-15 15:45:32.419   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
07-15 15:45:32.419   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
07-15 15:45:32.419   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
07-15 15:45:32.419   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
07-15 15:45:32.419   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
07-15 15:45:32.419   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
07-15 15:45:32.419   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
07-15 15:45:32.419   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
07-15 15:45:32.419   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
07-15 15:45:32.419   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
07-15 15:45:32.419   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
07-15 15:45:32.419   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:45:32.419   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:45:32.419   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-15 15:45:32.419   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-15 15:45:32.419   874   887 I ActivityManager:   Force finishing activity ActivityRecord{6ffac55 u0 com.test.thalitest/.MainActivity t10}
07-15 15:45:32.428   874  1702 W ActivityManager: Spurious death for ProcessRecord{852a2db 0:com.test.thalitest/u0a0}, curProc for 3840: null
07-15 15:45:32.430   874   897 I art     : Starting a blocking GC Explicit
07-15 15:45:32.474   874   897 I art     : Explicit concurrent mark sweep GC freed 40597(2MB) AllocSpace objects, 11(220KB) LOS objects, 33% free, 29MB/43MB, paused 710us total 43.991ms
07-15 15:45:32.497   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
07-15 15:45:32.514  4517  4517 I art     : System.exit called, status: 0
07-15 15:45:32.514  4517  4517 I AndroidRuntime: VM exiting with result code 0.
07-15 15:45:32.525   874   897 I ActivityManager: Start proc 4528:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
07-15 15:45:32.526   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
07-15 15:45:32.539   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
07-15 15:45:32.543  4200  4200 D BluetoothMapAppObserver: onReceive
07-15 15:45:32.543  4200  4200 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
07-15 15:45:32.544  1950  2057 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-15 15:45:32.549   874  1306 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-15 15:45:32.552  3676  3676 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
07-15 15:45:32.553  1662  1662 I Keyboard.Facilitator: resetDictionaries() : en_US
07-15 15:45:32.563  1662  4540 I Keyboard.Facilitator.DecoderInitializer: run()
07-15 15:45:32.568  1662  4540 I Decoder : createOrResetDecoder
07-15 15:45:32.603  1745  1745 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
07-15 15:45:32.612   874  1764 I ActivityManager: Start proc 4544:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
07-15 15:45:32.614   874  3204 I ActivityManager: Killing 1807:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
07-15 15:45:32.622   874  2031 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3840 uid 10000
07-15 15:45:32.646   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-15 15:45:32.648  1662  1662 I Keyboard.Facilitator: onFinishInput()
07-15 15:45:32.678   874  1315 D WifiService: Client connection lost with reason: 4
07-15 15:45:32.689  1523  1523 I ConfigService: onCreate
07-15 15:45:32.693   874  1312 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
07-15 15:45:32.699   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
07-15 15:45:32.700   874   886 E PackageManager: Failed to write settings, restoring backup
07-15 15:45:32.700   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
07-15 15:45:32.700   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
07-15 15:45:32.700   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
07-15 15:45:32.700   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
07-15 15:45:32.700   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
07-15 15:45:32.700   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:45:32.700   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:45:32.700   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-15 15:45:32.701  1759  1837 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
07-15 15:45:32.705  1523  4557 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
07-15 15:45:32.705  1523  4557 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-15 15:45:32.705  1523  4557 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-15 15:45:32.705  1523  4557 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-15 15:45:32.705  1523  4557 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-15 15:45:32.705  1523  4557 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-15 15:45:32.705  1523  4557 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-15 15:45:32.705  1523  4557 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-15 15:45:32.705  1523  4557 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-15 15:45:32.705  1523  4557 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-15 15:45:32.705  1523  4557 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-15 15:45:32.705  1523  4557 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-15 15:45:32.705  1523  4557 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-15 15:45:32.705  1523  4557 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-15 15:45:32.705  1523  4557 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-15 15:45:32.705  1523  4557 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
07-15 15:45:32.705  1523  4557 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
07-15 15:45:32.705  1523  4557 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-15 15:45:32.705  1523  4557 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
07-15 15:45:32.705  1523  4557 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-15 15:45:32.705  1523  4557 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-15 15:45:32.705  1523  4557 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-15 15:45:32.705  1523  4557 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-15 15:45:32.705  1523  4557 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-15 15:45:32.705  1523  4557 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-15 15:45:32.705  1523  4557 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-15 15:45:32.705  1523  4557 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-15 15:45:32.705  1523  4557 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-15 15:45:32.705  1523  4557 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-15 15:45:32.705  1523  4557 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-15 15:45:32.705  1523  4557 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-15 15:45:32.705  1523  4557 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-15 15:45:32.705  1523  4557 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-15 15:45:32.705  1523  4557 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
07-15 15:45:32.705  1523  4557 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
07-15 15:45:32.705  1523  4557 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
07-15 15:45:32.707   874   887 E DropBoxManagerService: Can't write: system_server_wtf
07-15 15:45:32.707   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
07-15 15:45:32.707   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-15 15:45:32.707   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-15 15:45:32.707   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-15 15:45:32.707   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-15 15:45:32.707   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-15 15:45:32.707   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-15 15:45:32.707   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
07-15 15:45:32.707   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
07-15 15:45:32.707   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
07-15 15:45:32.707   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
07-15 15:45:32.707   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-15 15:45:32.707   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:45:32.707   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-15 15:45:32.707   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-15 15:45:32.707   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-15 15:45:32.707   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-15 15:45:32.707   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-15 15:45:32.707   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-15 15:45:32.707   874   887 E DropBoxManagerService: 	... 13 more
07-15 15:45:32.710  4544  4544 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
07-15 15:45:32.723   874  3202 I ActivityManager: Start proc 4558:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
07-15 15:45:32.724  1759  1837 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
07-15 15:45:32.724  1759  1837 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1759
07-15 15:45:32.724  1759  1837 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-15 15:45:32.724  1759  1837 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-15 15:45:32.724  1759  1837 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
07-15 15:45:32.724  1759  1837 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-15 15:45:32.724  1759  1837 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-15 15:45:32.724  1759  1837 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
07-15 15:45:32.724  1759  1837 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
07-15 15:45:32.724  1759  1837 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
07-15 15:45:32.724  1759  1837 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
07-15 15:45:32.724  1759  1837 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-15 15:45:32.724  1759  1837 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:45:32.724  1759  1837 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-15 15:45:32.726   874  1758 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
07-15 15:45:32.727   874  4563 E DropBoxManagerService: Can't write: system_app_crash
07-15 15:45:32.727   874  4563 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
07-15 15:45:32.727   874  4563 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-15 15:45:32.727   874  4563 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-15 15:45:32.727   874  4563 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-15 15:45:32.727   874  4563 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-15 15:45:32.727   874  4563 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-15 15:45:32.727   874  4563 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-15 15:45:32.727   874  4563 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-15 15:45:32.727   874  4563 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-15 15:45:32.727   874  4563 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-15 15:45:32.727   874  4563 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-15 15:45:32.727   874  4563 E DropBoxManagerService: 	... 5 more
07-15 15:45:32.730  1759  1837 I Process : Sending signal. PID: 1759 SIG: 9
07-15 15:45:32.760  1523  4557 W SQLiteOpenHelper: Opened config.db in read-only mode
07-15 15:45:32.774  1662  4540 I Keyboard.Facilitator.MainLanguageModelLoader: run()
07-15 15:45:32.823  1662  4540 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
07-15 15:45:32.825  1662  4540 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
07-15 15:45:32.825  1662  4540 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
07-15 15:45:32.826  1662  4540 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
07-15 15:45:32.828  1662  4540 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
07-15 15:45:32.829  1662  4540 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
07-15 15:45:32.829  1662  4540 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
07-15 15:45:32.830  1662  4540 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
07-15 15:45:32.830  1662  4540 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
07-15 15:45:32.830  1662  4540 I Keyboard.Facilitator.Delight2FileSweeper: run()
07-15 15:45:32.830  1662  4540 I Keyboard.Facilitator.RecurringTaskScheduler: run()
07-15 15:45:32.830  1662  4540 I StatsUtilsManager: startPeriodStatsRecorder() : Success
07-15 15:45:32.830  1662  4540 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
07-15 15:45:32.867   874  3203 I WindowState: WIN DEATH: Window{37ee8ed u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
07-15 15:45:32.871   874  1758 D GraphicsStats: Buffer count: 1
07-15 15:45:32.891   874  3202 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1759) has died
07-15 15:45:32.892   874  3202 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
07-15 15:45:32.895  4544  4576 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
07-15 15:45:32.895  4544  4576 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-15 15:45:32.895  4544  4576 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-15 15:45:32.895  4544  4576 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-15 15:45:32.895  4544  4576 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-15 15:45:32.895  4544  4576 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-15 15:45:32.895  4544  4576 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-15 15:45:32.895  4544  4576 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-15 15:45:32.895  4544  4576 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-15 15:45:32.895  4544  4576 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-15 15:45:32.895  4544  4576 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-15 15:45:32.895  4544  4576 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-15 15:45:32.895  4544  4576 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-15 15:45:32.895  4544  4576 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-15 15:45:32.895  4544  4576 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-15 15:45:32.895  4544  4576 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
07-15 15:45:32.895  4544  4576 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
07-15 15:45:32.895  4544  4576 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
07-15 15:45:32.895  4544  4576 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
07-15 15:45:32.895  4544  4576 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:45:32.895  4544  4576 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:45:32.895  4544  4576 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-15 15:45:32.895   874  3202 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
07-15 15:45:32.895  4544  4576 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
07-15 15:45:32.895  4544  4576 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-15 15:45:32.895  4544  4576 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-15 15:45:32.895  4544  4576 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-15 15:45:32.895  4544  4576 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-15 15:45:32.895  4544  4576 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-15 15:45:32.895  4544  4576 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-15 15:45:32.895  4544  4576 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-15 15:45:32.895  4544  4576 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-15 15:45:32.895  4544  4576 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-15 15:45:32.895  4544  4576 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-15 15:45:32.895  4544  4576 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-15 15:45:32.895  4544  4576 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-15 15:45:32.895  4544  4576 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-15 15:45:32.895  4544  4576 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-15 15:45:32.895  4544  4576 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
07-15 15:45:32.895  4544  4576 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
07-15 15:45:32.895  4544  4576 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
07-15 15:45:32.895  4544  4576 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
07-15 15:45:32.895  4544  4576 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:45:32.895  4544  4576 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:45:32.895  4544  4576 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-15 15:45:32.905  4544  4544 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
07-15 15:45:32.916   874   887 I ActivityManager: Start proc 4579:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
07-15 15:45:32.934  1973  4577 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
07-15 15:45:32.936   874  3202 I ActivityManager: Start proc 4592:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
07-15 15:45:32.949  1973  4577 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
07-15 15:45:32.966  4544  4591 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-15 15:45:32.968  4579  4579 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-15 15:45:32.969  4579  4579 D AndroidRuntime: Shutting down VM
07-15 15:45:32.979  4579  4579 E AndroidRuntime: FATAL EXCEPTION: main
07-15 15:45:32.979  4579  4579 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4579
07-15 15:45:32.979  4579  4579 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-15 15:45:32.979  4579  4579 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
07-15 15:45:32.979  4579  4579 E AndroidRuntime: 	... 10 more
07-15 15:45:32.982   874  2033 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
07-15 15:45:32.982  4579  4579 I Process : Sending signal. PID: 4579 SIG: 9
07-15 15:45:32.983   874  4604 E DropBoxManagerService: Can't write: system_app_crash
07-15 15:45:32.983   874  4604 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
07-15 15:45:32.983   874  4604 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-15 15:45:32.983   874  4604 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-15 15:45:32.983   874  4604 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-15 15:45:32.983   874  4604 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-15 15:45:32.983   874  4604 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-15 15:45:32.983   874  4604 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-15 15:45:32.983   874  4604 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-15 15:45:32.983   874  4604 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-15 15:45:32.983   874  4604 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-15 15:45:32.983   874  4604 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-15 15:45:32.983   874  4604 E DropBoxManagerService: 	... 5 more
07-15 15:45:32.991  1973  4577 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
07-15 15:45:32.991  1973  4577 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
07-15 15:45:32.996  4592  4592 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
07-15 15:45:33.008   874  1706 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4579) has died
07-15 15:45:33.011   874  1706 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
07-15 15:45:33.019   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
